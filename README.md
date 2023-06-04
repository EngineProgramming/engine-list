## The Engine Programming Server's List of Game-Playing Engines
### Chess Engines

"*" ratings indicate a missing rating from the rating lists.

"~" prefix indicates that a rating is merely approximate.

"↓" prefix indicates that the rating was obtained with an older release of the engine.

All ratings are from single-CPU lists, last updated 2023-06-04.
| Engine Name | Author | [CCRL 40/15][ccrl-4015] | [CCRL Blitz][ccrl-blitz] | Notes |
|-------------|--------|------|------|----------|
| [Seer](https://github.com/connormcmonigle/seer-nnue) 2.60 | [Connor McMonigle](https://github.com/connormcmonigle) | 3405 | 3544 | Very strong engine, with NNUE trained via retrograde learning on tablebase positions. |
| [Clover](https://github.com/lucametehau/CloverEngine) 4.1 | [lucametehau](https://github.com/lucametehau) | 3394 | ~3541 | Plant. |
| [Viridithas](https://github.com/cosmobobak/viridithas) 9.1.0 | [Cosmo Bobak](https://github.com/cosmobobak) | ↓3360 | ↓3485 | Includes the Lichess Elite Database in his NNUE training data, the strongest UK chess engine & the strongest Rust chess engine. |
| [chess.cpp](https://github.com/GediminasMasaitis/chess-dot-cpp) 3.99 | [Gedas](https://github.com/GediminasMasaitis) | ~3350 | * | Very strong C++ engine, still doesn't have a proper name!! |
| [BlackCore](https://github.com/SzilBalazs/BlackCore) 6.0 | [Szil](https://github.com/SzilBalazs) | 3312 | 3429 | Very strong NNUE implementation. |
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3309 | 3433 | Supports FRC & uses self-generated NNUE data. |
| [Rice](https://github.com/rafid-dev/rice) 6.0.0 | [Rafid](https://github.com/rafid-dev) | 3264 | * | Written in C++ |
| [Alexandria](https://github.com/PGG106/Alexandria) 3.5.0 | [Zuppa D. Cipolle](https://github.com/PGG106) | 3258 | 3385 | Strong C engine with VICE ancestry. |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3222 | 3367 | NNUE chess engine that never had an HCE, learned to play chess from zero knowledge. |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3214 | 3313 | Another very strong HCE engine. [Doesn't support tablebases.](http://talkchess.com/forum3/viewtopic.php?f=2&t=76927#p888045) |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3209 | 3316 | A very strong VICE descendant, and one of the strongest HCE engines. |
| [StockNemo](https://github.com/TheBlackPlague/StockNemo) Stingray 5.7.0.0 | [Shaheryar Sohail](https://github.com/TheBlackPlague) | 3190 | ↓2933 | Written in C#! |
| [Drofa](https://github.com/justNo4b/Drofa) 3.3.22 | [No4b](https://github.com/justNo4b) | 3181 | 3245 | Drofa started as fork of the Shallow Blue chess engine - it's now much stronger, and is among the strong HCE engines. |
| [Svart](https://github.com/crippa1337/svart) 5 | [Crippa](https://github.com/crippa1337) | ↓3039 | ↓3137 | Written in Rust! |
| [Midnight](https://github.com/archishou/MidnightChessEngine) 6 | [archi](https://github.com/archishou) | 2927 | 3055 | "it be an engine" - archi |
| [Willow](https://github.com/Adam-Kulju/Willow) 2.8 | [Adam Kulju](https://github.com/Adam-Kulju) | 2852 | 2869 | Hung a queen in its second-ever tournament game! Has a very aggressive, freewheeling style of play. |
| [Altair](https://github.com/Alex2262/AltairChessEngine) 3.0.0 | [Antares](https://github.com/Alex2262) | ↓2808 | 3012 | 10x12 mailbox C++ engine. |
| [Polaris](https://github.com/Ciekce/Polaris) 1.7.0 | [Ciekce](https://github.com/Ciekce) | ↓2806 | ↓2885 | "author has a catboy as pfp" ~ crippa |
| [ice4](https://github.com/MinusKelvin/ice4) v3 | [MinusKelvin](https://github.com/MinusKelvin) & [Analog Hors](https://github.com/analog-hors) | ~2800 | * | ice4 is a chess engine which fits in 4096 bytes. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [4ku](https://github.com/kz04px/4ku) 3.0 | [kz04px](https://github.com/kz04px), [Gedas](https://github.com/GediminasMasaitis), [Gian-Carlo Pascutto](https://github.com/gcp), and [others](https://github.com/kz04px/4ku/graphs/contributors) | 2814 | 2920 | A UCI chess engine in 4 kB. The 4ku-mini script contains compressed C++ source code, that is extracted and compiled before being run. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [Apotheosis](https://github.com/spamdrew128/Apotheosis) 4.0.1 | [Spamdrew](https://github.com/spamdrew128) | 2748 | 2779 | Apotheosis is a blunder-prone silly lil guy that sometimes plays cool chess. |
| [Mess](https://github.com/raklaptudirm/mess) 0.3.0 | [Rak Laptudirm](https://github.com/raklaptudirm) | ↓2713 | ↓2482 | Written in Go! |
| [Peacekeeper](https://github.com/Sazgr/peacekeeper) 1.40 | [Sazgr](https://github.com/Sazgr) | 2696 | 2734 | A C++ engine with simple evaluation which sucks at LTC. |
| [Cheers](https://github.com/Algorhythm-sxv/Cheers) 0.2.2 | [Algorhythm](https://github.com/Algorhythm-sxv) | 2649 | 2659 | A Rust HCE engine! |
| [Akimbo](https://github.com/JacquesRW/akimbo) 0.3.0 | [JacquesRW](https://github.com/JacquesRW/akimbo) | ~2632 | * | Small engine written in Rust. |
| [Renegade](https://github.com/pkrisz99/Renegade) 0.11.0 | [Krisz](https://github.com/pkrisz99) | ↓2505 | ↓2497 | A chess engine written in C++ using Visual Studio 2019. It values readability and simplicity. |
| [Pedantic](https://github.com/JoAnnP38/Pedantic) 0.2.1 | [JoAnnP38](https://github.com/JoAnnP38) | 2442 | 2475 | Written in C#! |
| [Princhess](https://github.com/princesslana/princhess) 0.11.0 | [princesslana](https://github.com/princesslana) | ↓2406 | 2618 | CPU-only MCTS engine in Rust! |
| [Baislicka](https://github.com/kz04px/Baislicka) 1.0 | [kz04px](https://github.com/kz04px) | 2208 | 2253 | A chess engine written in C. Uses bitboards with fixed shift fancy movegen. |
| [Valiant](https://www.dropbox.com/sh/tfiwhx900g4ni42/AABEm29llAn1MaG8D6yW8ZO7a?dl=0) Mk 8 | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | ↓~1952 | * | Mk V has a startup sound, Mk 3.2 "Archer" has reversed piece square tables, Mk 2 "Valentine" barely cares about king safety, Mk2 and Mk3's sources are lost to time... Its greatest anomaly is being able to consistently beat BBC 1.4 (with Stockfish NNUE!). The 3rd strongest python engine. |
| [Honse](https://github.com/EngineProgramming/honse) | [The Engine Programming Discord](https://discord.com/invite/YctB2p4) | * | * | A public didactic engine open for anyone in the server to contribute to. Rust, Alpha-Beta, classical evaluation, maybe NNUE in the future. |
| [Dog](https://github.com/folkertvanheusden/dog) | [Folkert van Heusden](https://vanheusden.com/) | * | * | Runs on PCs and the ESP32 microcontroller. |
| [ℇuler Chess](https://www.dropbox.com/s/66nxcvl2knqg4s4/%E2%84%87uler%20Chess.zip?dl=0) | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | * | * | A port of Tom7's Elo World's ℇ engine. Despite the differing search algorithm, is still better than other mathematical constant engines. |
| [π Chess](https://www.dropbox.com/sh/tfiwhx900g4ni42/AAC5FPUjZZi1fr8TW-PEE52ja/%CF%80%20Chess.zip?dl=0) | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | * | * | A port of Tom7's Elo World's π engine. |

### Chess960 Engines
See above for notes.
| Engine Name | Author | [CCRL 40/2 FRC][ccrl-frc] |
|-------------|--------|---------------|
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3536 |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3495 |
| [Viridithas](https://github.com/cosmobobak/viridithas) 9.1.0 | [Cosmo Bobak](https://github.com/cosmobobak) | ~3470 |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3374 |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3358 |
| [Polaris](https://github.com/Ciekce/Polaris) 1.6.1 | [Ciekce](https://github.com/Ciekce) | ↓2745 |
| [Princhess](https://github.com/princesslana/princhess) 0.11.0 | [princesslana](https://github.com/princesslana) | ↓2188 |

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

[ccrl-blitz]:https://www.computerchess.org.uk/ccrl/404/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
[ccrl-4015]:https://www.computerchess.org.uk/ccrl/4040/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
[ccrl-frc]:https://www.computerchess.org.uk/ccrl/404FRC/cgi/compare_engines.cgi?class=Single-CPU+engines&only_best_in_class=on&num_best_in_class=1&print=Rating+list
