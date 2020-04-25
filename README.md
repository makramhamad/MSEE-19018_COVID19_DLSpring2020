# MSEE-19018_COVID19_DLSpring2020


** Accuracy and confusion matrices for VGG16 model.**
This is Confusion matix and accuracy on test data for vgg16 model when all of its layers are set learn able. 
![vggfull testC](https://user-images.githubusercontent.com/64316625/80282159-bbc23380-86c4-11ea-8b6c-6efb01362be2.png)

This is Confusion matix and accuracy on train data for vgg16 model when all of its layers are set learn able.
![vggfull trainC](https://user-images.githubusercontent.com/64316625/80282478-a51cdc00-86c6-11ea-948f-0e5075f32deb.png)

This is Confusion matix and accuracy on validation data for vgg16 model when all of its layers are set learn able.

![vgg_entire](https://user-images.githubusercontent.com/64316625/80287934-e2787c80-874d-11ea-86c3-7d0178192ad7.png)


This is Confusion matix and accuracy on test data for vgg16 model when all of its first 16 layers are set as not learn able but rest of the model is learn able. 
![vgg_16 conf test](https://user-images.githubusercontent.com/64316625/80282504-bbc33300-86c6-11ea-8761-59b3e1c179f5.png)
This is Confusion matix and accuracy on train data for vgg16 model when all of its first 16 layers are set as not learn able but rest of the model is learn able.
![vgg_16 conf train](https://user-images.githubusercontent.com/64316625/80282589-0b096380-86c7-11ea-81a0-1b1dac46da2e.png)
This accuracy for vgg16 model when all of its layers were freeze except the fully connected layers. On test data, train data and validation data respectively.
![vgg_1 conf test](https://user-images.githubusercontent.com/64316625/80287910-b3faa180-874d-11ea-8eb9-2f16d4f48d43.png)

![vgg_1 conf train](https://user-images.githubusercontent.com/64316625/80287916-b9f08280-874d-11ea-923a-8dd775d3139f.png)

![vgg_1 conf validation](https://user-images.githubusercontent.com/64316625/80287920-c1b02700-874d-11ea-9c54-60f3f9c31dc3.png)


**This Accuracy and Confusion Matrices for Resnet18**
This is confusion matrix and accuracy when no layers were freeze. On test data, train data and validation data respectively.
![resnetf conf test](https://user-images.githubusercontent.com/64316625/80287788-be686b80-874c-11ea-920e-9e72cb3dcf24.png)

![resnetf conf train](https://user-images.githubusercontent.com/64316625/80287791-c6281000-874c-11ea-9ab1-f47a81df1f16.png)
![resnetf conf validation](https://user-images.githubusercontent.com/64316625/80287795-cc1df100-874c-11ea-90ca-de6996f6ada4.png)
 
This is confusion matrix and accuracy when first 2 top layers were freeze. On test data, train data and validation data respectively. 

![resnet2L conf test](https://user-images.githubusercontent.com/64316625/80287820-04253400-874d-11ea-830c-fae1c7f5c44d.png)

![resnet2L conf train](https://user-images.githubusercontent.com/64316625/80287821-08515180-874d-11ea-9442-e56d1c2b68e2.png)
![resnet2L conf validation](https://user-images.githubusercontent.com/64316625/80287823-0be4d880-874d-11ea-9346-9f48353fa750.png)

This is confusion matrix and accuracy when all layers were freeze except fully connected layers. On test data, train data and validation data respectively. 

![resnet1 conf test](https://user-images.githubusercontent.com/64316625/80287862-5b2b0900-874d-11ea-8e3e-5f4d02f2f114.png)

![resnet1 conf train](https://user-images.githubusercontent.com/64316625/80287868-60885380-874d-11ea-8039-d98bdf200f13.png)
![resnet1 conf validation](https://user-images.githubusercontent.com/64316625/80287869-64b47100-874d-11ea-8f35-7d5821aa6423.png)


