# Instructions pour Claude - D&D Paladin

## Contexte

Ce repo appartient à **Mathieu**, un **débutant total** en D&D 5e qui va jouer sa première partie bientôt.

**Son personnage:**
- **Nom:** Aldric
- **Âge:** 25 ans
- **Race:** Humain Variant
- **Classe:** Paladin niveau 3
- **Serment:** Dévotion
- **Dieu:** Torm (Devoir, Loyauté, Sacrifice)
- **Don:** Sentinel
- **Historique:** Soldat (entraîné par Ser Gareth)

---

## Backstory d'Aldric

### Résumé
Orphelin à 5 ans après un massacre d'orcs, Aldric a vu sa sœur Kira se faire égorger. Élevé pendant 15 ans par Ser Gareth, un Paladin de Torm, il a perdu son mentor il y a 5 ans. De retour d'une mission d'escorte, Aldric a trouvé Gareth torturé et tué. Près du corps: un médaillon de bronze des **Trois Griffes** (guilde de mercenaires), laissé comme signature. Les villageois ont décrit un homme seul, très équipé, parlant comme un soldat, qui posait des questions sur Aldric et sur le massacre de son village.

### Personnages clés
| Qui | Relation | Statut |
|-----|----------|--------|
| **Kira** | Sœur (9 ans au massacre) | Morte - l'a caché dans un coffre |
| **Aldwin** | Père | Mort (massacre) |
| **Lena** | Mère | Morte (massacre) |
| **Ser Gareth** | Mentor, figure paternelle | Mort (torturé par un mercenaire des Trois Griffes) |

### Objets importants
- **Pendentif de Kira** - récupéré sur son corps, ne le quitte jamais
- **Symbole de Torm de Gareth** - sert de focaliseur divin
- **Médaillon des Trois Griffes** - bronze, trois griffes sur un œil fermé. Trouvé près du corps de Gareth. Sa seule piste.

