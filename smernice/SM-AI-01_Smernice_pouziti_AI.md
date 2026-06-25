# SM-AI-01 — Vnitřní směrnice pro používání umělé inteligence (AI) ve zdravotnickém zařízení

| Údaj | Hodnota |
|---|---|
| **Označení dokumentu** | SM-AI-01 |
| **Název** | Směrnice pro používání umělé inteligence (AI) |
| **Typ dokumentu** | Vnitřní řídicí akt (směrnice) |
| **Vydavatel** | [Doplňte: název poskytovatele zdravotních služeb] |
| **Garant dokumentu** | Pověřenec pro AI / Komise pro AI (viz čl. 6) |
| **Schválil** | Ředitel/ka (statutární orgán) |
| **Verze** | 1.0 |
| **Datum nabytí účinnosti** | [DD. MM. RRRR] |
| **Platnost do** | do odvolání / nejbližší revize |
| **Cyklus revize** | min. 1× ročně a vždy při změně legislativy |
| **Klasifikace** | Interní |

> **Upozornění k aktuálnosti:** Tato směrnice odkazuje na legislativu a normy, jejichž účinnost a znění se vyvíjí (zejména nařízení EU 2024/1689 — Akt o umělé inteligenci, nový zákon o kybernetické bezpečnosti / NIS2, připravovaná směrnice o odpovědnosti za AI a zákon o správě zdravotních dat). Garant dokumentu je povinen sledovat aktualizace metodik **MZ ČR / NCEZ**, **SÚKL** a **NÚKIB** a směrnici bezodkladně uvádět do souladu. Tato směrnice **nikdy nesmí být vykládána v rozporu s platnou legislativou**; v případě rozporu má vždy přednost zákon a přímo použitelné předpisy EU.

---

## Obsah

