![Logo Toastmasters Košice][logo]
# Úprava členského statusu
Každý člen, ktorý sa niekedy zúčastnil na stretnutí, má priradený členský status a dátum nastavenia statusu. Tu je zoznam bežných statusov:
- Aktívny člen - majú ho nastavený všetci platiaci členovia, ktorí sa aktívne zúčastňujú na stretnutí
- Neaktívny člen - majú ho členovia, ktorí sa nezúčastňujú dlhodobo stretnutí
- Bývalý člen/hosť/používateľ - majú ho členovia, ktorí už nie sú v klube

Popri bežných členských statusoch si viete pridať aj nové. V našom klube sme pridali status *Člen iného klubu* a označujeme tak hostí z iných klubov, ktorí k nám prídu na stretnutie.

> Poznámka: Aby ste mohli tieto nastavenia meniť, musíte mať dostatočné oprávnenia a mať prístup do ovládacieho panelu klubu. Typicky má prístup len viceprezident pre vzdelávanie.

## Obrazovka na správu statusov
Všetky nastavenia sa robia na obrazovke s názvom **Status Manager** (Správa statusov). Dostanete sa na ňu tak, že po [prihlásení sa][ovladaci-panel-klubu] do ovládacieho panelu klubu kliknete v bočnom menu naľavo na kartu `Member status` (členský status).

![Správa členských statusov][sprava-clenskych-statusov]

Na tejto obrazovke prehľadne vidíte, aké oprávnenia má člen s určitým statusom. Ak má člen nastavený status *Neaktívny člen*, easy-Speak mu nedovolí žiadať o prejavy. U hostí z iných klubov zase máme vypnuté posielanie emailov.

Na tejto obrazovke máte niekoľko možností:
- Môžete pridať nové členské statusy
- Môžete existujúce členské statusy zmazať alebo upraviť
    - Môžete statusy premenovať, aby lepšie zapadli do vášho klubu

Na uvedenom obrázku si môžete všimnúť, že členské statusy používané na stretnutiach klubu Toastmasters Košice už boli premenované, napríklad status *Aktívny člen* sa pôvodne volal *Active Member*. Úprava názvu členského statusu sa prejaví okamžite.

## Pridanie členského statusu
Nový členský status má zmysel pridať vtedy, ak potrebujete odlíšiť skupinu niektorých členov od tej vašej. V našom prípade sme zaviedli napríklad status *Člen iného klubu*. Status pridáte tak, že na obrazovke vyberiete možnosť `Add` (pridať). Nachádza sa úplne dole, vpravo.

Potrebujete zadať:
- Názov stavu (pole `Status Description`)
- Kód stavu (pole `Code`) - ide o unikátne číslo uvedené na obrazovke **Status Manager** vedľa názvu stavu v zátvorke. Číslo musí byť unikátne, inými slovami, nesmie ho používať už existujúci členský status
- Oprávnenia, ktoré bude člen s týmto statusom mať. Napríklad mu dovolíte mať prejavy na stretnutí, ale zakážete easy-Speaku, aby mu automaticky priradzoval rolu a posielal maily

Keď máte takto zadefinovaný status, môžete ho u člena nastaviť. To si ukážeme v samostatnom návode.

## Odstránenie členského statusu
Ak už členský status vo vašom klube nepotrebujete, môžete ho odstrániť. Na obrazovke kliknite na ikonu krížika vedľa statusu. Zmenu potvrďte.

> Poznámka: Nie je známe, ako sa zachová easy-Speak, ak členovia ešte majú status priradený a vy ho odstránite. Ak to zistíte, pokojne návod doplňte.

## Zmena existujúceho členského statusu a úprava jeho názvu
Kliknite na tlačidlo `Edit` (upraviť), čím sa dostanete na obrazovku s názvom **User Status Settings** (nastavenia používateľského statusu). Tu viete upraviť nastavenia statusu a takisto ho premenovať.

Premenovanie statusu vám umožní, aby zodpovedal tomu, na čo ste zvyknutí v klube. Typicky ide o premenovanie anglických názvov statusov do slovenčiny. Následne už všetci členovia vo vašom klube vidia to, na čo sú zvyknutí. Upravte pole **Status Description** (popis stavu) a zmeny uložte.

Takto vyzerá obrazovka stretnutia, kde je zadefinovaný status Aktívny člen. Všimnite si ho v zozname vedľa neobsadených rolí stretnutia.

![Členský status v slovenčine][clensky-status-v-slovencine]

## Súvisiace odkazy
- [Ovládací panel klubu][ovladaci-panel-klubu]
- [Obrazovka stretnutia][obrazovka-stretnutia]

[logo]: https://github.com/toastmasters-kosice/graficke-podklady/raw/main/Log%C3%A1/%C5%A0tandardn%C3%A9%20zmen%C5%A1en%C3%A9%20logo%20TMKE.png "Logo Toastmasters Košice"
[sprava-clenskych-statusov]: https://github.com/toastmasters-kosice/graficke-podklady/raw/main/Sn%C3%ADmky%20obrazovky/easy-Speak/Ovl%C3%A1dac%C3%AD%20panel%20klubu/%C4%8Clensk%C3%BD%20status.png "Správa členských statusov"
[clensky-status-v-slovencine]: https://github.com/toastmasters-kosice/graficke-podklady/raw/main/Sn%C3%ADmky%20obrazovky/easy-Speak/Ovl%C3%A1dac%C3%AD%20panel%20klubu/Role%20stretnutia%20v%20sloven%C4%8Dine.png "Členský status v slovenčine"
[ovladaci-panel-klubu]: 001%20Ovl%C3%A1dac%C3%AD%20panel%20klubu.md "Ovládací panel klubu"
[obrazovka-stretnutia]: ../Spr%C3%A1va%20stretnutia/001%20Obrazovka%20stretnutia.md "Obrazovka stretnutia"