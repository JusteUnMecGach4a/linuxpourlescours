# 🐧 Le Terminal Linux : Guide des Commandes Essentielles

**"Le Terminal Linux"** est une page web interactive conçue pour servir de **référence rapide** et de guide d'apprentissage des commandes Linux les plus courantes et essentielles, spécifiquement pour les distributions basées sur Debian (LMDE, Ubuntu, Mint, etc.).

Ce guide est idéal pour les administrateurs système juniors, les étudiants en réseaux/cybersécurité, ou toute personne effectuant ses premiers pas dans l'environnement du terminal.

## 🌟 Fonctionnalités Clés

* **Design sombre et épuré** inspiré des terminaux, réalisé avec **Tailwind CSS**.
* **Navigation rapide et fixe** pour basculer instantanément entre les catégories de commandes (APT, Fichiers, Réseau, Sécurité, etc.).
* **Cartes interactives** : Chaque commande est présentée dans une carte cliquable qui révèle des **détails supplémentaires**, des **options importantes** (`-r`, `-h`, `-i`), et des **exemples d'utilisation concrets** (`sudo apt clean`, `find -iname`).
* **Structure thématique** : Le guide est organisé en 8 sections logiques pour une recherche efficace :
    1.  Mise à jour et Installation (**APT**)
    2.  Gestion des Fichiers et Dossiers
    3.  Recherche et Emplacement
    4.  Texte, Pipes et Redirections
    5.  Utilisateurs, Groupes et Permissions
    6.  Réseau et Connexion à Distance (**SSH/SCP**)
    7.  Sécurité et Pentest (**John the Ripper**)
    8.  Système et Diagnostic (**top/htop, systemctl**)

## 💻 Technologies Utilisées

* **HTML5**
* **Tailwind CSS** : Framework CSS utilisé pour le style et la réactivité du site.
* **JavaScript** : Utilisé uniquement pour la fonction `toggleDetails(element)` qui gère l'affichage/masquage des informations supplémentaires de chaque commande.
* **Font Inter** : Utilisée pour un look moderne et lisible.

## 🚀 Installation et Utilisation

Ce projet ne nécessite aucune construction ni compilation. Il s'agit d'un simple fichier HTML autonome.

1.  **Cloner le dépôt :**
    ```bash
    git clone [URL_DU_DÉPÔT]
    cd Le-Terminal-Linux
    ```
2.  **Ouvrir le fichier :**
    Ouvrez le fichier `index.html` directement dans votre navigateur web préféré.
    ```bash
    xdg-open index.html  # Sous Linux
    ```

## 💡 Exemple d'Interaction

Les commandes clés et leurs explications sont visibles immédiatement. En cliquant sur la carte, des astuces d'administrateur système apparaissent, comme pour `apt upgrade` :

> *Détails supplémentaires :*
> **Mise à jour complète :**
> `sudo apt dist-upgrade`
> *Effectue une mise à jour de la distribution; peut **installer/supprimer** des paquets pour résoudre des dépendances...*

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! Si vous avez des commandes importantes à ajouter ou des améliorations à proposer :

1.  *Fork* ce dépôt.
2.  Créez une nouvelle branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-commande`).
3.  Commitez vos changements (`git commit -m 'Ajout de la commande man'`).
4.  Poussez vers la branche (`git push origin feature/nouvelle-commande`).
5.  Ouvrez une *Pull Request*.

---

## 📄 Licence

Ce projet est sous licence [MIT/Apache/GPL - À spécifier].
