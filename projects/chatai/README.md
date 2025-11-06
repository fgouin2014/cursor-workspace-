# ChatAI - Cursor Configuration

Configuration spécifique pour le projet ChatAI.

---

## 📋 Memories spécifiques ChatAI

Ajouter ces memories dans Cursor → Memories (en plus des memories universelles):

### **1. ChatAI Vision - Real Assistant**
```
ChatAI est un VRAI assistant IA commercial et utilisable au quotidien, pas un jeu de rôle. 
KITT est un style vocal et une interface élégante, PAS un personnage fictif. 
Les réponses doivent être factuelles, vraies et utiles dans la vie quotidienne.

Citation: "je ne veux pas que mon IA se prenne pour KITT. mais qu'il soit vraiment un Assistant."
```

### **2. ChatAI Architecture V3**
```
ChatAI utilise Architecture V3 avec 7 managers spécialisés:
1. KittAnimationManager
2. KittTTSManager  
3. KittVoiceManager
4. KittMessageQueueManager
5. KittMusicManager
6. KittStateManager
7. KittDrawerManager

Règles: Une responsabilité par manager, Lifecycle-aware, Thread-safe.
```

### **3. Drawer KITT Professional**
```
Drawer KITT v4.6.0: 16 boutons 100% fonctionnels, 0 boutons fictifs.
RÈGLE: Pas de Turbo Boost, Mode Poursuite ou autres boutons roleplay.
Tous les boutons doivent ouvrir vraies fonctionnalités.
Tests validés: "WOW A" (utilisateur).
```

### **4. ChatAI Commercial Vision**
```
Vision: Assistant utilisable tous les jours, commercialisable, Google Watch ready.
Citation: "vraiment aider l'humanité dans la vie de tous les jours et être commercialisé. 
Je m'imagine déjà dans le futur avec une google watch et mon assistant."
```

---

## 🔧 Commands spécifiques ChatAI

```bash
# Build
cd ChatAI-Android && ./gradlew assembleDebug

# Install
adb install -r app/build/outputs/apk/debug/app-debug.apk

# Logs
adb logcat | Select-String "ChatAI|KITT|API_TEST"

# Test drawer
# 1. Ouvrir KITT
# 2. Bouton MENU
# 3. Tester 16 boutons
```

---

## 📁 Fichiers importants

- `.cursorrules` → Règles spécifiques ChatAI
- `README.md` → Ce fichier (guide quick start)

---

**Version:** 4.6.0  
**Path:** `C:\androidProject\ChatAI-Android-beta\ChatAI-Android\`

