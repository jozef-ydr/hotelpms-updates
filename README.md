# Hotel PMS — Updates

This repository only hosts the signed update packages of Hotel PMS (in **Releases**).
It contains no source code. Each release has two files:

- `HotelPMS-Setup-<version>.zip` — the compiled program package
- `latest.json` — the signed update notice (Ed25519)

The program installed at each hotel checks
`https://github.com/jozef-ydr/hotelpms-updates/releases/latest/download/latest.json`
and only accepts packages signed by the owner's key.
