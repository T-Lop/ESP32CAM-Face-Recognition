1. Pengambilan Gambar: Sistem mengambil gambar wajah menggunakan kamera, seperti modul ESP32CAM.

2. Deteksi Wajah: Algoritma deteksi wajah mengidentifikasi dan menandai area wajah dalam gambar. Ini melibatkan penggunaan model pembelajaran mesin yang telah dilatih untuk mengenali fitur-fitur wajah.

3. Ekstraksi Fitur: Setelah wajah terdeteksi, sistem mengekstrak fitur-fitur penting dari wajah tersebut, seperti jarak antara mata, bentuk hidung, dan struktur rahang. Proses ini menghasilkan representasi digital wajah dalam bentuk vektor fitur.

4. Pembandingan Fitur: Vektor fitur yang diperoleh dibandingkan dengan vektor fitur wajah-wajah yang ada dalam database. Pembandingan ini menggunakan algoritma tertentu, seperti algoritma Euclidean Distance atau Cosine Similarity, untuk mengukur kesamaan antara wajah yang baru diambil dan wajah-wajah dalam database.

5. Identifikasi atau Verifikasi: Berdasarkan hasil pembandingan, sistem menentukan identitas wajah tersebut (identifikasi) atau mengonfirmasi apakah wajah tersebut sesuai dengan identitas yang diklaim (verifikasi). Jika tingkat kesamaan di atas ambang batas yang ditentukan, wajah dianggap cocok; jika tidak, wajah dianggap tidak cocok.

6. Tindakan Lanjutan: Berdasarkan hasil identifikasi atau verifikasi, sistem dapat melakukan berbagai tindakan, seperti membuka kunci pintu, mencatat kehadiran, atau memberikan akses ke aplikasi tertentu.
