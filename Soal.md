1. **Soal:** Kondisi RACE CONDITION pada proses konkuren terjadi ketika ...

**Pilihan:**
A. Dua proses mengakses data yang sama secara bersamaan dan hasilnya bergantung pada urutan akses
B. Sebuah proses menunggu terlalu lama sehingga dimatikan oleh OS
C. CPU melakukan context switch terlalu sering sehingga overhead meningkat
D. Dua proses memperebutkan prioritas penjadwalan yang sama

**Jawaban:** A – Dua proses mengakses data yang sama secara bersamaan dan hasilnya bergantung pada urutan akses

---

2. **32010.jpg**

**Soal:** Journaling pada sistem file modern (ext4, NTFS) berfungsi untuk ...

**Pilihan:**
A. Meningkatkan kecepatan baca dengan pre-fetching blok
B. Menjamin konsistensi file system setelah crash dengan mencatat perubahan sebelum diterapkan
C. Mengenkripsi data secara transparan sebelum ditulis ke disk
D. Mengurangi fragmentasi dengan mengatur ulang blok secara periodik

**Jawaban:** B – Menjamin konsistensi file system setelah crash dengan mencatat perubahan sebelum diterapkan

---

3. **32013.jpg**

**Soal:** Perbedaan UTAMA antara hard link dan symbolic link (symlink) pada sistem file Unix/Linux adalah ...

**Pilihan:**
A. Hard link dapat merujuk ke file di partisi berbeda; symlink hanya di partisi yang sama
B. Hard link berbagi inode yang sama dengan file asli; symlink hanya menyimpan path ke target
C. Symlink meningkatkan reference count inode; hard link tidak mempengaruhi inode
D. Hard link hanya berlaku untuk direktori; symlink hanya untuk file biasa

**Jawaban:** B – Hard link berbagi inode yang sama dengan file asli; symlink hanya menyimpan path ke target

---

4. **32025.jpg**

**Soal:** Sebuah sistem operasi harus menyediakan environment agar program dapat berjalan dengan benar. Komponen kernel yang bertugas menjadi PERANTARA antara hardware dan software aplikasi adalah ...

**Pilihan:**
A. Shell (command interpreter)
B. System call interface
C. Device driver
D. Compiler / linker

**Jawaban:** B – System call interface

---

5. **32043.jpg**

**Soal:** Mode kernel (kernel mode) memberikan akses penuh ke semua instruksi CPU dan memori, sedangkan mode pengguna (user mode) membatasi instruksi yang dapat dieksekusi suatu proses.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

6. **32019.jpg**

**Soal:** Tiga proses berada di antrian ready: P1 (burst=6ms), P2 (burst=2ms), P3 (burst=4ms). Dengan algoritma SJF non-preemptive, urutan eksekusi dan average waiting time adalah ...

**Pilihan:**
A. P2→P3→P1; AWT = 3.33 ms
B. P1→P2→P3; AWT = 4.00 ms
C. P2→P3→P1; AWT = 4.00 ms
D. P3→P2→P1; AWT = 5.00 ms

**Jawaban:** A – P2→P3→P1; AWT = 3.33 ms

---

7. **32022.jpg**

**Soal:** Pada algoritma penggantian halaman LRU (Least Recently Used), halaman yang paling lama tidak digunakan dipilih sebagai korban. LRU memberikan performa yang sama dengan algoritma Optimal (Belady) untuk semua pola akses.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** B – Salah

---

8. **32028.jpg**

**Soal:** Serangan BUFFER OVERFLOW bekerja dengan cara ...

**Pilihan:**
A. Mengisi buffer jaringan sehingga paket selanjutnya tertolak (DoS)
B. Menulis data melebihi batas buffer yang dialokasikan untuk menimpa return address dan mengarahkan eksekusi ke shellcode penyerang
C. Mengenkripsi buffer memori sehingga program tidak dapat membacanya
D. Memodifikasi nilai variabel di heap untuk memalsukan autentikasi

**Jawaban:** B – Menulis data melebihi batas buffer yang dialokasikan untuk menimpa return address dan mengarahkan eksekusi ke shellcode penyerang

