# 🌍 MineColonies & Create Server - Guide de Connexion & Gameplay

Ce guide explique comment rejoindre le serveur moddé MineColonies & Create (Minecraft 1.21.1 en NeoForge) et présente les fonctionnalités majeures du serveur pour vous aider à bien démarrer votre aventure.

---

## 🌐 Informations du Serveur
* **Version de Minecraft** : `1.21.1`
* **Modloader** : `NeoForge 21.1.248`
* **Adresse IP** : `minecolonietest.falixsrv.me:26137`
* **Dashboard Web (Colonie)** : [ColonyWeb Dashboard](http://eu21-free.falixserver.net:20017) (Interface externe pour suivre vos colons, stocks et bâtiments en temps réel).

---

## 📥 Comment rejoindre le serveur

### Étape 1 : Installer le Modloader
1. Téléchargez et installez **NeoForge version 21.1.248** pour Minecraft 1.21.1.
2. Lancez le jeu une première fois avec ce profil NeoForge pour générer les fichiers requis, puis fermez-le.

### Étape 2 : Installer les Mods
Copiez tous les mods listés ci-dessous dans le dossier `mods` de votre jeu Minecraft (situé par défaut dans `%appdata%\.minecraft\mods`, ou dans le dossier de votre instance personnalisée CurseForge/Prism).

### Étape 3 : Allocation de RAM recommandée
Le modpack contenant des mods lourds (comme Create et MineColonies), il est fortement recommandé d'allouer au moins **4 à 6 Go de RAM** dans les configurations de votre profil Minecraft Launcher.

---

## 📦 Liste des Mods

Tous ces mods doivent être installés dans votre dossier `mods` local :

### ⚙️ Mods requis (Côté Client & Serveur)
* **MineColonies** (`minecolonies-1.1.1374-1.21.1-snapshot.jar`) - Mod de simulation de colonie.
* **Create** (`create-1.21.1-6.0.10.jar`) - Mod d'ingénierie et d'automatisation mécanique.
* **CreateColonies** (`createcolonies-2.0.6.jar`) - Intègre des éléments esthétiques et des blocs de Create dans les styles de construction de MineColonies.
* **Create: Colony Logistics** (`create_colony_logistics-1.3.1.jar`) - Permet d'automatiser les échanges logistiques entre vos machines Create et vos colons.
* **Structurize** (`structurize-1.0.832-1.21.1.jar`) - Moteur de structures pour MineColonies.
* **BlockUI** (`blockui-1.0.211-1.21.1-snapshot.jar`) - API d'interface utilisateur pour MineColonies.
* **Domum Ornamentum** (`domum-ornamentum-1.0.234-snapshot-main.jar`) - Blocs de construction et décorations infinies.
* **Multi-Piston** (`multipiston-1.2.58-1.21.1.jar`) - Requis par Structurize.
* **Vanilla Food Compatibility** (`minecoloniesvanillafoodcompat-1.0.0.jar`) - Intègre les aliments vanilla dans les chaînes de repas de MineColonies.
* **ColonyWeb** (`colonyweb-1.21.1-neoforge-1.0.1.jar`) - Permet de lier le serveur au tableau de bord web.
* **Craftable Crops** (`craftable_crops-1.0.0-neoforge-1.21.1.jar`) - Permet de fabriquer des graines et cultures plus facilement.
* **MineColonies QoL** (`minecolonies_qol-1.0.0___1.1.921-1.21.1.jar`) - Améliorations de confort de jeu pour la colonie.
* **JourneyMap** (`journeymap-neoforge-1.21.1-6.0.5.jar`) - Système de cartographie intégré.
* **Kotlin for Forge** (`kotlinforforge-5.12.0-all.jar`) - Dépendance technique de développement.
* **MCTier Library** (`mctier_engine-1.0.0.jar`) - Moteur interne de gestion des niveaux d'alimentation.
* **Just Enough Items (JEI)** (`jei-1.21.1-neoforge-19.27.0.340.jar`) - Affichage des recettes. *(Note : Cette version spécifique est requise pour éviter tout crash si vous jouez avec une manette)*.

### 🎮 Mods recommandés (Client uniquement)
* **Controllable** (`controllable-neoforge-1.21.1-0.25.4.jar`) - Permet de jouer nativement à la manette.
* **Framework** (`framework-neoforge-1.21.1-0.13.11.jar`) - Requis pour le fonctionnement de *Controllable*.
* **Embeddium** (`embeddium-1.0.15+mc1.21.1.jar`) - Optimisation majeure des performances graphiques.
* **Mouse Tweaks** (`MouseTweaks-neoforge-mc1.21-2.26.1.jar`) - Tri et gestion facilitée de vos coffres.
* **Configured** (`configured-neoforge-1.21.1-2.6.3.jar`) - Permet d'éditer la configuration des mods directement depuis le menu du jeu.

---

## 🎮 Présentation du Gameplay & Fonctionnalités

### 🏛️ MineColonies : Créez votre Cité
MineColonies vous permet de fonder, de peupler et de gérer votre propre ville médiévale ou moderne. Vos colons (mineurs, gardes, fermiers, cuisiniers, bâtisseurs...) vont construire et faire prospérer votre colonie de manière autonome.
* **Premiers pas** : Fabriquez et posez un **Camp d'approvisionnement** (*Supply Camp*) pour obtenir vos premiers outils et le bloc d'**Hôtel de Ville** (*Town Hall*). Posez l'Hôtel de ville pour définir la zone de votre colonie.
* **Bâtisseur** : C'est le colon le plus important. C'est lui qui construit et améliore tous les autres bâtiments (maisons, fermes, scieries, etc.).

### ⚙️ Create : L'Ingénierie Mécanique
Create apporte une dimension d'automatisation industrielle basée sur l'énergie cinétique (rotation, engrenages, courroies). Vous pouvez concevoir des moulins à vent, des usines de traitement de minerais, des scies automatiques, ou même des réseaux de trains à vapeur personnalisés pour transporter vos ressources.

### 🤝 Synergie Create + MineColonies
Grâce au mod **Create: Colony Logistics**, vous pouvez connecter vos usines automatiques fonctionnant sous *Create* directement avec l'entrepôt de votre colonie *MineColonies* ! Vos colons n'auront plus besoin de récolter manuellement toutes les ressources ; vos machines peuvent alimenter directement les stocks de la ville.

---

## 🌾 Datapack de Confort : Biomes & Cultures
Pour simplifier l'alimentation de vos citoyens, le datapack **Minecolonies Crop Fix** est actif sur le serveur.
* **Effet** : Les restrictions de biomes pour la pousse des cultures de MineColonies sont désactivées. Vos fermiers peuvent faire pousser toutes les variétés de plantes (blé, choux, oignons, tomates, etc.) indépendamment du biome dans lequel votre colonie est installée.

---

## 🔧 Dépannage & Compatibilité
* **Crash au chargement des recettes (Manette)** : Si vous utilisez une manette via *Controllable*, assurez-vous de n'installer **que** la version **JEI 19.27.0.340**. Les versions plus récentes de JEI provoquent un crash systématique lors du chargement des recettes.