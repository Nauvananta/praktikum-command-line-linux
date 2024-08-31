1. sudo apt-get update
![Screenshot from 2024-08-30 18-11-10](https://github.com/user-attachments/assets/77bcb399-d201-41cd-a2e2-b08a8cdd1bc5)
Perintah sudo apt-get update digunakan untuk memperbarui daftar paket dari repositori perangkat lunak yang terdaftar di sistem Ini memastikan informasi terbaru tentang paket tersedia sebelum melakukan instalasi atau pembaruan perangkat lunak

2. sudo apt-get upgrade
![Screenshot from 2024-08-30 18-14-27](https://github.com/user-attachments/assets/81467599-9b55-4880-bceb-8fedf389586e)
Perintah sudo apt-get upgrade digunakan untuk memperbarui semua paket yang terinstal di sistem ke versi terbaru yang tersedia dari repositori perangkat lunak tanpa menghapus paket atau menginstal paket baru

3. pwd

![Screenshot from 2024-08-30 18-27-03](https://github.com/user-attachments/assets/ed27e465-24e5-46d2-bc77-28e4e0d6bbdb)

Perintah pwd digunakan untuk menampilkan path direktori kerja saat ini di terminal Ini menunjukkan lokasi direktori tempat kita berada di sistem file

4. cd /home

![Screenshot from 2024-08-30 18-27-17](https://github.com/user-attachments/assets/849587d6-4a48-487c-b889-f02e2c0cac67)

Perintah cd /home digunakan untuk mengubah direktori kerja saat ini ke direktori /home Setelah menjalankan perintah ini, kita akan berada di direktori /home pada sistem file

5. cd

![Screenshot from 2024-08-30 18-27-24](https://github.com/user-attachments/assets/20bf8f6f-6124-40a9-b632-f312b27e81df)

Perintah cd tanpa argumen digunakan untuk mengembalikan kita ke direktori home pengguna saat ini Di banyak sistem, ini adalah direktori seperti /home/nama_pengguna

6. history

![Screenshot from 2024-08-30 18-30-40](https://github.com/user-attachments/assets/00a58757-8fae-4ad4-9f71-a5e3a70b53bc)

Perintah history menampilkan daftar perintah yang telah kita jalankan sebelumnya di terminal

7. man

![Screenshot from 2024-08-30 18-31-02](https://github.com/user-attachments/assets/fbd4b8b0-a23c-4413-8c0d-1d1789a6edc2)

Perintah man digunakan untuk menampilkan halaman manual dari perintah atau program di Linux Halaman manual memberikan informasi dan petunjuk penggunaan untuk berbagai perintah dan program

8. man man

![Screenshot from 2024-08-30 18-31-13](https://github.com/user-attachments/assets/1e56be84-036a-4582-b9f4-9a84d1caa94a)
   
Perintah man man digunakan untuk menampilkan halaman manual dari perintah man Halaman ini memberikan informasi tentang cara menggunakan perintah man itu sendiri termasuk opsi-opsi yang tersedia dan fungsinya

9. file

![Screenshot from 2024-08-30 18-31-33](https://github.com/user-attachments/assets/749ac086-08f6-41a8-a7b1-ab82a36439c9)

Perintah file digunakan untuk menentukan tipe file di Linux Perintah ini menganalisis isi file dan memberikan informasi tentang format atau jenis file tersebut

10. ifconfig
![Screenshot from 2024-08-30 20-54-50](https://github.com/user-attachments/assets/a5b5a19b-8e99-4f58-a729-ac90c00d06ec)
Perintah ifconfig digunakan untuk menampilkan atau mengonfigurasi antarmuka jaringan di Linux Ini digunakan untuk melihat informasi seperti alamat IP subnet mask dan status antarmuka jaringan

11. cal

![Screenshot from 2024-08-30 20-54-21](https://github.com/user-attachments/assets/91f3ecea-c26a-41a9-a553-ec49228d3c91)

Perintah cal digunakan untuk menampilkan kalender bulan dan tahun saat ini di terminal

12. dig
![Screenshot from 2024-08-30 20-53-42](https://github.com/user-attachments/assets/7298ad36-0a2e-4a39-9203-fb5fa9a1d1e6)
Perintah dig digunakan untuk melakukan pencarian DNS dan mendapatkan informasi tentang domain tertentu seperti alamat IP dan server DNS yang terkait

13. netstat
![Screenshot from 2024-08-30 20-53-22](https://github.com/user-attachments/assets/c63bdca8-0e93-4826-b3f6-3fa8c8fd2101)
Perintah netstat digunakan untuk menampilkan statistik jaringan dan koneksi yang aktif di sistem Ini menunjukkan informasi seperti port yang terbuka alamat IP protokol jaringan dan status koneksi

14. sudo nano /etc/resolv.conf

![Screenshot from 2024-08-30 20-45-06](https://github.com/user-attachments/assets/e964a25d-5e56-4c89-9279-819417948a76)

Perintah sudo nano /etc/resolv.conf digunakan untuk membuka file konfigurasi DNS di Linux dengan hak akses superuser File ini berisi server DNS yang digunakan oleh sistem untuk melakukan pencarian nama domain

15. sudo systemctl restart NetworkManager

![Screenshot from 2024-08-30 20-43-19](https://github.com/user-attachments/assets/1bf6c602-af1d-4694-aa68-21f537c8e7f2)

Perintah sudo systemctl restart NetworkManager digunakan untuk me-restart layanan NetworkManager di Linux Ini akan menghentikan dan memulai ulang layanan yang mengelola koneksi jaringan

16. ping google.com
![Screenshot from 2024-08-30 20-41-35](https://github.com/user-attachments/assets/cb344c4b-8a9a-43e3-a0ed-e6ae6f036022)
Perintah ping google.com digunakan untuk mengirim permintaan echo ke server google.com dan memeriksa apakah server tersebut dapat dijangkau serta mengukur waktu respons

17. kill
![Screenshot from 2024-08-30 20-39-09](https://github.com/user-attachments/assets/bebdcb6a-b367-464d-8f4c-b2cad38fbb36)
Perintah kill digunakan untuk mengirim sinyal ke proses di Linux Biasanya digunakan untuk menghentikan proses dengan mengirimkan sinyal tertentu seperti SIGTERM untuk meminta proses berhenti secara normal atau SIGKILL untuk menghentikan proses secara paksa

18. watch -n 2 tail -n 10 /var/log/syslog

![Screenshot from 2024-08-30 20-21-34](https://github.com/user-attachments/assets/716b250f-6904-41d1-9079-7e144a057f6c)

Perintah watch -n 2 tail -n 10 /var/log/syslog digunakan untuk menampilkan 10 baris terakhir dari file log /var/log/syslog dan memperbarui tampilan setiap 2 detik Ini berguna untuk memantau log sistem secara real-time

19. watch -n 3 'top -b -n 1 | head -n 10'

![Screenshot from 2024-08-30 20-20-12](https://github.com/user-attachments/assets/42ce402a-afd0-42a7-95b0-52d2477f0f40)

Perintah watch -n 3 'top -b -n 1 | head -n 10' digunakan untuk menjalankan perintah top dalam mode batch untuk menampilkan 10 baris pertama dari output dan memperbarui tampilan setiap 3 detik Ini berguna untuk memantau proses-proses yang menggunakan sumber daya sistem secara real-time

20. watch -n 5 df -h

![Screenshot from 2024-08-30 20-19-18](https://github.com/user-attachments/assets/5591f4c0-22ce-48c0-bb93-6b56a2e3fb64)

Perintah watch -n 5 df -h digunakan untuk menampilkan informasi tentang penggunaan disk dengan format yang mudah dibaca dan memperbarui tampilan setiap 5 detik Ini berguna untuk memantau ruang disk yang tersedia secara real-time

21. watch 

![Screenshot from 2024-08-30 20-18-54](https://github.com/user-attachments/assets/066d24df-3e49-4bf0-a43e-499767f08cd6)

Perintah watch digunakan untuk menjalankan perintah tertentu secara berulang-ulang dan menampilkan hasilnya di terminal Perintah ini berguna untuk memantau perubahan dalam keluaran perintah secara real-time

22. systemctl
![Screenshot from 2024-08-30 20-17-35](https://github.com/user-attachments/assets/44614773-c444-4dd5-8917-b11a64238630)
Perintah systemctl digunakan untuk mengelola dan mengontrol layanan dan unit sistem di Linux Ini mencakup kemampuan untuk memulai, menghentikan, me-restart, dan memeriksa status layanan serta mengelola unit-unit sistem lainnya

23. time

![Screenshot from 2024-08-30 20-17-17](https://github.com/user-attachments/assets/2bb4458e-c572-4af4-91de-72739d4468ab)

Perintah time digunakan untuk mengukur waktu yang dibutuhkan untuk menjalankan suatu perintah Ini memberikan informasi tentang waktu yang dihabiskan untuk proses CPU dan waktu total yang diperlukan

24. hostname

![Screenshot from 2024-08-30 20-17-08](https://github.com/user-attachments/assets/af6bf122-572e-4faa-8d59-c4a6661e087d)

Perintah hostname digunakan untuk menampilkan atau mengatur nama host sistem di Linux Nama host adalah identifikasi unik untuk komputer di jaringan dan perintah ini membantu kita melihat atau mengubah nama tersebut

25. uname

![Screenshot from 2024-08-30 20-16-56](https://github.com/user-attachments/assets/c7a42e4e-1c40-46d6-b269-ccca620c3abb)

Perintah uname digunakan untuk menampilkan informasi tentang sistem operasi dan kernel yang digunakan di Linux Perintah ini bisa memberikan detail seperti nama kernel versi kernel dan nama mesin yang digunakan

26. top
![Screenshot from 2024-08-30 20-16-19](https://github.com/user-attachments/assets/32ce37a9-93db-4848-b443-76e4cf687176)
Perintah top digunakan untuk menampilkan proses-proses yang sedang berjalan di sistem secara real-time Ini menunjukkan penggunaan CPU memori dan informasi lainnya tentang proses yang aktif di Linux

27. du

![Screenshot from 2024-08-30 20-15-48](https://github.com/user-attachments/assets/32e4863d-ce84-4127-88ac-f3b4c10b847e)
Perintah du digunakan untuk menampilkan penggunaan ruang disk oleh file dan direktori di Linux Ini memberikan informasi tentang ukuran file dan direktori serta total ruang disk yang digunakan

28. useradd

![Screenshot from 2024-08-30 20-15-40](https://github.com/user-attachments/assets/8c90b68d-561a-4c0c-911d-b2239015cb4c)

Perintah useradd digunakan untuk membuat akun pengguna baru di Linux Perintah ini mengonfigurasi akun pengguna dengan nama pengguna yang ditentukan dan mengatur parameter default seperti direktori home dan shell login

29. df

![Screenshot from 2024-08-30 20-15-18](https://github.com/user-attachments/assets/243a2f6a-6d73-4e8e-9cee-fa973cb39756)
Perintah df digunakan untuk menampilkan informasi tentang ruang disk yang digunakan dan tersedia pada sistem file di Linux Ini menunjukkan kapasitas total, ruang yang digunakan, dan ruang yang tersedia pada setiap sistem file yang terpasang

30. exit

![Screenshot from 2024-08-30 20-11-35](https://github.com/user-attachments/assets/6462676f-4e0f-4ce9-90b4-96dd89f23c2c)

Perintah exit digunakan untuk keluar dari terminal atau sesi shell saat ini Ini menutup sesi terminal atau shell yang sedang aktif dan kembali ke lingkungan sebelumnya atau menutup jendela terminal jika tidak ada sesi lain yang terbuka

31. clear

![Screenshot from 2024-08-30 20-10-38](https://github.com/user-attachments/assets/97f74ede-2fc7-42f1-8ac5-d0bf87a9b153)

Perintah clear digunakan untuk membersihkan layar terminal dan menghapus semua teks yang ditampilkan sebelumnya Ini memberikan tampilan terminal yang bersih tanpa menghapus riwayat perintah yang telah dijalankan

32. su - lblanket -s /bin/bash
![Screenshot from 2024-08-30 19-58-28](https://github.com/user-attachments/assets/bbcb303e-742c-4287-9442-08ed76775b48)
Perintah su - lblanket -s /bin/bash digunakan untuk berpindah ke pengguna lblanket dengan shell /bin/bash dan login ke lingkungan pengguna tersebut Secara umum perintah su digunakan untuk berpindah ke pengguna lain atau ke shell root





