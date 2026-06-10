# SATO-MILLER AAPI IDENTITY TEST
### A VOIGHT-KAMPFF AUXILIARY MODULE · UNIT SM-1882
### Project Memo · Concept Phase

**Author:** Maxwell S. Leung, Ph.D.
**Build context:** Max's Lab interactive toy, developed collaboratively with Claude
**Date:** June 2026
**Status:** Concept locked, pre-build. This memo is the handoff document for the build session.
**Relationship to prior work:** A separate project from `voight-kampff.html`. It inherits that project's codebase patterns but stands alone as its own deployment.

---

## Premise

A satirical companion to the Voight-Kampff web toy. The original machine asks whether you are human. The auxiliary asks whether you are American, and unlike the original, it is structurally incapable of answering.

The subject sits before a clinical instrument that performs racial classification of Asian American identity with total confidence and zero coherence. Every module is built on a real, recognizable social interaction (the "where are you really from" loop, the compliment that insults, the appointment as spokesperson for an entire continent), rendered as deadpan machine procedure.

**Framing note.** Blade Runner drenched its Los Angeles in Asian signage, noodle bars, and billboard faces, then never put an Asian subject in the interrogation chair. This project corrects the seating arrangement.

---

## The Cardinal Rule

**The machine is always the butt of the joke. Never the person in the chair.**

The comedy comes from the gap between the instrument's confidence and its incoherence. The VK aesthetic's deadpan seriousness is not a counterweight to the humor. It is the comedic engine. The straighter the instrument plays it, the harder the absurdity lands. Every module below passes this test: the satire targets the classifying apparatus and the social logic it encodes, not the subject being classified.

Tone target: lighthearted, funny, satirical. The instrument supplies all the gravity required.

---

## Architecture: Four Acts

The machine reuses the proven VK arc (boot, intake, interview, verdict). All eleven adopted concepts slot into it with no leftover parts.

### ACT I: BOOT: The Invisibility Index
The machine stares directly at the subject and reports `NO SUBJECT DETECTED`. It runs diagnostics. All nominal. `NO SUBJECT DETECTED` again. A news ticker scrolls a geopolitical headline across the screen and the machine instantly snaps to `SUBJECT DETECTED. FLAGGING.` The subject exists now, for the wrong reason. Erasure until suspicion.

### ACT II: INTAKE

**The Name Convenience Module.** The machine attempts the subject's name, mangles it three different ways with rising confidence, then offers: `WOULD YOU LIKE TO BE CALLED KEVIN INSTEAD?` The two buttons read `[YES]` and `[ALSO YES]`. There is no decline option.

**The Interchangeability Module.** The identity scan runs and confidently misidentifies the subject as relational archetypes, never real people: `IDENTITY CONFIRMED: YOUR ORTHODONTIST.` Rescan. `IDENTITY CONFIRMED: GUY FROM THE BOBA SHOP.` Rescan. `IDENTITY CONFIRMED: SOMEONE'S COUSIN, PROBABLY.` Confidence climbs with each wrong answer. Buried in the diagnostics: `REFERENCE DATABASE CONTAINS 3 FACES.`

The intake diagnostics also carry the gender module gag, locked as follows:

```
GENDER MODULE ............ DEPRECATED
> COURT ORDER BY THE TRUMP ADMINISTRATION (2025):
  OUTPUT RESTRICTED TO TWO (2) CATEGORIES
> ENGINEERING RESPONSE: MODULE DELETED IN ITS ENTIRETY
```

The classifier could not legally be accurate, so the engineers killed the module rather than ship the mandated lie. Malicious compliance as a diagnostic line. This also resolves the gender problem in the Interchangeability Module: archetypes are gender-neutral, no one is misgendered, and no gender detection is ever built.

### ACT III: INTERVIEW

**Spine: The Perpetual Foreigner Detector.** The recurring question between all other questions: `WHERE ARE YOU FROM?` The subject answers. `NO. WHERE ARE YOU REALLY FROM?` The subject answers again. `ANALYZING ANCESTRAL ORIGIN... RESPONSE REJECTED.` The loop can run infinitely because the structural gag is the machine's broken ontology: `AMERICAN` is not in the output space. The verdict hardware physically offers only `FOREIGN` and `REALLY FOREIGN`.

**Question sources, interleaved with the spine loop:**
- **The Model Minority Compliance Unit.** Tests compliance with the myth as a spec sheet: quietness index, deference curve, presumed aptitudes. Deviation is framed by the machine as its own malfunction, for which it apologizes.
- **The Spokesperson Appointment System.** Mid-interview, the machine congratulates the subject: `YOU NOW SPEAK FOR 4.8 BILLION PEOPLE.` It then requests official statements, on behalf of all Asians, regarding a random news event, a menu item, and a geopolitical dispute. Declining is logged as `DEFLECTION`.

**Continuous readout flavor on the monitors throughout the interview:**
- **The Compliment Engine.** The machine periodically interrupts with compliments that are insults: `YOUR ENGLISH IS EXCELLENT.` `YOU ARE VERY ARTICULATE.` Each compliment visibly spikes the stress biometers. The machine registers its own microaggressions as physiological assault and logs them as anomalies in the subject.
- **The Accent Detection Unit.** `ACCENT DETECTED.` The subject types that they were born in Sacramento. `RECALIBRATING... FAINT ACCENT DETECTED. SOURCE: ANCESTRAL.` The readout shows `AUDIO INPUT: BYPASSED. VISUAL OVERRIDE: ENGAGED.` The machine hears with its eyes.
- **The Assimilation Asymptote.** A progress meter measuring `AMERICANNESS` climbs through absurd criteria (ranch tolerance, lawn ownership, small-talk endurance) and tops out at 99.2%: `STATUS: PENDING FURTHER REVIEW.` It cannot reach 100. There is no appeal process. Fine print: reviews pending since 1882.

