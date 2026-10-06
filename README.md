# Marketplace Claude Code d'Ingeno

Une seule liste de tous les plugins Claude Code d'Ingeno hébergés sur GitHub. Ce repo ne contient pas les plugins : il pointe vers les repos où ils vivent.

## Installation

```
/plugin marketplace add ingeno/ingeno-claude-marketplace
/plugin install <plugin>@ingeno
```

## Plugins

| Plugin | Repo source |
|--------|-------------|
| `ingeno-bizdev` | [ingeno/ingeno-bizdev-claude-plugin](https://github.com/ingeno/ingeno-bizdev-claude-plugin) |
| `filon` | [ingeno/ingeno-dev-claude-plugins](https://github.com/ingeno/ingeno-dev-claude-plugins) — `plugins/filon-plugin` |
| `ingeno-delivery` | [ingeno/ingeno-dev-claude-plugins](https://github.com/ingeno/ingeno-dev-claude-plugins) — `plugins/ingeno-delivery-plugin` |
| `ingeno-frontend` | [ingeno/ingeno-frontend-skills](https://github.com/ingeno/ingeno-frontend-skills) |
| `ingeno-frontend-process` | [ingeno/ingeno-frontend-skills](https://github.com/ingeno/ingeno-frontend-skills) — `process` |

## Ajouter un plugin

1. Ajouter une entrée dans `.claude-plugin/marketplace.json` (source `github` ou `git-subdir`).
2. Valider : `claude plugin validate .`

## Historique

L'ancienne marketplace `ingeno-claude-plugins` (dans `ingeno/ingeno-dev-claude-plugins`) reste en place pour l'instant. Elle sera retirée quand tous les hôtes utiliseront celle-ci.
