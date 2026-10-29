# USEFUL media

Films, music and sound for the browser edition of USEFUL at
https://ish.support/useful, served through jsDelivr. Media files only: no
code. The game loads them from a release tag, for example
`https://cdn.jsdelivr.net/gh/IshSupport/useful-media@<tag>/films/A05.mp4`, so a
published build keeps working when newer media is added.

Films are the game's films re-encoded for the web (H.264, CRF 23, no audio
track). Music credits and licences are listed in the game's own reference
screen and in `audio/provenance.json`.

USEFUL is brought to you by Ish.

## Hosting

Served by GitHub Pages at https://ishsupport.github.io/useful-media/<version>/..., one folder per published game build, so a build keeps loading its own media. (jsDelivr refuses repositories over 50 MB, and this one is about 94 MB.)
