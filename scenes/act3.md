# act3

```
SceneSetup.act3();
Game.WORDS_HEIGHT_BOTTOM = 205;
sfx("cheers");
```

r: Bersulang!

```
publish("act3",["roofhunter",1]);
publish("act3",["roofhong",1]);
sfx("drinking");
```

(...4001)

```
publish("act3-alpha", ["dizzyhunter",1]);
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",3]);
```

h2: *Ah* itu tepat sasaran.

```
publish("act3",["roofhunter",2]);
publish("act3",["roofhong",2]);
```

r: Kamu tahu, bocah...

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",6]);
```

h2: Khususnya, sasaran itu mengenai amigdala kanan dan kiriku.

```
publish("act3",["roofhunter",8]);
publish("act3",["roofhong",5]);
```

r: Kamu mengingatkanku pada diriku ketika aku masih muda. Dulu ketika aku disiksa oleh hewan yang ada di kepalaku.

```
publish("act3",["roofhunter",9]);
publish("act3",["roofhong",2]);
```

r: Aku sangat bersyukur aku bisa membayarnya, dan membantumu membunuh binatang itu seperti aku membunuh binatang milikku.

```
publish("act3",["roofhunter",2]);
```

r: Hei, pertanyaan cepat: kebenaran atau tan--

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",7]);
publish("act3-alpha", ["dizzyhong",0]);
```

h2: Tantangan!

```
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",2]);
```

r: Haha! Bagus.

```
publish("act3",["roofhunter",21]);
publish("act3",["roofhong",4]);
```

r: Oke. Kamu lihat kolam renang berwarna biru muda di bawah sana?

```
publish("act3-alpha", ["dizzyhong",0]);
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",9]);
```

h2: Ya? Enam lantai di bawah?

```
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",8]);
```

r: Lompatlah.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",10]);
```

h2: ...

```
publish("act3",["roofhong",11]);
```

h2: Sebentar, apa?

```
publish("act3",["roofhong",10]);
publish("act3",["roofhunter",2]);
```

r: Hewan itu mulai merengek, bukan?

```
publish("act3",["roofhunter",23]);
```

r: *Oh tidaakkkkk itu berbahaya, jangan lakukan ituuu.*

```
publish("act3",["roofhunter",22]);
```

r: Tapi itulah mengapa kita membutuhkan sensasi yang menantang maut! Pesta pora! Hari istimewa! Dengusan bersoda dari ^pantat^ ^pelacur^, #YOLO!

```
publish("act3",["roofhunter",10]);
```

r: Tunjukkan bahwa hewan kita tidak memberikan dua *^titit^* tentang ^jalang^nya! Terjunlah.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",13]);
```

h2: Eh, tapi kadang, um ... ketakutan ada benarnya ..

```
publish("act3",["roofhunter",5]);
publish("act3",["roofhong",12]);
music(null, {fade:2});
```

r: ...

```
publish("act3-alpha", ["dizzyhunter",0]);
publish("act3",["roofhunter",6]);
publish("act3",["dd",1]);
```

r: Maaf, apakah kamu terpesona oleh propaganda McMindfulness yang mengklaim bahwa perasaan buruk itu *baik?*

```
publish("act3",["roofhunter",17]);
```

r: Para ^bajingan^ yang menjalankan dunia ini membuat *kita* kecemasan dan depresi lainnya,

```
publish("act3",["roofhunter",18]);
```

r: Kemudian membuat TED Talks untuk memberitahu kita agar "menerima" menjadi kacau, dan "merangkul" iblis itu di kepala kita!

```
publish("act3",["roofhunter",6]);
```

r: Bocah, Aku mengetahui *binatangmu* itu *menyakiti* orang seperti kita. Itu *menyiksa* orang seperti kita.

```
publish("act3",["roofhunter",19]);
```

r: Itu bukan teman kita. Itu adalah binatang buas, yang perlu *ditenangkan*,

```
publish("act3",["roofhunter",20]);
```

r: Atau aku dapat *memasukan peluru ke tengkoraknya*.

```
publish("act3",["roofhunter",27]);
```

r: Jika tidak, kamu akan membiarkannya menang.

```
publish("act3",["roofhunter",31]);
publish("act3",["roofhong",14]);
publish("act3",["dd",2]);
```

h2: Tidak. Kamu salah.

