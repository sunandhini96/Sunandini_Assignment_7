# Sunandini_Assignment_7

Cifar- 10 dataset:
After applying data transformations:

![image](https://user-images.githubusercontent.com/63030539/218205519-2b536ac4-54f2-4bfa-a9f4-e382a05f3b85.png)

Model summary :

           Conv2d-1           [-1, 64, 32, 32]           1,728
       BatchNorm2d-2           [-1, 64, 32, 32]             128
            Conv2d-3           [-1, 64, 32, 32]          36,864
       BatchNorm2d-4           [-1, 64, 32, 32]             128
            Conv2d-5           [-1, 64, 32, 32]          36,864
       BatchNorm2d-6           [-1, 64, 32, 32]             128
        BasicBlock-7           [-1, 64, 32, 32]               0
            Conv2d-8           [-1, 64, 32, 32]          36,864
       BatchNorm2d-9           [-1, 64, 32, 32]             128
           Conv2d-10           [-1, 64, 32, 32]          36,864
      BatchNorm2d-11           [-1, 64, 32, 32]             128
       BasicBlock-12           [-1, 64, 32, 32]               0
           Conv2d-13          [-1, 128, 16, 16]          73,728
      BatchNorm2d-14          [-1, 128, 16, 16]             256
           Conv2d-15          [-1, 128, 16, 16]         147,456
      BatchNorm2d-16          [-1, 128, 16, 16]             256
           Conv2d-17          [-1, 128, 16, 16]           8,192
      BatchNorm2d-18          [-1, 128, 16, 16]             256
       BasicBlock-19          [-1, 128, 16, 16]               0
           Conv2d-20          [-1, 128, 16, 16]         147,456
      BatchNorm2d-21          [-1, 128, 16, 16]             256
           Conv2d-22          [-1, 128, 16, 16]         147,456
      BatchNorm2d-23          [-1, 128, 16, 16]             256
       BasicBlock-24          [-1, 128, 16, 16]               0
           Conv2d-25            [-1, 256, 8, 8]         294,912
      BatchNorm2d-26            [-1, 256, 8, 8]             512
           Conv2d-27            [-1, 256, 8, 8]         589,824
      BatchNorm2d-28            [-1, 256, 8, 8]             512
           Conv2d-29            [-1, 256, 8, 8]          32,768
      BatchNorm2d-30            [-1, 256, 8, 8]             512
       BasicBlock-31            [-1, 256, 8, 8]               0
           Conv2d-32            [-1, 256, 8, 8]         589,824
      BatchNorm2d-33            [-1, 256, 8, 8]             512
           Conv2d-34            [-1, 256, 8, 8]         589,824
      BatchNorm2d-35            [-1, 256, 8, 8]             512
       BasicBlock-36            [-1, 256, 8, 8]               0
           Conv2d-37            [-1, 512, 4, 4]       1,179,648
      BatchNorm2d-38            [-1, 512, 4, 4]           1,024
           Conv2d-39            [-1, 512, 4, 4]       2,359,296
      BatchNorm2d-40            [-1, 512, 4, 4]           1,024
           Conv2d-41            [-1, 512, 4, 4]         131,072
      BatchNorm2d-42            [-1, 512, 4, 4]           1,024
       BasicBlock-43            [-1, 512, 4, 4]               0
           Conv2d-44            [-1, 512, 4, 4]       2,359,296
      BatchNorm2d-45            [-1, 512, 4, 4]           1,024
           Conv2d-46            [-1, 512, 4, 4]       2,359,296
      BatchNorm2d-47            [-1, 512, 4, 4]           1,024
       BasicBlock-48            [-1, 512, 4, 4]               0
           Linear-49                   [-1, 10]           5,130
================================================================
Total params: 11,173,962
Trainable params: 11,173,962
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 11.25
Params size (MB): 42.63
Estimated Total Size (MB): 53.89

Output training logs:
EPOCH: 0
100%|██████████| 834/834 [00:29<00:00, 28.10it/s]

Train set: Average loss: 0.0250, Accuracy: 22484/50000 (44.97%)


Test set: Average loss: 0.0185, Accuracy: 6005/10000 (60.05%)

EPOCH: 1
100%|██████████| 834/834 [00:29<00:00, 28.13it/s]

Train set: Average loss: 0.0181, Accuracy: 30485/50000 (60.97%)


Test set: Average loss: 0.0156, Accuracy: 6675/10000 (66.75%)

EPOCH: 2
100%|██████████| 834/834 [00:29<00:00, 28.16it/s]

Train set: Average loss: 0.0149, Accuracy: 34077/50000 (68.15%)


Test set: Average loss: 0.0137, Accuracy: 7074/10000 (70.74%)

EPOCH: 3
100%|██████████| 834/834 [00:29<00:00, 28.07it/s]

Train set: Average loss: 0.0129, Accuracy: 36312/50000 (72.62%)


Test set: Average loss: 0.0119, Accuracy: 7528/10000 (75.28%)

EPOCH: 4
100%|██████████| 834/834 [00:29<00:00, 28.39it/s]

Train set: Average loss: 0.0115, Accuracy: 37965/50000 (75.93%)


Test set: Average loss: 0.0110, Accuracy: 7717/10000 (77.17%)

EPOCH: 5
100%|██████████| 834/834 [00:29<00:00, 28.24it/s]

Train set: Average loss: 0.0104, Accuracy: 39055/50000 (78.11%)


Test set: Average loss: 0.0104, Accuracy: 7846/10000 (78.46%)

EPOCH: 6
100%|██████████| 834/834 [00:29<00:00, 28.33it/s]

Train set: Average loss: 0.0083, Accuracy: 41445/50000 (82.89%)


Test set: Average loss: 0.0077, Accuracy: 8392/10000 (83.92%)

EPOCH: 7
100%|██████████| 834/834 [00:29<00:00, 28.35it/s]

Train set: Average loss: 0.0078, Accuracy: 41937/50000 (83.87%)


Test set: Average loss: 0.0075, Accuracy: 8441/10000 (84.41%)

EPOCH: 8
100%|██████████| 834/834 [00:29<00:00, 28.16it/s]

Train set: Average loss: 0.0075, Accuracy: 42256/50000 (84.51%)


Test set: Average loss: 0.0074, Accuracy: 8451/10000 (84.51%)

EPOCH: 9
100%|██████████| 834/834 [00:29<00:00, 28.18it/s]

Train set: Average loss: 0.0074, Accuracy: 42319/50000 (84.64%)


Test set: Average loss: 0.0074, Accuracy: 8485/10000 (84.85%)

EPOCH: 10
100%|██████████| 834/834 [00:29<00:00, 28.01it/s]

Train set: Average loss: 0.0072, Accuracy: 42613/50000 (85.23%)


Test set: Average loss: 0.0074, Accuracy: 8498/10000 (84.98%)

EPOCH: 11
100%|██████████| 834/834 [00:29<00:00, 28.18it/s]

Train set: Average loss: 0.0070, Accuracy: 42741/50000 (85.48%)


Test set: Average loss: 0.0072, Accuracy: 8489/10000 (84.89%)

EPOCH: 12
100%|██████████| 834/834 [00:29<00:00, 28.08it/s]

Train set: Average loss: 0.0067, Accuracy: 43098/50000 (86.20%)


Test set: Average loss: 0.0071, Accuracy: 8516/10000 (85.16%)

EPOCH: 13
100%|██████████| 834/834 [00:29<00:00, 27.94it/s]

Train set: Average loss: 0.0068, Accuracy: 43014/50000 (86.03%)


Test set: Average loss: 0.0072, Accuracy: 8517/10000 (85.17%)

EPOCH: 14
100%|██████████| 834/834 [00:29<00:00, 28.07it/s]

Train set: Average loss: 0.0067, Accuracy: 43112/50000 (86.22%)


Test set: Average loss: 0.0071, Accuracy: 8529/10000 (85.29%)

EPOCH: 15
100%|██████████| 834/834 [00:29<00:00, 28.29it/s]

Train set: Average loss: 0.0066, Accuracy: 43203/50000 (86.41%)


Test set: Average loss: 0.0072, Accuracy: 8514/10000 (85.14%)

EPOCH: 16
100%|██████████| 834/834 [00:29<00:00, 28.36it/s]

Train set: Average loss: 0.0066, Accuracy: 43286/50000 (86.57%)


Test set: Average loss: 0.0071, Accuracy: 8522/10000 (85.22%)

EPOCH: 17
100%|██████████| 834/834 [00:29<00:00, 28.32it/s]

Train set: Average loss: 0.0065, Accuracy: 43183/50000 (86.37%)


Test set: Average loss: 0.0071, Accuracy: 8520/10000 (85.20%)

EPOCH: 18
100%|██████████| 834/834 [00:29<00:00, 28.15it/s]

Train set: Average loss: 0.0066, Accuracy: 43204/50000 (86.41%)


Test set: Average loss: 0.0071, Accuracy: 8520/10000 (85.20%)

EPOCH: 19
100%|██████████| 834/834 [00:29<00:00, 28.16it/s]

Train set: Average loss: 0.0066, Accuracy: 43224/50000 (86.45%)


Test set: Average loss: 0.0071, Accuracy: 8536/10000 (85.36%)

Training and testing accuracies and loss graphs:

![image](https://user-images.githubusercontent.com/63030539/218205953-e6150d35-ef12-45ee-82c2-cd67414651d7.png)

Average test loss and test accuracy:

Test Loss: 0.424331

Test Accuracy of plane: 89% (600/670)
Test Accuracy of   car: 95% (676/705)
Test Accuracy of  bird: 76% (501/653)
Test Accuracy of   cat: 69% (458/663)
Test Accuracy of  deer: 83% (562/677)
Test Accuracy of   dog: 78% (529/672)
Test Accuracy of  frog: 89% (594/664)
Test Accuracy of horse: 89% (602/674)
Test Accuracy of  ship: 93% (607/652)
Test Accuracy of truck: 89% (581/650)

Test Accuracy (Overall): 85% (5710/6680)

Misclassification of images:

![image](https://user-images.githubusercontent.com/63030539/218206213-81738cdd-be03-4081-94ac-9650691188a2.png)

red color represents misclassification of images and green color represents correct classification of images.

