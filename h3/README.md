# H3

Verkkoon tunkeutuminen ja tiedustelu
## x) Lue ja tiivistä.
- URH:n käytöstä opetusvideo jossa siepataan ja kopioidaan kaukosäätimen singaali toimimaan toisella piirilevyllä.
- rtl_433 ohjelmaa käytetään tutkimaan auriol sää aseman singaalia
- URH ohjelmaan hiukan syvällisempi ohje mitä aikasempi video tarjosi

## a) WebSDR
Taajuus 13635.03 kHz
Aallonpituus 1365035030 Hz / 300 000 000 m/s = 22m
Modulaatio USB 
![Screenshot From 2025-04-16 12-41-07](https://github.com/user-attachments/assets/dde4eec4-9374-4c62-a7db-47d00237d8c0)

Ekaksi klikkaamalla lähemmäs selkeää viivaa paljon laajemmassa vesiputous näkymässä sen jälkeen hieno säätämällä kanava kuulumaan selkeästi.
Eipä sieltä kuulunut turkkilaista musiikkia kummempaa.

## b) rtl_433
![Screenshot From 2025-04-15 22-27-01](https://github.com/user-attachments/assets/25e271fc-dd4c-4a90-bbf9-1e705bb43f26)

## c) Automaattinen analyysi
![Screenshot From 2025-04-15 22-29-37](https://github.com/user-attachments/assets/6b96b416-8e9c-4eff-87fd-37d3acc96f5a)
![Screenshot From 2025-04-15 22-35-11](https://github.com/user-attachments/assets/be68ad0f-0cbe-469f-bfa1-a89e46a459ac)
![Screenshot From 2025-04-15 22-36-58](https://github.com/user-attachments/assets/19fd8251-196a-49ed-b9fa-d8d4a38da7e8)


## d) too complex16?
![image](https://github.com/user-attachments/assets/0d5461e0-03a1-491c-88ee-16283bf371c2)
![image](https://github.com/user-attachments/assets/4eb7bcd3-b2dd-4b30-9e85-31ca901aa08c)
- Ilmeisesti sama laite kyseessä

## e) URH
Piti asentaa suoraan gitistä ja ajaa polusta /urh/src/urh ./main.py tiedosto, että ohjelman sai auki.

## f) Yleiskuva
5.42s 
Taajuus 433.912 Mhz
Nauhoitettu 12.04.2025 

## g) Bittistä
ASK modulaatio.
Autodetectistä saatu 1bitti per 500 näytettä ja ja näytteessä on 2Miljoonaan näytettä sekunnissa voidaan laskea arvoksi 500 / 2 000 000 =  0.00025s
Raakabitti 250 mikrosekuntia = 0.00025s eli vaikeata verrata mihinkään.
![image](https://github.com/user-attachments/assets/b016ba56-67dc-46e8-af4d-ddca9c0e8bfc)

