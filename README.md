# Semesterprojekt i grundlæggende styring af robotter

Tegnerobot der konverterer digitale billeder til fysiske tegninger via en punktbaseret metode. Projektet inkluderer billedbehandling i Mathematica og design af elektroniske kredsløb.

---

## Projektoversigt

### Billedbehandling i Mathematica  
Billedet konverteres til gråtoner, kanter detekteres, pixelpositioner udtrækkes, og der genereres G-kode optimeret med korteste rute.

### Tegnemekanisme  
Robotten følger G-koden ved brug af G00, G01 og G98. Højden på blyanten justeres automatisk i forhold til slitage efter spidsning.

### Hardware og elektronik  
- Ekstern blyantspidser aktiveret af IR-sensor og op-amp-komparator  
- Spændingsregulator nedtransformerer 12V DC til 6V DC  
- Udvikling, analyse og test af kredsløb til motor og sensorsystem

---

## Inkluderede filer

- Semester_Project.pdf – Fuld rapport med metode, eksperimenter og kredsløbsanalyse  
- RobotCode.nb – Mathematica-kildekode til billedbehandling og G-kode-generering  
- RobotCode.pdf – PDF-version af koden  
- Datasheets/ – Mappe med databladene for de anvendte komponenter:
  - LM7805.pdf (Spændingsregulator)
  - OP505.pdf / OP593.pdf (IR-sender/modtager)
  - 1N4002.pdf, 1N4148.pdf (Dioder)
  - BC639.pdf, LM2904.pdf (Transistor og op-amp)

---

## Udførte eksperimenter

- Sammenligning af tegnehastigheder: 100 %, 200 %, 400 %  
- Forskellige billedtyper: fotografier, karakterkunst m.m.  
- Analyse af opløsningers betydning for tegningskvalitet og tid

---

## Kompetencer

- Udvikling af billedbehandlingsalgoritmer i Mathematica  
- Design og simulering af elektroniske kredsløb  
- Generering og implementering af G-kode  
- Integration og test af sensorbaserede løsninger  
- Teknisk dokumentation, samarbejde og projektledelse

---

## Bidragsydere

- Anas Butt Hussain  
- Alan Rashid  
- Thomas Vilholm  
- Jakub Hubert Rudowski

---

## Intention

Dette projekt blev afleveret som en bedømt gruppeoplevelse på Syddansk Universitet og deles her med det formål at demonstrere færdigheder og erfaring som en del af en professionel portefølje.
