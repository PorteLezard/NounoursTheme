# 🧸 Nounours Theme

Un thème Discord chaleureux, doux et cosy aux teintes **chocolat noir, caramel et crème**, basé sur l'architecture de [Dark Matter](https://github.com/DiscordStyles/DarkMatter).

![Bannière Nounours](assets/banner.png)

## 🎨 Palette de couleurs

| Rôle | Variable CSS | Couleur |
| :--- | :--- | :--- |
| **Fond principal (Chocolat)** | `--background-solid` | `#1f1410` |
| **Fond sombre (Espresso)** | `--background-solid-dark` | `#170e0b` |
| **Fond très sombre (Cacao)** | `--background-solid-darker` | `#110a08` |
| **Accent principal (Caramel)** | `--accent` | `rgb(235, 155, 108)` (`#eb9b6c`) |
| **Accent secondaire (Cannelle)** | `--accent-alt` | `rgb(155, 76, 44)` (`#9b4c2c`) |
| **Texte / Clair (Crème lait)** | `--white` | `rgb(255, 244, 236)` (`#fff4ec`) |

## 📦 Contenu du pack

* **`Nounours-Standalone.theme.css`** : Version **prête à l'emploi (Plug & Play)**. Tout est inclus dedans (le CSS + le fond d'écran + l'icône accueil nounours). Tu le glisses dans ton dossier `themes` et ça marche direct sans rien héberger !
* **`Nounours.theme.css`** : Fichier thème léger pour hébergement GitHub / GitHub Pages.
* **`src/base.css`** : Feuille de style principale adaptée au thème Nounours.
* **`assets/background.png`** : Fond d'écran 16:9 Nounours.
* **`assets/banner.png`** : Bannière large NounoursDev.
* **`assets/home-icon.png`** : Icône carrée tête de nounours pour le bouton Accueil Discord.
* **`powercord_manifest.json`** : Manifest pour Powercord / Replugged.

## 🚀 Installation rapide (BetterDiscord / Vencord)

### Option 1 : Utilisation immédiate (sans GitHub)
1. Ouvre Discord → **Paramètres** → **Thèmes** → **Ouvrir le dossier des thèmes**.
2. Glisse le fichier **`Nounours-Standalone.theme.css`** dans le dossier.
3. Active **Nounours (Standalone)** dans la liste des thèmes !

### Option 2 : Héberger ton propre pack sur GitHub
1. Crée un dépôt GitHub nommé `NounoursTheme`.
2. Upload les fichiers (`Nounours.theme.css`, `src/`, `assets/`, `powercord_manifest.json`, `README.md`, `LICENSE`).
3. Active **GitHub Pages** dans *Settings → Pages* (branche `main`, dossier `/root`).
4. Dans `Nounours.theme.css`, remplace `TON_PSEUDO_GITHUB` par ton vrai pseudo GitHub.
5. Glisse `Nounours.theme.css` dans ton dossier `themes` Discord.

## Crédits
* Design & Univers : **NounoursDev**
* Base technique : [Dark Matter](https://github.com/DiscordStyles/DarkMatter) par Tropical & Hammock (Licence MIT)
* BlurpleRecolor par DevilBro