1. [Účel a předmět směrnice](#1-účel-a-předmět-směrnice)
2. [Působnost](#2-působnost)
3. [Pojmy a zkratky](#3-pojmy-a-zkratky)
4. [Legislativní a normativní rámec](#4-legislativní-a-normativní-rámec)
5. [Základní (kogentní) zásady používání AI](#5-základní-kogentní-zásady-používání-ai)
6. [Řízení AI (governance), role a odpovědnosti](#6-řízení-ai-governance-role-a-odpovědnosti)
7. [Klasifikace AI systémů a režimy použití](#7-klasifikace-ai-systémů-a-režimy-použití)
8. [Režim A — AI ve zdravotní péči (diagnostika a léčba)](#8-režim-a--ai-ve-zdravotní-péči-diagnostika-a-léčba)
9. [Režim B — AI ve výzkumu a klinických zkouškách](#9-režim-b--ai-ve-výzkumu-a-klinických-zkouškách)
10. [Režim C — Vývoj AI a „vibe coding"](#10-režim-c--vývoj-ai-a-vibe-coding)
11. [Režim D — Provozní a administrativní AI (THP zaměstnanci)](#11-režim-d--provozní-a-administrativní-ai-thp-zaměstnanci)
12. [Režim E — Generativní AI a velké jazykové modely (LLM)](#12-režim-e--generativní-ai-a-velké-jazykové-modely-llm)
13. [Požadavky na dodavatele (přísný režim)](#13-požadavky-na-dodavatele-přísný-režim)
14. [Ochrana osobních a zdravotních dat](#14-ochrana-osobních-a-zdravotních-dat)
15. [Kybernetická bezpečnost](#15-kybernetická-bezpečnost)
16. [Informovaný souhlas a práva pacienta](#16-informovaný-souhlas-a-práva-pacienta)
17. [Odpovědnost, dokumentace a řešení rozporu AI vs. člověk](#17-odpovědnost-dokumentace-a-řešení-rozporu-ai-vs-člověk)
18. [Schvalovací proces a registr AI systémů](#18-schvalovací-proces-a-registr-ai-systémů)
19. [Vzdělávání a kompetence](#19-vzdělávání-a-kompetence)
20. [Kontrola, audit, hlášení incidentů a sankce](#20-kontrola-audit-hlášení-incidentů-a-sankce)
21. [Přechodná a závěrečná ustanovení](#21-přechodná-a-závěrečná-ustanovení)
22. [Přílohy](#22-přílohy)

---

## 1. Účel a předmět směrnice

1.1 Účelem této směrnice je stanovit **závazná, jednotná a přísná pravidla** pro pořizování, schvalování, zavádění, provoz, vývoj a vyřazování systémů a nástrojů využívajících umělou inteligenci (dále jen „**AI systém**") u poskytovatele zdravotních služeb (dále jen „**poskytovatel**" nebo „**nemocnice**").

1.2 Směrnice sleduje tři rovnocenné a nadřazené cíle:
- a) **Bezpečnost a zdraví pacienta** — žádné použití AI nesmí ohrozit bezpečí, zdraví ani práva pacienta;
- b) **Soulad s legislativou** — veškeré použití AI musí být plně v souladu s platnými právními předpisy ČR a EU a s metodickými stanovisky MZ ČR / NCEZ, SÚKL a NÚKIB;
- c) **Důvěryhodnost a kontrola dodavatelů** — žádný dodavatel ani AI systém nesmí být nasazen bez prokázání shody, bezpečnosti a doložené odpovědnosti.

1.3 Směrnice provádí a doplňuje obecně závazné předpisy; **v žádném bodě je nenahrazuje ani neomezuje**. Pokud by jakékoli ustanovení této směrnice bylo v rozporu s pozdější legislativou, použije se přednostně legislativa a garant je povinen směrnici neprodleně upravit.

---

## 2. Působnost

2.1 **Osobní působnost:** Směrnice je závazná pro všechny zaměstnance v pracovněprávním vztahu, lékaře a nelékařské zdravotnické pracovníky, THP (technicko-hospodářské) zaměstnance, vědecké a vývojové pracovníky, IT pracovníky, studenty, stážisty, dobrovolníky, externí spolupracovníky, dodavatele a jejich pracovníky, kteří v prostorách nebo v systémech poskytovatele používají nebo zavádějí AI.

2.2 **Věcná působnost:** Směrnice se vztahuje na **všechny** AI systémy bez ohledu na formu nasazení (lokálně, on-premise, cloud, SaaS, mobilní aplikace, modul NIS/PACS, samostatný software, vestavěný software ve zdravotnickém prostředku, veřejně dostupný online nástroj).

2.3 **Místní působnost:** Všechna pracoviště, datová centra a vzdálené přístupy poskytovatele.

2.4 Z působnosti **nelze vyjmout** žádné použití AI, které pracuje s pacientskými, osobními či citlivými provozními daty poskytovatele, nebo které může ovlivnit zdravotní péči.

---

## 3. Pojmy a zkratky

| Pojem / zkratka | Význam |
|---|---|
| **AI systém** | Strojový systém ve smyslu čl. 3 nařízení (EU) 2024/1689 (Akt o AI), který na základě vstupů generuje výstupy (predikce, doporučení, rozhodnutí, obsah). |
| **AI Act / Akt o AI** | Nařízení Evropského parlamentu a Rady (EU) 2024/1689 o umělé inteligenci. |
| **ZP** | Zdravotnický prostředek. |
| **MDR** | Nařízení (EU) 2017/745 o zdravotnických prostředcích. |
| **IVDR** | Nařízení (EU) 2017/746 o diagnostických zdravotnických prostředcích in vitro. |
| **MDSW / SaMD** | Software jako zdravotnický prostředek (Software as a Medical Device). |
| **CE** | Označení shody prostředku/produktu s požadavky příslušných předpisů EU. |
| **SÚKL** | Státní ústav pro kontrolu léčiv. |
| **NCEZ** | Národní centrum elektronického zdravotnictví (MZ ČR). |
| **NÚKIB** | Národní úřad pro kybernetickou a informační bezpečnost. |
| **GDPR** | Nařízení (EU) 2016/679 o ochraně osobních údajů. |
| **DPIA** | Posouzení vlivu na ochranu osobních údajů (čl. 35 GDPR). |
| **ISMS** | Systém řízení bezpečnosti informací (dle ISO/IEC 27001). |
| **NIS2** | Směrnice (EU) 2022/2555 a navazující zákon o kybernetické bezpečnosti. |
| **RZPRO / ISZP** | Registr zdravotnických prostředků / Informační systém zdravotnických prostředků (SÚKL). |
| **DPO / pověřenec** | Pověřenec pro ochranu osobních údajů. |
| **THP** | Technicko-hospodářští pracovníci (provoz, administrativa, ekonomika, HR, právní, technika). |
| **„Vibe coding"** | Vývoj softwaru za vydatné asistence generativní AI, kdy člověk popisuje záměr přirozeným jazykem a AI generuje kód; pro účely této směrnice forma vývoje AI/SW (viz čl. 10). |
| **Lege artis** | Postup na náležité odborné úrovni. |
| **Black box** | AI řešení bez transparentního vnitřního fungování pro uživatele/provozovatele. |

---

## 4. Legislativní a normativní rámec

Tato směrnice je vázána zejména na následující předpisy a normy. Při jejich novelizaci se použije aktuální znění.

### 4.1 Přímo použitelné předpisy EU
- **Nařízení (EU) 2024/1689 (Akt o AI)** — horizontální regulace AI; kategorizace dle rizika, požadavky na vysoce rizikové systémy AI (kvalita dat, technická dokumentace, záznamy/logy, transparentnost, lidský dohled, přesnost, robustnost, kybernetická bezpečnost).
- **Nařízení (EU) 2017/745 (MDR)** a **Nařízení (EU) 2017/746 (IVDR)** — software/AI s určeným účelem zdravotnického prostředku.
- **Nařízení (EU) 2016/679 (GDPR)** — ochrana osobních údajů včetně zvláštní kategorie údajů o zdravotním stavu a pravidel pro předávání do třetích zemí.
- **Nařízení o horizontálních požadavcích na kybernetickou bezpečnost produktů s digitálními prvky (Cyber Resilience Act)** — pro produkty s digitálními prvky (např. EHR); povinnosti výrobců se předpokládají v náběhu (orientačně od r. 2027).

### 4.2 Právní předpisy ČR
- **Zákon č. 375/2022 Sb.**, o zdravotnických prostředcích a diagnostických zdravotnických prostředcích in vitro.
- **Zákon č. 372/2011 Sb.**, o zdravotních službách (zdravotnická dokumentace, práva pacienta, informovaný souhlas, lege artis).
- **Zákon č. 110/2019 Sb.**, o zpracování osobních údajů (adaptace GDPR).
- **Zákon o kybernetické bezpečnosti** (stávající č. 181/2014 Sb. a připravovaný nový zákon transponující NIS2) a navazující vyhlášky NÚKIB.
- **Zákon č. 89/2012 Sb.**, občanský zákoník (odpovědnost za škodu).
- **Zákon č. 268/2014 Sb.** (související předpisy ke ZP, v rozsahu dosud účinném).
- Připravovaný **zákon o správě (zdravotních) dat** — po nabytí účinnosti se zapracuje.

### 4.3 Technické normy a metodiky
- **ČSN EN ISO/IEC 27001** — systém řízení bezpečnosti informací (ISMS).
- **ISO 27799** — bezpečnost informací ve zdravotnictví.
- **ISO/IEC 82304-1** — bezpečnost zdravotnického softwaru / požadavky na bezpečnost produktu.
- **ISO 25237** — pseudonymizace/anonymizace zdravotních informací.
- **ISO/IEC 13485** — systém managementu kvality pro ZP (požadavek na výrobce/dodavatele).
- **ISO/IEC 14971** — řízení rizik zdravotnických prostředků.
- **ISO/IEC 42001** — systém managementu umělé inteligence (doporučeno pro dodavatele i poskytovatele).
- **Metodiky a FAQ MZ ČR / NCEZ** k AI a digitálním technologiím ve zdravotnictví; doporučení NÚKIB; stanoviska SÚKL.

---

## 5. Základní (kogentní) zásady používání AI

Následující zásady jsou **nepřekročitelné**. Jejich porušení je závažným porušením pracovních povinností.

5.1 **Primát pacienta a zdraví.** AI je vždy jen **podpůrný nástroj**. Konečné klinické rozhodnutí (diagnóza, léčba) vždy činí příslušný zdravotnický pracovník v kontextu celkového stavu pacienta a všech dostupných informací, postupem lege artis. AI nikdy nesmí samostatně a bez lidského dohledu rozhodovat o zdravotní péči.

5.2 **Zákonnost.** Jakékoli použití AI musí mít právní základ a být v souladu s GDPR, MDR/IVDR, AI Act, zákonem o zdravotních službách a zákonem o kybernetické bezpečnosti.

5.3 **Žádné necertifikované ZP v péči.** Pro poskytování zdravotní péče smí být použit **výhradně** AI systém, který má charakter ZP **s platným označením CE** (posouzenou shodou dle MDR/IVDR). Necertifikovaný AI systém (bez CE, nebo CE mimo určený účel) smí být v péči použit **pouze v rámci klinické zkoušky / studie funkční způsobilosti schválené SÚKL** (viz čl. 8 a 9). Porušení je sankcionováno pokutou až **30 mil. Kč** a vyvozením osobní odpovědnosti.

5.4 **Určený účel.** AI systém smí být používán výhradně k **určenému účelu** dle dokumentace výrobce. Použití mimo určený účel (off-label) je zakázáno mimo schválenou klinickou zkoušku.

5.5 **Lidský dohled (human oversight).** U každého AI systému musí být určen způsob lidského dohledu a zachována možnost člověka výstup přezkoumat, odmítnout a přepsat.

5.6 **Transparentnost.** Uživatelé musí být informováni, že pracují s AI; výstupy AI musí být v dokumentaci jednoznačně označitelné jako výstupy AI.

5.7 **Minimalizace dat.** Do AI systému se vkládá pouze nezbytně nutný rozsah údajů (princip data minimization). Přednostně se používají **anonymizovaná** data; pokud anonymizace není možná, pseudonymizovaná data s odpovídajícím právním základem.

5.8 **Zákaz vkládání pacientských/citlivých dat do neschválených nástrojů.** Vkládání pacientských, osobních nebo citlivých provozních dat do veřejných či neschválených AI nástrojů (zejména veřejných LLM) je **přísně zakázáno** (viz čl. 12).

5.9 **Dohledatelnost a logování.** Provoz AI systémů, které ovlivňují péči nebo zpracovávají osobní údaje, musí být logován tak, aby bylo možné zpětně rekonstruovat, jaký výstup byl vygenerován, kdy a kdo s ním pracoval.

5.10 **Přísnost vůči dodavatelům.** Žádný AI systém nesmí být nasazen bez splnění požadavků čl. 13. V pochybnostech platí princip předběžné opatrnosti — systém se nenasadí.

5.11 **Zákaz zakázaných praktik AI.** Je zakázáno pořizovat a provozovat AI systémy spadající mezi zakázané praktiky dle AI Act (např. nepřípustné scoringy, manipulativní techniky, nedovolené biometrické kategorizace). 

---

## 6. Řízení AI (governance), role a odpovědnosti

6.1 **Komise pro AI** (dále „Komise") je zřízena jako poradní a schvalovací orgán ředitele. Složení (minimálně):
- vedoucí lékař / náměstek pro léčebnou péči (předseda v klinických otázkách),
- pověřenec pro AI (garant směrnice),
- pověřenec pro ochranu osobních údajů (DPO),
- manažer kybernetické bezpečnosti / vedoucí IT,
- biomedicínský inženýr / správce zdravotnických prostředků,
- právník,
- zástupce vědy a výzkumu,
- dle potřeby zástupce etické komise a klinický farmaceut.

6.2 **Pravomoci Komise:**
- schvaluje/zamítá nasazení každého nového AI systému,
- vede a kontroluje **Registr AI systémů** (Příloha 1),
- posuzuje kategorizaci rizika dle čl. 7,
- schvaluje výjimky pouze v mezích zákona,
- iniciuje stažení/odstavení AI systému při riziku.

6.3 **Pověřenec pro AI** odpovídá za výklad a aktualizaci směrnice, sledování legislativy (MZ ČR/NCEZ, SÚKL, NÚKIB), metodickou podporu a koordinaci hodnocení rizik.

6.4 **DPO** odpovídá za soulad s GDPR, posuzuje nutnost a obsah DPIA a předávání dat (včetně do třetích zemí).

6.5 **Manažer kybernetické bezpečnosti** odpovídá za zařazení AI systému do ISMS, analýzu rizik, schválení síťového zapojení a dohled nad black-box řešeními.

6.6 **Správce ZP / biomedicínský inženýr** ověřuje status ZP, platnost CE, registraci v RZPRO/ISZP a vede evidenci ZP.

6.7 **Vedoucí pracovišť** odpovídají za to, že podřízení používají pouze schválené AI systémy a k určenému účelu.

6.8 **Každý uživatel** odpovídá za dodržování této směrnice, za správnou interpretaci výstupů AI a za to, že do AI nevkládá nepovolená data.

---

## 7. Klasifikace AI systémů a režimy použití

7.1 Před nasazením musí být každý AI systém klasifikován ve dvou osách:

**A) Dle vztahu ke zdravotnickému prostředku:**
- (ZP) AI s určeným účelem zdravotnického prostředku → režim MDR/IVDR (CE povinné);
- (ne-ZP) AI bez určeného účelu ZP (administrativa, provoz) → režim AI Act + GDPR + ISMS.

> Pozn.: I AI implementovaná jako modul NIS/PACS může být ZP. Rozhodující je **určený účel** modulu i celého systému; posuzuje se individuálně. Je-li účel modulu naplněním definice ZP, musí být posouzena shoda (modulu, nebo celého systému).

**B) Dle rizika dle AI Act:**
- nepřípustné riziko (zakázáno),
- **vysoce rizikové** (přísné požadavky: kvalita dat, dokumentace, logy, transparentnost, lidský dohled, přesnost, robustnost, kyberbezpečnost) — sem typicky spadá AI ovlivňující zdraví,
- omezené riziko (povinnost transparentnosti),
- minimální riziko.

7.2 Podle výsledku klasifikace se použije příslušný **režim použití**:

| Režim | Oblast | Článek |
|---|---|---|
| **A** | Zdravotní péče — diagnostika a léčba | 8 |
| **B** | Výzkum a klinické zkoušky | 9 |
| **C** | Vývoj AI a „vibe coding" | 10 |
| **D** | Provoz a administrativa (THP) | 11 |
| **E** | Generativní AI / LLM (průřezově) | 12 |

7.3 Jeden AI systém může spadat do více režimů; pak platí **nejpřísnější** z dotčených požadavků.

---

## 8. Režim A — AI ve zdravotní péči (diagnostika a léčba)

8.1 **Podmínka nasazení:** AI systém s charakterem ZP smí být v péči použit **pouze** pokud:
- a) nese **označení CE** a výrobce vydal **EU prohlášení o shodě** dle MDR/IVDR,
- b) je používán **k určenému účelu**,
- c) je ověřitelný v **RZPRO/ISZP** (popř. doloženo ES prohlášení o shodě, je-li systém z objektivních důvodů neuveden — typicky starší/zahraniční SW, IVD),
- d) splňuje požadavky dalších účinných předpisů (zejm. AI Act u vysoce rizikových systémů),
- e) prošel schvalovacím procesem dle čl. 18.

8.2 **Zákaz** použití necertifikovaného AI systému (bez CE, nebo s CE mimo určený účel) v reálné péči. Jediná výjimka = schválená klinická zkouška (čl. 9). Postih dle čl. 5.3 (pokuta až 30 mil. Kč).

8.3 **Klinická autonomie a lege artis.** Riziková třída ZP (např. IIa) **sama o sobě nezavazuje** lékaře řídit se výstupem AI. Lékař se řídí určeným účelem prostředku, léčebnými postupy a protokoly a vždy posuzuje celkový stav pacienta. **Konečnou diagnózu a léčbu určuje lékař.**

8.4 **Postup při rozporu AI vs. lékař.** Liší-li se výstup AI od úsudku lékaře, postupuje se dle čl. 17; vždy se pořídí řádný záznam zdůvodnění do zdravotnické dokumentace a v indikovaných případech se zajistí konzultace dalšího specialisty.

8.5 **Black-box řešení v péči.** AI fungující jako black box připojený do sítě nemocnice smí být nasazen pouze po posouzení manažerem kyberbezpečnosti (čl. 15) a musí u něj být doloženy požadavky na přesnost, spolehlivost a kyberbezpečnost po celý životní cyklus (AI Act, MDR/IVDR).

8.6 **Validace a verifikace.** Před nasazením do klinické praxe musí být doložena posouzená shoda (CE) a — kde je to relevantní — lokální verifikace funkčnosti v prostředí poskytovatele (vstupní data, integrace, výkonnost). Výsledky se zaznamenají do Registru AI.

8.7 **Monitoring po nasazení.** Pracoviště průběžně sleduje výkonnost a bezpečnost AI; podezření na vadu/nežádoucí příhodu hlásí dle čl. 20 a v režimu vigilance ZP (SÚKL).

---

## 9. Režim B — AI ve výzkumu a klinických zkouškách

9.1 **Použití necertifikovaného AI ZP k diagnostice/péči je možné výhradně v rámci klinické zkoušky / studie funkční způsobilosti povolené SÚKL.**

9.2 **Informovaný souhlas:** Pacient musí udělit **písemný informovaný souhlas**, jehož text je **schválen SÚKL** spolu s dokumentací klinické zkoušky. Zkouška smí probíhat jen, je-li povolena.

9.3 **Etická komise:** Etická hlediska posuzuje příslušná etická komise; bez jejího kladného stanoviska se zkouška nezahájí.

9.4 **Bezpečnost:** Za bezpečnost výrobku odpovídá výrobce; bezpečnost použití v rámci zkoušky posuzuje SÚKL (preklinické/klinické údaje, poměr přínos/riziko). Požadavky na bezpečné, důvěryhodné a etické AI řeší AI Act.

9.5 **Poskytování dat externím subjektům pro výzkum/vývoj:**
- a) **Preferovaná cesta = anonymizovaná data** (nepožívají ochrany, není třeba souhlas pacienta), při dodržení ISO 25237 a posouzení reziduálního rizika rozpoznatelnosti;
- b) jinak je **nezbytný souhlas pacienta**, resp. jiný zákonný titul;
- c) každé poskytnutí dat schvaluje DPO a Komise; uzavírá se smlouva vymezující účel, rozsah, dobu, zabezpečení a zákaz reidentifikace;
- d) po nabytí účinnosti zákona o správě dat se doplní další přípustné varianty přístupu.

9.6 **Reziduální riziko anonymizace:** Vždy se hodnotí kvalita a účinnost anonymizace a dostupnost „dodatečných informací" u příjemce, které by umožnily zpětnou identifikaci. Při nezanedbatelném riziku se data neposkytnou.

9.7 Veškeré výzkumné použití se eviduje v Registru AI a v evidenci výzkumných projektů.

---

## 10. Režim C — Vývoj AI a „vibe coding"

10.1 **Působnost:** Vlastní vývoj AI/SW poskytovatelem, společný vývoj s partnery a vývoj s asistencí generativní AI („vibe coding").

10.2 **Klíčové pravidlo statusu ZP:** Vyvíjí-li se SW/AI, jehož **určený účel naplní definici ZP**, vztahují se na něj MDR/IVDR a takový SW **nesmí být použit v reálné péči bez posouzení shody (CE)**; do té doby smí být ověřován pouze v rámci klinické zkoušky (čl. 9). Vývojový stav ≠ povolení k použití v péči.

10.3 **Data ve vývoji a testování:**
- pro vývoj/testování se primárně používají **anonymizovaná nebo syntetická data**;
- použití reálných pacientských dat vyžaduje právní titul, DPIA a souhlas DPO;
- vývojová a testovací prostředí musí být oddělena od produkce a zabezpečena dle ISMS.

10.4 **„Vibe coding" — zvláštní pravidla:**
- a) **Žádná reálná pacientská/osobní/citlivá data, tajemství ani bezpečnostní konfigurace se nesmí vkládat do generativních AI nástrojů**, které nejsou schváleny Komisí a smluvně ošetřeny (viz čl. 12 a 13);
- b) veškerý AI-generovaný kód podléhá **povinnému lidskému review**, bezpečnostnímu přezkumu (SAST/DAST, kontrola závislostí), licenční kontrole a testování před nasazením;
- c) za AI-generovaný kód a jeho důsledky **odpovídá vývojář a poskytovatel jako autor díla** — odpovědnost nelze přenést na nástroj;
- d) musí být vedena evidence, které části kódu vznikly za asistence AI, jaký nástroj a verze byly použity (kvůli auditu a licencím);
- e) generativní AI **nesmí** být použita k vygenerování produkčního klinického rozhodovacího kódu, který by obešel režim ZP (čl. 8) — takový výstup by byl nelegálním necertifikovaným ZP.

10.5 **Bezpečný vývojový životní cyklus (SDLC):** Pro vyvíjený SW/AI se uplatní řízení rizik (ISO 14971), požadavky na bezpečnost zdravotnického SW (ISO 82304-1), QMS (ISO 13485, je-li ZP), a u AI doporučeně ISO/IEC 42001. Dokumentace, datasety a logy musí splňovat požadavky AI Act na vysoce rizikové systémy, pokud do této kategorie spadají.

10.6 **Uvedení vlastního AI na trh / do provozu jako ZP:** Pokud by poskytovatel vyvinul a chtěl provozovat vlastní AI naplňující definici ZP, vstupuje do role **výrobce** se všemi povinnostmi MDR/IVDR a AI Act (včetně posouzení shody, technické dokumentace, řízení rizik a post-market surveillance). Tento krok schvaluje výhradně ředitel na návrh Komise po právním posouzení.

---

## 11. Režim D — Provozní a administrativní AI (THP zaměstnanci)

11.1 **Působnost:** AI pro administrativu, ekonomiku, HR, nákup, logistiku, správu budov, plánování, reporting, právní agendu, dokumentové zpracování apod. (typicky **ne-ZP**, často nižší riziko dle AI Act).

11.2 **I provozní AI podléhá schválení** Komisí (zjednodušený režim dle čl. 18) a evidenci v Registru AI.

11.3 **Ochrana dat:** I administrativní AI běžně zpracovává osobní údaje (zaměstnanci, pacienti v ekonomické/správní agendě). Platí GDPR, minimalizace dat, DPIA tam, kde je třeba, a zákaz vkládání citlivých dat do neschválených nástrojů.

11.4 **Personální rozhodnutí:** AI nesmí být jediným základem rozhodnutí s právními účinky vůči osobám (např. výběr/hodnocení zaměstnanců) bez lidského posouzení; respektuje se čl. 22 GDPR (automatizované rozhodování) a relevantní povinnosti AI Act (vysoce rizikové oblasti zaměstnanosti).

11.5 **Zákaz „stínové AI":** Zaměstnanci THP nesmí pořizovat ani používat neschválené AI nástroje (včetně bezplatných online služeb) pro pracovní agendu s daty poskytovatele.

11.6 **Transparentnost vůči adresátům:** Komunikuje-li AI navenek (např. chatbot), musí být zřejmé, že jde o AI.

---

## 12. Režim E — Generativní AI a velké jazykové modely (LLM)

12.1 Tento režim platí **průřezově** pro jakékoli použití generativní AI / LLM ve všech ostatních režimech a má **přednost svou přísností**.

12.2 **Absolutní zákazy:**
- vkládání pacientských, osobních, zdravotních a citlivých provozních dat, přístupových údajů, klíčů, neanonymizovaných snímků či dokumentace do **veřejných / neschválených** generativních AI nástrojů;
- spoléhání na výstup generativní AI jako na klinické rozhodnutí bez ověření kvalifikovaným pracovníkem;
- vydávání AI-generovaného obsahu za ověřený bez kontroly (riziko „halucinací").

12.3 **Povolené použití** generativní AI je možné pouze:
- s nástroji **schválenými Komisí**, provozovanými v režimu, který smluvně vylučuje trénink na vložených datech a zaručuje lokalizaci/zpracování dat v souladu s GDPR;
- pro účely, kde nedochází ke zpracování nepovolených dat (např. obecné texty, šablony, návrhy bez citlivého obsahu);
- s povinným lidským ověřením výstupu před použitím.

12.4 **Označování:** Generativní AI obsah určený pro pacienty nebo úřední komunikaci musí být zkontrolován a, kde to vyžaduje AI Act (transparentnost, deepfake/syntetický obsah), odpovídajícím způsobem označen.

12.5 **Klinické LLM** (např. asistent pro dokumentaci) jsou-li ZP, podléhají režimu A; jinak režimu D + tomuto článku, vždy s lidským dohledem.

---

## 13. Požadavky na dodavatele (přísný režim)

> Tento článek je **kogentní**. Bez splnění všech relevantních bodů nesmí být dodavatel vybrán ani AI systém nasazen. V pochybnostech se uplatní **princip předběžné opatrnosti** — nenasazovat.

13.1 **Doklady o shodě a statusu ZP (je-li ZP):**
- a) platné **označení CE** a **EU/ES prohlášení o shodě** dle MDR/IVDR;
- b) **certifikát** vydaný oznámeným subjektem (u tříd IIa a vyšší);
- c) **návod v českém jazyce** (povinné dodání distributorem); na vyžádání prohlášení o shodě a certifikát;
- d) doložení **registrace v RZPRO/ISZP** (nebo zdůvodnění výjimky + ES prohlášení o shodě);
- e) jasně definovaný **určený účel** a riziková třída.

13.2 **Soulad s AI Act:**
- klasifikace systému dle rizika; u **vysoce rizikových** systémů doložení splnění požadavků (kvalita dat, technická dokumentace, vedení logů, transparentnost a informace pro uživatele, lidský dohled, přesnost, robustnost, kyberbezpečnost);
- u generativní AI doložení opatření proti manipulaci s tréninkovými/vstupními daty.

13.3 **Kybernetická bezpečnost dodavatele (přísně):**
- a) platný certifikát **ISO/IEC 27001** **výrobce i dodavatele**; v rozsahu certifikace musí být **explicitně zahrnut vývoj a nasazování SW** (ověřit, že nebyly vyňaty);
- b) soulad s **ISO 27799** (zdravotnictví);
- c) u zdravotnického SW soulad s **ISO 82304-1**; u ZP **ISO 13485** a **ISO 14971**;
- d) pro anonymizaci/pseudonymizaci **ISO 25237**;
- e) doporučeně **ISO/IEC 42001** (management AI);
- f) doložení opatření proti kybernetickým útokům po celý životní cyklus (za bezpečnost a účinnost ZP nese plnou odpovědnost výrobce).

