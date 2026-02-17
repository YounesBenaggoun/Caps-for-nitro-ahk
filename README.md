# ⌨️ Raccourcis clavier personnalisés – AutoHotkey (Windows)

Ce projet contient un script **AutoHotkey (AHK)** permettant de personnaliser des raccourcis clavier sous Windows afin d’automatiser des actions courantes et améliorer la productivité.

---

## 📌 Prérequis

- Windows 10 / 11  
- :contentReference[oaicite:0]{index=0} installé  
  👉 https://www.autohotkey.com/

---

## 🚀 Installation

1. Installer AutoHotkey depuis le site officiel
2. Télécharger ou cloner ce dépôt
3. Double-cliquer sur le fichier `.ahk` pour lancer le script
4. Une icône **H verte** apparaît dans la barre des tâches → le script est actif

---

## ⌨️ Raccourcis disponibles

| Raccourci | Action |
|----------|--------|
| `Ctrl + Alt + N` | Ouvre le Bloc-notes |
| `Ctrl + Alt + C` | Copie le texte sélectionné |
| `Win + T` | Insère un texte prédéfini |
| `Alt + Q` | Ferme la fenêtre active |

> ⚠️ Les raccourcis peuvent être modifiés directement dans le fichier `.ahk`.

---

## 🛠️ Modifier les raccourcis

Ouvre le fichier `.ahk` avec un éditeur de texte.

Exemple :
```ahk
^!n::Run notepad.exe
