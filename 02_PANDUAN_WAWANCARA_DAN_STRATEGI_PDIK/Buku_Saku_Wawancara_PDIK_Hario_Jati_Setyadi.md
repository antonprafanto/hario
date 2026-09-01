# 📘 BUKU SAKU BEDAH PROPOSAL DISERTASI & PANDUAN WAWANCARA SELEKSI S3
> ⚠️ **CATATAN PENTING / DISCLAIMER:**  
> Dokumen buku saku ini merupakan **DRAF CONTOH / ILUSTRASI SIMULASI** yang disusun berbasis **Usulan Topik 1 (Adaptive UI & Real-Time Technostress Detection)** sebagai gambaran kesiapan wawancara.  
> Saat ini calon mahasiswa (Pak Hario) masih dalam tahap mempertimbangkan dan memilih salah satu dari **4 Alternatif Topik Unggulan**.  
> **Setelah Pak Hario menetapkan pilihan topiknya, buku saku ini akan disesuaikan dan difinalisasi secara penuh mengikuti topik definitif yang dipilih.**

---

### **Kandidat Calon Doktor:** Hario Jati Setyadi, S.Kom., M.Kom.
**Jabatan Profesi:** Ketua APTIKOM Provinsi Kalimantan Timur (Periode 2026–2030)  
**Program Studi Tujuan:** S3 Program Doktor Ilmu Komputer (PDIK) - Universitas Dian Nuswantoro (UDINUS)  
**Bidang Minat/Peminatan:** *Human-Computer Interaction, Intelligent Systems & Software Architecture*  
**Website Kurikulum Resmi:** https://pdik.dinus.ac.id/kurikulum/  

---

## 🎯 1. Ringkasan Topik Disertasi dalam 1 Kalimat Santai (Elevator Pitch - *Contoh Topik 1*)

> **Judul Usulan Contoh:**  
> *"Intelligent Adaptive User Interface Framework Based on Real-Time Cognitive Load and Technostress Detection Using Deep Neural Networks"*
>
> **Bahasa Manusianya (Penjelasan Sederhana 30 Detik):**  
> *"Membuat antarmuka aplikasi komputer cerdas yang bisa **mendeteksi kapan penggunanya mulai merasa pusing, stres, atau kelelahan secara otomatis dari cara mereka mengetik dan menggerakkan mouse**, lalu tampilan antarmuka layarnya akan **otomatis disederhanakan dan dibantu langkah-langkahnya** agar pekerjaan selesai tanpa memicu stres dan kesalahan manusia (human error)."*

---

## 💡 2. Analogi Sederhana untuk Memahami 4 Konsep Kunci (*Contoh Topik 1*)

### A. Apa itu *Technostress & Cognitive Load*?
* **Analogi Sopir di Tengah Hujan Badai:**  
  Saat jalanan lengang dan cuaca cerah (beban kognitif rendah), sopir bisa menyetir santai sambil mendengarkan musik. Namun saat hujan badai lebat dan jalanan macet parah (stres tinggi), sopir mematikan musik dan fokus penuh. Antarmuka aplikasi enterprise sering kali memaksa pengguna bekerja seperti dalam badai terus-menerus tanpa adaptasi.

### B. Mengapa menggunakan *Keystroke Dynamics & Mouse Trajectory*?
* **Analogi Ketukan Pintu Seseorang:**  
  Saat seseorang sedang tenang, ketukan pintunya berirama teratur. Saat sedang panik atau lelah, ketukannya menjadi tidak beraturan dan tersendat-sendat. Dinamika pengetikan dan gerakan tetikus memiliki pola mikroskopis yang dapat dibaca oleh Deep Learning secara non-invasif tanpa kamera atau alat sensor tempel yang ribet.

### C. Apa itu *Self-Adaptive User Interface (SA-UI)*?
* **Analogi Asisten Pintar yang Peka:**  
  Ketika asisten melihat bosnya sedang kewalahan dengan setumpuk berkas rumit, asisten segera menyortir dan hanya menyodorkan 1 formulir terpenting yang perlu ditandatangani saat itu juga, menyembunyikan detail yang tidak mendesak.

