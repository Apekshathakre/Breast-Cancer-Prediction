# Breast-Cancer-Prediction
Breast cancer is a cancer that forms in the cells of the breast. Breast
cancer can occur in women and rarely in men. It requires a medical
diagnosis, through lab tests or imaging.
We have data on patients . The main goal of this notebook is to build a
machine learning model, that will be able to predict whether a patient will
survive breast cancer or not.
#Data understanding
This dataset consists of a group of breast cancer patients, who had
surgery to remove the tumour. The dataset consists of these variables:
1.Patient_ID: unique identifier id of a patient
2.Age: Age of patient (Years)
3.Gender: Male/Female.
4.Protein1, Protein2, Protein3, Protein4: These expression levels are
biomarker for the dectection of breast cancer.
5.Tumour_Stage: I, II, III. It is a form of staging to describe the
extensiveness of breast cancer, based on the size of the tumor and its
spread to the lymph nodes.
6.Histology: Infiltrating Ductal Carcinoma, Infiltrating Lobular
Carcinoma, Mucinous Carcinoma.
7.ER status: Positive/Negative:(Estrogen receptor) the hormone receptor
determines the type of breast cancer to determine treatment.
8.PR status: Positive/Negative:(Progesterone receptor)the hormone
receptor determines the type of breast cancer to determine treatment.
9.HER2 status: Positive/Negative.(human epidermal growth factor
receptor2). This protein promotes the growth of cancer cells .
10.Surgery_type: Lumpectomy, Simple Mastectomy, Modified Radical
Mastectomy, Other surgery type.
11.Date of Surgery: the date the surgery was performed (in DD-MON-YY).
12.Date of Last_Visit: Date of last visit (in DD-MON-YY) to the hospital.
13.Patient_Status: If Alive or Dead
 
By this we can infer whether the patient is alive or dead.
