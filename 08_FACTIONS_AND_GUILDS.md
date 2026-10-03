# 🏰 Modul 08 — FACTIONS, GUILDS & REPUTATION SYSTEM

> **Modul Sistem 08**
> Memuat matriks reputasi faksi, hierarki Guild Petualang, mekanisme quest, pajak guild, serta profil mendalam organisasi lintas wilayah di Eldoria.

---

## 1. SISTEM MATRIKS REPUTASI FAKSI (*FACTION REPUTATION MATRIX*)

Sikap setiap faksi, ordo, dan organisasi terhadap petualang diukur dalam 6 Tingkat Reputasi. Reputasi bersifat dinamis dan dapat berubah berdasarkan tindakan, quest yang diselesaikan, atau pengkhianatan.

| Skor Reputasi | Tingkat Status | Perlakuan NPC & Faksi | Diskon / Penalti Harga | Akses Quest & Fasilitas |
|---|---|---|---|---|
| **-100 s/d -51** | **Hostile (Musuh Abadi)** | Diserang saat terlihat oleh penjaga/anggota faksi. Bounty dikeluarkan untuk menangkap/membunuh pemain. | Tidak ada perdagangan (Pembelian Ditolak) | Dilarang masuk wilayah/fasilitas faksi. |
| **-50 s/d -11** | **Unfriendly (Tercela)** | NPC curiga, dingin, dan menolak berbicara panjang. Penjaga mengawasi gerak-gerik pemain. | Mark-up Harga **+50%** | Quest faksi terkunci. Hanya tersedia quest berbahaya/hukuman. |
| **-10 s/d +10** | **Neutral (Netral)** | Perlakuan standar layaknya orang asing atau petualang biasa. | Harga Standar Katalog (**0%**) | Akses ke Quest Umum Papan Pengumuman. |
| **+11 s/d +50** | **Friendly (Bersahabat)** | NPC ramah, memberikan tips lokal, serta bersedia menyewakan kamar/fasilitas dasar. | Diskon **10%** | Akses ke Quest Khusus Faksi Tier E–D. |
| **+51 s/d +90** | **Honored (Dihormati)** | Disambut sebagai sekutu terpercaya. Penjaga memberikan hormat militer. | Diskon **20%** | Akses ke Fasilitas Rahasia, Pelatihan Skill Faksi Tier C–B, & Toko Eksklusif. |
| **+91 s/d +100** | **Exalted (Pahlawan Faksi)** | Dianggap pahlawan faksi. Memiliki suara dalam dewan faksi dan perlindungan militer penuh. | Diskon **30%** | Akses ke Artefak Pusaka Faksi, Misi Khusus Rank A–S, & Hak Menyewa Pasukan Faksi. |

### Mekanik Perubahan Reputasi:
- **Menyelesaikan Quest Faksi**: +5 s/d +20 Reputasi.
- **Membunuh Anggota/Penjaga Faksi**: -25 s/d -50 Reputasi (Mengurangi reputasi faksi sekutu sebesar -10).
- **Mencuri Aset Faksi**: -15 Reputasi jika ketahuan.
- **Menyumbangkan Logam Mulia / Artefak ke Faksi**: +1 Reputasi per 50 GP nilai barang.

---

## 2. GUILD PETUALANG LINTAS WILAYAH (*ADVENTURER GUILD SYSTEM*)

Guild Petualang adalah organisasi independen yang diakui oleh Kerajaan Eldoria dan seluruh pemerintah regional untuk mengelola tenaga petualang, keamanan sipil, serta perburuan monster.

### 2.1 Peringkat Petualang & Syarat Promosi

| Rank Petualang | Sebutan | Syarat Promosi (Level & Ujian) | Fasilitas & Batas Quest |
|---|---|---|---|
| **Rank F (Bronze)** | Pemula / Novice | Karakter Baru (Level 1–5). Tanpa ujian. | Quest Gathering, Perbasmian Pest/Goblin (Reward max 2 GP). |
| **Rank E (Silver)** | Apprentice | Level 6+, Selesaikan 5 Quest Rank F + Ujian Tanding D20 vs Instruktur Guild. | Quest Escort Lokal, Perburuan Beast (Reward max 10 GP). |
| **Rank D (Gold)** | Journeyman | Level 11+, Selesaikan 8 Quest Rank E + Laporan Investigasi Dungeon. | Quest Cleansing Crypt, Hutan Liar (Reward max 50 GP). |
| **Rank C (Platinum)**| Expert | Level 16+, Selesaikan 10 Quest Rank D + Penumpasan Sarang Monster Rank C. | Quest Sub-Dungeon, Escort Karavan Inter-Wilayah (Reward max 200 GP). |
| **Rank B (Diamond)** | Master | Level 26+, Rekomendasi 2 Guildmaster Regional + Penumpasan Monster Rank B. | Quest Pengawalan Pejabat High-Profile, Perburuan Boss (Reward max 1.000 GP). |
| **Rank A (Mythic)** | Grandmaster | Level 36+, Pembunuhan Monster Rank A + Kontribusi Krisis Regional. | Quest Ancamam Bencana Benua, Penjelajahan Underdark Abyss (Reward max 5.000 GP). |
| **Rank S / SSS** | Champion | Level 45+, Keputusan Dewan Agung Guild & Kerajaan. | Quest Pembasmian Dragon / Calamity / Archdemon (Reward Tak Terbatas). |