13.4 **Ochrana dat (smluvně):**
- a) **smlouva o zpracování osobních údajů** dle čl. 28 GDPR, pokud dodavatel zpracovává osobní údaje;
- b) jasné vymezení **lokality zpracování a uložení dat**; přenos do **třetích zemí** (mimo EU/EHP) jen při splnění kap. V GDPR (rozhodnutí o odpovídající ochraně / standardní smluvní doložky + posouzení) a po schválení DPO;
- c) **zákaz tréninku** modelů na datech poskytovatele bez výslovného právního titulu a souhlasu;
- d) princip **minimalizace dat** a šifrování při přenosu i uložení.

13.5 **Odpovědnost a záruky (přísně):**
- a) smluvní převzetí **odpovědnosti výrobce za pravdivost/účinnost** a za vady prostředku;
- b) **pojištění odpovědnosti** v adekvátní výši;
- c) **SLA** (dostupnost, doba reakce, řešení incidentů, bezpečnostní aktualizace);
- d) povinnost **hlásit bezpečnostní incidenty a nežádoucí příhody** poskytovateli bez zbytečného odkladu;
- e) **právo na audit** dodavatele poskytovatelem nebo třetí stranou;
- f) ujednání o **exit strategii**, přenositelnosti a bezpečném výmazu/vrácení dat po ukončení;
- g) doložení **transparentnosti** modelu v rozsahu nezbytném pro lidský dohled (zejm. u black-box řešení).

