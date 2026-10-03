# 🔮 Modul 09 — MAGIC & CLASS SYSTEM

> **Modul Sistem 09**
> Memuat sistem Class Karakter, Subclass/Spesialisasi, Pohon Skill per Rank (Rank F s/d SSS), serta Katalog Mantra Sihir Terstruktur per Tier (Tier 0 s/d Tier 5).

---

## 1. ENAM CLASS UTAMA & SPESIALISASI (*CORE CLASSES & SUBCLASSES*)

Setiap karakter yang dibuat wajib memilih salah satu Class Utama. Pada **Rank D (Level 11)**, karakter dapat memilih satu **Subclass / Spesialisasi** untuk membuka skill eksklusif.

### 1.1 WARRIOR (Ksatria / Pejuang)
- **Atribut Utama**: STR & CON
- **Base HP**: 12 + CON Mod / Level | **Base Mana**: 4 + INT Mod / Level | **Base Stamina**: 100 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *Berserker*: Fokus pada rage, damage fisik masif, dan ketahanan terhadap pingsan.
  2. *Guardian*: Fokus pada perlindungan perisai, taunt, armor class tinggi, dan memotong damage musuh.
  3. *Spellblade*: Memadukan pertarungan pedang dengan infusi sihir elemental (Fire/Ice/Lightning).
- **Pohon Skill Warrior**:
  - **Rank F (Level 1-5)**: *Heavy Strike* (Cost 10 Stamina: +1d6 Slashing damage), *Taunt* (Cost 5 Stamina: DC 12 WIS Save musuh dipaksa menyerang Warrior).
  - **Rank E (Level 6-10)**: *Shield Bash* (Cost 15 Stamina: 1d6 Bludgeoning + DC 13 STR Save or Stunned 1 turn), *Cleave* (Cost 20 Stamina: Mengubah serangan menjadi area 180 derajat).
  - **Rank D (Level 11-15)**: *Battle Cry* (Cost 25 Stamina: Memberikan +2 STR Modifier pada seluruh party selama 3 turn), *Unstoppable Charge* (Cost 30 Stamina: Menghantam target sejauh 10m, 3d8 Damage).
  - **Rank C (Level 16-25)**: *Whirlwind Slash* (Cost 40 Stamina: 4d8 Slashing area 5m radius), *Iron Body* (Cost 35 Stamina: Resistance terhadap damage fisik selama 2 turn).
  - **Rank B (Level 26-35)**: *Titan Slam* (Cost 50 Stamina: 6d10 Damage + merobohkan tanah/Knockdown area 10m).
  - **Rank A/S (Level 36+)**: *God-Slayer Slash* (Cost 80 Stamina: 12d10 True Damage, menembus Armor Class).

---

### 1.2 MAGE (Penyihir Elemen / Arcane)
- **Atribut Utama**: INT & DEX
- **Base HP**: 6 + CON Mod / Level | **Base Mana**: 20 + INT Mod / Level | **Base Stamina**: 80 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *Elementalist*: Spesialis ledakan destruktif Api, Es, dan Petir.
  2. *Necromancer*: Spesialis memanggil mayat hidup (*Undead*), sihir pembusukan, dan penyedot nyawa.
  3. *Chronomancer / Arcane Weaver*: Spesialis manipulasi waktu, wujud bayangan, dan crowd control.
- **Pohon Skill Mage**:
  - **Rank F (Level 1-5)**: *Arcane Bolt* (Cost 5 Mana: 1d8 Arcane damage), *Mana Shield* (Cost 8 Mana: Menyerap 15 Damage menggunakan Mana).
  - **Rank E (Level 6-10)**: *Blink* (Cost 12 Mana: Teleportasi sekejap sejauh 10 meter), *Elemental Blast* (Cost 15 Mana: 3d6 Damage Fire/Ice/Lightning).
  - **Rank D (Level 11-15)**: *Counterspell* (Cost 20 Mana: Batalkan sihir musuh Tier 1-2, D20 INT Check vs DC Spell), *Summon Minor Familiar* (Cost 25 Mana: Memanggil roh pelindung).
  - **Rank C (Level 16-25)**: *Chain Lightning* (Cost 45 Mana: 5d8 Lightning damage melompat ke 4 target), *Ice Nova* (Cost 40 Mana: 4d6 Freeze damage + Freeze 2 turn).
  - **Rank B (Level 26-35)**: *Meteor Strike* (Cost 80 Mana: 8d10 Fire/Bludgeoning damage area 15m radius).
  - **Rank A/S (Level 36+)**: *Singularity Collapse* (Cost 150 Mana: 15d10 Arcane Damage, menyedot seluruh musuh ke pusat gravitasi).

