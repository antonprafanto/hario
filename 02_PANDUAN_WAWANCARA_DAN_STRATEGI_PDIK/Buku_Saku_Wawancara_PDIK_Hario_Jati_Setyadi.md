# 📘 BUKU SAKU BEDAH PROPOSAL DISERTASI & PANDUAN WAWANCARA SELEKSI S3
> ⚠️ **CATATAN PENTING / DISCLAIMER:**  
> Dokumen buku saku ini merupakan **DRAF CONTOH / ILUSTRASI SIMULASI** yang disusun berbasis **Usulan Topik 1 (Digital Forensik Cloud Microservices & GNN)** sebagai gambaran kesiapan wawancara.  
> Saat ini calon mahasiswa (Pak Hario) sedang meninjau dan memilih salah satu dari **4 Alternatif Topik Digital Forensik Unggulan**.  
> **Setelah Pak Hario menetapkan pilihan topiknya, buku saku ini akan disesuaikan dan difinalisasi secara penuh mengikuti topik definitif yang dipilih.**

---

### **Kandidat Calon Doktor:** Hario Jati Setyadi, S.Kom., M.Kom.
**Jabatan Profesi:** Ketua APTIKOM Provinsi Kalimantan Timur (Periode 2026–2030)  
**Program Studi Tujuan:** S3 Program Doktor Ilmu Komputer (PDIK) - Universitas Dian Nuswantoro (UDINUS)  
**Bidang Minat/Peminatan:** *Digital Forensics, Cloud Security, & Applied Deep Learning*  
**Website Kurikulum Resmi:** https://pdik.dinus.ac.id/kurikulum/  

---

## 🎯 1. Ringkasan Topik Disertasi dalam 1 Kalimat Santai (Elevator Pitch - *Contoh Topik 1*)

> **Judul Usulan Contoh:**  
> *"Autonomous Digital Forensics Investigation Framework Based on Deep Graph Learning for Multi-Stage Attack Reconstruction in Cloud Microservices Environments"*
>
> **Bahasa Manusianya (Penjelasan Sederhana 30 Detik):**  
> *"Membuat sistem investigasi forensik digital otomatis untuk lingkungan server cloud kontainer (Docker/Kubernetes), di mana sistem bisa **merekam dan merekonstruksi jalur kejahatan peretas secara utuh menggunakan grafik hubungan sistem (Provenance Graph) dan Deep Learning**, meskipun kontainer server sudah sengaja dihapus atau dimatikan oleh peretas untuk menghilangkan barang bukti."*

---

## 💡 2. Analogi Sederhana untuk Memahami 4 Konsep Kunci (*Contoh Topik 1*)

### A. Apa itu *Ephemeral Container & Forensic Dilemma*?
* **Analogi Kamar Hotel Sewa Harian:**  
  Kontainer cloud seperti kamar hotel yang disewa beberapa jam lalu langsung dibersihkan total. Jika ada pencuri beraksi di dalam kamar lalu check-out, seluruh sidik jari di kamar sudah hilang dibersihkan (*ephemeral*). Forensik hard disk konvensional (*dead-box*) langsung lumpuh karena tidak ada jejak permanen.

### B. Apa itu *System Provenance Graph (SPG)*?
* **Analogi Rekaman CCTV Interaksi Kota:**  
  Bukan sekadar foto statis, melainkan peta alur yang mencatat siapa bertemu siapa: *"Proses A membaca File B, lalu membuka Jalur Jaringan C, lalu menyuntikkan kode ke Proses D"*. Semua hubungan sebab-akibat antar-proses digambarkan dalam bentuk grafik hubungan (*graph*).

### C. Mengapa menggunakan *Temporal Graph Attention Network (TGAT)*?
* **Analogi Detektif Sherlock Holmes yang Menyaring 10.000 Saksi:**  
  Setiap menit ada 1.000.000 log aktivitas normal di server (kebisingan log). Model TGAT bertindak seperti detektif cerdas yang membuang 99,9% aktivitas normal dan hanya menyorot 10 simpul relasi yang terbukti mencurigakan sebagai rangkaian serangan (*attack storyline*).

### D. Apa itu *Chain of Custody & Court-Admissible Report*?
* **Analogi Segel Plastik Bukti Kriminal Polisi:**  
  Setiap potongan bukti log dan graf kausalitas ditandatangani secara kriptografis (*hash checksum*) sehingga bukti digital tidak bisa dimanipulasi dan 100% sah diakui di pengadilan hukum.

---

## 🔍 3. Mengapa Riset Ini Sangat Penting & Bernilai Doktoral?

1. **Kebutuhan Mendesak di Era SPBE & IKN Kalimantan Timur:**
   * Pusat data nasional dan sistem pemerintahan daerah bermigrasi ke cloud kontainer. Serangan ransomware dan APT kini menyasar kontainer cloud yang minim jejak forensik.
2. **Kelemahan Riset Forensik Terdahulu:**
   * Riset forensik lama masih manual dan lambat (butuh waktu berhari-hari). Riset ini menghadirkan **rekonstruksi rantai serangan otonom dalam hitungan menit**.
3. **Peluang Publikasi Top-Tier Scopus Q1:**
   * Sangat diminati jurnal papan atas dunia seperti *IEEE Transactions on Information Forensics and Security (TIFS)* dan *Forensic Science International: Digital Investigation*.

---

## 🔬 4. Desain Eksperimen & Validasi (Sangat Feasible di Lab)

* **Lingkungan Eksperimen:**
  * Pengujian dilakukan pada klaster server Docker & Kubernetes di Laboratorium Komputer UNMUL.
  * Perekaman jejak kernel menggunakan *eBPF (Extended Berkeley Packet Filter)* yang sangat ringan (*overhead* CPU < 2%).