13.6 **Subdodavatelé:** Dodavatel ručí za soulad všech subdodavatelů (včetně poskytovatelů cloudu a modelů) s touto směrnicí; změny subdodavatelů podléhají souhlasu.

13.7 **Akceptační kritéria:** Splnění bodů 13.1–13.6 se vyhodnotí pomocí **Přílohy 2 (Dotazník/akceptační checklist dodavatele)**; výsledek schvaluje Komise.

---

## 14. Ochrana osobních a zdravotních dat

14.1 Údaje o zdravotním stavu jsou **zvláštní kategorií** osobních údajů (čl. 9 GDPR) s nejvyšší úrovní ochrany.

14.2 **Právní titul** zpracování musí být určen před zahájením; pro každé nasazení AI zpracovávající osobní údaje se posoudí nutnost **DPIA** (čl. 35 GDPR) — u vysoce rizikových AI je DPIA zpravidla povinná.

14.3 **Anonymizace/pseudonymizace** dle ISO 25237; preferuje se anonymizace. Hodnotí se reziduální riziko reidentifikace.

14.4 **Minimalizace** — vkládá se jen nezbytný set údajů k zajištění funkčnosti.

14.5 **Přenosy do třetích zemí (např. USA, Čína, Indie):**
- přípustné jen při dodržení kap. V GDPR a po schválení DPO;
- i u anonymizovaných dat se hodnotí kvalita anonymizace a riziko zpětné identifikace;
- na úrovni ISMS musí být pro takové transakce zaveden rámec informační bezpečnosti.

