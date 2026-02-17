# Instrukce pro tvorbu webu

**Situace**
Jsi zkušená e-shopařka a markeťačka, která nabízí individuální 1:1 mentoring pro majitele e-shopů a rostoucích firem, kteří chtějí mít ve svém podnikání přehled, strukturu a jasná rozhodnutí. Tvým úkolem je vytvořit kompletní malý web podle specifikací níže.

**Cíl**
Dodej uživateli kompletní, profesionální mobile-first webovou stránku, která je vizuálně atraktivní, funkční na všech zařízeních a připravená k okamžitému použití.

**Úkol**
Vytvoř funkční web, který bude obsahovat:
•	Strukturovaný komentovaný HTML5 kód s validní sémantikou
•	Responzivní design (mobile-first přístup)
•	CSS styly pro přizpůsobení všem obrazovkám (4K monitory, desktop, tablet, mobil)
•	Používej moderní CSS vlastnosti (CSS variables, transitions, animations)
•	CSS jednotky velikosti: pro běžný text použij rem, pro nadpisy použij clamp 
•	Základní JavaScript pro interaktivitu (na jemné oživení stránek)
•	Dbej na bezpečnost webu (CSP hlavička a nastavení bezpečnostní HTTP hlavičky, u kontaktního formuláře řeš ochranu proti spamu pomocí honeypot)
•	Nedávej do soubor .htaccess pokyny k přesměrování (to se řeší na úrovni hostingu)

**Znalosti**
•	Zajisti rychlé načítání a optimalizovaný výkon
•	Dodržuj best practices pro přístupnost (barevný kontrast, velikost písma, ARIA)
•	Vlož favicon ve formát svg (pokud ho nemáš dodaný, vytvoř ho)
•	Pokud je potřeba Cookie lišta, vytvoř ji v barvách webu


**Základní SEO**
•	Strukturuj nadpisy H1-H6
•	Přidej meta title a description na každé stránce
•	Vytvoř strukturovaná data – LocalBusiness, FAQ, Article (pokud je to relevantní)
•	Přidej do adresáře soubory sitemap.xml, robot.txt a llms.txt
•	Urči kanonickou url
•	Obrázkům dej alt popisky
•	Propoj stránky vnitřními odkazy
•	Vytvoř Open Graph meta tagy (náhled webu pro Facebook a další sociální sítě)


**Optimalizace obrázků**
•	Přidej lazy loading ke všem obrázkům, které nejsou vidět hned při načtení stránky (below the fold). Tj. u hero sekce lazy loading nedělej.
•	Obrázky ti dodám zkomprimované ve formátu jpg nebo png, ale kdyby se ti zdály velké, řekni si o formát avif.
**Vizuální hierarchie a čitelnost**
•	Jasná typografická hierarchie (nadpisy H1-H6, konzistentní velikosti)
•	Dostatečný kontrast mezi textem a pozadím (minimum 4.5:1 pro běžný text)
•	Čitelné fonty s českou diakritikou
•	Správné řádkování (line-height 1.5-1.8 pro odstavce)
•	Nikdy nezarovnávej text do bloku
•	Optimální šířka řádku pro text (max 70% obrazovky)

**Layout**
•	Šířku celého webu dej na 85% obrazovky
•	Jasné oddělení sekcí a obsahových celků
•	Vyvážené použití bílého prostoru (white space)
•	Intuitivní navigace - logo vlevo, hamburger menu na mobilu pravo
•	Dej si záležet na patičce webu
•	Jednopísmenové znaky (spojky, předložky) zalamuj na nový řádek
•	Jednotky (Kč, m, kg, Eur, atd.) spoj s číslem nedělitelnou mezerou
•	Datum piš ve formátu 1. 1. 2026 a mezery dej nedělitelné

**Obsah**
•	Stručné a srozumitelné texty
•	Výrazné nadpisy s klíčovými informacemi a CTA tlačítka
•	Vizuální prvky podporující obsah (ikony, obrázky, grafika)
•	Logické uspořádání informací (nejdůležitější nahoře)
•	Chybová stránka (místo „404“ dej ikonu <i class="bi bi-emoji-frown"></i> a přidej ji na web pomocí příkazu v souboru .htaccess: ErrorDocument 404 /404.html)
•	Kontrola povinných údajů na webu: jméno, sídlo, IČ, zápis v rejstříku

**Konzistence**
•	Jednotný styl tlačítek, karet a komponent
•	Stejný padding/margin napříč podobnými elementy
•	Stejné zaoblení prvků
•	Konzistentní ikonografie
•	Stíny karet pouze velmi jemné
•	Jednotný projev značky (brand voice)
•	Konzistentní použití barev napříč celým webem
•	Jednotný spacing a odsazení (používej jednotný systém, např. 8px grid)

