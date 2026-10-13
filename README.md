# Naija Linework

Een browsertool die echte straten in Nigeria omzet in 3D-lijnwerk met rastertonen, voor manga- en stripachtergronden.

**Website:** https://faith-al.github.io/Naija-Linework/

## Wat het doet

- Haalt gebouwen, wegen, water en groen op uit OpenStreetMap en bouwt er een 3D-scène van.
- Tekent die scène als manga: zwarte lijnen, rastertonen, zwarte vlakken en schaduwen.
- Voegt Nigeriaanse straatbeelden toe: golfplaatdaken, watertanks, palmbomen, mensen, danfo's, keke's, okada's, elektriciteitspalen met draden, reclameborden en marktkraampjes.
- Toont een satellietbeeld van dezelfde plek ernaast, met links naar Google Earth en Street View.
- Slaat op als PNG (tot 4800 px, ook met transparant papier) of als 3D-model (GLB) voor Blender of Clip Studio Paint.

## Laadt de kaart niet?

Ga naar openstreetmap.org, zoom in op je plek, klik op **Exporteren** en laad het bestand `map.osm` in de tool met **Kaartbestand laden (.osm)**.

## Bronnen

- Kaartdata © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), ODbL. Vermeld deze bron bij tekeningen die je publiceert.
- 3D-weergave met [three.js](https://threejs.org) (MIT), kaartje met [Leaflet](https://leafletjs.com) (BSD-2).
- Satellietbeeld © Esri, Maxar, Earthstar Geographics.

Hoogtes die niet in OpenStreetMap staan, worden geschat. Bomen, mensen, voertuigen en straatmeubilair worden willekeurig geplaatst.