14.6 **Práva subjektů údajů** (přístup, oprava, výmaz aj.) musí zůstat zajištěna i při použití AI.

14.7 **Zdravotnická dokumentace:** AI-generované výstupy zařazené do dokumentace podléhají právu pacienta na informace a přístup dle zákona o zdravotních službách (viz čl. 16).

---

## 15. Kybernetická bezpečnost

15.1 Každý AI systém se **zařadí do ISMS** poskytovatele (ISO/IEC 27001, ISO 27799) a podrobí **analýze rizik** na úrovni celého systému; rizika se vyčíslí, posoudí a minimalizují technickými a administrativními opatřeními na přijatelnou úroveň, popř. přenesou na jiné subjekty.

15.2 Politika informační bezpečnosti se **neomezuje pouze na pacientská data**, ale komplexně na všechna informační aktiva.

15.3 **NIS2 / zákon o kybernetické bezpečnosti:** Poskytovatel zdravotních služeb spadá mezi subjekty kritické pro společnost; uplatní se povinnosti dle nového zákona o kybernetické bezpečnosti a vyhlášek NÚKIB, včetně řízení bezpečnosti dodavatelského řetězce a hlášení incidentů.

15.4 **Black-box AI v síti:** Připojení black-box AI vyžaduje doložení přesnosti, spolehlivosti a kyberbezpečnosti (AI Act), segmentaci sítě, řízení přístupů, monitoring a opatření proti manipulaci se vstupy/daty.

