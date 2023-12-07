# CNNPneu

In this notebook we employ a Convolution Neural Network approach to examine chest radiographs of patients and predict the presence of pneumonia. The original dataset "Chest X-Ray Images" is taken from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).
<div>
<img src="https://github.com/klrmnn95/CNNPneu/blob/main/images/lungs.jpg"width="500" class="centerImage"/>
</div>

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

The following steps would be taken towards the dataset analysis:
1. Load the data
2. Visualization
3. Data preparation
4. Train the model
5. Analysis of the predictions
