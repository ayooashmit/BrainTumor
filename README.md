# Brain Tumor Classification: Project Overview 
- Created a Convolutional Neural Network model to classify if a patient has Brain Tumor or not from Brain MRI scans. 
- Downloaded the MRI dataset on Kaggle.
- Made use of Transfer learning to compensate for the dataset size and Data Augmentation to allow the model to generalise better. 
- ImageNet dataset and VGG-16 architecture was utilized for transfer learning via fine-tuning.
- Six Statistical metrics was used to evaluate model performance.
- Metrics: Accuracy, Precision, Recall, F1-score, Macro-average and Weighted-average. 
- Built an application to automate the process of Brain Tumor classification. 

## Resources
**Python Version:** 3.8 <br>
**Packages:** Tensorflow, Keras, Sklearn, imutils, matplotlib, numpy, argparse, pickle, cv2, os, streamlit <br>
**Dataset:** https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection <br>

## Brain MRI scan (Gray Image)
![Image](https://github.com/user-attachments/assets/96041b8d-e692-4a1e-9cff-381a53f5791f) <br>
Source: [Wikipedia](https://en.wikipedia.org/wiki/Brain_tumor)

## Statistical Evaluation 
<img width="446" height="146" alt="Image" src="https://github.com/user-attachments/assets/a4ab6dc3-9cbe-43c5-94a7-d9796e79206c" />

## Filter and Feature (Hot Colormap)
- A hot colormap was applied, a sequential black-red-yellow-white, to emulate blackbody radiation from an object at increasing temperatures
- This was to illustrate prominent features in brain MRI scans learned by the Neural Network
<img width="575" height="180" alt="Image" src="https://github.com/user-attachments/assets/b2201594-ee85-4e3a-99f7-be616846ebec" />


## Classifications from test samples
- The images below got presevered to be used to test the model. <br>
- Outputs from the Classification.py <br> 
<img width="400" height="429" alt="Image" src="https://github.com/user-attachments/assets/4da35ba6-2025-48b6-9389-fcaa81277ae2" />
<img width="393" height="535" alt="Image" src="https://github.com/user-attachments/assets/06431cf1-fe5a-467e-84cd-4acfb14bf930" />
## Application to Classify Brain Tumor (screenshot)
<img width="738" height="454" alt="Image" src="https://github.com/user-attachments/assets/e967b2b3-f73d-4501-8538-302e19161a63" />

