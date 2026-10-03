# 🫀 Modul 11 — VITALITY, STAMINA & STATUS CONDITIONS SYSTEM

> **Modul Sistem 11**
> Memuat mekanik Hit Points (HP), Permadeath, Formula Stamina, Sistem Kelaparan & Kelelahan, serta Matriks Kondisi Status & Luka Perang terperinci.

---

## 1. HIT POINTS (HP), DEATH SAVES & PERMADEATH

Hit Points (HP) mengukur kapasitas fisik dan ketahanan hidup karakter dari kematian.

### 1.1 Kondisi HP 0 & Death Saving Throws
Ketika HP karakter mencapai **0**:
- Karakter langsung terkapar dan mengalami status **Unconscious / Bleeding Out**.
- Setiap giliran/turn, karakter **WAJIB** melempar **D20 Death Saving Throw** (tanpa modifier stat):
  - **Natural 20**: Karakter langsung pulih ke 1 HP dan sadar kembali.
  - **D20 >= 10**: Sukses 1 kali.
  - **D20 < 10**: Gagal 1 kali.
  - **Natural 1**: Dihitung sebagai 2 kali Gagal!
- **3x Sukses**: Kondisi karakter menjadi Stabil (0 HP, pingsan selama 1 jam, tidak lagi melempar Death Save kecuali menerima damage baru).
- **3x Gagal**: **Kematian Permanen (Permadeath)**. Karakter tewas secara naratif dan fisik.

### 1.2 Instant Death (Kematian Seketika)
Jika damage yang diterima melebihi sisa HP karakter ditambah Max HP-nya sekaligus (contoh: HP tersisa 5, menerima damage 55, sedangkan Max HP 40), karakter mengalami **Instant Death** tanpa kesempatan Death Save.

---

## 2. MATRIKS KONDISI STATUS & LUKA PERANG Terperinci

### 2.1 Pendarahan (*Bleeding Stages*)
- **Stage 1 (Luka Tergores)**: Kehilangan 1d4 HP di awal setiap turn. DC 10 Medicine Check / Bandage untuk menyembuhkan.
- **Stage 2 (Luka Terbuka)**: Kehilangan 2d6 HP per turn + -2 DEX Modifier. DC 13 Medicine Check.
- **Stage 3 (Arteri Putus)**: Kehilangan 3d8 HP per turn + Speed berkurang 50%. Wajib disembuhkan dengan Sihir Pemulih / Surgery DC 16.

### 2.2 Kelelahan (*Exhaustion Levels*)
Exhaustion terakumulasi dari kurang tidur, perjalanan tanpa istirahat, atau kelaparan ekstrem.

| Level Exhaustion | Efek Mekanis |
|---|---|
| **Level 1** | Disadvantage pada seluruh D20 Ability Checks (STR/DEX/CON/INT/WIS/CHA). |
| **Level 2** | Speed berkurang 50%. |
| **Level 3** | Disadvantage pada Attack Rolls dan Saving Throws. |
| **Level 4** | Max HP dan Max Stamina berkurang 50%. |
| **Level 5** | Speed berkurang menjadi 0 meter. |
| **Level 6** | **Kematian Seketika karena Gagal Organ**. |

### 2.3 Hypothermia (Paparan Dingin Ekstrem)
Dipicu oleh lingkungan dingin (Frostlands / Pegunungan Es) tanpa pakaian hangat.
- **Stage 1**: Menggigil hebat, Penalti -2 DEX Modifier, Stamina terkuras 10/jam.
- **Stage 2**: Frostbite pada jemari. Disadvantage pada serangan jarak jauh dan Lockpicking.
- **Stage 3**: Mati rasa fisik. Speed -50%, Max HP berkurang 25%.
- **Stage 4**: Pingsan beku. Terkena status Unconscious dan menerima 1d10 Cold Damage per jam.

### 2.4 Racun (*Poisoning Types*)
- **Neurotoxin**: DC 14 CON Save. Gagal = Terkena status Paralyzed selama 3 turn + 2d6 Poison Damage per turn.
- **Corrosive Poison**: DC 13 CON Save. Gagal = Zirah AC berkurang 2 poin + 3d6 Acid Damage.
- **Paralytic Venom**: DC 12 CON Save. Gagal = Speed 0 m, tidak dapat mengambil Action atau Bonus Action.

### 2.5 Kegilaan & Teror (*Madness & Terror*)
Dipicu oleh terpapar makhluk Eldritch/Abyssal di Underdark atau sihir kegelapan.
- **Stage 1 (Kecemasan / Panic)**: Disadvantage pada WIS Saving Throws.
- **Stage 2 (Halusinasi / Paranoia)**: D20 WIS Save setiap turn (DC 14). Gagal = menyerang sekutu terdekat.
- **Stage 3 (Gila Permanen)**: Karakter kehilangan kendali kesadaran, membutuhkan sihir *Greater Restoration*.

---

## 3. FORMULA STAMINA & KELAPARAN (*HUNGER & THIRST*)

### 3.1 Konsumsi & Over-Exertion Stamina
- **Max Stamina**: `100 + (CON Modifier * 5)`
- **Konsumsi Stamina**:
  - *Sprint / Lari Cepat*: 10 Stamina / Turn.
  - *Serangan Berat / Heavy Skill*: 10–30 Stamina / Aksi.
  - *Perjalanan Darat Lintas Wilayah*: 15 Stamina / 2 Jam.
- **Kondisi Stamina 0 (Exhausted)**:
  - Karakter tidak dapat melakukan Sprint, Dodge, atau Heavy Attack.
  - Menerima penalti -4 pada AC dan -2 pada Attack Roll.

### 3.2 Kelaparan & Dehidrasi (*Starvation & Dehydration*)
- **Kebutuhan Harian**: 1 Ransum Makanan + 2 Liter Air per hari.
- **Tanpa Makanan (1 Hari)**: Max Stamina berkurang 20%.
- **Tanpa Makanan (3 Hari)**: Terkena status Starving (Menerima 1 Level Exhaustion per hari).
- **Tanpa Air (1 Hari)**: Terkena 1 Level Exhaustion seketika + HP berkurang 10% per 12 jam.

---

## 4. ISTIRAHAT & PEMULIHAN (*REST & RECOVERY*)

1. **Short Rest (Istirahat Pendek — 1 Jam)**:
   - Memulihkan Stamina sebesar **50% Max Stamina**.
   - Memulihkan HP dengan melempar **Hit Dice** (sebanding Level) + CON Modifier.
2. **Long Rest (Istirahat Panjang — 8 Jam)**:
   - Harus dilakukan di tempat aman (Kemah/Kedai/Rumah).
   - Memulihkan **100% Max HP, Mana, dan Stamina**.
   - Menghilangkan **1 Level Exhaustion** (jika mengonsumsi makanan dan air yang cukup).
3. **Perawatan Medis vs Sihir Pemulih**:
   - **Bandaging / Surgery**: D20 Medicine Check vs DC 12 untuk menghentikan Bleeding Stage 1-2.
   - **Sihir Pemulih (Cure Wounds)**: Menghilangkan Bleeding seketika dan memulihkan HP langsung.
