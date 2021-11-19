## Ogólne informacje
Środowisko wirtualne, wpisz polecenie
`python -m venv env`

### Zapis requirements w odbywa się przez uruchomienie komendy
`pip freeze > requirements.txt`

### Instalacja zależności
Aby zainstalować te biblioteki, wpisz pip install `-r requirements.txt` w swoim terminalu

### Uruchomienie serwera 
`uvicorn main:app --reload`