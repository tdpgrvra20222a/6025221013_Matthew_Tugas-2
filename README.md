# 6025221013_Matthew_Tugas-2
Komponen Game
---
<h1> Mekanika Game Stone Age (2008) </h1>

1. Ruang: <br>
&emsp;•	2D (Board Game)<br>
&emsp;•	List (Resources, Figure, Civilization & Building Card, Score)<br>

2. Waktu <br>
&emsp;•	Turn-Based <br>

2. Objek <br>
&emsp;•	Figure <br>
&emsp;&emsp;i.	Tidak terpakai <br>
&emsp;&emsp;ii.	Berada pada 1 lokasi <br>
&emsp;•	Farm <br>
&emsp;&emsp;i.	Generate food per turn <br>
&emsp;•	Dadu <br>
&emsp;&emsp;i.	menentukan jumlah resources <br>
&emsp;•	Tool <br>
&emsp;&emsp;i.	Menambah hasil dadu <br>
&emsp;•	Resources <br>
&emsp;&emsp;i. Food <br>
&emsp;&emsp;&emsp;-	Cukup sesuai Figure <br>
&emsp;&emsp;&emsp;-	Berlebih dari Figur <br>
&emsp;&emsp;&emsp;-	Kekurangan untuk Figur <br>
&emsp;&emsp;i. Resources (Wood, clay, Stone, Gold) <br>
&emsp;&emsp;&emsp;-	Cukup sesuai Figur <br>
&emsp;&emsp;&emsp;-	Berlebih dari Figur <br>
&emsp;&emsp;&emsp;-	Kekurangan untuk Figur <br>

4.	Aksi <br>
&emsp;•	Basic <br>
&emsp;&emsp;i.	Menaruh figure pada sebuah lokasi <br>
&emsp;&emsp;ii.	Melempar dadu untuk mendapatkan resources <br>
&emsp;•	Strategic <br>
&emsp;&emsp;i.	Mengambil sebuah lokasi sebelum diambil/dipenuhi pemain lain <br>
&emsp;&emsp;ii.	Meningkatkan lv dari farm agar tidak perlu menaruh figure pada lokasi hunting <br>
&emsp;&emsp;iii.	Menggunakan tool untuk menambah hasil dadu agar mendapat resources tambahan (jika ideal, contoh: lemparan dadu = 3 pada bagian wood, secara normal hanya mendapatkan 1 wood dari perhitungan wood 3/2 tetapi dari tambahan tool maka hasil dadu dari 3 menjadi 4, sehingga mendapat 2 wood dari perhitungan 4/2) <br>
&emsp;&emsp;iiv.	Meningkatkan jumlah figure agar dapat lebih banyak melempar dadu (lebih banyak menaruh figure) <br>
&emsp;&emsp;v.	Mendapatkan Card: <br>
&emsp;&emsp;&emsp;-	Building <br>
&emsp;&emsp;&emsp;&emsp;->	Mencari kartu yang memberi point tinggi <br>
&emsp;&emsp;&emsp;&emsp;->	Menggunakan resources yang mahal untuk kartu yang memberi point bergantung dengan resources yang dipakai <br>
&emsp;&emsp;&emsp;-	Civilization <br>
&emsp;&emsp;&emsp;&emsp;->	Mencari kartu yang berbackground hijau dengan artefak yang berbeda untuk point yang tinggi <br>
&emsp;&emsp;&emsp;&emsp;->	mencari kartu sesuai dengan kondisi tangan (level farm, jumlah figur, jumlah tool, dll) <br>
&emsp;&emsp;&emsp;&emsp;->	Menunggu kartu sampai pada bagian kanan agar biaya kartu lebih sedikit dibanding kartu saat berada pada paling kiri <br>

5.	Aturan <br>
&emsp;•	Pemain bergantian menaruh figure searah jarum jam dimulai dari pemain pertama <br>
&emsp;•	1 figure membutuhkan 1 food pada akhir giliran, bila tidak cukup maka harus ditukar dengan resources (1 resources = 1 food) <br>
&emsp;•	Pemain hanya dapat menempati tempat jika tidak penuh atau belum ditempati (bergantung lokasi) oleh pemain lain <br>
&emsp;•	Pemain mendapatkan resources sesuai dengan lemparan dadu dan juga berdasarkan perhitungan unik per resources (Pada Wood: Hasil Dadu/2 = Jumlah Wood) <br>

6.	Keterampilan <br>
&emsp;•	Memilih lokasi/item yang benar benar dibutuhkan <br>
&emsp;•	Melakukan perkiraan pemain lain akan memilih lokasi tertentu berdasarkan resources yang dipunyai <br>

