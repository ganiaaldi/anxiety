# act1

```
SceneSetup.act1();
```

(...300)

n: DAN INI ADALAH KECEMASAN MANUSIA

n: _KAMU_ ADALAH KECEMASAN ITU

{{if window.localStorage.continueChapter=="replay"}}
(#act1_replay)
{{/if}}

{{if window.localStorage.continueChapter!="replay"}}
(#act1_normal)
{{/if}}



# act1_replay

`hong({mouth:"0_neutral", eyes:"0_neutral"})`

h: Oh hei! Kita kembali kesini lagi?

`hong({eyes:"0_neutral"})`

n: PEKERJAANMU UNTUK MELINDUNGI MANUSIA DARI *BAHAYA*

`bb({eyes:"look", mouth:"small_lock"})`

n: FAKTANYA, MEMULAI GAME INI MENEMPATKAN MEREKA KE DALAM *BAHAYA*

n: CEPAT, PERINGATKAN MEREKA!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Manusia! Dengar, kita dalam bahaya! Para pemain...

[...akan menyiksa kita lagi!](#act1_replay_torture)

[...tidak akan menemukan akhir cerita lain!](#act1_replay_alternate)

[...akan mendapat disonansi ludonarrative!](#act1_replay_dissonance)

# act1_replay_torture

```
window.HACK_REPLAY = JSON.parse(localStorage.act4);
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

{{if window.HACK_REPLAY.act1_ending=="fight"}}
b: Mereka akan membuat kita menringkuk menjadi bola dan menangis!
{{/if}}

{{if window.HACK_REPLAY.act1_ending=="flight"}}
b: Mereka akan mematikan ponselmu untuk memberikan serangan panik!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="fight"}}
b: Mereka *Tidak* akan membuat kita  memukul tuan rumah pesta!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="flight"}}
b: Mereka akan membuat kita bersimpati memukul penjahat kebenaran!
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="jump"}}
h: Yah setidaknya mereka tidak menyuruh kita melompat dari atap in--
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="walkaway"}}
b: MEREKA AKAN MEMBUAT KITA MELOMPAT DARI ATAP.
{{/if}}

`bb({body:"fear"});`

b: SEMUA HAL BARU MENGERIKAN AKAN TERJADI, DAN KEMUDIAN KITA AKAN--

(#act1_replay_end)


#act1_replay_alternate

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Tentu, cerita secara *keseluruhan* tetap sama, tetapi setiap bab memiliki dua kemungkinan akhir, ditambah satu opsi dialog bercab--

`bb({body:"fear"});`

b: Pemain akan merasa kecewa, menutup tab browser ini, menghapus aplikasi, lalu kita akan--

(#act1_replay_end)


# act1_replay_dissonance

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: hal cabul-apa sekarang?

`bb({eyes:"normal"});`

b: Alur cerita tentang bagaimana kamu dapat *MEMILIH* untuk membangun kolaborasi dengan ketakutanmu,

`bb({eyes:"normal_right"});`

b: Tapi mengulang kembali permainan akan memberikan cerita sama, yang berarti *PILIIHAN* tidaklah penting,

`bb({eyes:"narrow_eyebrow"});`

b: Dengan demikian menunjukan kontradiksi antara pesan dan mekanisme permainan,

`bb({eyes:"fear"});`

b: Dengan demikian mengungkap susunan dari naratif dunia ini,

`bb({body:"fear"});`

b: Lalu kita akan--

(#act1_replay_end)


# act1_replay_end

`bb({body:"panic"})`

b: MATIIIIIIIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.clearText();
```

(...1001)

```
bb({body:"laugh"});
hong({body:"laugh"});
Game.clearText();
sfx("laugh");
```

(...5001)

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"0_sammich"});
```

h: Oke mari kita kembali ke karakter.

```
Game.clearText();
```

n4: (BIARKAN _KECEMASANMU_ BLAH BLAH MIRIP DENGAN _KETAKUTANMU_ BLAH BLAH KAMU MENGETAHUI LUBANGNYA)

```
sfx("squeak");
hong({body:"0_squeeze"});
bb({body:"squeeze"});
```

(#act1_normal_choice)



# act1_normal

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: Ya Tuhan, serigalaku kembali. Faaaaanntastis.

`hong({eyes:"0_neutral"})`

n: PEKERJAANMU ADALAH MENJAGA MANUSIA DARI *BAHAYA*

`bb({eyes:"look", mouth:"small_lock"})`

n: FAKTANYA, ROTI LAPIS ITU MENEMPATKAN MEREKA KE DALAM *BAHAYA* SAAT INI

n: CEPAT, PERINGATKAN MEREKA!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Manusia! Dengar, kita dalam bahaya! Bahayanya adalah..

`bb({body:"squeeze"})`

n4: (BIARKAN _KECEMASANMU_ KELUAR UNTUK BERMAIN! PILIH YANG PALING SAMA DENGAN _KETAKUTANMU_)

(#act1_normal_choice)

# act1_normal_choice

[Kita makan sendirian untuk makan siang! Lagi!](#act1a_alone) `bb({body:"squeeze_talk"})`

[Kita tidak produktif ketika makan!](#act1a_productive) `bb({body:"squeeze_talk"})`

[Roti putih itu buruk untuk kita!](#act1a_bread) `bb({body:"squeeze_talk"})`

# act1a_alone

```
bb({body:"normal", mouth:"small", eyes:"narrow"});
hong({body:"0_sammich"});
```

b: Apa kamu tahu bahwa kesepian dikaitkan dengan kematian dini dikarenakan merokok sebanyak 15 batang perhari?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad 2010, PLoS Medicine)

`hong({eyes:"0_annoyed"})`

h: Hm, terimakasih telah mengutip dari sumber tetapi--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Yang berarti jika kita tidak bergaul dengan seseorang *sekarang* kita akan-

`bb({body:"panic"})`

b: MATIIIIIIIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "alone");
publish("hp_show");
```

(...2500)

`_.fifteencigs = true`

n: KAMU MENGGUNAKAN *KETAKUTAN TIDAK DICINTAI*

(#act1b)

# act1a_productive

```
bb({body:"normal", mouth:"small", eyes:"normal"});
hong({body:"0_sammich"});
```

b: Keluarkan laptopmu dan lakukan beberapa pekerjaan sekarang!
`hong({eyes:"0_annoyed"})`

h: Hm, aku tidak suka mendapat remah-remah di keybo--

```
bb({mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Jika kita tidak berkontribusi pada masyarakat maka kita adalah masyarakat parasit !

b: Badan masyarakat akan pergi ke dokter untuk pengobatan guna membunuh masyarakat parasit , lalu kita akan--

```
bb({body:"panic", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: MATIIIIIIIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "bad");
publish("hp_show");
```

(...2500)

`_.parasite = true`

n: KAMU MENGGUNAKAN *KETAKUTAN MENJADI ORANG BURUK*

(#act1b)

# act1a_bread

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich", eyes:"0_annoyed"});
```

h: Apakah penelitian itu telah direplika--

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Gandum olahan meningkatkan gula darah kita, sehingga mereka harus mengamputasi anggota tubuh kita dan kita akan--
`bb({body:"panic"})`

b: MATIIIIIIIIIIIIIIIIII

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "harm");
publish("hp_show");
```

(...2500)

`_.whitebread = true`

n: KAMU MENGGUNAKAN *KETAKUTAN MENJADI ORANG TERSAKITI*

(#act1b)

# act1b

n: INI SANGAT EFEKTIF!

`bb({mouth:"smile", eyes:"smile"});`

b: Lihat, manusia? Aku adalah serigala penjagamu!

`bb({body:"pride_talk"});`

b: Percayai nalurimu! Perasaanmu selalu benar!

`bb({body:"pride"});`

n: DAPATKAN BATAS ENERGI ANDA KE NOL

n: UNTUK MELINDUNGI FISIK + SOSIAL + MORAL, KAMU DAPAT MENGGUNAKAN:

n: KETAKUTAN *MENJADI TERSAKITI* #harm#

n: KETAKUTAN *TIDAK DICINTAI* #alone#

n: DAN KETAKUTAN *MENJADI ORANG BURUK* #bad#

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: (TIPS: BERMAIN DENGAN PILIHAN DENGAN KEPRIBADIANMU TERDALAM, KETAKUTAN TERGELAP!~)

h: ...

```
hong({body:"putaway"});
sfx("rustle");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

(...1000)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h: kamu tahu, apa mungkin sudah waktunya aku mengecek ponsel.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: LINDUNGI MANUSIA

n: DARI DUNIA. DARI ORANG LAIN. DARI DIRI SENDIRI.

n: SEMOGA BERUNTUNG

(...500)

`Game.clearText()`

(...500)

(#act1c)

# act1c

`music('battle', {volume:0.5})`

n: RONDE PERTAMA: *MULAI!*

`bb({body:"normal", mouth:"normal", eyes:"normal"});`

h: Huh. Umpan Facebook mengatakan ada pesta pada akhir pekan ini.

`bb({eyes:"uncertain"});`

b: Bukankah aneh ketika mengadakan pesta *setiap* akhir pekan?

`bb({eyes:"uncertain_right"});`

b: Kepuasan batin apa yang mereka coba isi? Sepertinya dalam diri mereka sangatlah kacau!

`hong({eyes:"surprise"});`

h: Lalu, Aku mendapat undangan?

`bb({eyes:"fear", mouth:"normal"});`

b: Baiklah kalau begitu!

[Katakan ya, atau kita mati karena kesepian!](#act1c_loner)

[Katakan tidak, itu akan penuh dengan obat-obatan!](#act1c_drugs)

[Abaikan saja, kita hanya membuat pesta menjadi sedih.](#act1c_sad)

# act1c_loner

{{if _.fifteencigs}}
b: Lima belas rokok perhari, manusia! Lima belas!
{{/if}}

{{if !_.fifteencigs}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if !_.fifteencigs}}
b: Maka tidak ada seorang pun yang datang ke pemakaman kita, mereka akan membuang abu kita ke laut, dan dimakan oleh ikan puas,
{{/if}}

{{if !_.fifteencigs}}
b: dan kita menjadi KOTORAN IKAN PAUS!
{{/if}}

{{if !_.fifteencigs}} `_.whalepoop = true` {{/if}}

(...500)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

{{if !_.fifteencigs}}
b: Jadi ya, kita harus pergi ke pesta itu!
{{/if}}

{{if _.parasite}}
b: Bawa saja laptopnya agar kita bisa bekerja, dan tidak menjadi masyarakat parasit.
{{/if}}

{{if _.whitebread}}
b: Asalkan mereka tidak menyajikan ROTI PUTIH
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: TUHAN. Jika itu akan membuatmu diam, baiklah.

h: Aku akan mengatakan ya.

{{if _.whalepoop}}
b: Kotoran paus, manusia! Kotoran ikan paus!
{{/if}}

`_.partyinvite="yes"`

(#act1d)

# act1c_drugs

`bb({mouth:"small", eyes:"fear"});`

{{if _.whitebread}}
b: atau bahkan lebih buruk.. ROTI PUTIH
{{/if}}

{{if _.whitebread}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if _.whitebread}}
b: Kita akan overdosis sabu dan roti putih, sehingga mereka tidak akan bisa memasukan mayat gemuk ke dalam tungku kremasi!
{{/if}}

{{if !_.whitebread}}
b: Kita akan overdosis pada begitu banyak obat dan mereka akan bertanya tubuh kami *sudah* dibalsem!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.parasite}}
b: Selain tidak bisa berpesta, kita membutuhkan pekerjaan agar tidak menjadi masyarakat parasit!
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: TUHAN. Jika itu akan membuatmu diam, baiklah.

h: Aku akan mengatakan tidak.

`_.partyinvite="no"`

(#act1d)

# act1c_sad

`bb({eyes:"uncertain_right", mouth:"normal"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.fifteencigs}}
b: Semua yang kita lakukan hanya menangis di pojokan merenung tentang kesepian sama mematikannya dengan merokok.
{{/if}}

{{if _.parasite}}
b: Semua yang kita lakukan di pesta adalah khawatir tentang bagaimana kita menjadi produktif.
{{/if}}

{{if _.whitebread}}
b: Semua yang kita lakukan adalah khawatir tentang makanan tidak sehat akan membunuh kita.
{{/if}}

```
bb({mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"lookaway"});
```

h: hee aku heran kenapa.

`hong({eyes:"neutral"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: Jadi jika kita datang mereka akan merasa tidak nyaman, tetapi jika kita menolak undangan maka rasanya buruk!
`bb({body:"fear", eyes:"fear"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: SEMUA YANG KITA LAKUKAN MEMBUAT ORANG MERASA BURUK, JADI KITA HARUS MENJADI BURUK

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`hong({mouth:"anger", eyes:"anger"});`

h: Uhh. Jika itu akan membuatmu diam, baiklah.

h: Aku akan mengabaikan undangannya.

`_.partyinvite="ignore"`

(#act1d)

# act1d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"annoyed"});
```

h: Bagaimanapun. Facebook terlalu berlebihan. Aku butuh sesuatu lebih tenang, yang tidak menimbulkan kecemasan.

`hong({eyes:"neutral"});`

h: Apa yang baru di Twitter?

`bb({eyes:"look"});`

[Oh tidak, lihat berita mengerikan itu!](#act1d_news)

[Oh tidak, apakah itu tweet berisi rahasia tentang *kita?*](#act1d_subtweet)

[Hei, animasi kucing minum susu](#act1d_milk)


# act1d_news

```
bb({eyes:"pained1"});
music(null, {fade:2});
```

b: Tuhan, dunia ini rasanya seperti terbakar bukan?

```
bb({eyes:"pained2"});
hong({mouth:"sad", eyes:"sad"});
```

b: Rasanya semua akan berakhir, seperti semuanya sekarat dan kita dikutuk dan tidak ada yang bisa kita lakukan untuk itu.

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
bb({mouth:"shut"});
```

b: ...

`bb({mouth:"smile", eyes:"smile"});`

b: Mari kita Retweet cerita itu!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.badnews=true`

```
music('battle', {volume:0.5});
hong({mouth:"anger", eyes:"anger"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Oke aku akan meretweet itu!

`hong({mouth:"neutral", eyes:"annoyed"});`

h: Persetan, mari kita lihat Snapchat.

(#act1e)


# act1d_subtweet

`bb({eyes:"fear"});`

b: Ini tweet! Sebuah tweet yang licik dan licik!

`hong({eyes:"annoyed"});`

h: Mungkin saja tidak?

`bb({eyes:"narrow", mouth:"small"});`

b: Tapi bagaimana jika mereka semua berbicara dibelakang punggung kita

h: Mereka ti-

`bb({body:"fear", eyes:"fear", mouth:"normal"});`

b: DI DEPAN DARI BELAKANG KITA

`hong({eyes:"sad", mouth:"sad"});`

h: Aku ti-

`bb({eyes:"narrow", mouth:"small"});`

b: Tapi *bagaimana jika*

h: A--

`bb({eyes:"narrow_eyebrow"});`

b: *Bagaimana jika*

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
hong({mouth:"shut"});
```

h: ...

(...1000)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.subtweet=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KAY, gonna try Snapchat.

(#act1e)

# act1d_milk

`hong({mouth:"smile", eyes:"neutral"});`

h: Haha itu lucu, mari kita retweet, aku su--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KUCING TIDAK DAPAT MENCERNA SUSU DAN KITA ADALAH ORANG MENGERIKAN KARENA MENIKMATI PELECEHAN HEWAN

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("18p", "bad");
```

(...2500)


`_.catmilk=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: O-ke, mari coba Snapchat.

(#act1e)

# act1e

`hong({mouth:"neutral", eyes:"neutral"});`

h: Hah, foto dari kemarin malam. Jadi *begitulah* seperti apa pesta mingguan terlihat.

{{if _.partyinvite=="yes"}} (#act1e_said_yes) {{/if}}

{{if _.partyinvite=="no"}} (#act1e_said_no) {{/if}}

{{if _.partyinvite=="ignore"}} (#act1e_said_ignore) {{/if}}

# act1e_said_yes

`hong({mouth:"sad", eyes:"annoyed"});`

h: Oof, terlihat terlalu ramai untuk kecemasanku.

h: Mungkin aku seharusnya tidak mengatakan ya untuk datang ke sini?

```
hong({mouth:"neutral", eyes:"neutral"});
bb({mouth:"normal", eyes:"normal"});
```

[Ubah jawaban kita? Seperti orang brengsek?!](#act1e_yes_dontchange)

[Ubah jawaban kita! Ini terlalu ramai!](#act1e_yes_changetono)

{{if _.subtweet}}
[Yahh mereka benar-benar melakukan tweets kita.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Tunggu, kita meretweet tanpa pemeriksaan fakta.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Tahukah kamu, posturmu benar-benar buruk?](#act1e_ignore_posture)
{{/if}}

# act1e_yes_dontchange

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Mereka menghitungmu untuk datang dan sekarang kamu menghianati kepercayaan mereka? Apa kamu ingin mati sendiri?!

{{if _.fifteencigs}}
b: LIMA BELAS. BATANG ROKOK.
{{/if}}

{{if _.whalepoop}}
b: KOTORAN. IKAN PAUS.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Diamm, aku tetap menjawab ya!

(#act1f)

# act1e_yes_changetono

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Apakah kamu mengetahui tentang penyerbuan manusia?

```
bb({body:"fear", mouth:"small", eyes:"narrow"});
hong({eyes:"sad", mouth:"sad"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Pada tahun 2003 klub malam Pulau Rhode mengalami kebakaran dan kepanikan membuat orang-orang memacetkan pintu keluar sehingga 100 orang terbakar hingga mati-

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({mouth:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: APAKAH KAMU INGIN MENGETAHUI APA YANG TERJADI-

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 2.5;
```

b: KATAKAN TIDAK KATAKAN TIDAK KATAKAN TI--


```
bb({body:"normal", eyes:"fear", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
hong({eyes:"anger", mouth:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Diamm, aku akan mengganti jawaban ke tidak!

(#act1f)

# act1e_said_no

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... itu terlihat menyenangkan.

h: Mungkin seharusnya aku datang ke undangan?

`bb({mouth:"normal", eyes:"normal"});`

[Ubah jawaban kita? Seperti orang brengsek?!](#act1e_no_dontchange)

[Ubah jawaban kita? Jangan mati sendirian](#act1e_no_changetoyes)

{{if _.subtweet}}
[Yahh mereka benar-benar melakukan tweets kita.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Tunggu, kita meretweet tanpa pemeriksaan fakta.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Tahukah kamu, posturmu benar-benar buruk?](#act1e_ignore_posture)
{{/if}}

# act1e_no_dontchange

`bb({eyes:"anger"})`

b: Semua orang mengandalkan kita!

b: ...untuk membiarkan mereka pergi sendiri dan membiarkan mereka berpesta tanpa gangguan menyebalkan{{if _.whitebread}}pengunyah roti putih{{/if}} yang menjijikan sepertimu--


```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
bb({body:"normal", eyes:"uncertain", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Diamm, aku tetap berkata tidak!

(#act1f)

# act1e_no_changetoyes

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Kesepian kronis meningkatkan kadar kolesterol serta resiko penyakit kardiovaskular dan stroke!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.fifteencigs}}
b: LIMA BELAS. BATANG ROKOK.
{{/if}}

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Diamm, aku akan mengubah jawaban menjadi ya! Oh Tuhan!

(#act1f)

# act1e_ignore_subtweet

```
bb({eyes:"fear", mouth:"small"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Semua tweets yang bermasalah kembali bertengger!

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.7;
```

b: Kita akan dipanggil dan diseret dengan tali diatas punggung kuda menyusuri jalan raya!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Kenapa kamu seperti ini?!

(#act1f)

# act1e_ignore_factcheck

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Kita menyebarkan informasi palsu! Kita menghancurkan kepercayaan pers!

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Kita akan menjadi alasan fasisme bangkit dari puing-puing demokrasi!

```
bb({body:"normal", eyes:"anger"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
_.factcheck = true;
```

h: Kenapa kamu seperti ini?!

(#act1f)

# act1e_ignore_posture

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Apakah kamu ingin pretzel untuk tulang belakang?! Berhenti membungkuk di depan layar!

```
bb({body:"meta"});
```

b: Itu berlaku untukmu juga.

```
bb({body:"normal", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Kenapa kamu seperti ini?!

(#act1f)

# act1e_said_ignore

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... itu terlihat menyenangkan.

h: Mungkin seharusnya aku tidak mengabaikan undangan?

`bb({mouth:"normal", eyes:"normal"});`

[Tetap abaikan, kita adalah kotoran pesta.](#act1e_ignore_continue)

[Sebenarnya, katakan ya.](#act1e_ignore_changetoyes)

[Sebenarnya, katakan tidak.](#act1e_ignore_changetono)

# act1e_ignore_continue

`hong({eyes:"annoyed"});`

h: Itu agak kasar untuk terus mengabaikan mereka, bukan?

`bb({eyes:"normal_right"});`

b: Yahh orang lain selalu mengabaikan *kita*, jadi

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

b: jadi anggap saja itu impas

(#act1f)

# act1e_ignore_changetoyes

`hong({eyes:"surprise", mouth:"smile"});`

h: Kamu.. membiarkanku untuk bersenang-senang?

b: Yahh, maksudku, kesepian *bisa* membunuh kita.

`hong({eyes:"neutral", mouth:"neutral"});`

(#act1e_no_changetoyes)

# act1e_ignore_changetono

`bb({eyes:"narrow"});`

b: Ini terlalu ramai. Keramaian itu berbahaya.

(#act1e_yes_changetono)


# act1f

```
hong({mouth:"neutral", eyes:"neutral"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: Whatever. New Tinder notification.

`bb({eyes:"uncertain"})`

b: What, that hookup app?

`hong({eyes:"annoyed"})`

h: It's not a hookup app, it's just a way to meet new peopl--

`bb({eyes:"narrow"})`

b: It's a hookup app.

```
hong({eyes:"surprise", mouth:"smile"});
bb({eyes:"normal"});
```

h: Oh, I got a match! They look cute!

```
bb({eyes:"narrow_eyebrow"});
hong({eyes:"sad", mouth:"anger"})
```

h: Please don't ruin this for m--

```
bb({body:"panic"});
Game.OVERRIDE_TEXT_SPEED = 2.0;
```

b: DANGER DANGER DANGER DANGER DANGER DANGER

`bb({body:"fear", eyes:"fear", mouth:"normal"})`

[We're being *used* by other people.](#act1f_used_by_others)

[We're just *using* other people.](#act1f_using_others)

[YOUR MATCH IS A SERIAL KILLER](#act1f_killer)

# act1f_used_by_others

`bb({body:"point_crotch", eyes:"normal", mouth:"normal"})`

b: Random hookups may be able to fill the hole down there,

b: but they can never fill the hole...

`bb({body:"point_heart", eyes:"pretty", mouth:"small"})`

b: in *here*.

(...1000)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: The point is WE'RE GOING TO DIE ALONE

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.hookuphole=true`

(#act1g)

# act1f_using_others

`bb({eyes:"narrow", mouth:"small"})`

b: You think other people's genitals are Pokémon for us to collect?

```
bb({body:"sing", eyes:"pretty", mouth:"shut"});
music("pokemon");
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

```
Game.FORCE_TEXT_DURATION = 1000;
Game.FORCE_NO_VOICE = true;
```

b: ♫ (pokemon theme song)-

(...5600)

```
bb({mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2400;
```

b: ♫ I wanna be, the ^slut^ti-est-

(...500)

```
bb({eyes:"narrow", mouth:"small"});
Game.FORCE_TEXT_DURATION = 2100;
```

b: ♫ Like no one ever was-

(...1500)

```
bb({eyes:"pretty"});
Game.FORCE_TEXT_DURATION = 2300;
```

b: ♫ Thighs n' ^ass^, voluptuous breast-

(...500)

```
bb({eyes:"fear", mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2000;
```

b: ♫ with sweaty ^dick^ and balls!-

(...1000)

```
bb({eyes:"smile", mouth:"smile"});
Game.FORCE_TEXT_DURATION = 1000;
```

b: ♫ PERVY-MON! GOTTA CA-

```
Game.FORCE_CANT_SKIP = false;
Game.clearText();
music(false);
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: The point is we're a manipulative creep.

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`_.pokemon=true`

(#act1g)

# act1f_killer

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.whitebread}}
b: They'll trap you in a well and force-feed you white bread to fatten you up so they can wear your skin like a suit!
{{/if}}

{{if _.parasite}}
b: They'll bludgeon you with a pomodoro timer and say "YOU SHOULDA BEEN MORE PRODUCTIVE YOU PARASITE"
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: They'll tear your flesh to gory confetti, turn your entrails into streamers, and mix your blood into a punch bowl!
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: How's THAT for a party invite?!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.serialkiller=true`

(#act1g)

# act1g

```
bb({body:"normal", mouth:"normal", eyes:"look"});
hong({body:"2_tired"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
music(false);
```

h: ...

(...500)

h: i'm so sick of this game.

(...700)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h:
{{if _.fifteencigs}}"loneliness will kill us"... {{/if}}
{{if _.parasite}}"we're a society-parasite"... {{/if}}
{{if _.whitebread}}"don't eat that, it'll kill us"... {{/if}}
{{if _.subtweet}}"they're talking behind our back"... {{/if}}
{{if _.badnews}}"the world is burning"... {{/if}}
{{if _.hookuphole}}"we'll die alone"... {{/if}}
{{if _.serialkiller}}"they're a serial killer"... {{/if}}
{{if _.catmilk}}"cats can't digest milk"... {{/if}}
{{if _.pokemon}}a ^crappy^ parody song... {{/if}}

h: i just want to live my life.

h: i just want to be free from all this... pain.

`bb({eyes:"look_sad"});`

b: Hey... human...

`Game.OVERRIDE_TEXT_SPEED = 0.5;`

b: It'll be okay.

(...600)

`bb({body:"point_heart", eyes:"look_sad_smile", mouth:"smile"});`

b: As your loyal guard-wolf, I'll always keep an eye out for danger, and do my best to keep you safe.

`bb({body:"normal", eyes:"look_sad", mouth:"smile"});`

b: I promise.

(...600)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({body:"phone1", eyes:"neutral", mouth:"neutral"});
```

h: Last app. Instagram. What you got?

`hong({eyes:"sad"});`

h: It's... more party pictures.

`hong({mouth:"sad"});`

h: Everyone looks so happy. Free from worry. Free from anxiety.

`hong({mouth:"anger"});`

h: God, why can't I be like them? Why can't I just be *normal?*

`bb({eyes:"normal_right"});`

b: Speaking of parties, about this weekend's invite. Here's my FINAL decision:

`bb({eyes:"normal"});`

[We should go.](#act1g_go) `Game.OVERRIDE_CHOICE_LINE=true`

[We should not go.](#act1g_dont) `Game.OVERRIDE_CHOICE_LINE=true`

# act1g_go

`_.act1g = "go"`

(#act1h)

# act1g_dont

`_.act1g = "dont"`

(#act1h)

# act1h

b: We sh--

```
bb({eyes:"wat", mouth:"small"});
hong({body:"2_fuck"});
```

h: *^FUCK^.*

`hong({body:"2_you"});`

h: YOU.

(...500)

b: w

(...1500)

`bb({eyes:"wat_2"});`

b: wha?

`hong({body:"phone1", eyes:"anger", mouth:"anger"});`

h: I'm going to say YES to that party,

{{if _.act1g=="go"}}
h: NOT because you want me to, but because *I* want to.
{{/if}}

{{if _.act1g=="dont"}}
h: Precisely BECAUSE you don't want me to.
{{/if}}

```
hong({body:"putaway"});
sfx("rustle");
```

h: You're NOT in control of me.

```
sfx("rustle2");
hong({body:"0_sammich", eyes:"0_annoyed", mouth:"0_neutral"});
```

h: Now excuse me while I eat this delicious sandwich in ^goddamn^ peace.

`hong({body:"2_sammich_eat"});`

(...601)

```
sfx("sandwich");
hong({body:"2_sammich_eaten", eyes:"0_lookaway", mouth:"0_chew1"})
```

(...601)

```
bb({body:"normal", eyes:"uncertain", mouth:"shut"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
```

b: ...

```
bb({eyes:"normal_right"});
Game.OVERRIDE_TEXT_SPEED = 1;
```

b: ...

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 4;
```

b: ..................

(...500)

`bb({mouth:"normal"});`

[AHHHH WE'RE GONNA DIE](#act1h_death) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH EVERYONE HATES US](#act1h_loneliness) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH WE'RE HORRIBLE PEOPLE](#act1h_worthless) `Game.OVERRIDE_CHOICE_LINE = true;`

# act1h_death

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WE'RE GONNA DIE AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "harm");
```

(...2500)

(#act1i)

# act1h_loneliness

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH EVERYONE HATES US AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "alone");
```

(...2500)

(#act1i)

# act1h_worthless

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WE'RE HORRIBLE PEOPLE AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "bad");
```

(...2500)

(#act1i)

# act1i

```
bb({mouth:"smile_lock", eyes:"smile", body:"normal"});
music('battle', {volume:0.5});
```

n: CONGRATULATIONS

(...500)

n: YOU'VE SUCCESSFULLY PROTECTED YOUR HUMAN'S PHYSICAL + SOCIAL + MORAL NEEDS

n: WHY, LOOK HOW GRATEFUL THEY ARE!

(...500)

n: NOW THAT THEIR ENERGY IS ZERO, YOU CAN DIRECTLY CONTROL THEIR ACTIONS

`bb({mouth:"smile", eyes:"normal"});`

n: PICK YOUR ENDING MOVE

`bb({mouth:"small_lock", eyes:"fear"});`

n: *FINISH THEM*

[{FIGHT: Punish your stressful phone!}](#act1i_phone) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIGHT: Curl up in a ball and cry!}](#act1i_cry) `Game.OVERRIDE_CHOICE_LINE=true`

# act1i_phone

`bb({mouth:"normal", eyes:"narrow"})`

b: Your phone was giving you a panic attack!

`bb({eyes:"anger"})`

b: Zuckerberg and Co are hijacking your mental health for venture capitalist money!

```
bb({body:"fear", eyes:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Punish your phone! Destroy it! Kill it!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "fight";
```

b: KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL IT KILL I--

(#act1j)

# act1i_cry

`bb({eyes:"fear", mouth:"normal"})`

b: The whole world is filled with danger!

```
bb({body:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Do like the armadillo! Curl up into a ball for self-defense!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "flight";
```

b: CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CRY CURL UP AND CR-- 

(#act1j)

# act1j

`SceneSetup.act1_outro()`