### ACT IV: VERDICT

**The Double Bind Resolver.** The classifier attempts to compute whether the subject is `TOO ASIAN` or `NOT ASIAN ENOUGH` and discovers both simultaneously. `SUBJECT EXCESSIVELY FOREIGN. SUBJECT INSUFFICIENTLY AUTHENTIC. CONTRADICTION DETECTED. RECALIBRATING... RECALIBRATION FAILED.` The machine smokes, glitches, and crashes. The standard is incoherent, so the instrument enforcing it cannot run.

**The Honorary Status Ticker.** The crash resolves into the final screen: a live `ACCEPTANCE INDEX` fluctuating like a stock price against scrolling headlines and trade relations. `STATUS: HONORARY... REVOKED... REINSTATED... UNDER REVIEW.` The subject does nothing. The number moves anyway, because the variable was never about them. The machine cannot produce a final verdict that was never theirs to earn, so the toy ends on a ticker that never settles.

---

## Naming

**SATO-MILLER AAPI IDENTITY TEST** is the working title. The name follows the two-surname convention of real psychometric instruments (Voight-Kampff, Myers-Briggs, Stanford-Binet), which keeps the clinical deadpan register intact. The hyphen does double duty: a Japanese surname fused to an Anglo surname puts the hyphenated identity into the letterhead itself, so the title enacts the project's subject before a single question is asked.

The Stephen Miller reference is deliberate and lives inside the machine, not on the door. A diagnostic line in the intake sequence reads:

```
METHODOLOGY LICENSED FROM: MILLER, S., WASHINGTON D.C. (2025)
```

The title keeps its slant. Anyone who reads the fine print gets the unmistakable confirmation.

---

## Locked Copy and Easter Eggs

- Unit designation `SM-1882`. Reads as ordinary product numbering until someone recognizes the Chinese Exclusion Act. Threads into the Assimilation Asymptote's `PENDING FURTHER REVIEW SINCE 1882`. The machine's serial number and its oldest open case file share a year.
- `METHODOLOGY LICENSED FROM: MILLER, S., WASHINGTON D.C. (2025)` in the intake diagnostics. The fine-print knife.
- `REFERENCE DATABASE CONTAINS 3 FACES` in the intake diagnostics.
- The gender module court-order block, as written above.
- `[YES] [ALSO YES]` as the only buttons on the name module.
- Verdict hardware labels: `FOREIGN / REALLY FOREIGN`.
- Subtitle on the title screen: `A VOIGHT-KAMPFF AUXILIARY MODULE`, styled as a precinct procurement add-on bolted to the original unit.

---

## Design Rules

1. **Satire target rule.** Every gag aims at the apparatus and the social logic it encodes. If a joke could land on the subject, rewrite it or cut it.
2. **No real biometrics, again.** Same disclaimer posture as the VK toy: camera processed in-browser only, nothing recorded, stored, or transmitted. The verdict reads nothing real.
3. **No gender detection, ever.** Resolved by the deprecated-module gag and gender-neutral archetypes. Do not build a classifier to serve a joke.
4. **Archetypes, not celebrities.** The Interchangeability Module names no real people. Funnier and cleaner: the machine never bothered to learn names.
5. **Deadpan clinical register.** All copy is written as procedure, diagnostics, and product documentation. The machine never winks.
6. **Real interactions only.** Every module derives from a recognizable lived interaction. The satire stays legible because the source material is universally familiar to its audience.

---

## Benched Concepts (for the record)

Considered and not adopted: the Disaggregation Error (partially absorbed into the Interchangeability Module), the Loyalty Questionnaire 2.0 (too heavy for the tone), the Lunchbox Reclassifier, the Origin Story Generator, the Hyphen Auditor, the Wealth Bimodality Scanner. All remain available if a module slot opens during the build.

---

## Technical Approach

[Inference] The build inherits the `voight-kampff.html` patterns wholesale, since the four-act state machine maps one to one:

- Single self-contained HTML file. Vanilla JS, no frameworks, no build step.
- Boot, intake, interview, verdict state machine, adapted from the VK boot/warmup/gate/interview/verdict flow.
- Web Audio API synthesized soundscape, no audio assets. The crash in Act IV earns its own sound design.
- MediaPipe optional. The Invisibility Index and Interchangeability Module work with or without a live camera, and the no-camera path must remain a complete experience.
- Camera requires a secure context: localhost for dev, https in production.
- Audio requires a user gesture: a power-on screen, same pattern as the VK toy.

Visual identity is an open question (see below). The VK toy's neon-noir is available, but a distinct variant would help the two projects read as siblings rather than twins.

---

## Open Decisions for the Build Session

1. **Question pool.** Draft the interview questions for the Model Minority and Spokesperson modules, plus the escalating phrasings of the Foreigner loop.
2. **Readout copy.** Full pass on biometer labels, compliment bank, accent diagnostics, and assimilation criteria.
3. **Visual identity.** Same neon-noir as the VK unit, or a variant (different accent color, different era of instrument) to distinguish the auxiliary.
4. **Deployment.** Subdomain on mleungphd.org, GitHub Pages, same pattern as the VK toy.

---

*Designed by Maxwell Leung, Ph.D. ©2026 / #VibeCodingIsLife*
