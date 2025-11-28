I denna repo kommer jag att gå igenom det som jag har lärt mig under veckan.

## Vad är en mikroprocessor(CPU)?
Mikroprocessor är den centrala "hjärnan" i datorsystem. Det gör beräkningar och styr programflödet, men behöver andra komponenter för att fungera som ett komplett system.

Viktiga uppgifter
* Bearbetar instruktioner
* Tar beslut i programmet
* Flyttar data mellan olika delar av system

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/0ded7788-59d8-4cff-979a-974a0846a865" />

## Var används mikroprocessor?
* Datorer
* Smartphones
* Surfplattor
* Laptops
* Spelkonsoler
* Smarta TV-apparater

## De två basfunktioner i Arduino
- I Arduino-programmering finns två funktioner som alltid måste finnas med. Dessa kallas ofta för " de två basfunktionerna" eftersom de är grunden i varje Arduino-sketch

### 1.) setup()

<img width="335" height="77" alt="Screenshot 2025-11-26 at 11 11 06" src="https://github.com/user-attachments/assets/c78cb321-c0dd-41e4-91f6-cd7e744abbd4" />


#### Vad den gör:
* Förbereder allt innan programmet börjar köra
* Sätter upp portar
* Starta serieloggen
* Initierar sensorer, nätverk eller annan hårdvara

Körs endast en gång vid start eller reset.

### 2.) loop()

<img width="435" height="72" alt="Screenshot 2025-11-26 at 11 11 19" src="https://github.com/user-attachments/assets/f906cc95-a509-4695-9b06-c024cc521d8b" />

#### Vad den gör:
* Innehåller det som ska ske kontinuerligt
* Upprepar programlogiken
* Läser sensorer
* Anropar funktioner som ska köras flera gånger

Körs oändligt många gånger, så länge mikrokontrollern är på.