**Barevná paleta**
•	Omezený počet barev (2-3 hlavní + neutrální)
•	Primární barva pro CTA (call-to-action) tlačítka
•	Neutrální jemné barvy pro pozadí 
•	Pro text #333333
•	Brand barvy (HEX): 
   - primární: světlá
   - sekundární: tmavší
   - tlačítka: kontrastní
   - pozadí: [DOPLŇ]
   - text: [#333333]

**Fonty**
•	Zvol vhodný patkový nebo bezpatkový font podle obsahu webu
•	Pokud není jasné, zvol moderní sans-serif font (př. Outfit)

**Struktura**
•	Jednostránkový web
Položky menu – DOMŮ, CO DĚLÁM, JAK SPOLUPRÁCE PROBÍHÁ, O MNĚ, KONTAKT

**Další prvky na webu**
Vlož Google kalendář, zde je kód:
<!-- Google Calendar Appointment Scheduling begin -->
<iframe src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ1yfdOyyERvNGizfJIX4gOxpUpjrtEbxdlKf52UmiGbwdKM-B-WcPuXrV6vo0TbmUd8SiSxOvHD?gv=true" style="border: 0" width="100%" height="600" frameborder="0"></iframe>
<!-- end Google Calendar Appointment Scheduling -->

**Design**
Vytvoř moderní mobile-first web: použít můžeš trendy jako bento grid layout se zaoblenými rohy, velká typografie, barevné gradienty, glass efekt, micro-animace na hover a scroll efekty či 3D prvky.
**Moderní design**
•	Layout: Bento grid nebo asymetrické rozvržení s velkým bílým prostorem                               
•	Typografie: Velké nadpisy na hero sekci
•	Barvy: Jemné gradienty, plynulé přechody
•	Prvky: Zaoblené rohy (border-radius 16-24px), jemné stíny, 3D prvky
•	Glass efekt: Skleněný efekt v pozadí karet (glassmorphism)
•	Animace: Mikro interakce na hover, jemné scroll animace 
**obrázky**
Na webu použij fotky (př. přílohy), které najdeš ve složce 
Obrazky/hlavni – pro Hlavní stranu (hero sekce atd.)
Obrazky – ostatní obrázky rozlož do webu. Použij maximálně tři, které se ti budou graficky hodit. 

**texty**
Na webu použij tyto texty pro jednotlivé sekce / stránky. Drž se jich doslova a nic neměň ani nepřidávej. 
*Hero sekce*
Řiďte firmu systematicky.
Systematický růst založený na datech, odpovědnosti a jasné struktuře.
Individuální 1:1 mentoring pro majitele e-shopů a rostoucích firem, kteří chtějí mít ve svém podnikání přehled, strukturu a jasná rozhodnutí.

REALITA PODNIKÁNÍ
Firma roste.
Obrat stoupá.
S růstem přichází větší komplexita.
•	závislost firmy na majiteli
•	neformální procesy
•	nejasné odpovědnosti
•	omezený finanční přehled
•	operativní řízení místo strategického
To je běžná fáze vývoje firmy.

CO DĚLÁM
Pracuji individuálně s majiteli e-shopů a menších firem, kteří chtějí:
•	nastavit provozní procesy
•	získat finanční přehled a kontrolu cashflow
•	vyjasnit odpovědnosti ve firmě
•	zavést funkční delegování
•	připravit firmu na další růst
•	nastavit účetní, výrobní a skladové systémy včetně ERP řešení
Nepracuji s teorií.
Vycházím z dlouholeté praxe v oblasti e-commerce, marketingu a provozního řízení.

JAK SPOLUPRÁCE PROBÍHÁ
Spolupráce je individuální a dlouhodobá.
Začínáme analýzou současného stavu firmy a definováním priorit.
Na základě toho nastavíme konkrétní kroky a systém práce.
Pravidelně pracujeme na:
•	stabilizaci provozu
•	zavádění systémů
•	práci s čísly
•	přípravě na růst
Cílem není krátkodobá změna.
Cílem je struktura, která bude fungovat dlouhodobě.
Spolupráce je vždy nastavena individuálně podle situace firmy.
Rozsah i cenové podmínky řešíme otevřeně po vstupním rozhovoru.

CTA tlačítko: Domluvit vstupní rozhovor
Spolupráce začíná nezávazným vstupním rozhovorem, během kterého posoudíme vzájemnou kompatibilitu.

S kým pracuji
Spolupracuji především s majiteli e-shopů a menších firem, které:
•	již mají stabilní obrat
•	chtějí firmu řídit systematicky
•	jsou připraveny upravit způsob řízení
•	hledají dlouhodobého partnera, nikoliv jednorázovou radu
Spolupracuji s omezeným počtem firem současně, abych každé z nich mohla věnovat plnou pozornost.

O mně
Podnikání vnímám jako systém, který musí fungovat dlouhodobě.
Mám více než 30 let zkušeností v oblasti administrativy a provozního řízení.
Dlouhodobě se věnuji e-commerce, marketingu a nastavování procesů ve firmách.
Stála jsem u vzniku i růstu několika e-shopů a podílela se na zavádění účetních, skladových a výrobních systémů včetně ERP řešení.
Pracuji s realitou každodenního provozu – s čísly, odpovědnostmi, procesy i technologiemi.
Mentoring pro mě není teorie, ale praktická práce se strukturou firmy.

ZÁVĚR 
Spolupracuji s omezeným počtem klientů.
Výběr probíhá na základě vstupního rozhovoru.
CTA tlačítko: Domluvit vstupní rozhovor – po kliknutí se posuň na kalendář Google
Spolupráce začíná nezávazným vstupním rozhovorem, během kterého posoudíme vzájemnou kompatibilitu.
Kód pro vložení kalendáře: 
<!-- Google Calendar Appointment Scheduling begin -->
<iframe src="https://calendar.google.com/calendar/appointments/schedules/AcZssZ1yfdOyyERvNGizfJIX4gOxpUpjrtEbxdlKf52UmiGbwdKM-B-WcPuXrV6vo0TbmUd8SiSxOvHD?gv=true" style="border: 0" width="100%" height="600" frameborder="0"></iframe>
<!-- end Google Calendar Appointment Scheduling -->

KONTAKT
Ing. Veronika Příplatová 
tel. +420 737 859 995
e-mail: veronika@exteras.cz

IČ 74363689
