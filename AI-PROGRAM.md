---
owner: Vitar
category: Projects
status: active
created: 2026-03-16
version: "4.0"
---

# AI @ VITAR — Program

> Tvůj průvodce AI implementací ve VITARu. 7 modulů, konkrétní kroky, žádná teorie.

**Zdroj:** Meeting AI Governance 11.3.2026 (Tomáš, Radim, Juraj, Daniel, Karolína, Radovan) + deep research EU best practices (McKinsey, Eurostat, OECD, OpenAI).

---

## Přehled modulů

| # | Modul | Obsah |
|---|-------|-------|
| 1 | AI Mindset | Proč musíme šlapat. GymBeam, EU data, modely adopce |
| 2 | Nástroje & Hardware | Cursor, Claude Code, GitHub, Vercel, Railway + trial strategie |
| 3 | Dvě kategorie | Co smíte volně, co musí projít procesem |
| 4 | Release proces & GitHub | 3-fázová metodika (Alfa → Beta → Live), GitHub pravidla |
| 5 | Lidé & role | Kdo co dělá. Kde se učit |
| 6 | Jak začít | Schvalovací flow, Teams kanál, rituály |
| 7 | Plán & budget | Kickoff → Weekly AI Committee → iterace. Budget |

---

## Modul 1: AI Mindset

**Nestačí být AI-curious. Musíme být AI-first. A musíme začít teď.**

### ⚠️ Kde jsme vs. kde bychom měli být

Absolvovali jsme kurzy. Máme licence. Ale **reálně AI používá pár lidí, pár hodin týdně, na pár věcí.** To nestačí.

**GymBeam má 2 OpenClaw boty**, které jim autonomně vymýšlejí produkty. Konkurence neřeší, jestli „má smysl používat Cursor" — oni už mají AI agenty, kteří pracují 24/7.

My se pořád bavíme o tom, **jestli** — oni už řeší **jak škálovat**. Ten gap se každý měsíc zvětšuje.

### ❌ Co děláme teď (a nestačí to)

Otevřít ChatGPT → zkopírovat text → dostat odpověď → zkopírovat zpátky → ručně opravit. Kurzy proběhly, ale nedaly lidem **nástroje v ruce** — daly jim teorii. Výsledek: „AI je fajn, ale nic zásadního."

### ✅ AI-first mindset

AI vidí přímo vaše soubory. Řeknete *„Udělej z tohohle report"* — a ona to udělá. AI není doplněk workflow. **AI je workflow.** Každý nový úkol začíná otázkou: „Jak to udělá AI?" Ne: „Mám na to čas?"

### Hledáme Power Users

Nepotřebujeme, aby 100 lidí používalo ChatGPT na emaily. Potřebujeme **5–10 lidí, kteří budou v AI žít** — buildovat, zkoušet, lámat věci, ukazovat ostatním. Lidé, kteří sami chtějí. Ne ti, které musíme přesvědčovat. Pokud jsi ten člověk — ozvi se.

### Klíčová výzva: přenést mindset na tým

Máme v týmu lidi, kteří AI zvládají na úrovni. Ale **největší výzva není technická zdatnost jednoho člověka — je to přenést tento mindset na celý tým.** Klíč k růstu leží v tom, aby tým adoptoval AI **stejně intenzivně**. Ne jeden člověk, který builduje za všechny — ale dvacet lidí, kteří AI používají denně ve svém workflow.

### Jak to dělají firmy v EU

*Z deep research: „Škálování AI adopce v SMB firmách 70–100 zaměstnanců v Evropě" (Eurostat 2025, McKinsey, OECD, OpenAI leadership guide).*

#### GymBeam (SK/CZ, ~500 zaměstnanců)
2 OpenClaw boty, které autonomně vymýšlejí produkty. AI není doplněk — je to core business proces. Začínali stejně jako my. Dnes mají AI agenty pracující 24/7.

#### Model 1: Hub-and-Spoke pro SMB (McKinsey)
Pro firmu 70–100 lidí nejlepší default. McKinsey ukazuje, že governance a risk bývají centralizované, zatímco adopce use-casů funguje hybridně.

- **Hub (2–4 lidi):** CEO sponsor, AI owner, IT/data owner. Řeší: policy, schválené nástroje, bezpečnost, přístup k datům, KPI.
- **Spokes (5–7 championů):** 1 champion v sales, CS, finance, operations, marketing, HR. Redesign workflow + adoption v týmu.

