# Product Requirement Document (PRD)
## Landing Page Pemasaran & Penjualan "Nugget Daun Kelor (Gluten-Free)"

---

## 1. Ringkasan Eksekutif & Tujuan Produk

### 1.1 Latar Belakang
Nugget Daun Kelor adalah produk *healthy frozen food* inovatif yang mengombinasikan protein hewani (ayam), nabati (tahu), tepung bebas gluten (*gluten-free*), serta daun kelor (*Moringa oleifera*) sebagai *superfood* kaya gizi untuk mendukung tumbuh kembang anak dan pencegahan stunting.

### 1.2 Tujuan Proyek (Goals)
* **Edukasi & Brand Awareness:** Memberikan pemahaman kepada konsumen (terutama orang tua) mengenai manfaat kelor, bahaya stunting, dan keuntungan makanan bebas gluten.
* **Konversi Penjualan Direct-to-Consumer (D2C):** Mendorong pengunjung landing page untuk segera melakukan pemesanan via WhatsApp checkout
* **Validasi Pasar:** Mengukur minat konsumen melalui rasio klik tombol (*Click-Through Rate* - CTR) dan leads yang masuk.

---

## 2. Target Pengguna (User Persona)

| Parameter | Persona Utama (Parent Buyer) | Persona Sekunder (Health Enthusiast) |
| :--- | :--- | :--- |
| **Nama Fiktif** | Bunda Rina (28–38 tahun) | Dimas (22–32 tahun) |
| **Profil** | Ibu bekerja/rumah tangga dengan anak balita/usia SD | Pekerja kantoran, pegiat hidup sehat/alergi gluten |
| **Pain Point** | Anak susah makan sayur (*picky eater*), khawatir gizi kurang/stunting, waktu masak terbatas. | Susah cari frozen food tanpa pengawet dan tanpa gluten yang enak & ramah lambung. |
| **Tujuan** | Memberikan lauk sehat, praktis, disukai anak, dan padat nutrisi. | Stok makanan sehat tinggi serat & protein yang cepat disajikan. |

---

## 3. Arsitektur Informasi & Alur Halaman (Page Structure)

Landing page dirancang dengan alur bercerita (*persuasive storytelling*) dengan pendekatan PAS (Problem - Agitate - Solution):

```
[1. Hero Section] 
       ↓
[2. Problem / Pain Points (Anak Picky Eater & Isu Gizi)]
       ↓
[3. Solution & Product Showcase (Nugget Kelor Gluten-Free)]
       ↓
[4. Manfaat & Kandungan Nutrisi (Fokus Stunting & Imunitas)]
       ↓
[5. Keunggulan Komparatif (Mengapa Produk Ini Berbeda)]
       ↓
6. Social Proof Testimoni
       ↓
7. Pricing 
       ↓
[9. FAQ (Pertanyaan Umum)]
       ↓
[10. Footer & Floating CTA Button (WhatsApp)]
```

---

## 4. Rincian Fitur & Konten Tiap Section

### Section 1: Hero Section (Above the Fold)
* **Headline:** "Solusi Anak Lahap Makan Sayur Tanpa Drama: Nugget Ayam Tahu Daun Kelor."
* **Sub-headline:** "Kaya zat besi & kalsium untuk cegah stunting, 100% tepung *gluten-free*, tanpa pengawet buatan. Gurihnya disukai si kecil!"
* **Visual:** Gambar/video hero berkualitas tinggi: nugget matang keemasan dipotong memperlihatkan tekstur lembut dengan bintik hijau kelor alami.
* **CTA Button:** 
  * Primary CTA: `Pesan Sekarang (Diskon Bundling)` -> *Scroll* ke Paket Harga / langsung buka WA template.
  * Secondary CTA: `Pelajari Manfaat` -> Smooth scroll ke Section Manfaat.
* **Trust Badges:** Logo Gluten-Free, Bahan Alami, Halal (Proses/Siap), Pengiriman Dingin Aman.

### Section 2: Identifikasi Masalah (Pain Points)
* Ilustrasi/kartun interaktif mengenai tantangan orang tua:
  * Anak selalu menolak sayuran hijau di piring.
  * Takut anak kurang gizi mikro dan risiko pertumbuhan terhambat (stunting).
  * Khawatir anak sensitif terhadap tepung terigu / gluten biasa.
  * Tidak punya banyak waktu menyiapkan makanan bergizi dari nol setiap pagi.

