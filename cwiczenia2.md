Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

git
yum install git/apt-get install git --- centos/ubuntu??
git clone https://github.com/jkanclerz/http-chat
python http-chat


curl -X POST -d '{"text": "Hello World"}' https://10.0.5.4:8888/chat --- symuluje przeglądarkę, wysyła tekst do czatu

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | | |
| MASKA  | | |
|   |  | |
| PC 2  |  | |
| IP - address  | 10.0.2.15 | |
| MASKA  | | |

Weryfikacja połączenia

Polecenie
```

```

Efekt
```
```

Statyczna konfiguracja parametrów połączenia
Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 192.168.10.10 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 172.16.100.100 | |
| MASKA  | 255.255.0.0 | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Nowa statyczna konfiguracja 

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |  | |
| MASKA  |  | |
|   |  | |
| PC 2  |  | |
| IP - address  |  | |
| MASKA  |  | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Warto wiedzieć
--------------

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Lokalizacja pliku z konfiguracją sieci| | |
| UP -> Wyłączenie interfejsu sieciowego| ifup nazwa | |
| DOWN -> Włączenie interfejsu sieciowego| ifdown nazwa | |
| Sprawdzenie obecnych parametrów | nmcli ??  | centos i ubuntu, w debianie nie ma|
| lista wszystkich interfejsów | ip a | |
| Które interfejsy jakie porty słuchają | | | cat /etc/resolv.conf
