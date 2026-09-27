# ⚔️ Modul 12 — COMBAT SYSTEM

> **Modul Sistem 12**
> Memuat aturan sistem pertarungan berbasis D20, Initiative, Armor Class, Serangan, Damage Roll, Critical, dan Melarikan Diri.

---

## 1. STRUKTUR GILIRAN & INISIATIF (*INITIATIVE*)

Ketika pertarungan dimulai, seluruh peserta melempar dadu inisiatif untuk menentukan urutan giliran:
- **Initiative Roll**: `D20 + DEX Modifier`.
- Urutan giliran ditentukan dari nilai terbesar hingga terkecil.

---

## 2. METODE SERANGAN & ARMOR CLASS (AC)

Untuk menentukan apakah serangan fisik atau sihir jarak dekat berhasil mengenai sasaran:

### Formula Lemparan Serangan (*Attack Roll*):
`Total Attack Roll = D20 Roll + Stat Modifier + Proficiency Bonus`
- **Serangan Jarak Dekat (Melee)**: Menggunakan STR Modifier (atau DEX jika senjata *Finesse*).
- **Serangan Jarak Jauh (Ranged)**: Menggunakan DEX Modifier.
- **Serangan Sihir (Spell Attack)**: Menggunakan INT/WIS Modifier.

### Penentuan Hit vs Miss:
- Jika `Total Attack Roll >= Target Armor Class (AC)`, serangan **BERHASIL (HIT)**.
- Jika `Total Attack Roll < Target Armor Class (AC)`, serangan **GAGAL (MISS / PARRIED / BLOCKED)**.

---

## 3. KALKULASI DAMAGE & CRITICAL HIT

- **Damage Roll**: Dilempar sesuai tipe senjata/mantra + Stat Modifier.
  - *Misal: Pedang Panjang (1d8) + STR Modifier (+3) = 1d8 + 3 Physical Damage.*
- **Critical Hit (Natural 20 pada D20)**:
  - Serangan otomatis Berhasil (HIT).
  - Lempar jumlah dadu damage 2x lipat! *(Misal: 2d8 + 3).*
- **Critical Failure (Natural 1 pada D20)**:
  - Serangan otomatis Gagal, senjata berisiko terlepas/rusak.

---

## 4. TIPE DAMAGE & KETAHANAN (*RESISTANCE*)

- **Tipe Damage**: Physical (Slashing/Piercing/Bludgeoning), Fire, Ice, Lightning, Poison, Radiant, Necrotic, Arcane.
- **Resistance**: Mengurangi damage tipe terkait sebesar 50%.
- **Immunity**: Menolak 100% damage tipe terkait.
- **Vulnerability**: Menerima 2x lipat damage tipe terkait.

---

## 5. MEKANIK KABUR (*ESCAPE / RETREAT*)

Pemain dapat mencoba melarikan diri dari pertarungan pada gilirannya:
- **Escape Roll**: `D20 + DEX Modifier` vs `DC 12 + Monster DEX Modifier`.
- Berhasil = Karakter berhasil melarikan diri ke area aman terdekat.
- Gagal = Karakter kehilangan giliran dan musuh mendapatkan serangan bebas (*Opportunity Attack*).