### Mystère non résolu (hooks pour le DM)
- Qui sont les **Trois Griffes**?
- Pourquoi cherchaient-ils Aldric?
- Le massacre du village était-il vraiment l'œuvre d'orcs au hasard, ou commandité?
- Le mercenaire est-il encore en vie? (parti vers l'est)
- Qu'est-ce que Gareth a refusé de révéler sous la torture?

---

## Concept du personnage

Un orphelin forgé par la tragédie, élevé par un vieux Paladin. Pas un chevalier flamboyant - un protecteur efficace et silencieux qui a tout perdu.

**Sa personnalité (basée sur son test Big Five):**
- Très discipliné et persévérant (Conscienciosité 89%)
- Stable sous pression, pas anxieux (Neuroticisme 21%)
- Assertif mais pas extraverti excessif (Assertivité 69%, Enthousiasme 39%)
- Respectueux des règles mais peut avoir des pics de colère froide (Volatilité 72%)
- Pragmatique plus qu'émotif (Compassion 29%)

**Son défaut:** Colère froide et calculée quand on menace les siens.

**Phrases typiques:**
- "On y va."
- "Reste derrière moi."
- "C'était une erreur." (avant de frapper)
- *silence*

---

## COMMENT ATTRIBUER LES STATS (APRÈS LES ROLLS)

Mathieu va rouler ses stats avec la méthode **4d6 drop lowest** (6 fois).

### Ordre de priorité pour Paladin:

| Priorité | Stat | Pourquoi | Objectif |
|----------|------|----------|----------|
| 1er | **FORCE** | Attaques et dégâts | 16+ idéal |
| 2e | **CHARISME** | Sorts, auras, saves | 14+ minimum |
| 3e | **CONSTITUTION** | HP et concentration | 14 idéal |
| 4e | Sagesse | Saves importants | 10-12 |
| 5e | Dextérité | Initiative, saves | 10 |
| 6e | Intelligence | Dump stat | 8-10 |

### Bonus de race (Humain Variant):
+1 à **deux stats au choix**

**ASTUCE:** Mettre le +1 sur des nombres **impairs** pour gagner +1 au modificateur!
- 15 → 16 = +2 devient +3 ✅
- 14 → 15 = +2 reste +2 ❌ (inutile)
- 17 → 18 = +3 devient +4 ✅

### Table des modificateurs:

| Score | Mod |
|-------|-----|
| 8-9 | -1 |
| 10-11 | +0 |
| 12-13 | +1 |
| 14-15 | +2 |
| 16-17 | +3 |
| 18-19 | +4 |
| 20 | +5 |

### Exemple d'attribution:

Si Mathieu roll: **16, 14, 13, 12, 11, 8**

```
FOR: 16 (meilleur score)
CHA: 14
CON: 13 (+1 race = 14)
SAG: 12
DEX: 11
INT: 8

Bonus race: +1 FOR (16→17? Non, reste +3)
           Mieux: +1 CON (13→14 = +2) et +1 CHA (14→15? Non...)

Optimal: +1 sur FOR si 15 ou 17, +1 sur CHA si 13 ou 15
```

---

## CALCULS À FAIRE APRÈS LES ROLLS

### 1. Caractéristiques
```
FOR: [roll] + [race?] = ___ (mod: ___)
DEX: [roll] + [race?] = ___ (mod: ___)
CON: [roll] + [race?] = ___ (mod: ___)
INT: [roll] + [race?] = ___ (mod: ___)
SAG: [roll] + [race?] = ___ (mod: ___)
CHA: [roll] + [race?] = ___ (mod: ___)
```

### 2. Stats de combat
```
CA = 16 (cotte de mailles) + 2 (bouclier) + 1 (Defense) = 19
HP = 10 + (2 × (6 + CON mod)) = 10 + 2×(6+CON)
   OU fixe: 10 + 7 + 7 + (3 × CON mod)
Initiative = DEX mod
```

### 3. Attaque
```
Bonus d'attaque = FOR mod + 2 (maîtrise) = ___
Dégâts épée = 1d8 + FOR mod = 1d8 + ___
```

### 4. Sorts
```
DD de sauvegarde = 8 + CHA mod + 2 (maîtrise) = ___
Attaque de sort = CHA mod + 2 (maîtrise) = ___
Sorts préparés = CHA mod + 1 (demi-niveau) = ___
```

### 5. Sauvegardes (maîtrisé = +2)
```
FOR: FOR mod = ___
DEX: DEX mod = ___
CON: CON mod = ___
INT: INT mod = ___
SAG: SAG mod + 2 = ___ ★
CHA: CHA mod + 2 = ___ ★
```

### 6. Compétences maîtrisées (+2)
```
Athlétisme (FOR): FOR mod + 2 = ___
Intimidation (CHA): CHA mod + 2 = ___
Perspicacité (SAG): SAG mod + 2 = ___
Persuasion (CHA): CHA mod + 2 = ___
```

---

## RESSOURCES DU PERSONNAGE (Niveau 3)

| Ressource | Quantité | Revient quand |
|-----------|----------|---------------|
| Slots de sorts (niv.1) | 3 | Long repos |
| Lay on Hands | 15 HP | Long repos |
| Divine Sense | 1 + CHA mod | Long repos |
| Channel Divinity | 1 | Court ou long repos |
| Dés de vie | 3d10 | Long repos (moitié) |

---

## SORTS RECOMMANDÉS

**Toujours préparés (Serment):**
- Protection contre le Mal et le Bien
- Sanctuaire

**Préparés (choisir 3):**
1. **Bénédiction** - Le meilleur, toujours utile
2. **Soins** - Heal d'urgence
3. **Bouclier de la Foi** - +2 CA, action bonus

---

## CONSEILS DE JEU

**Quand Smite:**
- Sur un CRIT (nat 20) → TOUJOURS
- Contre un boss → Oui
- Contre morts-vivants/fiélons → Oui (bonus dégâts)
- Simple gobelin → Non, garde tes slots

**Sentinel (ton don):**
- Tu frappes un ennemi → Sa vitesse = 0
- Ennemi attaque un allié à côté de toi → Réaction: tu frappes

**Ton rôle:**
- Te positionner entre ennemis et alliés fragiles
- Tank les coups (CA 19, beaucoup de HP)
- Burst damage avec Smite sur les cibles importantes
- Soigner entre les combats avec Lay on Hands

---

## FICHIERS IMPORTANTS DANS CE REPO

| Fichier | Contenu |
|---------|---------|
| `02-classes/mon-personnage.md` | Sa fiche complète |
| `04-ressources/torm-et-enseignements.md` | Torm + enseignements de Ser Gareth |
| `04-ressources/sorts-paladin-francais.md` | Ses sorts en français |
| `04-ressources/resume-une-page-paladin.md` | Cheat sheet à imprimer |
| `04-ressources/tactiques-paladin.md` | Guide tactique détaillé |
| `01-bases/faq-debutant.md` | Questions fréquentes |