### D. Mengapa menggunakan *Temporal Transformer / CNN-LSTM*?
* **Analogi Membaca Cerita Bersambung:**  
  Data gerakan mouse dan ketukan keyboard adalah data deret waktu (*time-series*). Model Temporal Transformer mampu mengingat konteks gerakan 10 detik lalu untuk memahami apakah jeda pengetikan pengguna adalah karena sedang berpikir normal atau sedang mengalami kebuntuan kognitif (*cognitive freeze*).

---

## 🔍 3. Mengapa Riset Ini Sangat Penting & Bernilai Doktoral?

1. **Masalah Nyata Produktivitas Kerja & Human Error:**
   * Di lingkungan perguruan tinggi, perbankan, dan pemerintahan, ribuan staf mengalami kejenuhan dan stres operasional saat mengoperasikan aplikasi yang rumit, memicu tingginya angka kesalahan input data.
2. **Kelemahan Riset Technostress Terdahulu:**
   * Riset sebelumnya hanya mengukur technostress secara retrospektif (lewat kuesioner setelah kerja selesai). Riset ini **melakukan deteksi dan intervensi langsung saat sistem sedang berjalan (*runtime mitigation*)**.
3. **Peluang Publikasi Top-Tier Scopus Q1:**
   * Topik perpaduan antara *Human Factors (HCI)* dan *Deep Learning* sangat diminati oleh jurnal papan atas dunia seperti *ACM TOCHI*, *Int. J. Human-Computer Studies*, dan *Computers in Human Behavior*.

---

## 🔬 4. Desain Eksperimen & Validasi (Sangat Feasible di Lab)

* **Lingkungan Eksperimen:**
  * Pengujian dilakukan di Laboratorium Komputer UNMUL menggunakan aplikasi web enterprise simulasi.
  * Logging telemetri interaksi berbasis JavaScript event listener ringan (bebas dari isu pelanggaran privasi karena tidak merekam karakter sensitif, melainkan hanya *timing interval* dan *velocity*).
* **Skenario Evaluasi:**
  1. *Baseline Tasks:* Pengujian tugas normal vs tugas berbatas waktu ketat (*high-stress workload*).
  2. *A/B Testing:* Pengukuran performa pengguna dengan antarmuka statis vs antarmuka adaptif cerdas (SA-UI).
  3. *Metrik Keberhasilan:* Reduksi *Task Completion Time*, penurunan angka kesalahan klik (*misclick rate*), dan penurunan skor beban kerja *NASA-TLX*.

---

## 🏛️ 5. Keselarasan dengan Kurikulum Resmi PDIK UDINUS (55 SKS, 6 Semester)

* **Semester 1 (11 SKS):**
  * *Philosophy of Science* (2 SKS)
  * *Research Methodology* (3 SKS)
  * *Advanced Soft Computing* (3 SKS)
  * *Advanced Software Systems / HCI* (3 SKS)
* **Semester 2 (10 SKS):**
  * *Scientific Writing* (2 SKS)
  * *Research Trends on Intelligent Systems* (3 SKS)
  * **Disertasi I: International Conference** (5 SKS → Submit Paper IEEE Prosiding)
* **Semester 3 (7 SKS):**
  * **Disertasi II: Proposal Dissertation** (7 SKS → Sidang Ujian Proposal Disertasi)
  * *Progress Report 1*
* **Semester 4 (7 SKS):**
  * **Disertasi III: Scientific Publication 2** (7 SKS → Submit Paper Jurnal Scopus Q1/Q2, e.g., ACM TOCHI / IJHCS)
  * *Progress Report 2*
* **Semester 5 (7 SKS):**
  * **Disertasi IV: Completion Seminar** (7 SKS → Sidang Ujian Tertutup)
  * *Progress Report 3*
* **Semester 6 (6 SKS):**
  * **Disertasi V: Open Viva** (6 SKS → Sidang Ujian Terbuka / Promosi Doktor & Wisuda)

---

## 🎓 6. Cheat Sheet & Tanya-Jawab Taktis Wawancara Seleksi S3 PDIK UDINUS

