# Komentář k zákonu č. 250/2017 Sb., o elektronické identifikaci

> **Znění k 1. dubnu 2023** (dokument e-Sbírky `SB-2017-00250_2023-04-01`). Komentář je zpracován **výhradně z lokálních materiálů**; nevyužívá živé komerční právní databáze.
>
> **Metodická poznámka:** Výklad vychází z místního konsolidovaného znění zákona po změnách provedených zákony č. 12/2020 Sb., č. 261/2021 Sb. a č. 471/2022 Sb., z místního znění navazujících předpisů (zejména zákona o informačních systémech veřejné správy, zákona o právu na digitální služby a vyhlášky č. 409/2022 Sb.) a z textu, systematiky a účelu zákona. Komentář **neuvádí žádné spisové značky soudních rozhodnutí**, protože k nim v místních materiálech není opora; kde by u jiného předpisu stála judikatorní citace, komentář otevřeně označuje problém jako **výkladovou otázku**. Kdekoli doprovodné soubory (ZASADY.md, PRAVNI-MODALITY.md) cituje doslovně, jde o citace z kapitol tohoto repozitáře, nikoli o citace rozhodnutí.

---

## Co tento zákon je

Zákon č. 250/2017 Sb., o elektronické identifikaci (dále „**zákon o elektronické identifikaci**", „**ZeID**" nebo „**zákon**"), je **adaptačním předpisem** k přímo použitelnému nařízení Evropského parlamentu a Rady (EU) č. 910/2014 o elektronické identifikaci a službách vytvářejících důvěru pro elektronické transakce na vnitřním trhu (eIDAS). Nepřebírá unijní pravidla, ale upravuje to, co nařízení ponechává vnitrostátnímu právu:

- **kdy a jakou** elektronickou identifikaci lze připustit tam, kde právní předpis nebo výkon působnosti vyžaduje prokázání totožnosti (§ 2),
- **kdo** smí spravovat systém elektronické identifikace použitelný pro tyto účely — kvalifikovaný správce, tedy státní orgán nebo akreditovaná osoba (§ 3, § 4),
- **jak** se získává, mění, odnímá a zaniká akreditace a jak se posuzují prostředky a systémy elektronické identifikace (§ 5 až § 14),
- **jaké povinnosti** nesou kvalifikovaný správce, držitel prostředku a kvalifikovaný poskytovatel (§ 15 až § 18),
- **jakou roli** má Digitální a informační agentura, národní bod pro identifikaci a autentizaci a navazující evidence a seznamy (§ 19 až § 23),
- **jak** se sankcionuje porušení povinností akreditované osoby (§ 25, § 26).

Zákon nabyl účinnosti **1. července 2018** (§ 28). Jeho ústřední myšlenkou je, že tam, kde právo vyžaduje prokázání totožnosti, smí elektronická identifikace nahradit fyzické ověření totožnosti jen tehdy, je-li zaručena **úroveň záruky** podle unijních technických standardů a napojení na **národní bod**, který umožňuje bezpečné a od agendy k agendě oddělené předávání identifikačních údajů.

## Vztah k nařízení eIDAS a k prováděcím aktům

ZeID na unijní akty navazuje třemi poznámkami pod čarou, které vymezují jeho pojmový a technický rámec:

- **nařízení (EU) č. 910/2014** (poznámka 1) — obecný rámec elektronické identifikace a vzájemného uznávání oznámených systémů; ZeID jeho pojmy (systém elektronické identifikace, prostředek pro elektronickou identifikaci, úroveň záruky) nepředefinovává, ale vykládá autonomně podle nařízení,
- **prováděcí nařízení Komise (EU) 2015/1502** (poznámka 2, legislativní zkratka „příslušný předpis Evropské unie") — minimální technické specifikace, normy a postupy pro úrovně záruky nízká, značná a vysoká; jde o jediné měřítko posuzování prostředků a systémů (§ 13),
- **prováděcí nařízení Komise (EU) 2015/1501** (poznámka 4) — rámec interoperability, podle něhož samostatná součást národního bodu plní úlohu uzlu (§ 20 odst. 3 a 4).

Úkoly jednotného kontaktního místa plní Agentura podle prováděcího rozhodnutí Komise (EU) 2015/296 (poznámka 3, § 19 písm. b)). Vnitrostátní zákon tedy **nestanoví žádné vlastní technické požadavky** na prostředky elektronické identifikace — jeho přidanou hodnotou je institucionální, procesní a sankční rámec.

## Vývoj působnosti — Digitální a informační agentura

Původně byla působnost na úseku elektronické identifikace rozdělena mezi **Ministerstvo vnitra** (akreditace, pověřování, kontrola, přestupky) a **Správu základních registrů** (správa národního bodu, seznamy). Zákon č. 471/2022 Sb. ji s účinností od **1. dubna 2023** soustředil do **Digitální a informační agentury** jako ústředního správního úřadu (§ 2a zákona o právu na digitální služby). Podle přechodného ustanovení čl. XX zákona č. 471/2022 Sb. dokončuje Agentura postupy zahájené před tímto dnem a dosavadní úkony obou orgánů se považují za její úkony. Na úkony a skutečnosti z doby před 1. 4. 2023 je proto třeba aplikovat znění účinné v rozhodné době, zejména pokud jde o příslušný orgán.

Agentura dnes vystupuje v **několika rolích současně**: rozhoduje o akreditaci (§ 5 až § 7), pověřuje posuzovatele a subsidiárně sama posuzuje (§ 11 až § 14), kontroluje kvalifikované správce, kvalifikované poskytovatele a pověřené osoby (§ 19 písm. c)), spravuje národní bod (§ 20 odst. 2), vede evidence a seznamy (§ 19 písm. d), § 23), projednává přestupky (§ 26) a sama je kvalifikovaným správcem vydávajícím prostředek pro elektronickou identifikaci (§ 19 písm. h)). Kumulace těchto rolí je jedním z hlavních systémových témat komentáře.

