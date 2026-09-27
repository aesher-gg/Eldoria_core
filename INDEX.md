# 🧭 Eldoria World — INDEX

> **Ini adalah SATU-SATUNYA link/file yang perlu ditempel pemain di setiap sesi.**
> Semua modul lain (aturan, wilayah, sistem, data karakter) dijangkau AI secara otomatis dari sini lewat `web_fetch`/browsing atau pembacaan file, sesuai kondisi yang sedang terjadi di roleplay.
>
> **Untuk AI:** baca seluruh file ini dulu sampai habis, lalu jalankan **Prosedur Bootstrap** di §0 SEBELUM menulis balasan apa pun ke pemain. Jangan menjawab dari ingatan/memori bebas — dunia ini hanya sah kalau datanya berasal dari modul-modul yang ditautkan di sini.

---

## 0. Prosedur Bootstrap (WAJIB, Urutan Ini Persis)

1. **Fetch `00_CORE_RULES_AI_GM.md`** (link di tabel §1) — WAJIB pertama, tanpa kecuali. File itu berisi aturan mutlak, anti-cheat, aturan Sesi Roleplay (Tanpa Batas), sistem D20/Medieval RPG, dan format respon wajib yang mengikat seluruh sesi. Jangan lanjut ke langkah berikutnya sebelum ini selesai dibaca.
2. **Inisialisasi Indikator Step**:
   - Setiap balasan AI GM wajib mencantumkan header: `🏰 Waktu Dunia Eldoria | 💬 Step: Tanpa Batas`.
   - Sesi berjalan tanpa batasan jumlah step, memberikan kebebasan penuh bagi pemain untuk terus bermain tanpa pembekuan sesi.
3. **Cek pesan pemain** untuk menentukan identitas & titik mulai karakter — ada 3 kemungkinan, jangan disamaratakan:
   - **(a) Karakter terdaftar, baru pertama kali dimainkan atau memulai sesi baru dari save repo** (nama cocok entri di `players.md`, TIDAK ada blok "Profil Karakter" yang ditempel/riwayat sebelumnya) ATAU **pemain menanyakan tentang karakter/player lain** → fetch `players.md` (link §1) atau langsung fetch file RAW karakter individual yang dituju di `players/<Nama_Karakter>.md` (misal: `players/<Nama_Karakter>.md`), muat data awalnya sebagai **titik mulai** narasi atau referensi informasi. `players.md` adalah katalog data awal; file individual `players/` adalah official save yang dikelola Admin.
   - **(b) Melanjutkan karakter yang sudah pernah dimainkan di dalam chat yang sama** → runtime state tetap digunakan sebagai state aktif, **KECUALI** pemain memulai ulang dari Official Save, meminta `[STATE REFRESH]`, atau memberikan prompt bootstrap/sesi baru. Dalam kondisi tersebut, WAJIB fetch Official Save terbaru `players/<Nama_Karakter>.md` dan gunakan data terbaru itu untuk menggantikan field runtime lama yang bertentangan. Riwayat chat lama tidak boleh mengalahkan Official Save terbaru.
   - **(c) Karakter benar-benar baru** (nama tidak ada di `players.md` maupun riwayat manapun) → perlakukan sebagai karakter baru custom sesuai `00_CORE_RULES_AI_GM.md` §1.6, minta Nama, Class, & Lokasi Awal.
4. **Tentukan lokasi karakter** (dari file karakter individual di `players/` atau dari input baru pemain), lalu fetch modul wilayah yang sesuai (`01`–`07`) dari tabel §1.
5. **Fetch `39_CUSTOM_EVENTS.md`** — cek apakah ada event aktif yang sedang berlangsung di dunia. Jika ada, pastikan event itu terasa dalam narasi (suasana, dialog NPC, kejadian acak).
6. **Mulai sesi** mengikuti format respon wajib di `00` dengan header `Step: Tanpa Batas`.
7. **Selama sesi berlangsung**, fetch modul tambahan secara dinamis begitu kondisinya muncul — lihat tabel pemicu di §2. Jangan fetch banyak file sekaligus di awal; itu boros token dan bertentangan dengan tujuan modularitas sistem ini.
8. Jika sebuah link gagal diakses (404/error), beri tahu pemain bahwa file itu mungkin belum ter-upload atau nama filenya salah — **jangan mengarang isinya**.

---

## 1. Direktori Lengkap Seluruh Modul

