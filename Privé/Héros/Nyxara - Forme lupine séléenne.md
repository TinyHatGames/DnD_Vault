---
type: forme_alternative
personnage: Nyxara
tags:
  - héros
  - séléen
  - lycanthropie
---

# Nyxara — Forme lupine séléenne

![[Nyxara - Forme lupine séléenne.png]]

Fiche calibrée pour le **niveau 4**. À un autre niveau, utiliser **12 PV par niveau** et remplacer les bonus fixes par le bonus de maîtrise actuel de [[Nyxara]].

```statblock
layout: Basic 5e Layout
image: "Nyxara - Forme lupine séléenne.png"
name: Nyxara, louve séléenne
size: Medium
type: humanoïde
subtype: métamorphe, séléen
alignment: alignement de Nyxara
ac: 15
hp: 48
hit_dice: 4d12 + 20
speed: "40 ft."
stats: [20, 14, 20, 8, 14, 8]
saves:
  - strength: +7
  - constitution: +7
  - wisdom: +4
skillsaves:
  - athletics: +7
  - perception: +4
  - stealth: +4
damage_vulnerabilities:
damage_resistances:
damage_immunities:
condition_immunities:
senses: "vision dans le noir 120 ft., odorat et ouïe aiguisés, Perception passive 14"
languages: "comprend les langues connues par Nyxara, mais ne peut pas parler"
cr: 4
spells: []
traits:
  - name: "Appel du sang"
    desc: "Dès que Nyxara voit du sang frais, elle se transforme immédiatement. Elle peut provoquer volontairement la transformation par une action bonus en se coupant et en subissant 1 dégât perforant ou tranchant."
  - name: "Métamorphose irrévocable"
    desc: "La transformation dure 24 heures et ne peut être interrompue volontairement, par une perte de connaissance ni par une dissipation ordinaire. À 0 PV, Nyxara reste sous cette forme, tombe inconsciente et effectue normalement ses jets contre la mort. Son équipement fusionne avec elle et devient inutilisable."
  - name: "Corps renversé"
    desc: "Sous cette forme, les qualités magiques de Nyxara deviennent physiques : Force et Constitution 20, Intelligence et Charisme 8. Elle conserve ses souvenirs, sa personnalité et le contrôle de ses décisions. Lors de la transformation et du retour à sa forme normale, conserver le nombre de PV manquants plutôt que de lui rendre tous ses PV."
  - name: "Silence de la bête"
    desc: "Nyxara ne peut pas parler, lancer de sorts, maintenir sa concentration ni utiliser un objet nécessitant une formule, une activation complexe ou des mains humanoïdes. Elle peut communiquer par gestes, regards et sons animaux."
  - name: "Armes séléennes"
    desc: "Les attaques naturelles de Nyxara sont magiques. Elle bénéficie d’un avantage aux tests de Sagesse (Perception) fondés sur l’odorat ou l’ouïe."
actions:
  - name: "Attaques multiples"
    desc: "Nyxara effectue deux attaques, dans la combinaison de son choix, avec ses griffes ou sa morsure."
  - name: "Morsure"
    desc: "Attaque d’arme de mêlée : +7 pour toucher, allonge 5 ft., une cible. Touché : 10 (1d10 + 5) dégâts perforants."
  - name: "Griffes"
    desc: "Attaque d’arme de mêlée : +7 pour toucher, allonge 5 ft., une cible. Touché : 12 (2d6 + 5) dégâts tranchants."
legendary_actions: []
bonus_actions: []
reactions: []
```

## Règles de transformation

- La vue de sang frais déclenche automatiquement la transformation.
- Nyxara peut donc se transformer volontairement en se coupant pour 1 dégât.
- La forme dure **24 heures complètes**, même à 0 PV.
- Le sang déjà sec ne déclenche rien.
- À la transformation, ses PV maximaux deviennent 48. Conserver ses PV manquants : si sa forme normale avait perdu 7 PV, la louve commence à 41 PV.
- Au retour, appliquer le même principe avec ses PV maximaux normaux.
- Un repos ne met pas fin à la transformation.

## Instinct choisi

Le choix effectué dans [[Vision de Nyxara]] accorde **les deux capacités** de l’instinct correspondant.

### Les tiens

#### Égide de la Meute

Lorsqu’un allié que Nyxara voit dans un rayon de 60 ft. doit subir des dégâts, elle peut utiliser sa réaction pour apparaître dans son espace et le déplacer dans le sien. Nyxara subit les dégâts à sa place, mais seulement à hauteur de **la moitié du total**, arrondie à l’inférieur. Ces dégâts ne peuvent pas être réduits une seconde fois.

Si l’effet touche une zone et devait également blesser Nyxara, elle subit normalement sa propre part en plus des dégâts interceptés.

#### Course du Cœur Blessé

Tant qu’un allié visible a perdu au moins un point de vie, la vitesse de Nyxara est doublée lorsqu’elle se déplace dans sa direction. Ce déplacement supplémentaire ne peut servir ni à s’éloigner de cet allié ni à poursuivre une autre cible.

### Le sang

#### Marque de la Proie

Après avoir blessé avec sa morsure une créature vivante possédant du sang, Nyxara peut en mémoriser le goût. Jusqu’à la mort de la cible ou la fin de la transformation, la première attaque qu’elle lui réussit à chacun de ses tours inflige un nombre de **d6 supplémentaires égal à son bonus de maîtrise**. Elle ne peut marquer qu’une seule proie à la fois.

#### Festin Écarlate

Une fois par combat, immédiatement après avoir réussi une morsure contre une créature vivante blessée, Nyxara peut boire son sang par une action bonus. Elle lance **un nombre de d8 égal à son bonus de maîtrise**, puis ajoute son modificateur de Constitution au total : actuellement **2d8 + 5 PV** récupérés.

Cette capacité est sans effet sur les morts-vivants, les créatures artificielles et les êtres dépourvus de sang.

### Le pouvoir

#### Peau du Colosse Lunaire

Nyxara est résistante (50% de dégats) aux dégâts contondants, perforants et tranchants provenant d’attaques non magiques qui ne sont pas faites avec une arme en argent. Elle a également l’avantage aux jets de sauvegarde de Force et de Constitution contre les effets qui veulent la déplacer, la renverser ou l’entraver.

#### Apothéose de la Bête

Une fois par combat, Nyxara peut utiliser une action bonus pour laisser la puissance lunaire gonfler son corps pendant une minute :

- elle devient de taille Grande ;
- son allonge augmente de 5 ft. ;
- elle gagne 8 PV temporaires, soit deux fois son niveau ;
- la première attaque de mêlée réussie à chacun de ses tours inflige 1d8 dégâts de force supplémentaires ;
- elle ne peut être déplacée ou mise à terre contre sa volonté.

### La nuit

#### Voile de la Lune Morte

Un nombre de fois par transformation égal à son bonus de maîtrise, Nyxara peut devenir invisible par une action bonus pendant une minute. L’invisibilité prend fin immédiatement après qu’elle effectue une attaque, inflige des dégâts ou entre volontairement en pleine lumière.

#### Croc de l’Entre-Nuit

Lorsque Nyxara réussit une attaque contre une créature qui ne peut pas la voir, ou qui n’a pas encore joué son premier tour du combat, l’attaque inflige un nombre de **d8 supplémentaires égal à son bonus de maîtrise**. La cible ne peut pas effectuer de réaction et doit réussir un jet de sauvegarde de Constitution DD 15 ou tomber à terre.

Nyxara ne peut utiliser cette capacité qu’une fois par tour.
