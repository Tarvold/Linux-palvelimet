# H1 - Oma Linux

## Rapotin kirjoittaminen
  - Kertoa selkeästi mitä on tehty
  - Onko kohdattu ongelmia?
  - Miten ongelmat ratkaistiin?
  - Raportti pitää kirjoittaa kieliopillisesti oikein
  - Raportin avulla toisen henkilön tulee pystyä toistamaan mitä tehtiin
  - Muista laittaa lähdeviittaukset

## FSF Free Software Definition
  - Vapaus käyttää ohjelmaa miten itse haluaa, mihin tahansa tarkoitukseen
  - Vapaus opetella miten ohjelma toimii ja muokata sitä haluammallaan tavalla. Vapaa lähdekoodi on edellytys
  - Vapaus jakaa ohjelmas eteenpäin muille käyttäjille
  - Vapaus jakaa kopioita ohjelmasta, johon on tehnyt itse muokkauksia. Vapaa lähdekoodi on edellytys
  - Jos jokin yllälevista ehdoita ei täyty, kyseessä ei ole vapaa ohjelmisto

## Linux asennus virtuaalikoneeseen

Lataa koneellesi uusin version Debian ISO Imagesta osoitteesta https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/
![image](https://github.com/user-attachments/assets/941102e3-d2a1-4954-8181-21341a07253d)

Kirjoitus hetkellä se on 	debian-live-12.6.0-amd64-xfce.iso
Klikkaa sitä ja lataa tiedosto koneellesi

Asenna VirtualBox koneellesi, jos sinulla sitä ei vielä ole osoitteesta https://www.virtualbox.org/wiki/Downloads
![image](https://github.com/user-attachments/assets/ec70b71b-4360-4079-b677-b3eed79a099a)
Klikkaa oman käyttöjärjestelmäsi nimeä ja lataa tiedosto koneellesi

Avaa VirtualBox ja valitse Machine-valikosta New
![image](https://github.com/user-attachments/assets/1cc10ec5-040e-4796-8f9b-e20e7f6c0f79)

Valitse alhaalta Expert Mode
![image](https://github.com/user-attachments/assets/aa6da211-c94f-408d-8b3a-c748d5d88b69)

Anna virtuaalikoneellesi nimi, kohtaan ISO Image etsi koneeltasi lataamasi tiedosto, valitse tyypiksi Linux ja versioksi Debian (64-bit)
![image](https://github.com/user-attachments/assets/adff7304-b5bb-42b5-9a2d-b50697337744)

Laita täppä kohtaan Skip Unattended Installation

Määritä Hardware kohdasta koneellesi sopiva määrä RAM-muistia, mitä enemmän pystyt laittamaan sitä parempi
![image](https://github.com/user-attachments/assets/66ebae5f-6811-424e-a519-24260239c335)

Määritä Hard Disk kohdasta koneellesi sopiva määrä kovalevytilaa
![image](https://github.com/user-attachments/assets/f4be46b0-ab6b-43f2-97a7-23e725a3ce1c)

Paina alhaalta Finish-painiketta

Asennettu virtuaalikone nyt näkyvissä. Valitse ensin Settings, sitten Storage ja Optical Drive -kohdan levynkuvan valikosta Chooe/Create Virtual Optical Disk
Minulla tämä oli automaattisesti valittuna, mutta jos ei ole valitse lataamasi debian-tiedosto
![image](https://github.com/user-attachments/assets/2bc00edd-76e6-46fa-bef7-493f2799c4ab)

