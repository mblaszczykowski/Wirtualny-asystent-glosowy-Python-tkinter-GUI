# Wirtualny asystent głosowy stworzony w języku Python z GUI
> Wirtualny asystent głosowy z GUI wykonany w języku Python, obsługujący język polski, wykorzystujący moduł speech_recognition do rozpoznawania mowy oraz pyttsx3 do generowania odpowiedzi z użyciem głosu, oferujący wiele funkcji przedstawionych poniżej

## Bezpośrednie odnośniki
* [Ogólne informacje](#ogolne-informacje)
* [Wykorzystane technologie](#wykorzystane-technologie)
* [Funkcje](#funkcje)
* [Zrzuty ekranu](#zrzuty-ekranu)
* [Setup](#setup)
* [Użytkowanie](#użytkowanie)
* [Status projektu](#status-projektu)
* [Przyszłe aktualizacje](#przyszłe-aktualizacje)
* [Kontakt](#kontakt)
<!-- * [License](#license) -->


## Ogólne informacje
- Provide general information about your project here.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Wykorzystane technologie
- Python 3.9
- Python built-in `tkinter` module
- Python `SpeechRecognition` module
- Python `pyttsx3` module
- Python `webbrowser` module


## Funkcje
### Powiedz:
Strony internetowe:
- Powiedz `facebook`, a następnie poczekaj na odpowiedź i `imię i nazwisko/nazwę`, aby wyszukać takie profile/wydarzenia na Facebook'u
- Powiedz `youtube` + `fraza do wyszukania`, aby program wyświetlił wyniki wyszukiwania tej frazy na YouTube
- Powiedz `wikipedia` + `fraza do wyszukania`, aby program wyszukał odpowiedni artykuł na Wikipedii i przeczytał go na głos
- Powiedz `allegro` + `fraza do wyszukiwania`, aby program przeniósł do wyników wyszukiwania tej frazy na Allegro
- Powiedz `soundcloud` + `nazwa utworu/albumu/artysty`, aby program przeniósł do wyników wyszukiwania tej frazy na SoundCloud
- Powiedz `grafika` + `nazwa grafiki do wyszukania na Google Grafika`, aby program wyświetlił wyniki
- Powiedz `mapy` lub `pokaż na mapie` + `adres/nazwę miejsca`, aby program wyświetlił konkretną lokalizację w Mapach Google
- Powiedz `jak dojadę`, aby włączyć Jak Dojadę

Inne:
- Powiedz `zapisz` + `tekst do zapisania w notatce`, aby program zapisał notatkę na pulpicie
- Powiedz `przypomnienie` + `czas` + `jednostka czasu (sekund/minut)` + `tytuł jednowyrazowy`, aby ustawić przypomnienie 
Przykład: `przypomnienie 20 minut obiad`
- Powiedz `tłumacz` + `fraza do przetłumaczenia` + `na angielski/na polski/na francuski`, aby program przetłumaczył i wymówił oraz wyświetlił konkretną frazę
- Powiedz `pogoda` + `miasto`, aby program powiedział pogodę dla tego miasta
- Zawrzyj `godzina` w wypowiedzi, aby program powiedział aktualną godzinę
Przykład: `która jest godzina?`
- (*) Powiedz `mail`, aby wysłać maila do osoby wybranej w konfiguracji

(*) Konfigurowalne:
    Jeśli podałeś ścieżkę, powiedz:
        `kalendarz`
        `kalkulator`
        `muzyka`
        `zdjęcia`
        `książka`
        `projekty`
    A program za Ciebie otworzy wybrany folder.
        
(*) oznacza, że konfigurowalne rzeczy zostaną wkrótce dodane, w panelu menu

Zadania:
- Powiedz `wyświetl zadania` albo `pokaż zadania`, aby wyświetlić swoje zapisane w aplikacji zadania 
- Powiedz `dodaj zadanie` + `treść zadania do zapisania`, aby zapisać nowe zadanie
- Powiedz `usuń zadanie` + `numer zadania`, aby usunąć konkretne zadanie
- Powiedz `usuń wszystkie zadania`, aby usunąć wszystkie zapisane zadania

### Napisz:
- Napisz: `wikipedia`/`wiki`+`ilość zdań` + `wydarzenie/frazę/postać`
Przykład: `wikipedia4 Nikola Tesla`
Przykład: `wiki3 Elon Musk`
- Napisz `clear`, aby wyczyścić chat
- 
    'mail*<adresodbiorcy@gmail.com>*<tytul>*<tresc>'
    lub
    'mail*<adresodbiorcy@gmail.com>*<tresc>'

    'nudzi mi się' lub 'motywacja' lub 'co robić'

    'darkmode', aby włączyć darkmode!
    'whitemode', aby wrócić do whitemode'a

### Napisz/powiedz:
    przepisy/danie wegetrianskie
    przepisy/danie w


- Więcej wkrótce...

###Jeśli nie wymówisz/nie napiszesz żadnej frazy z powyższych, Twoja wypowiedź zostanie wysłana jako zapytanie do Google i wyświetlona w postaci wyników wyszukiwania


## Zrzuty ekranu
![Example screenshot](./img/screenshot.png)
<!-- If you have screenshots you'd like to share, include them here. -->


## Setup
Aby włączyć program, potrzebny jest Python 3.x oraz pobranie następujących bibliotek:
- `pip3 install SpeechRecognition`
- `pip3 install pyttsx3`
- `pip3 install webbrowser`
- `pip3 install pyaudio`


W razie problemów z instalacją PyAudio, na MacOS powinno zrobić się tak:
- Zainstaluj Xcode

Następnie w Terminalu:
- `xcode-select --install`
- `brew remove portaudio`
- `brew install portaudio`
- `pip3 install pyaudio`


## Użytkowanie
Kliknij w mikrofon i zacznij mówić, bądź wpisz pożądaną frazę w pole tekstowe.


## Status projektu
W trakcie rozwijania, możliwości tego programu są niemalże nieograniczone, więc jeżeli masz jakieś propozycje na nową funkcjonalność, zapraszam do kontaktu poniżej.


## Przyszłe aktualizacje
Do poprawienia:
Na MacOS po wywołaniu funkcji odpowiadającej za mówienie przez program, program crashuje. Na Windows tego nie było.

Do dodania:
- Dodać okno ustawień aplikacji
- Dać możliwość wyboru ile zdań ma zostać przeczytanych na głos z Wikipedii podczas czytania artykułu (aktualnie 2) w ustawieniach aplikacji
- Dodać (*) konfigurowalne rzeczy - możliwość ich konfiguracji 
- Dać w ustawieniach możliwość dodania maili do najbliższych osób z ich imionami, a następnie wywoływanie ich przez:
    - "Napisz maila do Pauli" 
    - "Jaki temat maila?"
    - "Temat"
    - "Jaka treść?"
    - "Treść"
    - "Mail wysłany"


## Kontakt
Mail: michvlbbb@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
