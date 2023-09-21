# ARlebnispfade OBK Content Hub

Das production-repo nutzt [11ty](https://www.11ty.dev) für die strukturierte Ablage von Content und das generieren statischer Seiten.

## Ordnerstruktur

### `/strasse-der-arbeit`, `/whiel`, `/wipperfuerth`
Die einzelnen Pfade

### `/wipperfuerth` als Beispiel
```
ar-media                    Content für die ARlebnise
    images                  Dateien für NFT(Natural Feature Tracking) und die Bilder, aus denen die NFT-Dateien erzeugt wurden
    models                  3D Modelle (mit oder ohne Animation)
    videos                  Videos
images                      Thumbnails für den Pfad und die einzelnen Spots
000-pulvermuseum.md         Markdown mit Informationen zu dem ARSpot, inklusive welcher Content präsentiert werden soll
...
```

### `/wipperfuerth/000-pulvermuseum.md` als Beispiel
```
title:                      Titel des Spots
image:                      Name des zugehörigen image
layout:                     Name des zu verwendeten Layouts
gmaps:                      Google Maps Link
coords:                     Longitude/Latitude Koordianten
info:                       (Historische) Informationen zum Spot
arDesc:                     Was kann man hier Erleben
ar:                         Welcher Content wird an diesem ARSpot verwendet
```