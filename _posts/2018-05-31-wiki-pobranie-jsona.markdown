---
layout: post
title:  "Wiki - pobranie JSONa"
date:   2018-05-31 23:14:19 +0200
categories: pl
---

Popchnąłem do przodu [zadanie][challenge] od [FreeCodeCamp'u][FreeCodeCamp] - przeglądarka Wikipedii. Udało się pobrać JSONa. Starczyło dopisać frazę `&callback=?`, czyli byłoby to: [https://en.wikipedia.org/w/api.php?action=opensearch&search=black%20hole&format=json&callback=?](https://en.wikipedia.org/w/api.php?action=opensearch&search=black%20hole&format=json&callback=?) 

Teraz już sam JSON jest sczytywany do programu, więc można się zająć już obróbką tegoż. Czyli pętelką do ładnego zHTML'owania go.
Ten cały `&callback=?` jest "zgapiony", muszę koniecznie rozkminić do czego onn jest :metal: :)  :-) :smile:




[challenge]: https://learn.freecodecamp.org/coding-interview-prep/take-home-projects/build-a-wikipedia-viewer
[FreeCodeCamp]: https://www.freecodecamp.org


