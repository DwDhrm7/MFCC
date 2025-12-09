# 🎵 MFCC Feature Extraction Pipeline  
Proyek ini berisi workflow lengkap untuk melakukan ekstraksi fitur audio menggunakan **MFCC (Mel-Frequency Cepstral Coefficients)** dari file MP3. Pipeline ini dirancang untuk kebutuhan machine learning, seperti klasifikasi genre, analisis audio, atau tugas audio preprocessing lainnya.

---

## 🚀 Fitur Utama
- Konversi file **MP3 → WAV** secara otomatis  
- Pemotongan audio (trim) untuk mengambil durasi tertentu, misalnya 30 detik pertama  
- Melakukan **FFT (Fast Fourier Transform)**  
- Ekstraksi **MFCC** dengan jumlah koefisien fleksibel  
- Menyimpan hasil fitur menjadi **CSV** untuk keperluan machine learning  
- Dapat dijalankan di **Google Colab** ataupun **Jupyter Notebook**

---

## 📁 Struktur Umum Pipeline
1. **Load MP3 file**  
2. **Convert ke WAV**  
3. **Trim durasi (opsional)**  
4. **FFT processing**  
5. **Ekstraksi MFCC**  
6. **Simpan ke CSV**

---

## 🧪 Teknologi yang Digunakan
- Python 3  
- `librosa` — untuk processing audio & MFCC  
- `numpy` — manipulasi numerik  
- `pydub` — konversi MP3 → WAV  
- `matplotlib` — visualisasi FFT (opsional)  
- `pandas` — untuk menyimpan hasil CSV  

---

## 📌 Cara Menjalankan
### 1. Clone Repository
```bash
git clone https://github.com/DwDhrm7/MFCC.git
cd MFCC


pip install -r requirements.txt
