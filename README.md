## The Engine Programming Server's List of Game-Playing Engines
### Chess Engines

"*" ratings indicate a missing rating from the rating lists.

"~" prefix indicates that a rating is merely approximate.

"↓" prefix indicates that the rating was obtained with an older release of the engine.

All ratings are from single-CPU lists, last updated 2023-05-09.
| Engine Name | Author | CCRL 40/15 | CCRL Blitz | Notes |
|-------------|--------|------|------|----------|
| [Seer](https://github.com/connormcmonigle/seer-nnue) 2.60 | [Connor McMonigle](https://github.com/connormcmonigle) | 3406 | 3544 | Very strong engine, with NNUE trained via retrograde learning on tablebase positions. |
| [Clover](https://github.com/lucametehau/CloverEngine) 4.0 | [lucametehau](https://github.com/lucametehau) | 3396 | 3535 | Plant. |
| [chess.cpp](https://github.com/GediminasMasaitis/chess-dot-cpp) 3.99 | [Gedas](https://github.com/GediminasMasaitis) | ~3350 | * | Very strong C++ engine, still doesn't have a proper name!! |
| [BlackCore](https://github.com/SzilBalazs/BlackCore) 6.0 | [Szil](https://github.com/SzilBalazs) | 3313 | 3429 | Very strong NNUE implementation. |
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3308 | 3434 | Supports FRC & uses self-generated NNUE data. |
| [Viridithas](https://github.com/cosmobobak/viridithas) 8.1.0 | [Cosmo Bobak](https://github.com/cosmobobak) | 3303 | 3406 | Includes the Lichess Elite Database in his NNUE training data, considered a very aggressive engine by the [EAS Ratinglist](https://www.sp-cc.de/eas-ratinglist.html). |
| [Alexandria](https://github.com/PGG106/Alexandria) 3.5.0 | [Zuppa D. Cipolle](https://github.com/PGG106) | 3257 | 3384 | Strong C engine with VICE ancestry. |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3222 | 3366 | NNUE chess engine that never had an HCE, learned to play chess from zero knowledge. |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3213 | 3313 | Another very strong HCE engine. [Doesn't support tablebases.](http://talkchess.com/forum3/viewtopic.php?f=2&t=76927#p888045) |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3209 | 3316 | A very strong VICE descendant, and one of the strongest HCE engines. |
| [StockNemo](https://github.com/TheBlackPlague/StockNemo) Stingray 5.7.0.0 | [Shaheryar Sohail](https://github.com/TheBlackPlague) | 3188 | ↓2926 | Written in C#! |
| [Drofa](https://github.com/justNo4b/Drofa) 3.3.22 | [No4b](https://github.com/justNo4b) | 3180 | 3240 | Drofa started as fork of the Shallow Blue chess engine - it's now much stronger, and is among the strong HCE engines. |
| [Rice](https://github.com/rafid-dev/rice) 5.0.0 | [Rafid](https://github.com/rafid-dev) | 3131 | * | Written in C++ |
| [Svart](https://github.com/crippa1337/svart) 4 | [Crippa](https://github.com/crippa1337) | 3015 | 3138 | Written in Rust! |
| [Midnight](https://github.com/archishou/MidnightChessEngine) 6 | [archi](https://github.com/archishou) | ↓2697 | 3054 | "it be an engine" - archi |
| [Altair](https://github.com/Alex2262/AltairChessEngine) 2.0.0 | [Antares](https://github.com/Alex2262) | 2805 | 2874 | 10x12 mailbox C++ engine. |
| [ice4](https://github.com/MinusKelvin/ice4) TCEC S24 Swiss | [MinusKelvin](https://github.com/MinusKelvin) & [Analog Hors](https://github.com/analog-hors) | ~2800 | * | ice4 is a chess engine which fits in 4096 bytes. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [4ku](https://github.com/kz04px/4ku) 3.0 | [kz04px](https://github.com/kz04px), [Gedas](https://github.com/GediminasMasaitis), [Gian-Carlo Pascutto](https://github.com/gcp), and [others](https://github.com/kz04px/4ku/graphs/contributors) | ↓2692 | ↓2756 | A UCI chess engine in 4 kB. The 4ku-mini script contains compressed C++ source code, that is extracted and compiled before being run. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [Polaris](https://github.com/Ciekce/Polaris) 1.6.1 | [Ciekce](https://github.com/Ciekce) | ↓2675 | ↓2746 | "author has a catboy as pfp" ~ crippa |
| [Mess](https://github.com/raklaptudirm/mess) 0.2.0 | [Rak Laptudirm](https://github.com/raklaptudirm) | 2717 | ↓2484 | Written in Go! |
| [Apotheosis](https://github.com/spamdrew128/Apotheosis) 4.0.1 | [Spamdrew](https://github.com/spamdrew128) | ↓2330 | ↓2350 | Apotheosis is a blunder-prone silly lil guy that sometimes plays cool chess. |
| [Willow](https://github.com/Adam-Kulju/Willow) 2.7 | [Adam Kulju](https://github.com/Adam-Kulju) | 2685 | 2675 | Hung a queen in its second-ever tournament game! Has a very aggressive, freewheeling style of play. |
| [Peacekeeper](https://github.com/Sazgr/peacekeeper) 1.40 | [Sazgr](https://github.com/Sazgr) | 2684 | 2714 | A C++ engine with simple evaluation which sucks at LTC. |
| [Cheers](https://github.com/Algorhythm-sxv/Cheers) 0.2.2 | [Algorhythm](https://github.com/Algorhythm-sxv) | 2649 | 2655 | A Rust HCE engine! |
| [Akimbo](https://github.com/JacquesRW/akimbo) 0.2.0 | [JacquesRW](https://github.com/JacquesRW/akimbo) | 2520 | * | Small engine written in Rust. |
| [Renegade](https://github.com/pkrisz99/Renegade) 0.10.0 | [Krisz](https://github.com/pkrisz99) | ~2500 | 2495 | A chess engine written in C++ using Visual Studio 2019. It values readability and simplicity. |
| [Baislicka](https://github.com/kz04px/Baislicka) 1.0 | [kz04px](https://github.com/kz04px) | 2207 | 2251 | A chess engine written in C. Uses bitboards with fixed shift fancy movegen. |
| [Valiant](https://www.dropbox.com/sh/tfiwhx900g4ni42/AABEm29llAn1MaG8D6yW8ZO7a?dl=0) Mk 7 | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | ↓~1952 | * | Mk V has a startup sound, Mk 3.2 "Archer" has reversed piece square tables, Mk 2 "Valentine" barely cares about king safety, Mk2 and Mk3's sources are lost to time... Its greatest anomaly is being able to consistently beat BBC 1.4 (with Stockfish NNUE!). The 3rd strongest python engine. |
| [Honse](https://github.com/EngineProgramming/honse) | [The Engine Programming Discord](https://discord.com/invite/YctB2p4) | * | * | A public didactic engine open for anyone in the server to contribute to. Rust, Alpha-Beta, classical evaluation, maybe NNUE in the future. |
| [π Chess](https://www.dropbox.com/sh/tfiwhx900g4ni42/AAC5FPUjZZi1fr8TW-PEE52ja/%CF%80%20Chess.zip?dl=0) | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | * | * | A port of Tom7's Elo World's π engine. |
| [Dog](https://github.com/folkertvanheusden/dog) | [Folkert van Heusden](https://vanheusden.com/) | * | * | runs on pcs and on the esp32 microcontroller |
### Chess960 Engines
See above for notes.
| Engine Name | Author | CCRL 40/2 FRC |
|-------------|--------|---------------|
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3536 |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3496 |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3375 |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3358 |
| [Polaris](https://github.com/Ciekce/Polaris) 1.6.1 | [Ciekce](https://github.com/Ciekce) | 2742 |
### Ataxx Engines
| Engine Name | Author | Notes |
|-------------|--------|-----------|
| [Scarletxx](https://github.com/folkertvanheusden/Scarletxx) | [Folkert van Heusden](https://vanheusden.com/) | |
### GGPs & Other Game Engines
| Engine Name | Author | Game | Notes |
|-------------|--------|------|----------|
| [Ampersand](https://github.com/chesstastic-org/Ampersand) | [Corman](https://github.com/Cormanz/) | GGP (Fairy Chess) | Ampersand is a fairy chess engine powered by the monster-chess move generation library. It currently isn't functional. |
| [bashtet](https://github.com/analog-hors/bashtet) | [Analog Hors](https://github.com/analog-hors) | Tetris | A bash script that plays Tetris. |
| [Della Baduck](https://github.com/folkertvanheusden/dellabaduck) | [Folkert van Heusden](https://vanheusden.com/) | Go | |

# Contributing
* Engines are sorted in descending order of their CCRL 40/15 rating, or their CCRL 40/2 FRC rating for Chess960.
* If you are:
    * Updating the version-number of an existing engine, but you lack a rating for it, prefix the earlier rating with an "↓".
    * Updating/adding an engine and the error margins of a rating is >30, prefix the rating with an "~".
