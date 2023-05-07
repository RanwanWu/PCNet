# Pyramid Contract-based Network for RGB-T Salient Object Detection
![image](figs/PCNet.png)
   Figure.1 The overall architecture of the proposed PCNet model.  
   The paper can be downloaded from [here], which is accepted in Multimedia Tools and Appllications 🎆.
# 1.Requirements
Python v3.6, Pytorch 0.4.0+, Cuda 10.0, TensorboardX 2.0, opencv-python

# 2.Data Preparation
Download the dataset from [here](https://pan.baidu.com/s/1sL3LMtTnr4984-MWV5uXeA)[code:NEPU], which includes train, test in train and test dataset. Then put them under the following directory: 

    -Dataset\   
       -train\  
       -test\ 
           -VT821\
           -VT1000\
           -VT5000_test\
       -test_in_train\
           
# 3.Training/Testing & Evaluating
* **Training the PCNet**  

Please download the released code and then:  
  
    run python Train.py  

* **Testing the PCNet**  

Please download the trained weights from [here](https://pan.baidu.com/s/1oo86hczZ_hB2uP9-u5L8HA) and then:  

    run python Test.py  

Then the test maps will be saved to './Salmaps/'

* **Evaluate the result maps**  

You can evaluate the result maps using the tool from [here](https://pan.baidu.com/s/1gmckcn7FZuDP2ufiTM6qow)[code:NEPU], thanks for [Dengpin Fan](https://github.com/DengPingFan).

# 4.Results
* **Qualitative comparison**  

![image](figs/vision_results.png)  
Figure.2 Qualitative comparison of our proposed method with some SOTA methods.  

* **Quantitative comparison** 

![image](figs/qulities_results.png)  
Table.1 Quantitative comparison with some SOTA models on there public RGB-T SOD benchmark datasets. 

* **Salmaps**   
The results of three RGB-T SOD benchmark datasets can be download from [here](https://pan.baidu.com/s/1h4SDlWui45QgcOoiHS7A5A) [code:NEPU]


# 5.Contact  
If you have any questions, feel free to contact us via wuranwan2020@sina.com (Ranwan Wu). 









