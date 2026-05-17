# A-clinical-decision-support-system-of-cervical-intraepithelial-neoplasia-clinic-diagnosis

Cervical intraepithelial neoplasia (CIN) is the second most common malignancy in women all over the world as the abnormal growth of cells on the surface of the cervix could induce cervical cancer. The clinical reference
standard based on colposcopically directed biopsies divided them into various grades such as Grade1, Grade2, and Grade3. The Grade1 CIN is called a Low-grade squamous intraepithelial lesion(LSIL) and is usually considered
benign or non-cancer. Grade2 and Grade3 belong to a High-grade squamous intraepithelial lesion(HSIL) and is considered to be cancer.

As part of this project our team builds a predictive model which is able to predict if a patient has a cancer or not based upon the various attributes and their values which would save a lot of mundane human eﬀorts.The given
data set is labeled making it suitable for supervised learning.

## Dataset

The dataset consists of real samples of the tests conducted on the patients. The dataset has a sparsity of 92%. 
This dataset used for training mainly concentrates on medical(clinical) tests such as HPV results and TCT results rather than behavioral features like smoking, sexual partners, marital status e.t.c. 
There are 4923 samples without CIN, 418 samples with CIN1, 546 samples with CIN2, and 86 samples with CIN 3 to be precise.
 
Total subjects - 6063
Cancer subjects - 632 = CIN(2) + CIN(3)
Non-Cancer subjects - 5013 = CIN(0) + CIN(1)

### Features 

Age - 24 years to 84 years
HPV - Human Papilomma Virus test ( HPV DNA type:16,18,31,33,35,39,45,51,52,56,58,59,68 )
TCT - Thinrep Cytologic Test ( 0: Normal, 1: ASCUS, 2: ASC-H, 3: LSIL, 4: HSIL+ )
Virus Types - 16,18,31,33,52,58
Viral Load - v16,18,31,33,52,58 

### Models Used

1. Wide and Deep Model
2. Multi Layer Perceptron
3. Random Forest
4. Support Vector Machines

