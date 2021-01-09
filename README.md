# Hackerearth_HolidaySeason
Holiday Season deep learning challenge by HackerEarth
https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-holidays/machine-learning/holiday-season-11-2c924626/

## TOOLS USED
Python 3.7.9, Microsoft Lobe


## APPROACH
STEP 1. Using Python, the training date was segregated into their respective 'class' folders as indicated in the train.csv file. This operation took ~18 secs.
STEP 2. The individual class folders, along-with training data, were uploaded into Microsoft Lobe and manually annotated. This operation took ~10 mins.
STEP 3. Lobe automatically trained a model using the ResNet-50 V2 and Transfer Learning with pretrained weights from the ImageNet dataset. The first iteration of the model took 20 mins and was ~84% accurate. Lobe did further optimization to achieve 95% accuracy on the training data which took ~12 hrs. All of this was done automatically in Lobe without any coding.
STEP 4. Using Python, the test data was passed recursively to the model in order to get a prediction, which was then written into  a CSV file. This operation took ~12 mins.
