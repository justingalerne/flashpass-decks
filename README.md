# flashpass-decks

Fichiers publics lus par l'application **FlashPass** (Android) :

- `decks.json` — liste des decks proposés dans l'app ;
- `*.apkg` — decks téléchargeables, importés dans AnkiDroid ;
- `PRIVACY.md` — politique de confidentialité de l'app.

## Format de `decks.json`

```json
{ "decks": [
  { "name": "…", "description": "…", "notes": 68, "url": "https://raw.githubusercontent.com/justingalerne/flashpass-decks/main/peg.apkg" },
  { "name": "…", "description": "…", "ankiweb": "https://ankiweb.net/shared/info/<id>" }
] }
```

`url` : deck téléchargé par FlashPass puis tendu à AnkiDroid. `ankiweb` : simple lien
vers la fiche AnkiWeb (decks tiers, non redistribués). Les `.apkg` sont exportés depuis
Anki **sans planification** pour rester légers.

FlashPass n'est pas affilié à Anki ni à AnkiDroid.
