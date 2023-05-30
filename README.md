
#  Personal Professional Project : Image classification with transfer learning
This projet was made by [Yassine Dhaouadi](https://github.com/YassDH) , [Adam Fendri](https://github.com/adam-fendri)  and [Mohamed Aziz Klai](https://github.com/AzizKlai) , focuses on classifying car images according to their brands/models by relying on both Transfer Learning and the The Stanford Cars dataset which has 196 car classes in it . And to do so, we experimented with diffrent models and techniques that are explained down below :
##  ResNet 50 with IMAGENET1K_V2 weights :
This is basically the version that gave us the best accuracy so we chose it as our **Final Version**.
Thanks to it's 50 pretrained layers on the **IMAGENET V2** DataSet this version of the model gave us **83%** accruacy.
To see the code and results [Click here](https://github.com/YassDH/ProjetPPP/blob/main/FinalVersion%20with%20ResNet%2050.ipynb)
##  ResNet 18 with DEFAULT weights :
Setting the weights to **DEFAULT** is equivalent to setting them to **IMAGENET1K_V1**.
Even though it was trained on the **IMAGENET V1** DataSet and has only 18 layers, the performance was not bad and gave us and accruacy of **78%** . This was our baseline . 
To see the code and results [Click here](https://github.com/AzizKlai/transferlearning_resnet18/blob/main/resnet18.ipynb)
##  EfficientNetB1 with DEFAULT weights :
Setting the weights to **DEFAULT** is equivalent to setting them to **IMAGENET1K_V1**.
Even though it was trained on the **IMAGENET V1** DataSet and has 26 layers, the performance was worse than our baseline and gave us and accruacy of **77%** .
To see the code and results [Click here](https://github.com/adam-fendri/TransferLearning-EfficientNetB1/blob/main/efficientnet-b1.ipynb)
##  ResNet 50 with Data Augmentation :
Setting the weights to **IMAGENET1K_V2**.
Even though it was trained on the **IMAGENET V2** DataSet and has 50 layers, after applying data augmentation,  the performance took a small hit and gave us and accruacy of **77%** .
To see the code and results [Click here](https://github.com/YassDH/ProjetPPP/blob/main/ResNet%2050%20with%20data%20augmentation.ipynb)
##  EfficientNetB1 with Data Augmentation :
Setting the weights to **DEFAULT** is equivalent to setting them to **IMAGENET1K_V1**.
Even though it was trained on the **IMAGENET V1** DataSet and 26 layers, after applying data augmentation, we had a pretty poor performance and got just **54%** of accruacy .
To see the code and results [Click here](https://github.com/YassDH/ProjetPPP/blob/main/efficientnet_b1%20Version%20with%20data%20augmentation.ipynb)
