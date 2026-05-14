# mAI Desktop 🚀

[![Version](https://img.shields.io/badge/version-0.0.6-%2331c48d)](https://mai-officiel.vercel.app)
[![License](https://img.shields.io/badge/license-AGPL--3.0-blue)](LICENSE)
[![GitHub](https://img.shields.io/badge/github-mDevsLabs-black)](https://github.com/mDevsLabs/mAI-OpenWebUI-Desktop)

**Avec mAI sur bureau, augmentez votre productivité !** ✨

mAI Desktop est l'application native officielle pour transformer votre expérience avec l'IA. Basée sur Open WebUI, elle vous offre une interface fluide, rapide et sécurisée, directement sur votre ordinateur.

![mAI Desktop](./demo.png)

## Pourquoi mAI ?

mAI Desktop n'est pas seulement un navigateur pour votre IA. C'est un compagnon de productivité complet qui élimine le besoin de Docker, de terminaux ou de configurations complexes. **Téléchargez, lancez, discutez.**

### Points Forts 🌟

- ⚡ **Spotlight :** Invoquez une barre de chat flottante instantanément avec `Shift+Ctrl+I` (Windows/Linux) ou `Shift+Cmd+I` (macOS). Capturez des captures d'écran et posez des questions en un clin d'œil.
- 🎙️ **Entrée Vocale :** Dictée système globale. Parlez, mAI transcrit et envoie votre message.
- 🧠 **Inférence Locale :** Exécutez des modèles directement sur votre matériel grâce à l'intégration de `llama.cpp`. Vos données ne quittent jamais votre machine.
- 🔌 **Connexions Multiples :** Jonglez entre vos serveurs locaux et distants en un clic depuis la barre latérale.
- 🔄 **Mises à jour Automatiques :** Profitez toujours des dernières fonctionnalités sans effort.
- 🛡️ **Confidentialité Totale :** Pas de télémétrie, pas de suivi. Votre vie privée est notre priorité.

## Téléchargement 📥

| Plateforme | Installateur |
|----------|-----------|
| **Windows x64** | [**Télécharger .exe**](https://mai-officiel.vercel.app) |
| **macOS (Silicon)** | [**Télécharger .dmg**](https://mai-officiel.vercel.app) |
| **Linux (AppImage)** | [**Télécharger .AppImage**](https://mai-officiel.vercel.app) |

*Pour toutes les autres versions et plateformes, visitez [mai-officiel.vercel.app](https://mai-officiel.vercel.app).*

## Configuration Requise 💻

| Composant | Modèles Locaux | Mode Distant |
|-----------|----------------|--------------|
| **Disque** | 5 Go+ | ~500 Mo |
| **RAM** | 16 Go+ (recommandé) | 4 Go |
| **Système** | Windows 10+, macOS 12+, Linux (glibc 2.28+) | Identique |

> [!NOTE]
> Les modèles locaux sont gourmands en ressources. Si votre machine est limitée, privilégiez la connexion à un serveur distant.

## Installation & Développement 🛠️

Si vous souhaitez contribuer ou compiler l'application vous-même :

```bash
# Installer les dépendances
npm install

# Lancer en mode développement
npm run dev

# Compiler pour votre plateforme
npm run build:win  # Pour Windows
npm run build:mac  # Pour macOS
npm run build:linux # Pour Linux
```

## Communauté & Support 🤝

- 🌐 **Site Officiel :** [mai-officiel.vercel.app](https://mai-officiel.vercel.app)
- 🐛 **Bugs & Suggestions :** [GitHub Issues](https://github.com/mDevsLabs/mAI-OpenWebUI-Desktop/issues)
- 📜 **Changelog :** [CHANGELOG.md](CHANGELOG.md)

---

Développé avec ❤️ par **mDevsLabs**. Sous licence [AGPL-3.0](LICENSE).
