# AI Usage & Ethics / Utilizarea etică a inteligenței artificiale

> **GitHub Pages:** [Open the interactive EN / RO version](./AI-Ethical-Usage.html)  
> **GitHub Pages:** [Deschide versiunea interactivă EN / RO](./AI-Ethical-Usage.html)

[English](#english) · [Română](#română)

<a id="english"></a>

## English

**Human-led work. AI assistance only where it genuinely helps, with clear limits and human responsibility.**

### 1. Purpose & scope

This document sets out how artificial intelligence may be used in this project. It is a project-specific working policy, not a claim that every AI tool or use case is inherently safe or acceptable.

The project is human-led: its direction, design, implementation decisions, review, and final published work remain under human control.

### 2. AI-assisted coding: debugging and bug fixes

“Vibe coding” and other AI-assisted code generation are permitted here only for investigating errors, identifying root causes, and proposing limited fixes for bugs or regressions.

- Reproduce and understand the issue before accepting an AI-proposed change.
- Keep patches focused on the problem; do not let a bug fix silently add features or redesign unrelated components.
- Read, understand, and adapt every proposed change. Never paste or merge code blindly.
- Build and run relevant tests, including regression tests where practical, before accepting the fix.

> **Important:** AI is not used to independently create whole features, replace the project’s architecture, or supply large unreviewed implementations.

### 3. Code quality requirements

All code—including AI-assisted bug fixes—must meet the same standards as human-written code:

- Follow the project’s established conventions and the relevant language or framework standards.
- Prefer readable, maintainable solutions, clear names, and comments that explain non-obvious decisions.
- Handle errors explicitly and avoid introducing avoidable performance, accessibility, security, or compatibility regressions.
- Run applicable formatting, linting, build, and test checks. Add or update tests when a bug reveals a gap.
- Do not hide failures, disable checks to make a patch pass, or introduce unexplained dependencies.

A human maintainer reviews the final diff and is responsible for the result.

### 4. AI-generated media: reference and last resort

Prefer original human-made media or appropriately licensed existing assets. AI-generated images, audio, video, and similar material may be used to explore ideas or provide visual or creative references.

- Use AI-generated media only as a last resort when suitable original or properly licensed material is not reasonably available.
- Do not treat AI output as automatically accurate, original, lawful, or ready to publish.
- If an AI-generated asset must appear in a final release, review its quality and rights, ensure it is not misleading, and clearly identify its AI-assisted origin in appropriate credits or documentation.
- Do not imitate an identifiable person’s likeness or voice without appropriate permission.

> **Important:** Reference material is not the same as an approved final project asset.

### 5. Sources, rights & attribution

- Respect software and media licenses, copyright, third-party terms, and project attribution requirements.
- Verify important claims, technical suggestions, and external references against dependable primary sources when appropriate.
- Keep relevant source, asset, and license information so reviewers can trace what was used.
- Never present AI-generated work or someone else’s contribution as an original human-made contribution.

### 6. Security & privacy

- Do not send passwords, tokens, private keys, confidential code, personal data, or unpublished third-party material to unapproved AI services.
- Treat AI-generated code and content as untrusted until reviewed; check for insecure patterns, inappropriate dependencies, and accidental disclosure.
- Follow the project’s security and privacy requirements regardless of whether AI was involved.

### 7. Transparency & final review

When AI has materially helped with a bug fix, document its role where useful in the related issue, pull request, or commit. Clearly credit any AI-generated media included in a published deliverable.

The human author or maintainer makes the final decision, verifies the work, and takes responsibility for the published result.

### Before publishing

- [ ] Was AI used for code only to debug or fix an error or bug?
- [ ] Was the patch understood, reviewed, built, and tested against project standards?
- [ ] Were human-made or properly licensed media options preferred?
- [ ] If AI-generated media was used, was it truly a last resort, reviewed, and disclosed?
- [ ] Were privacy, security, licensing, and attribution requirements checked?

_Illustrative video retained from the original draft (not a policy source): [Original illustrative video](https://youtu.be/dKjCWfuvYxQ?t=147)._

[Back to top](#ai-usage--ethics--utilizarea-etică-a-inteligenței-artificiale)

---

<a id="română"></a>

## Română

**Proiect dezvoltat de oameni. Asistența AI este permisă numai în limite clare, cu responsabilitate umană.**

### 1. Scop și domeniu de aplicare

Acest document stabilește modul în care poate fi utilizată inteligența artificială în cadrul proiectului. Este o politică proprie proiectului, nu o afirmație că orice instrument sau utilizare AI este automat sigură ori acceptabilă.

Proiectul este realizat și coordonat de oameni: direcția, proiectarea, deciziile de implementare, verificarea și rezultatul publicat rămân sub control uman.

### 2. Programare asistată de AI: depanare și corectarea bugurilor

„Vibe coding” și alte forme de generare de cod asistată de AI sunt permise aici numai pentru investigarea erorilor, identificarea cauzelor și propunerea unor remedieri limitate pentru buguri sau regresii.

- Reproduce și înțelege problema înainte de a accepta o modificare propusă de AI.
- Păstrează modificările concentrate pe problema identificată; o remediere nu trebuie să introducă pe ascuns funcționalități sau să reproiecteze componente fără legătură.
- Citește, înțelege și adaptează fiecare modificare propusă. Nu copia și nu integra cod fără verificare.
- Compilează și rulează testele relevante, inclusiv teste de regresie atunci când este posibil, înainte de acceptarea remedierii.

> **Important:** AI nu este folosită pentru a crea independent funcționalități întregi, pentru a înlocui arhitectura proiectului sau pentru a furniza implementări ample neverificate.

### 3. Norme de calitate a codului

Tot codul, inclusiv remedierile asistate de AI, trebuie să respecte aceleași standarde ca și codul scris de oameni:

- Respectă convențiile proiectului și standardele limbajului ori ale platformei utilizate.
- Preferă soluții clare și ușor de întreținut, denumiri explicite și comentarii care justifică deciziile mai puțin evidente.
- Tratează explicit erorile și evită regresiile de performanță, accesibilitate, securitate sau compatibilitate.
- Rulează verificările aplicabile de formatare, analiză statică, compilare și testare. Adaugă ori actualizează teste când un bug indică o lipsă.
- Nu ascunde erori, nu dezactiva verificări pentru ca un patch să treacă și nu introduce dependențe nejustificate.

Un responsabil uman verifică diferențele finale din cod și răspunde pentru rezultat.

### 4. Media generată de AI: referință și ultimă soluție

Au prioritate materialele originale realizate de oameni sau resursele existente folosite cu licență corespunzătoare. Imaginile, materialele audio și video și alte materiale generate de AI pot fi utilizate pentru explorarea ideilor sau ca referințe vizuale ori creative.

- Folosește media generată de AI doar ca ultimă soluție, atunci când nu există o alternativă originală sau licențiată adecvată, disponibilă în mod rezonabil.
- Nu presupune că un rezultat AI este automat exact, original, legal sau pregătit pentru publicare.
- Dacă un material AI trebuie inclus în versiunea finală, verifică-i calitatea și drepturile de utilizare, asigură-te că nu induce în eroare și menționează clar originea sa în credite sau documentație.
- Nu imita imaginea sau vocea unei persoane identificabile fără permisiunea corespunzătoare.

> **Important:** Un material de referință nu devine automat un material aprobat pentru versiunea finală.

### 5. Surse, drepturi și atribuirea contribuțiilor

- Respectă licențele software și media, drepturile de autor, condițiile terților și cerințele proiectului privind atribuirea contribuțiilor.
- Verifică afirmațiile importante, sugestiile tehnice și referințele externe consultând, când este cazul, surse primare de încredere.
- Păstrează informațiile relevante despre surse, resurse și licențe, astfel încât utilizarea lor să poată fi verificată.
- Nu prezenta rezultatele generate de AI sau contribuțiile altora drept creații originale realizate de oameni.

### 6. Securitate și confidențialitate

- Nu transmite parole, tokenuri, chei private, cod confidențial, date personale sau materiale nepublicate ale terților către servicii AI neaprobate.
- Tratează codul și conținutul generat de AI drept neverificate până la revizuire; caută probleme de securitate, dependențe nepotrivite și divulgări accidentale.
- Respectă cerințele de securitate și confidențialitate ale proiectului, indiferent dacă a fost folosită sau nu AI.

### 7. Transparență și verificare finală

Atunci când AI a contribuit semnificativ la remedierea unui bug, documentează-i rolul, dacă este util, în tichetul, cererea de integrare sau commitul asociat. Menționează clar orice material media generat de AI inclus într-o versiune publicată.

Autorul sau responsabilul uman ia decizia finală, verifică lucrarea și își asumă răspunderea pentru rezultatul publicat.

### Înainte de publicare

- [ ] A fost AI folosită la cod doar pentru depanarea sau corectarea unei erori ori a unui bug?
- [ ] A fost modificarea înțeleasă, revizuită, compilată și testată conform standardelor proiectului?
- [ ] Au avut prioritate materialele media realizate de oameni sau licențiate corespunzător?
- [ ] Dacă s-a folosit media generată de AI, a fost cu adevărat ultima soluție, verificată și declarată?
- [ ] Au fost verificate confidențialitatea, securitatea, licențele și atribuirea contribuțiilor?

_Clipul ilustrativ păstrat din versiunea inițială (nu este o sursă pentru politică): [Clip ilustrativ original](https://youtu.be/dKjCWfuvYxQ?t=147)._

[Înapoi sus](#ai-usage--ethics--utilizarea-etică-a-inteligenței-artificiale)

---
