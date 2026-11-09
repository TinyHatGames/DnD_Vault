---
type: fabrication-image
session: 10
tags: [session, prive-mj, image]
---

# Prompts — Croquis des Gratte-Racines

Image réalisée avec l'outil intégré **image_gen**. Une variante de la passerelle a été conservée, puis le MJ a demandé une version de la première image sans les annotations sélectionnées par un masque. Version retenue : [[Privé/Sessions/Session 10/Images/Croquis des Gratte-Racines - sans annotations.png]]. Aucun placement dans le répertoire public avant sa remise en jeu.

## Génération

```text
Use case: illustration-story.
Asset type: a simple in-world player handout for a French Dungeons & Dragons campaign, a rough route sketch drawn by cave explorers called the Gratte-Racines.
Create ONE landscape sketch on a plain warm off-white sheet, viewed perfectly flat from above. Hand-drawn black ink, small uneven exploratory strokes, extremely sparse muted blue pencil for water. Large blank spaces, modest faint paper folds. Practical amateur field sketch, NOT a richly illustrated fantasy map and NOT an elaborate battlemap. No grid, no scale bar, no compass, no scenic border, no characters.

The geography must read as ONE continuous navigable route through these five successive areas. Arrange loosely in a wide zigzag, left to right; make all connections clearly visible and prevent any overlapping labels.
1) At far left, a small departure pool, connected to a single narrow winding underwater tunnel, marked with a thin handrail line along one wall. Labels "Départ" and "Siphon".
2) Tunnel emerges at a small dock in a large irregular cavern drawn as a SIMPLE outline. A few triangular crystal symbols on the walls, a small warm-water inlet marked by only three steam curls, a pool and ONE little bridge leading out. Labels "Quai" by the dock and "Passerelle" by the bridge. The bridge must connect the quay side to the old outpost.
3) Beyond the bridge, a tiny old stone outpost represented by THREE rough adjoining rectangular rooms and a corridor, labelled "Avant-poste". No furnishings. At its far exit draw ONE monumental door as two thick short parallel bars across the corridor, labelled "Grande porte". Do not draw the gate mechanism.
4) Beyond this door, an irregular room with TWO simple interconnected water basins and a clear dry path around them, labelled "Bassins". A tiny handwritten question mark in the margin here, suggesting uncertainty about danger without identifying anything. No monster or person.
5) From the basins a short stair goes up into ONE small dry rectangular chamber; write "Siraë" beside it, indicating the known destination where she worked. Keep that room completely empty.

Labels should be small casual handwritten French but readily legible, exact spellings as quoted. Only these eight names and the tiny question mark. No explanatory legend, no title, no other writing. Discrete arrowheads along the main route may guide direction. All five areas MUST be clearly physically connected in the stated sequence, without shortcuts.
Avoid any chest, treasure, corpse, bones, skull, hag, monster, nest, altar, mural, fresco, carved story, secret passage, roots, vegetation, magic mechanism diagram, or dungeon-master information. Show geographic landmarks known by guides only. The result must feel like a rough sketch an explorer can draw from memory in a minute.
```

## Correction

```text
Edit this existing dungeon route sketch. Preserve the landscape paper, rough ink and pale blue water style, all eight French labels, and the entire map except the geometry of the large crystal cavern around "Quai" and "Passerelle".

CRITICAL LOCAL CORRECTION: In the crystal cavern the small bridge labelled "Passerelle" must be the ONLY dry connection from the arrival quay to the outpost. Currently a dry strip/corridor above the bridge bypasses it. Remove that bypass. Make the cavern's pool extend all the way to the upper boundary of this cavern, splitting it into a western dry shore connected to "Siphon" and "Quai", and an eastern dry abutment connected to "Avant-poste". Reposition or lengthen the existing bridge so its left end is clearly ON the western dry shore and its right end clearly ON the eastern abutment. It should visibly span the water channel. No alternate dry connection above or below it. The cavern's north and south walls should interrupt the dry shores so one must cross the bridge to reach the old outpost. Keep one small thermal steam inlet and a few simple crystal marks. A dotted route should go Siphon -> Quai -> across this bridge -> Avant-poste. Keep the route and the bridge easily readable.

Do not change the departure pool, the underwater siphon, the three outpost rooms, the monumental door, the two interconnected final basins, the stairs or the empty final chamber marked "Siraë". Keep all labels spelled exactly as before. Do not add any new text, rooms, passages, monsters, treasure or secrets. This remains a very simple in-world guide's sketch, without battle grid.
```

## Suppression des annotations avec le masque fourni

```text
Use case: precise-object-edit.
There are TWO relevant recent images: a parchment dungeon map with pale blue water (the EDIT TARGET), and a black mask with white painted regions (the EDIT MASK). Identify them by their contents, regardless of their display order.

Remove the content under every WHITE region of the mask from the parchment map. These regions select all handwritten labels and the question mark. Erase "Départ", "Siphon", "Quai", "Passerelle", "Avant-poste", "Grande porte", "Bassins", "Siraë", and the lone "?". Seamlessly reconstruct the existing warm off-white paper texture underneath each annotation. No visible white paint, mask shapes, blur, or residual letters.

Preserve all the actual map artwork outside these selected annotations: the exact cave and room outlines, original pool shapes and sizes, original diagonal bridge, quay, narrow water tunnel with handrail, outpost walls, gate bars, final two basins, staircase and final room. Also preserve all dotted route arrows, crystal symbols, steam marks, pale blue water, paper folds and the original landscape framing. Do not redesign the map or change any geography. Produce the same map with ONLY the selected writing and question mark removed. Opaque paper background, no transparency.
```
