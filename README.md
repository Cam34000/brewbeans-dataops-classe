# Brew Beans — DataOps (Module 7)

Projet pédagogique fictif : apprendre Git, GitHub et Markdown en travaillant sur des ventes de cafés.

## Références communes

- `data/reference/ventes_reference.csv` : **40 transactions** historiques (ne pas modifier).
- `data/reference/magasins.csv` : référentiel des magasins.
- `data/livraisons/livraison_paris_20261026.csv` : **3 nouvelles transactions**, dont `BB-041` est enregistrée à **40,00 EUR** avant correction officielle à **45,00 EUR**.
- `scripts/reference/preparer_ventes.py` : script pandas de départ à copier, puis à compléter.

## Travail par binôme

- Branche : `nompromo_groupeN` (exemple : `daft-ft-21_groupe1`).
- Données produites : `data/groupeN/livraison_corrigee.csv` et `data/groupeN/ventes.csv`.
- Script Python pandas : `scripts/groupeN/preparer_ventes.py`.
- Documentation : `docs/groupeN/README.md`.

Les groupes publient leur branche, puis proposent une **Pull Request** vers `main` ; aucune modification directe de `main`.

## Conditions d'exécution

Depuis la racine du dépôt, avec Python et pandas installés :

```bash
python scripts/groupe1/preparer_ventes.py
```

Cette commande n'est utilisable qu'après la préparation des fichiers du groupe. Remplacer `groupe1` pour les autres binômes et adapter la constante `GROUPE` du script.

Les données sont entièrement fictives. Ne pas publier de données clients réelles ni de secrets.
