# keras_like_model
this program enables torch model  keras-like train and outputs.

※This program is work in progres and has many point to be improved.

## Description
This program is designed to show a Keras-like progress-ver.
And you can use fit func.

## Demo(quick start)
Only replace train part to below.
```python
import time
k_model = keras_model(model)
k_model.fit(epoch=10,dataloader=trainloader,criterion=criterion,optimizer=optimizer)
```
It has additional parameter shceduler,validation data,accuracy func.

This is demo screen.
![Screenshot from 2020-03-22 03-07-03](https://user-images.githubusercontent.com/22934822/77241280-1c2c0400-6c33-11ea-89fc-be0cd9ce9ea9.png)

## Requirement
+ Python3
+ torch
+ torchvision
+ 1GPU train(in the future, plan to use multi-gpu and cpu)

