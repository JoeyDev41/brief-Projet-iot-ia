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
| `05-Wireframes/` | Wireframes des 17 écrans en noir et blanc, même mise en page que les maquettes HD (logo et graphiques remplacés par des zones barrées), PNG 2880 × 1920 : `ecrans/` et `annotees-accessibilite/` (rôles autorisés, accessibilité, comportement) |
| `06-Maquettes-HD/` | Maquettes haute fidélité en couleur des 17 écrans (étape 3), PNG 2880 × 1920 : `ecrans/` (écran seul, à importer dans Figma pour le prototype) et `annotees-accessibilite/` (écran + panneau rôles autorisés, accessibilité, comportement) |

Les maquettes reprennent exactement le contenu des wireframes et appliquent la charte : bleu nuit #001848, bleu de marque #0060C0, accent or #F9BA19, couleurs d'alerte (chaleur, froid, vent fort, pluie), Space Grotesk + Inter.

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
