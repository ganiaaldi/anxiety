# act2

`SceneSetup.act2();`

{{if _.badnews && !_.factcheck}}
(#act2-preamble-news1)
{{/if}}

{{if _.badnews && _.factcheck}}
(#act2-preamble-news2)
{{/if}}

{{if _.catmilk}}
(#act2-preamble-cat)
{{/if}}

(#act2-preamble-tinder)


# act2-preamble-news1

```
publish("act2",["dee",3]);
```

s: Tapi apakah kamu *lihat* "berita baru" tentang hal mengerikan terjadi disuatu tempat?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ha-hai...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Tuhan aku benci berita itu. Itu semua hanya sensasionalisme dan umpan klik.

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: a... pesta yang bagus...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Benar, tetapi mereka hanya mengikuti insentif. Masalah *sebenarnya* adalah orang yang termakan umpan klik.

```
publish("act2",["dee",3]);
```

s: Siapa yang akan meretweet berita buruk, dan membuat semua temannya merasa tidak enak?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, aku mengetahuinya?

(#act2-preamble-end)


# act2-preamble-news2

```
publish("act2",["dee",3]);
```

s: Tapi apakah kamu *lihat* "berita baru" itu menjadi viral?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ha-hai...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Ya, itu sepenuhnya palsu. Siapa yang akan termakan dan meretweet itu?

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: a... pesta yang bagus...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Serius bung. Seperti, haloo, bukalah Google dan cek fakta terlebih dahulu?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, aku mengetahuinya?

(#act2-preamble-end)


# act2-preamble-cat

```
publish("act2",["dee",3]);
```

s: Seperti yang aku katakan, Industri Meme mengeksploitasi kucing.

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: ha-hai..

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Jelaskan tesis ini.

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: a... pesta yang bagus...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Ya, kemarin aku melihat seseorang meretweet animasi kucing yang minum susu.

```
publish("act2",["dee",3]);
```

s: Mereka tidak bisa mencerna ^omong kosong^! Siapa yang akan meretweet *pelecehan hewan* seperti itu?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, aku mengetahuinya?

(#act2-preamble-end)


# act2-preamble-tinder

```
publish("act2",["dee",1]);
```

s: Jadi yahh, mereka tidak pernah membalas!

```
publish("act2",["dee",0]);
publish("act2",["party_hong","next"]);
```

h2: ha-hai...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Meskipun kalian berdua cocok satu sama lain di Tinder?

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: a... pesta yang bagus...

```
publish("act2",["party_hong","next"]);
```

{{if _.serialkiller}}
(#act2-preamble-serialkiller)
{{/if}}

{{if _.hookuphole}}
(#act2-preamble-hookuphole)
{{/if}}

{{if _.pokemon}}
(#act2-preamble-pokemon)
{{/if}}

# act2-preamble-serialkiller

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Yah aku tidak tahu! Apa, mereka mengira diriku adalah *pembunuh berantai* atau semacamnya? Sangat paranoid.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, aku mengetahuinya?

(#act2-preamble-end)


# act2-preamble-hookuphole

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ya, aku tidak tahu! Mungkin mereka berpikir bahwa teman kencan tidak bisa mengisi lubang di hati mereka?

s: Berhentilah menjadi pemalu! Buka pikiranmu, lalu bukalah kakimu!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, aku mengetahuinya?

(#act2-preamble-end)


# act2-preamble-pokemon

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ya, aku tidak tahu! Mereka tidak terlalu aduhay, tapi mereka akan menjadi tangkapan yang bagus!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Harus Tangkap 'Mereka Semua!™

(#act2-preamble-end)


# act2-preamble-end

```
Game.clearText();
publish("act2-out-1");
music(null, {fade:1});
```

(...3000)

```
music('battle', {volume:0.5});
publish("hp_show");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

n: RONDE DUA: *MULAI!*

[Oh tidak mereka semua membenci kita!](#act2a_social)

[Apakah kamu *melirik* si rambut merah?](#act2a_perv)

[Hei, mari kita berbicara tentang arti hidup.](#act2a_meaning)

# act2a_social

`bb({eyes:"sad"})`

b: Kita menurunkan mood pesta ini dengan menjadi orang yang menyedihkan!

`bb({eyes:"shock", body:"two_up"})`

b: Kita membunuh suasana bagus! Kita melakukan gelar-pertama pembunuh!

`bb({eyes:"normal", body:"normal"})`

b: Manusia, kita harus pergi *sekarang* sebelum--

```
_.a2_first_danger = 'social';
_.a2_attack_1 = "alone";
```

(#act2b)

# act2a_perv

`bb({eyes:"suspect"})`

b: Mereka lebih menarik dari kita, yang berarti jika kita *melihat* mereka, maka--

`bb({eyes:"shock", body:"two_up"})`

b: KITA MENYERAMKAN

`bb({body:"normal"})`

b: Kita menyeramkan, jahat, buruk, mengerikan, cab--

```
_.a2_first_danger = 'perv';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2a_meaning

`bb({body:"one_up", eyes:"normal_r"})`

b: Pada akhirnya, apa yang bisa kita lakukan untuk hal yang benar-benar penting?

`bb({body:"normal", eyes:"sad"})`

b: Berkontribusi untuk kemanusiaan? Di jalan Ozymandias semua karya besar membusuk. Cinta? Kematian akan selalu melakukan bagiannya.

`bb({eyes:"sad_r"})`

b: Dan berapa banyak kematian! *Kita* akan mati. *Orang yang kita cintai* akan mati.

`bb({eyes:"shock", body:"two_up"})`

b: Heck, Hukum Kedua Termodinamika berarti bahkan *alam semesta* akan mati!

`bb({eyes:"suspect", body:"normal"})`

b: Oh, "kematian membuat kita menghargai hidup"? Itu seperti mengatakan perbudakan itu baik karena itu membuat kita menghargai kebebasan!

`bb({body:"one_up"})`

b:  Oh, "kamu perlu membuat arti dirimu sendiri"? Itulah yang dilakukan oleh para pemuja dan teori konspirasi!

`bb({eyes:"shock", body:"two_up"})`

b: Hidup tidak ada artinya, kematian tidak ada artinya, bahkan *arti* tidak ada artinya! Apa yang seharusnya dilakukan oleh jiwa fana--

```
_.a2_first_danger = 'meaning';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2b

`bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"suspect"})`

b: Um... bisakah kamu mendengarku, manusia?

`bb({eyes:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"shock", mouth:"small_talk", body:"chest", MOUTH_LOCK:true})`

b: *HUFT*

`bb({mouth:"small_talk"})`

b: AKU HARUS PERINGATKAN KAMU TENTANG ...

[*Lebih* dari bahaya yang sama!](#act2b_louder)

{{if _.a2_first_danger=="social"}}
[*Perbedaan* bahaya sosial!](#act2b_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*Perbedaan* bahaya moral!](#act2b_different_moral)
{{/if}}

[Kamu mengabaikan bahaya! Itu berbahaya!](#act2b_ignore)

# act2b_louder

`_.a2_first_choice = "louder"`

{{if _.a2_first_danger=="social"}}
(#act2b_louder_social)
{{/if}}

{{if _.a2_first_danger=="perv"}}
(#act2b_louder_perv)
{{/if}}

{{if _.a2_first_danger=="meaning"}}
(#act2b_louder_meaning)
{{/if}}

# act2b_louder_social

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: EMOSI ITU MENULAR! JADI JIKA KAMU TIDAK KELUAR KAMU AKAN MENULARKAN SEMUANYA DENGAN PENYAKIT MENTALMU! 

b: Kamu akan menciptakan wabah mematikan dari SINDROM GUMPALAN KESEDIHAN

`bb({eyes:"suspect", body:"normal", mouth:"normal"})`

b: Kita harus keluar dari sini dan mengarantina diri kita sendiri selamanya di ruangan kecil, dengan Netflix dan pengiriman makanan!

```
_.a2_second_danger = 'netflix';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "a quarantine";
```

(#act2c)

# act2b_louder_perv

`bb({eyes:"suspect", body:"two_up", mouth:"normal"})`

b: JANGAN MENJADI JALAR. ITU MELAWAN HUKUM!

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Hukum menjalar, Bagian 74.5: (1) Setiap orang akan diperiksa (a) bahu yang berotot (b) gelembung di bagian bawah (2) dengan ini dikenal sebagai

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "SAMPAH SAMPAH BESAR MESUM MENJIJIKAN"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "the law";
```

(#act2c)

# act2b_louder_meaning

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b:Sebenarnya, jika kamu menemukan tujuan mulia dalam hidup, kamu *masih* dapat mengacaukan semuanya!

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Alfred Nobel menginginkan perdamaian dunia dan budaya untuk saling memahami. Jadi dia memutuskan untuk membuat perjalanan lebih mudah.

`bb({eyes:"normal_r"})`

b: Jadi dia butuh cara untuk membuat terowongan kereta api dengan harga murah. Jadi dia menemukan bahan baru yang disebut "dinamit" ...

`bb({body:"one_up", eyes:"normal"})`

b: yang digunakan dalam Perang Dunia I untuk MEMBUNUH JUTAAN ORANG

`bb({body:"two_up", eyes:"shock"})`

b: ITU PENGARUH KUPU-KUPU, MANUSIA! SEKARANG BERAPA BANYAK ORANG YANG KAMU BUNUH SECARA TIDAK SENGAJA 

```
_.a2_second_danger = 'butterfly';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "World War I";
```

(#act2c)

# act2b_different_social

`_.a2_first_choice = "different"`

`bb({eyes:"normal_r", body:"point", mouth:"normal"})`

b: Sebenarnya, kamu tahu apa yang lebih buruk daripada tidak ada orang yang menyukaimu? *Semua orang* menyukaimu.

`bb({body:"one_up", eyes:"suspect", mouth:"normal"})`

b: Itu dia, menjadi salah satu *dari* hewan pesta yang mengejar-kesenangan.

`bb({body:"normal", mouth:"small"})`

b: Kehidupan dangkal dengan teman-teman yang dangkal yang hanya mengetahui dangkalnya dirimu!

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Manusia, kita harus lari dari zombie kesenangan ini sebelum kita berubah menjadi salah satu dari mereka!

```
_.a2_second_danger = 'zombies';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "zombies";
```

(#act2c)

# act2b_different_moral

`_.a2_first_choice = "different"`

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: *Saat ini* orang-orang sekarat karena kelaparan serta genosida dan kita hanya berpesta!

`bb({body:"point", eyes:"closed", mouth:"small"})`

b: Orang bijak pernah berkata, "Satu-satunya hal yang diperlukan untuk menang adalah tidak melakukan apa-apa."

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: KITA TIDAK MELAKUKAN APA PUN.

`bb({mouth:"small"})`

b: DENGAN PESTA, KITA MEMBANTU *HITLER*.

```
_.a2_second_danger = 'hitler';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Hitler";
```

(#act2c)

# act2b_ignore

`_.a2_first_choice = "ignore"`

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Kamu pikir kamu aman hanya karena mengeluarkan baterai dari detektor karbon monoksida?

`bb({eyes:"suspect_r"})`

b: Kamu bahkan tidak akan mencium racun! Kamu hanya akan mengantuk dan kemudian akan--

`bb({body:"scream_c_1"})`

b: MATIIIIIIIIIIIIIIIIII

```
_.a2_second_danger = 'ignore';
_.a2_attack_2 = "harm";
_.a2_hoodie_callback = "carbon monoxide";
```

(#act2c)

# act2c

```
hong({body:"ignore_sweat"});
bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true});
```

b: ...

`bb({eyes:"happy", mouth:"smile", body:"chest"})`

b: Oh syukurlah manusia, Kupikir kamu bisa mendengarku lagi!

`bb({eyes:"closed", body:"point"})`

b: AKU HARUS PERINGATKAN KAMU TENTANG ...

{{if _.a2_first_choice=="louder"}}
[*Bahkan lebih* dari bahaya yang sama!](#act2c_louder)
{{/if}}

{{if _.a2_first_choice!="louder"}}
[*Lebih* dari bahaya yang sama!](#act2c_louder)
{{/if}}

{{if _.a2_first_danger=="social"}}
[*Perbedaan* bahaya sosial!](#act2c_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*Perbedaan* bahaya moral!](#act2c_different_moral)
{{/if}}

[Apakah kamu memeriksa minuman itu sebelum minum?](#act2c_punch)

#act2c_louder

{{if _.a2_second_danger=="netflix"}}
(#act2c_louder_netflix)
{{/if}}

{{if _.a2_second_danger=="law"}}
(#act2c_louder_law)
{{/if}}

{{if _.a2_second_danger=="butterfly"}}
(#act2c_louder_butterfly)
{{/if}}

{{if _.a2_second_danger=="zombies"}}
(#act2c_louder_zombies)
{{/if}}

{{if _.a2_second_danger=="hitler"}}
(#act2c_louder_hitler)
{{/if}}

{{if _.a2_second_danger=="ignore"}}
(#act2c_louder_ignore)
{{/if}}

# act2c_louder_netflix

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: Sebenarnya, Netflix & pengiriman makanan tidak cukup karantina! Kita masih akan menginfeksi kurir pengirim!

`bb({body:"one_up", mouth:"small"})`

b: Kita harus pindah ke wilayah Yukon Kanada, dan makanan kita dikirim dengan drone!

`bb({body:"two_up", mouth:"normal"})`

b: Dan kemudian mereka harus mensterilkan drone untuk menyingkirkannya dari GUMPALAN KUMAN KESEDIHAN kita

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "a quarantine";`

(#act2d)

# act2c_louder_law

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: SAMPAH BESAR MESUM akan dijatuhi hukuman 72 jam di salah satu alat penghinaan publik abad pertengahan

b: kecuali mereka diam-diam *masuk* ke hal semacam itu

`bb({body:"scream_a_1"})`

b: karena mereka SAMPAH BESAR MESUM

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the law";`

(#act2d)

# act2c_louder_butterfly

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: EFEK KUPU-KUPU! Kamu menggunakan gelas plastik non-biodegradable??

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: BAM, KEBOCORAN RACUN PADA TEMPAT PENAMPUNGAN ANAK DAN MEMBUNUH SEORANG ANAK

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: Kamu berkeringan dan jantungmu berdebar-debar?

`bb({body:"scream_a_1"})`

b: BAM, SISTEM PERAWATAN KESEHATANMU BANGKRUT DAN JUTAAN ORANG MATI

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the butterfly effect";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: Zombie kesenangan ini akan tersandung ke arahmu lalu bergumam,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: SUUUUUKA. SUUUUKAAAA.

`bb({body:"scream_a_1"})`

b: Kemudian mereka MENGGIGITMU dan kamu akan berubah menjadi ORANG TANPA OTAK dan TANPA PIKIRAN!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zombies";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: ORANG-ORANG NAZI KEMBALI KE JALAN SAAT INI

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Mengatakan, *hal baik itu 'orang baik' yang mengendurkan dengan hal-hal seperti 'bersantai' dan 'perawatan diri'!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Sekarang rencana kita bisa menjadi yang keempat, Negara Jerman sesuai jadwal!*

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitler";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b:  Kalau dipikir-pikir, apa kita tahu kalau gedung ini *mempunyai* detektor monoksida ?!

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: Bagaimana jika *SAAT INI* kita semua diracuni?

`bb({body:"scream_a_1"})`

b: KITA BAHKAN TIDAK MELIHAT KEMATIAN MENDEKAT. KITA HANYA BERHENTI UNTUK SELAMANYA DAN SELAMA--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "carbon monoxide";`

(#act2d)

# act2c_different_social

`bb({body:"normal", mouth:"normal", eyes:"sad"})`

b: Bagaimana jika kita *pada dasarnya tidak mampu* untuk dicintai, atau mencintai orang lain?

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Bagaimana jika ada sesuatu yang tidak dapat diubah dalam diri kita sejak lama? Atau tidak pernah ada di dalam diri kita?

`bb({body:"scream_a_1"})`

b: AHH KITA RUSAK! BEGITU RUSAK BEGITU RUSAK--

`_.a2_attack_3 = "alone";`

(#act2d)

# act2c_different_moral

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Bagaimana jika kita *pada dasarnya itu busuk*

`bb({body:"one_up", eyes:"sad"})`

b: Orang lain memiliki dorongan batin untuk melakukan kebaikan, tetapi kita hanya melakukan "kebaikan" karena rasa bersalah atau malu.

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Bagaimana jika sifat alami kita untuk menyakiti orang lain? Bagaimana jika kita tidak bisa menjadi apa pun *selain* menjadi beban bagi orang-orang yang dekat dengan kita?

`bb({body:"scream_a_1"})`

b: AHH KITA RUSAK! SANGAT RUSAK SANGAT RUSAK--

`_.a2_attack_3 = "bad";`

(#act2d)

# act2c_punch

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Aku tidak bersikap tidak rasional. Orang-orang *menelan* semangkuk obat-obatan. Itu adalah hal yang sebenarnya terjadi.

`bb({eyes:"suspect"})`

b:  Manusia, apakah kepalamu sakit? Apakah anggota tubuhmu lemas? Aku pikir kita sedang sekarat.

`bb({body:"scream_a_1"})`

b:  AHHH KITA MATI! KITA MATI, KITA MATI KITA MA--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "punch bowls";`

(#act2d)

# act2d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"attacked"});
attack("20p", _.a2_attack_1);
```

(...401)

```
hong({body:"attacked_2"});
attack("20p", _.a2_attack_2);
```

(...401)

```
hong({body:"attacked_3"});
attack("20p", _.a2_attack_3);
```

(...1001)

h: BANG^SAAAT^!

h: B^ANGG^SAT B^ANG^-B^ANG^SAT *B^ANGSATT^*

`bb({body:"two_up", mouth:"smile", eyes:"happy"});`

b: Hore, manusia! Aku sangat senang kamu dapat mendengarkanku lagi!

`bb({body:"normal", mouth:"small", eyes:"sad"})`

b: Mengapa kamu mengabaikanku?

`hong({body:"facepalm"})`

h: Demi ^neraka^, dasar tolol.

`hong({body:"facepalm_2"})`

h: Kamu tahu cerita penduduk asli Amerika itu?

h: "Ada dua serigala di dalam dirimu, yang satu adalah harapan, yang satu lagi putus asa. Serigala mana yang menang? Serigala Yang kamu beri makan."

```
hong({body:"facepalm_3"});
bb({eyes:"normal"});
```

h: Aku mencoba untuk *membuatmu kelaparan*, dasar sadis ^brengsek^!

`hong({body:"smile", mouth:"smile"})`

h: Persetan, aku akan melakukan afirmasi positif sebagai gantinya.

h: *Aku dicintai. Aku baik. Aku pintar. Aku cantik. Aku spesial. *

`bb({eyes:"suspect"});`

[Astaga, itu sangat narsistik!](#act2d_narcissist)

[Kau tahu penegasan *tidak terbukti?*](#act2d_disproven)

[Demi Tuhan, jangan kreditkan cerita acak kepada penduduk asli](#act2d_racist)

# act2d_disproven

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Faktanya, itu akan menjadi *bumerang* untuk orang-orang dengan harga diri rendah! 

`bb({body:"one_up", mouth:"small", eyes:"normal"})`

b: Itu adalah studi yang dirancang dengan baik - uji coba terkontrol secara acak, pelaku eksperimen tidak mengetahui ada di kelompok mana.

`bb({body:"two_up", mouth:"small", eyes:"normal_r"})`

b: Hasil: Jika kamu sudah memiliki harga diri yang rendah, kamu diminta untuk mengulangi afirmasi yang membuatmu merasa *lebih buruk* daripada tidak mengatakan apa-apa!

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Wood 2009, Psychological Science. Cari di Google Cendekia, manusia,

`bb({body:"scream_b_1"})`

b: LALU BERHENTILAH MENYEBARKAN BERITA PALSU YANG TIDAK BENAR

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_narcissist

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Kamu *perlu* untuk rendah hati melihat kekuranganmu untuk tumbuh menjadi seseorang!

`bb({body:"two_up", eyes:"suspect"})`

b:  Kamu tidak bisa menyemprotkan pengharum ke ruangan yang berjamur! Menutupi kekuranganmu akan membuatmu menjadi semakin buruk dalam jangka panjang.

`bb({body:"chest", mouth:"smile", eyes:"closed"})`

b: Syukurlah, aku, sebagai serigala penjaga setiamu, dapat mengingatkan akan kekuranganmu. Dan sekarang, itu-

`bb({body:"scream_b_1"})`

b: SEMUANYA. SEMUANYA SALAH

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_racist

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Penduduk asli Amerika adalah *orang yang sebenarnya*, bukan seorang "bangsawan biadab" yang bisa kamu namai untuk membuat kuemu lebih *eksotis*.

`bb({eyes:"suspect_r"})`

b: Kamu mengurangi individu & budaya kompleks menjadi kartu ucapan! Itu adalah sebuah "rasisme yang baik hati"!

`bb({body:"scream_b_1"})`

b: BERHENTI MENJADI RASIS KAU BRENGSEK BERMATA ANEH

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2e

h: ^SIALAN^.

`hong({body:"yell", mouth:"yell"})`

h: Kamu tahu? Kamu *tidaklah rasional*

h: Semua orang tahu emosi itu tidak rasional! Terutama ketakutan!

`hong({body:"facepalm_2"})`

h: Kamu adalah sisa evolusi yang tidak berguna, seperti usus buntu atau gigi bungsu!

`hong({body:"yell", mouth:"yell"})`

h: ^Neraka^, metafora serigala ini bodoh! Kamu hanyalah sekelompok bahan kimia saraf yang ada di kepalaku.

`hong({body:"cross", mouth:"cross"})`

h: Jadi mengapa aku harus mendengarkan potongan ^kotoran^ yang tidak berharga, tidak rasional sepertimu ?!

`bb({eyes:"sad", MOUTH_LOCK:true})`

b: ...

[Astaga, manusia. Itu sangat menyakitkan.](#act2e_hurtful)

[Aku punya perasaan. Perasaan itu benar.](#act2e_valid)

[Manusia, kita *berdua* "hanyalah bahan kimia""](#act2e_rational)

# act2e_hurtful

`bb({body:"chest"})`

b: Aku *bagian* darimu, kamu tahu. Saat kamu mengatakan itu, Kamu menyakiti *diri sendiri*

`bb({body:"scream_a_1"})`

b: Mengapa kamu memukul diri sendiri, manusia? BERHENTI MEMUKUL DIRI SENDIRI.

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2e_rational

`bb({body:"normal", mouth:"normal", eyes:"normal_r"});`

b: Motivasi terdalammu adalah dopamin, kegembiraan terkayamu adalah serotonin.

`bb({body:"one_up"});`

b: Ingatanmu adalah beban sinaptik, alasanmu adalah sinyal listrik yang rawan kesalahan.

`bb({eyes:"normal", body:"normal"});`

b: Jadi jika aku menjadi *bahan kimia* itu berarti *Aku* tidak rasional... yang berarti *kamupun* tidak rasional!

`bb({body:"two_up", eyes:"shock"});`

b: Dan jika kita *berdua* tidak rasional, maka kita *tidak akan pernah* mencari cara menjadi puas dan bahagia!

`bb({body:"scream_a_1"})`

b: AHH KITA RUSAK! BEGITU RUSAK BEGITU RUSAK--

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2f)

# act2e_valid

`bb({body:"normal", mouth:"normal", eyes:"suspect"});`

b: Tunggu ... "mereka" mengatakan bahwa perasaan itu benar, sehingga kamu harus selalu menerima emosimu.

`bb({eyes:"suspect_r"});`

b: Tapi "mereka" juga mengatakan emosi itu tidak rasional, sehingga emosi tidak bisa dipercaya.

`bb({eyes:"angry"});`

b: Ya ampun, "mereka" telah berbohong kepada kita selama ini!

`bb({body:"scream_a_1"})`

b: "MEREKA" MEMBERI KITA KONTRADIKSI UNTUK MEMBUAT KITA BERGANTUNG PADA KOMPLEKS INDUSTRI BANTUAN MANDIRI

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2f

`hong({body:"defeated", MOUTH_LOCK:true});`

h: ...

h: Aku benci ini. Tuhan itu sangat sakit, aku *membenci* ini.

h: Aku tidak bisa menenangkanmu. Aku tidak bisa mengabaikanmu. Aku tidak bisa melawanmu. 

`bb({eyes:"suspect"});`

h: Apa pun yang aku lakukan, aku tidak bisa menyingkirkan ka--

`bb({body:"cry_1"});`

b: Yah, mungkin kamu TIDAK *SEHARUSNYA* MENYINGKIRKANKU.

`bb({body:"cry_2"});`

b: Bagaimana kamu berpikir perasaan *Aku*, manusia!

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: Aku mencoba yang terbaik untuk menjadi anjing penjaga Anda, tetapi Anda terus melihatku sebagai Serigala Jahat Besar!

b: Jadi aku berusaha lebih *keras* untuk memperingatkanmu dari bahaya! Bahaya *Lain*! Bahaya *Berbeda*!

`bb({eyes:"cry_2"})`

b: Tapi tidak peduli seberapa keras aku mencoba untuk melindungimu, Kamu *masih* berpikir aku adalah musuhmu!

`bb({body:"cry_5"});`

b: Apa yang aku lakukan salah ?!

`bb({body:"cry_2"});`

b:  Aku *tahu* aku payah di pekerjaanku. Tetapi aku *berusaha*, manusia!

`bb({body:"cry_3"});`

b: ...Aku berusaha.

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: Kamu tidak perlu mendengar peringatanku, atau setuju denganku, atau bahkan *menyukaiku*.

`bb({eyes:"cry_r_2"});`

b: Aku hanya ... yang aku inginkan adalah kamu bersabar denganku.

`bb({eyes:"cry_r_3"});`

b: Aku hanya ingin kamu duduk bersamaku sebentar, bukannya berpaling dan--

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: Hai.

```
hong({body:"look"});
Game.clearText();
publish("act2-in-2");
publish("hp_hide");
music('party1', {volume:0.4, fade:2});
```

(...2000)

```
publish("act2",["party_hunter",2]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Sepertinya kamu sedang bertengkar dengan diri sendiri, nak.

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: Apakah terlihat jelas?

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: Kamu, uh, bergumam tentang jaketmu atau sesuatu.

```
publish("act2",["party_hunter",13]);
publish("act2",["party_hong",15]);
sfx("rustle", {volume:0.6});
setTimeout(function(){
	publish("act2",["party_hong",16]);
	sfx("concrete_step3", {volume:0.6});
},401);
setTimeout(function(){
	publish("act2",["party_hong",17]);
	sfx("concrete_step4", {volume:0.6});
},801);
```

h2: Ya Tuhan, aku berantakan sekali.

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: Hei. Kamu tidak sendiri, teman. Kecemasan sangatlah umum.

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: Heck, baru kemarin, aku mendengar seseorang di kampus mengalami gangguan saraf dan menghancurkan ponsel mereka!
{{/if}}

{{if _.act1_ending=="flight"}}
r: Heck, baru kemarin, aku mendengar seseorang meringkuk menjadi bola armadillo dan menangis di depan umum!
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: Dengar: aku tahu bagaimana rasanya memiliki hewan itu di kepala Anda.

```
publish("act2",["party_hunter",8]);
```

r: Kami *semua* mempunyainya. Itu sebabnya aku mengadakan pesta ini setiap akhir pekan, untuk melupakan kekhawatiran kita, lupakan hewan itu.

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: tapi kecemasanku ...

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: Jangan khawatir, nak. Aku dulu sepertimu. Tapi kemudian aku menemukan sedikit trik untuk membuat suara negatif itu diam selamanya ...

```
publish("act2",["party_hunter",3]);
Game.clearText();
music(null, {fade:1});
```

(...2001)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",22]);
sfx("rustle");
```

(...2501)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",23]);
sfx("rustle2");
```

(...1001)

```
publish("act2",["party_hunter",11]);
```

r:  Campuran spesialku sendiri. Ini sedikit lebih kuat dari ... yah, apapun yang sebenarnya legal .

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: Bawalah, ^jaa-luang^!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[Ya Tuhan](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[Ini adalah mekanisme kepala batu yang buruk.](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[Jangan mengambil minuman dari orang asing.](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: YA--

(#act2g)

# act2g_2

b: IN--

(#act2g)

# act2g_3

b: JAN--

(#act2g)

# act2g

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"forward", mouth:"forward"});
bb({body:"frazzled", mouth:"frazzled", eyes:"frazzled"});
```

h: Mmm, palet yang sangat indah!

h: Rasa penuh dari "menutup pikiranmu," dengan sisa rasa halus yang "tidak pernah merasakan apapun lagi"!

b: Ini buruk, manusia. Ini benar-benar buruk.

[Ini *sebenarnya* bagaimana kecanduan dimulai.](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[Aku *tahu* bahwa tuan rumah benar-benar kacau!](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[Juga, mereka bisa memasukan obat kesitu!](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: Ini *seben*--

(#act2h)

# act2h_opt2

b: Juga, mer--

(#act2h)

# act2h_opt3

b: Aku *tahu* i--

(#act2h)

# act2h

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"back", mouth:"back"});
bb({body:"panicked", mouth:"panicked", eyes:"panicked"});
```

h: Lezat, *dan* lebih murah dari terapi!

b: MANUSIA TOLONG BERHENTI

h: Hehehe!

h: Dan apa yang  akan *kamu* lakukan tentang itu, ^brengsek^?

b: Maafkan aku, manusia.

b: Aku harus menggunakan SERANGAN KHUSUSKU

```
bb({body:"special_a"});
music('battle', {volume:0.5});
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act2h_attack) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act2h_attack) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act2h_attack) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`

# act2h_attack

```
bb({body:"special_b_1"});
hong({body:"forward", mouth:"forward"});
sfx("charging");
```

h: Apa ^omong kosong^ ini?

h: Kamu akan memberikan *kata-kata* bodoh lagi kepada--

```
bb({body:"special_c"});
sfx("hadouken");
```

(...901)

(#act2i)

# act2i

```
publish("hide_tabs");
publish("show_special_attack");
Game.FORCE_CANT_SKIP = true;
music(null);
stopAllSounds();
```

(...5000)

```
publish("show_tabs");
hong({ body:"final", mouth:"final" });
bb({ body:"normal", mouth:"normal", eyes:"sad" });
attack("100p", _.SPECIAL_ATTACK);
Game.FORCE_CANT_SKIP = false;
setTimeout(function(){
	publish("remove_special_attack");
},30);
```

(...2500)

h: APAAN TUHH

b: Maaf. Aku perlu memperlihatkanmu konsekuensinya.

{{if _.SPECIAL_ATTACK=="harm"}}
h: AKU DAPAT *MELIHAT* MAYATKU SENDIRI. AKU DAPAT *MERASAKAN* SENSASI KEMATIAN SEBENARNYA.
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: AKU DAPAT *MELIHAT* TATAPAN JIJIK SEMUA ORANG. AKU DAPAT *MENDENGAR* SEMUA YANG MEREKA KATAKAN.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: AKU DAPAT *MENDENGAR* TULANG RUSUK PATAH. AKU DAPAT *MERASAKAN* DARAHNYA DI UDARA.
{{/if}}

b: Aku minta maaf, manusia.

n: *HABISI MEREKA*

[{HABISI: Pukul tuan rumah.}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{PERGI: Ayo pergi dari sini.}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: Psikopat itu memanfaatkanmu.

b: Mereka mencoba merusakmu, membuatmu kacau seperti mereka!

`bb({ body:"yell_angry_1" });`

b: Pukul si brengsek itu! Pukul mereka hingga mereka padam!

`bb({ body:"final_1" });`

b: PUKUL MEREKA PUKUL MEREKA PUKUL MEREKA PUKUL MEREKA PUKUL MEREKA PUKUL MEREKA PUKUL ME--

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: Aku *tahu* semua pengunjung pesta ini sangat kacau. Mereka menghilangkan rasa sakit dengan hal-hal yang mengerikan!

`bb({ body:"yell_1" });`

b: Dan mereka menipumu untuk melakukan hal yang sama! Mereka akan merusakmu! Kita harus keluar!

`bb({ body:"final_1" });`

b: KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KELUAR KEL--

`_.a2_ending = "flight";`

(#act2k)

# act2k

```
Game.clearText();
publish("act2-in-4");
publish("hp_hide");
music('party1', {volume:0.6, fade:1.5});
```

(...2001)

```
publish("act2",["party_hong",26]);
sfx("slide");
```

(...1001)

```
publish("act2",["party_hunter",14]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Kamu baik-baik saja, nak?

`publish("act2",["party_hunter",13]);`

{{if _.a2_ending=="fight"}}
(#act2k_fight)
{{/if}}

{{if _.a2_ending=="flight"}}
(#act2k_flight)
{{/if}}

# act2k_fight

```
Game.clearText();
publish("act2",["party_hunter",21]);
publish("act2",["party_hong",33]);
music(null);
sfx("hit");
```

(...1000)

```
sfx("record_scratch");
publish("act2",["party_hunter",22]);
publish("act2",["party_hong",34]);
publish("act2",["dee",6]);
publish("act2",["dum",6]);
```

r: Ka-kamu...

```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: sangat *kacau*.

r: Aku menyukainya. Datang ke pestaku akhir pekan depan, manis.

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: oke selamat tinggal, ciao, adios, au revoir

r: Hewan itu mungkin menang hari ini, dan saat kembali nanti aku akan mencampur sesuatu yang lebih kuat untukmu!

h2: sayōnara, auf wiedersehen, zài jiàn, shalom

r: Kau dan aku, nak, kita akan tunjukan ke hewan buas itu siapa bosnya!

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: Oke maaf saya harus lari

`publish("act2",["party_hunter",16]);`

r: ^Sialan^. Hewan itu menang hari ini, ya?

`publish("act2",["party_hunter",15]);`

h2: Tidak tidak, hanya, uh, harus lari maraton. harus lari dengan cepat.

`publish("act2",["party_hunter",19]);`

r: Datang ke pestaku akhir pekan depan, manis. Aku akan mencampur sesuatu yang lebih kuat untukmu!

h2: Oke terima kasih aku akan lari lari lari lari

r: Kau dan aku, nak, kita akan tunjukan ke hewan buas itu siapa bosnya!

(#act2k_end)

# act2k_end

```
Game.clearText();
publish("act2-out-5");
publish("act2-outro", ["end1"]);
music("hum", {fade:2, volume:0.6});
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2500)

```
publish("act2", ["act2_end",2]);
sfx("whoosh");
```

(...1000)

b: Manusia! Apa kamu baik-baik saja?!

```
publish("act2", ["act2_end","next"]);
```

b: Astaga, itu tadi *hampir*. Kita benar-benar bisa--

```
Game.clearText();
publish("act2", ["act2_end","next"]);
music(null);
sfx("squeak");
```

(...1500)

```
publish("act2", ["act2_end","next"]);
sfx("hit");
```

(...1000)

h: Minggu depan aku akan kembali ke pesta.

h: Selanjutnya saat kita bertarung, aku tidak begitu saja *membunuhmu*...

h: Aku akan pergi *membunuhmu* ^sial^an.

```
Game.clearText();
publish("act2", ["act2_end","next"]);
sfx("concrete_step1");
````

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step2", {volume:0.8});
```

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step3", {volume:0.5});
```

(...901)

`sfx("concrete_step4", {volume:0.25});`

(...3000)

`_.INTERMISSION_STAGE = 2;`

(#intermission)