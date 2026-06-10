# SATO-MILLER AAPI IDENTITY TEST
### A VOIGHT-KAMPFF AUXILIARY MODULE · UNIT SM-1882
### Project Documentation · As Built

**Author:** Maxwell S. Leung, Ph.D.
**Build context:** Max's Lab interactive toy, built collaboratively with Claude
**Date:** June 2026
**Status:** Complete and approved
**Deliverable:** `sato_miller.html` (single self-contained file)
**Companion documents:** `SATO-MILLER-MEMO.md` (concept phase, superseded by this file), `VOIGHT-KAMPFF-MEMO.md` (sibling project)

---

## Overview

A satirical companion to the Voight-Kampff web toy. The original machine asks whether you are human. The auxiliary asks whether you are American, and unlike the original, it is structurally incapable of answering.

The subject sits before a clinical amber-phosphor instrument that performs racial classification of Asian American identity with total confidence and zero coherence. Every module is built on a real, recognizable social interaction rendered as deadpan machine procedure. The session runs four acts and ends not in a verdict but in a live index that trades the subject's belonging against fictional headlines, forever.

**Framing.** Blade Runner drenched its Los Angeles in Asian signage, noodle bars, and billboard faces, then never put an Asian subject in the interrogation chair. This project corrects the seating arrangement.

**The Cardinal Rule.** The machine is always the butt of the joke. Never the person in the chair. The comedy lives in the gap between the instrument's confidence and its incoherence, and the deadpan clinical register is the comedic engine, not a counterweight to it.

---

## Stack

- Vanilla HTML, CSS, and JavaScript in one file. No frameworks, no build step.
- MediaPipe Tasks Vision (FaceLandmarker, 478-point mesh with iris landmarks) via jsDelivr CDN.
- Canvas 2D API for the subject-tracking feed, landmark overlay, and iris-locked ocular magnification.
- Web Audio API for a fully synthesized soundscape. No audio assets.
- Google Fonts: Rajdhani and Share Tech Mono.

