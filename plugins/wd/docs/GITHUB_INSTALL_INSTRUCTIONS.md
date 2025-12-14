# 🚀 Installation du Plugin GoDev depuis GitHub

Le plugin a été pushé sur GitHub avec succès! Il est maintenant installable depuis n'importe où.

## 📦 Installation

### Étape 1: Installer depuis GitHub
```bash
/plugin marketplace add Para-FR/godev-framework
```

### Étape 2: Redémarrer Claude Code
**Important:** Fermer complètement Claude Code et le relancer.

### Étape 3: Vérifier l'installation
```bash
/plugin list --installed
```

**Résultat attendu:**
```
Installed Plugins:
- gd v1.0.0 (from gd-marketplace)
  Commands: 17
  Agents: 5
```

## ✅ Test des Commandes

### Commandes Principales
```bash
# Analyse de code
/gd:analyze

# Implémentation de features
/gd:implement

# Build de projet
/gd:build

# Amélioration de code
/gd:improve

# Tests
/gd:test
```

### Toutes les Commandes (17)
- `/gd:analyze` - Multi-dimensional code analysis
- `/gd:implement` - Feature implementation
- `/gd:build` - Project builder with framework detection
- `/gd:improve` - Code quality improvements
- `/gd:test` - Testing and QA
- `/gd:document` - Documentation generation
- `/gd:troubleshoot` - Issue diagnosis
- `/gd:cleanup` - Code cleanup
- `/gd:design` - System design
- `/gd:estimate` - Development estimation
- `/gd:explain` - Code explanation
- `/gd:git` - Git operations
- `/gd:index` - Project indexing
- `/gd:load` - Context loading
- `/gd:spawn` - Task orchestration
- `/gd:task` - Task management
- `/gd:workflow` - Workflow generation

### Agents (5)
- `frontend` - UI/UX development
- `backend` - Server-side development
- `security` - Security analysis
- `test` - QA and testing
- `docs` - Documentation

## 🎯 Format Propre

Les commandes apparaissent maintenant comme:
```
/gd:analyze    Multi-dimensional code and system analysis
               (plugin:gd@gd-marketplace)
```

Au lieu de:
```
/godev-framework:gd-analyze    ...
                              (plugin:godev-framework@godev-framework-marketplace)
```

## 🐛 Troubleshooting

### Erreur SSH
Si vous voyez "SSH authentication failed":
```bash
# Configurer Git pour utiliser HTTPS
git config --global url."https://github.com/".insteadOf git@github.com:

# Réessayer l'installation
/plugin marketplace add Para-FR/godev-framework
```

### Alternative: URL HTTPS Directe
```bash
/plugin marketplace add https://github.com/Para-FR/godev-framework.git
```

### Plugin non visible après installation
1. Vérifier que Claude Code a été redémarré
2. Vérifier avec `/plugin marketplace list`
3. Si nécessaire, retirer et réinstaller:
   ```bash
   /plugin marketplace remove gd-marketplace
   /plugin marketplace add Para-FR/godev-framework
   ```

## 🎉 Succès!

Si tout fonctionne, vous devriez voir:
- ✅ 17 commandes `/gd:*` disponibles
- ✅ 5 agents activables
- ✅ Format propre dans l'autocomplétion
- ✅ Plugin affiché comme `gd@gd-marketplace`

---

**Repository GitHub:** https://github.com/Para-FR/godev-framework
**Commit:** 6361829 (Rename plugin to 'gd' with clean command names)
