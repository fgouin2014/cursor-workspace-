# Project-Specific Configurations

Ce dossier contient les configurations spécifiques pour chaque projet.

---

## 📂 Projets disponibles

### **chatai/**
- Configuration pour ChatAI (assistant IA vocal)
- Architecture V3 (7 managers)
- Drawer KITT professionnel
- Real Assistant System

### **gamelibrary/**
- Configuration pour GameLibrary (émulateurs rétro)
- EmulatorJS integration
- WebServer rules (port 9999)
- ROMs management

### **retroplay/**
- Configuration pour RetroPlay
- RetroArch overlays
- LibRetro cores
- Zapper implementation

---

## 🔧 Utilisation

Pour utiliser une config projet:

```bash
# Copier .cursorrules spécifique
cp cursor-workspace-/projects/chatai/.cursorrules /path/to/chatai/

# Ajouter memories spécifiques
# Consulter projects/chatai/memories.md
# Ajouter dans Cursor → Memories
```

---

**Note:** Les configs projet héritent des règles universelles (`.cursorrules` à la racine) et ajoutent des spécificités.

