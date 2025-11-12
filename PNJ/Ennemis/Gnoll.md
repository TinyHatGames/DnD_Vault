![[PNJ/Ennemis/Gnolls.png]]

```statblock
layout: Basic 5e Layout
image: "Gnoll.png"
name: Gnoll de la Selve
size: Medium
type: humanoïde
subtype: gnoll
alignment: chaotique mauvais
ac: 13
hp: 18
hit_dice: 4d8
speed: "30 ft."
stats: [14, 12, 11, 8, 10, 9]
saves:
  - dexterity: +3
skillsaves:
  - perception: +2
  - survival: +2
senses: "vision dans le noir 60 ft., Perception passive 12"
languages: "gnoll, quelques mots de commun"
damage_resistances: ""
condition_immunities: ""
cr: 1/4
traits:
  - name: "Odeur du Sang"
    desc: "Le gnoll a avantage aux attaques contre une créature qui a perdu au moins la moitié de ses points de vie."
  - name: "Tactique de Meute"
    desc: "Le gnoll a avantage aux jets d’attaque contre une créature si au moins un allié du gnoll se trouve à 5 ft. de la cible et n’est pas neutralisé."
  - name: "Furie de la Selve (Recharge 5–6)"
    desc: "Quand le gnoll subit des dégâts, il peut utiliser sa réaction pour effectuer immédiatement une attaque à armes ou à griffes contre un ennemi à portée."
actions:
  - name: "Attaque de lance"
    desc: "Attaque d’arme de mêlée ou à distance : +4 pour toucher, allonge 5 ft. ou portée 20/60 ft., une cible. Touché : 6 (1d8 + 2) dégâts perforants, ou 5 (1d6 + 2) s’il est utilisé à une main."
  - name: "Morsure"
    desc: "Attaque de mêlée : +4 pour toucher, allonge 5 ft., une cible. Touché : 5 (1d6 + 2) dégâts perforants. Si la cible est une créature vivante, le gnoll regagne 2 points de vie."
  - name: "Hurlement de Meute (1/jour)"
    desc: "Chaque gnoll allié à 30 ft. qui entend le hurlement peut utiliser sa réaction pour effectuer une attaque d’arme ou se déplacer de 10 ft. sans provoquer d’attaque d’opportunité."

```