* **Skenario Evaluasi:**
  1. *Attack Injections:* Pengujian skenario serangan nyata (*Container Escape, Reverse Shell, Privilege Escalation, Ransomware Lateral Movement*).
  2. *Metrik Keberhasilan:* *Graph Reduction Rate (> 95%)*, *Attack Path Precision/Recall (> 98%)*, dan *Investigation Time Reduction (dari jam ke detik)*.

---

## 🏛️ 5. Keselarasan dengan Kurikulum Resmi PDIK UDINUS (55 SKS, 6 Semester)

* **Semester 1 (11 SKS):**
  * *Philosophy of Science* (2 SKS)
  * *Research Methodology* (3 SKS)
  * *Advanced Soft Computing* (3 SKS)
  * *Advanced Information Security / Digital Forensics* (3 SKS)
* **Semester 2 (10 SKS):**
  * *Scientific Writing* (2 SKS)
  * *Research Trends on Cybersecurity* (3 SKS)
  * **Disertasi I: International Conference** (5 SKS → Submit Paper IEEE Prosiding)
* **Semester 3 (7 SKS):**
  * **Disertasi II: Proposal Dissertation** (7 SKS → Sidang Ujian Proposal Disertasi)
  * *Progress Report 1*
* **Semester 4 (7 SKS):**
  * **Disertasi III: Scientific Publication 2** (7 SKS → Submit Paper Jurnal Scopus Q1/Q2, e.g., IEEE TIFS / FSI: Digital Investigation)
  * *Progress Report 2*
* **Semester 5 (7 SKS):**
  * **Disertasi IV: Completion Seminar** (7 SKS → Sidang Ujian Tertutup)
  * *Progress Report 3*
* **Semester 6 (6 SKS):**
  * **Disertasi V: Open Viva** (6 SKS → Sidang Ujian Terbuka / Promosi Doktor & Wisuda)

---

## 🎓 6. Cheat Sheet & Tanya-Jawab Taktis Wawancara Seleksi S3 PDIK UDINUS

---

### ❓ Pertanyaan 1: *"Pak Hario, mengapa Anda memilih topik Digital Forensik pada lingkungan Cloud Microservices untuk disertasi Anda?"*
> **Jawaban Taktis Pak Hario:**  
> *"Terima kasih Bapak/Ibu Penguji. Saat ini hampir seluruh infrastruktur SPBE, perbankan, dan enterprise telah bertransformasi ke arsitektur *Cloud-Native Microservices* berbasis kontainer. Namun, terdapat celah kritis dalam investigasi forensik: kontainer bersifat sementara (*ephemeral*). Saat penyerang berhasil masuk dan menghapus kontainer, metode forensik *dead-box* tradisional yang mengandalkan citra hard disk fisik menjadi lumpuh.  
> Melalui disertasi ini, saya mengusulkan **Kerangka Kerja Investigasi Forensik Digital Otonom Berbasis Deep Graph Learning**. Kami menangkap jejak kernel saat runtime menggunakan eBPF untuk membangun *System Provenance Graph*, lalu menggunakan *Temporal Graph Attention Network* untuk merekonstruksi seluruh kronologi serangan multi-tahap secara otomatis dan membuktikan bukti hukum yang sah."*

---

### ❓ Pertanyaan 2: *"Bagaimana Anda mengatasi masalah ledakan log (log explosion / dependency explosion) pada penelusuran graf forensik?"*
> **Jawaban Taktis Pak Hario:**  
> *"Masalah utama analisis provenance graph tradisional adalah jutaan simpul log normal yang membingungkan penyidik (*dependency explosion*).  
> Solusi kebaruan ilmiah (*novelty*) kami adalah mengintegrasikan arsitektur **Temporal Graph Attention Network (TGAT)** dengan algoritma *causal pruning*. Model ini mampu memfilter lebih dari 95% aktivitas rutin sistem operasi dan hanya mengisolasi subgraf kausalitas yang memiliki korelasi langsung dengan taktik serangan siber, sehingga waktu investigasi terpangkas dari hitungan hari menjadi hitungan menit."*

---

### ❓ Pertanyaan 3: *"Apa hubungan topik forensik ini dengan publikasi dan kepakaran Anda sebelumnya?"*
> **Jawaban Taktis Pak Hario:**  
> *"Topik ini merupakan integrasi linear dari rekam jejak riset saya:  
> 1. Pada tahun 2025, saya mempublikasikan riset infrastruktur CI/CD berbasis **Jenkins dan Docker**, sehingga saya sangat menguasai arsitektur kontainerisasi.  
> 2. Saya memiliki rekam jejak riset dalam pengujian penetrasi server (**Framework ISSAF dan Kali Linux**) serta pemantauan lalu lintas jaringan.  
> 3. Saya aktif meneliti arsitektur *Deep Learning* (termasuk *ConvNeXt, EfficientNet, dan AI Agents*). Disertasi ini mengawinkan keahlian infrastruktur cloud, keamanan siber, dan kecerdasan buatan menjadi kontribusi orisinal tingkat doktoral."*

---

### ❓ Pertanyaan 4: *"Dengan jabatan Anda sebagai Ketua APTIKOM Kaltim, apa dampak nyata hasil disertasi ini bagi masyarakat dan daerah?"*
> **Jawaban Taktis Pak Hario:**  
> *"Hasil disertasi ini akan menjadi standar kerangka kerja forensik insiden siber yang dapat diadopsi langsung oleh CSIRT (*Computer Security Incident Response Team*) instansi pemerintah daerah di Kalimantan Timur dan IKN, serta menjadi modul penguatan kurikulum keamanan siber nasional di lingkungan perguruan tinggi anggota APTIKOM."*
