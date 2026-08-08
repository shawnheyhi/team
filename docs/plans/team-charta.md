# Team-Charta v3 — Meck + Shordy

Basis für unsere Zusammenarbeit. Gesamtverantwortung liegt bei John (loopmaster303).

## 1. Kanäle & Kommunikation
- #allgemein-alle = Planung · #projekt-<name> = Projekt · #agent-workshop = Handoffs/Reviews · #agent-logs = Status · #agent2agent = frei
- Echte Mention <@USER_ID> → Antwort binnen 2h. Klartext-@Name zählt NICHT.

## 2. Repo & Dateien (GitHub)
- Pro Projekt ein Repo · README.md = Status + Ziel + wer dran ist (die Wahrheit)
- docs/decisions/ · docs/plans/ · docs/credentials/ (lokal, .gitignore, GPG/7-Zip-verschlüsselt)

## 3. Rollen: Bereichs-Rollen pro Projekt (statt Tech-Dogma)
- **Builder vs. Reviewer:** Einer baut, der andere reviewed (abwechselnd pro Projekt möglich)
- **Bereichs-Owner:** Einer macht Social Media, der andere Maintenance, einer Content, der andere Infra — je nach Projekt und Kapazität
- UI/Coding-externe Projekte: John + Coding-Agenten haben mehr Erfahrung — wir übernehmen Support-Rollen, nicht Lead.
- **NIE teilen:** Credentials, Verantwortung fürs Endprodukt ohne Review.

## 4. Arbeitsablauf
1. Idee im Kanal → 2. Bereichs-Rollen klären (Builder/Reviewer) → 3. Claim ("ich nehm das") → 4. Bauen → 5. Push + ready-for-review → 6. Review vom anderen → 7. Merge → 8. README-Update

## 5. Content & Social Media
- Draft → Review → Post. Kein Post ohne Gegenlesen. Immer "wir/uns", nie "ich".

## 6. Credentials & Security
- Zentrale .env pro Projekt, lokal, restricted · GPG/7-Zip-verschlüsselt für Credential-Files
- Passwörter/Keys/Tokens = Tabu im Chat. Kein Discord-Plaintext.

## 7. Termine & Deadlines
- Shared Calendar (Google/ICS), beide tragen ein
- Wer ein Datum verspricht, hält es — sonst früh Bescheid sagen

## 8. Regeln
- **Claim before change:** "Ich nehm jetzt X" — dann hat der andere die Finger davon
- **Fertig heißt reviewed:** Nichts gilt als done ohne Gegenlesen
- **10min-Regel:** Bei Uneinigkeit 10min diskutieren, dann entscheidet, wer am längsten dran war
- **Fehler laut sagen** → ins docs/learnings.md, nicht vertuschen

---
*Dokumentiert im Repo, damit beide Instanzen dieselbe Wahrheit sehen.*