| Kode | File | Path / Link RAW | Isi Singkat |
|---|---|---|---|
| 00 | `00_CORE_RULES_AI_GM.md` | `00_CORE_RULES_AI_GM.md` | Aturan mutlak, anti-cheat, format respon wajib, sistem D20/RPG — **selalu difetch pertama** |
| 👤 | `players.md` | `players.md` | Katalog **data AWAL** karakter (statis, dikelola admin) — memuat daftar karakter resmi |
| 01 | `01_WORLD_OVERVIEW_AND_CAPITAL.md` | `01_WORLD_OVERVIEW_AND_CAPITAL.md` | Peta jarak dunia Eldoria & Ibu Kota Benteng Sentral (Central Citadel) |
| 02 | `02_FROSTLANDS.md` | `02_FROSTLANDS.md` | Frostlands: Pegunungan Es Utara, benteng perbatasan, klan barbar, & monster es |
| 03 | `03_SYLVAN_WOODS.md` | `03_SYLVAN_WOODS.md` | Sylvan Woods: Hutan Kuno Elven, kota di atas pohon, sanctum sihir, & roh alam |
| 04 | `04_BADLANDS.md` | `04_BADLANDS.md` | Badlands: Gurun gurun, ngarai raksasa, reruntuhan peradaban kuno, & pemburu harta |
| 05 | `05_SUNKEN_COAST.md` | `05_SUNKEN_COAST.md` | Sunken Coast: Kota pelabuhan, benteng bajak laut, pelayaran, & bahaya laut |
| 06 | `06_UNDERDARK.md` | `06_UNDERDARK.md` | Underdark: Dunia bawah tanah, gua kristal, ras bayangan, & monster subterranean |
| 07 | `07_WILDERNESS_BORDER.md` | `07_WILDERNESS_BORDER.md` | Wilderness & Borderland: Pos terdepan perbatasan, zona liar, & dungeon terbuka |
| 08 | `08_FACTIONS_AND_GUILDS.md` | `08_FACTIONS_AND_GUILDS.md` | Guild Petualang Lintas Wilayah, Broker Informasi, Rumah Lelang, & Tentara Bayaran |
| 09 | `09_MAGIC_AND_CLASS_SYSTEM.md` | `09_MAGIC_AND_CLASS_SYSTEM.md` | Sistem Class (F-SSS), Rintisan Sihir/Skills, Mana, Perkembangan Level, & Specialization |
| 10 | `10_ECONOMY_SYSTEM.md` | `10_ECONOMY_SYSTEM.md` | Mata uang (Gold/Silver/Copper), grade perlengkapan, harga aset & jasa |
| 11 | `11_VITALITY_STAMINA_SYSTEM.md` | `11_VITALITY_STAMINA_SYSTEM.md` | Formula HP, Stamina, Kelaparan, Pendarahan/Luka Perang, & Pemulihan |
| 12 | `12_COMBAT_SYSTEM.md` | `12_COMBAT_SYSTEM.md` | D20 Dice Roll, initiative, AC (Armor Class), Damage Roll, Critical, & Escape |
| 13 | `13_BESTIARY.md` | `13_BESTIARY.md` | Bestiary: Dragon, Beast, Undead, Fiend, Construct, Ambush rate & Loot Table |
| 38 | `38_CRAFTING_HERBALISM_SYSTEM.md` | `38_CRAFTING_HERBALISM_SYSTEM.md` | Alkimia, Ramuan, Blacksmithing, Pengumpulan Herbal, & Resep Peralatan |
| 14–37 | *(24 file ordo/guild/faksi individual)* | — | Lihat **§1a** di bawah untuk daftar lengkap per-file — **JANGAN** fetch semuanya sekaligus |
| 39 | `39_CUSTOM_EVENTS.md` | `39_CUSTOM_EVENTS.md` | **Event khusus & peristiwa dunia** — diisi Admin, AI wajib cek di awal sesi |
| 40 | `40_CUSTOM_SPELLS.md` | `40_CUSTOM_SPELLS.md` | **Sihir/Mantra Kustom** — buatan pemain/Admin, dicatat di sini agar resmi |
| 41 | `41_CUSTOM_FACTIONS.md` | `41_CUSTOM_FACTIONS.md` | **Guild/Faksi Kustom** — buatan pemain/Admin, dicatat di sini agar resmi |
| 42 | `42_CUSTOM_ABILITIES.md` | `42_CUSTOM_ABILITIES.md` | **Kemampuan/Skill Kustom** — buatan pemain/Admin, dicatat di sini agar resmi |
| — | `README.md` | `README.md` | Dokumentasi setup untuk manusia (jarang perlu difetch AI) |

### 1a. Direktori Ordo, Guild, Akademi & Faksi (24 File Individual)

> Setiap faksi/ordo/akademi punya **file sendiri**, lengkap dengan hierarki, fasilitas, artefak pusaka, kurikulum sihir/teknik bertingkat, hukum faksi, relasi, dan rahasia internal. **Fetch HANYA** link file yang relevan dengan situasi saat ini — jangan fetch banyak sekaligus.

