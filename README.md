# enix

Marketplace public Claude Code — plugins et skills open source par [enixCode](https://github.com/enixCode).

## Installation

```bash
/plugin marketplace add enixCode/plugins
```

Puis installer un plugin :

```bash
/plugin install light-process@enix
```

## Plugins

| Nom | Description |
|---|---|
| [light-process](https://github.com/enixCode/light-process) | Skills pour light-process : moteur DAG orchestrant du code dans des conteneurs Docker via light-run. |

## Mises à jour

Les plugins suivent la branche par défaut de leurs repos sources (pas de version épinglée). Pour récupérer les derniers commits :

```bash
/plugin marketplace update enix
/plugin update
```

Claude Code tente aussi un auto-update au démarrage.

## Licence

MIT