&emsp;7.	Peluang <br>
&emsp;•	Hasil dadu menentukan jumlah resources atau efek kartu yang didapat <br>
&emsp;&emsp;- Pada kartu civilization, terdapat efek unik pada saat mendapatkan, salah satu contoh yaitu melempar dadu dan mendapatkan resources sesuai dengan hasil lemparan dadu <br>

---
<h1> Mekanika Game Sid Meier’s Civilization V </h1>

1.	Ruang <br>
&emsp;•	Isometric 3D  <br>
&emsp;•	Tilemaps <br>
&emsp;•	Collision Detection <br>
2.	Waktu <br>
&emsp;•	Hybrid (Continous) <br>
&emsp;&emsp;i.	Pemain bergerak bersamaan, yg bergerak tercepat yg jalan dahulu <br>
&emsp;•	Turn Based <br>

3.	Objek <br>
&emsp;•	City <br>
&emsp;&emsp;i.	Attribut	: Citizen, Food, Production, HP, Def, Follower (Religion) <br>
&emsp;&emsp;ii.	Status	: Unhappy, Happy, Hungry, Terrain <br>
&emsp;•	Unit <br>
&emsp;&emsp;i.	Type, EXP, Lv, Production, Combat Strength, Range, Abilities, Cost, Lokasi (bonus) <br>
&emsp;&emsp;ii.	Action: Moves, Attack, Guard, Build, Sleep, Skip <br>
&emsp;•	Lokasi <br>
&emsp;&emsp;i.	Bonus, Resources <br>

4.	Aksi <br>
&emsp;•	Basic <br>
&emsp;&emsp;i.	Menggerakkan unit <br>
&emsp;&emsp;ii.	Memerintahkan worker untuk membangun improvement pada tile sekitar kota <br>
&emsp;&emsp;iii.	Memilih produksi kota <br>
&emsp;&emsp;iv.	Memilih bonus yang didapat (policy, promotion) <br>
&emsp;•	Strategic <br>
&emsp;&emsp;i.	Menggerakkan unit “melee” kedepan agar unit “ranged” tidak diserang <br>
&emsp;&emsp;ii.	Membangun kota di tempat strategis sebelum diambil pemain lain <br>
&emsp;&emsp;iii.	Memilih pembangunan “World Wonder” sebelum dibangun oleh pemain lain <br>
&emsp;&emsp;iv.	Mengumpulkan unit sebelum memulai menyerang negara/pemain lain <br>
&emsp;&emsp;v.	Menggunakan “Siege” unit untuk menyerang kota agar HP dari kota tersebut berkurang banyak <br>
&emsp;&emsp;vi.	Memilih promotion atau hal lainnya yang dapat meningkatkan damage serangan unit sebelum menyerang <br>
&emsp;&emsp;vii.	Meningkatkan point dengan city state untuk mendapatkan bonus strategis dibanding player lain <br>
&emsp;&emsp;viii.	Membangun jalan agar unit dapat berjalan dengan cepat <br>

5.	Aturan <br>
&emsp;•	Pemain bergantian/ bersamaan menjalankan aksi yang dapat dijalankan <br>
&emsp;•	Unit pemain tidak dapat melewati wilayah pemain lain (tanpa persetujuan <br>
&emsp;•	Penggunaan cheat dilarang <br>
&emsp;•	Beberapa lokasi tidak dapat dilewati oleh unit pemain (beberapa unit dapat melewati, beberapa memiliki konsekuensi) <br>
&emsp;•	Pemain harus menemukan wilayah pemain lain baru dapat melakukan trading, dll <br>
&emsp;•	Pemain tidak dapat melihat wilayah yang tidak terdapat unit atau wilayah milik pemain <br>

6.	Keterampilan <br>
&emsp;•	Berkoordinasi dengan ally dalam hal perang, teknologi, atau ekonomi <br>
&emsp;•	Pemain dapat menentukan keputusan yang bagus dalam menggerakkan unit, memilih produksi bangunan, memilih lokasi kota, dll <br>
&emsp;•	Pemain melakukan observasi terhadap pemain lain (pergerakan unit, pembangunan “World Wonder”, ekspansi kota) <br>

7.	Peluang <br>
&emsp;•	Lokasi kota pertama dari pemain <br>
&emsp;•	Tingkat damage unit <br>
&emsp;•	Lokasi dan jumlah strategic resources yang dapat diakses <br>
&emsp;•	Bonus dari ruins <br>