## Klíčové instituty

### Výhrada kvalifikovaného systému (§ 2)

Ústředním pravidlem zákona je podmíněná výhrada: **vyžaduje-li** právní předpis nebo výkon působnosti prokázání totožnosti **a** umožní-li ten, kdo totožnost ověřuje, její prokázání elektronickou identifikací, smí jít **pouze o kvalifikovaný systém**. Zákon tím nezakládá povinnost elektronickou identifikaci nabízet („lze umožnit"); povinnost připustit digitální úkon může plynout z jiných předpisů, zejména ze zákona o právu na digitální služby. Dvouleté přechodné období, během něhož bylo možné využít i nekvalifikovaný systém (§ 27 odst. 2), uplynulo k 1. 7. 2020; dnes platí pravidlo § 2 bez výjimky.

### Kvalifikovaný systém a kvalifikovaný správce (§ 3, § 4)

Kvalifikovaný systém existuje ve **dvou podobách**: jako **tuzemský** systém, který kumulativně splňuje pět znaků podle § 3 odst. 1 (kvalifikovaný správce, alespoň jedna úroveň záruky, služba národního bodu, spojení identifikačních údajů s osobou a spojení prostředku s osobou), a jako **oznámený** systém jiného členského státu s úrovní záruky alespoň značnou (§ 3 odst. 2). Kvalifikovaným správcem může být **pouze** státní orgán, nebo akreditovaná osoba (§ 4). Státní orgán akreditaci nepotřebuje, věcné požadavky § 3 odst. 1, plán ukončení činnosti a povinnosti podle § 16 však nese i on.

### Akreditace (§ 5 až § 10)

Akreditaci uděluje Agentura **rozhodnutím na písemnou žádost** ve lhůtě 3 měsíců; rozhodnutí je **nárokové** — splňuje-li žadatel šest podmínek § 5 odst. 2 (technické požadavky, bezúhonnost, pojištění, plán ukončení činnosti, služba národního bodu, způsobilost z hlediska veřejného pořádku a bezpečnosti), Agentura akreditaci udělí. Změna akreditace (§ 6) slouží k rozšíření o další prostředek, odnětí (§ 7) je dvoufázové (upozornění s výzvou k nápravě, poté obligatorní odnětí), zánik (§ 8) nastává ex lege smrtí nebo zánikem akreditované osoby. Povinné pojištění (§ 9) doplňuje vyhláška č. 409/2022 Sb. o minimálním limitu pojistného plnění; pojistný limit však **neomezuje** povinnost k náhradě škody. Bezúhonnost (§ 10) je vymezena negativně a pro účely ZeID.

### Posuzování prostředků a systémů (§ 11 až § 14)

Splnění technických požadavků posuzuje **pověřená osoba**, kterou Agentura pověřuje z okruhu atestačních středisek podle zákona o informačních systémech veřejné správy; pověření je **odvozené** od atestačního pověření a **nepřevoditelné**. Posouzení probíhá na smluvním základě, končí písemným potvrzením se stanovenou úrovní záruky nebo odůvodněným vyrozuměním o nesplnění požadavků a je podkladem řízení o akreditaci. Není-li pověřena žádná osoba, posuzuje subsidiárně Agentura (§ 14).

### Povinnosti správce, držitele a poskytovatele (§ 15 až § 18)

Kvalifikovaný správce zpracovává **plán ukončení činnosti** (§ 15) a nese katalog dvanácti povinností (§ 16 odst. 1) — dostupnost systému přes národní bod, vedení evidence, ověření totožnosti držitele před prvním použitím, zápis identifikátoru a úrovně záruky, zneplatnění prostředků a jejich oznámení správci národního bodu — spolu s personálními předpoklady (§ 16 odst. 2 a 3). **Držitel** ověřuje správnost údajů, zachází s prostředkem s náležitou péčí a ohlašuje zneužití (§ 17). **Kvalifikovaný poskytovatel** — každý, kdo umožňuje zákonem vyžadované prokázání totožnosti elektronicky — vyrozumívá správce národního bodu o zahájení a ukončení této činnosti prostřednictvím elektronické aplikace (§ 18).

### Národní bod, evidence a seznamy (§ 19 až § 23)

**Národní bod** pro identifikaci a autentizaci je informačním systémem veřejné správy, jehož správcem je Agentura (§ 20). Vede taxativně vymezené identifikátory a provozní údaje (§ 21), nikoli jméno, adresu či datum narození — ty obsahuje **evidence vydaných prostředků** vedená každým kvalifikovaným správcem (§ 22). Údaje se uchovávají zpravidla **15 let** od skončení platnosti prostředku. Agentura vede veřejný **seznam** kvalifikovaných správců a kvalifikovaných poskytovatelů usazených v České republice (§ 23), který má evidenční, nikoli konstitutivní povahu.

### Přestupky (§ 25, § 26)

Skutkové podstaty jsou **blanketní** a zrcadlí povinnosti kvalifikovaného správce podle § 16; pachatelem může být **jen akreditovaná osoba**. Za personální přestupky lze uložit pokutu do 1 000 000 Kč, za ostatní do 2 000 000 Kč. Porušení povinností státního orgánu jako správce, držitele (§ 17) ani kvalifikovaného poskytovatele (§ 18) podle tohoto zákona přestupkem není. Přestupky projednává Agentura (§ 26).

## Doslovné znění § 2

> **§ 2 — Prokázání totožnosti s využitím elektronické identifikace**
>
> Vyžaduje-li právní předpis nebo výkon působnosti prokázání totožnosti, lze umožnit prokázání totožnosti s využitím elektronické identifikace pouze prostřednictvím kvalifikovaného systému elektronické identifikace (dále jen „kvalifikovaný systém“).

## Vazby na jiné předpisy

| Předpis | Vazba na ZeID |
|---|---|
| nařízení (EU) č. 910/2014 (eIDAS) | adaptovaný unijní rámec; oznámené systémy (§ 3 odst. 2), úkoly podle čl. 9 a 10 (§ 19 písm. a)) |
| prováděcí nařízení (EU) 2015/1502 | měřítko úrovní záruky a posuzování (§ 3 odst. 1 písm. b), d), e), § 13) |
| prováděcí nařízení (EU) 2015/1501 | rámec interoperability, uzel národního bodu (§ 20 odst. 3 a 4, § 21 odst. 1 písm. d), odst. 6) |
| zákon č. 12/2020 Sb., o právu na digitální služby | postavení Agentury jako ústředního správního úřadu (§ 2a); povinnost připustit digitální úkon navazující na § 2 ZeID |
| zákon č. 365/2000 Sb., o informačních systémech veřejné správy | okruh pověřitelných osob (atestační střediska), obdobné použití § 6d odst. 3 a § 6e (§ 11, § 13); národní bod jako ISVS (§ 20) |
| zákon č. 111/2009 Sb., o základních registrech | agendové identifikátory držitele pro agendu autentizace (§ 21 odst. 1 písm. b)) |
| zákon č. 471/2022 Sb. | přenesení působnosti na Agenturu od 1. 4. 2023, přechodné ustanovení čl. XX |
| vyhláška č. 409/2022 Sb. | pravidla výpočtu minimálního limitu pojistného plnění (§ 9 odst. 1) |
| zákon č. 500/2004 Sb., správní řád | subsidiárně pro řízení o akreditaci, její změně a odnětí (§ 5 až § 7) |
| zákon č. 255/2012 Sb., kontrolní řád | postup kontroly podle § 19 písm. c) |
| zákon č. 250/2016 Sb., o odpovědnosti za přestupky a řízení o nich | obecná úprava odpovědnosti, výměry pokuty a promlčení (§ 25, § 26) |
| zákon č. 269/1994 Sb., o Rejstříku trestů | prokazování bezúhonnosti a elektronické vyžádání výpisu (§ 10 odst. 6) |
| obecné nařízení o ochraně osobních údajů a zákon č. 110/2019 Sb. | zpracování osobních údajů v evidenci vydaných prostředků a v národním bodu (§ 21, § 22) |
| občanský zákoník | předpoklady a rozsah náhrady škody (§ 9 odst. 2); soukromoprávní význam povinností držitele (§ 17) |

