# Privacyverklaring — AutoPot

**Laatst bijgewerkt:** 8 oktober 2026
**Versie:** 1.1

Deze privacyverklaring legt uit welke persoonsgegevens de app **AutoPot** verwerkt,
waarom, op welke juridische grondslag, met wie ze worden gedeeld, hoe lang ze worden
bewaard en welke rechten je hebt. AutoPot is een app waarmee een vaste groep mensen
de kosten van één of meer gedeelde auto's eerlijk verdeelt (ritten, tankbeurten en
uitgaven).

We verwerken zo min mogelijk gegevens, gebruiken **geen** tracking, **geen** advertenties
en **geen** analytics, en verkopen je gegevens **nooit**.

---

## 1. Wie is verantwoordelijk?

De verwerkingsverantwoordelijke voor je gegevens is:

- **Ditmar Zuiderwijk** (natuurlijk persoon), Nederland
- **E-mail:** ditmar.hhs@gmail.com

Voor alle vragen over deze verklaring of over je gegevens kun je dit e-mailadres gebruiken.

---

## 2. Welke gegevens we verwerken

We verwerken uitsluitend de gegevens die nodig zijn om de app te laten werken. We vragen
**geen** telefoonnummer, **geen** geboortedatum, **geen** betaalgegevens en **geen**
foto's of contacten.

### a. Accountgegevens
- **E-mailadres** — om in te loggen en je account te identificeren.
- **Wachtwoord** — versleuteld/gehasht opgeslagen door onze backendleverancier; wij
  kunnen je wachtwoord niet inzien.
- **Gebruikers-ID** — een willekeurige unieke code (UUID) die je account intern aanduidt.

### b. Profiel- en groepsgegevens
- **Weergavenaam** — de naam die andere leden van jouw auto-groep zien.
- **Rol** — of je in een groep beheerder of lid bent.
- **Auto-/groepsnaam** en groepsinstellingen (zoals de standaard kilometertoeslag).
- **Lidmaatschap-periodes** — wanneer je in een groep actief was of tijdelijk afwezig,
  en toetredings-/vertrekverzoeken.

### c. Door jou ingevoerde inhoud
- **Ritten** — datum, kilometerstanden (begin/eind), een optionele omschrijving en wie
  de rit reed.
- **Tankbeurten / rittenlijsten** — datum, bedrag, getankte liters en wie betaalde.
- **Uitgaven** — datum, omschrijving, bedrag, wie betaalde en wie meedeelt.
- **Agenda-claims** — wanneer je de auto reserveert (datum/dagdeel en een optionele titel).

### d. Locatiegegevens (optioneel, alleen met jouw keuze)
- Bij het vastleggen van een rit kun je er zélf voor kiezen om je **huidige locatie** als
  auto-locatie toe te voegen. Doe je dat, dan slaan we de **coördinaten (breedte-/
  lengtegraad)** en een **leesbaar adres** op bij die rit, zodat de groep weet waar de
  auto staat.
- Dit gebeurt **alleen** als je daar op dat moment voor kiest; je kunt de locatie ook
  handmatig overslaan. Er is **geen** locatietracking op de achtergrond.
- Zie verder hoofdstuk 4.

### e. Gegevens op je toestel (niet op onze servers)
- Je **inlog-sessie (token)** wordt veilig op je toestel bewaard (iOS Keychain).
- Je **voorkeuren** voor meldingen en voor het automatisch vastleggen van locatie worden
  lokaal op je toestel bewaard.

### Wat we NIET verzamelen
- Geen advertentie-identifiers (IDFA), geen tracking over apps of websites heen.
- Geen analytics-/statistiek-SDK's, geen crash-reporting van derden.
- Geen camera, microfoon, contacten, agenda van je telefoon, gezondheid of foto's.

---

## 3. Doeleinden en juridische grondslagen (AVG)

| Gegevens | Doel | Grondslag (AVG art. 6) |
|---|---|---|
| Account (e-mail, wachtwoord, gebruikers-ID) | Je account aanmaken, beveiligen en je laten inloggen | Uitvoering van de overeenkomst (art. 6 lid 1 sub b) |
| Profiel, groep, lidmaatschap | De kerndienst leveren: kosten eerlijk verdelen binnen je groep | Uitvoering van de overeenkomst (sub b) |
| Ritten, tankbeurten, uitgaven, agenda | De boekhouding en verdeling van de gedeelde auto bijhouden | Uitvoering van de overeenkomst (sub b) |
| Locatie bij een rit | De laatst bekende plek van de auto delen met je groep | **Toestemming** (sub a) — per keer, intrekbaar |
| Beveiliging en misbruikpreventie | De app en accounts beschermen | Gerechtvaardigd belang (sub f) |
| Pushmeldingen (zodra beschikbaar) | Je op de hoogte houden van acties in je groep | **Toestemming** (sub a) |

Je bent niet verplicht gegevens te verstrekken, maar zonder e-mailadres en weergavenaam
kun je de app niet gebruiken. Locatie en meldingen zijn volledig optioneel.

---

## 4. Locatiegegevens in detail

- AutoPot gebruikt je locatie **alleen op het moment dat je de app gebruikt** en alleen
  nadat je daar toestemming voor hebt gegeven (iOS vraagt dit via de standaard
  toestemmingsvraag "tijdens gebruik van de app").
- De locatie wordt **eenmalig** opgehaald wanneer je bij een rit op "gebruik mijn locatie"
  tikt — er is **geen** continue of achtergrond-tracking.
- We bewaren de coördinaten en het afgeleide adres alleen bij de betreffende rit, zodat
  je groep ziet waar de auto het laatst stond.
