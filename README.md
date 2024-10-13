# Wemod Premium Unlocker - Saku

Bienvenue dans le dépôt **Wemod Premium Unlocker** développé par Saku. Ce script est conçu pour patcher et restaurer les fichiers de l'application WeMod. Veuillez suivre les instructions ci-dessous pour configurer et utiliser le script.

## Description

Ce script Python vous permet de :
- **Patcher** l'application WeMod en remplaçant le fichier `app.asar` par une version modifiée.
- **Restaurer** le fichier `app.asar` original à partir d'une sauvegarde.
- Inclut des vérifications d'intégrité pour s'assurer que le script n'a pas été modifié.

## Compatibilité

**Le script fonctionne avec toutes les versions de l'application WeMod, sauf la version 9.10.0.**
| Version         | Statut           |
|-----------------|------------------|
| 4.0.7           | ✅ Supporté      |
| 4.0.8           | ✅ Supporté      |
| 4.0.9           | ✅ Supporté      |
| 4.0.10          | ✅ Supporté      |
| 4.0.11          | ✅ Supporté      |
| 4.0.12          | ✅ Supporté      |
| 4.0.13          | ✅ Supporté      |
| 5.0.0           | ✅ Supporté      |
| 5.0.1           | ✅ Supporté      |
| 5.0.2           | ✅ Supporté      |
| 5.0.3           | ✅ Supporté      |
| 5.0.4           | ✅ Supporté      |
| 5.0.5           | ✅ Supporté      |
| 7.0.0           | ✅ Supporté      |
| 8.2.0           | ✅ Supporté      | 
| 8.3.0           | ✅ Supporté      |
| 9.0.0           | ❌ Non Supporté  |
| 9.10.0          | ❌ Non Supporté  |

## Ancienne version de WeMod
https://www.wingetgui.com/apps/WeMod-WeMod/8-2-0

## Prérequis

Avant d'exécuter le script, assurez-vous d'avoir :
- Python 3 installé sur votre machine.
- Les dépendances Python requises installées. (voir ci-dessous)

## Installation

1. **Clonez le dépôt :**

    ```bash
    git clone https://github.com/sakusql/Wemod-Premium-Unlocker
    cd Wemod-Premium-Unlocker
    ```

2. **Installez les dépendances :**

    Assurez-vous que les modules suivants sont installés :
    - `colorama`
    - `tqdm`
    - `yaspin`
    - `rich`

    Vous pouvez installer ces dépendances en utilisant `pip` :

    ```bash
    pip install colorama tqdm yaspin rich
    ```

3. **Placez vos fichiers :**

    Assurez-vous que le fichier `app.asar` est présent dans le répertoire de travail.

## Utilisation

1. **Exécutez le script :**

    Pour exécuter le script, utilisez le fichier `start.bat` inclus dans le dépôt. Ce fichier batch prépare l'environnement et lance le script Python.

    ```bash
    start start.bat
    ```

2. **Suivez les instructions :**

    Le script affichera un menu avec les options suivantes :
    - **1** : Patch app
    - **2** : Restaurer app
    - **3** : Quitter

    Suivez les instructions affichées pour utiliser les fonctionnalités du script.

## Vérification d'intégrité

Le script comprend une vérification d'intégrité pour s'assurer qu'il n'a pas été modifié. Si la vérification échoue, le script se terminera avec un message d'erreur.

## Remarques

- **Modifiez** les chemins de fichiers et les options selon vos besoins spécifiques.
- **Fonctionne avec toutes les versions de l'application WeMod, sauf la version 9.10.0.** ⚠️

## Contact

Pour toute question ou problème, veuillez contacter Saku sur Discord : [sakuvlr].

---

Merci d'utiliser **Wemod Premium Unlocker - Saku**! 🎉

![Python](https://img.shields.io/badge/Python-3.8.6-blue)
