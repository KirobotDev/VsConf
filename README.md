# Ma configuration VS Code

Salut 👋

Ici je mets ma configuration personnelle de **VS Code** avec mes extensions et mes réglages.

Je l'ai faite principalement pour avoir un VS Code assez **minimaliste**, avec moins de trucs qui prennent de la place et une interface qui me plaît.

## 📁 Contenu

* `settings.json` → mes paramètres VS Code
* `extensions.json` → la liste de mes extensions

## 🎨 Ce que j'utilise

Quelques trucs importants dans ma config :

* Thème **Aura Dracula Spirit**
* Police **JetBrainsMono Nerd Font Propo**
* Material Icon Theme
* Sidebar à droite
* Activity Bar cachée
* Status Bar cachée
* Minimap désactivée
* Breadcrumbs désactivés
* Numéros de lignes relatifs
* Ligatures activées
* Quelques modifications de l'interface avec **APC**
* Extensions pour Python, Git, HTML/CSS, Astro, PHP, Django, etc.

## 🧩 Extensions

J'ai principalement des extensions pour :

* 🐍 Python
* 🌐 HTML / CSS / JavaScript
* 🚀 Astro
* 🐘 PHP / Django
* 🐙 Git / GitHub
* 🐳 Docker
* 🎮 Roblox / Verse
* 📝 Documentation
* 🎨 Personnalisation de VS Code

La liste complète est dans [`extensions.json`](./extensions.json).

## ⚙️ Installation

### 1. Installer VS Code

Télécharge et installe **Visual Studio Code** si ce n'est pas déjà fait.

### 2. Installer les extensions

Ouvre un terminal dans le dossier du projet puis lance :

```powershell
Get-Content extensions.json | ConvertFrom-Json | ForEach-Object { code --install-extension $_ }
```

Ça va installer automatiquement toutes les extensions présentes dans `extensions.json`.

### 3. Installer la police

Ma configuration utilise :

```text
JetBrainsMono Nerd Font Propo
```

Il faut donc installer cette police sur Windows avant de l'utiliser.

### 4. Installer les réglages

Copie le contenu de `settings.json` dans le fichier :

```text
%APPDATA%\Code\User\settings.json
```

Tu peux ouvrir directement le dossier avec :

```powershell
explorer "$env:APPDATA\Code\User"
```

Puis remplace ton `settings.json` par celui du dépôt.

### 5. Redémarrer VS Code

Une fois les extensions et les réglages installés, redémarre VS Code.

Et normalement c'est bon.

## ⚠️ Petit détail

Cette configuration est **personnelle**. Certaines extensions ou certains réglages peuvent ne pas être utiles pour tout le monde.

Le but est surtout de garder ici ma config pour pouvoir la retrouver ou la réinstaller facilement sur une autre machine.

---

**Made by KirobotDev**