---

9. **32031.jpg**

**Soal:** Segmentasi berbeda dari paging karena segmen memiliki ukuran tetap yang ditentukan oleh hardware, sementara halaman (page) memiliki ukuran yang ditentukan oleh programmer.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** B – Salah (segmentasi ukuran variabel, paging ukuran tetap oleh hardware)

---

10. **32037.jpg**

**Soal:** File system NTFS (Windows) menggunakan Master Boot Record (MBR) sebagai struktur utama untuk menyimpan metadata seluruh file, sedangkan ext4 (Linux) menggunakan inode table.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** B – Salah (NTFS menggunakan $MFT, bukan MBR)

---

11. **32052.jpg**

**Soal:** Pada mekanisme SEMAPHORE, operasi wait(S) (S = 0; block) dan signal(S) (S++; if S <= 0: wakeup). Jika S diinisialisasi = 1 dan dua proses P1, P2 memanggil wait() hampir bersamaan, hasil yang BENAR adalah ...

**Pilihan:**
A. P1 dan P2 masuk critical section bersamaan karena masing-masing mendapatkan S=1
B. Salah satu proses diblokir; hanya satu yang masuk critical section
C. Semaphore negatif tidak valid sehingga OS menghentikan kedua proses
D. S tetap 1 karena dua operasi decrement saling mengkompensasi

**Jawaban:** B – Salah satu proses diblokir; hanya satu yang masuk critical section

---

12. **32061.jpg**

**Soal:** Perintah Linux 'ls -l' menampilkan: -rwxr-x--- 2 budi dosen 4096 Hok

akses yang DIMILIKI oleh anggota group 'dosen' adalah ...

**Pilihan:**
A. Baca, tulis, dan eksekusi
B. Baca dan eksekusi saja
C. Baca saja
D. Tidak memiliki hak akses sama sekali

**Jawaban:** B – Baca dan eksekusi saja (r-x)

---

13. **32085.jpg**

**Soal:** THRASHING terjadi pada sistem virtual memory ketika ...

**Pilihan:**
A. Terlalu banyak proses aktif sehingga CPU menghabiskan lebih banyak waktu untuk paging daripada eksekusi
B. Proses mengakses halaman yang sama berulang kali sehingga TLB penuh
C. Disk swap space penuh dan OS tidak bisa mengalokasikan halaman baru
D. Algoritma LRU gagal menemukan halaman victim yang tepat

**Jawaban:** A – Terlalu banyak proses aktif sehingga CPU menghabiskan lebih banyak waktu untuk paging daripada eksekusi

---

14. **32088.jpg**

**Soal:** Operasi 'open()' pada file mengembalikan FILE DESCRIPTOR — sebuah bilangan bulat kecil yang digunakan proses untuk merujuk file tersebut pada operasi read(), write(), dan close() berikutnya.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

15. **32091.jpg**

**Soal:** SELinux (Security-Enhanced Linux) mengimplementasikan Mandatory Access Control (MAC) yang menambahkan lapisan kebijakan keamanan di atas DAC (Discretionary Access Control) standar Unix, sehingga bahkan root pun dapat dibatasi aksesnya ke sumber daya tertentu.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

16. **32097.jpg**

**Soal:** Algoritma Banker digunakan untuk menghindari deadlock. Sistem berada dalam SAFE STATE jika ...

**Pilihan:**
A. Tidak ada proses yang sedang menunggu resource
B. Terdapat urutan eksekusi (safe sequence) di mana setiap proses dapat menyelesaikan tugasnya
C. Semua resource yang tersedia melebihi total kebutuhan maksimum semua proses
D. Tidak ada dua proses yang memegang resource yang sama

**Jawaban:** B – Terdapat urutan eksekusi (safe sequence) di mana setiap proses dapat menyelesaikan tugasnya

---

17. **32100.jpg**

**Soal:** Enkripsi simetris menggunakan kunci yang berbeda untuk enkripsi dan dekripsi, sehingga kunci privat tidak perlu dikirimkan ke penerima.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** B – Salah (enkripsi simetris menggunakan kunci yang sama untuk enkripsi dan dekripsi)

