---
Title: Load
Template: analysis
---

# Rapport på tre webbsidor där laddtid kontrolleras.
---
# Inledning

Den här uppgiften och analysen handlar om att välja tre hemsidor där vi ska analysera och mäta laddningstiden.

---

# Urval

Jag har valt följande webbplatser för analys:

[Swedbank](https://www.swedbank.se/)

[Nordea](https://www.nordea.se/)

[SEB](https://seb.se/)

I denna urval har jag fokuserat på kriterier som betonar de kritiska samhällspåverkningarna av dessa webbplatser. Dessutom strävade jag efter att välja webbplatser med likheter i deras funktioner eller syften.

---

# Metod

Jag kommer använda Google Pagespeed-verktyget för att mäta laddningstiderna för varje webbplats. För analysen har jag valt tre specifika hemsidor. Resultaten kommer att sammanställas i en tabell i den kommande rapporten. Dessutom kommer jag att använda webbläsarens utvecklarverktyg för att mäta nätverksladdningstider samt antalet och storleken på resurser.

---

# Resultat

## Detta är resultaten från de alla sidorna:

<div class="centered">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTLNOilnva4qVWTccYJ8h3zNvrjASnR637RdEXMr3jb85xz0PjPFoq6psYDH7h6dGBkpU9KNjTYdQbm/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" 
            width="614" 
            height="150" 
            title="Results"></iframe>
</div>

<div class="image-container">
<img class="dp-image" src="%base_url%/assets/img/swedbank.png" width="800" height="800" alt="Swedbanks hemsida">
</div>
Swedbank är en svensk bank som erbjuder ett brett spektrum av finansiella tjänster, inklusive sparande, lån, företagsfinansiering och investeringsprodukter.
Banken är en viktig aktör på den svenska marknaden och har även närvaro i andra baltiska länder.

<div class="image-container">
<img class="dp-image" src="%base_url%/assets/img/nordea.png" width="800" height="800" alt="Nordeas hemsida">
</div>
Nordea är en nordisk finanskoncern med verksamhet i Norden och Östersjöregionen. Den erbjuder banktjänster, investeringar, försäkringar och pensionstjänster.
Nordea är en av de största bankerna i Norden och har en betydande närvaro internationellt

<div class="image-container">
<img class="dp-image" src="%base_url%/assets/img/seb.png" width="800" height="800" alt="SEBs hemsida">
</div>
SEB är en svensk bank och finansiell koncern som erbjuder ett brett utbud av bank- och finanstjänster för privatpersoner, företag och institutioner.
Banken har en stark närvaro i Norden och Baltikum och fokuserar på affärsområden som företagsbank, investment banking och privatbanktjänster.

---

# Analys

Orsaken till att mobilversionerna av webbplatser ibland är långsammare än deras desktop-versioner kan bero på att dessa webbplatser ursprungligen inte konstruerades med mobila enheter som förstahandsmål, utan snarare designades för dator i åtanke. Därefter har de anpassats för att fungera på mobila enheter. Detta utgör ofta en utmaning, särskilt för äldre webbplatser.

Det är intressant att notera att en analys på Google PageSpeed Insights visar att SEB har den högsta poängen, följt av Nordea och sist Swedbank. Den övergripande trenden förefaller bekräftas av laddningstiden, där SEB presterar bäst och Swedbank ligger sist.

Denna information antyder att SEB har lyckats optimera sin webbplats för bättre prestanda enligt Google PageSpeed Insights-kriterierna. Det är möjligt att SEB har investerat i effektiva webbutvecklingsmetoder och teknologier för att förbättra användarupplevelsen och minska laddningstiderna på deras webbplats.

Å andra sidan indikerar placeringen av Swedbank som den långsammaste i analysen att det kan finnas utrymme för förbättring när det gäller webbplatsens prestanda och optimering.

Det är viktigt att notera att PageSpeed Insights-poängen och laddningstiderna kan påverkas av olika faktorer, inklusive webbplatsens design, serverkapacitet och nätverksförhållanden. Det kan vara användbart att utforska ytterligare för att förstå vilka specifika aspekter av webbplatserna som bidrar till dessa skillnader.

Snabb laddningstid och hög prestanda för nätbanker är avgörande för att förbättra användarupplevelsen, öka tillgängligheten, främja konverteringar och engagemang, bygga förtroende och säkerhet samt förbättra sökmotorrankningen. Det är en strategisk investering för att säkerställa smidiga och effektiva finansiella transaktioner och öka kundnöjdheten.

När man kollar på vilken sida som var bäst, av de analyserade webbplaterserna ser vi att SEB tar vinsten. Det kan vara för att SEB använder mer modern bildkomprimering och så kallade lazy load tekniker för att bilder ska laddas snabbare. Även deras Javascript och CSS kombineras och förminskas för att minska antalet HTTP-förfrågningar. Detta hjälper att dra ner laddningstiderna. Samt en effektiv cachehantering som gör att resurser laddas snabbare när man besöker sidan om igen. Detta är verktyg som alla sidor kan ta med sig för att minska laddningstiderna för sidorna och leverera innehållet snabbare.

Rangordningen för dessa banker baserat på resultatet visar att SEB hade snabbast laddningstid, med även minst resurser samt låg storlek. Därefter kommer Nordea som likt SEB har låga resurser och storlek. Sist har vi Swedbank som har nästan halva av poängen för mobil och dator och dubblet så lång loadtime jämfört med de andra.

Det är viktigt att laddningstiderna för onlinebanker optimeras då det förbättrar användarupplevelsen. Det bygger förtroende om att banken jobbar för användarnas användarupplevelse samt visar engagemang. Detta är en strategisk investering utformad för att säkerställa smidiga och effektiva finansiella transaktioner och förbättra kundnöjdheten.

---

# Referenser

I have used the Google pagespeed tool, and Devtools in my browser

---

# Övrigt

Skriven av Noah Hjelm

---
