# KiCad 3D models for FerroEDA on the web

This repository holds no models itself: its workflow takes KiCad's official 3D model library
([kicad-packages3D](https://gitlab.com/kicad/libraries/kicad-packages3D)), gzips every STEP
file and publishes them on GitHub Pages, where [FerroEDA](https://github.com/ferroeda/ferroeda)'s
browser app loads them:

    https://ferroeda.github.io/ferroeda-3dmodels/<library>.3dshapes/<model>.step.gz

The files are unchanged apart from the gzip compression. `revision.txt` on the site gives the
kicad-packages3D commit they come from.

## Licence

The models are KiCad's, by the KiCad library contributors, and are licensed under the
[Creative Commons CC-BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/legalcode)
with an exception for designs that use them: see [LICENSE.md](https://gitlab.com/kicad/libraries/kicad-packages3D/-/blob/master/LICENSE.md),
also published on the site. They are not part of FerroEDA, which is not affiliated with the
KiCad project.