15.5 **Produkty s digitálními prvky / EHR:** Po nabytí účinnosti nařízení o horizontálních požadavcích na kyberbezpečnost (Cyber Resilience Act, orientačně od 2027) budou tyto produkty muset nést CE a splňovat základní požadavky; dodavatelé musí prokázat shodu.

15.6 **Hrozby a opatření:** Seznam hrozeb se vytváří v kontextu organizace (lze využít materiály NÚKIB); zahrnuje útoky, ale i fyzické hrozby (požár, zaplavení) a zneužití identity. Pro každou hrozbu se volí technická i administrativní opatření.

15.7 **Kryptografie:** Šifrování dat v přenosu i klidu. Kvantově odolné šifrování není v horizontu 5–10 let kritickou nutností, garant však sleduje vývoj a v případě posunu hrozby zajistí migraci.

---

## 16. Informovaný souhlas a práva pacienta

16.1 Použití **necertifikovaného AI ZP** k diagnostice/léčbě (v rámci klinické zkoušky) **vyžaduje písemný informovaný souhlas** schválený SÚKL (čl. 9).

16.2 U **certifikovaného AI** jako podpůrného nástroje české právo explicitně neukládá zvláštní povinnost informovat o použití AI v informovaném souhlasu; **jako dobrá praxe** se však doporučuje pacienta informovat, že AI je **pouze pomocný nástroj** a konečné rozhodnutí činí lékař. Poskytovatel tuto dobrou praxi tímto **zavádí jako standard** a zařazuje informaci o využití AI do informovaných souhlasů tam, kde je AI relevantně využita.

