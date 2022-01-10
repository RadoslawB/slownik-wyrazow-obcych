# Słownik wyrazów obcych

Szukasz polskiego slownika wyrazów obcych? Zobacz  plik `./thesaurus.csv`. 
Jeśli Twoim celem jest poszerzenie swojego słownictwa, słownik ten wgrałem również do aplikacji Anki która pozwala na łatwą naukę wykorzystując efekty podejście space-time-repetition.
Link do [talii Anki](https://ankiweb.net/shared/info/341353038)

Glosariusz powstał przez scrapowanie ponad 10'000 [stron](`http://www.edupedia.pl/map/dictionary/id/8_slownik_wyrazow_obcych.html`) z hasłami. 

| Hasło | Definicja | 
|---|---|
| lapidarny  | (przym.) <niem. lapidar, fr. lapidaire, z łac. lapidarius kamienny; litterae lapidariae napis wyryty na kamieniu (nagrobnym)> zwięzły, wyrazisty, treściwy: lapidarna odpowiedź, wypowiedź, ocena |
|sago|(n; ndm) <mal. sagu> kaszka, mączka jadalna z rdzenia pnia i gałęzi niektórych drzew z rodziny sagowców"
|
| mizantropijny  | (przym.) <od mizantropia> niechętny ludziom, zgorzkniały

Pełna procedura scrapowania i stworzenia pliku ze słownikiem znajduje się w `./scrape-and-create-thesaurus.ipynb`
 
## Uruchomienie projektu
###Wymagania wstepne
1.  [poetry](https://python-poetry.org/docs/)

### Instalacja
```bash
poetry install 
```

### Uruchomienie
```bash
poetry run jupyter notebook
```
