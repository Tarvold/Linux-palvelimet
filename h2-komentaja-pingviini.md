# Command Line Basics Revisited
- Linuxissa käytettävä komentorivi on säilyttänyt paikkansa ajan kuluessa.
- Se on vanhempi kuin Windows tai Internet.
- Se on kätevä, nopea ja helposti automatisoitavissa.
- Komentojen avulla voidaan liikkua eri kansioiden ja tiedostojen välillä, muokata tiedostoja, ottaa SSH etäyhteys jollekin palvelimelle.
- Komentoriviä käyttämällä pystytään myös päivittämään ja asentamaan uusia ohjelmia.
- En tiedä onko itselläni asetuksissa jotain vikaa, mutta kaikki näppäimet eivät toimi samalla tavall kuin Windowsissa, esim. + ja - ovat toisinpäin.
  
# Micro 2.9.2024 12:00
Avasin komentorivin.

Päivitin paketit "sudo app-get update" -komennolla.

Asensin Micron "sudo apt-get install micro" -komennolla.

# Apt.

## Fish 2.9.2024 12:30
Asensin Fish-komentoriviohjelman "sudo apt-get install fish" -komennolla.

Fish ehdottaa minun aikaisempiin hakuihin liittyäviä komentoja ja tab-painiekkeella saa näkyviin listan mahdollisista komennoista.

![image](https://github.com/user-attachments/assets/69897366-0e9f-4201-ad96-53dd46f15916)

## Nano 2.9.2024 13:15
Asensin Nano-komentoriviohjelman "sudo apt-get install nano" -komennolla.

Nano on komentoriviltä käytettävä teksti editori.

![image](https://github.com/user-attachments/assets/b0817b4a-9e65-4b5e-b984-ec381927d260)

## Tilde 2.9.2024 14:30
Asensin Tilde-komentoriviohjelman "sudo apt-get install Tilde" -komennolla.

Tilde näyttää tältä.

![image](https://github.com/user-attachments/assets/c9a6ad6e-34f3-497b-8415-13e7277d88c5)
 
# FHS 3.9.2024 14:00
Komenolla "/" pääsin Root-hakemistoon, komennolla "ls" sain näkyviin:

![image](https://github.com/user-attachments/assets/c3ae0d04-78e6-485b-8b07-0e009ca537b0)

Komennolla "/home/user" pääsin käyttäjän-hakemistoon, komenolla "ls" sain näkyviin:

![image](https://github.com/user-attachments/assets/708ddc9b-b9a6-4ec4-8f45-801e427f192a)

Komennolla "/etc/"  pääsin järjestelmän asetus-hakemistoon, komennolla "ls" sain näkyviin:

![image](https://github.com/user-attachments/assets/81818b6e-32c9-4c2e-aa0b-91effcb42d1a)

Komennolla "/var/log" pääsin järjestelmän loki-hakemistoon, komennolla "ls" sain näkyviin:

![image](https://github.com/user-attachments/assets/066c98a0-d8b3-41fd-972f-e9ac35f3a926)

Komennolla "/media/" ei tullut mitään:

![image](https://github.com/user-attachments/assets/105c0154-d83a-4843-b781-72a53af63bae)

# The Friendly M 3.9.2024 17:30
Grep-komennolla saan suodatettua hakutuloksista vain tiettyjä kirjaimia sisältävät tiedostot.

Komennon avulla voin myös hakea jotain tiettyä sanaa sisältävät tekstitiedostot.

Komennon avulla saan näkyviin haluamani tiedoston sijainnin.

# Pipe 3.9.2024 15:00
Putkien avulla pystyn yhdellä rivillä syöttämään ensimmäisen komennon syöte seuraavaan komentoon.

Komennolla "ls | grep host" saan "etc/"-hakemistosta näkyviin vain sellaiset tiedostot, joiden nimessä on sana "host":

![image](https://github.com/user-attachments/assets/a18a99dd-5f11-4e3c-97a9-52ebbbafabef)

# Rauta 3.9.2024 16:30
Asensin lshw:n "sudo apt-get install lshw" -komennolla.

Komennolla "sudo lshw -short sanitize" tuli näkyviin koneen käyttöjärjestelmä, järjestelmämuistin määrä, cpu:n tiedot ja näytön tiedot

