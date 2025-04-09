
# H2

Verkkoon tunkeutuminen ja tiedustelu
## x) Lue ja vastaa lyhyesti kysymyksiin.
## Selitä tuskan pyramidin idea
Tuskan pyramidi kuvaa tunnistamisen vaikeutta. Mitä ylempäna ollaan, sitä vaikeampi hyökkäys on havaita, mutta sitä enemmän hyökkääjää satuttaa sen havaitseminen.
## Selitä timanttimallin (Diamond Model) idea
Timanttimallissa tarkastellaan neljää osaa: hyökkääjää, uhria, palvelinta ja haittaohjelmaa. Näiden analysointi auttaa ymmärtämään hyökkäyksen kokonaisuutta.


## a) Apache log
![pic-a](https://github.com/user-attachments/assets/2ba50b58-d80b-4450-9e5b-037481589d13)

Kävijän IP-osoite 

Käyttäjätunnus -  

Aikaleima 

HTTP pyyntö mihin kävijä haluaa ja mitä protokollaa käyttää  

HTTP-status koodi 

Vastauksen koko  

referrer viittaava url tässä tapauksessa tyhjä koska ollaan juurihakemistossa "-” 

Selaimesta ja käyttöjärjestelmästä tietoa 

Selaimen renderöinti moottori ja selaimen versio. 
## b) Nmapped
![pic-b](https://github.com/user-attachments/assets/b27e722e-18ab-4c6f-8604-e8f2b3dec395)

Aloitetaan Nmap ja aikaleima 

Scannauksen raportti localhostiin 

Palvelin on päällä 

Muita osoitteita localhostiin ei skannattu 

999 tcp porttia suljettu 

Mitä porttia käytetään 80/tcp, palvelun tila open, palvelu http, versio apache2.4.63  

Sivun otsikko 

Laitteen tyyppi 

Käyttöjärjestelmän arvio  

CPE standardi kuvata käyttöjärjestelmiä, ohjelmistoja ja laitteita. 

Verkkoetäisyys 0 koska skannattiin localhosti. 

# c) Skriptit
Käyttöjärjestelmän tunnistus -O 

Versioiden tunnistus -sV 

Traceroute --traceroute 

Skripti skannaus –sC sama kuin --script=default 
# d) Jäljet lokissa
![pic-d](https://github.com/user-attachments/assets/bddadf45-9f31-4549-8c58-d42c95113eed)
Komennolla grep -i nmap /var/log/apache2/access.log 

“global regex print” -i osa tarkoittaa, että ei oteta huomioon onko isolla vai pienellä ja loppu tottakai mistä etsitään. 

# e) Wire sharking
![pic-e](https://github.com/user-attachments/assets/59a6b303-6e89-49ad-91b2-48f53b235958)

HTTP suodatus paketeista, jotka sisältää nmap  

# f) Net grep
![pic-f](https://github.com/user-attachments/assets/92cdef67-715b-47dd-aeec-ce3df436441c)

Enemmänkin olisi ollut, mutta eikai kannata rullailla useempaa riviä kuin nuo. 

# g) Agentti
![pic-g](https://github.com/user-attachments/assets/6eabf620-4dbf-4935-9b33-9afeb016766d)


# h) Pienemmät jäljet
![pic-h1](https://github.com/user-attachments/assets/e946d78b-87ca-4ce0-add8-03a5cc3cc338)
![pic-h2](https://github.com/user-attachments/assets/7f0c123e-2268-45b8-84e0-856de6dd7ebe)



# i) Hieman vaikeampi: LoWeR ChEcK
Eipä näy enään wiresharkilla tai acesslogissa 
![pic-i1](https://github.com/user-attachments/assets/fb8e3dfb-5109-4cfb-ae13-e1ee09223ea6)
![pic-i2](https://github.com/user-attachments/assets/56e59f5e-baaf-4fd4-8f15-f9c62de573bf)
![pic-i3](https://github.com/user-attachments/assets/80bc7ed7-ce25-4a65-b60d-e66c3f6d170a)