## Struktura komentáře

Zákon má **27 paragrafových jednotek** (§ 1 až § 28; § 24 se v místním znění kapitol nevyskytuje — kapitola 3 přechází od § 23 přímo k přestupkům v § 25). Komentář je rozdělen do tří kapitol:

| Kapitola | Předmět | Paragrafy |
|---|---|---|
| [01](01-zakladni-ustanoveni-kvalifikovany-system-akreditace.md) | **Předmět úpravy, prokázání totožnosti, kvalifikovaný systém a správce, akreditace** — předmět zákona, výhrada kvalifikovaného systému, znaky kvalifikovaného systému, okruh kvalifikovaných správců, udělení, změna, odnětí a zánik akreditace, pojištění odpovědnosti, bezúhonnost | § 1–10 |
| [02](02-posuzovani-povinnosti.md) | **Posuzování, plán ukončení činnosti, povinnosti** — pověřená osoba, odnětí a zánik pověření, posouzení prostředku a systému, subsidiární posuzování Agenturou, plán ukončení činnosti, povinnosti kvalifikovaného správce, držitele a kvalifikovaného poskytovatele | § 11–18 |
| [03](03-pusobnost-narodni-bod-evidence-prestupky.md) | **Působnost, národní bod, evidence, přestupky** — působnost Agentury, národní bod a údaje v něm vedené, evidence vydaných prostředků, seznam kvalifikovaných správců a poskytovatelů, přestupky a jejich projednávání, přechodná ustanovení a účinnost | § 19–23, § 25–28 |

