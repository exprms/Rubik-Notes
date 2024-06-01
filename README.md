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
  - d
 

  
## WCA Cube verstellen:
Algorithmus, beginnend mit weiß oben und grün vorne:
```
B' R2 B2 R2 U' R2 B2 D2 F2 R2 D2 B L D2 R2 D B' F R B2
```

## Source

- [Cube lösen](https://www.youtube.com/watch?v=HYyrneUsJ88)
- [WCA Cube verstellen](https://www.youtube.com/watch?v=7DJV3X6BnvE)
