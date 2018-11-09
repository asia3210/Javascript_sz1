# Wymagane narzędzia:
* git
* node/npm (https://nodejs.org/en/)

## Test setupu

```git clone https://kwasniew@bitbucket.org/kwasniew/training_setup_test.git```

```cd training_setup_test```

```npm i```

Proszę sprawdzić czy zainstalowały się biblioteki w katalogu node_modules

## Grupa II (temat TDD)

Proszę przetestować dostęp do testowego API: https://www.alphavantage.co/query?apikey=QHA8XN081HBT7UHR&function=TIME_SERIES_DAILY&datatype=csv&symbol=GOOG

API powinno zwrócić plik CSV z danymi giełdowymi.

### Grupa I (temat frontend architecture)

Trener dostarczy w trakcie szkolenia API do aplikacji frontendowej. API będzie potrzebować bazę MongoDB (https://docs.mongodb.com/manual/administration/install-community/).
Przed zajęciami proszę sprawdzić czy baza startuje.
Pomocny może być parametr --dbpath wskazujący katalog na dysku.

Dodatkowo proszę przetestować instalację zależności które będą używane.
```
cd groupI
npm i
```

Częsty problem w systemie Windows: https://catalin.me/how-to-fix-node-js-gyp-err-cant-find-python-executable-python-on-windows/