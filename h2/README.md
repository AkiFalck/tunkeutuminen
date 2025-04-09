
# H2

Verkkoon tunkeutuminen ja tiedustelu

## a) Apache log
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-a.png

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
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-b.png
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
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-d.png
Komennolla grep -i nmap /var/log/apache2/access.log 

“global regex print” -i osa tarkoittaa, että ei oteta huomioon onko isolla vai pienellä ja loppu tottakai mistä etsitään. 

# e) Wire sharking
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-e.png
HTTP suodatus paketeista, jotka sisältää nmap  

#f) Net grep
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-f.png
Enemmänkin olisi ollut, mutta eikai kannata rullailla useempaa riviä kuin nuo. 

# g) Agentti
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-g.png

# h) Pienemmät jäljet
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-h1.png
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-h2.png

# i) Eipä näy enään wiresharkilla tai acesslogissa 
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-i1.png
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-i2.png
/home/akif/Documents/projektit/tunkeutuminen/h2/pic-i3.png
