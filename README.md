Pierwsze programy służą do sumowania wektorów z CPU i GPU. W zależności od N(gdy jest mało) przypadków CPU sobie radzi nieznacznie lepiej, natomiast im więcej przypadków, wtedy GPU zaczyna przodować poprzez rozłożenia zadania na mniejsze wykonując je równolegle. W tym momencie mamy doczyninia z obliczaniem mniejszej ilości wektorów, wtedy CPU radzi sobie nieznacznie lepiej niz GPU.
Drugie programy służą do obliczania punktów Fraktalu Julii. Programy oblicza ogromną ilość punktów, dzięki czemu w tej sytuacji lepiej sobie radzi GPU, natomiast CPU jest o wiele wolniejszy.
Wyniki dla fraktalu Julii:
CPU: 2 min 16s, 1 min 43s, 2 min 1s, 1 min 51s
GPU: 2s, 1s, 1s, 2s

![ccccccc](https://user-images.githubusercontent.com/79971854/146847062-0cee5cb3-9f4c-40d6-bea6-8d8945315356.png)


Wnioski: Po przetestowaniu powyższych przykładów różniących się poziomem zaawansowania można bez zbędnych złudzeń, że GPU jest dużo wydajniejszy, przez co pozwala rozłożyć zadania na mniejsze  wykonywane równolegle. Jedynie CPU jest lepsze, gdy mamy doczynienia z mniej skomplikowanymi programami. Ponadto programy pisane na CPU zawiera łatwiejszy kod, jednakże GPU jest lepszym wyborem ze względu na o wiele większą moc obliczeniową.

PS. przez przypadek z edytowałem przez co jest inna data
