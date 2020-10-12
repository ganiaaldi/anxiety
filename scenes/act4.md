# act4

```
SceneSetup.act4();
publish("SAVE_GAME", ["act4"]);
Game.FORCE_CANT_SKIP = true;
```

(...5001)

```
publish("set_how_many_prompts", [1]);
Game.FORCE_CANT_SKIP = false;
Game.CLICK_TO_ADVANCE = true;
```

n3: (permainan otomatis tersimpan)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
var hong_frame = _.INJURED ? 9 : 0;
publish("act4", ["hong_walks_in",hong_frame]);
sfx("grass_step1", {volume:0.1});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.2});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.25});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.3});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...1667)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...1333)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.20});
```

(...167)

```
publish("act4_hong_sits");
```

(...66)

```
publish("act4", ["hong_transition", "next"]);
sfx("squeak");
```

(...133)

`publish("act4", ["hong_transition", "next"]);`

(...1333)

```
publish("act4", ["hong_transition", "next"]);
sfx("rustle");
```

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1001)

```
publish("act4", ["hong_transition", "next"]);
```

(...333)

```
publish("act4", ["hong_transition", 9]);
sfx("sandwich");
```

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1466)

`publish("act4-out-1");`

(...201)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

```
publish("act4-show-chars");
Game.FORCE_CANT_SKIP = false;
```

(...901)

`hong({body:"sigh_1"})`

(...601)

```
hong({body:"sigh_2"});
bb({eyes:"look_down"});
```

h: *huft*

```
hong({body:"hold", eyes:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Jadi apa moral dari cerita ^menyeramkan^ ini?

`hong({body:"one_up", eyes:"annoyed"})`

h: Apa yang kita *pelajari*? Aku *adalah* makluk bodoh, "temanku" *yang* memanfaatkanku, dan kita hampir' *mati*.

`hong({body:"normal", eyes:"normal"})`

{{if _.INJURED}}
[Yah, belum lagi tagihan rumah sakit.](#act4a_bill)
{{/if}}

{{if !_.INJURED}}
[Yah, belum lagi kerusakan pada hati.](#act4a_liver)
{{/if}}

[Yah, itu *adalah* skenario terburuk.](#act4a_worst)

[Yah, Aku benar.](#act4a_right)

# act4a_bill

`hong({eyes:"annoyed_l", mouth:"narrow"});`

h: Benar. Aku tidak berpikir rencana asuransiku mencakup "menjadi orang ^bodoh^".

`hong({eyes:"annoyed", mouth:"normal"});`

b: Namun ... kita selamat!

`hong({eyes:"normal"});`

h: ?

(#act4b)

# act4a_liver

`bb({eyes:"normal_d"});`

b: Kita benar-benar memangkas beberapa tahun dari harapan hidupmu ...

`bb({eyes:"surprise"});`

b: Tapi setidaknya kita masih *punya* harapan hidup! Kita selamat!

```
hong({eyes:"surprise"});
bb({eyes:"normal"});
```

h: ?

(#act4b)

# act4a_worst

`bb({eyes:"normal_d"});`

b: Namun...

h: Hm?

`bb({eyes:"surprise"});`

b: Kita selamat!

(#act4b)

# act4a_right

`bb({eyes:"normal_d"});`

b: Tapi... kamu juga benar.

`hong({eyes:"surprise"});`

h: Hm?

`bb({eyes:"normal"});`

b: Aku *adalah* serigala yang berteriak serigala. Jadi ketika bahaya *sebenarnya* datang, Kamu-secara wajar- tidak mempercayaiku.

`bb({eyes:"surprise_r"});`

b: Namun, kita selamat!

(#act4b)

# act4b

```
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

b: Terlepas dari segalanya, kita masih di sini.

`hong({eyes:"suspect"});`

{{if _.INJURED}}
h: Kamu terlihat tenang mengingat kita baru saja mengalami pengalaman yang mendekati kematian.
{{/if}}

{{if !_.INJURED}}
h: Kamu terlihat tenang mengingat kita baru saja mengalami pengalaman yang *mendekati* kematian.
{{/if}}

```
hong({eyes:"normal"});
bb({eyes:"annoyed_d", mouth:"narrow"});
```

b: Ya, itu membuat segalanya kurang menakutkan jika dibandingkan. Itu membuatku berpikir.

`bb({eyes:"normal", mouth:"normal"});`

b: Jika aku berkelahi denganmu sial, itu karena aku tidak melindungimu ...

h: Tapi aku melawanmu *juga* sial, itu  karena hanya membuatmu berteriak lebih keras ...

`bb({eyes:"normal_r"})`

b: Lalu mungkin...

`bb({eyes:"normal"})`

h: Mungkin kita tidak harus bertengkar..

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
```

(...301)

`publish("smash",[0]);`

(...2001)

```
publish("smash",[1]);
sfx("smash_glass");
```

(...2601)

```
publish("smash",[2]);
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

(...2001)

`Game.FORCE_CANT_SKIP = false;`

(#act4b_2)

# act4b_2

```
music('dontfight',{fade:5, volume:0.6});
bb({eyes:"annoyed_d"});
```

b: Aku bukan Serigala Besar Buruk. Tapi aku juga bukan serigala penjaga.

`bb({eyes:"sad_d"})`

b: Aku anjing penampungan yang babak belur.

`bb({eyes:"sad"})`

b: Kita telah melalui hal-hal yang sulit. Mungkin trauma atau pengabaian. Itulah mengapa aku terkadang bereaksi berlebihan dan pergi:

```
sfx("yaps", {volume:0.6});
bb({body:"yap_1"});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 215;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: YAP YAP YAP YAP YAP

(...1884)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_CANT_SKIP = false;
bb({body:"normal", mouth:"scream", eyes:"scream_sad"});
```

b: Tapi aku tidak *mau* menjadi anjing pengecut! Aku ingin melindungimu! Aku ingin menjadi anjing yang baik!

`bb({eyes:"sad", mouth:"normal"});`

b: Manusia... maukah kamu membantu menjinakkan serigala ini?

`hong({eyes:"sad"})`

h: A... aku akan mencoba.

`hong({eyes:"normal_l", body:"chin", mouth:"narrow"})`

h: Oke. Hubungan yang sehat dengan emosi. Hubungan membutuhkan komunikasi. Jadi, mari berkomunikasi.

`hong({eyes:"normal", body:"hands_1", mouth:"normal"})`

h: Lima menit berikutnya akan terdengar sangat murahan, tapi mari kita berpura-pura sampai kita berhasil.

```
hong({body:"hands_2", mouth:"normal"});
```

h: Serigala batin yang terhormat... bagaimana *perasaanmu*?

n2: TOTAL KETAKUTAN YANG DIGUNAKAN:

n2: *TERSAKITI* {{_.attack_harm_total}}, *TIDAK DICINTAI* {{_.attack_alone_total}}, *ORANG BURUK* {{_.attack_bad_total}}

n2: KETAKUTAN APA YANG INGIN DIBICARA PERTAMA KALI? (KAMU DAPAT MEMILIH YANG LAIN NANTI)

```
_.a4_fears_discussed = 0;
_.num_thanks = 0;
hong({body:"normal"});
bb({eyes:"normal"});
```

[Aku takut kita akan disakiti.](#act4_harm)

[Aku takut kita akan sendirian.](#act4_alone)

[Aku takut kita orang buruk.](#act4_bad)

# act4_harm

```
_.a4_talked_about_harm = true;
_.a4_fears_discussed += 1;
```

`bb({eyes:"normal_d"})`

b: Aku akan melindungimu untuk kebutuhan keselamatan fisik,

`bb({eyes:"sad_d"})`

b: Tapi *seluruh dunia* terlihat sangat berbahaya. Penuh dengan tragedi dan kejahatan.

`bb({eyes:"sad"})`

{{if _.a4_fears_discussed==1}}
b: Entahlah, *aku* cukup memilih apa yang akan dikatakan selanjutnya. Apa yang *kamu* katakan, manusia?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Sekali lagi, kembali kepadamu, manusia. Bagaimana menurutmu?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Lebih banyak pikiran, manusia?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Kamu benar. Jadi, mari lindungi diri kita sendiri.](#act4_harm_skills)

[Mari kita mengekspos diri kita ke *lebih* bahaya.](#act4_harm_exposure)

[Terima kasih.](#act4_thanks) `_.thanks_for = "physical safety";`

# act4_harm_skills

`bb({eyes:"look_down", body:"paw"})`

b: Tapi... bagaimana? Aku memiliki taring dan cakar, tetapi aku hanyalah sebuah metafora.

```
bb({ body:"normal", eyes:"normal" });
hong({ body:"one_up", eyes:"surprise" });
```

h: Kita bisa belajar bela diri? Bergabung dengan komunitas yang saling melindungi? Meningkatkan kesehatan umum & batasan pribadi kita?

```
bb({ eyes:"annoyed_r" });
hong({ body:"normal", eyes:"normal" });
```

b: Mungkin, tetapi ...

[Di mana kita akan memulai?](#act4_harm_skills_start)

[Bagaimana jika mereka masih tidak bekerja?](#act4_harm_skills_work)

[Bagaimana jika kita berlebihan pada "keamanan"?](#act4_harm_skills_overboard)

# act4_harm_skills_start

`bb({ eyes:"sad_d" })`

b: Ada begitu banyak yang harus dilakukan, begitu banyak kita perlu perbaiki tentang diri kita sendiri. Darimana kita *memulai*?

`hong({ body:"shrug", eyes:"surprise" })`

h: Kita mulai saat ini juga.

`bb({ eyes:"normal", mouth:"narrow" })`

b: Eh?

```
bb({ body:"normal", mouth:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal"});
```

h: Kita sedang mempraktikkan komunikasi yang baik sekarang. Yang akan membantu kita mendeteksi bahaya dengan lebih baik, dengan sedikit kepalsuan positif,

`hong({ eyes:"surprise" });`

h: Dan *itu* akan membantu melindungi kita dari bahaya!

`hong({ eyes:"normal", mouth:"normal" });`

h: Karena itu: ini *adalah* pelatihan pertahanan diri.

`bb({ eyes:"normal_r" })`

b: Hah. Aku mengharapkan lebih dari ini:

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
hong({ eyes:"sad", mouth:"smile" });
bb({ body:"karate_1" });
sfx("hiya");
```

(...1001)

`Game.FORCE_CANT_SKIP = false;`

(#act4_something_else)

# act4_harm_skills_work

`bb({ eyes:"normal" });`

h: Benar, tidak ada 100%  cara untuk melindungi diri kita sendiri .

`hong({ body:"one_up" });`

h: Tapi bahkan peningkatan 1% masih berharga, bukan?

```
bb({ eyes:"annoyed" });
hong({ normal:"one_up" });
```

b: Kamu melihat gelasnya tidak 99% kosong, tetapi 1% penuh?

`bb({ eyes:"normal" });`

h: Yang masih berharga jika Kamu terdampar di gurun.

`bb({ eyes:"closed" });`

b: Baiklah. Bawalah, lalu.

(#act4_something_else)

# act4_harm_skills_overboard

`bb({ body:"chest", eyes:"annoyed" })`

b: Maksudku, seluruh alasan kamu mengabaikan peringatanku adalah karena *Diriku* pergi dengan aman! 

`bb({ body:"normal", eyes:"normal" })`

h: Tidak, kamu benar. Kita ingin melakukan keamanan dalam jumlah secukupnya. Semuanya secukupnya.

`bb({ eyes:"suspect" })`

b: Maaf, *SEGALANYA* dalam secukupnya?

`hong({ eyes:"annoyed" })`

h: *Ada beberapa hal secukupnya* dalam secukupnya.

```
bb({ eyes:"closed" });
hong({ eyes:"normal" });
```

b: Terima kasih telah membuat pernyataanmu konsisten secara berulang.

(#act4_something_else)


# act4_harm_exposure

`bb({ mouth:"scream_talk", eyes:"scream", MOUTH_LOCK:true });`

b: *APA*

```
bb({ mouth:"narrow", eyes:"suspect" });
hong({ body:"one_up" });
```

h: Maksudku, katakanlah seekor anjing takut dengan petir.

`hong({ body:"hands_1" });`

h: Salah satu trik yang digunakan pelatih adalah memutar rekaman suara petir dengan volume rendah, kemudian memberi anjing cemilan agar tetap tenang.

`hong({ body:"hands_2" });`

h: Selama beberapa hari, pelatih menaikkan volume sedikit demi sedikit, sampai anjing mengatasi ketakutannya terhadap petir.

```
hong({ body:"normal", eyes:"surprise" });
bb({ mouth:"normal", eyes:"normal" });
```

h:  Ini disebut paparan terapi!

`hong({ body:"point", eyes:"normal" });`

h: Karena Kamu adalah seekor anjing, itu seharusnya bekerja untukmu juga, bukan? Semua mamalia memiliki respons melawan-atau-lari yang sama.

`hong({ body:"normal" });`

[Bagaimana jika kita tidak *terlalu* sensitif?](#act4_harm_exposure_overboard)

[Bagaimana jika kita terkena bahaya *nyata*?](#act4_harm_exposure_hurt)

[Aku serigala, bukan anjing.](#act4_harm_exposure_dog) `bb({ eyes:"suspect" })`

# act4_harm_exposure_dog

h: Aku akan menunjukkan kebaikan dan kesabaran sampai kamu dijinakkan menjadi anak anjing yang lucu.

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"sad", mouth:"smile" })`

b: aw.

(#act4_something_else)

# act4_harm_exposure_overboard

`bb({ eyes:"annoyed" })`

b: Kita *hanya* melihat apa yang terjadi jika kamu menutup ketakutanmu - Kamu menempatkan dirimu didalam situasi berbahaya *sebenarnya*.

`bb({ eyes:"angry_r", body:"one_up" })`

b: Selain itu, bukankah *terlalu* banyak desensitisasi mengubah kita menjadi psikopat?

`bb({ mouth:"scream", eyes:"scream", body:"two_up" })`

b: Secepatnya kita akan memberikan diri kita hadiah saat menonton film ^porno^

`hong({ eyes:"annoyed" })`

h: Aku... pikir ada garis antara itu dan petir.

`bb({ body:"normal", mouth:"normal", eyes:"suspect" })`

b: Tapi tepatnya *dimana*, manusia? *Dimana?!*

`hong({ eyes:"surprise", body:"one_up" })`

h: Aku tidak tahu. Tapi *kamu* bisa membantuku!

`hong({ eyes:"normal", body:"normal" })`

h: Bekerja dan bernegosiasi denganmu, kita akan menarik garis itu.

`bb({ body:"paw", mouth:"narrow", eyes:"closed" })`

b: Oke. Tapi aku tidak punya jempol yang berlawanan, jadi kamu yang harus menggambar.

(#act4_something_else)

# act4_harm_exposure_hurt

`bb({ body:"two_up", eyes:"angry_r" })`

{{if _.INJURED}}
b: Sebagai contoh: kita melompat dari *atap* yang aneh!*
{{/if}}

{{if !_.INJURED}}
b: Sebagai contoh: kita hampir melompat dari *atap* yang aneh!*
{{/if}}

```
hong({ eyes:"annoyed" });
bb({ body:"normal", eyes:"annoyed" });
```

h: Ya kamu benar. Seseorang *bisa* bertindak terlalu jauh.

`hong({ eyes:"normal" });`

h: Tapi itu sebabnya, jika kita melakukan paparan terapi, kita akan mulai dari yang kecil dan membuat langkah perlahan tapi pasti.

h: Tepat sebelum kita terkena bahaya *aktual*, kita berhenti.

`bb({ eyes:"annoyed_r", mouth:"narrow" });`

b: Ya, aku menggambar garis diantara mendengar petir yang keras, dan berdiri di tengah badai dengan topi runcing yang tinggi.

(#act4_something_else)

# act4_thanks

`_.num_thanks += 1`

{{if _.num_thanks==1}}
(#act4_thanks_1)
{{/if}}

{{if _.num_thanks==2}}
(#act4_thanks_2)
{{/if}}

{{if _.num_thanks==3}}
(#act4_thanks_3)
{{/if}}

# act4_thanks_1

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"annoyed" })`

b: Tunggu, tidak ada argumen untuk menentang apa yang aku rasakan? Hanya ... "terima kasih"?

`hong({ eyes:"surprise", body:"shrug" })`

h: Ya! Terima kasih telah menunjukkan kepedulianmu terhadap diriku.

```
bb({ eyes:"closed_annoyed", MOUTH_LOCK:true });
hong({ eyes:"normal", body:"normal" });
```

b: ...

h: Kamu baik-baik saja?

`bb({ eyes:"super_sad", mouth:"narrow" });`

b: Kamu belum pernah mengatakan *terima kasih* kepadaku sebelumnya.

`hong({ mouth:"smile" });`

h: Aw, kamu serigala besar berbulu halus yang panik.

(#act4_something_else)

# act4_thanks_2

h: Meskipun kamu bereaksi berlebihan, aku menghargaimu yang memperhatikan diriku.

`bb({ eyes:"annoyed" })`

b: Tunggu ... kamu tidak mengulangi "terima kasih" untuk menghindari pembicaraan tentang ketakutan ini, bukan?

```
bb({ eyes:"normal" });
hong({ eyes:"annoyed", body:"chin" });
```

h: Ya, masalahnya rumit, dan aku tidak selalu memiliki jawaban yang siap.

`hong({ eyes:"annoyed_l", body:"one_up" })`

h: Ini tidak seperti kehidupan yang memberimu daftar 3 tanggapan dialog yang telah dibuat sebelumnya.

`hong({ eyes:"normal", mouth:"smile", body:"normal" })`

h: Tapi untuk saat ini, setidaknya aku bisa mengucapkan terima kasih.

b: Terima kasih juga, karena telah mendengarkanku dengan sabar.

`bb({ eyes:"closed" });`

b: Kamu mamalia kecil tanpa bulu.

(#act4_something_else)

# act4_thanks_3

h: Meskipun gonggonganmu membuatku takut, Kamu hanya mencoba melindungi diriku.

`bb({ eyes:"smile_r" });`

b: Oke, jika kamu terus menyanjungku seperti ini, internet akan mendapatkan beberapa ide aneh tentang kita.

```
bb({ eyes:"smile" });
hong({ eyes:"annoyed" });
```

h: Ayolah, aku hanya anak usia kuliah yang rentan dan kamu adalah serigala yang besar dan menakutkan. Apa yang terburuk dari--

`hong({ eyes:"normal", body:"point" });`

h: Sebenarnya jangan jawab itu

(#act4_something_else)




# act4_alone

```
_.a4_talked_about_alone = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"sad_d" });`

b: Aku ingin memastikanmu memenuhi kebutuhan manusia terdalam   untuk dimiliki ...

`bb({ eyes:"sad_u" });`

b: Tapi aku khawatir jika ada orang yang mengenal kita-*yang sebenarnya*-kita akan menakuti mereka semua.

`bb({ eyes:"sad" });`

{{if _.a4_fears_discussed==1}}
b: Entahlah, cukup *aku* memilih apa yang akan dikatakan selanjutnya. Apa yang akan *kamu* katakan, manusia?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Sekali lagi, kembali kepadamu, manusia. Bagaimana menurutmu?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: More thoughts, human?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Aku setuju: mari kita kerjakan kehidupan sosial kita.](#act4_alone_skills)

[Aku pikir orang-orang menyukai kami. Ayo cari tahu?](#act4_alone_experiment)

[Terima kasih.](#act4_thanks) `_.thanks_for = "social belonging";`

# act4_alone_skills

```
bb({ eyes:"normal" });
hong({ body:"chin" });
```

h: Kita bisa melatih keterampilan seperti bertanya, mendengarkan dan berempati, menjadi terbuka dan transparan, dll?

`hong({ eyes:"normal_l" });`

h: Atau buat kebiasaan sosial yang lebih baik, seperti menjadwalkan waktu dengan teman atau pergi ke pertemuan secara teratur?

`hong({ body:"one_up" });`

h: Bisa juga belajar menjadi lebih nyaman dengan penolakan.

`hong({ eyes:"normal" });`

h: Atau belajar untuk mengetahui ketika orang *tidak* menolak kita, mereka hanya lelah atau sedang beristirahat dengan wajah ^jalang^ .

```
hong({ body:"normal" });
bb({ eyes:"annoyed_r" });
```

b: Banyak sekali pilihan. Tapi, tentang "mempelajari keterampilan sosial" ...

[Bukankah itu *manipulatif?*](#act4_alone_skills_manipulative)

[Bukankah itu akan membuat kita *lebih mudah untuk dimanipulasi?*](#act4_alone_skills_manipulated)

[Bagaimana jika kita masih gagal?](#act4_alone_skills_fail)

# act4_alone_skills_manipulative

`bb({ eyes:"suspect" });`

b: Bukankah pembunuh berantai bisa membaca emosi korbannya dengan baik dengan "empati"?

`bb({ eyes:"annoyed" });`

b: Bukankah Charles Manson mendapatkan teman dan mempengaruhi orang?

`hong({ eyes:"annoyed", body:"chin" });`

h: Tidak, kamu benar.

h: "Keterampilan sosial" tidak ada artinya jika kita tidak benar-benar peduli *pada* orang.

`hong({ body:"normal" });`

h: Pada dasarnya, jangan jadi seorang ^brengsek^

`bb({ eyes:"annoyed", mouth:"smile" });`

b: Itu bisa menjadi judul poster disana

`hong({ body:"shrug", mouth:"narrow" });`

h: “Jangan Menjadi Seorang ^Brengsek^™”

(#act4_something_else)

# act4_alone_skills_manipulated

`bb({ eyes:"angry" })`

b: Kita akan menjadi keset Selamat Datang, mengucapkan Tolong dan Terima Kasih saat orang-orang menyeka kaki mereka pada kita!

`bb({ mouth:"scream", eyes:"scream" })`

b: Kita akan mencium banyak pantat, itu akan terlihat seperti kita memakai lipstik coklat!

```
bb({ mouth:"normal", eyes:"normal" });
hong( body:"chin" });
```

h: Nah, kamu benar. "Keterampilan sosial" tidak hanya tentang menyenangkan orang lain, itu juga tentang menetapkan sebuah *batasan.*

`hong( body:"one_up" });`

h: Kita tidak dapat mengundang orang lain ke rumah kita, jika kita tidak memiliki dinding untuk menahan rumah kita.

```
hong( eyes:"angry", mouth:"narrow" });
bb( eyes:"annoyed", mouth:"smile" });
```

h: Juga... mengulang: gambar mental lipstik itu... *iw??*

(#act4_something_else)

# act4_alone_skills_fail

`bb({ eyes:"annoyed" });`

h: Kita mungkin gagal. Sebenarnya, kita *akan* gagal..

```
bb({ eyes:"normal" });
hong({ eyes:"surprise", body:"shrug" });
```

h: Dan itu tidak masalah! Gagal adalah cara seseorang mempelajari sesuatu yang baru pada awalnya!

`hong({ body:"normal", eyes:"normal" });`

h: Jadi mari kita gagal bersama, ya?

`bb({ eyes:"normal_r" });`

b: Tentu, kukira ... skenario terburuk, kita bisa melewati kota dan mendapatkan identitas baru.

`bb({ eyes:"normal" });`

h: Ya, aku pikir itu hanya berharga dua bitcoin hari ini.

(#act4_something_else)

# act4_alone_experiment

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: Kita bisa mencoba beberapa eksperimen!

`hong({ body:"chin" });`

h: Kita bisa mengajak teman untuk hang out, berhubungan kembali dengan sobat lama, atau bahkan sekedar ngobrol dengan barista.

`hong({ body:"normal" });`

h: Aku pikir kita mungkin lebih disukai daripada yang kita duga.

`bb({ eyes:"annoyed" });`

[Bagaimana jika ini adalah *kemenangan* kecil dan murah?](#act4_alone_experiment_cheap)

[Bagaimana jika ini menjadi beban bagi orang lain?](#act4_alone_experiment_burden)

[Tapi obrolan ringan bukanlah hal *nyata* bagi kami!](#act4_alone_experiment_real_us)

# act4_alone_experiment_real_us

`bb({ eyes:"sad" });`

b: Jika kita memasang senyum yang dangkal, kita tidak akan pernah benar-benar terhubung dengan siapa pun,

`bb({ eyes:"super_sad" });`

b: *Tetapi* jika kita terbuka, orang lain akan melihat semua bagian dalam kita yang kacau!

`hong({body:"chin", mouth:"narrow", MOUTH_LOCK:true})`

h: ...

```
hong({body:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Berguling.

b: Apa.

`hong({body:"hands_1"})`

h: Ketika anjing ingin menunjukkan cinta dan kepercayaan, mereka membuat dirinya memperlihatkan perutnya.

`hong({body:"one_up"})`

h: Mungkin kita *belum* cukup aman untuk menjadi terlalu transparan, tetapi dengan pelatihan yang cukup,

`hong({body:"normal", eyes:"surprise"})`

h: Suatu hari kita bisa menunjukkan kepada orang-orang kita bahwa sebenarnya - semua kacau, semua manusia.

```
hong({eyes:"normal"});
bb({ eyes:"super_sad", mouth:"smile", body:"chest" });
```

b: Aku akan mampir jika kamu memberiku hadiah.

`bb({ eyes:"normal", mouth:"normal" });`

h: Tidak.

(#act4_something_else)


# act4_alone_experiment_cheap

b: Mengucapkan "hai" kepada barista bukanlah prestasi medali emas pada Olimpiade Kupu-Kupu Sosial.

```
hong({ body:"point", eyes:"surprise" });
bb({ eyes:"normal" });
```

h: Ini untuk *kita!*

`hong({ body:"one_up", eyes:"annoyed" });`

h: Di arena sosial, kita bahkan bukan kelas bulu, kita seperti... kelas berat.

`hong({ body:"normal", eyes:"normal" });`

h: Jika kita harus mulai dengan kemenangan kecil dan murah, biarlah. Kita harus mendaki anak tangga pertama sebelum anak tangga 1000.

b: Ya! Mungkin setelah mengucapkan "Hai", kita bisa melanjutkan dengan mengatakan...

`bb({ body:"two_up", mouth:"smile", eyes:"smile_u" });`

b: *"Apa kabar?"*

`hong({ body:"shrug", mouth:"smile", eyes:"surprise_l" });`

h: *"Tidak banyak!"*

(#act4_something_else)

# act4_alone_experiment_burden

`bb({ eyes:"suspect_r" })`

b: Mungkin barista hanya ingin membuat kopi , bukan suatu *percobaan* untuk melihat apakah keterampilan sosial kita payah.

`bb({ eyes:"annoyed" })`

h: Nah, jika ternyata kita *menjadi* sebuah beban.

```
hong({ eyes:"surprise" });
bb({ eyes:"normal" });
```

h: Itu bagus untuk diketahui juga!

`hong({ eyes:"normal" });`

h: Kita kemudian dapat belajar bagaimana secara pro-aktif bertanya kepada orang-orang apa yang membuat mereka nyaman, juga mengetahui dan menghormati batasan orang lain.

```
hong({ eyes:"annoyed_l", mouth:"narrow" });
bb({ eyes:"annoyed", mouth:"smile" });
```

h:Kamu tahu, semua "keterampilan antar-pribadi" itu ^omong kosong^ kita lihat itu di brosur konselor.

(#act4_something_else)



# act4_bad

```
_.a4_talked_about_bad = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"annoyed_r" })`

b:  Aku ingin membela kebutuhan moralmu, dan mendorong untuk menjadi orang yang lebih baik,

`bb({ eyes:"sad_d" })`

b: Tapi rasanya jauh di lubuk hati, pada dasarnya kita ... hancur.

`bb({ body:"two_up", eyes:"angry" })`

{{if _.INJURED}}
b:  Dan jangan bilang kita *tidak* kacau. Kita melompat dari *atap*.
{{/if}}

{{if !_.INJURED}}
b: Dan jangan bilang kita *tidak* kacau. Kita hampir melompat dari *atap*.
{{/if}}

`bb({ body:"normal", eyes:"sad" })`

{{if _.a4_fears_discussed==1}}
b: Entahlah, cukup *aku* memilih apa yang akan dikatakan selanjutnya. Apa yang akan *kamu* katakan, manusia?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Sekali lagi, kembali kepadamu, manusia. Bagaimana menurutmu?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Lebih banyak pikiran, manusia?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Jadi kita hancur. Mari kita perbaiki.](#act4_bad_fix)

[Jadi kita hancur. Mari kita terima.](#act4_bad_accept)

[Terima kasih.](#act4_thanks) `_.thanks_for = "moral well-being";`

# act4_bad_fix

```
bb({eyes:"normal"});
hong({body:"chin"});
```

h: Kita perlahan bisa membangun kebiasaan yang lebih baik, membuat hidup kita lebih sejalan dengan apa yang kita hargai,

`hong({body:"one_up"});`

h: Dan jika diperlukan, kita bisa mendapatkan bantuan profesional - terapis atau konselor.

`hong({body:"normal"});`

h: Itulah cara untuk memperbaiki kita.

[Bagaimana jika kita tidak dapat memperbaiki semuanya?](#act4_bad_fix_cant)

[Bagaimana jika kita memperbaiki *terlalu* banyak?](#act4_bad_fix_too_much)

[Kita tidak mampu membayar bantuan profesional.](#act4_bad_fix_afford)

# act4_bad_fix_cant

`hong({eyes:"annoyed"});`

h: Nah, kurasa kamu benar.

h: Kita tidak bisa memperbaiki semuanya.

`bb({mouth:"scream", eyes:"scream_sad"});`

b: Ahhh aku tahu kita akan selalu hancur!

`hong({eyes:"surprise"});`

h: Tapi setidaknya kita bisa *mengurangi* kerusakan.

```
bb({mouth:"normal", eyes:"annoyed"});
hong({eyes:"sad", mouth:"smile"});
```

h: Bekas luka sembuh seiring waktu, tapi tidak pernah hilang. Dan itu tidak apa.

`bb({eyes:"annoyed_r"});`

b: Aku kira. Selain,

```
Game.FORCE_TEXT_Y = 460;
Game.clearText();
publish("act4-sexy", [true]);
```

b: Bekas luka itu * seksi. *

```
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-sexy", [false]);
bb({body:"chest", mouth:"smile_talk", MOUTH_LOCK:true, eyes:"sexy"}, 0);
hong({eyes:"normal", mouth:"normal"}, 0);
```

h: Tolong jangan lakukan itu.

(#act4_something_else)

# act4_bad_fix_too_much

`bb({ eyes:"angry_d" })`

b: Ini terasa mual untuk mengakuinya, tapi ... sebagian dari diriku *ingin* mengalami kelainan ini.

`bb({ eyes:"angry" })`

b: Maksudku, tanpa itu, tidakkah kita akan *membosankan?*

`bb({ eyes:"sad_r", body:"one_up" })`

b: Tanpa gangguan, bukankah seni kita akan menjadi basi dan hambar?

`bb({ eyes:"sad_u", body:"two_up" })`

b: Tanpa gangguan tersebut, bukankah kita tidak dapat terhubung dengan teman-teman kita yang memiliki gangguan tersebut?

`bb({ eyes:"sad", body:"chest" })`

b: Jika kita puas dengan hidup, bukankah kita akan berhenti mendorong diri kita sendiri untuk melakukan hal-hal hebat?

`hong({ MOUTH_LOCK:true })`

h: ...

h: Jika kita bahkan takut... "lari dari ketakutan" ...

h: Aku tidak berpikir kita akan lari dari ketakutan.

`bb({ eyes:"smile_u", body:"normal", mouth:"smile" })`

b: Oh, ya! Wah! Sangat lega!

(#act4_something_else)

# act4_bad_fix_afford

`bb({ body:"one_up", eyes:"sexy", mouth:"normal" })`

b: "Dok, saya ingin sekali saya membayar $ 100 / jam hanya untuk mendengar Anda bertanya *bagaimana perasaan Anda?*"

`bb({ body:"paw", eyes:"closed", mouth:"narrow" })`

b: "Mm-hmm. Dan bagaimana perasaanmu?"

```
bb({ body:"normal", eyes:"normal", mouth:"normal" });
hong({ eyes:"sad" });
```

h: Nah, itu kekhawatiran yang sangat masuk akal.

`hong({ eyes:"annoyed", mouth:"sad" });`

h: Dan sungguh menyebalkan bahwa perawatan kesehatan mental tidak terjangkau oleh banyak orang.

`hong({ eyes:"normal", mouth:"normal" });`

h: Tetap saja, ada beberapa opsi murah atau gratis:

`hong({ body:"chin" })`

h: Sekelompok pendukung, terapi online, pusat kesehatan non profit/pelajar...

`hong({ body:"hands_1" })`

h: Membangun kebiasaan seperti meditasi, tidur nyenyak, mengobrol teratur dengan teman, mempelajari hal-hal baru..

`hong({ body:"hands_2" })`

h: Pergi ke perpustakaan untuk meminjam buku kerja tentang psikoterapi...

`hong({ body:"one_up" })`

h: Ada daftar lengkap sumber daya di akhir permainan ini!

```
hong({ body:"normal" });
bb({ eyes:"annoyed", mouth:"narrow" });
```

b: Yah *itu* tembok keempat tidak akan bertahan lama.

`hong({ body:"point" });`

h: Beberapa hal lebih penting daripada konvensi naratif. Seperti kesehatan mental.

(#act4_something_else)


# act4_bad_accept

```
bb({ eyes:"normal" });
hong({ eyes:"normal_l", body:"one_up", mouth:"narrow" });
```

h: Maksudku, itu yang dikatakan terapis kan? Terima semua emosimu, bahkan yang negatif?

```
bb({ eyes:"annoyed" });
hong({ eyes:"normal", body:"normal", mouth:"normal" });
```

b: Tunggu.

["Terima" dalam artian *menyerah*?](#act4_bad_accept_give_up)

["Terima" dalam artian *setuju*?](#act4_bad_accept_approve)

["Seperti" dalam artian *secara harfiah*?](#act4_bad_accept_literally)

# act4_bad_accept_give_up

`bb({ eyes:"angry", body:"one_up" });`

b:  Apakah menurutmu Martin Luther King akan berkata, "Sial kita tidak bisa duduk di depan bus, mari kita *terima* saja?"

`bb({ eyes:"angry_r", body:"two_up" });`

b: Mengapa Kompleks Industri Pertolongan Pertama berpikir bahwa mengibarkan bendera putih adalah suatu *kebijaksanaan yang mendalam?    *

`bb({ eyes:"annoyed", body:"normal" });`

h: Menurutku terapis "menerima" hal-hal buruk seperti dalam: mengakui bahwa mereka ada dan sulit diubah,

h: Tapi belum tentu menyerah pada komitmen untuk berubah.

`bb({ eyes:"suspect" });`

b: Kemudian terapis harus mengatakan *mengakui*, bukan *menerima*.

`hong({ body:"chin", eyes:"annoyed" });`

h: Ya kalau dipikir-pikir, "menerima" itu agak membingungkan.

`bb({ eyes:"closed", mouth:"narrow" });`

b: Ya, aku *mengakui* itu.

(#act4_something_else)

# act4_bad_accept_approve

`bb({ eyes:"angry" });`

b: Seperti itu *bagus* bahwa kita rusak atau sesuatu? Tidak!

`bb({ eyes:"angry_r", body:"one_up" });`

b: Semua penulis skenario Hollywood yang meromantisasi penyakit mental itu sangat kasar!

`bb({ eyes:"angry", body:"two_up" });`

b: Memiliki gangguan mental *menyebalkan!* Itu merampas *nyawa orang!* Mengapa kita harus "menerima" itu ?!

`bb({ body:"normal" });`

h: Aku pikir yang dimaksud terapis itu "menerima" emosi kita seperti dalam: bersabar bersama mereka.

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: Seperti bagaimana bergumul di pasir hisap membuatmu tenggelam lebih cepat, dan solusinya adalah dengan sabar berbaring,

`hong({ eyes:"surprise" });`

{{if _.INJURED}}
h: Melawanmu, ketakutanku, membuatku ingin melompat dari atap.
{{/if}}

{{if !_.INJURED}}
h: Melawanmu, ketakutanku, membuatku hampir ingin melompat dari atap.
{{/if}}

`hong({ body:"normal", eyes:"normal" });`

h: Sebaliknya, solusinya adalah melakukan apa yang kita lakukan sekarang - bukan untuk bertengkar, tetapi dengan sabar bersama-sama.

`bb({ eyes:"annoyed" });`

b: Kemudian mereka harus mengatakan *itu* daripada beberapa kata bermasalah seperti kata "menerima".

`hong({ body:"chin", eyes:"annoyed" });`

h: Ya kalau dipikir-pikir, "menerima" agak menyebalkan.

`bb({ eyes:"closed_annoyed", mouth:"narrow" });`

b: Aku tidak menerima kata "menerima".

(#act4_something_else)

# act4_bad_accept_literally

`bb({ eyes:"sad", body:"one_up" });`

b: Tapi kita sudah *tahu* kamu seharusnya tidak menganggapku secara harfiah!

`bb({ eyes:"sad_u", body:"two_up" });`

b: Keseluruhan *masalah* adalah aku ingin membantumu, tetapi aku payah menggunakan kata-kata untuk melakukannya!

`bb({ eyes:"sad", body:"normal" });`

h: Aku pikir terapis berarti "menerima" emosimu seperti: "jangan melawan atau mengabaikannya."

`hong({ eyes:"surprise", body:"one_up" });`

h: Untuk mendengarkanmu, bekerja bersama *dengan* dirimu, tetapi jangan anggap apa yang aku katakan sebagai 100% kebenaran literal.

```
hong({ eyes:"normal", body:"normal" });
bb({ eyes:"annoyed", mouth:"normal" });`
```

b: Kemudian mereka harus mengatakan *itu* daripada beberapa kata bermasalah seperti kata "menerima".

`hong({ body:"chin", eyes:"annoyed" });`

h: Aku rasa mereka juga payah menggunakan kata-kata.

(#act4_something_else)




# act4_something_else

```
bb({ body:"normal", mouth:"normal", eyes:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal" });
```

{{if _.a4_fears_discussed==1}}
h: Ngomong-ngomong, ada hal lain yang ingin kamu bicarakan?
{{/if}}

{{if _.a4_fears_discussed==2}}
h: Jadi, ada hal lain di yang memberatkan hatimu?
{{/if}}

{{if _.a4_fears_discussed==3}}
(#act4_something_else_2)
{{/if}}

{{if _.a4_talked_about_harm!=true}}
[Aku takut kita akan disakiti.](#act4_harm)
{{/if}}

{{if _.a4_talked_about_alone!=true}}
[Aku takut kita akan sendirian.](#act4_alone)
{{/if}}

{{if _.a4_talked_about_bad!=true}}
[Aku takut kita orang buruk.](#act4_bad)
{{/if}}

[Nah, aku baik-baik saja untuk saat ini.](#act4c_prelude)

# act4_something_else_2

h: Oke, aku pikir kita sudah membicarakan semua ketakutan kita sekarang.

b: Ya, hanya ada tiga ketakutan.

h: Yup, tepat tiga.

b: Betul.

(#act4c)

# act4c_prelude

h: Obrolan yang bagus, tim.

(#act4c)

# act4c

```
Game.clearText();
music(null,{fade:3});
bb({body:"normal", eyes:"normal", mouth:"normal", MOUTH_LOCK:true},0);
hong({body:"normal", eyes:"normal", mouth:"normal"},0);
```

b: ...

`hong({MOUTH_LOCK:true},0)`

h: ...

`bb({eyes:"annoyed_d"})`

b: Kamu tahu, ini bukan *permainan*.

`bb({eyes:"angry_d", body:"one_up"})`

b: Membangun hubungan yang sehat dengan emosimu tidak sesederhana mengklik tombol di layar.

`bb({eyes:"sad", body:"normal"})`

b: *Bisakah* kita benar-benar akur?

b: *Bisakah* kita bekerja sama, sebagai satu tim?

`hong({eyes:"sad", body:"one_up"})`

h: Nah,

```
hong({eyes:"surprise_l"});
bb({eyes:"normal"});
```

a: Per-permisi...

```
Game.clearText();
publish("act4-in-2");
music('campus', {volume:0.5, fade:1});
```

(...2101)

(#act4d)

# act4d

`Game.WORDS_HEIGHT_BOTTOM = 221;`

`publish("act4", ["alshire", 0]);`

a: Ma-ma-maukah kamu jika aku duduk bersamamu untuk makan siang?

`publish("act4", ["alshire", 1]);`

{{if _.TOP_FEAR=="harm"}}
s: *Ini* orang yang kamu sukai? Mengapa mereka duduk sendiri seperti pembunuh berantai psiko?
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: Menanyakan orang yang kamu sukai apakah dirimu bisa duduk bersama mereka? Tahukah kamu betapa kita terdengar sangat *membutuhkannya*?!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: *Ini*  orang yang kamu sukai? Kita menyela kedamaian dan ketenangan mereka! Kita benar-benar beban!
{{/if}}

`publish("act4", ["alshire", 2]);`

a: A- Aku maksud- itu, itu tidak apa jika tidak, aku hanya...

`publish("act4", ["alshire", 3]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "h2"`

[Tunggu, bukankah aku melihatmu di pesta?](#act4d_recognition) `publish("act4", ["hong_to_alshire",1])`

[Ya tentu saja! Ayo sini.](#act4d_yes) `publish("act4", ["hong_to_alshire",2])`

[Maaf, aku butuh waktu sendiri sekarang.](#act4d_no) `publish("act4", ["hong_to_alshire",8])`

# act4d_recognition

`publish("act4", ["hong_to_alshire",2]);`

h2: Ya kamu yang ada di sofa! Di pesta pertama yang kukunjungi ..

`publish("act4", ["hong_to_alshire",10]);`

{{if _.a2_ending=="fight"}}
h2: Di mana aku mengalami serangan panik dan meninju tuan rumah.
{{/if}}

{{if _.a2_ending=="flight"}}
h2: Dimana aku mengalami serangan panik itu dan berlari keluar sambil menangis.
{{/if}}

```
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Tunggu manusia, kita mungkin membuat mereka tidak nyaman.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, aku tidak bermaksud menempatkanmu di tempat!

`publish("act4", ["hong_to_alshire",4]);`

h2: Hanya mengingat wajah yang bersahabat saja.

```
publish("act4", ["hong_to_alshire",5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: AHHHHH AKU TAHU! MEREKA PSYCHO PANIK BERBAHAYA !
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: AHHH KESAN PERTAMA YANG KITA BUAT ADALAH "SAKSI TRAUMA SAYA"! ITU BERARTI MEREKA BENCI KITA!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AAAHHH KITA MEMBUAT SESEORANG INGAT PERISTIWA TRAUMATIK. KEHADIRAN KITA MENYAKITI ORANG LAIN.
{{/if}}

(#act4e)

# act4d_yes

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Bangun manusia, mereka tampak tidak nyaman.

```
publish("act4", ["hong_to_alshire", 6]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, tentu saja tidak ada tekanan!

`publish("act4", ["hong_to_alshire", 4]);`

h2: Bilang saja, kamu dapat duduk di sini kalau mau.

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: MEREKA TERLALU * RAMAH! SEPERTI TED BUNDY, PEMBUNUH DALAM SERI TV!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: MEREKA HANYA BERSANDIWARA BAIK! TIDAK ADA SATUPUN *KESERIUSAN* UNTUK DEKAT DENGAN KITA!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AHHH KITA SELALU MEMBUAT ORANG LAIN MERASA CANGGUNG! KITA NODA DI BUMI!
{{/if}}

(#act4e)

# act4d_no

```
publish("act4", ["hong_to_alshire", 9]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Bangun manusia, mereka tampak tidak nyaman.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Ah, Aku tidak bermaksud kasar!

`publish("act4", ["hong_to_alshire", 6]);`

h2: Aku hanya butuh waktu untuk memproses emosiku. Tolong jangan menganggapnya sebagai penolakan pribadi.

```
publish("act4", ["hong_to_alshire", 7]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: APA YANG SAKIT, PIKIRAN APA YANG MEREKA PROSES ?! APA KEINGINAN GELAP YANG MENGISI HATI PSYCHO INI ?!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: KITA TELAH DITOLAK SECARA PRIBADI! KITA TIDAK AKAN PERNAH DICINTAI!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: KITA MENGGANGGU EMOSI MEREKA! SEKARANG MEREKA AKAN DI TRAUMAS SELAMANYA DAN ITU SEMUA KESALAHAN KITA!
{{/if}}

(#act4e)

# act4e

```
Game.WORDS_HEIGHT_BOTTOM = 195;
publish("act4", ["alshire", 6]);
```

s: LARI LARI LARI LARI LARI LARI LARI LARI LARI LARI LARI LARI

```
Game.clearText();
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["alshire", 10]);
sfx("pop");
```

(...1001)

```
publish("act4", ["alshire", 11]);
sfx("alshire_run");
```

(...2601)

```
publish("act4-out-3");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
```

(...1201)

`publish("act4-jumpcut-hong");`

h: Hah. Itu aneh. Entah apa yang terjadi di kepala mereka.

`publish("act4", ["hong_closer", 2]);`

h: Ngomong-ngomong, tadi kamu bilang apa?

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 6]);
```

b: Eh, aku lupa? Sesuatu tentang tim dan pekerjaan?

```
publish("act4", ["bb_closer", 0]);
publish("act4", ["hong_closer", 3]);
```

h: ¯\_(ツ)_/¯

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 4]);
```

b: Mereka berkata kamu harus "berdamai" dengan emosimu, seolah-olah emosimu adalah *penjahat perang*

`publish("act4", ["bb_closer", 7]);`

b: Tapi aku ingin kita membuat *lebih* dari sekedar kedamaian! Aku ingin kita menjadi *sekutu!*

`publish("act4", ["bb_closer", 3]);`

b: Aku ingin menjadi anjing penjaga yang baik. Seperti lapar & haus adalah untuk kebutuhan fisikmu,

`publish("act4", ["bb_closer", 8]);`

b: Aku ingin menjadi kebutuhan *psikologismu*- kebutuhanmu akan keamanan, rasa memiliki, kebaikan.

`publish("act4", ["bb_closer", 1]);`

b: Tapi... Aku payah dalam pekerjaanku, jadi aku membutuhkanmu untuk melatihku.

`publish("act4", ["bb_closer", 4]);`

b:  Aku tidak "selalu benar", atau "selalu tidak rasional". Aku hanya... mencoba yang terbaik. Jadi tolong,

`publish("act4", ["bb_closer", 30]);`

b: Bantu aku!

`publish("act4", ["bb_closer", 6]);`

b: Padahal, mengajari anjing tua trik baru *akan* memakan waktu cukup lama. Mungkin *bertahun-tahun.*

`publish("act4", ["bb_closer", 3]);`

b:  Dan terkadang aku akan kambuh, aku akan menyelinap ke kebiasaan lamaku.

`publish("act4", ["bb_closer", 2]);`

b:  Aku akan menggonggong pada bayangan. Aku akan menakutimu dengan kata-kata. Aku bahkan mungkin menunjukkan beberapa gambar mengganggu dari... sesuatu.

`publish("act4", ["bb_closer", 9]);`

b: Maaf! Aku anjing penampungan yang babak belur! Anjing yang babak belur terkadang buang air di tempat tidurmu!

`publish("act4", ["bb_closer", 4]);`

b: Tapi jika Anda sabar denganku... dan diam dan duduk dengan diriku ...

`publish("act4", ["bb_closer", 8]);`

b: Mungkin kamu bisa menjinakkan serigala ini.

`publish("act4", ["bb_closer", 0]);`

`Game.clearText();`

(...1000)

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Anjing baik.](#act4f-pat-bb) `Game.OVERRIDE_CHOICE_SPEAKER = "h"; publish("act4", ["hong_closer", 2]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "b"`

[Manusia baik.](#act4f-pat-hong) `Game.OVERRIDE_CHOICE_SPEAKER = "b"; publish("act4", ["bb_closer", 8]);`

# act4f-pat-hong

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 13]);
```

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...6501)

`publish("act4", ["bb_closer", 15]);`

(...1001)

(#act4f)

# act4f-pat-bb

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 10]);
```

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...6501)

`publish("act4", ["bb_closer", 12]);`

(...1001)

(#act4f)

# act4f

```
Game.FORCE_CANT_SKIP = false;
publish("act4", ["bb_closer", 16]);
publish("act4", ["hong_closer", 5]);
```

{{if _.fifteencigs}}
b: AAAAA ANDA MASIH MAKAN SENDIRI LIMA BELAS ROKOK AAAAA
{{/if}}

{{if _.parasite}}
b: AAAAA ANDA MASIH TIDAK PRODUKTIF SAAT MAKAN KITA MASYARAKAT-PARASIT AAAAA
{{/if}}

{{if _.whitebread}}
b: AAAAA ANDA BERLEBIH MAKAN ROTI PUTIH AAAAA
{{/if}}

```
publish("act4", ["bb_closer", 18]);
publish("act4", ["hong_closer", 6]);
sfx("yaps", {volume:0.6});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 205;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: YAP YAP YAP YAP YAP

(#credits)
