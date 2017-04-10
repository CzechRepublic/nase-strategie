# Jak vybrat dodavatele "svobodného" software

### co znamená "svobodný"?

"Svobodný" neznamená zadarmo ani amatérsky. Software šířený pod svobodnou licencí dnes pohání nejkritičtější aplikace na trhu. Například sám Oracle, enterprise IT vendor, produkuje velké množství svobodného software ([Oracle & Open Source](http://www.oracle.com/us/technologies/open-source/overview/index.html)). 

### výhody svobodného software pro stát

Poptáte-li dodávku "svobodného" software, přihlásí se vám dodavatelé, kteří vás neplánují vzít na hůl. Uvidíte do zdrojových kódů, získáte vyšší úroveň bezpečnosti, rychlosti a otevřenosti. Mezi vámi a vaším dodavatelem vznikné férové pouto založené na vyrovnaných podmínkách. V případě konfliktu budete schopni na volném trhu snadno najít pomoc - díky otevřenosti nebude problém aby přišel někdo další a navázal na existující dílo. Na zakázce realizované jako "svobodné dílo" se velmi špatně okrádá stát.

## správná architektura - co chceme?

Vždy po dodavateli požadujeme aby:

1. veškeré zdrojové kódy veřejně publikoval pod svobodnou licencí do repozitáře zdrojových kódů 
2. veškeré funkční celky softwarového díla byly pokryty testy
3. vyvíjel software v souladu s principy "Continuous Deliver" 
4. svoje dílo zapouzdřil do Docker kontejneru

### jakou vybrat svobodnou licenci?

V českém právním řádu je autor díla autorem. Svobodný software neznamená odcizení autorství. Pro užití díla je klíčová licence. Licence je kámen úrazu - klíčový dokument. Pokud je špatně nastavená, dostanete se do slepé uličky, jako před lety [ČSA](http://www.ceskatelevize.cz/ct24/ct24/ekonomika/1371604-reporteri-ct-csa-neopravnene-uzivaji-stare-logo) nebo hlavní město Praha a projekt [OpenCard](http://praha.idnes.cz/praha-odmita-platit-stamiliony-za-licence-k-opencard-f94-/praha-zpravy.aspx?c=A140506_144238_praha-zpravy_klu). 

Jedna z nejsvobodnější licenci je [**MIT**](https://cs.wikipedia.org/wiki/Licence_MIT) - umožňuje libovolné modifikace díla a jakékoliv použití, včetně komerčního. MIT licencí nemůžete nic zkazit. Pokud si chcete detailně nastudovat principy svobodných licencí, podívejte se na web Právní Prostor - [Jak vybrat licenci k software – manuál pro právníky](http://www.pravniprostor.cz/clanky/obcanske-pravo/jak-vybrat-licenci-k-software-manual-pro-pravniky) a na web creativecommons.cz na [Vydali jsme praktický manuál pro obce k licencím CC](http://www.creativecommons.cz/vydali-jsme-prakticky-manual-pro-obce-k-licencim-cc/)

Jsme přesvědčeni, že zakázkový software placený z veřejných peněz **má být svobodné dílo!**

### co je repozitář zdrojových kódů

Repozitíř zdrojového kódu je místo, kde jsou uloženy kódy tvořící softwarové dílo. Nejznámější repozitáře jsou [GitHub](https://github.com/) a [BitBucket](https://bitbucket.org/). Veřejně dostupný repozitář umožní komukoliv vidět, jak se softwarové dílo v čase mění. [Zde](https://github.com/datasyscz/KeboolaChatbot/commits/master) například můžete vidět, jak firma DataSys s.r.o. programuje "ChatBota" a publikuje veřejně zdrojové kódy ([první vlašťovka](http://take.ms/axOvj)?).

 Otevřený repozitář komukoliv umožní:
  - podívat se jak je sw dílo naprogramované
  - udělat si kopii (fork) a vyrobit vlastní verzi stejného díla
  - najít chybu a poslat opravu (pull request)
  - připomínkovat dílo a komunikovat s autorem (issues) 

Jsme přesvědčeni, že zakázkový software placený z veřejných peněz **má být komukoliv otevřený!**

### proč chtít kód pokrýt testy
> TBD
### co znamená "Continuous Delivery"
> TBD
### co je Docker kontejner

Tak jako [vmWare](http://www.vmware.com/) virtualizoval operační systém, virtualizoval Docker aplikace. Pokud vám někdo dodá aplikaci v Docker kontejneru, dovedete si ji velmi snadno spustit na svém serveru, aniž byste museli řešit kompatibilitu prostředí. Budete schopni velmi efektivně provozovat aplikaci v cloudu ([Azure Container Service](https://azure.microsoft.com/en-us/services/container-service/), [Amazon Container Service](https://aws.amazon.com/ecs/), [Google Container Engine](https://cloud.google.com/container-engine/)) i na svém serveru.

Docker [kontejner je bezpečný](https://www.docker.com/docker-security) a důvěřují mu největší firmy na světě, jako např. [Accenture](https://www.docker.com/accenture), [Hewlett Packart Enterprise](https://www.docker.com/hpe), [Microsoft](https://www.docker.com/microsoft) nebo [Cisco](https://www.docker.com/cisco).

Váš požadavek na vývoj v Dockeru přinese dodavateli pohodlí při realizaci a jednoduché předávání do vaší produkce. Pro vás znamená flexibilitu, jistotu a bezpečí.