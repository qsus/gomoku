# gomoku
Development of new Gomoku web.

## Situation now
There are many websites like playfive.net, piskvorky.net, piskvorky.cz, vcpr.cz, euroleague.cz under management of the Czech Gomoku and Renju federation and several others like gomokuworld.com, renju.net, ...

## Goal
- A good place to play with a good ELO system, saving games, correspondence games
- tournament system, official tournaments and the abbility to organize small and private tournaments
- Puzzles, making snapshots of current games so people can turn interesting moments into puzzles later
- tutorials, courses (VCT, VCF, swap 2)
- profiles, badges (permanent & temporary) <sup>[discord](https://discord.com/channels/1196025578051096728/1198221232445870130)</sup>
- integrated betting system
- bigger tournaments (ČPL, EL, MBE, ...) (buďto napojit, nebo nějak zkopírovat a integrovat)
- analysis (of finished games and during games)
- shop (equipment and merch)
- forums
- discord integration


## Journey
- central API for:
  - saving games
  - rating (possibly online & tournament), profiles
- k centrálnímu api pak půjde modulárně připojit třeba hernu, nebo další komponenty
- spolupracovat s grafiky při tvorbě front-end
- ta logika je, že front-end musí být nezávislý na back-endu

## Other notes
- we can partially copy lichess
