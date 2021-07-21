# Wirtualny asystent głosowy stworzony w języku Python z GUI
> Wirtualny asystent głosowy z GUI wykonany w języku Python, obsługujący język polski, wykorzystujący moduł speech_recognition do rozpoznawania mowy oraz pyttsx3 do generowania odpowiedzi z użyciem głosu, oferujący wiele funkcji przedstawionych poniżej

## Bezpośrednie odnośniki
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
<!-- * [Acknowledgements](#acknowledgements) -->
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
- Provide general information about your project here.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.9
- Python built-in `tkinter` module
- Python `SpeechRecognition` module
- Python `pyttsx3` module
- Python `webbrowser` module


## Funkcje
Strony internetowe:
- Powiedz `facebook`, a następnie poczekaj na odpowiedź i `imię i nazwisko/nazwę`, aby wyszukać takie profile/wydarzenia na Facebook'u
- Powiedz `wikipedia` + `fraza do wyszukania`, aby program wyszukał dla nas odpowiedni artykuł na Wikipedii i przeczytał go na głos
- 

Zadania:
- Powiedz `wyświetl zadania` albo `pokaż zadania`, aby wyświetlić swoje zapisane w aplikacji zadania 
- Powiedz `dodaj zadanie` + `treść zadania do zapisania`, aby zapisać nowe zadanie
- Powiedz `usuń zadanie` + `numer zadania`, aby usunąć konkretne zadanie
- Powiedz `usuń wszystkie zadania`, aby usunąć wszystkie zapisane zadania
- 

- Więcej wkrótce...


## Zrzuty ekranu
![Example screenshot](./img/screenshot.png)
<!-- If you have screenshots you'd like to share, include them here. -->


## Setup
Aby włączyć program, potrzebny jest Python 3.x oraz pobranie następujących bibliotek:
- `pip3 install SpeechRecognition`
- `pip3 install pyttsx3`
- `pip3 install webbrowser`
- `pip3 install pyaudio`

\
\

W razie problemów z instalacją PyAudio, na MacOS powinno zrobić się tak:
- Zainstaluj Xcode

Następnie w Terminalu:
- `xcode-select --install`
- `brew remove portaudio`
- `brew install portaudio`
- `pip3 install pyaudio`


## Usage
How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`


## Status projektu
W trakcie rozwijania, możliwości tego programu są niemalże nieograniczone, więc jeżeli masz jakieś propozycje na nową funkcjonalność, zapraszam do kontaktu poniżej.


## Przyszłe aktualizacje

Do poprawienia:
-
-

Do dodania:
- Dodać okno ustawień aplikacji
- Dać możliwość wyboru ile zdań ma zostać przeczytanych na głos z Wikipedii podczas czytania artykułu (aktualnie 2) w ustawieniach aplikacji
- Improvement to be done 2


<!--
## Acknowledgements
Give credit here.
- This project was inspired by...
- This project was based on [this tutorial](https://www.example.com).
- Many thanks to...
-->


## Kontakt
Mail: michvlbbb@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