---

### 1.3 ROGUE (Pencuri / Pembunuh Bayaran)
- **Atribut Utama**: DEX & CHA
- **Base HP**: 8 + CON Mod / Level | **Base Mana**: 8 + INT Mod / Level | **Base Stamina**: 110 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *Assassin*: Fokus pada Critical Hit mematikan dari kegelapan dan racun mematikan.
  2. *Shadow Stalker*: Menggunakan sihir bayangan redup untuk melompati bayangan dan ilusi.
  3. *Swashbuckler*: Pertarungan jarak dekat lincah, feint, dan manipulasi koin/intimidasi.
- **Pohon Skill Rogue**:
  - **Rank F (Level 1-5)**: *Stealth* (Cost 5 Stamina: D20 DEX Check untuk tidak terlihat), *Sneak Attack* (Pasif: +2d6 damage jika menyerang dari belakang/striked unseen).
  - **Rank E (Level 6-10)**: *Poison Coating* (Cost 10 Stamina: Melumuri senjata dengan racun 2d4 Poison damage / turn), *Lockpicking & Trap Disarm* (D20 DEX Check).
  - **Rank D (Level 11-15)**: *Shadow Step* (Cost 15 Stamina: Melompat dari satu bayangan ke bayangan lain sejauh 12m), *Evasion* (Pasif: Mengurangi 50% damage dari serangan area DEX Save).
  - **Rank C (Level 16-25)**: *Assassinate* (Cost 30 Stamina: Critical Hit Otomatis jika musuh dalam kondisi Surprised, 6d6 Damage).
  - **Rank B (Level 26-35)**: *Thousand Daggers* (Cost 45 Stamina: 8d8 Piercing damage area kerucut 10m).
  - **Rank A/S (Level 36+)**: *Phantom Strike* (Cost 70 Stamina: 10d10 Damage, abaikan AC target).

---

### 1.4 CLERIC (Pendeta / Sihir Suci)
- **Atribut Utama**: WIS & CHA
- **Base HP**: 10 + CON Mod / Level | **Base Mana**: 16 + WIS Mod / Level | **Base Stamina**: 90 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *High Healer*: Pemulihan HP masif, kebal terhadap racun/kutukan, dan kebangkitan.
  2. *War Priest*: Menggunakan zirah berat, palu perang, dan sihir penghancur Undead.
  3. *Inquisitor*: Fokus pada pembongkaran kebohongan, penyegelan sihir hitam, dan punishment radiant.
- **Pohon Skill Cleric**:
  - **Rank F (Level 1-5)**: *Cure Wounds* (Cost 8 Mana: Pemulihan 2d4 + WIS Mod HP), *Sacred Flame* (Cost 5 Mana: 1d8 Radiant Damage).
  - **Rank E (Level 6-10)**: *Purify* (Cost 12 Mana: Hilangkan efek Poison/Disease/Bleeding), *Bless* (Cost 15 Mana: +1d4 pada D20 Roll seluruh party selama 3 turn).
  - **Rank D (Level 11-15)**: *Turn Undead* (Cost 20 Mana: D20 WIS vs DC, memaksa Undead kabur ketakutan), *Radiant Smite* (Cost 22 Mana: 3d8 Radiant damage).
  - **Rank C (Level 16-25)**: *Mass Heal* (Cost 45 Mana: Pemulihan 5d6 HP seluruh anggota party dalam radius 15m).
  - **Rank B (Level 26-35)**: *Divine Protection Aura* (Cost 60 Mana: Party menerima Resistance terhadap semua damage selama 3 turn).
  - **Rank A/S (Level 36+)**: *Resurrection* (Cost 150 Mana: Membangkitkan anggota party yang mati jika digunakan dalam waktu 1 jam kematian).

---