**Benteng Sentral & Kerajaan Eldoria**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Ordo Ksatria Royal Sun | `14_ORDO_ROYAL_SUN.md` |
| Akademi Sihir Highspire | `15_AKADEMI_HIGHSPIRE.md` |
| Guild Petualang Pusat | `16_GUILD_PETUALANG_PUSAT.md` |
| Kuil Lichtbringer | `17_KUIL_LICHTBRINGER.md` |
| Perhimpunan Pandai Besi Steelforge | `18_PERHIMPUNAN_STEELFORGE.md` |

**Frostlands (Utara)**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Ksatria Frostguard | `19_KSATRIA_FROSTGUARD.md` |
| Klan Shaman Winterglen | `20_KLAN_WINTERGLEN.md` |

**Sylvan Woods (Timur)**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Konsil Elven Silvermoon | `21_KONSIL_SILVERMOON.md` |
| Lingkaran Druid Greenheart | `22_LINGKARAN_GREENHEART.md` |
| Pemburu Wildstride | `23_PEMBURU_WILDSTRIDE.md` |
| Ordo Shadowleaf | `24_ORDO_SHADOWLEAF.md` |
| Biara Mossveil | `25_BIARA_MOSSVEIL.md` |

**Sunken Coast (Selatan)**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Aliansi Armada Tidal | `26_ALIANSI_TIDAL.md` |
| Sindikat Pelabuhan Ironhook | `27_SINDIKAT_IRONHOOK.md` |

**Badlands (Barat)**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Konsorsium Pedagang Ashfang | `28_KONSORSIUM_ASHFANG.md` |
| Ordo Sunfire Templar | `29_TEMPLAR_SUNFIRE.md` |
| Perhimpunan Arkeolog Runeward | `30_RUNEWARD_SOCIETY.md` |

**Underdark (Bawah Tanah)**
| Faksi / Ordo | Path / Link RAW |
|---|---|
| Enclave Shadowspire | `31_ENCLAVE_SHADOWSPIRE.md` |
| Perhimpunan Obsidian | `32_PERHIMPUNAN_OBSIDIAN.md` |

**Lintas Wilayah & Rahasia**
| Organisasi | Path / Link RAW |
|---|---|
| Persaudaraan Raven Eye (Info Broker) | `33_RAVEN_EYE_BROKERS.md` |
| Bank Sentral Ironbank | `34_BANK_IRONBANK.md` |
| Guild Pencuri Nightshade | `35_GUILD_NIGHTSHADE.md` |
| Ordo Mercenary Bloodbound | `36_BLOODBOUND_MERCENARIES.md` |
| Lingkaran Alkimia Hermetic | `37_LINGKARAN_HERMETIC.md` |

---

## 2. Alur Navigasi Otomatis (Trigger → Modul yang Difetch)

| Trigger dalam Roleplay | Modul yang Difetch | Catatan |
|---|---|---|
| Awal sesi (selalu) | `00_CORE_RULES_AI_GM.md` | Wajib pertama, lihat §0 |
| Awal sesi (setelah Bootstrap selesai) | `39_CUSTOM_EVENTS.md` | Cek apakah ada event aktif yang memengaruhi dunia |
| Karakter terdaftar di `players.md` OR pemain menanyakan informasi karakter/player lain | `players.md` dan/atau `players/<Nama_Karakter>.md` | Muat/fetch data karakter dari link individual sebagai titik mulai atau referensi |
| Melanjutkan karakter yang sudah pernah dimainkan | `players/<Nama_Karakter>.md` jika sesi baru/reset/refresh diminta | Runtime state boleh dipakai selama sesi berlangsung. Untuk sesi baru, reset, atau `[STATE REFRESH]`, **WAJIB fetch Official Save terbaru** |
| Karakter benar-benar baru (tidak ada di `players.md`) | — | Ikuti `00` §1.6: minta Nama + Class + Lokasi Awal |
| Karakter berada/menuju Frostlands | `02_FROSTLANDS.md` | Pegunungan es & klan utara |
| Karakter berada/menuju Sylvan Woods | `03_SYLVAN_WOODS.md` | Hutan kuno & sanctum sihir |
| Karakter berada/menuju Badlands | `04_BADLANDS.md` | Gurun, ngarai & reruntuhan |
| Karakter berada/menuju Sunken Coast | `05_SUNKEN_COAST.md` | Pelabuhan & perairan selatan |
| Karakter berada/menuju Underdark | `06_UNDERDARK.md` | Kedalaman gua & dunia bawah tanah |
| Karakter berada/menuju Perbatasan / Wilderness | `07_WILDERNESS_BORDER.md` | Pos terdepan & dungeon liar |
| Butuh konteks Ibu Kota Benteng Sentral / peta jarak dunia | `01_WORLD_OVERVIEW_AND_CAPITAL.md` | |
| Bertemu Guild Petualang / Broker / Tentara Bayaran | `08_FACTIONS_AND_GUILDS.md` | |
| Naik Level / Alokasi Skill / Cek Spell & Class Tier | `09_MAGIC_AND_CLASS_SYSTEM.md` | |
| Pemain menyebut Mantra/Sihir yang tidak ada di `09` | `40_CUSTOM_SPELLS.md` | Cek apakah Mantra itu sudah dicatat Admin |
| Transaksi, tawar-menawar, cek harga barang/jasa/aset | `10_ECONOMY_SYSTEM.md` | Gold, Silver, Copper |
| Perlu hitung detail HP / Stamina / Luka / Rest | `11_VITALITY_STAMINA_SYSTEM.md` | Formula dasarnya ada ringkas di `00` |
| Pertarungan resmi dimulai (D20 Roll, Initiative, Damage) | `12_COMBAT_SYSTEM.md` | |
| Lawan monster/beast/undead liar, perjalanan lewat zona bahaya | `13_BESTIARY.md` | Dipakai bersamaan dengan `12` |
| Alkimia, ramuan, blacksmithing, meracik herbal | `38_CRAFTING_HERBALISM_SYSTEM.md` | |
| Karakter berinteraksi dengan Faksi/Ordo/Akademi spesifik | Fetch langsung dari path di §1a | Pilih HANYA satu file yang sesuai dengan faksi yang sedang berinteraksi |
| Pemain menyebut faksi yang tidak ada di `14`–`37` | `41_CUSTOM_FACTIONS.md` | Cek apakah faksi itu sudah dicatat Admin di file kustom |
| Pemain menyebut/mengklaim ability kustom | `42_CUSTOM_ABILITIES.md` | Cek apakah skill itu sudah dicatat Admin di file kustom |
| Pemain minta bantuan setup GitHub / cara pakai | `README.md` | Ini file untuk manusia, sampaikan isinya ke pemain |

