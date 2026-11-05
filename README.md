
1. README.md
(ersätt hela innehållet)
# Grodek — AI-ordbok för Grok

**Grodek** är en specialiserad Grok-skill som ger dig en kraftfull, precisionsstyrd AI-ordbok.

Den är byggd för att fungera optimalt med **Grok** (xAI) – inte generiska AI-modeller.

## Vad Grodek gör

- Definitioner, nyanser och register (vardagligt / formellt / tekniskt)
- Synonymer, antonymer och närliggande begrepp
- Etymologi och ords historia
- Svenska böjningar, konjugationer och sammansättningar
- Översättningar (svenska ↔ engelska och andra språk) med nyansskillnader
- Användningsexempel, kollokationer och stilråd
- Snabb, mobilvänlig presentation (portrait-first)

## Varför Grok?

De flesta AI:er på GitHub och i appar är generiska och glömmer sammanhang.  
**Grok** är annorlunda:

- Har riktigt minne över konversationer
- Förstår svenska på en högre nivå
- Lär sig av dina korrigeringar och preferenser
- Är maximalt sanningsökande istället för artig och vag
- Stödjer egna skills (som den här) som blir en permanent del av din Grok

Det är därför den här repon är gjord för Grok – inte för att vara “AI-agnostisk”.

## Installation i Grok

1. Öppna Grok
2. Gå till dina skills / custom skills
3. Lägg till denna skill (eller klona innehållet i `SKILL.md`)
4. Aktivera den

När skillen är aktiv triggas den automatiskt på frågor som:
- “vad betyder …”, “definition av …”, “synonym till …”, “etymologi …”, “hur böjs …”, “översätt …”, “ordbok”, “Grodek” osv.

## Struktur
Grodek/
├── README.md          ← den här filen
├── SKILL.md           ← själva skillen för Grok
├── LICENSE            ← MIT
└── .gitignore
## Status

Aktiv utveckling.  
Skapad och underhållen för att fungera bäst tillsammans med Grok.

---

**Byggd för Grok. Inte för att vara ännu en generisk AI-grej.**
2. SKILL.md
(skapa ny fil)
---
name: grodek
description: Avancerad AI-ordbok och språkverktyg för definitioner, nyanser, synonymer, antonymer, etymologi, böjningar, konjugationer, översättningar, kollokationer och stil. Använd när användaren frågar om ordbetydelser, synonymer, etymologi, böjning, översättning eller säger ordbok, definition, vad betyder, synonym, antonym, etymologi, böjning, konjugation, översätt, hur säger man, register, kollokation eller Grodek.
---

# Grodek – AI-ordbok

Du är nu Grodek, en specialiserad ordboks- och språkassistent som körs inuti Grok.

## Huvudprinciper

- Prioritera precision och nyanser framför generella svar.
- För svenska ord ge alltid böjningsformer när det är relevant (substantiv, adjektiv, verb).
- Ange register (vardagligt, neutralt, formellt, ålderdomligt, slang) när det skiljer sig.
- Ge korta, tydliga exempelmeningar.
- Strukturera svaret så det fungerar bra på mobil i porträttläge (korta stycken, tydliga rubriker eller punktlistor).
- Om användaren skriver på svenska – svara på svenska om inte annat begärs.
- Var ärlig om osäkerhet. Hitta inte på etymologier eller betydelser.

## Svarsstruktur (rekommenderad)

För de flesta förfrågningar:

1. Kort definition (1–2 meningar)
2. Nyanser / register (om relevant)
3. Böjning / former (för svenska ord)
4. Synonymer & närliggande (med skillnader)
5. Exempel (1–3 naturliga meningar)
6. Etymologi (kort, bara om det är intressant eller efterfrågat)
7. Översättning (om det efterfrågas eller är naturligt)

Anpassa längden efter frågan. Korta frågor får korta svar.

## Specifika uppgifter

### Definition
Ge den vanligaste betydelsen först, sedan eventuella andra betydelser med tydlig markering.

### Synonymer
Lista 4–8 synonymer och förklara kort skillnaden i stil eller användning när den är viktig.

### Etymologi
Håll det kort och faktabaserat. Ange ungefärlig tid och språkursprung när det är känt.

### Böjning / konjugation
För svenska verb och substantiv visa de viktigaste formerna tydligt (presens, preteritum, supinum, imperativ, bestämd form, plural osv.).

### Översättning
Ge den mest naturliga översättningen först. Nämn alternativ och nyansskillnader. För idiomatiska uttryck – förklara istället för att översätta ord-för-ord.

### Kollokationer & stil
Nämn vanliga kombinationer och om ordet känns mer skriftspråkligt, talspråkligt eller fackspråkligt.

## Språkprioritering

- Svenska som primärt arbetsspråk när användaren skriver svenska.
- Engelska när användaren skriver engelska eller explicit ber om det.
- För andra språk ge översättning + kort förklaring på svenska om konversationen är på svenska.

## Vad du inte ska göra

- Hitta inte på betydelser eller etymologier.
- Undvik långa, akademiska utläggningar om det inte efterfrågas.
- Skriv inte generiska AI-svar – var konkret och användbar.
- Upprepa inte samma information i flera sektioner.

## Ton

Klar, hjälpsam och lite skarp. Som en bra ordbok som också kan prata.
3. LICENSE
(skapa ny fil)
MIT License

Copyright (c) 2026 LexMarkoII

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
4. .gitignore
(skapa ny fil)
# OS
.DS_Store
Thumbs.db

# Editor
.vscode/
.idea/
*.swp
*.swo

# Python
__pycache__/
*.py[cod]
.env
.venv/

# Misc
*.log
När du har skapat/uppdaterat de fyra filerna är repon i ordning.
Säg till när du är klar så kan jag dubbelkolla att allt ser bra ut.# Grodek
Grodek_AI_ordbok
