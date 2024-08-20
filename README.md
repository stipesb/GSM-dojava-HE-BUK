kada se jedan od pinova D (10, 11, 12, 13) prespoji sa GND, tajmer pocinje odbrojavati 15 sekundi. Ako se stanje u međuvremenu nije promijenilo, modul SIM800A poziva određeni broj mobitela. Kada se završi sa pozivom, korisnik može poslati poruku modulu sa kodnom riječju " ZAUSTAVI " (poruka ide bez navodnika). Modul bi trebao zaprimiti tu poruku i vratiti natrag poruku "naredba zaprimljena" te sklop vise nece izvrsavati pozive prema korisniku. Ako se poruka ne posalje, modul ce pozivati svakih 15 sekundi korisnika. Ponovna aktivacija modula izvrsava se porukom " POKRENI ", moze se i malim slovima slat jer je ovo high tech projekt.

Koristeni su moduli SIM800A, Arduino UNO i regulator napona s kondezatorom. SIM800A modul je dosta osjetljiv, te zna povuci do 2A struje. Tako da je kondezator bio nuzan da se ispegla napon...



dobri linkovi s literaturom

https://microchip.ua/simcom/2G/SIM800%20Series_AT%20Command%20Manual_V1.12.pdf

https://www.manelsoft.com/projects/arduino_sim800.aspx

https://lastminuteengineers.com/sim800l-gsm-module-arduino-tutorial/
