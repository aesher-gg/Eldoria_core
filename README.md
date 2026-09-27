# 🏰 Eldoria Core — AI-Driven Persistent World RPG (Medieval Fantasy)

> **Eldoria Core** adalah engine Roleplay/RPG berbasis AI dengan dunia persisten bertema **Medieval Fantasy**, di mana seluruh data dunia, aturan, dan save state disimpan secara terstruktur di GitHub Repository.

---

## 🧭 CARA BERMAIN (UNTUK PEMAIN)

1. Buka sesi obrolan baru dengan AI Game Master (seperti **Qwen AI**, ChatGPT, Claude, dll.).
2. Tempelkan link file `INDEX.md` dari repository ini ke AI GM.
3. Sebutkan nama karakter Anda (atau buat karakter baru) dan lokasi awal Anda.
4. Nikmati petualangan simulasi dunia Medieval Fantasy yang imersif, adil, dan tanpa plot armor!

---

## 🏗️ ARSITEKTUR & ALUR KERJA SISTEM

```
GitHub Repository (Eldoria_core)
       ↓
INDEX.md (Gatekeeper & Bootstrapper)
       ↓
00_CORE_RULES_AI_GM.md + Modul Wilayah + Modul Sistem
       ↓
Qwen AI Game Master
       ↓
Narasi + NPC + Simulasi Dunia D20
       ↓
Pemain (Action Input)
       ↓
Runtime State (Sesi Roleplay)
       ↓
Checkpoint Save → Admin Verification → Official Save (players/<Karakter>.md)
```

---

## 📚 STRUKTUR MODUL DOKUMEN

- **`INDEX.md`**: Pintu masuk tunggal yang memuat Prosedur Bootstrap dan Direktori Modul.
- **`00_CORE_RULES_AI_GM.md`**: Aturan mutlak AI GM, format respon wajib, dan cheat-sheet formula.
- **`01_WORLD_OVERVIEW_AND_CAPITAL.md`**: Peta jarak benua & Ibu Kota Benteng Sentral (Central Citadel).
- **`02` s/d `07`**: Modul Wilayah (Frostlands, Sylvan Woods, Badlands, Sunken Coast, Underdark, Wilderness).
- **`08` s/d `13`, `38`**: Sistem Mekanik (Guild, Class & Sihir, Ekonomi, Vitalitas, Combat D20, Bestiary, Crafting).
- **`14` s/d `37`**: 24 File Faksi, Ordo Ksatria, Akademi Sihir, & Guild Individual.
- **`39` s/d `42`**: Modul Ekstensi Kustom (World Events, Spells, Factions, Abilities).
- **`players.md` & `players/`**: Katalog & Official Save file karakter pemain yang dikelola Admin.

---

## 🛡️ HUKUM & FITUR UTAMA

- **D20 System Standard**: Menggunakan kalkulasi dadu D20 transparan (`D20 Roll + Modifier vs DC/AC`).
- **Tanpa Plot Armor**: Kegagalan dan kematian bersifat nyata dan logis.
- **Persistent World**: Perkembangan karakter dan dunia dicatat secara resmi melalui Official Save.

---

*Selamat Menjelajahi Eldoria!*
