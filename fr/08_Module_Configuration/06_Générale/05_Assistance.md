Onglet Assistance
=================

Cet onglet permet de paramétrer le comportement de la partie assistance de GLPI.

Assistance
----------
![image](docs/image/configAssistance.png)

- **Pas pour les heures (en minutes)** : utilisé par toutes les zones déroulantes de temps

- **Taille limite par défaut des fichiers importés par un collecteur** : à ce paramètre il convient de coupler la valeur maze_uoload_size de votre configuration PHP

- **Rubrique par défaut pour les documents liés aux tickets** : permet d'affiner le classement des documents pour une recherche ultérieure

- **Conserver les tickets à la purge d'un élément de l'inventaire** : le ticket lié sera conservé mais l'élément associé dans celui-ci sera supprimé

- **Autoriser les ouvertures de tickets anonymes (helpdesk, collecteur)** : Les ouvertures de tickets anonymes sont désactivées par défaut. L'activation de l'option est nécessaire lors de l'utilisation d'un collecteur ou du formulaire de saisie de tickets anonymes afin de permettre la création de ticket par des utilisateurs non reconnus par GLPI.

- **Limite des horaires pour le planning** : plage horaire affichée dans les plannings

- **Utiliser du texte riche pour l'assistance** : permet de saisir du texte en HTML

- **Par défaut, un logiciel peut être associé à un ticket** : pré-rempli le champ "Associable à un ticket" dans le formulaire de création d'un ticket

- **Voir les informations personnelles lors de la création d'un ticket (interface simplifiée)** : affiche les nom, téléphones et lieu de la fiche utilisateur. Si besoin le bouton ***Editer*** redirige vers l'onglet *Principal* des préférences de l'utilisateur

- **Autoriser les suivis anonymes (collecteur)** : permet à un utilisateur non présent dans GLPI de répondre à un courriel provenant de GLPI


Matrice de définition de la priorité
------------------------------------
Le cycle de vie du ticket est influencé par des événements qui peuvent déclencher des traitements automatiques : suppression des tickets liés à un élément lors de sa purge, assignation d'une rubrique par défaut aux documents liés aux tickets.

![image](docs/image/configMatrice.png)
La matrice de définition de la priorité permet de définir la priorité des tickets en fonction du niveau d'impact et d'urgence. La disponibilité de ces niveaux dans l'application peut aussi être définie mais le niveau Moyen ne peut être supprimé.

-----
**Sujet parent :** [Configurer les paramètres centraux](index.php?fr/08_Module_Configuration/06_Générale/01_Configures_les_paramètres_centraux.md)