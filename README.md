# 📌 Deskripsi

Proyek ini bertujuan untuk menganalisis sentimen pengguna terhadap aplikasi Bareksa dengan memanfaatkan data ulasan dari Google Play Store. Metode yang digunakan dalam penelitian ini meliputi:

    💾 Scraping Data: Mengambil data ulasan aplikasi Bareksa dari Google Play Store.

    🔧 Preprocessing Data: Melakukan beberapa langkah preprocessing seperti:

        ✂️ Menghapus karakter khusus dan angka

        🔡 Mengubah teks menjadi huruf kecil

        ✂️ Tokenisasi dan stopword removal

        🔄 Stemming atau lemmatization

    🏷️ Labelling dengan VADER Lexicon: Menggunakan pendekatan Lexicon-Based dengan VADER untuk memberikan label sentimen awal terhadap teks ulasan.

    🔢 Chi-Square Feature Selection: Memilih fitur yang paling berpengaruh dalam meningkatkan performa model.

    🤖 Support Vector Machine (SVM): Digunakan sebagai model klasifikasi utama.

    📈 SMOTE (Synthetic Minority Over-sampling Technique): Digunakan untuk mengatasi ketidakseimbangan kelas dalam data.

## 📊 Hasil Eksperimen
Pada penelitian ini diharapkan akurasi yang cukup baik dalam penggunaan metode Support Vector Machine.


## 🔧 Teknologi yang Digunakan
```bash
Python (pandas, numpy, scikit-learn, imbalanced-learn)
Natural Language Processing (NLP)
Google Colab / Jupyter Notebook
📂 Struktur Repositori
bash
Copy
Edit
📦 Sentiment-Analysis-Bareksa
 ┣ 📂 data               # Dataset ulasan aplikasi Bareksa
 ┣ 📂 notebooks          # Jupyter Notebook untuk analisis
 ┣ 📂 models             # Model yang telah dilatih
 ┣ 📄 README.md          # Dokumentasi proyek
 ┗ 📄 requirements.txt   # Library yang digunakan

```
# 🚀 Cara Menjalankan
Clone repositori ini:
```bash
git clone https://github.com/username/Sentiment-Analysis-Bareksa.git
cd Sentiment-Analysis-
```
Install dependensi:
```bash
Copy
Edit
pip install -r requirements.txt
```
Jalankan notebook analisis di Jupyter Notebook atau Google Colab.

# 📢 Kontribusi
Jika ingin berkontribusi atau memiliki saran, silakan buat issue atau pull request di repositori ini.