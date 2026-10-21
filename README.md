# 🎮 Docteur Doom Traduction — Traducteur de jeux vidéo et multimédia en temps réel

Traducteur de jeux vidéo et multimédia en temps réel (**Turbo 10ms**) ! Idéal pour GTA et les jeux non traduits (Français/Anglais). Permet également de lire et traduire les vidéos sur YouTube et en streaming directement à partir de Google (`chrome.exe`). 

Lecture OCR instantanée et synthèse vocale haute performance (**Piper TTS** avec son modèle embarqué). Projet 100% gratuit, sécurisé (chiffrement local Windows DPAPI) et open-source à but éducatif. Rejoignez l'aventure et participez !

---

## 🎥 Démos & Communauté

- 🎥 [Voir la démo GTA (1)](https://streamable.com/plshku)
- 🎥 [Voir la démo GTA (2)](https://streamable.com/bn7qg4)
- 🎥 [Voir la démo South Park](https://streamable.com/3kxvtl)
- 🌐 [Rejoindre le serveur Discord officiel](https://discord.gg/PWGJYKp23g)

### 🔐 Certification & Signature de l'Installateur (Version Entreprise / Production)
Pour garantir la sécurité et l'authenticité de l'exécutable officiel `DocteurDoom_Traduction_Setup.exe`, voici l'empreinte cryptographique officielle de référence de la version :
- **Empreinte SHA-256 :** `955F89F9213E1C95C35DCB5E0793E35AEBE714A628A79BF1137E664479BFFF49`[cite: 4]

---

## 📸 Captures d'écran

| Interface Principale | Paramétrage & Dictionnaire |
| :---: | :---: |
| ![Démo 1](1.PNG) | ![Démo 2](2.PNG) |

*(Plus de visuels et l'installeur officiel `DocteurDoom_Traduction_Setup.exe` sont disponibles directement dans les salons de notre serveur Discord).*

---

## ⚙️ Fonctionnalités & Stack Technique

- **Performance Turbo (10ms) :** Capture d'écran et traitement ultra-rapides pour ne pas impacter les performances de vos jeux.
- **OCR Intelligent :** Intégration de Tesseract OCR (`fra`, `eng`, `osd`) pour une reconnaissance de texte instantanée à l'écran.
- **Synthèse Vocale Locale :** Utilisation de **Piper TTS** (`onnxruntime`) avec le modèle vocal `fr_FR-siwis-medium.onnx` pour un rendu vocal fluide et naturel.
- **Sécurité Maximale (DPAPI) :** Les clés de configuration (Google API, Dictionnaire Maître, Prénoms) sont chiffrées localement via le profil Windows. Aucune donnée sensible n'est stockée en clair.
- **Dictionnaires & Méga-Lexiques :** Système unifié de gestion et d'enrichissement continu pour adapter le vocabulaire des jeux (GTA, Red Dead Redemption, etc.) et des prénoms.

---

## 🚀 Installation & Premier Lancement

1. **Récupération de l'application :** 
   - Téléchargez l'installeur officiel `DocteurDoom_Traduction_Setup.exe` directement depuis le salon `#téléchargements` sur notre Discord ou depuis les releases du dépôt.
2. **Assistant d'installation :** 
   - Lancez l'exécutable, laissez-vous guider par l'interface (avec musique rétro et création automatique du raccourci Bureau).
3. **Configuration des Clés (1er lancement) :**
   - Renseignez vos 3 clés obligatoires (Clé API Google Cloud, Clé du Dictionnaire Maître et Clé des Prénoms) dans l'écran de configuration sécurisé. Tout est chiffré localement sur votre machine !

---

## 📚 Gestion & Enrichissement des Dictionnaires

Le projet intègre un **Menu Dictionnaire Unifié** permettant d'alimenter en continu le lexique des jeux et des prénoms :
- **Récupération :** Téléchargez les fichiers `.json` spécifiques aux jeux (GTA, RDR, etc.) depuis le serveur Discord.
- **Fusion & Injection :** Utilisez l'outil intégré pour coller vos listes au format code, garantissant une synchronisation parfaite entre les dictionnaires Jeux et Google.

---

## 🤝 Contribuer

Consultez les schémas et l'architecture technique pour comprendre le fonctionnement du pipeline en temps réel (OCR, Piper TTS, gestion des dictionnaires et sécurité). Toutes les contributions, suggestions ou améliorations sont les bienvenues ! 

Faites une pull request ou venez en discuter sur le Discord !