### Section 3: Solusi Produk (Product Intro)
* Deskripsi ringkas perpaduan 3 bahan utama:
  1. **Daun Kelor Pilihan:** Superfood kaya zat besi, vitamin C, dan antioksidan tanpa rasa pahit/langu.
  2. **Daging Ayam Segar & Tahu:** Paduan protein hewani dan nabati yang seimbang, lembut saat dikunyah.
  3. **Tepung Gluten-Free:** Menggunakan tepung alternatif lokal yang aman untuk pencernaan sensitif.

### Section 4: Manfaat Kesehatan & Kandungan Gizi
* Grid/Kartu fitur manfaat:
  * **Cegah Stunting & Anemia:** Tinggi zat besi dan asam folat untuk pembentukan sel darah merah dan kecerdasan anak.
  * **Tumbuh Kembang Tulang & Gigi:** Kalsium alami dari daun kelor dan tahu.
  * **Daya Tahan Tubuh Kuat:** Vitamin C dan antioksidan untuk melindungi si kecil dari infeksi musiman.
  * **Ramah Pencernaan:** Bebas gluten sehingga aman dan tidak memicu peradangan pada anak intoleran gluten.


### Section 5: Bukti Sosial / testimoni


### Section 9: FAQ (Frequently Asked Questions)
* *Apakah daun kelornya terasa pahit atau langu?* (Dijelaskan teknik pengolahan khusus kami sehingga rasa tetap disukai anak).
* *Berapa lama daya tahan produk?* (Tahan hingga 3 bulan di freezer, 24 jam di chiller, 12 jam di suhu ruang).
* *Bagaimana cara memasaknya?* (Bisa digoreng langsung, dipanggang oven, atau menggunakan air fryer tanpa minyak tambahan).
* *Apakah aman untuk anak mulai usia berapa?* (Aman untuk anak yang sudah terbiasa dengan tekstur finger food / di atas 1 tahun).

### Section 10: Footer & Sticky CTA
* Tombol Mengambang (Floating Action Button): Ikon WhatsApp di pojok kanan bawah bertuliskan "Tanya Gizi / Order Cepat".
* Footer: Kontak resmi, alamat dapur produksi, link media sosial, dan disclaimer kesehatan.

---

## 5. Kebutuhan Fungsional & Teknis

### 5.1 Fungsionalitas
* **WhatsApp Direct Lead Generator:**
  * Tombol CTA otomatis membuka WhatsApp dengan pesan yang sudah diformat:
    `"Halo Admin, saya tertarik memesan Paket [Nama Paket] Nugget Kelor Gluten-Free. Mohon info ketersediaan stok & ongkir ke [Nama Kota]."`
* **Responsive Design:** Optimal untuk perangkat mobile (minimal 80% trafik penjualan diperkirakan dari smartphone).
* **Fast Loading & Image Optimization:** Kompresi gambar format WebP agar waktu pemuatan halaman di bawah 2.5 detik pada koneksi 4G.

### 5.2 Kebutuhan Non-Fungsional
* **Keamanan:** Akses HTTPS/SSL aktif.
* **SEO-Friendly:** Meta title, meta description, alt text gambar yang menargetkan kata kunci: *"nugget daun kelor", "nugget anak gluten free", "makanan sehat pencegah stunting"*.
* **Aksesibilitas:** Kontras teks dan latar belakang yang mudah dibaca ibu-ibu dengan font sans-serif modern.

---

## 6. Metrik Keberhasilan (Success Metrics / KPIs)

1. **Conversion Rate (CR):** Minimal 3% - 5% dari total pengunjung unik menekan tombol CTA WhatsApp / Marketplace.
2. **Page Bounce Rate:** Di bawah 55%.
3. **Average Session Duration:** Lebih dari 1 menit 30 detik (menandakan pengunjung membaca edukasi gizi).
4. **Click-to-Chat Completion:** Minimal 60% klik WhatsApp berlanjut menjadi percakapan transaksi.

---
