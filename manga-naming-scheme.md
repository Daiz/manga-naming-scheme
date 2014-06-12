# Manga Naming Scheme

#### **Name of Manga [lang] - ch000-000 (v00) [Extra Information] [Group]{revision}.zip**

- **Name of Manga** is ***required***. A full title ***must*** always be used. New releases ***must*** use the same title as older releases. For first releases with no older releases to go by, here is how the title should be decided:
  - Japanese should be romanized with [Hepburn romanization](http://en.wikipedia.org/wiki/Hepburn_romanization). Long vowels (ō, ū, etc) are to be written without macrons (ou, uu, etc).
  - Non-Japanese katakana words should be romanized to the matching language (eg. レールガン should become "Railgun").
  - If a kanji is given a foreign katakana reading, the previous also applies (eg. 超電磁砲 read as レールガン should be "Railgun", ***not*** "Choudenjihou")
  - If the series has a canonical English / Western name *from the original author(s)* to go with its Japanese kanji title, it should be used instead of romanizing the Japanese kanji. Examples:
      -  シドニアの騎士 should use "Knights of Sidonia", ***not*** "Sidonia no Kishi"
      - 蒼き鋼のアルペジオ should use "Arpeggio of Blue Steel", ***not*** "Aoki Hagane no Arpeggio"
      - 鋼の錬金術師 should use "Fullmetal Alchemist", ***not*** "Hagane no Renkinjutsushi"
      - 進撃の巨人 should use "Attack on Titan", ***not*** "Shingeki no Kyojin"
  - Title Case ***should*** be used for capitalization.
- **[lang]** is a [three-letter ISO-639-2 language code](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) ***required*** for Non-English releases. English releases are ***required*** to omit this.
- **ch000** chapter number is ***required***. If multiple chapters are included (eg. if you are doing a full volume release), the range ***must*** be indicated with the **-000**. Chapter numbers ***must*** be padded to three digits minimum.
- If a chapter has no clear number associated with it, the logically or chronologically previous chapter number should be chosen and incremented by 0.1 - **[Extra Information]** is ***recommended*** in these cases to specify the type of the chapter.
- **(v00)** volume numbering is ***required*** for tankobon scans, and ***unallowed*** for magazine scans. This allows one to easily distinguish magazine and tankobon releases, and volume information usually is not available at the time of a magazine release anyway. Volume numbers ***must*** be padded to two digits minimum.
- **[Extra Information]** is ***optional***.
- **[Group]** is ***required***. If group is not known, **[Unknown]** ***must*** be used.
- **{revision}** is ***optional***. Recommended formatting is either **{r0}** or **{v0}**.
- **.zip** A file extension is ***required***. Zip is the ***recommended*** archive format due to its universality.

### Exceptions for Oneshots
- Oneshots ***must*** omit all numbering - **ch000-000 (v00)**.
- Oneshots ***must*** include **[Extra Information]**, which ***must*** include *Oneshot* at minimum.

### Examples (In natural sorting order)
```
Name of Manga - [Oneshot from Comic Q] [Unknown].zip
Name of Manga - ch001-005.1 (v01) [Unknown].zip
Name of Manga - ch006-010 (v02) [FooScans].zip
Name of Manga - ch010.1 (v02) [Omake] [FooScans].zip
Name of Manga - ch011 (v03) [FooScans].zip
Name of Manga - ch012-013 [BarScans].zip
Name of Manga - ch014 [BarScans].zip
Name of Manga - ch014 [BarScans]{v2}.zip
Name of Manga - ch015 [BarScans].zip
Name of Manga - ch015.1 (v03) [Omake] [FooScans].zip
Name of Manga - ch015.2 (v03) [Extras] [FooScans].zip
Name of Manga - ch016-020.1 (v04) [FooScans].zip
Name of Manga [jpn] - ch011-015.2 (v03) [Unknown].zip
Name of Manga [jpn] - ch014 [Unknown].zip
```