---

18. **32106.jpg**

**Soal:** Proses P1 (prioritas 3) sedang berjalan. P2 (prioritas 7) tiba. Pada algoritma Priority Scheduling PREEMPTIVE (prioritas lebih tinggi = angka lebih besar), yang terjadi adalah ...

**Pilihan:**
A. P1 tetap berjalan hingga selesai karena sudah dijadwalkan
B. P2 menunggu dalam antrian sampai P1 selesai
C. P1 dihentikan sementara dan CPU diberikan ke P2
D. Keduanya berjalan secara paralel (pseudo-parallelism)

**Jawaban:** C – P1 dihentikan sementara dan CPU diberikan ke P2

---

19. **32115.jpg**

**Soal:** Sebuah inode pada sistem file ext4 menyimpan 12 direct block pointer, 1 single indirect, 1 double indirect, dan 1 triple indirect. Dengan ukuran blok 4 KB dan pointer 4 byte, BERAPA BESAR MAKSIMUM file yang dapat ditangani single indirect pointer?

**Pilihan:**
A. 4 KB
B. 1024 × 4 KB = 4 MB
C. 4 KB × 12 = 48 KB
D. 1024 × 1024 × 4 KB = 4 GB

**Jawaban:** B – 1024 × 4 KB = 4 MB

---

20. **32034.jpg**

**Soal:** Algoritma alokasi memori BEST-FIT memilih hole terkecil yang masih cukup untuk proses. Kelemahan utama Best-Fit dibanding First-Fit adalah ...

**Pilihan:**
A. Best-Fit lebih lambat karena harus memindai seluruh daftar hole
B. Best-Fit menghasilkan fragmentasi internal lebih besar
C. Best-Fit tidak dapat menangani proses yang lebih besar dari hole manapun
D. Best-Fit memerlukan hardware khusus untuk pointer aritmatika

**Jawaban:** A – Best-Fit lebih lambat karena harus memindai seluruh daftar hole

---

21. **32040.jpg**

**Soal:** Manajemen ruang bebas (free space management) dengan metode BITMAP menggunakan 1 bit per blok. Untuk disk berukuran 500 GB dengan blok 4 KB, berapa UKURAN BITMAP yang dibutuhkan?

**Pilihan:**
A. Sekitar 15 MB
B. Sekitar 500 MB
C. Sekitar 125 KB
D. Sekitar 1 GB

**Jawaban:** A – Sekitar 15 MB

---

22. **32058.jpg**

**Soal:** Struktur direktori ACYCLIC GRAPH berbeda dari struktur TREE karena ...

**Pilihan:**
A. Acyclic graph tidak mendukung subdirektori bertingkat
B. Acyclic graph memungkinkan satu file memiliki beberapa nama (link) di direktori berbeda
C. Tree structure hanya bisa digunakan pada sistem single-user
D. Acyclic graph tidak memiliki direktori root (akar)

**Jawaban:** B – Acyclic graph memungkinkan satu file memiliki beberapa nama (link) di direktori berbeda

---

23. **32064.jpg**

**Soal:** Translation Lookaside Buffer (TLB) digunakan dalam sistem paging untuk ...

**Pilihan:**
A. Menyimpan isi halaman yang sering diakses agar tidak perlu baca disk
B. Mempercepat translasi alamat dengan menyimpan cache entri tabel halaman
C. Mendeteksi page fault sebelum terjadi
D. Menggantikan page table sepenuhnya pada proses kecil

**Jawaban:** B – Mempercepat translasi alamat dengan menyimpan cache entri tabel halaman

---

24. **32073.jpg**

**Soal:** Algoritma penggantian halaman OPTIMAL (Belady) memberikan page fault rate terendah tetapi tidak dapat diimplementasikan secara praktis karena ...

**Pilihan:**
A. Terlalu kompleks secara komputasi untuk dilakukan real-time
B. Membutuhkan pengetahuan di muka tentang urutan referensi halaman yang akan datang
C. Tidak kompatibel dengan arsitektur TLB modern
D. Hanya bekerja untuk program dengan referensi acak, bukan sequential

