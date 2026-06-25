# Příloha 4 — Klasifikační rozhodovací strom

Pomůcka k zařazení AI systému dle čl. 7 směrnice SM-AI-01. Výstupem je režim použití a soubor povinností. V pochybnostech rozhoduje Komise pro AI; platí nejpřísnější dotčený režim.

## Krok 1 — Zakázané praktiky (AI Act)

> Spadá systém mezi **zakázané praktiky** dle AI Act?
> - **ANO →** STOP. Pořízení/provoz **zakázán**.
> - **NE →** pokračuj na Krok 2.

## Krok 2 — Je to zdravotnický prostředek?

> Naplňuje **určený účel** definici ZP dle MDR/IVDR (diagnostika, prevence, monitorování, predikce, prognóza, léčba, zmírnění nemoci…)?
> - **ANO →** režim **ZP** (pokračuj Krok 3).
> - **NE →** režim **ne-ZP** (pokračuj Krok 5).

## Krok 3 — Má ZP platné CE?

> Má AI ZP **označení CE** + prohlášení o shodě a (třída IIa+) certifikát oznámeného subjektu?
> - **ANO →** lze použít v péči k **určenému účelu** → **Režim A** (čl. 8). Ověřit RZPRO/ISZP, validace, lidský dohled, ISMS.
> - **NE →** nelze použít v běžné péči. Použití jen v **Režimu B** (čl. 9): klinická zkouška povolená SÚKL + etická komise + písemný informovaný souhlas schválený SÚKL. Jinak STOP (hrozí pokuta až 30 mil. Kč).

## Krok 4 — Vyvíjíme / upravujeme AI sami?

> Jde o **vlastní vývoj** nebo „vibe coding"?
> - **ANO →** **Režim C** (čl. 10). Pozor: pokud vyvíjené AI naplní definici ZP, **nesmí do péče bez CE** (jinak Režim B). Reálná data jen s titulem + DPIA; AI-generovaný kód = povinné lidské review a bezpečnostní přezkum.

## Krok 5 — Riziko dle AI Act (ne-ZP)

> Zařaď systém:
> - **Vysoce rizikový** (např. zaměstnanost/HR, kritická infrastruktura) → plné požadavky AI Act (data, dokumentace, logy, transparentnost, lidský dohled, přesnost, robustnost, kyberbezpečnost) → **Režim D** v přísné podobě.
> - **Omezené riziko** → povinnost transparentnosti (uživatel ví, že jde o AI) → **Režim D**.
> - **Minimální riziko** → **Režim D** ve zjednodušeném schválení (čl. 18.3).

## Krok 6 — Používá se generativní AI / LLM?

> Používá se v jakémkoli režimu **generativní AI / LLM**?
> - **ANO →** navíc se uplatní **Režim E** (čl. 12): zákaz vkládání citlivých/pacientských dat do neschválených nástrojů, povinné lidské ověření výstupu, jen schválené nástroje bez tréninku na datech.

## Krok 7 — Společné povinnosti (vždy)

Pro **každý** nasazovaný systém bez ohledu na režim:
1. Posouzení dodavatele (čl. 13, Příloha 2).
2. Ochrana dat: právní titul, minimalizace, DPIA dle potřeby, řešení přenosů do třetích zemí (čl. 14).
3. Zařazení do ISMS a analýza rizik (čl. 15).
4. Lidský dohled a logování (čl. 5, 17).
5. Schválení Komisí a zápis do Registru AI (čl. 18, Příloha 1).
6. Školení uživatelů (čl. 19).
7. Periodická revize a hlášení incidentů (čl. 20).

---

### Rychlá tabulka

| Otázka | ANO | NE |
|---|---|---|
| Zakázaná praktika AI Act? | STOP (zákaz) | dál |
| Je to ZP? | Krok 3 | Krok 5 |
| ZP má CE? | Režim A | Režim B (klinická zkouška) nebo STOP |
| Vlastní vývoj / vibe coding? | Režim C (+ pozor na ZP) | — |
| Generativní AI / LLM? | + Režim E | — |