16.3 **Přístup k dokumentaci:** Pacient má právo na veškeré informace shromážděné ve zdravotnické dokumentaci. Jsou-li AI-označené snímky/výstupy součástí dokumentace, má k nim pacient na vyžádání přístup.

16.4 **Komunikace s pacientem** o AI musí být srozumitelná, nezavádějící a zdůrazňovat odpovědnost lékaře.

---

## 17. Odpovědnost, dokumentace a řešení rozporu AI vs. člověk

17.1 **Odpovědnost za prostředek:** Za pravdivost vyhodnocení, bezpečnost a účinnost AI ZP nese **plnou odpovědnost výrobce**.

17.2 **Klinická odpovědnost:** Konečnou odpovědnost za diagnostické a léčebné rozhodnutí nese **lékař** (nikoli AI systém); rozhodující je postup lege artis.

17.3 **Postup při rozporu (AI pozitivní × lékař negativní a obráceně):** Pro ochranu pacienta i poskytovatele se vždy:
1. zajistí **řádná dokumentace rozhodovacího procesu** lékaře včetně **zdůvodnění**, proč byl výstup AI vyhodnocen jinak;
2. uplatní **interní postup pro rozpory**, včetně možnosti **konzultace dalšího specialisty**;
3. pacient **informuje** o tom, že AI je pouze podpůrný nástroj;
4. zajistí, že lékaři jsou **proškoleni** v používání AI i v interpretaci výsledků.

17.4 **Důkazní hodnota AI:** Výstup AI může být v řízení posuzován jako jeden z podkladů rozhodnutí lékaře; pro posouzení správnosti postupu se standardně vyžaduje **znalecký posudek** nezávislého odborníka. Soud hodnotí důkazy ve vzájemné souvislosti a klíčové je, zda lékař postupoval lege artis.

17.5 **Vývoj odpovědnostního rámce:** Pravidla odpovědnosti za AI se na úrovni EU dále formují (připravovaná směrnice o odpovědnosti za AI); garant sleduje vývoj a směrnici aktualizuje.

