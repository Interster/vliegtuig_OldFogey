# Old Fogey vliegtuig

Planne en kode van die Old Fogey vliegtuig soos gesien op FliteTest.  
Die vliegtuig word gebou met Arduino en Raspberry Pi komponente en van rou materiale (nie van 'n uitgekoopte bou stel nie).
Die vliegtuig moet 'n lae koste hê in vergelyking met 'n uitgekoopte radio en vlugbeheerstelsel.
Die doel met die vliegtuig is om die onderliggende elektroniese konsepte onder die knie te kry.

Planne en bou instruksies:
https://www.flitetest.com/articles/FT_Old_Fogey_Scratch_Build

Video van hoe om vliegtuig te bou:
https://www.youtube.com/watch?v=w9VzlVO2adQ&t=4s

Wenk om die old Fogey planne op A4 te druk:

To print "tiled" use Adobe Reader X and in the print dialog select "POSTER", select "Cut Marks" and make sure "Tile Scale" is 100%. Thenoverlap and tape as required (after trimming the top overlapping edge). 

## Voorgestelde hardeware



| WEIGHT WITHOUT BATTERY: 13.3 oz (377 g)  |
| ---------------------------------------- |
| CENTER OF GRAVITY: 3 - 3.5 inches (76 - 89mm) from leading edge |
| CONTROL SURFACE THROWS: 12 ̊ deflection (elevator/rudder) Expo 30% |
| WINGSPAN: 37.75 inches (959mm)           |
| RECOMMENDED MOTOR: 24 g 1300 kv minimum  |
| RECOMMENDED PROP: 9 x 4.7                |
| RECOMMENDED ESC: 10 - 18 amp             |
| RECOMMENDED BATTERY: 500 - 1300 mAH 3s   |
| RECOMMENDED SERVOS: (2) 9 gram servos    |





### Skroef

Gebruik 'n 9 x 4.7 skroef.  Dit is 'n 9 duim by 4.7 duim pitch skroef.  Tipiese massa is 0.32oz of 9gram. 

### Elektriese motor (borselloos)

Dit is bekend ook as 'n "brushless motor".  Vereis 'n motor met 1300KV.  Dit beteken 1300opm per Volt.  Tipiese massa is 24gram.
Spanning is 11.1Volt met 7.5A stroom.  Drywing is 80Watt.  Tipiese stukrag is 400gram.

### Battery

Gebruik 1300mAh battery wat 11.1V is.  Dit is 'n 3 sel battery.



## Futaba hardeware

Het 'n 6J transmitter

Het volgende ontvangers of receivers:

- R2106GF
- R2006GS

## Futaba met SBUS uitset na Windows joystick

Futaba gebruik 'n SBUS protokol:



Hier word die protokolle verduidelik:

https://oscarliang.com/rc-protocols/



As jy die transmitter met 'n Windows joystick wil doen, koop 'n SBUS receiver soos:

https://futabausa.com/product/r2001sb/

Dan installeer VJOY serial feeder:

https://github.com/Cleric-K/vJoySerialFeeder

installeer VJOY driver:

https://sourceforge.net/projects/vjoystick/



Dan kan jy die transmitter oorstuur na Windows as 'n joystick.



## Maak 'n joystick met VJOY

Maak 'n VJOY joystick met 'n Arduino en 'n paar resistors en stuur die data oor IBUS protokol en stel so 'n joystick op:

https://github.com/Cleric-K/vJoySerialFeeder/blob/master/Docs/Arduino.md

Dan stel VJOY feeder op om die kanale in te lees.

Kan dit dan in enige vlugsimulator gebruik.

Gebruik hierdie video as 'n gids:

https://www.youtube.com/watch?v=_lLa6RrWfoQ



## Meet stukrag

Dit is moontlik dat motor nie sterk genoeg is vir die massa van die Fogey nie.

Maak 'n opstelling om stukrag te meet.  Dit is in /meetStukrag

