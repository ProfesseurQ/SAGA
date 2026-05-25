# SAGA — Suivi et Accompagnement Global des Apprenants

> Outil de suivi pédagogique et personnel de l'enfant, de la maternelle à la fin du primaire, conçu pour l'enseignement en Belgique.

**© 2026 Quentin Elacalle — Tous droits réservés**  
*Première publication : mai 2026*

---

## Vision

SAGA n'est pas un simple gestionnaire de bulletins. C'est un **outil de suivi global de l'enfant**, conçu pour accompagner l'enseignant tout au long de la scolarité d'un élève — de l'accueil en maternelle jusqu'à la fin du primaire.

L'idée centrale : **l'enfant reste au cœur du dispositif**, d'une année à l'autre, d'un enseignant à l'autre. SAGA permet de construire une mémoire scolaire vivante, transmissible et exploitable par chaque nouveau titulaire de classe.

---

## Ce que SAGA couvre

### 👤 Fiche élève complète
Chaque élève dispose d'un dossier personnel structuré :
- **Santé & besoins spécifiques** — informations médicales, allergies, besoins particuliers
- **Réunions de parents** — compte-rendu et suivi des échanges
- **Commentaires libres** — observations de l'enseignant au fil du temps
- **Grille d'observation** — suivi comportemental, social, méthodologique
- **DAccE** (Dossier d'Accompagnement de l'Élève) — ouvert et alimenté tout au long du parcours

### 📋 Suivi de la maternelle au primaire
SAGA accompagne l'enfant dès son entrée à l'école :

| Niveau | Bulletins | Fiche élève | Grille d'observation |
|--------|-----------|-------------|----------------------|
| Accueil / M1 / M2 / M3 | — | ✅ | ✅ |
| P1 → P6 | ✅ | ✅ | ✅ |

La partie bulletin est activée à partir du primaire. Le suivi personnel, lui, commence dès la maternelle.

### 📊 Bulletins (primaire)
- Saisie des notes par période (décembre, avril, juin)
- Matières et compétences configurables
- Auto-évaluation de l'élève intégrée
- Génération de commentaires assistée par IA (Claude / Anthropic)
- Impression optimisée

### 🔄 Transmission & continuité
L'une des forces majeures de SAGA : **la continuité entre les années et entre les enseignants**.
- Export / Import JSON structuré pour transmission en fin d'année
- Gestion multi-années avec archives consultables
- Mode chaînage : les données d'un élève suivent sa progression de classe en classe
- Un nouvel enseignant reprend un dossier complet, pas une page blanche

---

## Principes de conception

- **Autonomie totale** — fonctionne sans serveur, sans connexion, sans abonnement
- **Données privées** — tout reste en local sur la machine de l'enseignant
- **Fichier unique** — une seule application HTML auto-contenue, zéro installation
- **Interface soignée** — pensée pour un usage quotidien sur le terrain
- **Assistance IA** — Claude (Anthropic) intégré pour les commentaires pédagogiques

---

## Stack technique

- HTML5 / CSS3 / JavaScript vanilla — aucune dépendance framework
- Chart.js — visualisations graphiques
- API Anthropic (Claude) — génération de commentaires pédagogiques
- LocalStorage — persistance locale des données
- Fichier unique auto-contenu (~7000 lignes)

---

## Versioning

Le projet suit un versioning sémantique :

| Format | Signification |
|--------|---------------|
| `v1.0.x` | Correction mineure |
| `v1.x.0` | Accumulation de corrections |
| `v2.0.0` | Nouvelles fonctionnalités majeures |

Les sauvegardes JSON sont nommées `bulletins_[classe]_[prénom]_v01.json`, avec incrémentation automatique à chaque export.

---

## Licence

Cette application est une **œuvre originale protégée par le droit d'auteur** (Loi belge du 30 juin 1994 relative au droit d'auteur et aux droits voisins).

**Toute reproduction, modification, distribution ou exploitation commerciale — partielle ou totale — sans autorisation écrite préalable de l'auteur, est strictement interdite.**

La conception, la direction fonctionnelle et pédagogique, ainsi que toutes les décisions d'architecture ont été initiées et pilotées par Quentin Elacalle. Le développement a été réalisé avec l'assistance de Claude (Anthropic).

---

## Auteur

**Quentin Elacalle**  
Enseignant — Belgique  
elacalleq@gmail.com

---

*SAGA est un projet personnel né d'un besoin réel de terrain. Il n'est pas affilié à une institution scolaire ni à Anthropic.*