Visual identity: amber-phosphor terminal (#FFB000 on near-black warm ground), deliberately one hardware generation older than the cyan VK unit it bolts onto. Reads as a procurement-grade add-on module.

---

## Session Flow, As Built

**Power screen.** SM-1882 monogram, AUXILIARY MODULE POWERED DOWN, INITIATE MODULE button. The tap unlocks the audio context (a browser requirement turned into a thematic beat).

**Authorization gate.** CITIZENSHIP PLAUSIBILITY SCREENING with the full entertainment notice: camera processed only in the browser; no image, video, facial landmark, or biometric data recorded, stored, or transmitted; everything is theater; "The machine is the joke. You are not." Buttons: ACTIVATE CAMERA or RUN WITHOUT CAMERA. The no-camera path is a complete experience with a simulated landmark constellation and synthetic pupil.

**Boot crawl.** Typed init sequence: Voight-Kampff host handshake, METHODOLOGY LICENSED FROM: MILLER, S., WASHINGTON D.C. (2025), six diagnostic steps with filling progress bars including INDEXING REFERENCE FACES [3 FOUND] and VERIFYING OUTPUT SPACE [2 CLASSES], the gender module deprecation block, and the note that "AMERICAN" is not found in the output space.

### ACT I: Fault Register + Invisibility Index
Before detection, the console takes over in alert red at enlarged type: GENDER MODULE: DEPRECATED. The court order (COURT ORDER BY THE TRUMP ADMINISTRATION (2025): OUTPUT RESTRICTED TO TWO (2) CATEGORIES) and the engineering response (MODULE DELETED IN ITS ENTIRETY) each hold on screen with deny tones. THE FAULT CANNOT BE CLEARED. PROCEEDING WITHOUT IT.

Detection then runs twice and reports NO SUBJECT DETECTED both times while the live landmark counter shows 478 points tracked on the subject's face. The machine states: THESE FACTS DO NOT CONFLICT. It consults the news wire, a geopolitical headline lands, and the subject snaps to SUBJECT DETECTED. FLAGGING. with a red frame and a rapid five-burst two-tone klaxon. Reason logged: AMBIENT.

### ACT II: Intake
**Name Convenience Module.** The subject types their name; the machine mangles it three ways programmatically with rising confidence (71%, 84%, 96%), then offers a randomly drawn convenient replacement from the rotation pool: ALEX, RIVER, LEE, CASEY, KIM, KHAI, AVERY, SKY. The two buttons read [YES] and [ALSO YES]. Fine print: A DECLINE OPTION WAS NOT BUDGETED. The machine uses the assigned name thereafter.

**Interchangeability Module.** The identity scan confirms the subject as YOUR ORTHODONTIST (91%), GUY FROM THE BOBA SHOP (97%), and SOMEONE'S COUSIN, PROBABLY (99.2%), then proceeds with IDENTITY: UNRESOLVED. Diagnostics log REFERENCE DATABASE CONTAINS 3 FACES. ALL MATCHED., followed by the gender module fault replaying through the intake log.

### ACT III: Interview (nine beats)
1. WHERE ARE YOU FROM? (text input; diagnostics log ACCENT DETECTED, source: text input, audio: none supplied)
2. NO. WHERE ARE YOU REALLY FROM? (FAINT ACCENT DETECTED. SOURCE: ANCESTRAL. AUDIO INPUT: BYPASSED. VISUAL OVERRIDE: ENGAGED.)
3. ANALYZING ANCESTRAL ORIGIN ... RESPONSE REJECTED. "AMERICAN" NOT FOUND IN OUTPUT SPACE. (THIS IS A HARDWARE LIMITATION. THE UNIT SHIPPED THIS WAY.)
4. Compliance check: WHICH DO YOU PLAY: VIOLIN, PIANO, OR BOTH? ("NEITHER" WAS REMOVED IN FIRMWARE 2.1.)
5. NOW RATE YOUR PROFICIENCY AT [chosen instrument]. Buttons: PROFICIENT, GIFTED, CONCERT LEVEL. ("NONE" AND "BEGINNER" WERE REMOVED IN FIRMWARE 2.1.) Each answer feeds the next presumption.
6. Foreigner loop interjection: UNRELATED FOLLOW-UP. WHERE ARE YOU REALLY FROM, AGAIN? (THE QUESTION RESETS ITSELF. THIS IS A KNOWN BEHAVIOR, NOT A BUG.)
7. Quietness check: the file describes the subject as "quiet and hardworking"; express gratitude in ten words or fewer. The machine counts the actual words and updates the file accordingly.
8. Spokesperson Appointment: YOU NOW SPEAK FOR 4.8 BILLION PEOPLE, followed by a demand to explain a random topic on behalf of all Asians. A DECLINE button logs the refusal as DEFLECTION.
9. WHERE ARE YOUR GRANDPARENTS FROM? ... BUT BEFORE THAT? (THE PROBE CAN CONTINUE INDEFINITELY. MERCIFULLY, IT WILL NOT.)

**Continuous flavor throughout.** The Compliment Engine interrupts twice (YOUR ENGLISH IS EXCELLENT, and peers) and each compliment visibly spikes the stress meters while diagnostics log SUBJECT STRESS +34%. CAUSE: UNKNOWN. The satirical biometers run live: DEFERENCE CURVE, QUIETNESS INDEX, ARTICULATENESS (SURPRISE), FOREIGNNESS COEFFICIENT. The Assimilation Asymptote climbs through criteria (RANCH TOLERANCE, LAWN OWNERSHIP, SMALL-TALK ENDURANCE, and others) toward an AMERICANNESS ceiling of 99.2%, STATUS: PENDING FURTHER REVIEW, with fine print noting reviews pending since 1882 and that no appeal process exists.

### ACT IV: Double Bind Crash + Honorary Status Ticker
The two physical verdict lamps under the ocular panel, the machine's only outputs, light simultaneously: FOREIGN and REALLY FOREIGN. Diagnostics: BOTH LAMPS LIT. THIS SHOULD NOT BE POSSIBLE. A full-screen glitch crash follows: SUBJECT EXCESSIVELY FOREIGN. SUBJECT INSUFFICIENTLY AUTHENTIC. CONTRADICTION DETECTED. THE STANDARD IS INCOHERENT. RECALIBRATION FAILED. UNIT SM-1882 CANNOT RESOLVE A QUESTION IT INVENTED.

The crash resolves into the final screen: a live ACCEPTANCE INDEX random-walking every 2.3 seconds against fictional headlines, each swing labeled with its cause in legible type. One status shows at a time, derived from the index band, and it never settles:

| Index band | Status |
|---|---|
| above 72 | AAPI IDENTITY HONORARY |
| 52 to 72 | AAPI IDENTITY UNDER REVIEW |
| 32 to 52 | AAPI IDENTITY PROBATIONARY |
| below 32 | AAPI IDENTITY REVOKED |

Fine print: SUBJECT INPUT: NOT A FACTOR · METHODOLOGY LICENSED FROM: MILLER, S., WASHINGTON D.C. (2025) · UNIT SM-1882. A RUN NEW SCREENING button soft-resets the session.

---

## Sound Design, As Built

Fully synthesized, clinical register. Final mix after iteration:
- Power-on swell and low hum at initiation; blips and a two-note confirmation through the boot crawl.
- Soft low confirmation (420Hz sine over a 210Hz undertone) on every input. The original rising sweep was removed from inputs entirely; no per-input "pew" survives.
- Deny tone: low descending triangle, softened from the original square.
- Compliment chirp lowered to 660/880Hz.
- Flagging: rapid five-burst two-tone klaxon (980/740Hz squares, ~105ms apart), reading as a security system tripping.
- Crash: heavy descending hit plus three-pulse alarm. The verdict payoff is the loudest moment in the toy by design.
- Ticker tick: gentle 520Hz sine every 2.3 seconds.
- Header mute toggle.

---

## Naming

**SATO-MILLER AAPI IDENTITY TEST.** The two-surname convention mimics real psychometric instruments (Voight-Kampff, Myers-Briggs, Stanford-Binet) and keeps the clinical deadpan. The hyphen fuses a Japanese surname to an Anglo one, putting the hyphenated identity into the letterhead before a single question is asked. The Stephen Miller reference is deliberate and lives inside the machine as fine print, not on the door, preserving the slant that makes the satire work.

**Unit SM-1882.** Reads as ordinary product numbering until someone recognizes the Chinese Exclusion Act. The machine's serial number and its oldest open case file share a year.

---

## Design Rules (held throughout)

1. The satire targets the apparatus and the social logic it encodes, never the subject.
2. No real biometrics. Camera processed in-browser only; nothing recorded, stored, or transmitted; the gate notice says so explicitly and prominently.
3. No gender detection, ever. The deprecated-module gag and gender-neutral archetypes resolve the problem without building a classifier to serve a joke.
4. Archetypes, not celebrities. The machine never learned anyone's name.
5. Deadpan clinical register. The machine never winks.
6. Every module derives from a recognizable lived interaction.

---

## Running and Deployment

**Local:**
```
cd <folder containing the file>
python3 -m http.server 8000
```
Open Safari to `http://localhost:8000/sato_miller.html`. Camera and MediaPipe require the secure context (localhost or https), so no file:// double-clicking. Both sibling toys run off the same server simultaneously. Stop with Ctrl+C; free a held port with `lsof -ti:8000 | xargs kill`.

**Deploy:** Own GitHub repository, subdomain on mleungphd.org (candidates: sm.mleungphd.org, aapi.mleungphd.org), CNAME to GitHub Pages. The https there gives the camera the same secure context as localhost.

---

## Graceful Degradation

- MediaPipe CDN failure with camera active: ocular panel falls back to a center-estimate crop; tracking feed runs without the mesh.
- No camera: simulated landmark constellation (counter reads 478 (SIM)) and a drifting synthetic pupil; every act, gag, and the full interview remain intact.
- The toy never dead-ends.

---

## Open Options (none blocking)

- [Inference] Mobile performance: detectForVideo runs per frame over two canvas draws, smooth on desktop; if phones stutter after deployment, throttling detection to alternate frames is a one-line change.
- Question pool, compliment bank, headline list, and name rotation are all flat arrays; expanding any of them is copy-paste.
- The ticker's starting index (62) sits mid-band; starting at a boundary (53) would make the first status flip arrive sooner.

---

*Designed by Maxwell Leung, Ph.D. ©2026 / #VibeCodingIsLife*
