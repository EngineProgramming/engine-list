## The [Engine Programming Server][discord-invite]'s List of Game-Playing Engines
### Chess Engines

"*" ratings indicate a missing rating from the rating lists.

"~" prefix indicates that a rating is merely approximate.

"↓" prefix indicates that the rating was obtained with an older release of the engine.

All ratings are from single-CPU lists, last updated 2023-07-17.
| Engine Name | Author | [CCRL 40/15][ccrl-4015] | [CCRL Blitz][ccrl-blitz] | Notes |
|-------------|--------|------|------|----------|
| [Clover](https://github.com/lucametehau/CloverEngine) 5.0 | [lucametehau](https://github.com/lucametehau) | 3412 | 3565 | Plant. |
| [Seer](https://github.com/connormcmonigle/seer-nnue) 2.6.0 | [Connor McMonigle](https://github.com/connormcmonigle) | 3402 | 3542 | Very strong engine, with NNUE trained via retrograde learning on tablebase positions. |
| [Caissa](https://github.com/Witek902/Caissa) 1.10 | [Witek902](https://github.com/Witek902) | 3397 | 3519 | Written in C++! |
| [Viridithas](https://github.com/cosmobobak/viridithas) 10.0.0 | [Cosmo Bobak](https://github.com/cosmobobak) | 3385 | 3525 | The strongest UK chess engine & the strongest Rust chess engine. |
| [chess.cpp](https://github.com/GediminasMasaitis/chess-dot-cpp) 3.99 | [Gedas](https://github.com/GediminasMasaitis) | ~3350 | * | Very strong C++ engine, still doesn't have a proper name!! |
| [Rice](https://github.com/rafid-dev/rice) 7.0.0 | [Rafid](https://github.com/rafid-dev) | 3333 | 3472 | Written in C++ |
| [BlackCore](https://github.com/SzilBalazs/BlackCore) 6.0 | [Szil](https://github.com/SzilBalazs) | 3310 | 3428 | Very strong NNUE implementation. |
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3306 | 3433 | Supports FRC & uses self-generated NNUE data. |
| [Alexandria](https://github.com/PGG106/Alexandria) 3.5.0 | [Zuppa D. Cipolle](https://github.com/PGG106) | 3258 | 3384 | Strong C engine with VICE ancestry. |
| [StockDory](https://github.com/TheBlackPlague/StockDory) 1.1-Alpha | [Shaheryar Sohail](https://github.com/TheBlackPlague) | 3247 | * | C++ rewrite of StockNemo. |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3218 | 3366 | NNUE chess engine that never had an HCE, learned to play chess from zero knowledge. |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3212 | 3310 | Another very strong HCE engine. [Doesn't support tablebases.](http://talkchess.com/forum3/viewtopic.php?f=2&t=76927#p888045) |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3207 | 3316 | A very strong VICE descendant, and one of the strongest HCE engines. |
| [StockNemo](https://github.com/TheBlackPlague/StockNemo) Stingray 5.7.0.0 | [Shaheryar Sohail](https://github.com/TheBlackPlague) | 3189 | ↓2933 | Written in C#! |
| [Svart](https://github.com/crippa1337/svart) 5 | [Crippa](https://github.com/crippa1337) | 3180 | 3261 | Written in Rust! |
| [Drofa](https://github.com/justNo4b/Drofa) 4.0.0 | [No4b](https://github.com/justNo4b) | 3179 | 3227 | Drofa started as a fork of the Shallow Blue chess engine - it's now much stronger, and is among the strong HCE engines. |
| [Nalwald](https://gitlab.com/tsoj/Nalwald) 17.1 | [tsoj](https://gitlab.com/tsoj/Nalwald) | 3140 | ↓3194 | Alpha-beta engine with BAE, written in Nim! |
| [Altair](https://github.com/Alex2262/AltairChessEngine) 4.0.0 | [Antares](https://github.com/Alex2262) | ↓3002 | ↓3012 | 10x12 mailbox C++ engine. |
| [Polaris](https://github.com/Ciekce/Polaris) 1.8.1 | [Ciekce](https://github.com/Ciekce) | 2987 | 3061 | "author has a catboy as pfp" ~ crippa<br />C++20 HCE engine that does not care about king safety! |
| [Peacekeeper](https://github.com/Sazgr/peacekeeper) 1.60 | [Sazgr](https://github.com/Sazgr) | ~2970 | 3058 | A C++ engine which formerly had simple evaluation, still sucks at LTC, and has 2.19999999 in its code. |
| [Midnight](https://github.com/archishou/MidnightChessEngine) 6 | [archi](https://github.com/archishou) | 2927 | 3049 | "it be an engine" - archi |
| [Willow](https://github.com/Adam-Kulju/Willow) 2.9 | [Adam Kulju](https://github.com/Adam-Kulju) | 2956 | 2997 | Hung a queen in its second-ever tournament game! Has a very aggressive, freewheeling style of play. |
| [Akimbo](https://github.com/JacquesRW/akimbo) 0.4.0 | [JacquesRW](https://github.com/JacquesRW) | ~2890 | * | Small engine written in Rust. |
| [4ku](https://github.com/kz04px/4ku) 3.1 | [kz04px](https://github.com/kz04px), [Gedas](https://github.com/GediminasMasaitis), [Gian-Carlo Pascutto](https://github.com/gcp), and [others](https://github.com/kz04px/4ku/graphs/contributors) | ~2870 | ↓2919 | A UCI chess engine in 4 kB. The 4ku-mini script contains compressed C++ source code, that is extracted and compiled before being run. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [ice4](https://github.com/MinusKelvin/ice4) v3.1 | [MinusKelvin](https://github.com/MinusKelvin) & [Analog Hors](https://github.com/analog-hors) | ~2800 | * | ice4 is a chess engine which fits in 4096 bytes. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [Mess](https://github.com/raklaptudirm/mess) 0.3.0 | [Rak Laptudirm](https://github.com/raklaptudirm) | 2770 | 2817 | Written in Go! |
| [Pedantic](https://github.com/JoAnnP38/Pedantic) 0.3.1 | [JoAnnP38](https://github.com/JoAnnP38) | 2745 | ↓2747 | Written in C#! |
| [Apotheosis](https://github.com/spamdrew128/Apotheosis) 4.0.1 | [Spamdrew](https://github.com/spamdrew128) | 2743 | 2778 | Apotheosis is a blunder-prone silly lil guy that sometimes plays cool chess. |
| [Renegade](https://github.com/pkrisz99/Renegade) 0.11.0 | [Krisz](https://github.com/pkrisz99) | 2696 | 2727 | A chess engine written in C++ using Visual Studio 2019. It values readability and simplicity. |
| [Cheers](https://github.com/Algorhythm-sxv/Cheers) 0.2.2 | [Algorhythm](https://github.com/Algorhythm-sxv) | 2644 | 2656 | A Rust HCE engine! |
| [Princhess](https://github.com/princesslana/princhess) 0.12.0 | [princesslana](https://github.com/princesslana) | ↓2484 | ↓2618 | CPU-only MCTS engine in Rust! |
| [Baislicka](https://github.com/kz04px/Baislicka) 1.0 | [kz04px](https://github.com/kz04px) | 2207 | 2254 | A chess engine written in C. Uses bitboards with fixed shift fancy movegen. |
| [Valiant](https://www.dropbox.com/sh/tfiwhx900g4ni42/AABEm29llAn1MaG8D6yW8ZO7a?dl=0) Mk 8 | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | * | 1046 | Mk V has a startup sound, Mk 3.2 "Archer" has reversed piece square tables, Mk 2 "Valentine" barely cares about king safety, Mk2 and Mk3's sources are lost to time... Its greatest anomaly is being able to consistently beat BBC 1.4 (with Stockfish NNUE!). The 3rd strongest python engine. |

### Chess960 Engines
See above for notes.
| Engine Name | Author | [CCRL 40/2 FRC][ccrl-frc] |
|-------------|--------|---------------|
| [Caissa](https://github.com/Witek902/Caissa) 1.10 | [Witek902](https://github.com/Witek902) | 3775 |
| [Clover](https://github.com/lucametehau/CloverEngine) 5.0 | [lucametehau](https://github.com/lucametehau) | 3713 |
| [Viridithas](https://github.com/cosmobobak/viridithas) 10.0.0 | [Cosmo Bobak](https://github.com/cosmobobak) | 3675 |
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3539 |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3494 |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3375 |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3358 |
| [Drofa](https://github.com/justNo4b/Drofa) 4.0.0 | [No4b](https://github.com/justNo4b) | 3266 |
| [Altair](https://github.com/Alex2262/AltairChessEngine) 4.0.0 | [Antares](https://github.com/Alex2262) | 3082 |
| [Nalwald](https://gitlab.com/tsoj/Nalwald) 17.1 | [tsoj](https://gitlab.com/tsoj/Nalwald) | ↓3052 |
| [Polaris](https://github.com/Ciekce/Polaris) 1.8.1 | [Ciekce](https://github.com/Ciekce) | 2981 |
| [Akimbo](https://github.com/JacquesRW/akimbo) 0.3.0 | [JacquesRW](https://github.com/JacquesRW) | ↓2313 |
| [Princhess](https://github.com/princesslana/princhess) 0.12.0 | [princesslana](https://github.com/princesslana) | ↓2188 |

### Ataxx Engines
| Engine Name | Author | Notes |
|-------------|--------|-----------|
| [Scarletxx](https://github.com/folkertvanheusden/Scarletxx) | [Folkert van Heusden](https://vanheusden.com/) | |

### GGPs & Other Game Engines
| Engine Name | Author | Game | Notes |
|-------------|--------|------|----------|
| [Ampersand](https://github.com/chesstastic-org/Ampersand) | [Corman](https://github.com/Cormanz/) | GGP (Fairy Chess) | Ampersand is a fairy chess engine powered by the monster-chess move generation library. It currently isn't functional. |
| [bashtet](https://github.com/analog-hors/bashtet) | [Analog Hors](https://github.com/analog-hors) | Tetris | A bash script that plays Tetris. |
| [Cold Clear](https://github.com/MinusKelvin/cold-clear) | [MinusKelvin](https://github.com/MinusKelvin) | Tetris | The strongest Tetris engine as of the last time anyone bothered to check. |
| [Della Baduck](https://github.com/folkertvanheusden/dellabaduck) | [Folkert van Heusden](https://vanheusden.com/) | Go | |

# Contributing
* Engines are sorted in descending order of their CCRL 40/15 rating, or their CCRL 40/2 FRC rating for Chess960.
* If you are:
    * Updating the version-number of an existing engine, but you lack a rating for it, prefix the earlier rating with an "↓".
    * Updating/adding an engine and the error margins of a rating is >30, prefix the rating with an "~".

[discord-invite]:https://discord.com/invite/F6W6mMsTGN
[ccrl-blitz]:https://www.computerchess.org.uk/ccrl/404/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
[ccrl-4015]:https://www.computerchess.org.uk/ccrl/4040/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
[ccrl-frc]:https://www.computerchess.org.uk/ccrl/404FRC/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
