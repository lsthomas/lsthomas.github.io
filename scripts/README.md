# Synchronisation des supports Sciences Po

Après avoir compilé les PDF dans `cours-SP`, lancer depuis la racine de ce dépôt :

```sh
./scripts/sync-cours-sp-materials
```

La commande recopie uniquement les fichiers qui ont réellement changé. Elle attend par défaut le dépôt source dans `/Users/thomas/Documents/cours/cours-SP`. Si le dépôt est déplacé, indiquer son chemin ponctuellement :

```sh
COURS_SP_DIR=/chemin/vers/cours-SP ./scripts/sync-cours-sp-materials
```

Ensuite, vérifier, committer et pousser les changements normalement.