> ⚠️ **Kdy selhává:** Když hub sklouzne do „AI policie" a business týmy nemají ownership nad workflow.

#### Model 2: BSP-first — nejdřív podpůrné procesy (EU komise)
Evropská komise přímo říká: AI v business support procesech vytváří dovednosti, governance a důvěru potřebné k tomu, aby se AI později rozšířila do core operations. **Nejdřív transformuj podpůrné procesy, teprve potom core.**

Kde začít: Customer support · Sales admin & nabídky · Finance & faktury · HR & onboarding · Marketing & content · Knowledge management

70 % procesů neznamená 70 % plně automatizovaných. Znamená, že AI je embedded ve většině workflow jako **copilot, classifier, summarizer, router, knowledge layer nebo QA layer**.

#### Model 3: Fluency → Workflow → Agents (OpenAI)
Firmy, které se posouvají nejrychleji, nejdou od pilotu k pilotu, ale od fluency k workflow integraci a pak teprve k agentům. Spousta SMB chce skočit rovnou do agentů. **To je chyba.**

| Fáze | Popis | Status |
|------|-------|--------|
| **1. Fluency** | Každý zaměstnanec umí AI použít pro svou práci | ← JSME ZDE |
| **2. Workflow** | Top workflow zabudované do standardních nástrojů a SOP | |
| **3. Agents** | Vybrané procesy agentizované s human-in-the-loop | |

> **Bez fluency a governance se agenti mění na drahé demo.** Nejdřív musí lidi umět, pak teprve automatizovat.

#### Model 4: Top-down cíl + Bottom-up use cases (OpenAI leadership guide)
OpenAI doporučuje nastavit company-wide AI adoption goal navázaný na každodenní práci a KPI. Pět principů: **Align, Activate, Amplify, Accelerate, Govern.**

- ⬇️ **Top-down:** Vedení řekne, proč AI souvisí s růstem, marží, rychlostí a kvalitou.
- ⬆️ **Bottom-up:** Týmy sbírají konkrétní use cases a redesignují workflow.
- ↔️ **Middle-out:** Champions překládají strategii do denní praxe.

> **Bez top-down cíle vznikne chaos. Bez bottom-up návrhů vznikne powerpoint.**

#### Model 5: Use-case portfolio (McKinsey + OpenAI)
Ne jeden monolitický AI program, ale portfolio value models. Firmy, které z AI dostávají nejvíc, ji neřídí jako sérii odtržených pilotů.

- 🟢 **Quick wins:** meeting notes, search, summarizace, drafting — *máme*
- 🔵 **Unit economics:** rychlejší nabídky, méně manuálních hodin, support deflection
- 🟣 **Data leverage:** AI nad CRM/ERP/helpdesk/knowledge base
- 🟠 **Strategic reinvention:** nové produkty/služby, self-service — *sem míříme*

### 7 znaků firem, které jsou nejdál

1. **CEO sponsor a jasné „proč teď"** — bez přímého leadership signálu adopce zůstává u pár nadšenců ✅ máme (Tomáš)
2. **Jedna lehká governance vrstva** — ne enterprise board; stačí policy, approved tools, citlivá data, logging, evals ⚡ budujeme
3. **Start v business support procesech** — EU: právě to vytváří základ pro širší transformaci ✅ děláme
4. **Champions network** — 1 provozní tahoun na tým, ne školitel na plný úvazek ⚡ identifikujeme
5. **Měření adopce i hodnoty** — ne jen počet licencí: WAU, % týmů se 3+ AI workflow, hodinová úspora, cycle time, first-pass quality
6. **Standardizace** — nejdřív manuální prompty, pak reusable playbooky, až potom automatizace
7. **Human-in-the-loop** u všeho s obchodním, právním nebo reputačním dopadem — zejména v EU regulatorním prostředí

### Evropská data (Eurostat 2025)

| Segment | AI adopce |
|---------|-----------|
| Všechny podniky v EU | 20% |
| Střední firmy | 30% |
| Velké firmy | 55% |

Firmy, které se dostanou k plošnější adopci, jsou pořád **menšina**. Největší příležitost je ve středně velkých firmách — dost procesní struktury, ale ještě ne enterprise složitost. **To jsme my. Teď potřebujeme exekuci.**

### Co už dnes funguje

