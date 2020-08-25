# Covid-19-Prediction-using-Chest-X-ray
The COVID-19 pandemic is causing a major outbreak in more than 150 countries around the world, having a severe impact on the health and life of many people globally. 
One of the crucial step in fighting COVID-19 is the ability to detect the infected patients early enough, and put them under special care. Detecting this disease from radiography and radiology images is perhaps one of the fastest way to diagnose the patients. Some of the early studies showed specific abnormalities in the chest radiograms of patients infected with COVID-19. Inspired by earlier works, we study the application of deep learning models to detect COVID-19 patients from their chest radiography images.
We first prepare a dataset of 5,910 Chest X-rays from the publicly available datasets. Images exhibiting COVID-19 disease presence were identified by board-certified radiologist. Transfer learning onradiograms was used to train our convolutional neural networks, including MobileNetV2 and DenseNet-121, to identify COVID-19 disease in the analyzed chest X-ray images.
We also performed an histogram analysis of COVID-19 X-ray images andnormal images. We used image augmentation for the purpose of boosting the performance of the image classifier. We evaluated these models on the validation images, and most of these networks achieved good results.

DETECTION OF COVID-19 THROUGH X-RAY IMAGES:
COVID-19 tests are currently hard to come by — there are simply not enough of them and they cannot be manufactured fast enough, which is causing panic.
When there’s panic, there are nefarious people looking to take advantage of others, namely by selling fake COVID-19 test kits after finding victims on social media platforms and chat applications.
Given that there are limited COVID-19 testing kits, we need to rely on other diagnosis measures.
For the purposes of this tutorial, I thought to explore X-ray images as doctors frequently use X-rays and CT scans to diagnose pneumonia, lung inflammation, abscesses, and/or enlarged lymph nodes.
Since COVID-19 attacks the epithelial cells that line our respiratory tract, we can use X-rays to analyze the health of a patient’s lungs.
And given that nearly all hospitals have X-ray imaging machines, it could be possible to use X-rays to test for COVID-19 without the dedicated test kits.
A drawback is that X-ray analysis requires a radiology expert and takes significant time — which is precious when people are sick around the world. Thereforedeveloping an automated analysis system is required to save medical professionals valuable time.

DATASET:
We have used X-ray images for COVID-19 prediction.Collection Chest X Ray of Healthy vs Pneumonia (Corona) affected patients infected patients along with few other categories such as SARS (Severe Acute Respiratory Syndrome ) ,Streptococcus & ARDS (Acute Respiratory Distress Syndrome).The dataset contains 5286 train images and 624 test images. We have replaced the missing data with “unknown” and performed data augmentation and separated validation for checking validation accuracy.

OBJECTIVE

The prime motive behind this project is to create and develop a machine learning model that could predict Covid-19 using X-ray image with a descent accuracy.
Inspired with the earlier works, in this project we have applied deep learning models on chest radiography images to detect covid-19. We have build a CNN model and also have used the concept of transfer learning and data augmentation. We have used imagenet-121 and mobilenet-v2 model working on imagenet database and analyzed its accuracy. We have also done the prediction of Covid-19 on validation data. We have also used various graphical methods for plotting and analyzing the dataset and thereby developing an efficient model that could serve us with a good accuracy. Apart from this for validation we also created a python function that can predict covid-19 on any random x-ray image.

DISCUSSION & CONCLUSION:
Researchers compiled COVID-19 X-Ray data and made it publiclyavailable for the purpose of development of accurate deep learning model for the detection of COVID-19 accurately.
In this project, we have proposed a deep learningbased model to detect and classify COVID-19 cases from X-ray images. Our model is fully automated with an end-to-end structure without the need for manual feature extraction.The proposed model can be used for the diagnosis of COVID-19 using X-ray radiographs. X-ray radiographs are preferred because they are readily accessible for disease diagnosis. They are widely used in health centers worldwide during the pandemic. The model has the ability to diagnose COVID-19 within seconds.
Patients diagnosed as COVID positive by the model can bedirected to advanced centers for confirmation, followed by treatment without delay. In addition, patients who have beendiagnosed negatively by the model can be prevented fromundergoing PCR tests and occupying health centers unnecessarily.
After going through traditional deep learning methods we attempted Transfer Learning to check if the prediction is decent or not on pretrained model (DenseNet-121 & MobileNetV2). Densenet-121 gave and accuracy of 60% and MobileNetV2 gave and accuracy of 77%, these values of accuracy prove the fact that since these models are not trained on radiography images they are not performing well on an X-ray dataset

The proposed CNN model is fully automated with an end-to-end structure without the need for manual feature extraction. Our developed system is able to perform binary classification task with accuracy of 94.25%.This system can be used in remote places in countries affected by COVID-19 to overcome a shortage of radiologists. Also, such models can be used to diagnose other chest-related diseases including tuberculosis and pneumonia.

A limitation of the is the use of a limited number of COVID-19 X-ray images.In the future, we intend to make our model more robust and accurate by using more such images from local hospitals validate our model. This developed model can be placed in a cloud to provide diagnosis instantly and to help rehabilitate affected patients immediately. This should reduce clinician workload significantly.







