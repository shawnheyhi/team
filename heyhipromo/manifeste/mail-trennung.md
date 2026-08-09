# Mail-Trennung: privat (iCloud) vs. hey-hi.cloud (Geschäft via Zoho-Weiterleitung)

Konvention seit 2026-08-09. Ziel: private und hey-hi.cloud-Mails NIEMALS
verwechseln, obwohl beide über dasselbe iCloud-Postfach / Himalaya laufen.

## Empfänger-Übersicht
- **Privat**: `meckeljohn@icloud.com` (direkt an iCloud) — der Dummy-/Privat-Posten.
- **Geschäft hey-hi.cloud**: 4 Zoho-Adressen `@hey-hi.cloud` → **weitergeleitet an
  `meckeljohn@icloud.com`** (Zoho-Forwarding). Diese Mails landen im selben
  iCloud-Postfach, sind aber als Weiterleitung erkennbar.

## Unterscheidung im Postfach (wie ich sie erkenne)
- **Direkt privat**: `Delivered-To: meckeljohn@icloud.com` / Absender ist
  iCloud-Gespräch → privat behandeln.
- **Weitergeleitet (Geschäft)**: Zoho-Forwarding setzt `Resent-From`
  (oder `From: <die @hey-hi.cloud-Zieladresse>` + `Sender`) auf eine
  hey-hi.cloud-Adresse. Erkenne ich an der Zoho-Adresse im Absender-/Original-
  Header. → Geschäft behandeln, DRAFT für die hey-hi.cloud-Adresse.

## Draft-/Antwort-Mechanik
- Ich DRAFTE Antworten, schlage Handlungsoptionen vor. NIE automatisch senden
  (Senden bleibt manuell im Browser, weil Zoho Free kein SMTP für Clients hat).
- Drafts sauber kennzeichnen: `[hey-hi.cloud Draft]` / `[Privat Draft]` im
  Betreff-Präfix, und im Text die ZIEL-Adresse der Antwort nennen.

## Paralleler Kanal (Zoho-Webmail)
- Senden läuft manuell über Zoho-Webmail (`mail.zoho.eu`) mit der jeweiligen
  @hey-hi.cloud-Adresse. Ich bereite Text/Drafts vor; John sendet.

## WICHTIG
- Nie hey-hi.cloud-Mails als privaten iCloud-Postfachbestand verrechnen.
- Nie private Technik (iCloud-Dummy) als hey-hi.cloud-Absender ausgeben.
- 4 Zoho-Adressen (Stand 2026-08-09):
  1. `john.meckel@hey-hi.cloud` (Haupt/Geschäft)
  2. `jm@hey-hi.cloud` (Legacy von Hostinger)
  3. `socials@hey-hi.cloud` (Social Media / Newsletter-Kanal)
  4. `mailadmin@hey-hi.cloud` (Zoho-Admin-Postfach, bereits an meckeljohn-iCloud verknüpft)