| Projekt | Úspora |
|---------|--------|
| HTML prezentace pro retail — Intersport cenník | 30 min vs. 2 dny |
| 126 bannerů — outlet kampaň CZ+SK | 2h vs. 3 dny |
| Produktové karty e-shop — SEO, HTML | 4h vs. 2 dny |
| Prospector — 5 464 B2B kontaktů, dashboard | MVP live |

### Projekty v buildu

- **PRIORITA 1: Kalkulačka vývoje** — Webová app, obchodník zadá parametry, dostane cenu. Aktuálně v Lovable, rozhodnutí: pokračovat nebo migrovat do Cursoru.
- **PRIORITA 2: Vzorky app** — Formulář → admin view → PDF pro sklad. Analýza v Miro (Karolína). Potřeba 2–3 řádky testovací DB.

**Cíl:** Marketing assety v GitHubu. Verzované, sdílené, nasaditelné. Žádné `v7_final_FINAL.pptx`.

---

## Modul 2: Nástroje & Stack

**Žádný ChatGPT Teams. Pořádné nástroje, které mění způsob práce.**

### 🔴 Přestaňte používat free verzie

Free ChatGPT, free Gemini — uživatelé pak nechápou rozdíl a říkají „AI mi nic nedává." Rozdíl mezi free a Pro je jako mezi Škodou 105 a Teslou. **Buď Pro, nebo vůbec.**

### Pro buildování

| Nástroj | Popis | Cena |
|---------|-------|------|
| **Cursor** | AI editor. Vidí vaše soubory. Píše kód, generuje weby, reporty, prezentace. **To hlavní.** | $20/měs |
| **Claude Code (CLI)** | Terminálový AI agent od Anthropic. Builduje, refaktoruje, testuje. Alternativa/doplněk ke Cursoru — **testujte oba, zvolte co sedne.** | v ceně Claude Max |
| **GitHub** | Všechno co vyrobíme je tu. Verzované. Sdílené. 1 projekt = 1 repozitář. | zdarma |
| **Vercel** | Hosting front-end. 1 klik z GitHubu = live web. | zdarma |
| **Railway** | Hosting back-end + databáze. Alternativa k Vercel pro složitější appy. | free tier / $5+ |

### Pro každodenní práci

| Nástroj | Popis | Cena |
|---------|-------|------|
| **Claude Pro** | Konverzační AI. Emaily, research, analýzy, překlady. | $20/měs |
| **Gemini Pro** | Google AI. Kreativa, texty, analýzy. | $20/měs |

### Pro kreativní tým

| Nástroj | Popis | Cena |
|---------|-------|------|
| **Artlist** | AI vizuály — bannery, produktové fotky, kreativa. | Pro |
| **Koda** | AI vizuální nástroj. Testování vedle Artlistu. | Pro |

**Testovací účty (schváleno Tomášem 11.3.):** Registrace přes `ai-devel@vitar.cz`. Využívejte max free trial (Cursor 14 dní, Claude 7 dní...) — **než zaplatíte, musí si to sedět.**

**Lovable:** No-code prototyping. Dá se napojit na GitHub (auto-sync), ale nechová se agenticky — proto přechod na Cursor pro seriózní vývoj.

### Trial strategie & měsíční review

Nedělejte velké commity. Neplaťte roční licence „do zásoby." Každý měsíc review:

1. **Trial first:** Cursor 14-day trial, Claude free tier, Railway free tier — *vyzkoušej, než koupíš.*
2. **Cursor vs. Claude Code:** Každý power user testuje oba. Po 2 týdnech: *co ti sedne víc?* Nemusíme mít jeden tool pro všechny.
3. **Měsíční review:** Na weekly AI committee **každý měsíc zhodnotit** — přináší nástroj hodnotu? Kolik hodin ušetřil? Pokud ne → switch.
4. **Kreativní AI zvlášť:** Artlist, Koda, Midjourney — testovat měsíčně. Kreativní nástroje se mění nejrychleji.

> **Pravidlo: žádná licence nepřežije víc než 3 měsíce bez review. Pokud nepřináší value → zrušit, switchnout.**

### Hardware — bez toho to nepojede

AI nástroje (Cursor, lokální modely, velké projekty) potřebují **výkonné stroje**. Na starém notebooku s 8 GB RAM se v Cursoru nedá seriózně pracovat.