---

### ❓ Pertanyaan 1: *"Pak Hario, coba jelaskan dalam 2 menit apa fokus utama disertasi Anda dan mengapa topik ini penting bagi keilmuan Ilmu Komputer?"*
> **Jawaban Taktis Pak Hario:**  
> *"Terima kasih Bapak/Ibu Penguji. Penelitian saya berfokus pada ranah **Human-Computer Interaction (HCI) dan Intelligent Systems**, khususnya pada penanganan isu *Technostress* dan *Cognitive Overload* saat manusia berinteraksi dengan sistem perangkat lunak yang kompleks.  
> Kelemahan utama riset sebelumnya adalah evaluasi technostress hanya dilakukan secara pasif melalui kuesioner pasca-penggunaan, sementara antarmuka sistem tetap kaku dan tidak mampu merespons kondisi stres pengguna secara langsung.  
> Melalui disertasi ini, saya mengusulkan **Kerangka Kerja Antarmuka Pengguna Adaptif Cerdas berbasis Deep Neural Networks**. Sistem ini mendeteksi indikator stres secara non-invasif dari telemetri dinamika pengetikan dan gerakan mouse saat runtime, lalu secara otomatis merekonfigurasi tata letak antarmuka agar beban kognitif pengguna segera berkurang dan human error dapat dicegah."*

---

### ❓ Pertanyaan 2: *"Bagaimana Anda menjamin bahwa data biometrik perilaku (keystroke dynamics) tidak melanggar privasi pengguna?"*
> **Jawaban Taktis Pak Hario:**  
> *"Sangat penting untuk ditekankan Bapak/Ibu, bahwa sistem kami **tidak merekam karakter atau konten teks yang diketik (no keylogging)**. Telemetri yang diekstraksi murni adalah parameter waktu fisika (*temporal dynamics*), seperti *Dwell Time* (durasi tombol ditekan dalam milidetik), *Flight Time* (jeda waktu antar tombol), dan akselerasi gerakan kursor tetikus. Dengan demikian, privasi dan kerahasiaan data pengguna terjamin 100% aman dan patuh pada regulasi Pelindungan Data Pribadi (UU PDP)."*

---

### ❓ Pertanyaan 3: *"Apa hubungan penelitian ini dengan rekam jejak akademik Anda sebelumnya?"*
> **Jawaban Taktis Pak Hario:**  
> *"Topik ini merupakan integrasi linear dan penyempurnaan dari rekam jejak riset saya, Bapak/Ibu:  
> 1. Pada jenjang S2 Magister Teknik Informatika ITS di bawah bimbingan Dr. Tony Dwi Susanto, saya telah meneliti pengaruh usia kognitif dan technostress terhadap kinerja pengguna teknologi informasi.  
> 2. Saya aktif mempublikasikan artikel ilmiah di bidang evaluasi antarmuka, *Design Thinking*, dan model adopsi sistem informasi (termasuk di *Procedia Computer Science* dengan 48 sitasi).  
> 3. Saya juga aktif meneliti arsitektur *Deep Learning* terbaru. Disertasi ini mentransformasikan riset empiris perilaku manusia menjadi sistem komputasi cerdas terapan."*

---

### ❓ Pertanyaan 4: *"Dengan status Anda sebagai Ketua APTIKOM Kaltim, apakah Anda yakin memiliki waktu cukup untuk menyelesaikan S3 tepat waktu 3 tahun?"*
> **Jawaban Taktis Pak Hario:**  
> *"Sangat yakin, Bapak/Ibu. Justru peran saya sebagai Ketua APTIKOM Kaltim dan rekam jejak publikasi saya (h-index 10 dengan 89 publikasi) membuktikan manajemen waktu dan tradisi riset saya sudah sangat matang dan teruji.  
> Selain itu, desain eksperimen disertasi ini berbasis uji laboratorium perangkat lunak di kampus UNMUL, sehingga seluruh pengambilan data, pengujian model, dan penulisan naskah berada di bawah kendali penuh saya tanpa hambatan izin eksternal yang kompleks."*
