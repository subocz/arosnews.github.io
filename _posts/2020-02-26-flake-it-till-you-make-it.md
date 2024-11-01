---
layout: post
title: AROS x86 - październik 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1024
---

Dawno nie działo się tak wiele jednocześnie. W tym miesiącu dostaliśmy zbiorczą aktualizację do wersji bazowej systemu ABIv0, mamy nową wersję przeglądarki internetowej, a na dodatek zaczęły się pojawiać wersje x64 ważnego oprogramowania. Parafrazując slogan Commodore: "Are you keeping up with the AROS?". Mam nadzieję, że tak!

Firma AirSoft Softwair wydała nową wersję wtyczki do programu Hollywood, która umożliwia odtwarzanie plików dźwiękowych w formacie SID. W wersji 2.0 dokonano całkowitej zmiany głównego silnika obsługującego ten format, zastępując TinySID nowym cRSID. Dzięki temu emulacja jest bardziej precyzyjna i wspiera Real SID. Wersję dla AROS x86 można pobrać [stąd](https://www.hollywood-mal.com/download/SID_Amiga.lha).

Nowe pozycje w AROS-Archive od zeszłego miesiąca:

> ## [Raylib](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_raylib5.i386-aros.zip) (v. 5.0)
> (autor: www.raylib.com, port by Serk118)

Raylib 5

![Raylib](/assets/img/1024/SkyBallsAros.png)
*Raylib 5*

> ## [GLFW](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_glfw_3_4.i386-aros.zip) (v. 3.4)
> (autor: www.glfw.org, port by Serk118)

GLFW 3.4

![GLFW](/assets/img/1024/SkyBallsAros.png)
*GLFW 3.4*

> ## [rFXGen](https://archives.aros-exec.org/?function=showfile&file=audio/rfxgen-aros.zip)
> (autor: raylibtech.itch.io/rfxgen, port by Serk118)

Prosty i łatwy w użyciu generator efektów dźwiękowych.

Funkcje:  
- Predefiniowane **ustawienia dźwiękowe** (Coin, Shoot, Explosion, PowerUp...)
- Obsługa wielu typów fal (kwadratowa, piłokształtna, sinusoidalna, szum)
- Do **5 slotów dźwiękowych** do przechowywania wygenerowanego dźwięku (zapis tymczasowy)
- Wczytywanie plików `.rfx` z parametrami generowania dźwięku
- Zapisywanie plików `.rfx` z parametrami generowania dźwięku (**104 bajty**)
- Eksport danych wave jako `.wav`, `.raw` lub `.h` (tablica bajtów)
- Konfigurowalna częstotliwość próbkowania, bity na próbkę i kanały podczas eksportu
- Wiele stylów GUI z obsługą niestandardowych (`.rgs`)
- Obsługa konwersji wsadowej `.rfx` do `.wav` z wiersza poleceń
- Odtwarzacz audio z wiersza poleceń dla plików `.wav`, `.ogg`, `.mp3` i `.flac`
- Całkowicie przenośny (jednoplikowy, bez zależności)**.
- **Darmowy i open-source**

![rFXGen](/assets/img/1024/SkyBallsAros.png)
*rFXGen*

> ## [RayGui](https://archives.aros-exec.org/?function=showfile&file=development/misc/raygui.i386-aros.zip)
> (autor: github.com/raysan5/raygui, port by Serk118)

RayGui

![RayGui](/assets/img/1024/SkyBallsAros.png)
*RayGui*

> ## [kMusicPlayer](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip)
> (autor: github.com/notkatsuu/kMusicPlayer, port by Serk118)

kMusicPlayer to wizualny odtwarzacz muzyki zbudowany z C i Raylib. Zapewnia prosty interfejs wizualny do odtwarzania ulubionych utworów muzycznych.  

Główne cechy:
- Odtwarzanie muzyki: Łatwe odtwarzanie ulubionych utworów. Obsługuje formaty .mp3 i .wav.
- Wizualizacja kształtu fali: Wizualizacja muzyki dzięki renderowaniu kształtu fali.
- Wątkowe ładowanie muzyki: Szybkie ładowanie muzyki dzięki ładowaniu wątkowemu.
- Proste sterowanie: Kontroluj odtwarzanie za pomocą prostych skrótów klawiaturowych w RayGUI.

![kMusicPlayer](/assets/img/1024/SkyBallsAros.png)
*kMusicPlayer*

> ## [BeeBase](https://archives.aros-exec.org/?function=showfile&file=office/database/beebase-1.1.lha) (v. 1.1)
> (autor: Steffen Gutman)

BeeBase to relacyjny, programowalny system baz danych z graficznym interfejsem użytkownika dla wszystkich systemów amigowych, a także dla Windows, Mac i Linux. Siła BeeBase leży w graficznym interfejsie użytkownika i możliwościach programowania. Umożliwia on przetwarzanie danych na różne sposoby, np. automatyczne obliczenia po wprowadzeniu danych przez użytkownika, generowanie raportów, importowanie i eksportowanie danych itp. 

![BeeBase](/assets/img/1024/beebase.png)
*BeeBase*

> ## [Koala Seasons](https://archives.aros-exec.org/?function=showfile&file=game/strategy/koala_seasons.i386-aros.zip)
> (autor: www.raylib.com, port by Serk118)

Walcz z żywiołami! Walcz z wrogami! Ocal świat! Jak długo uda ci się przetrwać? Ta gra została pierwotnie stworzona przez emegeme jako benchmark dla Raylib na urządzeniach z Androidem.

![Koala Seasons](/assets/img/1024/SkyBallsAros.png)
*Koala Seasons*

> ## [Amifish](https://archives.aros-exec.org/?function=showfile&file=game/board/amifish.i386-aros.lha) (v. 2.0)
> (autor:	Domenico Lattanzi)

Amifish to program szachowy stworzony do gry w szachy na systemach amigowych, wykorzystujący moc jednego z najpotężniejszych silników szachowych na świecie: Stockfish, opracowanego przez Torda Romstada, Marco Costalbę, Joonę Kiiski i Gary'ego Linscotta. Silnik szachowy to program konsolowy, który gra w szachy, odbierając ciągi znaków jako polecenia i generując ciągi znaków na wyjściu jako wynik obliczeń. Stockfish i wiele innych silników jest kompatybilnych ze standardem o nazwie UCI (Universal Chess Interface). Nazwa Amifish powstała z połączenia słów Amiga i Stockfish (choć projekt jest otwarty dla wszystkich silników zgodnych ze standardem UCI), jest lekkim programem dla amatorów, stworzonym do zabawy w szachy, z zaimplementowanymi tylko najważniejszymi opcjami.

Do gry przeciwko komputerowi potrzebny jest silnik szachowy Stockfish, który również można pobrać z AROS Archives.

![Amifish](/assets/img/1024/amifish.png)
*Amifish*

> ## [GemRB](https://archives.aros-exec.org/?function=showfile&file=game/roleplaying/gemrb-0.8.8-0.i386-aros.zip) (v. 0.8.8-0)
> (autor: The GemRB Project)

GemRB

![GemRB](/assets/img/1024/blackivancard.jpg)
*GemRB*

> ## [CabExtract](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip) (v. 1.11)
> (autor: Stuart Caie, port by Farox)

Program do rozpakowywania plików Microsoft Cabinet. Pliki Cabinet (`.CAB`) są formą archiwum, którego Microsoft używa do dystrybucji swojego oprogramowania i rzeczy takich jak Windows Font Packs. Program cabextract rozpakowuje te pliki.

![CabExtract](/assets/img/1024/SkyBallsAros.png)
*CabExtract*

> ## [Unshield](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unshield.i386-aros.zip) (v. 1.5.1)
> (autor:	David Eriksson, port by Farox)

Narzędzie do wyodrębniania plików `.CAB` z pliku `.exe` InstallShield.

![Unshield](/assets/img/1024/MemoryGameAros.png)
*Unshield*

> ## [SetScreenMode](https://archives.aros-exec.org/?function=showfile&file=utility/shell/setscreenmode.i386-aros.zip) (v. 1.0)
> (autor:	Nigel Tromans)

SetScreenMode

![SetScreenMode](/assets/img/1024/organica.jpg)
*SetScreenMode*

> ## [Perl](https://archives.aros-exec.org/?function=showfile&file=development/language/perl-5.7.2.x86_64-aros-v11.zip) (v. 5.7.2)
> (autor: Stanislaw Szymczyk)

Perl

![Perl](/assets/img/1024/baccarat.jpg)
*Perl*

> ## [Python](https://archives.aros-exec.org/?function=showfile&file=development/language/python-2.5.2.x86_64-aros-v11.zip) (v. 2.5.2)
> (autor: Stanislaw Szymczyk)

Python 2.5.2

![Python](/assets/img/1024/baccarat.jpg)
*Python 2.5.2*

> ## [Adoom3](https://archives.aros-exec.org/?function=showfile&file=game/fps/adoom3-1.5.3.x86_64-aros-v11.zip) (v. 1.5.3)
> (autorzy:	Nick 'Kalamatee' Andrews)

Adoom3

![Adoom3](/assets/img/1024/neandertaler.jpg)
*Adoom3*