**Jawaban:** B – Membutuhkan pengetahuan di muka tentang urutan referensi halaman yang akan datang

---

25. **32076.jpg**

**Soal:** Memory compaction (pemadatan memori) pada pemartisan dinamis bertujuan menggabungkan hole-hole kecil yang tersebar menjadi satu hole besar, tetapi memerlukan relokasi semua proses aktif dan menghentikan eksekusi sementara.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

26. **32079.jpg**

**Soal:** Sistem operasi menggunakan FILE CONTROL BLOCK (FCB) / inode untuk menyimpan metadata file. Informasi yang TIDAK tersimpan di dalam inode/FCB adalah ...

**Pilihan:**
A. Ukuran file dan timestamp modifikasi
B. Izin akses (permission bits) dan owner UID/GID
C. Nama file (filename)
D. Pointer ke blok-blok data di disk

**Jawaban:** C – Nama file (filename)

---

27. **32082.jpg**

**Soal:** Pada virtual memory dengan demand paging, PAGE FAULT terjadi ketika ...

**Pilihan:**
A. Proses mencoba mengakses halaman yang tidak ada di page table
B. Proses mencoba mengakses halaman yang ada di memori fisik tetapi tidak memiliki akses
C. Halaman yang diakses berada di memori fisik tetapi TLB-miss terjadi
D. Proses mengakses halaman yang berada di memori fisik tetapi sudah di-swap

**Jawaban:** A – Proses mencoba mengakses halaman yang tidak ada di page table (atau tidak di memori fisik)

---

28. **32109.jpg**

**Soal:** Pada sistem dengan virtual memory, proses dapat menggunakan ruang alamat logis yang LEBIH BESAR dari memori fisik yang tersedia karena OS secara transparan memindahkan halaman yang tidak aktif ke disk (swap space).

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

29. **32112.jpg**

**Soal:** Pada metode alokasi disk linked (berkait), akses acak (random access) ke blok ke-n dalam sebuah file memiliki kompleksitas O(n) karena harus mengikuti rantai pointer dari blok pertama hingga blok ke-n.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

30. **32118.jpg**

**Soal:** Perbedaan UTAMA antara microkernel dan monolithic kernel adalah ...

**Pilihan:**
A. Microkernel menjalankan semua layanan OS di kernel space, monolithic di user space
B. Microkernel hanya menyimpan fungsi minimal di kernel, layanan lain di user space
C. Monolithic kernel tidak mendukung multitasking; microkernel mendukung
D. Microkernel lebih lambat karena menggunakan bahasa interpreted

**Jawaban:** B – Microkernel hanya menyimpan fungsi minimal di kernel, layanan lain di user space

---

31. **32046.jpg**

**Soal:** Pada arsitektur sistem operasi berlapis (layered), jika lapisan ke-9 mengalami gangguan, lapisan mana yang PALING LANGSUNG terdampak?

**Pilihan:**
A. Lapisan ke-(N+2) karena bergantung transitif
B. Lapisan ke-(N+1) yang berada tepat di atasnya
C. Semua lapisan secara bersamaan
D. Lapisan ke-(N-1) karena terjadi callback

**Jawaban:** B – Lapisan ke-(N+1) yang berada tepat di atasnya

---

32. **32049.jpg**

**Soal:** Kondisi DEADLOCK membutuhkan EMPAT syarat Coffman yang harus terpenuhi secara simultan. Syarat yang menyatakan proses hanya dapat melepas resource setelah selesai menggunakannya adalah ...

**Pilihan:**
A. Mutual Exclusion
B. Hold and Wait
C. No Preemption
D. Circular Wait

**Jawaban:** C – No Preemption

---

33. **32055.jpg**

**Soal:** Perbedaan MENDASAR antara pemartisan statis dan pemartisan dinamis pada manajemen memori adalah ...

