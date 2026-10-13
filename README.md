# ttsDecks

Hosted assets and source artwork for the Zombicide Tabletop Simulator scripts in TTS_scripts.

- `zombicide_cards.json`: card data loaded by the spawn script.
- `models/dashboard/`, `models/zombicide/` and `models/zombie-movement/`: assets still referenced by the saved game through GitHub.
- `ui/dark-fantasy/`: runtime UI sprites, current v3 portraits and editable high-resolution masters.
- `models/warrior/`: source model and exports for the separate warrior asset.

The superseded v2 portrait exports were removed. `models/zombicide/abominarat_final.obj` was removed after its SHA-1 matched a Steam Cloud URL in the newest TTS autosave on 2026-10-13; its collider remains referenced through GitHub. Other models remain because the save still references them here. Cleanup does not migrate older saves or other mods.
