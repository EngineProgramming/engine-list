## The Engine Programming Server's List of Game-Playing Engines
### Chess Engines

"*" ratings indicate a missing rating from the rating lists.

"~" prefix indicates that a rating is merely approximate.

"↓" prefix indicates that the rating was obtained with an older release of the engine.

All ratings are from single-CPU lists.
| Engine Name | Author | CCRL 40/15 | CCRL Blitz | Notes |
|-------------|--------|------|------|----------|
| [Seer](https://github.com/connormcmonigle/seer-nnue) 2.60 | [Connor McMonigle](https://github.com/connormcmonigle) | 3406 | 3631 | Very strong engine, with NNUE trained via retrograde learning on tablebase positions. |
| [chess.cpp](https://github.com/GediminasMasaitis/chess-dot-cpp) 3.99 | [Gedas](https://github.com/GediminasMasaitis) | ~3350 | * | Very strong C++ engine, still doesn't have a proper name!! |
| [Smallbrain](https://github.com/Disservin/Smallbrain) 7.0.0 | [Disservin](https://github.com/Disservin) | 3311 | 3433 | Supports FRC & uses self-generated NNUE data. |
| [BlackCore](https://github.com/SzilBalazs/BlackCore) 6.0 | [Szil](https://github.com/SzilBalazs) | 3307 | ↓3245 | Very strong NNUE implementation. |
| [Alexandria](https://github.com/PGG106/Alexandria) 3.5.0 | [Zuppa D. Cipolle](https://github.com/PGG106) | 3261 | 3383 | Strong C engine with VICE ancestry. |
| [Viridithas](https://github.com/cosmobobak/viridithas) 8.1.0 | [Cosmo Bobak](https://github.com/cosmobobak) | ↓3246 | 3391 | Includes the Lichess Elite Database in his NNUE training data, considered a very aggressive engine by the [EAS Ratinglist](https://www.sp-cc.de/eas-ratinglist.html). |
| [Frozenight](https://github.com/MinusKelvin/frozenight) 6.0.0 | [MinusKelvin](https://github.com/MinusKelvin) | 3226 | 3367 | NNUE chess engine that never had an HCE, learned to play chess from zero knowledge. |
| [Weiss](https://github.com/TerjeKir/weiss) 2.0 | [Terje](https://github.com/TerjeKir) | 3211 | 3430 | A very strong VICE descendant, and one of the strongest HCE engines. |
| [Stash](https://gitlab.com/mhouppin/stash-bot) 34.0 | [Morgan Houppin](https://gitlab.com/mhouppin) | 3211 | 3314 | Another very strong HCE engine. [Doesn't support tablebases.](http://talkchess.com/forum3/viewtopic.php?f=2&t=76927#p888045) |
| [StockNemo](https://github.com/TheBlackPlague/StockNemo) Stingray 5.7.0.0 | [Shaheryar Sohail](https://github.com/TheBlackPlague) | 3189 | ↓2922 | Written in C#! |
| [Drofa](https://github.com/justNo4b/Drofa) 3.3.22 | [No4b](https://github.com/justNo4b) | 3182 | 3245 | Drofa started as fork of the Shallow Blue chess engine - it's now much stronger, and is among the strong HCE engines. |
| [Svart](https://github.com/crippa1337/svart) 3 | [Crippa](https://github.com/crippa1337) | ~2811 | 2886 | Written in Rust! |
| [ice4](https://github.com/MinusKelvin/ice4) TCEC S24 Swiss | [MinusKelvin](https://github.com/MinusKelvin) & [Analog Hors](https://github.com/analog-hors) | ~2800 | * | ice4 is a chess engine which fits in 4096 bytes. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [4ku](https://github.com/kz04px/4ku) 2.0 | [kz04px](https://github.com/kz04px), [Gedas](https://github.com/GediminasMasaitis), [Gian-Carlo Pascutto](https://github.com/gcp), and [others](https://github.com/kz04px/4ku/graphs/contributors) | 2690 | 2758 | A UCI chess engine in 4 kB. The 4ku-mini script contains compressed C++ source code, that is extracted and compiled before being run. Written to take part in the [TCEC's 4K tournament](https://wiki.chessdom.org/TCEC_4k_Rules) |
| [Polaris](https://github.com/Ciekce/Polaris) 1.4.1 | [Ciekce](https://github.com/Ciekce) | ~2675 | ↓2514 | "author has a catboy as pfp" ~ crippa |
| [Cheers](https://github.com/Algorhythm-sxv/Cheers) 0.2.2 | [Algorhythm](https://github.com/Algorhythm-sxv) | 2649 | 2654 | A Rust HCE engine! |
| [Peacekeeper](https://github.com/Sazgr/peacekeeper) 1.30 | [Sazgr](https://github.com/Sazgr) | 2607 | 2647 | A C++ engine with simple evaluation which sucks at LTC. |
| [Willow](https://github.com/Adam-Kulju/Willow) 2.6 | [Adam Kulju](https://github.com/Adam-Kulju) | 2574 | ↓2415 | Hung a queen in its second-ever tournament game! Has a very aggressive, freewheeling style of play. |
| [Mess](https://github.com/raklaptudirm/mess) 0.1.0 | [Rak Laptudirm](https://github.com/raklaptudirm) | 2491 | 2488 | Written in Go! |
| [Akimbo](https://github.com/JacquesRW/akimbo) 0.1.1 | [JacquesRW](https://github.com/JacquesRW/akimbo) | 2471 | * | Small engine written in Rust. |
| [Altair](https://github.com/Alex2262/AltairChessEngine) 2.0.0 | [Antares](https://github.com/Alex2262) | 2409 | * | 10x12 mailbox C++ engine. |
| [Baislicka](https://github.com/kz04px/Baislicka) 1.0 | [kz04px](https://github.com/kz04px) | 2207 | 2263 | A chess engine written in C. Uses bitboards with fixed shift fancy movegen. |
| [Renegade](https://github.com/pkrisz99/Renegade) 0.9.0 | [Krisz](https://github.com/pkrisz99) | ~2200 | 2246 | A chess engine written in C++ using Visual Studio 2019. It values readability and simplicity. |
| [Valiant](https://www.dropbox.com/sh/tfiwhx900g4ni42/AABEm29llAn1MaG8D6yW8ZO7a?dl=0) Mk 7 | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | ↓~1952 | * | Mk V has a startup sound, Mk 3.2 "Archer" has reversed piece square tables, Mk 2 "Valentine" barely cares about king safety, Mk2 and Mk3's sources are lost to time... It's greatest anomaly is being able to consistently beat BBC 1.4 (with Stockfish NNUE!) |
| [Midnight](https://github.com/archishou/MidnightChessEngine) v2 | [archi](https://github.com/archishou) | 1935 | * | "it be an engine" - archi |
| [Honse](https://github.com/EngineProgramming/honse) | [The Engine Programming Discord](https://discord.com/invite/YctB2p4) | * | * | A public didactic engine open for anyone in the server to contribute to. Rust, Alpha-Beta, classical evaluation, maybe NNUE in the future. |
| [π Chess](https://www.dropbox.com/sh/tfiwhx900g4ni42/AAC5FPUjZZi1fr8TW-PEE52ja/%CF%80%20Chess.zip?dl=0) | [Enderjed](https://www.youtube.com/channel/UC1lxAkP5jGVBUIWdz3WIhSg) | * | * | A port of Tom7's Elo World's π engine. |
### Ataxx Engines
TBW
### GGPs & Other Game Engines
| Engine Name | Author | Game | Notes |
|-------------|--------|------|----------|
| [Ampersand](https://github.com/chesstastic-org/Ampersand) | [Corman](https://github.com/Cormanz/) | GGP (Fairy Chess) | Ampersand is a fairy chess engine powered by the monster-chess move generation library. It currently isn't functional. |
| [bashtet](https://github.com/analog-hors/bashtet) | [Analog Hors](https://github.com/analog-hors) | Tetris | A bash script that plays Tetris. |

# Contributing
* Engines are sorted in descending order of their CCRL 40/15 rating.
* If you are updating the version-number of an existing engine, but you lack a rating for it, prefix the earlier rating with an "↓".
