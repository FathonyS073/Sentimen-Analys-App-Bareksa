# 🧪 Skenario Pengujian 1: Support Vector Machine (SVM) dengan K-Fold Cross Validation
Pada skenario pertama, dilakukan pengujian model Support Vector Machine (SVM) dengan menggunakan teknik K-Fold Cross Validation untuk mengevaluasi performa model. Parameter K yang digunakan dalam pengujian ini adalah 5, 7, dan 9.

# ⚙️ Metodologi Pengujian
Preprocessing Data: Data ulasan telah melalui tahap pembersihan, tokenisasi, dan transformasi fitur menggunakan TF-IDF.
Model Klasifikasi: Model SVM digunakan untuk melakukan klasifikasi sentimen positif, netral, dan negatif.
K-Fold Cross Validation:
K = 5: Data dibagi menjadi 5 lipatan untuk validasi silang.

K = 7: Data dibagi menjadi 7 lipatan.

K = 9: Data dibagi menjadi 9 lipatan.

Evaluasi Model: Kinerja model diukur berdasarkan metrik akurasi, presisi, recall, dan f1-score.

# 📊 Hasil Pengujian

Penggunaan K-Fold Cross Validation dengan berbagai nilai K bertujuan untuk mengamati stabilitas dan generalisasi model terhadap data. Hasil eksperimen menunjukkan bahwa nilai K yang lebih besar cenderung meningkatkan stabilitas performa model, meskipun bisa berdampak pada waktu komputasi yang lebih lama.