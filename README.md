# Kiosk Server Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-kiosk-server-card.js` til `/config/www/ha-kiosk-server-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-kiosk-server-card/ha-kiosk-server-card.js?v=0.1.0
```

Tilføj derefter korttypen `custom:ha-kiosk-server-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
