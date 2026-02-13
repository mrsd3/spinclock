# Spinclock

Simulez vos horloges, anticipez vos rotations musicales.

Spinclock est un simulateur de rotations musicales conçu pour les programmateurs radio. Il permet de planifier des horloges, visualiser les rotations par catégorie et vérifier la conformité aux quotas francophones ARCOM — le tout dans une interface web unique, sans installation.

## Fonctionnalités

- **Catégories personnalisables** — Définissez vos catégories (P, A, B, C, R, G...) avec nombre de titres, titres FR, nouveaux talents et règles de séparation
- **Horloges programmées** — Créez des séquences de catégories par glisser-déposer, avec versions A/B pour l'alternance
- **Grille d'affectation 7j × 24h** — Assignez vos horloges à chaque créneau jour/heure, avec couleurs distinctes par horloge
- **Quotas français ARCOM** — Calcul automatique sur les heures d'écoute significative (lun-ven 6h-22h30, sam 6h30-22h30, dim 7h-22h30)
- **Régimes de quotas** — Général (40%), Jeunes talents (35%), Découverte (15%) ou personnalisé
- **Sous-quota nouveaux talents** — Jauge dédiée avec seuils par régime
- **Alertes** — Détection de sur-rotation, séparations insuffisantes, quotas impossibles
- **Visualisations** — Répartition horaire, vue hebdomadaire filtrable, heatmap de densité, distribution par catégorie
- **Presets** — 3 configurations prêtes à l'emploi (Radio A type CHR, Radio B locale, Radio C éclectique)
- **Import/Export** — Sauvegarde et partage de presets au format JSON, export CSV des résultats

## Utilisation

Ouvrez `index.html` dans un navigateur. Aucun serveur requis, tout fonctionne côté client. Les données sont sauvegardées dans le localStorage du navigateur.

### Démarrage rapide

1. Cliquez sur un **Preset** (Radio A, B ou C) pour charger une configuration exemple
2. Allez dans l'onglet **Horloges** pour voir les séquences et la grille d'affectation
3. Consultez l'onglet **Quotas français** pour vérifier la conformité ARCOM
4. Ajustez les catégories, horloges et affectations selon vos besoins

### Créer sa propre configuration

1. **Configuration** — Ajoutez vos catégories avec le nombre de titres, titres FR et nouveaux talents
2. **Horloges** — Créez vos horloges et glissez-déposez les catégories pour composer les séquences
3. **Grille** — Affectez chaque horloge aux créneaux souhaités (affectation rapide par jour ou case par case)
4. **Analyse** — Les résultats, alertes et quotas se mettent à jour automatiquement

## Stack technique

- HTML / CSS / JavaScript vanilla
- [Chart.js](https://www.chartjs.org/) pour les graphiques
- [Inter](https://rsms.me/inter/) (Google Fonts)
- Aucune dépendance serveur, aucun build

## Auteur

[MartialDem](https://martialdem.fr)

## Licence

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Vous êtes libre de partager et adapter ce projet, sous les conditions suivantes :
- **Attribution** — Vous devez créditer MartialDem
- **Pas d'utilisation commerciale** — Utilisation non commerciale uniquement
- **Partage dans les mêmes conditions** — Les modifications doivent être partagées sous la même licence
