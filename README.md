# Klasifikasi Kemenangan pada Game Mobile Legends
![Mobile Legends Bang-Bang](Video%20Game.jpg)

## About Notebook 
Proyek ini bertujuan untuk mengklasifikasikan kemenangan berdasarkan Draft Pick Hero pada game Mobile Legends Bang-Bang menggunakan algoritma Decision Tree Classifier dan Gaussian Naive Bayes. Decision Tree Classifier membangun model prediktif dengan membagi dataset menjadi subset yang semakin kecil berdasarkan fitur-fitur tertentu, sementara Gaussian Naive Bayes mengasumsikan bahwa nilai fitur dalam dataset diambil dari distribusi Gaussian.

![Draft Pick](draft%20pick.jpg)

Dua pendekatan ini memiliki kelebihan dan kelemahan masing-masing: 
 * Decision Tree Classifier cenderung lebih mudah dipahami dan dapat menangani data non-linier dengan baik, tetapi cenderung rentan terhadap overfitting jika tidak diatur dengan benar.
 * Gaussian Naive Bayes cenderung efisien dalam kasus dataset yang besar dan bekerja dengan baik dengan dataset yang memiliki fitur-fitur independen, namun asumsi bahwa fitur-fitur tersebut saling independen dapat menjadi tidak realistis dalam beberapa kasus.
   
  Dengan membandingkan kinerja kedua algoritma ini dalam mengklasifikasikan kemenangan pada game Mobile Legends Bang-Bang, diharapkan dapat memilih pendekatan yang paling sesuai dengan karakteristik dataset dan tujuan analisis yang ingin dicapai.

## About Dataset
Dataset Mobile Legends Professional League.xlsx dmemiliki 3 sheet yaitu:
1. Heroes
2. Match
3. Team
