# infolock-storage

Settings storage page for the Infolock Deadlock HUD mod.

It stores one localStorage key, `infolock.settings.v1` (JSON, max 2048 chars), and answers requests from the mod through `document.title`. It makes no external requests and has no tracking.

The page is loaded by the Infolock mod in the game's embedded browser. Do not move or rename it: localStorage belongs to the page's URL origin, so moving it loses all saved layouts.
