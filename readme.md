# Deskripsi `generate.py` 
Proyek ini adalah sebuah skrip Python yang menggunakan model CLIP untuk menguji kemampuan model dalam memahami gambar dan mencocokkannya dengan deskripsi teks. Skrip ini memproses gambar dan beberapa deskripsi teks, kemudian memprediksi deskripsi mana yang paling sesuai dengan gambar tersebut.

# Kegunaan
Skrip ini berguna untuk:
- Menguji kemampuan model CLIP dalam memahami dan menginterpretasikan gambar.
- Memberikan contoh sederhana tentang bagaimana menggunakan model CLIP untuk tugas pencocokan gambar dan teks.
- Mengukur waktu yang dibutuhkan untuk melakukan prediksi menggunakan model CLIP.

# Fungsi
Skrip ini memiliki beberapa fungsi utama:
- Memuat model CLIP dan melakukan preprocessing pada gambar dan teks.
- Memproses gambar dan deskripsi teks yang diberikan.
- Menggunakan model CLIP untuk memprediksi deskripsi yang paling sesuai dengan gambar.
- Menampilkan probabilitas prediksi dan waktu yang dibutuhkan untuk melakukan prediksi.

# Bagaimana Menjalankan
Untuk menjalankan skrip ini, ikuti langkah-langkah berikut:

1. **Instalasi Dependensi**
   Pastikan Anda telah menginstal semua dependensi yang diperlukan. Anda dapat menggunakan `pip` untuk menginstal dependensi yang tercantum dalam `requirements.txt`.

   ```bash
   pip install -r requirements.txt
   ```

2. **Menjalankan Skrip**
   Jalankan skrip Python dengan perintah berikut:

   ```bash
   python generate.py
   ```

3. **Hasil Prediksi**
   Skrip akan memproses gambar `CLIP.png` dan mencocokkannya dengan deskripsi yang diberikan. Hasil prediksi dan waktu yang dibutuhkan untuk melakukan prediksi akan ditampilkan di terminal.

# Kesimpulan
Skrip ini memberikan cara yang sederhana dan efektif untuk menguji kemampuan model CLIP dalam memahami gambar dan mencocokkannya dengan deskripsi teks. Dengan menggunakan skrip ini, pengguna dapat dengan mudah melihat bagaimana model CLIP bekerja dan mengukur kinerjanya dalam tugas pencocokan gambar dan teks.

---

# Deskripsi ` app.py` 
Proyek ini adalah sebuah aplikasi berbasis web yang menggunakan Streamlit untuk menguji kemampuan model CLIP dalam memahami gambar. Aplikasi ini memungkinkan pengguna untuk mengunggah gambar dan memberikan tiga deskripsi, di mana satu deskripsi harus benar. Model kemudian akan memprediksi deskripsi mana yang paling sesuai dengan gambar yang diunggah.

# Kegunaan
Aplikasi ini berguna untuk:
- Menguji kemampuan model CLIP dalam memahami dan menginterpretasikan gambar.
- Memberikan pengalaman interaktif kepada pengguna dalam menguji model AI.
- Menyediakan antarmuka yang mudah digunakan untuk eksperimen dengan model CLIP.

# Fungsi
Aplikasi ini memiliki beberapa fungsi utama:
- Mengunggah gambar melalui antarmuka Streamlit.
- Memproses gambar yang diunggah dan deskripsi yang diberikan oleh pengguna.
- Menggunakan model CLIP untuk memprediksi deskripsi yang paling sesuai dengan gambar.
- Menampilkan hasil prediksi dan probabilitasnya kepada pengguna.

# Bagaimana Menjalankan
Untuk menjalankan aplikasi ini, ikuti langkah-langkah berikut:

1. **Instalasi Dependensi**
   Pastikan Anda telah menginstal semua dependensi yang diperlukan. Anda dapat menggunakan `pip` untuk menginstal dependensi yang tercantum dalam `requirements.txt`.

   ```bash
   pip install -r requirements.txt
   ```

2. **Menjalankan Aplikasi**
   Jalankan aplikasi Streamlit dengan perintah berikut:

   ```bash
   streamlit run app.py
   ```

3. **Mengunggah Gambar dan Memberikan Deskripsi**
   - Buka browser dan akses alamat yang diberikan oleh Streamlit.
   - Unggah gambar yang ingin Anda uji.
   - Berikan tiga deskripsi tentang gambar tersebut, di mana satu deskripsi harus benar.
   - Klik tombol "Predict" untuk melihat hasil prediksi.

# Kesimpulan
Aplikasi ini memberikan cara yang interaktif dan mudah digunakan untuk menguji kemampuan model CLIP dalam memahami gambar. Dengan antarmuka berbasis web yang sederhana, pengguna dapat dengan mudah mengunggah gambar, memberikan deskripsi, dan melihat hasil prediksi dari model. Aplikasi ini dapat digunakan untuk berbagai keperluan, termasuk eksperimen dan demonstrasi kemampuan model AI dalam memahami konten visual.