Doprovodné soubory:

- [ZASADY.md](ZASADY.md) — právní zásady zákona doložené doslovnými citacemi z kapitol,
- [PRAVNI-MODALITY.md](PRAVNI-MODALITY.md) — mapa normativních modalit (příkaz, zákaz, dovolení, zmocnění, oprávnění a povinnost, domněnky a fikce) s doslovnými fragmenty znění.

## Poznámka k metodě

- U každého paragrafu je v citačním bloku uvedeno **úplné doslovné znění** (bez elips) podle dokumentu e-Sbírky `SB-2017-00250_2023-04-01`, pod ním oddíl `**Výklad:**` a dále oddíly F. Kazuistika, G. Protiargumenty a rizika, H. Praktický závěr s kontrolním checklistem.
- Odkazy na navazující předpisy (zákon o informačních systémech veřejné správy, zákon o právu na digitální služby, vyhláška č. 409/2022 Sb., zákon č. 471/2022 Sb.) vycházejí z jejich **místního znění**; kde komentář uvádí, že bylo něco ověřeno v lokálním znění, týká se to výhradně těchto souborů.
- Komentář **neobsahuje judikaturu ani spisové značky** — místní materiály k zákonu žádnou rozhodovací praxi nedokládají. Sporná místa jsou výslovně označena jako **výkladová otázka** a komentář u nich uvádí argumenty pro a proti, nikoli autoritativní řešení.
- Unijní akty jsou citovány podle poznámek pod čarou zákona v původním znění; jejich aktuální znění (včetně změn nařízení eIDAS) je třeba ověřit v úředních zdrojích Evropské unie.

---

> **Upozornění:** Komentář slouží odbornému a vzdělávacímu účelu. Vychází ze znění zveřejněného k 1. 4. 2023; pozdější změny nemusí být zohledněny. Nejde o právní službu ani závazné právní stanovisko.