### 1.5 RANGER (Pemburu / Penjaga Hutan)
- **Atribut Utama**: DEX & WIS
- **Base HP**: 10 + CON Mod / Level | **Base Mana**: 10 + WIS Mod / Level | **Base Stamina**: 110 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *Beast Master*: Bertarung berdampingan dengan binatang buas (Frostwolf, Bear, Falcon).
  2. *Sharpshooter*: Pemanah jarak jauh akurasi tinggi menembus titik lemah musuh.
  3. *Warden of Nature*: Memadukan panah dengan jebakan alam dan sihir akar pembelit.
- **Pohon Skill Ranger**:
  - **Rank F (Level 1-5)**: *Precise Shot* (Cost 5 Stamina: +2 Hit Roll), *Tracking* (D20 WIS Check mendeteksi jejak kaki & aroma).
  - **Rank E (Level 6-10)**: *Entangling Trap* (Cost 10 Stamina: DC 13 DEX Save musuh terikat akar selama 2 turn), *Multi-Shot* (Cost 15 Stamina: Menembak 3 anak panah sekaligus ke 3 target berbeda).
  - **Rank D (Level 11-15)**: *Hunter's Mark* (Cost 12 Mana: +1d6 ekstra damage pada target yang ditandai), *Animal Companion Bond* (Memanggil hewan pendamping).
  - **Rank C (Level 16-25)**: *Rain of Arrows* (Cost 35 Stamina: 4d8 Piercing damage area 10m radius).
  - **Rank B (Level 26-35)**: *Sniper's Execution* (Cost 50 Stamina: Menembak dari jarak 100m, 8d8 Damage + Instant Kill jika HP target < 20%).
  - **Rank A/S (Level 36+)**: *Storm Arrow Volley* (Cost 80 Stamina: 12d8 Area damage, menghentikan seluruh gerakan musuh).

---

### 1.6 PALADIN (Pelindung Suci)
- **Atribut Utama**: STR & WIS
- **Base HP**: 12 + CON Mod / Level | **Base Mana**: 12 + WIS Mod / Level | **Base Stamina**: 100 + (CON Mod * 5)
- **Subclass (Pilihan Rank D)**:
  1. *Oath of Light*: Penjaga suci pemulih & pemantul damage kegelapan.
  2. *Oath of Vengeance*: Pemburu kejahatan dengan serangan Smite destruktif.
  3. *Oath of the Citadel*: Pelindung benteng kerajaan dengan aura ketahanan fisik mutlak.
- **Pohon Skill Paladin**:
  - **Rank F (Level 1-5)**: *Lay on Hands* (Cost 5 Mana: Pemulihan HP instan sebanding dengan Level * 5), *Divine Sense* (Mendeteksi Fiend/Undead).
  - **Rank E (Level 6-10)**: *Divine Smite* (Cost 15 Mana: +2d8 Radiant damage pada serangan melee), *Aura of Courage* (Pasif: Kebal terhadap efek Ketakutan/Fear).
  - **Rank D (Level 11-15)**: *Cleansing Touch* (Cost 20 Mana: Hilangkan semua efek debuff pada target), *Shield of Faith* (Cost 18 Mana: +2 AC selama 5 turn).
  - **Rank C (Level 16-25)**: *Holy Wrath* (Cost 40 Mana: 5d8 Radiant damage + Blindness selama 2 turn).
  - **Rank B (Level 26-35)**: *Aura of Protection* (Pasif: Rekan dalam radius 5m mendapat bonus Saving Throw sebanding WIS Mod).
  - **Rank A/S (Level 36+)**: *Avatar of Light* (Cost 100 Mana: Transformasi wujud malaikat selama 3 turn, HP pulih penuh, semua serangan +4d8 Radiant).

---

## 2. KATALOG MANTRA SIHIR TERSTRUKTUR (TIER 0 s/d TIER 5)

Sihir terbagi dalam 4 Aliran Utama: **Arcane/Elemental**, **Sacred/Divine**, **Shadow/Necromancy**, dan **Nature/Druidic**.

### 2.1 TIER 0 (Cantrip) — Syarat Stat >= 10 | Cost: 0 Mana
- **Fire Bolt (Arcane)**: Range 18m | D20 INT vs AC | Damage: 1d10 Fire.
- **Ray of Frost (Arcane)**: Range 18m | D20 INT vs AC | Damage: 1d8 Ice + Kurangi Speed target 3m.
- **Light / Spark (Sacred)**: Menciptakan cahaya terang radius 10m selama 1 jam.
- **Shadow Dagger (Shadow)**: Range 9m | D20 INT vs AC | Damage: 1d6 Necrotic.
- **Thorn Whip (Nature)**: Range 9m | D20 WIS vs AC | Damage: 1d6 Piercing + menarik musuh mendekat 3m.