**AI ambasádoři / Power Users potřebují:**
- **Min. 16 GB RAM** (ideálně 32 GB) — Cursor + prohlížeč + lokální server
- **SSD** — rychlý disk, ne HDD
- **Moderní CPU** — Apple M-series nebo Intel 12th gen+
- **Dedikovaná GPU** (nice-to-have) — pro lokální AI modely, generování vizuálů

> **Radim (11.3.):** Máme dvouslotový server, GPU karty se dají dokoupit — teď o 30 % levněji. Zvážit, jestli dimenzovat infrastrukturu na lokální AI. Ale nejdřív koncept — *pak* hardware.

**Pravidlo: správný stroj = správný člověk.** Nedávejme silné stroje všem. Dávejme je **power userům, kteří dokazují, že je využijí**. Workshop absolvován, showcase ukázán, workflow sdílen → dostaneš lepší setup. Metrika: kolik hodin AI ušetřila / měsíc.

---

## Modul 3: Dvě kategorie

**Klíčové pravidlo dohodnuté 11.3. Základ celého přístupu.**

### ✅ Kategorie 1: Mimo firemní data → volně

Prezentace, HTML stránky, brand materiály, překlady, emaily, research, SOP. **Povoleno okamžitě** s basic best practices. Žádné schválení navíc.

Příklady: Marketing texty · Prezentace · Překlady · Emaily, nabídky · Research, analýzy · SOP, návody · Brand materiály

### 🔴 Kategorie 2: Sahá na firemní data → plný release proces

Kalkulačka vývoje, vzorky app, CRM, cokoliv s firemní DB. **Musí projít 3-fázovou release metodikou** (Alfa → Beta → Live). Scope dokument před prvním řádkem kódu.

Příklady: Receptury, složení · Finanční výkazy, marže · Mzdy, smlouvy · CRM, zákaznické DB · Cenové podmínky · Kapacitní plány

> ⚠️ **Riziko (Tomáš, 11.3.):** „Někdo si postaví Cursor bot na firemním počítači, napojí na firemní složky — a jsme v prdeli." Proto dvě kategorie. Proto scope dokument. Proto sandbox.

### Mapa: co kde běží

| Aktivita | Nástroj | Data | Schválení |
|----------|---------|------|-----------|
| Prezentace, texty, emaily | Claude / Gemini | Veřejná | Žádné extra |
| HTML stránky, brand | Cursor → GitHub | Veřejná | Žádné extra |
| Interní app (ALFA) | Cursor → GitHub → Vercel + testovací DB | Testovací (fake) | Scope doc → Tomáš + Radim |
| Interní app (BETA) | GitHub → devel server | Mix (anonymizovaná) | Code review + OWASP |
| Interní app (LIVE) | Produkční server | Firemní | PO + Security sign-off |

**Klíčový princíp:** Cursor nikdy přímo na firemním serveru. Cursor → GitHub (kód). GitHub → Vercel (testování). Teprve po review → devel server → produkce. Data a kód jsou **vždy oddělené** až do fáze LIVE.

### Upřímně: jak to reálně ohlídat?

#### Technicky to nejde zablokovat

Cursor je desktop appka. Claude a Gemini jsou webové. Pokud má člověk přístup, **technicky může vložit cokoliv** — recepturu, marže, smlouvu. Žádný DLP filter to v reálném čase nechytí. To je realita, ne výmluva.

Proto **nespoléháme na technologickou bariéru**, ale na tři věci:

1. **Člověk to musí vědět.** Proto školení, workshop, dvě kategorie. Každý, kdo dostane AI licenci, prošel 2h hands-on a ví, co je červená zóna. Neříkáme „nesmíš" — říkáme „víš proč ne."
2. **Prostředí to musí ztížit.** Cursor na dev strojích **nemá přístup k firemním složkám** (síťové disky, SharePoint sync, sdílené složky). Pracuje jen s lokálním projektem. Sandbox = oddělený od firemního prostředí.
3. **Proces to musí chytit.** Scope dokument před vývojem. Code review před deployem. Radim sign-off před napojením na firemní DB. Tři bariéry — ne proto, aby brzdily, ale aby chytily to, co člověk přehlédne.

> **Analogie:** Je to jako s firemní kartou. Technicky můžeš koupit cokoliv. Ale víš, co smíš a co ne. A je tam schvalovací proces pro větší částky. Stejný princíp — **důvěra + pravidla + kontrola**.

