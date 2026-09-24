# Étape 1 -  Dictionnaire de Données  

dico-données.xlsx

# Étape 2 — Identité visuelle & enchaînement des écrans

Station météo connectée & intelligente · Cité du Numérique de Blois

Référence données : `Proposition_Dictionnaire_Donnees_Station_Meteo.xlsx` (dictionnaire final — rôles, seuils, états, règles d'affichage).

## Contenu du dossier

| Dossier | Contenu |
|---|---|
| `01-Logo-Favicon/` | Logo Météo Blois fond clair / fond sombre en **SVG + PNG**, favicon **SVG + ICO** + PNG 16/32/192/512 px |
| `02-Charte-Graphique/` | Charte graphique PDF (2 pages) : logo, palette, typographies |
| `03-Regles-Interface/` | Règles d'interface PDF (4 pages) : contrastes WCAG vérifiés, typographie, composants, états d'alerte et du capteur, accessibilité, règles d'affichage issues du dictionnaire, droits par rôle |
| `04-Parcours-et-Schema-Enchainement/` | Parcours des 4 acteurs (journée réussie du brief) + schéma d'enchaînement des écrans (PDF + SVG/PNG) |
| `05-Wireframes/` | Wireframes basse fidélité des 17 écrans (SVG + PNG), avec rôles autorisés et note d'accessibilité sur chaque écran |
| `_prompts-figma/` | Prompts de travail utilisés pour Figma Make (hors livrable) — le dernier à appliquer est `PROMPT-CORRECTION-FIGMA-5.md` |

Les maquettes haute fidélité (étape 3) sont dans Figma : lien transmis séparément.

## Rôles (liste ROLE du dictionnaire)

| Rôle | Accès |
|---|---|
| Visiteur (sans compte) | Écran du hall, exploration, IA expliquée |
| Médiateur | Tableau de bord en lecture seule, atelier pédagogique (dont chatbot), profil |
| Animateur | Tableau de bord, export CSV, alertes (acquitter / clôturer), profil |
| Administrateur | Tout, dont l'administration (comptes, seuils, destinataires, état du capteur, journaux) |

## Périmètre couvert (17 écrans)

**Zone publique (sans compte)**
1. Écran d'accueil du hall (kiosque) — 2. Exploration de la donnée — 3. IA expliquée

**Accès du personnel**
4. Connexion — 5. Mot de passe oublié — 6. Réinitialisation (lien valable 30 min)

**Zone authentifiée**
7. Tableau de bord temps réel — 8. Tableau de bord historique (export CSV)
9. Liste des alertes — 10. Détail d'une alerte
11. Atelier pédagogique (rejeu, coulisses, vulgarisation de l'IA, chatbot)
12. Comptes — 13. Seuils d'alerte — 14. Destinataires — 15. État du capteur — 16. Journaux techniques
17. Mon profil

## Choix assumés

- Le logo est celui fourni par le commanditaire ; la palette de la charte en est dérivée.
- Le chatbot est réservé au médiateur (dossier d'architecture, partie E) : la zone publique explique l'IA sans conversation libre.
- Les 5 écrans d'administration partagent une même coquille à onglets.
- Wireframes et maquettes en version bureau uniquement (versions mobiles non demandées).


# Étape 3 — Maquette et Wireframes Figma 

https://www.figma.com/design/80DDNJwpAEE9XwPhjicyui/projet-iot?node-id=0-1&t=37oL1y9HOqrpZKWI-1
