![[Privé/PNJ/Personnages Importants/Images/Maro.png]]

Agent de [[Privé/Lieux/Villes/Koruha]] du [[Pacte des Initiés]]. En charge de la surveillance et de l'accompagnement / recrutement des joueurs. Ils commence l'aventure en se faisant passer pour un prisonnier.

Maro est un halfling d'un âge avancé avec les cheveux longs et une grande barbe blanche. Il porte une longue robe en laine (soutane) attachée par une corde simple qui cache un physique très impressionnant (possibilité de le voir avec un bon jet de perception).


```statblock
layout: Basic 5e Layout
image: "[[Maro_Lushan.jpg]]"
name: Mariel "Maro" Lushan
size: Medium
type: humanoïde
subtype: humain
alignment: neutre bon
ac: 15
hp: 45
hit_dice: 6d8+12
speed: "40 ft."
stats: [16, 16, 14, 12, 14, 10]
saves:
  - dexterity: +5
  - wisdom: +4
skillsaves:
  - acrobatics: +5
  - perception: +4
  - stealth: +5
  - insight: +4
  - athletics: +5
senses: "Perception passive 14"
languages: "Commun, Druidique (ancien), Langage codé du Pacte"
damage_resistances: "contondant, perforant et tranchant des attaques non magiques lorsqu'il est en défense sans armure"
condition_immunities: ""
cr: 2
traits:
  - name: "Défense sans armure"
    desc: "Tant qu’il ne porte pas d’armure et ne manie pas de bouclier, la CA de Maro est égale à 10 + son modificateur de Dextérité + son modificateur de Sagesse (CA 15)."
  - name: "Attaques de moine"
    desc: "Ses attaques à mains nues infligent 1d6 + 3 dégâts contondants et sont considérées comme magiques pour surmonter les résistances."
  - name: "Rafale de coups (Recharge 5–6)"
    desc: "Après avoir utilisé l’action Attaquer, Maro peut faire deux attaques supplémentaires à mains nues."
  - name: "Pas du vent"
    desc: "Maro peut dépenser une action bonus pour se désengager ou se replier sans provoquer d’attaque d’opportunité."
  - name: "Discipline du Pacte"
    desc: "Maro peut, en action bonus, concentrer son ki pour percevoir les flux de sève autour de lui. Pendant 1 minute, il bénéficie d’avantage aux tests de Perception et de Dextérité (Discrétion)."
  - name: "Vision du Fil"
    desc: "Maro perçoit les auras magiques ou lunaires comme des filaments de lumière. Il peut lancer *Détection de la magie* à volonté, portée réduite à 15 ft."
actions:
  - name: "Attaques multiples"
    desc: "Maro fait deux attaques à mains nues."
  - name: "Coup du Nœud"
    desc: "Attaque de mêlée à mains nues : +5 pour toucher, allonge 5 ft., une cible. Touché : 7 (1d6 + 3) dégâts contondants. La cible doit réussir un jet de sauvegarde de Constitution (DD 12) ou être étourdie jusqu’à la fin du prochain tour de Maro."
  - name: "Projectile de sève"
    desc: "Attaque à distance de ki : +5 pour toucher, portée 30 ft. Touché : 5 (1d4 + 3) dégâts de force. Ce projectile laisse une marque de sève luminescente sur la cible pendant 1 minute (utilisé pour suivre ou marquer)."
reactions:
  - name: "Déflexion des projectiles"
    desc: "Quand Maro est touché par une attaque à distance, il peut réduire les dégâts de 1d10 + 3. S’il réduit les dégâts à 0, il peut rattraper ou renvoyer le projectile."
```