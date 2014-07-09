# Manga Archive Naming Scheme

#### **Name of Manga [lang] - c000-000 x0 (mag/mix/v00-00) [Extra Information] [Group]{revision}.zip**

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
- **c000** chapter number is ***required***. If multiple chapters are included (eg. if you are doing a full volume release), the range ***must*** be indicated with the **-000**. Chapter numbers ***must*** be padded to three digits minimum.
  - If a series start with no clear chapter numbering of its own, the **c** ***must*** be dropped so that only numbers remain.
  - Oneshots should be numbered as **000**, with no **c** in front. **[Extra Information]** stating that it is a oneshot **should** be included.
  - If the series starts using clear chapter numbers at some point afterwards, then the **c** ***must*** be reintroduced.
  - If chapter numbers go into four digits, the **c** ***must*** be changed into **d** to ensure correct sorting.
  - With chapter ranges, the second number ***must*** not have any unit associated with it, unless a numbering system transition happens.
  - Examples:
```
    Some Oneshot That Gets Serialized - 000 (mag) [Oneshot] [Group].zip
    Some Oneshot That Gets Serialized - c001 (mag) [Group].zip
    Some Oneshot That Gets Serialized - c002 (mag) [Group].zip
    
    Unnumbered Initial Chapters - 001-003 (v01) [Group].zip
    Unnumbered Initial Chapters - 009-014 (v04) [Group].zip
    Unnumbered Initial Chapters - 015-c006 (v05) [Group].zip
    Unnumbered Initial Chapters - c007-016 (v06) [Group].zip
    
    Very Large Chapter Numbers - c998 (mag) [Group].zip
    Very Large Chapter Numbers - c999 (mag) [Group].zip
    Very Large Chapter Numbers - d1000 (mag) [Group].zip
    Very Large Chapter Numbers - d1001 (mag) [Group].zip
    
    Very Large Chapter Numbers Bunched - c986-995 (v98) [Group].zip
    Very Large Chapter Numbers Bunched - c996-d1005 (v99) [Group].zip
    Very Large Chapter Numbers Bunched - d1006-1015 (v99) [Group].zip
    
    Very Unrealistic But Technically Possible - 000-d1500 (mag) [Group].zip
```
- **x0** is intended to be used with chapters that deviate from a clear numbering system (eg. decimal chapter numbers like 10.5) already in place and ***must*** be used for these, and ***must*** be left out for regular chapters. **[Extra Information]** is ***recommended*** in these cases to specify the type of the chapter. If sequential special chapters go beyond one digit, **x** is to be changed to **y**. In the rare case of specials going to three digits in the same sequence, **z** is to be used. Examples:
```
    Serialized in Two Magazines - c001 (mag) [Magazine One] [Group].zip
    Serialized in Two Magazines - c001 x1 (mag) [Magazine Two] [Group].zip
    Serialized in Two Magazines - c002 (mag) [Magazine One] [Group].zip
    Serialized in Two Magazines - c002 x1 (mag) [Magazine Two] [Group].zip
    
    Lots of Bonus Chapters - c014 (mag) [Group].zip
    Lots of Bonus Chapters - c014 x1 (mag) [Extra] [Group].zip
    Lots of Bonus Chapters - c014 x2 (mag) [Special Arc 1] [Group].zip
    Lots of Bonus Chapters - c014 x3 (mag) [Special Arc 2] [Group].zip
    Lots of Bonus Chapters - c014 x4 (mag) [Special Arc 3] [Group].zip
    Lots of Bonus Chapters - c014 x5 (mag) [Special Arc 4] [Group].zip
    Lots of Bonus Chapters - c015  (mag) [Group].zip
    Lots of Bonus Chapters - c015 x1 (mag) [Extra] [Group].zip
    
    Way Too Much Bonus Chapters - c020 x8 (v04) [Group].zip
    Way Too Much Bonus Chapters - c020 x9 (v04) [Group].zip
    Way Too Much Bonus Chapters - c020 y10 (v04) [Group].zip
    Way Too Much Bonus Chapters - c020 y11 (v04) [Group].zip
```
- **(mag)** or **(v00)** or **(mix)** is ***required*** - all magazine scans **must** use the first one, all tankoubon scans **must** use the second, with the appropriate volume number, and any mixed content containing pages from both magazines and volumes **must** use the third option. Volume numbers are **unallowed** for magazine scans. If multiple volumes are included in a single archive, the range ***must*** be indicated with the **-00**. However, this is ***not recommended***. The range is **required** not to include an unit unless a range transition happens, ie. **v99-w100**. Volume numbers ***must*** be padded to two digits minimum. If no volume number is present, **(v00)** ***must*** be used. If volume numbers go beyond two digits, **v** is to be changed to **w** to ensure proper sorting.
- **[Extra Information]** is ***optional***.
- **[Group]** is ***required***. If group is not known, **[Unknown]** ***must*** be used.
- **{revision}** is ***optional***. Recommended formatting is either **{r0}** or **{v0}**.
- **.zip** A file extension is ***required***. Zip is the ***recommended*** archive format due to its universality.

### Examples (In natural sorting order)
```
Name of Manga - 000 (mag) [Oneshot from Comic Q] [Unknown].zip
Name of Manga - c001-005 x1 (v01) [Unknown].zip
Name of Manga - c006-010 (v02) [FooScans].zip
Name of Manga - c010 x1 (v02) [Omake] [FooScans].zip
Name of Manga - c011 (v03) [FooScans].zip
Name of Manga - c012-013 (mag) [BarScans].zip
Name of Manga - c014 (mag) [BarScans].zip
Name of Manga - c014 (mag) [BarScans]{v2}.zip
Name of Manga - c015 (mag) [BarScans].zip
Name of Manga - c015 x1 (v03) [Omake] [FooScans].zip
Name of Manga - c015 x2 (v03) [Extras] [FooScans].zip
Name of Manga - c016-020 x1 (v04) [FooScans].zip
Name of Manga [jpn] - c011-015 x2 (v03) [Unknown].zip
Name of Manga [jpn] - c014 (mag) [Unknown].zip
```

# Manga Page Naming Scheme

This will define how to name individual pages inside archives. To be added.