# phishing-email-checking
this project checks if the given email is a phishing email based on its train test

English
This project implements a machine learning pipeline to classify emails as either "Safe" or "Phishing". The primary focus of this project is not only model training but also robust data cleaning and preprocessing of unstructured text data. The dataset, sourced from Kaggle, contained significant parsing errors (delimiter issues and bad lines) which were handled programmatically using Pandas.

Key Features:

Robust Data Loading: Implementation of error handling strategies using on_bad_lines and specific engine parameters in Pandas to manage malformed CSV data.

Text Preprocessing: Vectorization of raw email content using TF-IDF (Term Frequency-Inverse Document Frequency).

Modeling: Utilization of Logistic Regression for binary classification.

Evaluation: Performance analysis using Confusion Matrix and Classification Reports.

Technologies Used:

Python 3.x

Pandas & NumPy

Scikit-learn

Seaborn & Matplotlib

How to Run:

Ensure the dataset Phishing_Email.csv is in the same directory.

Run the script to load data, clean it, train the model, and view evaluation metrics.

Türkçe
Bu proje, e-postaları "Güvenli" veya "Oltalama" (Phishing) olarak sınıflandıran bir makine öğrenmesi hattı (pipeline) uygular. Projenin birincil odağı sadece model eğitimi değil, aynı zamanda yapılandırılmamış metin verilerinin temizlenmesi ve ön işlenmesidir. Kaggle'dan alınan veri seti, Pandas kullanılarak programatik olarak çözülen önemli ayrıştırma hataları (ayırıcı sorunları ve bozuk satırlar) içermekteydi.

Temel Özellikler:

Güçlü Veri Yükleme: Bozuk CSV verilerini yönetmek için Pandas'ta on_bad_lines ve özel motor parametreleri kullanılarak hata işleme stratejilerinin uygulanması.

Metin Ön İşleme: Ham e-posta içeriğinin TF-IDF kullanılarak vektörleştirilmesi.

Modelleme: İkili sınıflandırma için Lojistik Regresyon kullanımı.

Değerlendirme: Karışıklık Matrisi (Confusion Matrix) ve Sınıflandırma Raporları ile performans analizi.

Kullanılan Teknolojiler:

Python 3.x

Pandas & NumPy

Scikit-learn

Seaborn & Matplotlib
