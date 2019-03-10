Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |10.0.2.15|maszyna 1 |
| MASKA  |255.255.255.0| |
|   |  | |
| PC 2  ||maszyna 2 |
| IP - address  |10.0.2.4
| MASKA  |255.255.255.0| |

Weryfikacja połączenia

Polecenie
ping 10.0.2.15/ping 10.0.2.4
10.0.2.4
0% loss


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
brak siec nie osiagalna 
Polecenie
``
ping 172.16.100.100 / 192.168.10.10
```

Efekt
```
```

Nowa statyczna konfiguracja 

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |10.0.2.10| |
| MASKA  |255.255.255.0  | |
|   |  | |
| PC 2  |  | |
| IP - address  |10.0.2.100 | |
| MASKA  |255.255.255.0   | |

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
| Lokalizacja pliku z konfiguracją sieci|/etc/network/interfaces| |
| UP -> Wyłączenie interfejsu sieciowego|ifup | |
| DOWN -> Włączenie interfejsu sieciowego|ifdown | |
| Sprawdzenie obecnych parametrów |ifconfig | |
| lista wszystkich interfejsów |ip a | |
| Które interfejsy jakie porty słuchają | | |