**Nevíte?** Zeptejte se v Teams kanálu AI @ VITAR. Lepší se zeptat než dát recepturu do AI.

---

## Modul 4: Release proces & GitHub

**3-fázová metodika pro vše, co sahá na firemní data. GitHub pravidla pro všechny.**

### 3-fázová release metodika (platí pro Kategorii 2)

| Fáze | Popis |
|------|-------|
| **0. Scope dokument** | 1 stránka: co, proč, jaká data, autentifikace, role. *(Radim: „Bez plánu = riziko.")* |
| **1. ALFA** | Builduju v sandboxu (Vercel + testovací DB). Žádná firemní data. IT nezatěžuju — *Dalibora zapojíme až s funkčním prototypem.* |
| **2. BETA** | Cross-model review (kód z Opus → kontrola Codexem). Člověk zkontroluje na základě strojové analýzy. OWASP Top 100 automaticky — 90 % čistoty bez lidské práce. |
| **3. Sign-off** | Product Owner + Security (Radim): „toto je SAFE" |
| **✓ LIVE** | Napojení na firemní DB, testování na firemním PC, onboarding uživatelů, monitoring |

> **Budget control (Tomáš):** Každý product owner má přidělený dolarový limit na tokeny. „Nevlezu do Cursoru hrát si — vlezu tam, až mám vymyšlenou strukturu a markdown dokumentaci. Jinak spálíme $100 za 40 minut."

### GitHub pravidla (dohodnuto 11.3.)

| Pravidlo | Detail |
|----------|--------|
| **main = produkce** | Co je v main, to je live. Nikdo nepushuje přímo do main. |
| **dev = testování** | Vývoj v dev branchi. Merge do main = code review. |
| **Commity v markdownu** | Navigovatelné pro dalšího vývojáře. Automatizovaný log na konci dne. |
| **README v každém repu** | Co to dělá, jak spustit, kdo to buildoval. Kolega musí být schopen pokračovat. |
| **Private repos + licence** | Každý repo private. Licence kódu (Apache 2.0 nebo interní). |

> **Existující infrastruktura (Radim):** M365, SharePoint, Graph API, Entra ID. Nebudovat od nuly, využít co firma má. SSO vyřešit jednou, ne pro každou appku.

---

## Modul 5: Lidé & role

**Kdo co dělá. Žádná zbytečná byrokracie — jasná odpovědnost.**

### Rozhodování & schvalování

| Kdo | Role | Odpovědnost |
|-----|------|-------------|
| **Tomáš Červinka** | Sponsor & CEO | Strategické rozhodnutí, budget, „proč to děláme." Schvaluje nové projekty. Natočí Loom tutoriál: Cursor → GitHub → Code flow. |
| **Radim Lorenc** | IT & Security Garant | Schvaluje nástroje a release do produkce. Scope dokument před vývojem. Využít M365/Graph API/Entra — nebudovat od nuly. SSO řešit jednou. |

### Architektura & inspirace

| Kdo | Role | Odpovědnost |
|-----|------|-------------|
| **Juraj Giacko** | AI Architekt | Ukazuje jak na to. Buduje referenční implementace, sdílí best practices, vede workshopy. Inspiruje a školí — **neschvaluje**. Schvalují Tomáš (strategie/budget) a Radim (bezpečnost/IT). |

### Exekuce

| Kdo | Role | Odpovědnost |
|-----|------|-------------|
| **Dan Sládečk** | IT exekuce | GitHub setup, testovací účty, registrace nástrojů. Hands-on IT podpora pro AI tým. |
| **Karolína Doušová** | Analýza & BI | Vzorky app analýza (Miro), Power BI dashboard, zákaznický servis workflow. Scope dokumenty. |

### Kreativní tým

| Kdo | Role | Odpovědnost |
|-----|------|-------------|
| **Radovan Zajíc** | Kreativa | Testuje Artlist, Gemini, Koda. Zastupuje kreativní potřeby designu a marketingu. |
| **Daniel Mimochodek** | Design | Vizuály, kampaně, produktové fotky. Testuje AI pro kreativní workflow. |

### Championi

1 na oddělení. Ne expert, ale ochotný člověk, který ukáže ostatním co se naučil. Rotuje Bi-weekly AI Coffee. Vybereme z lidí, kteří to chtějí zkoušet.

> **Kapacita (Radim, 11.3.):** Potřebujeme vychovat někoho interně — **2–3 hodiny denně pravidelně**, ne „když je trochu času." Zvažujeme i externího IT specialistu na part-time (kontakt od Kamila Škrobaly).

### Kde se učit — ne spolky, ale světoví lídři

Místo lokálních AI spolků se učme od lidí, kteří AI staví denně:

| Zdroj | Co nabízí |
|-------|-----------|
| **Lovable Academy** | Kurzy no-code AI prototypingu, reálné buildování produktů. Skvělé pro non-dev lidi. |
| **Aibility** | AI implementace pro firmy. Praktické frameworky, case studies, workshopy. |
| **AIFirst** | Komunita a kurzy zaměřené na AI-first mindset. Jak přetvořit firemní procesy. |
| **Cursor 101 / YouTube** | Best practices od power userů. Jak správně nastavit rules, context, workflow. |
| **Anthropic Cookbook / OpenAI Guides** | Oficiální zdroje od tvůrců modelů. Prompt engineering, best practices. |
| **Y Combinator / Build in Public** | Sledovat, jak startupy buildí s AI v reálném čase. |

> **Lokální spolky můžou pomoct s networkingem, ale skill buildit světovými zdroji.**

---

## Modul 6: Jak začít

**Chci AI. Jak ji dostanu. Kdo schvaluje. Kde se ptám.**

### Chci Claude / Gemini ($20/měs)

1. Požádám **přímého nadřízeného**
2. Absolvuji **2h hands-on workshop**
3. Dostanu licenci + přístup do **Teams kanálu AI @ VITAR**

### Chci Cursor ($20/měs)

1. Požádám **přímého nadřízeného**
2. **Radim / IT** schválí + povolí instalaci
3. Setup s pomocí **Tomášova Loom tutoriálu** (Cursor → GitHub → Code flow)

### Chci buildovat interní nástroj

1. Napíšu **scope dokument** — co, proč, jaká data, role
2. **Tomáš + Radim** schválí scope
3. Postupuji dle **release procesu** (→ Modul 4)

### Teams kanál: AI @ VITAR

Jedno místo pro všechno. Připnuté pravidla, sdílené tipy, showcase.

- 📌 **Připnuté** — Tento program, AI Use Policy, návod na Cursor
- 💡 **Tipy & workflow** — Našel jsi dobrý postup? Hoď to sem.
- ❓ **Otázky** — Nevíš jak na něco? Zeptej se, odpoví champion nebo tým.
- 🚀 **Showcase** — Udělal jsi něco v AI co ti ušetřilo čas? Ukaž to ostatním.

### Pravidelné rituály

#### 🔴 HIGHEST PRIORITY: Weekly AI Committee Sync

**Tomáš + Radim + Juraj + AI tým.** 30–45 min, fixní slot v kalendáři.

Bez tohohle se nic nepohne. Tady se řeší: co buildujeme, co blokuje, co schválit, co zastavit. Ne „když bude čas" — **toto je ten čas**.

**Agenda:**
1. Status projektů (5 min)
2. Blockery & rozhodnutí (15 min)
3. Nové požadavky / scope docs (10 min)
4. Security & IT update od Radima (5 min)
5. Akce na příští týden (5 min)

#### Bi-weekly AI Coffee

**Celý AI tým + zájemci.** 20 min, neformální. Každé 2 týdny.

Kdo co udělal. Top workflow za 2 týdny. „Hele, tohle mi ušetřilo 4 hodiny." Showcase, ne přednáška.

**Formát:** 2–3 lidi ukáží screenshare co buildili / co se naučili → diskuze → tip týdne.

#### AI Review (měsíčně)

**Tomáš + Radim + Juraj.** 45 min, poslední pátek v měsíci. Metriky, budget review nástrojů, bezpečnost, strategický pohled.

> **Proč highest priority?** Na callu 11.3. jsme se dohodli na spoustě věcí. Ale bez **pravidelného weekly syncu** se to rozpadne do dvou týdnů. Každý bude dělat svoje, nikdo nebude vědět co ostatní, blockery se budou hromadit. Weekly AI Committee = jediný bod, kde se potkáme, rozhodneme a posuneme.

---

## Modul 7: Plán & budget

**Kickoff → Weekly AI Committee → iterace. Žádný rigidní 30-dňový plán. Posouváme se tam, kam nás zavede weekly sync.**

### Co potřebujeme od IT — teď

| Co | Detail | Kdy |
|----|--------|-----|
| **Cursor / Claude Code** | Povolit instalaci na 3–5 PC. Desktop app, nulový přístup k serveru. | HNED |
| **GitHub org** | Založit "vitar-group". Webový nástroj, není na serveru. | HNED |
| **Webové služby** | Vercel, Railway, Neon, Firebase. Testovací, oddělené od firemního. | BŘEZEN |
| **Admin práva** | Pro Tier 1 vývojáře — instalace Cursor, terminál. Jen na dev strojích. | BŘEZEN |

### Kickoff akce — tohle spustit hned

Nedáváme rigidní 30-dňový plán. Spustíme tyto akce a pak iterujeme na **Weekly AI Committee**.

| Kdy | Co |
|-----|-----|
| HNED | 🔴 **Vykopnout Weekly AI Committee Sync** — fixní slot, Tomáš + Radim + Juraj + AI tým. Motor všetkého. |
| HNED | **Teams kanál** AI @ VITAR — připnout pravidla, tento program, AI Use Policy |
| HNED | **Tomáš: Loom tutoriál** — Cursor → GitHub → Code flow |
| T12 | **Dan: GitHub org** "vitar-group" + private repos + pozvat tým |
| T12 | **Dan: testovací účty** ai-devel@vitar.cz + free trial Cursor/Claude Code/Gemini |
| T12 | **Tomáš: kontakt IT spec.** od Kamila Škrobaly — part-time podpora |

### Kam dál? Rozhodne Weekly AI Committee.

Nemáme fixní roadmapu na 6 měsíců. Na každém weekly syncu vyhodnotíme, co funguje, a posuneme se dál.

| Kdy | Co |
|-----|-----|
| ~T3-4 | **Workshop #1** — 5–8 lidí, hands-on 2h (Cursor / Claude Code) |
| ~T4 | **Bi-weekly AI Coffee #1** — kdo co udělal, showcase, tip týdne |
| ~M2 | **AI Review #1** — Tomáš + Radim + Juraj. Metriky, budget review nástrojů |
| ~M2 | **Rozhodnutí: Cursor vs. Claude Code** — co sedne komu? Kdo potřebuje co? |
| ~M3 | **Měsíční review nástrojů** — přináší licence value? Switch / cancel neefektivních |

### Budget

**~22 000 CZK/měs** za celou firmu (25 licencí)

Pokud každý ušetří 2h týdně = **200+ hodin měsíčně**. 1 celý člověk na plný úvazek. Za cenu oběda na osobu.

---

## FAQ

**Proč nemůžu zůstat na free verzi?**
Free ChatGPT / free Gemini = starší modely, omezený kontext, pomalé odpovědi, žádné pokročilé funkce. Uživatelé pak říkají „AI mi nic nedává" — protože pracují s demo verzí. Rozdíl mezi free a Pro je jako mezi kalkulačkou a Excelem. Buď Pro, nebo nic.

**Můžu používat ChatGPT?**
Můžeš (Pro verzi), ale nebude to nic moc pro buildování. ChatGPT nevidí vaše soubory. Cursor / Claude Code ano. Rozdíl je v tom, že místo kopírování tam a zpátky AI pracuje přímo s vaším projektem.

**Co když nevím, jestli můžu dát data do AI?**
Zeptej se v Teams kanálu AI @ VITAR. Pravidlo: pokud bys to nenapsal na firemní nástěnku, nedávej to do AI. Receptury, marže, mzdy = nikdy.

**Musím umět programovat?**
Ne. Cursor umí generovat kód za tebe. Potřebuješ umět popsat, co chceš — a rozumět výsledku. Workshop tě naučí základy.

**Kdo schvaluje nový AI nástroj?**
Přímý nadřízený (standard nástroje). Radim / IT (Cursor, vývojové nástroje). Tomáš (budget nad rámec). Juraj neschvaluje — ukazuje, jak na to.

**Kde najdu víc o AI adopci v EU?**
Zkus Deep Research v ChatGPT, Copilotu nebo NotebookLM: *„Jaké jsou osvědčené modely pro škálování AI adopce v SMB firmách s 10–50 zaměstnanci v Evropě?"* — AI ti najde aktuální studie a případy. Výsledky sdílej v Teams kanálu.

---

*AI @ VITAR · v4.0 · 16. březen 2026 · Zdroj: meeting 11.3.2026 + EU deep research (McKinsey, OECD, Eurostat)*
