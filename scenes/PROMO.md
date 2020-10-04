# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[BERMAIN!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Jadi sebelum memulai, bagaimana *anda* ingin membaca ?

`publish("show_options_bottom")`

# intro-start-2

n3: Sekarang, mari kita mulai cerita kita..

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: INI ADALAH MANUSIA

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: DAN INI ADALAH KECEMASAN MANUSIA

n: _KAMU_ ADALAH SANG KECEMASAN ITU

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Tidak. Tidak, tidak mendengarkan. Aku akan memeriksa ponselku.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: PEKERJAANMU UNTUK MELINDUNGI MANUSIA DARI *BAHAYA*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Duhh! Kamu menghabiskan hidupmu di Twitter! Lagi!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Ya, aku bertanya mengapa aku tidak hanya duduk dan mendengarkan pikiranku lebih sering.

`hong({eyes:"neutral"});`

n: CEPAT, PERINGATKAN MEREKA MENGENAI *BAHAYA!*

```
bb({eyes:"look"});
```

[Oh tidak, lihat berita mengerikan itu!](#act1d_news)

[Oh tidak, apakah itu tweet berisi rahasia tentang *kita?*](#act1d_subtweet)

[Hei, animasi kucing minum susu](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Haha itu lucu, aku su--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KUCING TIDAK DAPAT MENCERNA SUSU DAN KITA ADALAH ORANG MENGERIKAN KARENA MENIKMATI PELECEHAN HEWAN

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



