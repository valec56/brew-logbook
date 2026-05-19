# ☕🍺 Logbook — Café & Bière

Carnet de recettes personnel. Chaque recette vit dans son propre dossier, chaque tentative dans un fichier versionné (`v1.md`, `v2.md`...).

## Structure

```
logbook/
├── cafe/
│   ├── _templates/       ← copier-coller pour nouvelle recette
│   │   ├── filtre.md
│   │   ├── moka.md
│   │   └── aeropress.md
│   └── recettes/
│       └── nom-du-cafe/  ← un dossier par café/origine
│           ├── v1.md
│           └── v2.md
└── biere/
    ├── _templates/
    │   ├── tout-grain-biab.md
    │   ├── tout-grain-multicuves.md
    │   └── extrait.md
    └── recettes/
        └── nom-de-la-biere/
            ├── v1.md
            └── v2.md
```

## Convention de nommage

- Dossier recette : `origine-torrefacteur` pour le café, `style-nom` pour la bière
- Fichier : `v1.md`, `v2.md`... — le numéro reflète la tentative, pas la version de la recette
- Git conserve le diff complet entre versions

## Templates disponibles

| Template | Usage |
|---|---|
| `cafe/_templates/filtre.md` | V60, Chemex, Kalita, etc. |
| `cafe/_templates/moka.md` | Bialetti Express Induction 6t / Venus 3t + filtres IMS |
| `cafe/_templates/aeropress.md` | Standard & inverted |
| `biere/_templates/tout-grain-biab.md` | Tout grain BIAB |
| `biere/_templates/tout-grain-multicuves.md` | Tout grain 2-3 cuves |
| `biere/_templates/extrait.md` | Brassage à l'extrait |
