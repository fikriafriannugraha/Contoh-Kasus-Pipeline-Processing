# Contoh-Kasus-Pipeline-Processing

---

### **Contoh Kasus: Pemrosesan Gambar dalam Aplikasi Kamera Digital**

#### **Deskripsi:**
Sebuah aplikasi kamera digital modern melakukan serangkaian pemrosesan pada gambar sebelum ditampilkan atau disimpan. Setiap langkah bisa dilakukan secara *pipeline*, agar sistem bisa menangani banyak gambar secara efisien.

---

### **Tahapan Pipeline:**

1. **Capture Image**  
   Kamera menangkap citra mentah dari sensor.

2. **Image Denoising**  
   Menghilangkan noise dari gambar untuk memperbaiki kualitas.

3. **Image Enhancement**  
   Meningkatkan kontras, pencahayaan, dan warna.

4. **Face Detection**  
   Mendeteksi wajah dalam gambar jika ada.

5. **Image Compression**  
   Mengompres gambar agar ukurannya lebih kecil untuk penyimpanan.

6. **Save/Display Image**  
   Gambar disimpan ke memori atau ditampilkan di layar.

---

### **Cara Kerja Pipeline:**

- Tahapan-tahapan ini bisa dijalankan dalam sistem *pipeline*, di mana setiap unit kerja menangani satu langkah dan mengoperkan hasilnya ke unit berikutnya.
- Misalnya, saat unit 1 memproses gambar ke-2, unit 2 sudah memproses gambar ke-1, dan seterusnya → seperti jalur perakitan.

---

### **Manfaat Pipeline Processing dalam Kasus Ini:**

- **Efisiensi waktu**: Gambar dapat diproses paralel di berbagai tahap.
- **Throughput tinggi**: Sistem bisa memproses banyak gambar per detik.
- **Skalabilitas**: Bisa menambah unit pemrosesan jika beban meningkat.
