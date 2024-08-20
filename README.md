# Identify-Lung-Cancer-from-CT-Scan-images

Identify Lung Cancer from CT-Scan images using Identity Block in ResNets like architecture. 


**Residual Block / Identity block**

The idea is that instead of letting layers learn the underlying mapping, let the network fit the residual mapping. So, instead of say H(x), initial mapping, let the network fit, F(x) := H(x)-x which gives H(x) := F(x) + x

The approach is to add a shortcut or a skip connection that allows information to flow, well just say, more easily from one layer to the next’s next layer, i.e., you bypass data along with normal CNN flow from one layer to the next layer after the immediate next.

The identity block is the standard block used in ResNets and corresponds to the case where the input activation has the same dimension as the output activation.

![image](https://github.com/user-attachments/assets/017dc66a-5db7-4420-b22c-eb590eb9810f)


### Used Dataset
Dataset used from kaggle. Data contain three chest cancer types, which are Adenocarcinoma, Large cell carcinoma, and Squamous cell carcinoma, and one folder for the normal cell.

link of the dataset https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images 

