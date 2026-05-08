# ⚡ CW Terminal

**Terminal de décodage et d'envoi CW (Morse) en temps réel pour radioamateurs**

> 📻 Version 1.8 — Mai 2026
> Développé par **F4LPS** dans l'esprit *HAM SPIRIT*

---

## ⚠️ Note importante

Ce dépôt distribue un **installateur Windows pré-compilé**. Le code source n'est pas publié à ce stade.

L'application accède à votre microphone (reconnaissance vocale) et communique avec votre radio via les ports COM. Comme pour toute application qui contrôle votre station, ne lancez l'installateur que si vous faites confiance à l'auteur (F4LPS) et à la chaîne de distribution.

> ℹ️ **Taille de l'installateur : ~533 Mo.** Cette taille s'explique par les bibliothèques embarquées (reconnaissance vocale Google, synthèse vocale TTS, traitement audio temps réel, 5 décodeurs CW parallèles, support multi-protocoles radio). Prévoyez une connexion stable pour le téléchargement.

---

## 🎯 Fonctionnalités principales

- 🔊 **Décodage CW temps réel** avec **5 décodeurs parallèles** pour maximiser la précision
- 📤 **Envoi CW** via keyer, interface COM ou DTR/RTS
- 📡 **Contrôle radio complet** : fréquence, mode, PTT, TUNE
- 🔌 **Support multi-protocoles** : Icom CI-V, Yaesu CAT, OmniRig (SDRplay/SDRuno), FLRig, Ham Radio Deluxe
- 🎙️ **Reconnaissance vocale** (Google) pour la saisie des QSO sans lâcher le manipulateur
- 🗣️ **Lecture vocale (TTS)** du texte décodé — phonétique OTAN
- 📝 **Logging des QSO** vers N1MM Logger+, DXLog.net, Win-Test, WinRef, eQSL, ClubLog, Log4OM, WaveLog, Log32
- 🌞 **Panneau de propagation solaire** en temps réel
- 📊 **Waterfall et spectre audio** temps réel avec vitesse de défilement réglable

---

## 💻 Prérequis

- **Windows 10 ou 11** (64 bits)
- Connexion Internet (pour la reconnaissance vocale Google)
- Une radio compatible (Icom, Yaesu, SDRplay, ou supportée via FLRig/HRD)

### Logiciels complémentaires recommandés

| Logiciel | Usage |
|---|---|
| **OmniRig 1.20** | Requis pour SDRplay/SDRuno |
| **com0com** | Ports COM virtuels (gratuit) |
| **FLRig** | Optionnel — contrôle radio universel |
| **Ham Radio Deluxe** | Optionnel — logging et contrôle radio |
| **Virtual Audio Cable** | Recommandé pour SDRuno |

---

## 📦 Installation

1. Rendez-vous dans la section [**Releases**](../../releases) du dépôt
2. Téléchargez `CW_Terminal_Setup_V1.8.exe` depuis la dernière version
3. Téléchargez aussi le **manuel utilisateur PDF** (joint à la Release)
4. **Exécuter l'installateur en tant qu'administrateur** (clic droit → "Exécuter en tant qu'administrateur")
5. Suivez l'assistant d'installation

L'installation crée automatiquement :
- Un raccourci sur le **Bureau**
- Une entrée dans le **menu Démarrer**
- Une entrée dans **Ajout/Suppression de programmes**

---

## 🚀 Démarrage rapide

1. Lancer **CW Terminal** depuis le raccourci Bureau
2. Cliquer sur **⚙ Réglages** pour saisir indicatif, prénom, QTH, locator, puissance
3. Choisir l'onglet de connexion correspondant à votre radio (Icom CI-V, Yaesu CAT, OmniRig, FLRig, HRD)
4. Cliquer sur **Connecter** — la fréquence s'affiche en vert
5. Régler le slider **Vitesse WF** entre 15 et 25 ms selon la vitesse CW
6. Le décodage CW commence automatiquement

> 📚 **Le manuel utilisateur complet (13 chapitres)** est disponible en PDF dans la dernière Release.

---

## 📜 Historique des versions

### Version 1.8 — Mai 2026

- ⚡ **Latence réduite** de ~5 secondes à moins de 100 ms (buffer audio optimisé)
- 🎨 **Interface réorganisée** : bouton Réglages centralisé, AUTO/MAN, AIDE, Imprimer ABR
- 📊 **Waterfall optimisé** : 18 ms/ligne, traits déplaçables à la souris, centre fixe
- 📡 **SDRuno via OmniRig** fonctionnel (Rig 1, TS-2000, com0com)
- ⏱ **TIME_OFF** ajouté dans tous les formats de log
- 📚 **Manuel V1.8** complet en français avec guide SDRuno/OmniRig
- 🎨 **Nouvelle icône** style cyberpunk ham radio

> 📋 Notes de mise à jour détaillées dans la [Release V1.8](../../releases/latest).

---

## 🤝 Crédits et remerciements

**Auteur :** F4LPS — `developpement@lesf4.fr`

**Remerciements :**
- **F4ELA** — support SDRuno
- **F4LQJ** — support Yaesu
- **F4LCL** — support Ham Radio Deluxe
- **F4MAJ** — hébergement et distribution

---

## 📜 Licence

Logiciel **gratuit** développé dans l'esprit **HAM SPIRIT** :

- ✅ Utilisation libre
- ✅ Distribution autorisée
- ✅ Modification autorisée *(merci de créditer l'auteur)*

---

## 🐛 Signaler un bug ou suggérer une amélioration

Deux options :

- Ouvrir une [**Issue** sur ce dépôt GitHub](../../issues)
- Envoyer un mail à `developpement@lesf4.fr` en précisant :
  - Description du problème
  - Capture d'écran si possible
  - Configuration radio utilisée (modèle, protocole de connexion)
  - Message d'erreur (si affiché)

---

## 🔗 Maintenance du dépôt

Ce dépôt est maintenu par **[F4MAJ](https://f4maj.fr)** au nom de la communauté **Discord Les F4**, afin de centraliser les développements logiciels de la communauté.

Site associé : [f4maj.fr](https://f4maj.fr)
Discord : [discord.gg/u5Nqpu7ECM](https://discord.gg/u5Nqpu7ECM)

---

📻 *Bons décodages et bons CW QSO !*

**73 de F4LPS**
