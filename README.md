# 🌍 MineColonies & Create Server (Minecraft 1.21.1)

Bienvenue sur le dépôt du serveur MineColonies & Create ! Ce document regroupe toutes les informations, la configuration technique, et la liste des mods nécessaires pour se connecter et jouer sur le serveur.

---

## 🌐 Informations de connexion au serveur
* **Version de Minecraft** : `1.21.1`
* **Modloader** : `NeoForge 21.1.248`
* **Adresse IP du serveur** : `minecolonietest.falixsrv.me`
* **Port** : `26137`
* **Dashboard ColonyWeb** : [Lien d'accès](http://eu21-free.falixserver.net:20017) (pour suivre et gérer votre colonie en ligne)
* **ID du serveur FalixNodes** : `3404549`

---

## 📥 Guide d'installation rapide

Pour vous connecter au serveur, vous devez avoir exactement la même configuration de mods. 

### 1. Dossier de l'instance locale
Votre dossier d'instance locale contenant les configurations et les mods est situé à l'emplacement suivant :
`C:\Users\lcpcc\curseforge\minecraft\Instances\MineColonie`

### 2. Configuration du lanceur Minecraft officiel
Pour lancer le jeu avec les mods :
1. Créez ou modifiez un profil nommé **`MineColonies 1.21.1`** dans votre Minecraft Launcher.
2. Définissez la version de ce profil sur **`neoforge-21.1.248`**.
3. Modifiez le répertoire du jeu (`gameDir`) pour pointer vers le dossier CurseForge ci-dessus :
   `C:\Users\lcpcc\curseforge\minecraft\Instances\MineColonie`
4. Sélectionnez ce profil dans le lanceur et lancez le jeu.

---

## 🛠️ Datapacks installés
* **Datapack** : `Minecolonies Crop Fix.zip`
  * **Emplacement** : Placé dans `saves/New World (2)/datapacks/` (client) et dans `/world/datapacks/` (serveur).
  * **Fonction** : Retire les restrictions de biome pour les cultures de MineColonies (les plantes poussent n'importe où sans contrainte de température ou d'humidité).

---

## 📦 Liste des Mods

Voici les mods requis, divisés selon leur rôle :

### 🖥️ Mods Clients uniquement (À installer sur votre PC uniquement)
Ces mods améliorent l'ergonomie, les performances et l'interface utilisateur locale.
* **Embeddium** (`embeddium-1.0.15+mc1.21.1.jar`) - Optimisation des performances graphiques.
* **Mouse Tweaks** (`MouseTweaks-neoforge-mc1.21-2.26.1.jar`) - Tri et gestion rapide de l'inventaire.
* **Controllable** (`controllable-neoforge-1.21.1-0.25.4.jar`) - Support natif pour jouer à la manette.
* **Configured** (`configured-neoforge-1.21.1-2.6.3.jar`) - Outil de configuration visuelle pour les mods.
* **Framework** (`framework-neoforge-1.21.1-0.13.11.jar`) - Bibliothèque requise par le mod *Controllable*.

### 🤝 Mods Partagés (À installer sur le PC ET sur le Serveur)
Ces mods gèrent le contenu du jeu et doivent correspondre parfaitement des deux côtés.
* **MineColonies** (`minecolonies-1.1.1374-1.21.1-snapshot.jar`) - Mod principal de gestion de colonie.
* **Create** (`create-1.21.1-6.0.10.jar`) - Technologie, engrenages, et automatisation industrielle.
* **CreateColonies** (`createcolonies-2.0.6.jar`) - Intégration esthétique entre Create et MineColonies.
* **Create: Colony Logistics** (`create_colony_logistics-1.3.1.jar`) - Automatisation des transports pour vos colons.
* **Structurize** (`structurize-1.0.832-1.21.1.jar`) - Moteur de placement de schémas de MineColonies.
* **BlockUI** (`blockui-1.0.211-1.21.1-snapshot.jar`) - Moteur d'interface pour MineColonies.
* **Domum Ornamentum** (`domum-ornamentum-1.0.234-snapshot-main.jar`) - Blocs décoratifs supplémentaires.
* **Multi-Piston** (`multipiston-1.2.58-1.21.1.jar`) - Dépendance pour Structurize.
* **Vanilla Food Compatibility** (`minecoloniesvanillafoodcompat-1.0.0.jar`) - Prise en charge des nourritures de base.
* **ColonyWeb** (`colonyweb-1.21.1-neoforge-1.0.1.jar`) - Plugin de liaison web pour le dashboard en ligne.
* **Craftable Crops** (`craftable_crops-1.0.0-neoforge-1.21.1.jar`) - Recettes de culture simplifiées.
* **MineColonies QoL** (`minecolonies_qol-1.0.0___1.1.921-1.21.1.jar`) - Améliorations diverses de qualité de vie.
* **JourneyMap** (`journeymap-neoforge-1.21.1-6.0.5.jar`) - Mini-carte et carte du monde intégrée.
* **Kotlin for Forge** (`kotlinforforge-5.12.0-all.jar`) - Bibliothèque de support de code Kotlin pour NeoForge.
* **Just Enough Items (JEI)** (`jei-1.21.1-neoforge-19.27.0.340.jar`) - Interface de visualisation des recettes (version rétrogradée pour compatibilité manette).
* **MCTier Library** (`mctier_engine-1.0.0.jar`) - Moteur de gestion des niveaux de nourriture (version corrigée localement pour éviter les crashs d'affichage).

---

## 🔧 Correctifs techniques appliqués
* **Crash de l'interface de manette (JEI + Controllable)** : Correction effectuée en utilisant la version JEI `19.27.0.340`.
* **Crash d'infobulle MCTier (Restaurant window ticking screen)** : Correction effectuée sur l'archive client `mctier_engine-1.0.0.jar` en désactivant les mixins graphiques d'infobulle uniquement, évitant ainsi le crash au chargement sans perturber le serveur.