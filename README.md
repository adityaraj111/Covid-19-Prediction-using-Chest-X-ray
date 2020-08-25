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




