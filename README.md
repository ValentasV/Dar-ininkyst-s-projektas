# DARŽININKO PADĖJĖJAS

## PROJEKTO APRAŠYMAS

Šio projekto tikslas sukurti Web aplikaciją, kuri padėtų daržininkams lengviau prižiūrėti savo augalus ir jais rūpintis. Sekti augalų istoriją, ją lyginti su praėjusių metų rodikliais. Gauti augalų priežiūros ir auginimo priminimus el. paštu.

## DUOMENYS

- Vartotojas
  - Vardas
  - Pavardė
  - Telefono numeris
  - El. paštas
  - Miestas (miestelis, kaimas)	

- Sėklų sėjimas
  - Kategorija (daržovių sėklos, gėlių sėklos)
  - Pavadinimas (agurkai, pomidorai)
  - Veislė (paprastieji trumpavaisiai agurkai Mirabelle H...) 
  - Sėklų kiekis
  - Sėjimo data
  - Vazonų – daigyklų informacija (talpa, dydis)
  - Žemių rūšis (durpės, juodžemis)
  - Sėjimo vieta (šiltnamis, patalpa, lysvė, laukas)
  - Daigų sodinimas (susieta su APPSU Daigų sodinimas)
  - Augalų priežiūra (susieta su APPSU Augalų priežiūra)
  - Pastabos

- Daigų sodinimas
  - Sėklų sėjimas (susieta su APPSU Sėklų sėjimas)
  - Daigų kiekis
  - Daigų sodinimo data
  - Pikiavimo data
  - Persodinimo vieta (šiltnamis, patalpa, lysvė, laukas)
  - Augalo užsodinimo plotas (arais)
  - Augalų priežiūra (susieta su APPSU Augalų priežiūra)

- Augalų priežiūra
  - Sėklų sėjimas (susieta su APPSU Sėklų sėjimas)
  - Daigų sodinimas (susieta su APPSU Daigų sodinimas)
  - Augalų priežiūros data
  - Trąšos
  - Pesticidai
  - Trašų – pesticidų kiekis
  - Ravėjimas
  - Laistymo būdas (kapiliarinis laistymas, laistymas purkštuvu...)
  - Vandens kiekis reikalingas augalams (litrais)
  - Dangos ir plėvelės tiesimas uždengimas (agrodanga, agroplėvelė)
  - Augalų Ligos
  - Sodo – daržo Įrankiai, technika (kastuvas, kultivatorius)
  - Pastabos

- Derliaus nuėmimas
  - Sėklų sėjimas (susieta su APPSU Sėklos)
  - Daigų sodinimas (susieta su APPSU Daigai)
  - Derliaus nuėmimo data
  - Augalų priežiūra (susieta su APPSU Augalų priežiūra)
  - Derliaus kiekis
  - Derliaus sandėliavimo vieta
  - Derliaus laikymo laikotarpis (nuo – iki)

- Augalų auginimo priminimai
  - Sėklų sėjimas (susieta su APPSU Sėklos)
  - Daigų sodinimas (susieta su APPSU Daigai)
  - Augalų priežiūra (susieta su APPSU Augalų priežiūra)
  - Priminimo data nuo kada
  - Priminimo data iki kada

## Procesai

- Sėklų arba daigų pridėjimas
  - Vartotojas paspaudžia  “Pridėti naujas sėklas arba pridėti naujus daigus“
  - Vartotojas užpildo sėklų arba daigų įvedimo laukelius
  - Vartotojas paspaudžia mygtuką “Įvesti sėklas“ arba “Įvesti daigus“, įvesti pasirinkimai išsisaugo
  - Vartotojas gali paspausti mygtuką “Peržiūrėti sėklas“ ar “Peržiūrėti daigus“

- Augalų priežiūros ir derliaus nuėmimo pasirinkčių pildymas ir pridėjimas
  - Vartotojas, taip pat gali pasirinkti ir pildyti “augalų priežiūros ir derliaus nuėmimo “ skiltis vadovaudamasis sėklų ir daigų pavyzdžiu.
  - Vartotojas į šiuos laukelius gali pridėti informaciją, ją peržiūrėti.

- Vartotojas gali peržiūrėti ir redaguoti savo pridėtas sėklas, daigus, augalų priežiūros ar derliaus nuėmimo informaciją
  - Vartotojas paspaudžia mygtuką “mano sėklos“,  “mano daigai“, “mano augalų priežiūra“ arba mygtuką “mano derlius“
  - Vartotojui parodoma visa įkeltų sėklų, daigų, augalų priežiūros ir derliaus nuėmimo informacija
  - Toliau vartotojui yra suteikiama teisė šiuos duomenis redaguoti. Kiekviename iš šių katalogų yra mygtukas “redaguoti“, kuris suteikia galimybę ten esančia informaciją pakeisti.
  - Paspaudus mygtuką “redaguoti“ atsidaro langas, su jau įvestais iš ankščiau duomenimis, kuriuos šiame lange galima keisti.
  - Užtvirtinti pakeistus duomenis reikia su mygtuku “saugoti“

- Įvestos informacijos paieška
  - Pagrindiniame meniu puslapyje rodomi sėklų, daigų, augalų priežiūros priemonių ir derliaus nuėmimo sąrašai.
  - Šiuos sąrašus galima filtruoti pagal daugelį parinkčių pvz: kategorija, veislė, trąšos, augalų ligos... ir t.t.
  - Taip pat, galima vykdyti paieška pagal raktinius žodžius

- Vartotojo pasirinktų rodiklių priminimai
  - Vartotojas savo profilyje pasirenka vieną ar kelis kriterijus pagal kuriuos bus el. paštu siunčiami priminimai.
  - Toliau turės pažymėti laiko tarpsnį, kada jam bus siunčiamas vienas ar kitas priminimas (nuo – iki)  
  - Patvirtinti savo pasirinktus kriterijus ir laiko tarpsnį

## Vartotojo ir svetainės administratoriaus funkcijos

1. Vartotojas gali matyti ir redaguoti savo paskyros duomenis. Vartotojui, taip pat suteikiama teisė savo paskyroje įkelti, koreguoti, ar kitaip tvarkyti sėklų, daigų, augalų priežiūros ir derliaus nuėmimo laukus.
2. Svetainės administratorius gali matyti vartotojo duomenis. Gali trinti sėklų, daigų, augalų priežiūros ar derliaus nuėmimo laukus. Gali keisti svetainės nustatymus. Gali ištrinti naudotojų paskyras.

## Dizainas

Svetainės dizainas funkcionalus, patogus vartotojui. 
