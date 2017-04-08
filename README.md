# DATA STÁTNÍ SPRÁVY

Všechna existující data, co nejsou striktně tajná či důvěrná, by měl stát publikovat tak, aby se k nim dalo přistupovat s co nejmenším úsilím.

## Open Data

Dnešní stav je tristní - člověk co chce s daty státu pracovat si musí postahovat spousty CSV souborů a dávat dohromady svojí vlastní infrastrukturu. Spousta dat je nadále přístupná jen jako PDF (jako příklad použiju [Přehled cenových map](http://www.mfcr.cz/cs/verejny-sektor/ocenovani-majetku/prehled-cenovych-map)). V některých případech nás od dat dělí “aplikace” [co vrací odpovědi do tabulek na webu](http://cedr.mfcr.cz/Cedr3InternetV419/CommonPages/ConditionPage.aspx?queryType=0) nebo máme k dispozici ke stažení spousty dat jejich [surových kopií](http://data.mfcr.cz/cs/dataset/dotace-cedr-iii) ve kterých najdeme miliony odkazů zpět na web - bez šance cokoliv smysluplného provést. 

Jako příklad správně provedené publikace dat může sloužit město New York, které ukládá data do cloudu, konkrétně do služby [Google BigQuery](https://cloud.google.com/bigquery/), která komukoliv umožňuje rovnou se dat dotazovat a získávat tak odpovědi na analytické otázky. Příklad: [Daňová mapa města New York](http://maps.nyc.gov/taxmap/) + jejich [publikace dat v Cloudu](https://cloud.google.com/blog/big-data/2017/01/new-york-city-public-datasets-now-available-on-google-bigquery) a [praktický postup](http://timingblog.brooklynmarathon.com/2014/04/steps-to-load-new-york-city-property.html). 

Data která dnes stát publikuje, by měl přiblížit konzumentům.

## Skoro Open Data

MF ČR provozuje [spoustu systémů](http://www.mfcr.cz/cs/o-ministerstvu/informacni-systemy) z nichž některé umožňují dotázat se na libovolné informace (například [plátci spotřební a ekologické daně](https://www.celnisprava.cz/cz/aplikace/Stranky/SpdInternet.aspx?act=findspd) nebo [registr plátců DPH](http://adisreg.mfcr.cz/cgi-bin/adis/idph/int_dp_prij.cgi?ZPRAC=FDPHI1&poc_dic=2)) nicméně neumožňují jednoduše získat odpovědi na analytické otázky typu “kolik subjektů se loni stalo plátci daně z piva”. Jako nejbouřlivější příklad dat co jsou de-facto veřejná, ale stát občanům uzurpuje strojový přítup, může sloužit ARES katalog, který má API, jenž provozovatel nesmyslně blokuje a limituje.

Data ke kterým se lze veřejně dostat složitou cestu, by měl stát aktivně publikovat!

## Praktické použití

Pro propagaci datové otevřenosti skvěle poslouží hackathony. 

> doplnit k info hackathonum 
> a rozvést myšlenku jak stát sám bude profitovat v denní operativě, pokud se takhle začne chovat

## Podaná ruka

V případě zájmu rádi pomůžeme připravit a neziskově provozovat analytický datawarehouse, skrz který bude každý novinář, student, data science člověk či zaměstnanec státu schopný snadno získávat odpovědi na analytické otázky. **Mimo jiné to přinese obrovké snížení žádostí na informace dle zákona o svobodném přístupu k informacím (106/1999 sb)**.

## Neveřejná data

Stát drží spoustu informací popisujících naší společnost. Spousta dat má charakter osobních údajů a důvěrných informací, nicméně při vhodné anonymizaci či zašifrování dokáží pomoci lidem v běžném rozhodování. Existují technologie jako je homomorfní šifrování, dnes perfektně adoptované například Českou Spořitelnou, které umožňují analyzování a práci s citlivými informacemi, aniž autor algoritmu získá přímo přístup k obsahu zkoumaných dat. Jsme přesvědčeni, že lze vystavět spolehlivé prostředí, ve kterém by data science lidi dokázali pracovat nad důvěrnými daty a tím pomoci státu v efektivnějším chování. 

Například data kontrolního hlášení DPH jsou skvělé datasety pro grafové databáze (po anonymizaci IČ a zaokrouhlení částek na celé tisícikoruny téměř klasifikovatená jako Open Data), popisující přelévání peněz v naší ekonomice. Obdobně mohou fungovat data z EET. 

## Další krok

Vhodné bankovní prostředí (tč. Česká spořitelna) dokáže zajistit prodmínky na otestování práce s šifrovanými daty.

> doplnit konkrétnější představy 

# MISC

## IT principy

Vývoj IT systémů probíhá vždy jako Open Source projekt. Stát neplatí žádné licenční poplatky, pouze náklady na údržbu a provoz služeb; vždy jde transparentně zhodnotit co je "správná cena" - dílo může kdokoliv nový převzít a provozovat! Dodavatel publikuje zdrojové kódy do veřejného repozitáře, ve kterém kdokoliv může zkontrolovat, jak je daný systém naprogramovaný. 

Státní správa tím získá stabilní zdroj talentů, kteří budou soutěžit IT zakázky. Jsme stát plný startupů s ohromnou penetrací technicky vzdělaných lidí. Využijme to! Otevřené zdrojové kódy neznamenají žádné riziko - transparentnost naopak vede k vysoké míře bezpečnosti, protože kdokoliv může upozornit na problémy. 

> doplnit témata 
> - Docker
> - API
> - CI
> - GitHub
> - MIT 

## Platby

Stát by měl emitovat vlastní krypto měnu (ala bitcoin), která v sobě může mít rovnou naprogramované daně. Česká Spořitelna znovu může posloužit jako příklad banky, schopné připravit infrastrukturu pro pilotní projekt. Základní výhody kryproměny jsou ve sledovatelnosti peněz a v algoritmizovatelnosti jejich funkčních principů (zaplacením se ihned odvede DPH, apod.). Pokud jde dokonale sledovat pohyb peněz, přestane dávat smysl krást a páchat trestnou činnost.

## Interface Stát <> Občané

> doplnit
> - stát je milý a hejčká nás (hlídá za nás naše problémy a mile se k nám chová )
> - stát se jako e-commerce subjekt snaží o konverze - má analytiky co sledují chování lidí na webu a intenzivně řeší aby se jim web dobře používal (online podání daňového přiznání je UX peklo)
> - co se má stát, abysme měli stát rádi a platili mu rádi daně? transparentní hospodaření s efektem jako přímé daně v UK?

# Epilog

Tohle je začátek manifestu IP ekomoniky pro ČR. Samozřejmě, že se bude nějak rozvíjet, ale takto to vidíme a rádi to vysvětlíme komukoliv, kdo se chce zasadit o otevřenou společnost bez korupce… https://github.com/CzechRepublic

Připomínky uvítáme v Issues zde na GitHubu [https://github.com/CzechRepublic/nase-strategie/issues/new](https://github.com/CzechRepublic/nase-strategie/issues/new) nebo v případě neveřejného kontaktování na [czechia@keboola.com](mailto:czechia@keboola.com).

