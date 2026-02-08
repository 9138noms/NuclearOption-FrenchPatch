# Nuclear Option – Patch français (Localization Patch)

Mod de traduction française pour Nuclear Option. Fonctionne comme plugin BepInEx et traduit l'interface, l'encyclopédie, les astuces et les infobulles — soit **1 427 entrées** au total.

## Prérequis

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Installation

1. Installez **BepInEx 5.x** dans le dossier du jeu.
   ```
   Exemple : C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Lancez le jeu **une fois** puis fermez-le. (Cela créera la structure de dossiers BepInEx)

3. Copiez tous les fichiers de ce dépôt dans :
   ```
   [Dossier du jeu]\BepInEx\plugins\LocalizationPatch\
   ```
   > Si le dossier « LocalizationPatch » n'existe pas, créez-le manuellement.

4. Lancez le jeu — la **traduction française sera appliquée automatiquement**.

## Fichiers inclus

| Fichier | Description |
|---------|-------------|
| `LocalizationPatch.dll` | Plugin du patch |
| `fr.json` | Données de traduction française (1 427 entrées) |

## Raccourcis clavier en jeu

| Touche | Fonction |
|--------|----------|
| `F10` | Afficher/masquer l'overlay de débogage |
| `Ctrl+F10` | Recharger les données de traduction (rechargement à chaud) |

## Remarques

- Les noms de missions et de factions (PALA, BDF) restent en anglais.
- En cas de problème, vous pouvez configurer manuellement la langue dans `BepInEx\config\com.yuulf.localizationpatch.cfg` en définissant `Language = fr`.
