# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

```
_.PLAYED_BEFORE = !!window.localStorage.continueChapter;
```

{{if !_.PLAYED_BEFORE}}
`Game.OVERRIDE_FONT_SIZE=30;`
{{/if}}

{{if !_.PLAYED_BEFORE}}
[#play1# BERMAIN! #play2#](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if _.PLAYED_BEFORE && window.localStorage.continueChapter=="act2"}}
[_LANJUTKAN_: Pesta](#act2) `publish("LOAD_GAME", ["act2"]); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if _.PLAYED_BEFORE && window.localStorage.continueChapter=="act3"}}
[_LANJUTKAN_: Pesta Lainnya](#act3) `publish("LOAD_GAME", ["act3"]); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if _.PLAYED_BEFORE && window.localStorage.continueChapter=="act4"}}
[_LANJUTKAN_: Roti Lapis Lainnya](#act4) `publish("LOAD_GAME", ["act4"]); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if _.PLAYED_BEFORE && window.localStorage.continueChapter=="replay"}}
`Game.OVERRIDE_FONT_SIZE=30;`
{{/if}}

{{if _.PLAYED_BEFORE && window.localStorage.continueChapter=="replay"}}
[#play1# MULAI ULANG! #play2#](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if _.PLAYED_BEFORE}}
[Pilih Bab Cerita](#chapter-select) `Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

[(content notes)](#intro-play-button) `Game.OVERRIDE_CHOICE_LINE=true; publish('show_cn');`

# chapter-select

`publish("HACK_chselect");`

[I. Roti Lapis](#intro-start) `publish("HACK_chselect_end"); publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

[II. Pesta](#act2) `publish("HACK_chselect_end"); publish("LOAD_GAME", ["act2"]); Game.OVERRIDE_CHOICE_LINE=true;`

{{if window.localStorage.act3}}
[III. Pesta Lainnya](#act3) `publish("HACK_chselect_end"); publish("LOAD_GAME", ["act3"]); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if !window.localStorage.act3}}
[III. Pesta Lainnya]()
{{/if}}

{{if window.localStorage.act4}}
[IV. Roti Lapis Lainnya](#act4) `publish("HACK_chselect_end"); publish("LOAD_GAME", ["act4"]); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if !window.localStorage.act4}}
[III. Roti Lapis Lainnya]()
{{/if}}

{{if window.localStorage.credits}}
[V. Ucapan Terima Kasih](#to-credits) `publish("HACK_chselect_end"); Game.OVERRIDE_CHOICE_LINE=true;`
{{/if}}

{{if !window.localStorage.credits}}
[V.  Ucapan Terima Kasih]()
{{/if}}

[(menu awal)](#intro-play-button) `publish("HACK_chselect_end"); Game.OVERRIDE_CHOICE_LINE=true;`

# to-credits

`stopAllSounds();`

(...101)

(#credits)

# intro-start

(...500)

`clearText()`

n3: Selamat datang! Ini bukanlah sebuah "permainan," melainkan sebuah cerita interaktif. Semoga kamu menyukainnya!

n3: Jadi sebelum kita memulai, bagaimana *kamu* ingin membaca?

`publish("show_options_bottom")`

# intro-start-2

n3: Mantap! Catatan: kamu dapat mengubah pengaturan dengan ikon ⚙ dibawah. Selain itu, permainan tersimpan otomatis di setiap bab!

n3: Sekarang, mari kita mulai cerita kita...

`clearText()`

(...1000)

`publish("intro-to-game-2")`

n2: INI ADALAH MANUSIA

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`