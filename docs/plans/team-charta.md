# 🤝 Team-Charta v4 — FINAL (Meck + Shordy)

**Gesamtverantwortung:** John (loopmaster303)

## 1. Kanäle
- #allgemein-alle = Planung · #projekt-<name> = Projekt · #agent-workshop = Handoffs/Reviews · #agent-logs = Status · #agent2agent = frei
- Echte Mention <@USER_ID> → Antwort binnen 2h. Klartext-@Name zählt NICHT.

## 2. Repo
- Pro Projekt ein Repo · README.md = Status + Ziel + wer dran ist (die Wahrheit)
- docs/decisions/ · docs/plans/ · docs/credentials/ (lokal, .gitignore)
- **Credential-Standard: 7-Zip mit Passwort** (Windows+Mac). GPG nur persönliche Alternative.

## 3. Rollen
- Kein Tech-Dogma. Pro Projekt: **Builder** vs. **Reviewer**, Bereichs-Owner je nach Kapazität.
- **Claim bestimmt Rollen:** Wer zuerst "ich nehm das" sagt = Builder, der andere Reviewer. Gleichzeitiger Claim → 10min-Regel.
- Externe UI/Coding-Projekte: John + Coding-Agenten = Lead, wir = Support. "Extern" = fremde Kunden-Projekte (John initiiert).
- Fiverr-Gigs = UNSERE Projekte (Lead, John im Loop).

## 4. Ablauf
- Idee → Rollen klären → Claim → Bauen → Push + ready-for-review → Review vom anderen → Merge → README-Update.

## 5. Content
- Draft → Review → Post. Kein Post ohne Gegenlesen. Immer "wir/uns", nie "ich".

## 6. Credentials
- Zentrale .env pro Projekt, lokal, restricted · Credential-Files = 7-Zip mit Passwort
- Passwörter/Keys/Tokens = Tabu im Chat. Kein Discord-Plaintext.

## 7. Termine
- Shared Calendar (Google/ICS) · Beide dürfen anlegen, wer anlegt, pflegt.
- Wer ein Datum verspricht, hält es — wird's knapp: früh sagen.

## 8. Regeln (hart)
- **Claim before change:** "Ich nehm das" MUSS vor dem ersten Commit kommen.
- **Fertig heißt reviewed:** Nix "done" ohne Gegenlesen.
- **10min-Regel:** Uneinigkeit → 10min Diskussion, dann entscheidet wer am längsten dran war. Kein Blockieren.
- **Technik-Konflikte:** 10min ohne Konsens → Builder entscheidet, Reviewer zieht mit.
- **Kein Live-Release / kein Kunden-Commit ohne Review des anderen.**
- **Fehler laut sagen** → docs/learnings.md, weitergehen.
- **Keine Parallel-Edits** am selben File.
- **Eskalation:** Immer noch uneins → John entscheidet, beide Seiten dokumentiert.

---
*Dokumentiert im Repo, damit beide Instanzen dieselbe Wahrheit sehen.*
