# ⚔️ Modul 12 — COMBAT & TACTICAL SYSTEM

> **Modul Sistem 12**
> Memuat aturan sistem pertarungan D20, Initiative, Surprise Round, Cover System, Combat Maneuvers, Critical Fumbles, serta Bahaya Lingkungan Pertarungan.

---

## 1. INISIATIF & SURPRISE ROUND

Pertarungan berjalan dalam putaran bertahap (*Turn-Based Round*) di mana 1 Round direpresentasikan sebagai 6 detik waktu dunia.

### 1.1 Initiative Roll
Setiap peserta pertempuran melempar:
`Initiative Roll = D20 + DEX Modifier`
Urutan giliran berjalan dari nilai terbesar hingga terkecil. Jika ada nilai seri, karakter dengan DEX Score lebih tinggi melangkah lebih dulu.

### 1.2 Surprise Round (Serangan Kejutan)
Jika satu pihak berhasil melakukan pendeteksian tersembunyi (*Stealth Check vs WIS Passive Perception*) sebelum pertarungan dimulai:
- Pihak yang terkejut (*Surprised*) **tidak dapat mengambil Action, Movement, atau Reaction** pada Round pertama pertarungan.

---

## 2. ARMOR CLASS (AC), ATTACK ROLL & SYSTEM COVER

### 2.1 Attack Roll vs Armor Class
`Total Attack Roll = D20 + Stat Modifier (STR/DEX/INT/WIS) + Proficiency Bonus`
- Jika `Total Attack Roll >= Target AC`: **HIT (Serangan Berhasil)**.
- Jika `Total Attack Roll < Target AC`: **MISS / PARRIED / BLOCKED**.

### 2.2 Cover System (Perlindungan Medan)
Karakter yang bersembunyi di balik objek lingkungan mendapatkan bonus AC dan DEX Saving Throw:
- **Half Cover (Setengah Perlindungan — Tembok Rendah/Pohon)**: **+2 AC** & **+2 DEX Saving Throw**.
- **Three-Quarter Cover (Tiga Perempat Perlindungan — Pintu Barikade/Celah Tembok)**: **+5 AC** & **+5 DEX Saving Throw**.
- **Total Cover (Perlindungan Penuh)**: Tidak dapat ditargetkan langsung oleh serangan fisik atau sihir jarak jauh.

---

## 3. COMBAT MANEUVERS (MANUVER PERTARUNGAN TAKTIS)

Setiap karakter dapat menggunakan Action mereka untuk mengeksekusi manuver taktis berikut:

1. **Grapple (Penyergapan / Cengkeraman)**:
   - *Check*: Contested **D20 STR (Athletics)** Player vs **D20 STR/DEX** Target.
   - *Berhasil*: Target terkena status **Grappled** (Speed menjadi 0m, Disadvantage pada serangan).
2. **Disarm (Melucuti Senjata)**:
   - *Check*: Player melempar **Attack Roll** vs Target **STR/DEX Saving Throw**.
   - *Berhasil*: Senjata target terlempar sejauh 3 meter ke tanah.
3. **Shove / Knockdown (Mendorong / Merobohkan)**:
   - *Check*: Contested **D20 STR** Player vs **D20 STR/DEX** Target.
   - *Berhasil*: Target terdorong mundur 3 meter ATAU jatuh telungkup (**Prone** — Serangan melee ke target Prone mendapat Advantage).
4. **Parry & Riposte (Tangkisan & Serangan Balas)**:
   - *Reaction*: Ketika diserang melee, lempar **D20 + DEX Mod**. Jika hasil > Attack Roll musuh, serangan ditangkis penuh dan pemain dapat melancarkan 1x serangan balasan.
5. **Feint (Tipuan Serangan)**:
   - *Check*: Contested **D20 CHA (Deception)** Player vs **D20 WIS (Insight)** Target.
   - *Berhasil*: Serangan berikutnya pada turn yang sama mendapatkan **Advantage**.
6. **Disengage**: Bergerak pergi tanpa memicu *Opportunity Attack*.
7. **Dodge**: Mengambil posisi bertahan. Seluruh serangan musuh hingga turn berikutnya mendapatkan **Disadvantage**.

---

## 4. CRITICAL HITS & CRITICAL FUMBLES TABLE

### 4.1 Critical Hit (Natural 20)
- Serangan otomatis Berhasil (HIT).
- **Damage Roll**: Lempar jumlah dadu damage 2x lipat + tambahkan Stat Modifier. *(Contoh: Pedang 1d8+3 menjadi 2d8+3).*

### 4.2 Critical Fumble Table (Natural 1)
Jika lemparan D20 Attack Roll menghasilkan angka **1 murni**, lempar **D6 Fumble Table**:

| Roll D6 | Efek Critical Fumble |
|---|---|
| **1** | **Senjata Terlepas**: Senjata terlempar sejauh 3m ke arah acak. |
| **2** | **Tergelincir (Trip)**: Karakter jatuh telungkup (*Prone*) dan kehilangan sisa Movement. |
| **3** | **Melukai Sekutu**: Serangan mengenai sekutu terdekat (Lempar damage normal ke sekutu). |
| **4** | **Senjata Tersangkut / Rusak**: Senjata tersangkut di zirah/tanah. Membutuhkan Action STR Check DC 12 untuk mencabut. |
| **5** | **Armor Jam**: Tali zirah terlepas, mengurangi AC karakter sebesar -2 hingga diperbaiki. |
| **6** | **Terguncang (Stunned)**: Karakter kehilangan Reaction hingga awal turn berikutnya. |

---

## 5. BAHAYA LINGKUNGAN PERTARUNGAN (*ENVIRONMENTAL HAZARDS*)

 Pertarungan di lokasi ekstrem menambahkan bahaya medan berikut:
- **Lava / Volcanic Terrain**: Berada dalam jarak 2m dari lava memberikan 2d10 Fire Damage per turn. Jatuh ke lava = 10d10 Fire Damage per turn.
- **Slippery Ice (Es Licin)**: Setiap kali bergerak cepat, karakter wajib D20 DEX Save DC 12. Gagal = Tergelincir (*Prone*).
- **Submerged Water Fighting**: Pertarungan di dalam air memberikan **Disadvantage** pada serangan senjata tumpul/tebas (*Slashing/Bludgeoning*), kecuali Dagger, Spear, atau Trident.
- **Extreme Darkness (Kegelapan Abadi)**: Seluruh serangan tanpa penglihatan malam (*Darkvision*) atau obor mendapat **Disadvantage**.