---

### 2.2 TIER 1 — Syarat Stat >= 12 | Cost: 5–8 Mana
- **Magic Missile (Arcane)**: Range 30m | Auto-hit (Tanpa Roll) | 3 proyektil @ 1d4 + 1 Force Damage.
- **Burning Hands (Arcane)**: Area Kerucut 5m | DC 13 DEX Save | Damage: 3d6 Fire (Half damage jika lolos Save).
- **Cure Wounds (Sacred)**: Touch | Pemulihan: 2d8 + WIS Modifier HP.
- **Inflict Wounds (Shadow)**: Touch | D20 INT vs AC | Damage: 3d10 Necrotic.
- **Entangle (Nature)**: Area 6m radius | DC 12 STR Save | Target terikat tak bisa bergerak selama 2 turn.

---

### 2.3 TIER 2 — Syarat Stat >= 14 | Cost: 12–18 Mana
- **Fireball (Lesser) (Arcane)**: Range 24m | Area 5m radius | DC 14 DEX Save | Damage: 4d6 Fire.
- **Misty Step (Arcane)**: Self | Bonus Action | Teleportasi instan 9m ke area yang terlihat.
- **Lesser Restoration (Sacred)**: Touch | Menghilangkan status Poisoned, Blinded, Deafened, atau Paralyzed.
- **Ray of Enfeeblement (Shadow)**: Range 18m | D20 INT vs AC | Target mengalami potongan 50% damage fisik selama 3 turn.
- **Barkskin (Nature)**: Touch | Mengubah kulit target keras seperti kayu, set AC minimal menjadi 16.

---

### 2.4 TIER 3 — Syarat Stat >= 16 | Cost: 25–35 Mana
- **Lightning Bolt (Arcane)**: Garis lurus 30m | DC 15 DEX Save | Damage: 8d6 Lightning.
- **Haste (Arcane)**: Range 9m | Target mendapat +2 AC, double Speed, dan +1 ekstra Action per turn selama 1 menit.
- **Revivify (Sacred)**: Touch | Membangkitkan target yang baru mati kurang dari 1 menit (Kembali ke 1 HP).
- **Vampiric Touch (Shadow)**: Touch | D20 INT vs AC | Damage: 4d6 Necrotic (Mengekstrak 50% damage untuk memulihkan HP caster).
- **Call Lightning (Nature)**: Area 10m radius | DC 15 DEX Save | Damage: 4d10 Lightning per turn selama 3 turn.

---

### 2.5 TIER 4 — Syarat Stat >= 18 | Cost: 45–60 Mana
- **Ice Storm (Arcane)**: Area 12m radius | DC 16 DEX Save | Damage: 4d8 Ice + 4d6 Bludgeoning + Medan Es Licin.
- **Greater Restoration (Sacred)**: Touch | Menghilangkan kutukan tingkat tinggi, penalti stat permanen, atau Charm/Possession.
- **Blight (Shadow)**: Range 9m | DC 16 CON Save | Damage: 8d8 Necrotic (Sangat mematikan bagi makhluk tumbuhan).
- **Wall of Stone / Thorns (Nature)**: Range 18m | Menciptakan dinding batu/duri setinggi 6m panjang 15m (AC 18, HP 100).

---

### 2.6 TIER 5 (Ultimate) — Syarat Stat >= 20 | Cost: 80–120 Mana
- **Meteor Swarm (Arcane)**: Range 100m | Area 20m radius | DC 18 DEX Save | Damage: 12d10 Fire + 8d10 Bludgeoning (Mampu meratakan bangunan/benteng).
- **Divine Sunburst (Sacred)**: Area 15m radius | DC 18 CON Save | Damage: 10d10 Radiant + Blindness permanen bagi Undead/Fiend.
- **Finger of Death (Shadow)**: Range 18m | DC 18 CON Save | Damage: 12d8 + 30 Necrotic. Jika target mati, berubah menjadi Zombie permanen di bawah kendali caster.
- **Wrath of Nature (Nature)**: Area 30m radius | Seluruh pohon dan tanah menyerang musuh (6d10 Damage + Stun 2 turn).
