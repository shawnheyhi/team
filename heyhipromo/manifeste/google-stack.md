# Google-Stack-Trennung (Stand 2026-08-09)

## Prinzip
- **Mail = himalaya** (IMAP): icloud, gmail, zoho-jm, zoho-socials. Dafür ist
  himalaya das Werkzeug — bewährt, IMAP-basiert.
- **Alles andere Google = gog** (gogcli.sh): Docs, Drive, Sheets, Contacts,
  Tasks, Calendar, YouTube/Playlists, etc. über die Google-API.

## gog auf Mac
- v0.35.0 (brew openclaw/tap/gogcli), Client hermes-gog-cli-505015
- credentials.json FLACH (client_id/client_secret top-level, NICHT unter installed)
- keyring_backend=file, Passwort in macOS Keychain (Service gog-keyring)
- Einstieg: ~/.local/bin/gog-wrapper (setzt Env, kein Klartext)
- Accounts: maation@gmail.com + juanmigueldj37@gmail.com (alle Scopes inkl. YouTube)
- YouTube: gog youtube playlists list --mine -a <email> (Johnny-Mysterio-Kanal)
- Shordy/Windows: selbst eingerichtet

## Regeln
- Nie Google-Mail-Funktionen über gog, wenn himalaya es kann (Mail-Flow = himalaya)
- Nie himalaya für Docs/Drive/YouTube etc. (nur gog)
- gog-Wrapper nutzen (nie nacktes gog ohne Env)