```
publish("act3",["roofhunter",13]);
publish("act3",["roofhong",15]);
music('battle_dark', {volume:1.0}, function(){
	music('battle_dark_loop');
});
```

h2: Aku tidak akan membiarkannya menang.

```
publish("act3",["roofhunter",25]);
publish("act3-alpha", ["roofhong",0]);
publish("act3-alpha", ["transition",1]);
publish("act3",["dd",6]);
```

r: Ya ^Sialan^! Aku percaya padamu sayang! Bunuh dia! <3

(#act3a)



# act3a

```
Game.clearText();
publish("act3-out");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
_.act3_bb_body = 1;
```

(...1500)

```
publish("hp_show");
```

b: tidak, tidak, tidak, tidak, tidak

n: BAB INI HANYA MEMILIKI DUA KEMUNGKINAN AKHIR. SALAH SATUNYA *SANGAT, SANGAT BURUK.*

b: TIDAK TIDAK TIDAK TIDAK TIDAK TIDAK TIDAK

n: PILIH DENGAN BIJAKSANA. LINDUNGI KEMANUSIANMU

`bb({ eyes:"oh_crap", mouth:"normal_talk", MOUTH_LOCK:true });`

b: AAAAAAAAAAAAAAAAAA

`bb({ mouth:"normal" });`

n: SEMOGA BERUNTUNG

```
Game.clearText();
bb({ eyes:"start" });
```

[Manusia, kamu sebenarnya bisa MATI di sini!](#act3a_harm) `Game.OVERRIDE_CHOICE_LINE=true`

[Ini bodoh dan menghancurkan diri sendiri!](#act3a_bad) `Game.OVERRIDE_CHOICE_LINE=true`

[Orang sakit ini sebenarnya bukan temanmu!](#act3a_alone) `Game.OVERRIDE_CHOICE_LINE=true`

# act3a_harm

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: M--

(#act3a_after)

# act3a_alone

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: O--

(#act3a_after)

# act3a_bad

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: I--

(#act3a_after)

# act3a_after

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Kamu tahu, aku mungkin mempercaimu... jika kamu belum mencobanya jutaan kali sebelumnya.

h: Kamu adalah serigala yang menangisi serigala.

```
bb({ eyes:"sad" });
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act3_fork) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act3_fork) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act3_fork) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`


# act3_fork

```
Game.clearText();
bb({body:"special_attack"});
sfx("charging");
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
Game.FORCE_CANT_SKIP = false;
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Kamu mencobanya juga.

b: Manusia, tolong...

`hong({ eyes:"look_right" });`

h: Oh aku *minta maaf* Farmasi Besar tidak menyetujui pengobatan sendiri.

h: Lihat ^brengsek^, kami *semua* punya cara untuk membungkammu ^brengsek^.

`hong({ body:"look_up", eyes:"look_up" });`

h: Beberapa orang menceburkan diri ke dalam pekerjaan.

`hong({ body:"look_down", eyes:"look_down" });`

h:  Beberapa orang melakukan seks, narkoba, dan memperbarui feed Facebook mereka.

`hong({ body:"normal", eyes:"look_right" });`

h: Beberapa orang menceburkan diri ke orang lain.

`hong({ eyes:"angry" });`

h: Aku akan menceburkan diri ke kolam renang itu.

[Kamu mabuk dan itu ENAM LANTAI KEBAWAH](#act3_bad_1_harm)

[Sial, ini ucapan terima kasih yang kudapat?!](#act3_bad_1_insult) `bb({eyes:"angry"});`

[Oke, Aku akui. Aku mengacaukannya.](#act3_good_1) `bb({mouth:"sorry", eyes:"sorry_down"});`

# act3_bad_1_harm

b: Bahkan jika kamu mendarat di air, tegangan permukaannya akan mematahkan tulang rusukmu dan menyebabkanmu *setidaknya gegar otak!*

h: Eh.

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Saya pernah melihat seorang pria Rusia melakukan ini di YouTube.

(#act3_bad_2)

# act3_bad_1_insult

`hong({ eyes:"look_right" });`

h: A- Permisi, ber*terima kasih?*

`bb({ eyes:"angry" });`

b: Inilah tepatnya mengapa aku *ada!* Karena manusia tidak dapat dipercaya untuk melindungi diri mereka sendiri!

b: Aku sudah berusaha melindungi pantat bodohmu sepanjang hidupku dan sekarang kamu hanya akan--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)

# act3_good_1

`hong({ body:"laugh_1" })``

h: heh.

`hong({ body:"laugh_2" })``

h: hahahaha

`hong({ body:"laugh_3" })``

h: HAHAHAHAHAHA

```
bb({ eyes:"sorry"});
hong({ body:"yell_1", mouth:"yell", eyes:"blank" });
```

h: Oh WOW itu adalah pernyataan *^sial^an* terbesar abad ini!

`hong({ body:"yell_2" });`

h: Yah, kau tumpukan busuk berlumur darah ^sialan^! Kau mengacaukannya ^sialan^!

`hong({ body:"normal", mouth:"angry", eyes:"angry" });`

h: Ada komentar lain, Kapten Jelas?

[Tapi balas dendam padaku bukanlah jawabannya!](#act3_good_1_fail_revenge) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Tapi kali ini aku *memang* benar!](#act3_good_1_fail_harm) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Aku telah menyakitimu.](#act3_good_2a)


# act3_good_1_fail_revenge

b: Kamu perlu memiliki hubungan yang lebih sehat dengan emosimu, daripada menenggelamkannya deng--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)



# act3_good_1_fail_harm

b: Jadi tolong, simpan botol itu dan mari--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)




# act3_bad_2

`bb({ eyes:"sad" });`

b: Tolong... jangan...

h: Bar energimu terlihat sangat rendah di sana, serigala.

h: Jika aku diposisimu, aku akan memilih kata-kata berikutnya dengan sangat hati-hati.

`bb({ eyes:"normal" });`

[Baik. Aku sudah selesai melindungimu.](#act3_bad_2_jump) `bb({ mouth:"ignore", eyes:"ignore" });`

[Saya selama ini benar.](#act3_bad_2_right)

[Aku minta maaf.](#act3_good_2b) `bb({mouth:"sorry", eyes:"sorry_down"});`


# act3_bad_2_jump

b: Jadi, lanjutkan dan lompatlah. Lihatlah apa aku peduli.

`hong({ eyes:"look_right", mouth:"normal", MOUTH_LOCK:true });`

h: ...

```
hong({ eyes:"less_angry", mouth:"normal" });
bb({ eyes:"ignore_oh_crap" });
```

h: Baiklah. Selamat minum.

```
bb({ mouth:"normal", eyes:"oh_crap" });
Game.OVERRIDE_TEXT_SPEED = 2;
```

b: TUNGGU ITU ADALAH PSIKOLOGI TERBALIK, KAMU SEHARUSNYA MELAKUKAN HAL *BERLAWANAN* DARI YANG AKU KATA--

(#act3_bad_3)



# act3_bad_2_right

`bb({ eyes:"angry" });`

b: Kamu *sedang* menempatkan dirimu dalam bahaya. Teman-teman yang kamu sebut *sedang* memanfaatkanmu. Dan *kamu* akan menggunakan apa yang disebut dengan teman.

`bb({ eyes:"sad" });`

b: Jadi tolong, manusia ... kenapa kamu tidak percaya padaku?!

h: Karena kamu tidak pernah percaya pada *diriku*.

(#act3_bad_3)


# act3_bad_2_terrible

`bb({ eyes:"angry" });`

b: Serigala penjaga lain memiliki manusia yang benar-benar meluangkan waktu untuk melatih mereka dengan sabar, untuk *belajar* bekerja sama,

b: Daripada membenci serigala penjaga karena mencoba melindungi mereka! Jadi kenapa kamu tidak bisa han--

`bb({ eyes:"normal" });`

h: Jawaban salah ^sialan^.

(#act3_bad_3)



# act3_bad_3

```
music(null);
hong({body:"drink"});
bb({body:"attacked"});
publish("bb_STOP_VIBRATING");
attackBB("100p");
```

(...2000)

```
hong({ body:"normal", mouth:"normal", eyes:"normal" });
bb({ body:"dead" });
```

(...999)

h: *"Satu-satunya hal yang perlu ditakuti adalah ketakutan itu sendiri."*

`hong({ body:"look_up", mouth:"happy", eyes:"blank" });`

h: *"Jangan khawatir, bersenang-senanglah!"*

`hong({ body:"normal", mouth:"normal", eyes:"normal" });`

h: Semua orang bijak di zaman kita setuju: emosi negatif itu *buruk!*

`hong({ eyes:"less_angry" });`

h: Duh! Itulah mengapa mereka disebut *negatif!*

b: manusia... tolong...

`hong({ eyes:"normal" });`

h: Beberapa waktu lalu, aku berkata: "Aku hanya ingin bebas dari semua rasa sakit ini."

h: Aku mendapatkan keinginanku. Aku tidak lagi merasakan sakit, atau ketakutan, atau kecemasan ...

h: Aku tidak merasakan apapun.

`_.a3_ending = "jump";`

(#act3_end)



# act3_good_2a

`bb({mouth:"sorry", eyes:"sorry_down"});`

b: Aku sangat terobsesi untuk memastikan tidak ada hal lain yang menyakitimu, sehingga diriku tidak menyadari *akulah* yang menciptakan rasa sakit itu.

```
bb({ eyes:"sorry"});
hong({ body:"yell_2", mouth:"yell", eyes:"blank" });
```

h: BUKAN. S^IALAN^.

`hong({ body:"yell_1" });`

h: ^DEMI TUHAN^. Itu membutuhkan waktu lama untuk akhirnya kau mengetahuinya?!

`hong({ body:"cry", mouth:"cry", eyes:"blank" });`

h: Kamu bisa menyelamatkan kami dari banyak masalah, dasar anjing besar ^sial^. Mengapa kamu tidak menyadarinya lebih awal? .

`_.apologized_for_hurt = true;`

(#act3_good_2q)



# act3_good_2b

`hong({ body:"normal", mouth:"angry", eyes:"look_right" });`

h: ...kamu *meminta maaf.*

`hong({ eyes:"angry", MOUTH_LOCK:true });`

h: ...

h: Minta maaf untuk *apa*?

(#act3_good_2q)


# act3_good_2q

`bb({mouth:"sorry", eyes:"sorry"});`

{{if _.apologized_for_hurt}}
(#act3_good_2q_already_apologized)
{{/if}}

{{if !_.apologized_for_hurt}}
(#act3_good_2q_not_already_apologized)
{{/if}}


# act3_good_2q_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"less_angry" });`

[Maaf, aku bukan pelindung yang baik.](#act3_good_3_protector)

[Maaf, aku tidak menghormatimu.](#act3_good_3_respect)

[Maafkan aku..](#act3_good_4)


# act3_good_2q_not_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"angry" }, 0);`

[Maaf, aku memiliki manusia yang buruk!](#act3_bad_2_terrible) `bb({mouth:"normal", eyes:"normal"})`

[Maaf, aku tidak menghormatimu](#act3_good_3_respect)

[Maaf, aku menyakitimu.](#act3_good_3_hurt)



# act3_good_3_protector

`bb({eyes:"sorry_down"});`

b: Itu tugas saya untuk memperingatkanmu mengenai bahaya *sebenarnya*, tapi aku hanya menggonggong seperti mobil dan tukang pos.

`bb({eyes:"sorry_up"});`

b: Menggonggong di bayangan. Banyak menggonggong.

`bb({eyes:"sorry"});`

b: Masuk akal jika kamu ingin memberangus saya.

`bb({eyes:"sorry_down"});`

b: Maafkan aku.

(#act3_good_4)



# act3_good_3_respect

`bb({eyes:"sorry_down"});`

b:Saya seharusnya menjadi *anjing penjagamu* yang setia, tapi aku bertindak seolah-olah kamu harus *mematuhiku*.

`bb({eyes:"sorry_up"});`

b: Ada perbedaan antara pelindung dan sipir penjara, dan aku telah melewati batas.

`bb({eyes:"sorry_down"});`

b: Maafkan aku.

(#act3_good_4)



# act3_good_3_hurt

`bb({eyes:"sorry_down"});`

b: Aku sangat terobsesi untuk memastikan tidak ada hal lain yang menyakitimu, sehingga diriku tidak menyadari *akulah* yang menciptakan rasa sakit itu.

`bb({eyes:"sorry_up"});`

b: Aku adalah anjing yang buruk.

`bb({eyes:"sorry_down"});`

b: Maafkan aku.

(#act3_good_4)


# act3_good_4

```
music(null,{fade:3});
hong({ eyes:"less_angry", MOUTH_LOCK:true },0);
```

h: ...

```
hong({ body:"stop", mouth:"stop", eyes:"blank" });
```

h: Ya, yah, itu merupakan ide yang bodoh.

h: Aku hanya melakukan ini untuk mengacaukanmu, dan, yah, saya mengacaukanmu.

h: Anggap saja babak ini seri, oke?

```
bb({ mouth:"sorry", eyes:"sorry" });
bb({ MOUTH_LOCK:true });
```

b: ...

b: Okay.

h: Okay.

n: *SERI*

`_.a3_ending = "walkaway";`

(#act3_end)









# act3_end

```
Game.clearText();
publish("act3-in");
publish("hp_hide");
Game.FORCE_CANT_SKIP = true;
```

{{if _.a3_ending=="walkaway"}}
(#act3_walkaway)
{{/if}}

{{if _.a3_ending=="jump"}}
(#act3_jump)
{{/if}}






# act3_walkaway

```
publish("start-walkaway-anim");
Game.WORDS_HEIGHT_BOTTOM = 205;
```

(...3501)

```
sfx("bottle_toss");
publish('hong-next');
publish("act3",["roofhunter",7]);
```

(...667)

```
publish("act3",["dd",4]);
publish("act3",["roofhunter",26]);
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("concrete_step2");
```

(...667)

```
publish('hong-next');
publish("act3",["roofhunter",27]);
```

`Game.FORCE_CANT_SKIP = false;`

r: Oh *ayolah*. Setelah semua yang binatang itu lakukan, kamu sudah *menyerah?*

r: Ada apa, bocah? Apakah kamu *takut?*

```
publish('hong-next');
publish("act3",["roofhunter",26]);
```

h2: Iya.

h2: Aku takut.

`publish('hong-next')`

h2: Dan itu tidak masalah!

`publish('hong-next')`

h2: Tidak masalah untuk takut.

`publish('hong-next')`

(...500)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1167)

```
publish('hong-next');
```

(...833)

```
publish('hong-next');
sfx("rustle2");
```

(...1333)

```
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",31]);
sfx("concrete_step4");
```

(...667)

```
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("door");
```

(...1333)

```
publish('hong-next');
sfx("concrete_step2");
```

(...501)

```
publish('hong-next');
Game.FORCE_CANT_SKIP = false;
sfx("lock_door");
publish("act3",["roofhunter",32]);
```

(...2001)

```
publish("act3",["roofhunter",33]);
```

r: Apa dia baru saja mengunci pintu?

```
Game.clearAll();
_.INJURED = false;
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2000)

(#act4)




# act3_jump

```
publish("start-jump-anim");
Game.FORCE_TEXT_Y = 300;
```

(...2001)

```
publish('hong-next');
sfx("bottle_toss");
```

(...833)

```
sfx("concrete_step1");
sfx("claps");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",28]);
```
(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step2");
publish('hong-next');
publish("act3",["roofhunter",28]);
```

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",34]);
```

(...1167)

```
sfx("rustle2");
publish('hong-next');
```

(...1001)

`publish('hong-next')`

b: tidak...

(...501)

`Game.clearText();`

`publish('hong-next')`

(...1333)

```
sfx("quack");
publish('hong-next');
```

(...1333)

`publish('hong-next')`

b: tidak tidak tidak

(...501)

`Game.clearText();`

`publish('hong-next')`

(...2001)

```
sfx("rustle2");
publish('hong-next')
```

(...501)

```
sfx("concrete_step1");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",30]);
```

(...167)

```
sfx("concrete_step2");
publish('hong-next');
```

(...167)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",2]);
publish("act3",["roofhunter",15]);
```

(...167)

```
sfx("bottle_slip");
publish('hong-next');
publish("act3",["dd",3]);
publish("act3",["roofhunter",16]);
```

(...833)

```
sfx("rustle");
publish('hong-next');
```

(...167)

`publish('hong-next')`

(...167)

```
publish('hong-next');
Game.FORCE_TEXT_Y = 325;
Game.OVERRIDE_FONT_SIZE = 50;
```

b: TIDAK!

(...400)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-injury-show");
publish("hide_tabs");
```

(...2000)

```
sfx("hospital1");
publish("act4-injury", [1]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital2");
publish("act4-injury", [2]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital3");
publish("act4-injury", [3]);
```

(...8000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...5500)

`_.INJURED = true;`

(#act4)
