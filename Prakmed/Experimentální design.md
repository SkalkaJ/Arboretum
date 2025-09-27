---
type: poznámky
tags:
  - škola
  - prakmed
year: 2025
created: 2025-09-27
updated: 2025-09-27
---
[[Kopie souboru Praktická metodologie vědy.pdf#page=18&selection=153,15,153,21&color=note| Učebnice]]
[[prakmet_design.pdf]]
### Základní typy
- **Pokus** experiment
	- Kontrola celého průběhu pokusu, zejména pokusných objektů
	- Bezpečné informování o kauzalitách
	- Riziko experimentálnch artefaktů
- **Pozorování**
	- Bez zásahu výzkumníka
	- Velmi obtížné zpracování a vyhodnocení
	- Průběh mají pod kontrolou experimentální objekty
### Uspořádání pozorování
- Kazuistiky = jednotlivý případ
- Korelační studie (porovnání populace)
- Průřezové studie
	- Jedinci, ale jednorázově
	- V jeden okamžik a nevím co je příčinou čeho
- Longitudiální studie
	- Opakovaně vyšetřované stejné osoby a pátrá se po důsledcích expozice určitéhofaktoru
	- Zjišťuje i něco o kauzalitě
- Studie případů a kontrol (case-control study)
	- Porovná vá se skupina pacientů a skupina kontrol
	- poměr skupin neodpovídá zastoupení v populaci
	- zkresluje význam daného faktoru
- Kohortová studie
	- Výskyt rizikového faktoru i nemoci odpovídá zastoupení v populaci
	- nevhodné pro vzácné nemoci
### Problémy observačních studií
- Asociace vs. Kauzalita
- Efekt síta
- *Uspořádání studie*
	- Jednoduché a komplexní uspořádání- 
	- Základní soubor a vzorek
		- Representativnost (zobecnitelnost výsledků)
		- Homogenita vzorku (zvyšuje sílu testu)
	- Kontroly
		- Randomizace
		- Placebo, slepý pokus, dvojnásobný slepý pokus, otevřený pokus
		- Velikost vzorku kontrol - maximálně 1:5, jinak exaktní či randomizační testy
		- spárování kontrol a případů (párové testy jsou silnější)
			- Jedna těžká myš objekt a jedna těžká myš kontrola
		- Náhodnost zařazení do skupin
		- Vyváženost dat v jednotlivých skupinách
### Struktura dat
- náhodnost zařazení do skupiny
- Nezávislost dat
	- Chyba je používat listy jedné rostliny, vejce v jednom hnízdě,...
	- Fylogeneticky příbuzné organismy (evoluční kontrasty)

# Dopracovat z prezentace a textu


### Matoucí Proměnné
- Eliminace
	- snižuje riziko systematické chyby
	- zvyšuje sílu testu
	- odstranit část variability (jen ženy,...)
- Randomizace
	- Při výběru a randomizaci můžeme mezi kontroly a objekty zařazovat páry, které mají stejné ty rušivé proměnné
- Blokování
	- Párování
	- Latinské čtverce
		- ![[prakmet_design.pdf#page=21&rect=191,66,548,257|prakmet_design, p.21]]
- Monitorování a následné statistické odfiltrování
	- Náročné, opatrně
	- Modelování pomocí strukturálních rovnic SEM 
	- Třeba Analýza drah
### Velikost Souboru
- **Riziko chyby II. typu**
	- Neúčinná randomizace
	- Když v malém souboru nenajdu signifikantní vliv nemusí znamenat, že tam nebyl, ale že jsem ho prostě nenašel kvůli velikosti
	- nemožnost blokovat rušivé proměnné
	- Nepoužitelnost některých metod
		- Chi$^2$ = četnost musí být větší než 5
		- Nejlepší jsou exaktní testy
			- Umožňují získat signifikantní výsledek i na malém souboru
			- Fisher - šálky s čajem
			- P= 0.031, pět hrnečků stačí, ale 4 by bylo málo ($0.5^5$)
- *Dostatečná velikost pokusného souboru závisí na*
	- Variabilitě sledované vleičiny
	- Počtu sledované veličiny
	- Technických možnostech
	- Požadované miře jistoty
	- *Velikost očekávaného efektu*
		- Pozor na příliš velké soubory
		- Na dostatčně velkém souboru dokážeme cokoli
		- Objeví se tam strašně slabý vliv, který existuje, ale nemá prakticky význam
		  (stín vlaštovky nad polem)
- ***Analýza síly studie*** (Power analysis)
	- Určení vhodné velikosti vzorku, aby se minimalizovalo riziku chyby II. typu,
	- Tedy prokázání existujícího jevu
	- Umožňuje předem zvolit nebo zpětně kvantifikovat pravděpodobnost, že neodhalíme asociaci, i když ve skutečnosti existuje
	- rozumná hodnost 80%