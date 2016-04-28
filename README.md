# RysGettingStarted
Instrukcja uruchomienia robota RYŚ

##Potrzebne elementy
1. Robot Ryś
2. Netbook sterujący (z naładowaną baterią)
3. Naładowany żelowy akumulator 12V
4. Kontroler (pad bezprzewodowy usb)

##Przygotowanie do uruchomienia
1. Należy włożyć akumulator, podłaczyć odpowiednio przewody zasilające i zabezpieczyć akumulator śrubą przed wypadnięciem. 
2. Następnie trzeba upewnić sie że wszystkie przewody sa odpowiednio podłączone oraz że koła robota mogą obracać się swobodnie. 

##Uruchomienie netbooka sterującego
1. Nalezy uruchomić komputer i poczekać aż na ekranie pojawi się komunikat checking battery state.
2. Jeżeli pojawia się informacja waiting for network należy włączyć moduł WiFi nasiakając Fn+(przycisk od wifi).
3. Nastepnie przełaczyć się na konsolę kombinacją przycisków CRTL+ALT+F2
4. Kolejnym krokiem jest logowanie za pomocą nazwy uzytkownika: eee i hasło: *********
5. Teraz podłączamy odbiornik od kontrolera w prawym gnieździe USB.
6. Następnie nalezy wpisać komandę ros-launch... i w ciągu kilku sekund podłączyć pod gniazda usb z lewej strony kolejno wtyczkę oznaczoną białą taśmą a następnie pozostałą. 
7. Jezeli podczas uruchamiania nie wystapiły zadne błędy można przejśc do kolejneog kroku. Jezeli operacja się nie powiodła nalezy wyjść komenda Crtl+c, odłaczyć wtyczki z portów USB po lewej stronie i powtórzyć krok6. 

##Przygotowanie robota do jazdy
1. Jeżeli poprzednie operacje sie powiodły, możemy sprawdzić czy komunikacja z padem przebiega prawidłowo (WAŻNE robot musi być wyłaczony).
2. Przechodzimy na widok innej konsoli klawiszami Alt+Crtl+F3 i wpisujeny ros-topic...
3. Jeżeli pojawiają się dane przy poruszaniu joystickiem na padzie to znaczy ze wszystko jest ok. 
4. Możemy przystąpić do montazu netbooka na robocie. Nalezy w tym celu ostroznie umieścić kompuer w kieszeni i zabezpieczyć go aluminiowym kontownikiem przymocowanym za pomoca 2 nakretek. 

##Uruchomienie robota 
1. Jeżeli wszystko do tej pory przebegało poprawnie możemy ustawić robota w bezpiecznym miejscu w pozycji lezącej i włączyć przycisk zasilania. 
2. sterowanie robotem odbywa się za pomocą pada, 
3. Jezlei robot znajdzie sie w pozycji pionowej to sam przechodzi do trybu balansowania więc wystarczy go postawić. 

##Wyłaczanie robota
1. Nalezy wyłaczyć robota orzy pomocy wyłacznika gółwnego
2. Nastepnie demontujemy zabezpieczenie netboka i ostroznie wyjmujemy go z kieszeni
3. Wyłączamy program sterujący Crtl+c i wyłączamy komputer komenda poweroff
4. Odłączmy wszystkie urzadzenia usb
5. Odkładamy wszystkie komponenty w przeznaczone miejsce ,wyjmujemy akumulator i jezeli wymaga naładowania to ładujemy, ładujmy rózniierz netbooka. 
6. Netbooka przechowujemy z wyjętą baterią. 