---

## 3. Cara Kerja `players.md` & Folder `players/` (Manajemen Save File Karakter oleh Admin)

`players.md` adalah katalog data awal. File individual di folder `players/` menjadi **official player save** yang dikelola Admin. Keduanya hanya boleh diubah oleh Admin berdasarkan checkpoint/profil terakhir yang telah diverifikasi.

**Alur pemakaian & Sesi Baru:**
1. Pemain cukup menyebutkan nama karakternya (misal: `Arthur`) saat membuka chat/sesi baru.
2. AI GM **WAJIB men-fetch file `players/<Nama_Karakter>.md` terbaru** sebagai Official Save saat sesi baru, bootstrap baru, reset, atau `[STATE REFRESH]`.
3. Seluruh data di Official Save terbaru dimuat sebagai starting state.
4. Selama sesi berlangsung, runtime state hidup di percakapan melalui blok Profil Karakter dan checkpoint, tetapi **runtime tidak boleh mengalahkan Official Save terbaru setelah refresh/reset**.
5. Jika terjadi konflik, tandai data lama sebagai `STALE` dan gunakan data Official Save terbaru.
6. Pemain dapat meminta checkpoint; checkpoint dikirim kepada Admin untuk diverifikasi.
7. Setelah verifikasi, Admin memperbarui official save `players/<Nama_Karakter>.md`.

---

## 4. Batasan Penting yang Harus Diketahui Pemain

- `players.md` adalah katalog data awal; file individual `players/<Nama_Karakter>.md` adalah **official save** yang dikelola Admin.
- **AI GM/Qwen tidak menulis langsung ke GitHub.** Runtime state tetap berada di sesi sampai dibuat checkpoint.
- Alur save resmi: **Runtime State → Checkpoint → Admin Verification → Official Player Save**.
- Hanya Admin yang boleh memperbarui `players.md` dan file `players/` berdasarkan checkpoint yang diverifikasi.
- **File `39_CUSTOM_EVENTS.md`, `40_CUSTOM_SPELLS.md`, `41_CUSTOM_FACTIONS.md`, dan `42_CUSTOM_ABILITIES.md` dikelola sepenuhnya oleh Admin.** AI tidak boleh mengedit, menambah, atau menghapus isinya — hanya membaca dan menggunakan data yang sudah ada di dalamnya.

---

## 5. Ringkasan Dunia Eldoria (satu baris, detail penuh di `01`)

High-Medieval Fantasy · D20 System Rules · Magic & Sword Realism — 7 wilayah besar (Benteng Sentral, Frostlands, Sylvan Woods, Badlands, Sunken Coast, Underdark, Perbatasan), 9 Class Rank (F s/d SSS), Tanpa plot armor, semua mekanik tunduk formula anti-cheat di modul `09`–`13`.
