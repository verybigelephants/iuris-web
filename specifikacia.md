# Iuris web 
Prezentacny web na statamicu, kde su administrovatelne staticke stranky, projekty a novinky. Bude mat 2 jazykove mutacie a je to "single page apka" aby sa mohli prechody medzi podstrankami animovat.

V specke sa na strankach spomina backend a frontend, teda ku stranke sa odhaduje zaroven aj frontendova cast aj praca na administracnom paneli. Tiez vo frontende je tiez odhadnuty len priblizne ceny animacii, ked este neviem presne uplne ako sa maju spravat animacie.


## harry potter
  - jednoduchy inline video player s callbackom na replay, administrovatelny claim klienta. Tuto pozor, na iphonoch autoplay nepojde, tam musi byt vykonana interakcia cloveka aby sa video prehralo
  - "o nas" textik + administrovatelne statistiky a ceny (statstiky su par hodnota:cislo, ceny su par svg ikona: cena/rok/projekt) 
  - animovany listing vsetkych projektov 
  - strucny listing 2 poslednych noviniek s preklikom na vsekty novinky
  
	:: backend: 3h
	:: frontend: 14h
	
## projekty 
iba detail a backend, frontend listingu je zahrnuty v harrym potterovi
  - administrovatelny projekt:
  	- text k projektu
	- fotky/"hero image" co je aj thumbnail do listingu
	- metadata: lokacia/rok/web/referencia na tagy ku projektu (apartmany/retail/etc)
	- zobrazeny/skovany (napr. mozno si len edituju projekt ale pojde von neskor)
  - administracia tagov ktore su vybratelne k projektu 
  - custom galeria s tym vertikalnym sliderom (na telefone by som dal mozno klasicky horizontalny)
  
	:: backend: 4h
	:: frontend: 10h
  
## novinky 
  - listing noviniek s lazy loadingom na button "nacitaj viac", collapsovatelny perex ked je pridlhy
  - vemli detail novinky ktory vyzera presne ako prva novinka zo zoznamu vsektych noviniek, akurat s rozrolovanym celym textom a back buttonom na vsetky novinky 
  - administrovatelna novinka: 
    - datum, published at
	- titulok
	- perex
	- plny text 
	- obrazok
  
	:: backend: 2h
	:: frontend: 10h
	
## staticke casti 
   - ochrana osobnych udajov - jednoduchy wysiwyg s hlavickami/paragrafmi
   - cookies - to iste
   - kontakt (vzdy zobrazeny vo footri) 
     - "sme clenmi" a mapku by som dal staticke, telefonik a email si mozu upravit v administracii 
	 - mapku staticku tiez 
	 
	:: backend 2h
	:: frontend 6h
	
## hlavny ram stranky/menu/url routing/layout/metatagy/etc
	
	:: backend 4h
	:: frontend 12h
	
## "one page" engine a animacie na scroll
engine na dynamicke nacitanie obsahu s animaciami pri kliknuti namiesto premserovania celej stranky, plus cele animacie co sa budu diat pocas toho ako clovek chodi strankou 

	:: backend 6h
	:: frontend 12h 
	
	
## pripomienky (odhad, vzdy zalezi od klienta)

	:: backend 2h
	:: frontend 6h
	
## deploy 

	:: 2h backend
	
## celkovo odhad
	25h backend * 40€ = 1000€ 
	70h frontend * €30€ = 2100€
	===
	3100€
	