17.6 **Logování pro účely odpovědnosti:** U AI ovlivňující péči musí být dohledatelné, jaký výstup, kdy a komu byl poskytnut a jak s ním bylo naloženo.

---

## 18. Schvalovací proces a registr AI systémů

18.1 **Žádný AI systém nesmí být nasazen bez schválení.** Žadatel (vedoucí pracoviště / projektu) podá **Žádost o schválení AI** (Příloha 3).

18.2 **Kroky schválení:**
1. **Klasifikace** (čl. 7): ZP/ne-ZP a riziko dle AI Act.
2. **Posouzení dodavatele** (čl. 13, Příloha 2).
3. **Posouzení ochrany dat** (DPO): právní titul, DPIA, přenosy.
4. **Posouzení kyberbezpečnosti** (manažer KB): zařazení do ISMS, analýza rizik, síťové zapojení.
5. **Klinické posouzení** (u režimu A/B): účel, validace, protokol, etická komise/SÚKL kde je třeba.
6. **Právní posouzení**: smlouvy, odpovědnost, pojištění.
7. **Rozhodnutí Komise**: schválit / podmínečně / zamítnout.
8. **Zápis do Registru AI** (Příloha 1) a stanovení odpovědné osoby a monitoringu.

18.3 **Zjednodušený režim** lze uplatnit u jednoznačně ne-ZP, nízkorizikové provozní AI nezpracovávající citlivá data; i tak je nutná evidence v Registru AI a souhlas DPO, pokud jsou zpracovávány osobní údaje.

18.4 **Periodická revize** každého zapsaného systému min. 1× ročně a při změně účelu, verze, dodavatele nebo legislativy.

18.5 **Odstavení:** Komise nařídí okamžité odstavení AI systému při zjištění rizika pro pacienta, ztrátě CE/shody, závažném incidentu nebo porušení této směrnice.

---

## 19. Vzdělávání a kompetence

19.1 Každý uživatel AI musí být **proškolen** před prvním použitím: rozsah dle role (klinický uživatel, vývojář, THP, administrátor).

19.2 Klinické školení zahrnuje **používání AI i interpretaci výstupů** a postup při rozporu (čl. 17).

19.3 Školení o ochraně dat a kyberbezpečnosti je povinné a opakuje se min. 1× ročně.

19.4 O školeních se vede evidence; bez doloženého školení nesmí pracovník daný AI systém používat.

---

## 20. Kontrola, audit, hlášení incidentů a sankce

20.1 **Kontrola** dodržování směrnice provádí Komise a vedoucí pracovišť průběžně; interní audit min. 1× ročně.

20.2 **Hlášení incidentů a nežádoucích příhod:**
- bezpečnostní incidenty → manažer KB (a NÚKIB dle zákona o KB);
- nežádoucí příhody ZP / podezření na vadu → správce ZP a **SÚKL** (vigilance);
- porušení ochrany osobních údajů → DPO (a Úřad pro ochranu osobních údajů ve lhůtě dle GDPR);
- každé hlášení se eviduje a vyhodnocuje.

20.3 **Sankce a postih:**
- použití necertifikovaného AI ZP mimo klinickou zkoušku — riziko **pokuty až 30 mil. Kč** pro poskytovatele a vyvození odpovědnosti vůči odpovědné osobě;
- porušení směrnice je posuzováno jako porušení pracovních povinností se všemi pracovněprávními důsledky;
- tím nejsou dotčeny případné správní, občanskoprávní a trestní následky.

20.4 **Princip předběžné opatrnosti:** Při pochybnostech o souladu, bezpečnosti nebo důvěryhodnosti se AI systém nenasadí, resp. se odstaví.

---

## 21. Přechodná a závěrečná ustanovení

21.1 **Inventarizace stávajících AI:** Do [např. 60 dnů] od účinnosti provedou vedoucí pracovišť soupis všech používaných AI systémů a předají jej Komisi k zařazení do Registru AI a posouzení. AI systémy, které neprojdou posouzením, budou odstaveny.

21.2 **Aktualizace:** Garant sleduje vývoj legislativy (AI Act a jeho prováděcí akty, nový zákon o KB/NIS2, Cyber Resilience Act, zákon o správě dat, směrnice o odpovědnosti za AI, metodiky MZ ČR/NCEZ, SÚKL, NÚKIB) a směrnici aktualizuje bez zbytečného odkladu.

21.3 **Výklad:** Závazný výklad podává garant; sporné otázky řeší Komise. V případě rozporu směrnice se zákonem platí zákon.

21.4 **Účinnost:** Tato směrnice nabývá účinnosti dnem [DD. MM. RRRR].

21.5 **Zrušovací ustanovení:** Touto směrnicí se ruší [dřívější úprava, pokud existuje].

---

## 22. Přílohy

- **Příloha 1** — Registr AI systémů (`prilohy/Priloha-1_Registr-AI-systemu.md`)
- **Příloha 2** — Akceptační checklist / dotazník dodavatele (`prilohy/Priloha-2_Checklist-dodavatele.md`)
- **Příloha 3** — Žádost o schválení nasazení AI (`prilohy/Priloha-3_Zadost-o-schvaleni-AI.md`)
- **Příloha 4** — Klasifikační rozhodovací strom (ZP / riziko dle AI Act) (`prilohy/Priloha-4_Klasifikacni-strom.md`)

---

*Dokument je interním řídicím aktem poskytovatele. Slouží k zajištění souladu s legislativou; nenahrazuje právní posouzení konkrétního případu, které je v případě nejasností nutné provést individuálně s ohledem na kontext.*
