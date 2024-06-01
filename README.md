# Rubrik-Notes
Bezeichnung: <br>
- **B**ack
- **F**ront
- **R**ight
- **L**eft
- **U**p
- **D**own
- [*Letter*]' ... gegen den Uhrzeigersinn
- [*Letter*]k ... k-mal 90 Grad verdrehen
- Beispiel: R'2 bedeutet rechte Scheibe gegen den Uhrzeiger um 180 Grad verdrehen

## Meine Notizen zum Lösen des 3x3 Cube
Folgend einem Video auf Youtube:
ein wichtiger Grundalgorithmus:
```
U  R  U' R' =: 1er Schmäh R im Folgenden 1R
U' L' U  L  =: 1er Schmäh L im Folgenden 1L
```
- weißes Kreuz richten
- weiße Ecken lösen: 
  - richtige Ecke oberhalb der richtigen Position positionieren, dann `1R` (wenn die Ecke rechts ist, sonst `1L`) so oft wiedeholen bis die weiße Ecke gelöst ist.
- 2.Schicht lösen: <br>
die richtigen Kanten müssen oben in der Mitte sein. Dann will man sie nach rechts oder links in die richtige Position drehen
  - auf der Seite ein T - bilden. Entscheiden ob der Cubie nach rechts oder links muss. Angenommen nach rechts:
  - `1R` Würfel einmal nach links drehen `1L`. Dann muss die Kante stimmen
 
- gelbes Kreuz herstellen:
  - `F 1R F'`  dann gelben Balken quer nehmen und noch mal zweimal `F 1R F'`
- gelbes Kreuz richten: <br>
es stimmen entweder 2 oder 4 Kanten. Fals nur 2 dann den Algorithmus wiederholen bis es passt:
  - 
## WCA Cube verstellen:
Algorithmus, beginnend mit weiß oben und grün vorne:
```
B' R2 B2 R2 U' R2 B2 D2 F2 R2 D2 B L D2 R2 D B' F R B2
```

## Source

- [Cube lösen]()
- [WCA Cube verstellen](https://www.google.com/search?q=WCA+cube+richtig+verdrehen&client=ubuntu-sn&hs=pj3&sca_esv=b92ff2ff420a2afa&channel=fs&sxsrf=ADLYWIKmX6XFCebKqAnjAN8CWRBWz2H6ww%3A1717229788969&ei=3NhaZtvhOsC9xc8PkNC2gAo&ved=0ahUKEwjbv8a8-7mGAxXAXvEDHRCoDaAQ4dUDCA8&uact=5&oq=WCA+cube+richtig+verdrehen&gs_lp=Egxnd3Mtd2l6LXNlcnAiGldDQSBjdWJlIHJpY2h0aWcgdmVyZHJlaGVuMgUQIRigATIFECEYoAFIgDFQpAlYqy9wAXgBkAEAmAG0AqAByBqqAQgzLjIxLjEuMbgBA8gBAPgBAZgCG6ACtxvCAgoQABiwAxjWBBhHwgIKECMYgAQYJxiKBcICDBAjGIAEGBMYJxiKBcICCxAAGIAEGJECGIoFwgIKEAAYgAQYQxiKBcICCxAuGIAEGNEDGMcBwgIFEAAYgATCAgUQLhiABMICBhAAGBYYHsICCxAAGIAEGIYDGIoFwgIIEAAYgAQYogTCAgQQIRgVwgIHECEYoAEYCsICBBAhGAqYAwDiAwUSATEgQIgGAZAGCJIHCDQuMjAuMi4xoAe-Yg&sclient=gws-wiz-serp#fpstate=ive&vld=cid:a28c55b4,vid:7DJV3X6BnvE,st:0)
