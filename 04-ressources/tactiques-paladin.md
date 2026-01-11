# Guide Tactique - Paladin Niveau 3

> Ce guide t'aide à prendre des décisions en combat et à gérer tes ressources.

---

## TON RÔLE EN COMBAT

```
Tu es le MUR entre les ennemis et tes alliés.

Objectifs:
1. Absorber les dégâts (CA 19, bons HP)
2. Contrôler le terrain (Sentinel)
3. Éliminer les menaces prioritaires (Smite)
4. Garder le groupe en vie (Lay on Hands, Soins)
```

---

## ARBRE DE DÉCISION - DÉBUT DE COMBAT

```
Le combat commence. Que faire au Round 1?

                    ┌─────────────────────┐
                    │ Combien d'ennemis?  │
                    └─────────────────────┘
                              │
              ┌───────────────┼───────────────┐
              ▼               ▼               ▼
         1-2 ennemis    3-5 ennemis      6+ ennemis
              │               │               │
              ▼               ▼               ▼
        ATTAQUE +       BÉNÉDICTION      BÉNÉDICTION
        Smite si boss   puis attaque     (priorité!)
                        round 2
```

### Questions à te poser Round 1:

| Question | Si OUI | Si NON |
|----------|--------|--------|
| Combat va durer 3+ rounds? | Bénédiction | Attaque directe |
| Y a-t-il un boss/menace majeure? | Garde Smite pour lui | Smite si crit |
| Allié fragile (mage) exposé? | Positionne-toi devant lui | Position offensive |

---

## ARBRE DE DÉCISION - TON TOUR

```
C'EST TON TOUR - CHECKLIST

ÉTAPE 1: ÉVALUATION (2 secondes)
├── Concentration active? → Ne pas lancer un autre sort [C]
├── Allié à 0 HP? → Priorité: le relever
└── Menace sur allié fragile? → Te repositionner

ÉTAPE 2: MOUVEMENT
├── Allié fragile menacé? → Te placer entre lui et l'ennemi
├── Ennemi dangereux libre? → Aller au contact (Sentinel)
└── Bien positionné? → Reste où tu es

ÉTAPE 3: ACTION
├── Allié à 0 HP? → Lay on Hands (1 point) ou Soins
├── Concentration active? → ATTAQUE (pas de sort [C])
├── Round 1, combat long? → BÉNÉDICTION
└── Sinon → ATTAQUE

ÉTAPE 4: APRÈS UNE ATTAQUE RÉUSSIE
├── C'est un CRIT? → SMITE TOUJOURS
├── C'est un boss? → Smite si slots > 1
├── Mort-vivant/Fiélon? → Smite (bonus dégâts)
└── Ennemi normal? → Garde ton slot
```

---

## GESTION DES SLOTS (3 slots niveau 1)

### Règle d'or:
```
Nombre de combats prévus = Nombre de Smites max

4 combats dans le donjon? → Max 1 Smite par combat (garde 1 pour urgence)
1 seul gros combat? → Tu peux Smite 2-3 fois
```

### Budget par scénario:

| Situation | Slots pour Smite | Slots pour Sorts | Reserve |
|-----------|------------------|------------------|---------|
| Donjon (4+ combats) | 1-2 | 0-1 | 1 |
| 2-3 combats | 2 | 1 | 0 |
| Boss fight unique | 3 | 0 | 0 |

### Quand utiliser un slot pour un SORT au lieu de Smite:

| Sort | Utilise si... | Valeur |
|------|---------------|--------|
| Bénédiction | Combat 3+ rounds, 3 alliés | +1d4 × 3 personnes × plusieurs rounds = ÉNORME |
| Bouclier de Foi | Allié fragile focusé | +2 CA pendant 10 min |
| Soins | Quelqu'un sous 50% HP entre combats | Économise Lay on Hands |

---

## POSITIONNEMENT - LE POUVOIR DE SENTINEL

### Le triangle de protection:
```
         ENNEMI
            │
            │ (veut attaquer le mage)
            ▼
   ┌─────[TOI]─────┐
   │    Sentinel   │
   │   "Tu passes  │
   │    pas."      │
   └───────────────┘
            │
            │ (protégé)
            ▼
          MAGE
```

### Comment Sentinel fonctionne:

| Situation | Ce qui se passe |
|-----------|-----------------|
| Tu touches un ennemi | Sa vitesse = 0 ce tour. Il peut plus bouger. |
| Ennemi fait Disengage | Tu frappes QUAND MÊME (attaque d'opportunité) |
| Ennemi à 5ft attaque un allié (pas toi) | RÉACTION: Tu le frappes |

### Positions optimales:

**Couloir étroit (5ft):**
```
[ALLIÉ] ← [TOI] ← [ENNEMI]

Parfait. Personne passe. Si l'ennemi t'attaque, cool.
S'il essaie d'attaquer l'allié derrière, tu frappes (Sentinel).
```

**Espace ouvert - Protéger le mage:**
```
        [ENNEMI 1]    [ENNEMI 2]
              \         /
               \       /
                [TOI]
                  │
                [MAGE]

Reste à 5ft du mage. Quiconque l'attaque = ta réaction.
```

**Flanquer un boss (avec un allié mêlée):**
```
        [ROGUE]
            │
    [TOI]──[BOSS]

Le rogue a Sneak Attack (avantage car tu es à côté).
Tu bloques le boss avec Sentinel.
Win-win.
```

---

## QUAND SMITE - DÉCISION FINALE

```
TU VIENS DE TOUCHER. SMITE OU PAS?

                    ┌──────────────┐
                    │ C'est un     │
                    │ CRITIQUE?    │
                    └──────────────┘
                          │
              ┌───────────┴───────────┐
              ▼                       ▼
             OUI                     NON
              │                       │
              ▼                       ▼
     ╔════════════════╗     ┌─────────────────┐
     ║ SMITE TOUJOURS ║     │ C'est un boss   │
     ║  (dés doublés) ║     │ ou menace       │
     ╚════════════════╝     │ majeure?        │
                            └─────────────────┘
                                    │
                        ┌───────────┴───────────┐
                        ▼                       ▼
                       OUI                     NON
                        │                       │
                        ▼                       ▼
               ┌────────────────┐     ┌─────────────────┐
               │ Slots restants │     │ GARDE TON SLOT  │
               │ > 1?           │     │ (gobelin random │
               └────────────────┘     │  pas worth)     │
                        │             └─────────────────┘
            ┌───────────┴───────────┐
            ▼                       ▼
           OUI                     NON
            │                       │
            ▼                       ▼
   ╔════════════════╗     ┌─────────────────┐
   ║     SMITE      ║     │ C'est ton       │
   ╚════════════════╝     │ dernier slot.   │
                          │ Vraiment le     │
                          │ moment?         │
                          └─────────────────┘
```

### Calcul rapide des dégâts:

| Attaque | Dégâts moyens |
|---------|---------------|
| Normal | 1d8+3 = **7-8** |
| + Smite | 1d8+3 + 2d8 = **16** |
| CRIT + Smite | 2d8+3 + 4d8 = **30** |
| CRIT + Smite vs undead | 2d8+3 + 6d8 = **35** |

---

## SCÉNARIOS DE COMBAT

### Scénario 1: Embuscade de gobelins (3 gobelins)

```
Situation:
- 3 gobelins surgissent
- Le mage est à côté de toi
- Combat probablement court (2-3 rounds)

Round 1:
✗ Bénédiction (combat trop court, pas worth)
✓ Attaque le gobelin le plus proche
✓ Si tu touches → NE SMITE PAS (ce sont juste des gobelins)
✓ Sa vitesse = 0 (Sentinel)

Rounds suivants:
- Continue d'attaquer
- Si un gobelin attaque le mage → RÉACTION (Sentinel)
- Smite seulement si tu veux finir le combat rapidement
```

### Scénario 2: Combat contre un boss (1 ogre + 2 orcs)

```
Situation:
- 1 ogre (la menace principale)
- 2 orcs (sbires)
- Combat va durer 4+ rounds

Round 1:
✓ BÉNÉDICTION sur toi + 2 alliés (+1d4 pour tout le monde)
✓ Mouvement vers l'ogre pour le bloquer

Round 2+:
✓ Attaque l'ogre
✓ Si CRIT → SMITE (dés doublés!)
✓ Si pas crit mais ogre presque mort → Smite pour finir
✓ Sinon garde tes slots

Réactions:
- Si un orc passe pour attaquer le mage → Attaque d'opportunité
- Si tu touches → sa vitesse = 0
```

### Scénario 3: Défendre un PNJ

```
Situation:
- Vous devez protéger un marchand
- Vagues d'ennemis arrivent
- Combat long, ressources limitées

Positionnement:
✓ RESTE À CÔTÉ DU MARCHAND
✓ Utilise Sentinel - quiconque l'attaque se mange ton épée

Ressources:
✓ Lay on Hands sur le marchand s'il prend des dégâts
✓ Bénédiction au Round 1 (combat long)
✓ Garde les Smites pour les menaces sérieuses

Si le marchand tombe à 0 HP:
✓ Lay on Hands IMMÉDIATEMENT (1 point = il se relève)
```

### Scénario 4: Morts-vivants (zombies, squelettes)

```
Situation:
- Groupe de morts-vivants
- Bonus Smite contre eux (+1d8)

Tactiques spéciales:
✓ SMITE PLUS LIBREMENT (bonus dégâts)
✓ Protection contre le Mal → Désavantage sur leurs attaques
✓ Turn the Unholy (Channel Divinity) si submergé

Rappel Smite vs undead:
- Normal: 2d8 radiant
- vs Undead: 3d8 radiant (+50% dégâts!)
```

---

## GESTION DU LAY ON HANDS (15 HP)

### Priorités:

| Situation | Points à dépenser |
|-----------|-------------------|
| Allié à 0 HP | **1 point** (suffit pour le relever!) |
| Poison/Maladie | 5 points (cure automatique) |
| Toi-même entre combats | Ce qu'il faut pour full HP |
| Allié blessé hors combat | Complément après Soins |

### Erreur courante:
```
❌ Dépenser 10 HP de Lay on Hands pour soigner quelqu'un à 0 HP
✓ 1 point suffit pour le relever. Garde le reste!
```

---

## CHANNEL DIVINITY - ARME SACRÉE

### Quand l'utiliser:
```
✓ Avant un boss fight (+2 aux jets d'attaque pendant 1 min)
✓ Contre des ennemis à haute CA
✓ Quand tu dois absolument toucher

✗ Contre des ennemis faciles (gaspillage)
✗ Si le combat est presque fini
```

### Combo avec Smite:
```
Arme Sacrée active:
- +2 au jet d'attaque = plus de chances de toucher
- Plus de chances de toucher = plus d'opportunités de Smite
- Plus de chances de CRIT = Smite ×2
```

---

## RÉACTIONS - NE LES OUBLIE PAS

Tu as **1 réaction par round**. Utilise-la!

| Déclencheur | Réaction |
|-------------|----------|
| Ennemi quitte ta portée | Attaque d'opportunité |
| Ennemi fait Disengage près de toi | Attaque d'opportunité (Sentinel!) |
| Ennemi à 5ft attaque un allié | Attaque (Sentinel!) |

### Rappel:
```
Ta réaction revient au DÉBUT de ton tour.
Si tu ne l'as pas utilisée, tu l'as perdue.
```

---

## ERREURS À ÉVITER

| Erreur | Pourquoi c'est mauvais | Correction |
|--------|------------------------|------------|
| Smite chaque attaque | Plus de slots pour urgence | Smite sur crits/boss |
| Rester en arrière | Tu perds Sentinel, CA gâchée | Sois devant |
| Oublier Bénédiction | +1d4 pour 3 personnes = énorme | Cast round 1 si combat long |
| Soigner 0 HP avec 10 points | Gaspillage | 1 point Lay on Hands suffit |
| Oublier ta réaction | Perte de dégâts gratuits | Check chaque tour |
| Lancer 2 sorts concentration | Le 1er s'arrête | 1 seul sort [C] à la fois |

---

## AIDE-MÉMOIRE RAPIDE

```
╔═══════════════════════════════════════════════════════════╗
║                    TON TOUR - QUICK                       ║
╠═══════════════════════════════════════════════════════════╣
║ 1. Allié à 0 HP? → Lay on Hands (1 pt) ou Soins          ║
║ 2. Round 1, combat long? → Bénédiction                   ║
║ 3. Sinon → ATTAQUE                                        ║
║ 4. Tu touches + CRIT? → SMITE                            ║
║ 5. Position: DEVANT les alliés fragiles                  ║
╠═══════════════════════════════════════════════════════════╣
║ RÉACTION: Ennemi bouge/attaque allié → FRAPPE            ║
╚═══════════════════════════════════════════════════════════╝
```

---

## HORS COMBAT - TON RÔLE

### Tu es la "face" du groupe:
- **Intimidation** +4 → Faire peur aux PNJ
- **Persuasion** +4 → Négocier, convaincre
- Tu as le charisme, utilise-le

### Divine Sense:
- Avant d'entrer quelque part de suspect
- Pour détecter morts-vivants/fiélons cachés
- 3 utilisations par jour, n'hésite pas

### Ton personnage (roleplay):
```
Tu parles peu. Quand tu parles, ça compte.

Phrases typiques:
- "On y va."
- "Reste derrière moi."
- "C'était une erreur." (avant de frapper)
- *silence*

Ta colère froide:
Quand quelqu'un menace les tiens, tu ne cries pas.
Tu deviens calme. Trop calme. Et tu Smite.
```