**Pilihan:**
A. Pemartisan statis menggunakan paging; pemartisan dinamis menggunakan segmentasi
B. Pemartisan dinamis membuat partisi tepat sesuai proses sehingga tidak ada fragmentasi internal
C. Pemartisan statis tidak mendukung multiprogramming; pemartisan dinamis mendukung
D. Pemartisan dinamis mengalokasikan memori di disk; statis di RAM

**Jawaban:** B – Pemartisan dinamis membuat partisi tepat sesuai proses sehingga tidak ada fragmentasi internal

---

34. **32067.jpg**

**Soal:** Starvation dapat terjadi pada algoritma Priority Scheduling ketika proses berprioritas rendah terus-menerus tertunda akibat proses berprioritas tinggi yang selalu tiba. Solusinya adalah teknik AGING yang secara bertahap menaikkan prioritas proses yang menunggu.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** A – Benar

---

35. **32070.jpg**

**Soal:** Sebuah sistem paging menggunakan ukuran halaman 4 KB. Alamat logis 0x3A7C (desimal: 14972) merujuk ke nomor halaman berapa dan offset berapa?

**Pilihan:**
A. Halaman 3, Offset 2684
B. Halaman 3, Offset 0x27C (636)
C. Halaman 14, Offset 972
D. Halaman 2, Offset 1900

**Jawaban:** A – Halaman 3, Offset 2684

---

36. **32094.jpg**

**Soal:** Sistem dengan memori fisik 256 KB menggunakan pemartisan statis ukuran sama menjadi 8 partisi. Sebuah proses berukuran 20 KB ditempatkan di partisi 32 KB. Berapa besar INTERNAL FRAGMENTATION yang terjadi?

**Pilihan:** (pilihan tidak tertulis jelas, tapi opsi B adalah 12 KB)

A. 0 KB
B. 12 KB
C. 8 KB
D. 4 KB

**Jawaban:** B – 12 KB

---

37. **32103.jpg**

**Soal:** Metode alokasi disk CONTIGUOUS mengharuskan setiap file menempati blok-blok yang berurutan. MASALAH UTAMA metode ini pada implementasi praktis adalah ...

**Pilihan:**
A. Tidak mendukung akses sekuensial sehingga lambat untuk file besar
B. Fragmentasi eksternal dan sulitnya mengembangkan ukuran file
C. Tidak dapat menyimpan metadata file (nama, izin, timestamp)
D. Tidak kompatibel dengan sistem operasi berbasis Unix

**Jawaban:** B – Fragmentasi eksternal dan sulitnya mengembangkan ukuran file

---

38. **32016.jpg**

**Soal:** Round Robin adalah algoritma penjadwalan non-preemptive karena setelah proses menerima quantum waktu, proses tidak dapat diinterupsi sampai quantum habis.

**Pilihan:**
A. Benar
B. Salah

**Jawaban:** B – Salah (Round Robin adalah preemptive)

---

39. **32007.jpg**

**Soal:** Prinsip LEAST PRIVILEGE dalam keamanan sistem operasi menyatakan bahwa ...

**Pilihan:**
A. Setiap pengguna harus menggunakan password sekuat mungkin
B. Proses dan pengguna hanya diberikan hak akses minimum yang diperlukan untuk menjalankan tugasnya
C. Superuser (root) tidak boleh login langsung ke sistem produksi
D. Semua proses harus berjalan di user mode tanpa pengecualian

**Jawaban:** B – Proses dan pengguna hanya diberikan hak akses minimum yang diperlukan untuk menjalankan tugasnya

---

40. **32002.jpg**

**Soal:** FAT (File Allocation Table) adalah implementasi dari metode alokasi ...

**Pilihan:**
A. Contiguous allocation dengan pointer di setiap blok
B. Indexed allocation dengan index block terpisah
C. Linked allocation di mana tabel FAT menyimpan rantai pointer di memori
D. Free space bitmap yang diperlukan dengan metadata blok

**Jawaban:** C – Linked allocation di mana tabel FAT menyimpan rantai pointer di memori

---

Jika ada soal yang ingin Anda bahas lebih lanjut atau ragu, silakan sebutkan nomornya.
