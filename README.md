# TP HTML / CSS — CityPulse (UI statique, sans JavaScript)

## Contexte
Vous réalisez l’intégration front d’un mini-site d’actualité locale nommé **CityPulse**.  
Le projet est **100% statique** : aucune logique applicative, aucun comportement dynamique, aucun JavaScript.

La réalisation doit suivre **fidèlement la maquette fournie** (versions **mobile** et **bureau**) et produire un rendu propre, cohérent et accessible.

**Durée indicative : 3 jours**.

---

## Objectif
Produire un mini-site composé de 5 pages avec une identité visuelle cohérente, une mise en page responsive et une qualité d’intégration proche d’un livrable “production”.

---

## Maquette
- **Maquette PDF fournie** dans le dossier Maquette
- Toutes les décisions graphiques (espaces, hiérarchie, composants visuels, variations mobile/bureau) doivent s’aligner sur cette maquette.

---

## Livrables attendus
Vous devez rendre :
- **5 pages** :
  - Accueil
  - Liste des articles
  - Détail d’un article
  - Agenda
  - Contact / Proposer une info
- **1 feuille de styles principale** (commune à toutes les pages)
- **1 fichier `README`** (ce fichier) complété avec :
  - État d’avancement
  - Choix réalisés (organisation, responsive, accessibilité, thème)
  - Points connus/non terminés (si nécessaire)

---

## Contraintes obligatoires

### Technologies
- **Interdiction totale de JavaScript**
- **Aucun framework**
- **Aucun style inline**
- Pas de dépendances externes

### Qualité d’intégration
- Approche **mobile-first**
- Responsive : rendu stable en mobile, tablette et bureau
- Cohérence stricte avec la maquette : alignements, espacements, hiérarchie visuelle

### Accessibilité (minimum requis)
- Navigation **au clavier** utilisable partout
- Focus visible
- Textes lisibles (tailles, contrastes, espacements)
- Formulaire compréhensible et utilisable (libellés, aides, champs requis)

### Contenus
- **Interdiction du “Lorem ipsum”**
- Textes réalistes et cohérents (titres, extraits, dates, lieux, catégories)

---

## Pages à produire (contenu minimum)

### 1) Accueil
- 1 “Une” mise en avant
- 3 articles “À la une”
- 1 bloc “Dernières infos” (liste compacte)
- 1 zone latérale d’informations (contenu statique : brèves, info pratique, chiffre du jour, etc.)

### 2) Liste des articles
- Une zone de filtres (présentation uniquement : non fonctionnelle)
- Une grille d’articles (au moins **9** entrées)
- Une pagination (présentation uniquement : non fonctionnelle)

Chaque article de la liste doit afficher au minimum :
- Titre
- Extrait
- Catégorie (ou thématique)
- Date de publication
- Visuel (ou espace prévu par la maquette)

### 3) Détail d’un article
- En-tête de l’article (titre, informations éditoriales)
- Visuel principal
- Article long structuré (au moins **600–900 mots**)
- Un encadré “À lire aussi” (3 liens)
- Une zone “Partager” (présentation uniquement)

### 4) Agenda
- Liste d’événements (au moins **8**)
- Chaque événement doit afficher :
  - Nom
  - Date + horaire
  - Lieu
  - Type/catégorie (ex. concert, marché, expo…)

### 5) Contact / Proposer une info
- Formulaire complet avec :
  - Identité (nom/prénom ou nom)
  - Email
  - Sujet / type d’information
  - Message
  - Consentement (case à cocher)
- Bloc “Coordonnées de la rédaction” (contenu statique)

---

## Thème et préférences utilisateur (obligatoire)
- **Thème sombre automatique** selon les préférences système
- Respect de la préférence “réduction des animations” si des effets sont présents

---

## Organisation du projet
- Une page = un fichier distinct
- Une feuille de styles principale commune
- Ressources regroupées (images, icônes, polices si utilisées)
- Noms de fichiers clairs et cohérents

---

## Critères d’évaluation
| Critère | Attendus | Pondération |
|---|---|---:|
| Fidélité à la maquette | Hiérarchie, espaces, alignements, cohérence globale | 30% |
| Responsive mobile-first | Adaptation fluide, aucune casse, lisibilité | 25% |
| Qualité HTML | Structure claire, titres cohérents, contenu bien organisé | 20% |
| Qualité CSS | Cohérence, maintenabilité, réutilisation, propreté | 20% |
| Accessibilité | Clavier, focus visible, formulaires utilisables | 5% |

---

## Checklist avant rendu
- [ ] Les 5 pages sont accessibles via la navigation
- [ ] Aucun JavaScript, aucun framework, aucun style inline
- [ ] Aucun “Lorem ipsum” (contenu réaliste partout)
- [ ] Mobile et bureau conformes à la maquette
- [ ] Navigation clavier utilisable sur toutes les pages
- [ ] Focus visible partout
- [ ] Thème sombre fonctionnel
- [ ] Réduction des animations respectée (si applicable)
- [ ] Projet organisé + ressources rangées
- [ ] README complété (état d’avancement + choix)

---

## Modalités de rendu
- Remettre le dossier du projet complet (pages, styles, ressources)
- Vérifier l’ouverture locale des pages (sans serveur requis)
- Vérifier le rendu sur au moins 2 tailles d’écran (mobile + bureau)

---

## Notes
Indiquez ici :
- ce qui a été le plus difficile,
- ce que vous amélioreriez avec plus de temps,
- ce que vous avez priorisé.
