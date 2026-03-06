## ANALISIS CLUSTERING INDUSTRI KEHUTANAN MENGGUNAKAN K-MEANS

Repositori ini mengandungi implementasi analisis clustering (pengelompokan) menggunakan algoritma K-Means untuk mengkategorikan data dalam industri kehutanan. Analisis ini bertujuan untuk mengenal pasti corak atau kelompok tertentu berdasarkan pemboleh ubah yang tersedia dalam dataset.

### 📊 RINGKASAN PROJEK
Projek ini menggunakan pendekatan unsupervised learning untuk mengelompokkan data industri kehutanan. Dengan teknik clustering, kita dapat memahami struktur data dengan lebih mendalam, seperti membezakan wilayah atau sektor yang mempunyai ciri-ciri pengeluaran atau nilai ekonomi yang serupa.

### 📁 DESKRIPSI FILE JUPYTER
Fail **Analisis_Clustering_K_Means.ipynb** mengandungi langkah-langkah kerja seperti berikut:

#### 1. **Persiapan Data:**
   - Mengimport library utama dan memuatkan dataset industri kehutanan.

#### 2. **Eksplorasi Data (EDA):**
   - Analisis awal untuk memahami taburan data melalui statistik deskriptif dan visualisasi.

#### 3. **Preprocessing:**
   - Pembersihan data (penanganan missing values).
   - Transformasi data agar sesuai untuk proses clustering.
   - Normalisasi atau penskalaan fitur (Scaling) untuk memastikan semua pemboleh ubah mempunyai impak yang seimbang pada algoritma.

#### 4. **Penentuan Jumlah Cluster:**
   - Menggunakan kaedah seperti Elbow Method atau Silhouette Score untuk menentukan bilangan kelompok ($k$) yang paling optimum.

#### 5. **Implementasi K-Means:**
   - Melakukan proses pengelompokan data ke dalam cluster yang telah ditetapkan.

#### 6. **Visualisasi & Interpretasi:**
   - Menampilkan hasil cluster dalam bentuk carta (seperti scatter plot) dan memberikan rumusan terhadap ciri-ciri setiap kelompok yang terbentuk.

### 🛠️ TEKNOLOGI & LIBRARY
Projek ini dibangunkan menggunakan bahasa Python 3 dengan library berikut:
- **pandas & numpy** - Untuk manipulasi dan pengurusan data.
- **matplotlib & seaborn** - Untuk visualisasi data dan hasil cluster.
- **scikit-learn** - Untuk implementasi algoritma K-Means dan metrik penilaian.

### 🚀 CARA MENJALANKAN
1. Muat turun fail `.ipynb` dalam repositori ini.
2. Buka fail tersebut menggunakan Jupyter Notebook, JupyterLab, atau Google Colab.
3. Pastikan anda telah memasang library yang diperlukan:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