### 2.2 Jenis Kontrak & Papan Quest (*Quest Board Types*)
1. **Eradication (Pembasmian)**: Membasmi sejumlah monster liar yang mengganggu jalur perdagangan atau pemukiman.
2. **Escort (Pengawalan)**: Melindungi pedagang, bangsawan, atau sarjana dari serangan bandit/monster selama perjalanan inter-wilayah.
3. **Investigation (Investigasi)**: Menganalisis fenomena aneh, reruntuhan kuno, atau hilangnya warga desa.
4. **Bounty Hunt (Perburuan Buronan)**: Menangkap atau mengeksekusi kriminal, buronan berdarah dingin, atau penyihir hitam.
5. **Dungeon Raid (Penyerbuan Dungeon)**: Membersihkan seluruh lantai dungeon dan mengalahkan boss utama.

### 2.3 Biaya Administrasi & Layanan Guild
- **Pajak Hadiah Quest (*Guild Tax*)**: Guild memotong **10%** dari total hadiah quest untuk biaya administrasi dan asuransi.
- **Layanan Penilaian Loot (*Appraisal*)**: 5% dari nilai taksiran item sihir/kuno.
- **Layanan Penyimpanan Barang (*Vault Storage*)**: 1 SP per hari per peti inventaris.
- **Layanan Medis Darurat Guild**: Pemulihan HP/Luka Berat di klinik Guild dengan diskon 20% bagi anggota Rank D ke atas.

---

## 3. ORGANISASI LINTAS WILAYAH UTAMA

### 3.1 Persaudaraan Raven Eye (Jaringan Informasi & Broker Rahasia)
- **Fungsi**: Menjual rahasia politik, peta rahasia dungeon, identitas buronan, dan rumor pergerakan faksi.
- **Struktur**: Dipimpin oleh *Shadow Broker*. Operatifnya tersebar sebagai pengemis, pelayan kedai, dan pedagang barang antik.
- **Mekanik Layanan**:
  - *Rumor Lokal Ringan*: 1 GP.
  - *Informasi Rahasia Faksi Tier C*: 25 GP.
  - *Peta Lokasi Harta Karun/Dungeon Tersembunyi*: 100 GP – 500 GP.
  - *Identitas Rahasia NPC/Penyusup*: 200 GP.

### 3.2 Bank Sentral Ironbank (Lembaga Keuangan Benua)
- **Fungsi**: Penyimpanan deposit emas murni, penerbitan surat hutang (*Promissory Notes*), peminjaman modal, dan penagihan hutang.
- **Struktur**: Dikelola oleh para Kurator Dwarf dan Bankers berpengalaman di Mid Citadel.
- **Mekanik Layanan**:
  - *Bunga Deposit*: +2% per bulan untuk tabungan di atas 500 GP.
  - *Pinjaman Modal*: Bunga 10% per bulan. Jika gagal bayar dalam 3 bulan, Ironbank mengeluarkan *Bounty Hunter Contract* Rank A untuk menyita seluruh aset dan organ sihir pemain.
  - *Surat Kredit Inter-Wilayah*: Memungkinkan pemain membawa modal dalam bentuk kertas tanpa beban berat koin (Biaya admin 2%).

### 3.3 Guild Pencuri Nightshade (Sindikat Pasar Gelap & Assassination)
- **Fungsi**: Perdagangan barang curian (*Fencing*), racun mematikan, pemalsuan dokumen, dan jasa pembunuhan bayaran.
- **Lokasi Utama**: Lorong rahasia di bawah Lower Citadel dan jaringan selokan kota-kota besar.
- **Mekanik Layanan**:
  - *Penampungan Barang Curian (Fencing)*: Membeli barang hasil curian dengan harga 50%–70% dari nilai asli katalog.
  - *Pemalsuan Dokumen Paspor/Surat Bebas Tembok*: 15 GP.
  - *Kontrak Kontra-Pembunuhan*: 100 GP s/d 2.000 GP tergantung Rank target.

### 3.4 Ordo Mercenary Bloodbound (Tentara Bayaran Profesional)
- **Fungsi**: Menyediakan prajurit tempur, pengawal pribadi elit, dan pasukan mengepung benteng untuk siapa saja yang sanggup membayar.
- **Aturan Loyalitas**: Sangat memegang teguh *Contract of Blood*. Tidak akan mengkhianati majikan selama kontrak berlangsung, kecuali majikan gagal membayar upah.
- **Biaya Penyewaan Pasukan**:
  - *Mercenary Veteran (Rank D)*: 3 GP / hari.
  - *Mercenary Commander (Rank B)*: 25 GP / hari.
  - *Pasukan Reguler (10 Prajurit Rank E)*: 20 GP / hari.

### 3.5 Lingkaran Alkimia Hermetic (Konsorsium Alkimis & Peneliti Exotik)
- **Fungsi**: Riset alkimia murni, monopoli bahan herbal langka, dan penjualan resep ramuan tingkat tinggi.
- **Fasilitas**: Laboratorium steril di pelbagai kota besar.
- **Mekanik Layanan**:
  - Pembelian bahan ramuan Tier C–A yang tidak dijual di pasar biasa.
  - *Transmutasi Logam*: Mengubah 10 kg Lead/Besi menjadi 1 kg Perak/Emas (Biaya sihir & reagen: 50 GP per proses).