- Je kunt je toestemming op elk moment intrekken via **iOS Instellingen → Privacy →
  Locatievoorzieningen → AutoPot**. Reeds vastgelegde locaties verdwijnen daarmee niet
  automatisch; die kun je verwijderen door de betreffende rit aan te passen of te wissen,
  of door contact met ons op te nemen.

---

## 5. Met wie we gegevens delen (verwerkers)

We verkopen of verhuren je gegevens nooit en gebruiken ze niet voor reclame. We schakelen
één externe partij in om de app te laten werken (een "verwerker" die uitsluitend in onze
opdracht handelt):

- **Supabase** — onze backend- en databaseleverancier. Hier worden je account- en
  appgegevens veilig opgeslagen. De gegevens worden gehost in de **Europese Unie**.
  Supabase verwerkt de gegevens uitsluitend voor het leveren van de opslag- en
  inlogfunctionaliteit van de app.

Daarnaast verloopt de distributie en facturering van de app via **Apple** (App Store /
StoreKit). Apple verwerkt eventuele aankoop- en abonnementsgegevens onder haar eigen
privacybeleid; wij ontvangen daarvan geen volledige betaalgegevens.

We kunnen gegevens delen wanneer de wet ons daartoe verplicht (bijvoorbeeld op grond van
een rechtmatig verzoek van een autoriteit).

---

## 6. Doorgifte buiten de Europese Economische Ruimte (EER)

Je app-gegevens worden opgeslagen op servers **binnen de EU**. Er vindt voor de kern van
de app **geen** doorgifte buiten de EER plaats.

Mocht in de toekomst een dienst worden ingezet die gegevens buiten de EER verwerkt
(bijvoorbeeld een pushmeldingen-dienst), dan zorgen we voor passende waarborgen zoals de
**modelcontractbepalingen (Standard Contractual Clauses)** van de Europese Commissie, en
werken we deze verklaring bij.

---

## 7. Hoe lang we gegevens bewaren

- **Accountgegevens en inhoud** bewaren we zolang je account bestaat en je lid bent van
  een groep.
- **Als je je account verwijdert**, verwijderen of anonimiseren we je persoonsgegevens.
  Omdat een gedeelde boekhouding ook voor de andere leden moet blijven kloppen, kunnen
  reeds verwerkte transacties (ritten/uitgaven) **geanonimiseerd** behouden blijven —
  losgekoppeld van je naam en e-mailadres — voor de juistheid van de groepsadministratie.
- **Back-ups** waarin gegevens nog voorkomen worden in de normale back-upcyclus binnen
  uiterlijk **30 dagen** overschreven.
- **Lokale voorkeuren** op je toestel verdwijnen wanneer je de app verwijdert.

---

## 8. Beveiliging

We nemen passende technische en organisatorische maatregelen om je gegevens te beschermen:

- Versleutelde verbindingen (HTTPS/TLS) tussen de app en de server.
- Versleutelde opslag aan de serverkant en gehashte wachtwoorden.
- **Toegangscontrole op rijniveau (Row Level Security):** de database dwingt af dat je
  alleen gegevens van je eigen groep(en) kunt zien — niet die van andere groepen.
- Je inlog-sessie wordt op je toestel bewaard in de beveiligde iOS Keychain.

Geen enkel systeem is 100% veilig; bij een datalek dat een hoog risico oplevert,
informeren we je en de toezichthouder zoals de wet voorschrijft.

---

## 9. Jouw rechten

Op grond van de AVG heb je het recht om:

- **Inzage** te vragen in de gegevens die we van je hebben;
- **Rectificatie** (correctie) van onjuiste gegevens te vragen;
- **Verwijdering** ("recht op vergetelheid") te vragen;
- de **verwerking te beperken**;
- **bezwaar** te maken tegen verwerking op grond van gerechtvaardigd belang;
- je gegevens te ontvangen in een overdraagbaar formaat (**dataportabiliteit**);
- een gegeven **toestemming in te trekken** (bijvoorbeeld voor locatie of meldingen),
  zonder dat dit eerdere verwerking ongedaan maakt.

Je oefent deze rechten uit door je account in de app te beheren of door te mailen naar
**ditmar.hhs@gmail.com**. We reageren binnen de wettelijke termijn (in beginsel binnen
één maand).

Je hebt ook het recht een klacht in te dienen bij de Nederlandse toezichthouder, de
**Autoriteit Persoonsgegevens** (autoriteitpersoonsgegevens.nl).

---

## 10. Je account en gegevens verwijderen

Je kunt je account en de bijbehorende persoonsgegevens verwijderen:

- **In de app**, via Instellingen → (account verwijderen), of
- door een verzoek te sturen naar **ditmar.hhs@gmail.com**.

Wat er bij verwijdering met gedeelde transacties gebeurt, staat in hoofdstuk 7.

---

## 11. Kinderen

AutoPot is bedoeld voor volwassenen die een auto delen en is niet gericht op kinderen.
We verzamelen niet bewust gegevens van personen jonger dan 16 jaar. Denk je dat een kind
ons toch gegevens heeft verstrekt, neem dan contact op zodat we deze kunnen verwijderen.

---

## 12. Geautomatiseerde besluitvorming

We doen **niet** aan geautomatiseerde besluitvorming of profilering met rechtsgevolgen.
De kostenberekeningen in de app zijn eenvoudige, transparante rekenregels en geen
profilering.

---

## 13. Wijzigingen in deze verklaring

We kunnen deze privacyverklaring bijwerken, bijvoorbeeld bij nieuwe functies. De datum
bovenaan geeft de laatste wijziging aan. Bij belangrijke wijzigingen informeren we je in
of via de app.

---

## 14. Contact

Vragen of verzoeken? Mail naar **ditmar.hhs@gmail.com**.
