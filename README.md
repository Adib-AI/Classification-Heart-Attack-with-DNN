# Classification-Heart-Attack-with-DNN
Dataset yang digunakan berasal University of Kurdistan Hewler yang diambil di Zheen hospital, Iraq. Terdapat sekitar 9 feature yaitu 
1. age
2. gender
3. heart rate
4. systolic blood pressure
5. diastolic blood pressure
6. blood sugar (Glukosa)
7. ck-mb (Creatine Kinase MB)
8. troponin (Protein yang ditemukan pada otot jantung)
9. Result (Negatif rentan terkena serangan jantung dan Positif rentan terkena serangan jantung)\
Note: Data bersifat binary class

Tahapan akan melewati 
1. Data Understanding yang mengeksplorasi persebaran data dengan rumus Rice Rule
2. Data Preparation yang menggunakan
  a. Cek dan Remove Outliers Z-Score with MAD
  b. Transformasi pada Blood Sugar
  c. Normalisasi Min Max
  d. LabelEncoder
  e. Split Data
3. Modeling menggunakan DNN dengan arsitektur kedalaman 4 Hidden Layer
4. Evaluation dengan parameter akurasi, presisi, recall, f1 score berdasarkan hasil confusion matrix

Komponen library yang digunakan
1. pandas    : 2.0.0
2. seaborn   : 0.13.2
3. numpy     : 1.24.0
4. matplotlib: 3.7.1
5. tensorflow: 2.10.1
