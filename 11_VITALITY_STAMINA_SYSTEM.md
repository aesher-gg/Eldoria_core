# 🫀 Modul 11 — VITALITY & STAMINA SYSTEM

> **Modul Sistem 11**
> Memuat mekanik Hit Points (HP), Stamina, Kelaparan, Pendarahan/Luka Perang, serta Rest & Recovery.

---

## 1. HIT POINTS (HP) & LUKA PERANG

- **Hit Points (HP)** merepresentasikan ketahanan hidup karakter dari kematian.
- **Kondisi HP 0**:
  - Karakter jatuh pingsan (*Unconscious / Bleeding Out*).
  - Karakter Wajib D20 Death Saving Throw setiap turn (DC 10).
  - 3x Sukses = Selamat/Stabil di 1 HP. 3x Gagal = Kematian Permanen (*Permadeath*).

### Status Luka (*Injuries*)
- **Luka Ringan (HP 50-75%)**: Tanpa penalti stat.
- **Luka Sedang (HP 25-49%)**: Penalti -2 pada semua D20 Roll.
- **Luka Berat (HP 1-24%)**: Penalti -4 pada semua D20 Roll, pergerakan berkurang 50%.
- **Pendarahan (*Bleeding*)**: Kehilangan 1d4 HP setiap turn sampai luka dibalut/disembuhkan sihir.

---

## 2. STAMINA & KELAPARAN (*HUNGER*)

- **Stamina**: Dipakai untuk aksi berat seperti sprint, menahan serangan zirah berat, dan perjalanan jauh.
- **Konsumsi Stamina**:
  - Perjalanan biasa: 10 Stamina / 2 Jam.
  - Pertarungan sengit: 5 Stamina / Turn.
- **Mekanik Kelaparan**:
  - Karakter membutuhkan 1 RansumMakanan/hari.
  - Jika tidak makan selama 1 hari: Max Stamina berkurang 20%.
  - Jika tidak makan selama 3 hari berturut-turut: Terkena status *Starving* (HP berkurang 5% per jam).

---

## 3. ISTIRAHAT & PEMULIHAN (*REST & RECOVERY*)

1. **Istirahat Pendek (*Short Rest*) - 1 Jam**:
   - Memulihkan Stamina sebesar 50%.
   - Memulihkan HP sebesar `1d6 + CON Modifier`.
2. **Istirahat Panjang (*Long Rest*) - 8 Jam**:
   - Memulihkan 100% Max HP, Mana, dan Stamina.
   - Menghilangkan status kelelahan (*Exhaustion*).
