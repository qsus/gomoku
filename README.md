# gomoku
Development of new Gomoku web.

## Situation now
There are many websites like playfive.net, piskvorky.net, piskvorky.cz, vcpr.cz, euroleague.cz under management of the Czech Gomoku and Renju federation and several others like gomokuworld.com, renju.net, ...

## Goal
- pořádná herna s dobrým rating systémem, co ukládá hry, včetně korespondenček
- možnost tvorby vlastních turnajů
- úlohy (snaphost ze záznamu hry)
- tutorials, courses (VCT, VCF, swap 2)
- integrated betting system
- bigger tournaments (ČPL, EL, MBE, ...) (buďto napojit, nebo nějak zkopírovat a integrovat)
- analýza (odehraných her a při hře)
- shop (equipment and merch)
- forums


## Journey
- vytvořit centrální API, které bude sloužit pro:
  - ukládání her
  - rating (possibly online & tournament), profiles
- k centrálnímu api pak půjde modulárně připojit třeba hernu, nebo další komponenty
- spolupracovat s grafiky při tvorbě front-end
- ta logika je, že front-end musí být nezávislý na back-endu

## Other notes
- we can partially copy lichess
