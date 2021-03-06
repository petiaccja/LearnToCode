---
title: "A weboldal bővítése"
date: 2019-09-28T14:20:45+02:00
draft: false
---


A tech stack
---

A statikus HTML/CSS weboldalt [Hugo](https://gohugo.io/) generálja Markdown fájlokból. A Hugo weblapján a Quick Startot elég átnézni. A lényeg:

1. sudo apt-get install hugo (vagy valami ilyesmi)
2. git clone --recursive [https://github.com/petiaccja/LearnToCode.git](https://github.com/petiaccja/LearnToCode)
3. cd <repo_root>
4. hugo server -D
5. nyisd meg a [http://localhost:1313/LearnToCode/](http://localhost:1313/LearnToCode/) weboldalt
6. írj tartalmat

Az új, nyers Markdown tartalommal küldj egy PR-t master branchre, a generált HTML-t dobd ki. A repóra fel van hookolva AppVeyor CI, ami Hugo-val generálja a HTML-t cloudon, és pusholja a "gh-pages" branchre, így minden commit után automatikusan frissül a weboldal, tekintve hogy a generálás hiba nélkül futott.


Tartalom
---

Egyelőre van egy főoldal (content/_index.md) és néhány fejezet (content/chapters/valami.md). Alapjáraton ezeket a Markdown fájlokat lehet buzizni, illetve lehet újakat hozzáadni a chapters-be. Új fejezet esetén persze az index.md-t is szerkeszteni kell, hogy elérhető legyen a tartalom. Egyelőre az index page tartalmaz egy linket az összes fejezetre, nem túl bonyolult.

Ha valamiről írni akarsz, akkor hajrá. Minél több ember ír, annál jobb, hiszen egy embernek úgysincs elég széles látóköre, hogy mindent leírjon.


Képek, miegymás
---

A Hugo leírásában megtaláljátok, gondolom.


Style
---

Ha a style-k megcsináljátok rendesen, az is hasznos.