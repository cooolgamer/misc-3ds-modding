# 3DS Home Menu bad translation

Note: this project is UNFINISHED, and may never be due to the lack of motivation.

Note2: due to how luma homemenu patching work, random crashes can occur while going to the homemenu, this is rare though.

## What is this?

Basically, I got the homemenu strings, put it on a website that translate it using 100 random languages using google translate, and put them back and adjust them if needed so they can fit.

## How 2 Install???

- [Mod your 3DS](https://3ds.hacks.guide/)
- Download the menu_msbt_LZ.bin file from this repo
- Put this file in ``luma/titles/000400300000XX02/romfs/message/REGION_Language/`` on your sdcard
  - XX is ``98`` for EUR, ``8F`` for USA, ``82`` for JPN and ``A9`` for KOR.
  - REGION is your region (``EU``, ``US``, ``JP``, ``KR``)
  - Language is your language in english (``English``, ``French``, ``Spanish`` etc.)
  - A path for Europe region with English language would be ``luma/titles/0004003000009802/romfs/message/EU_English/``
- Enable game patching in luma config (hold select while booting)
- Enjoy
