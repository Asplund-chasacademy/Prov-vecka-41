# Prov-vecka-41
Detta repo är till provet vecka 41

Här nedan ska jag ge instruktioner för hur man öppnar och navigerar på webbplatsen.

1. Klicka på länken till mitt github repo. Se till att du har laddat ner github desktop och visual studio code.
2. klicka på den gröna knappen som det står "<> code" på
3. Klicka på open with GitHub Desktop 
5. Då borde github desktop öppnas automatiskt. klicka sedan på open with visual studio code 
6. Nu är du inne i Visual studio code och min kod. I den vänstra spalten klicka på de fyra kuberna ( den femte ikonen uppefrån och ner.)
7. Då söker du i det lilla sökfältet uppe i vänstra hörnet som det står search extensions i och söker på live server. klicka sedan på install. 
8. Nu klickar du på de 2 pappersarken, den ikonen som är högst upp i vänstra hörnet.
9. Nu högerklickar du där det står index.html i den vänstra spalten, och väljer open with live server.
10. Nu kan du se min hemsida som jag har skapat. du kan även klicka dig vidare till nästa sida genom att klicka på "om mig".


Här kommer en kortfattad teknisk beskrivning på hur jag uppfyllde kraven.

HTML-
semantiska HTML-element: 
Jag har använt semantiska HTML-element som <header>, <nav>, <main>, <section>, <article>, och <footer> för att strukturera innehållet.
Hemsida och undersida:
Jag har inkluderat både en huvudsida (index.html) och en undersida (ommig.html).
Navigationsmenyn: 
Navigationsmenyn är konsekvent mellan sidorna och ligger inuti ett <nav>-element.

CSS-
Responsiv design:
Jag har implementerat responsiv design med hjälp av Flexbox för navigationsmenyn och Grid för huvudinnehållet i <main>. Textstorlekar och padding är dynamiska och använder Clamp.
Media queries: 
Jag har använt media queries för att anpassa layouten för olika skärmstorlekar, inklusive mobiler, surfplattor och desktops.
God praxis för CSS: 
CSS-koden är organiserad med tydliga namn och användning av variabler för färger och flexibla enheter (t.ex. rem, vw).

Responsiv design-
Mobiler, surfplattor och datorer:
Layouten är fullt responsiv med hjälp av Flexbox och Grid. Bilder och texter skalas korrekt med Clamp, och media queries används för att justera layouten för olika enheter.

Tillgänglighet-
Alt-attribut: Jag har lagt till alt-attribut på alla bilder för att säkerställa att de är tillgängliga för skärmläsare.
Rubrikstruktur: 
Rubrikstrukturen följer god praxis med användning av h1, h2, och h3 för att säkerställa korrekt semantik.
Färgkontrast: 
Färgkontrast mellan text och bakgrund har testats för att uppnå tillräcklig läsbarhet.
Beskrivande länkar: 
Alla länkar har tydliga aria-labels och beskrivningar för bättre tillgänglighet.

webbläsarverktyg-
Debugga HTML- och CSS-problem: Jag har använt Chrome DevTools för att inspektera och åtgärda HTML- och CSS-problem under utvecklingen.
Responsivitetstest: Genom DevTools har jag testat responsiviteten för olika enheter (mobil, surfplatta, dator).
Lighthouse: Jag har använt Lighthouse för att kontrollera tillgänglighetsaspekter och förbättrat där det behövts, som att se till att rubrikstruktur, kontrast, och tillgänglighet följs.
