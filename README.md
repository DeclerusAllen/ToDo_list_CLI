# ToDo_list_CLI
Une application en ligne de commande pour gérer vos tâches avec authentification utilisateur.
Écrit en Python avec typer et rich pour une interface simple et agréable.

Fonctionnalités principales

Gestion des utilisateurs

Créer un compte (register)

Se connecter (login) et se déconnecter (logout)

Vérification stricte des entrées

Gestion des tâches

Ajouter des tâches avec titre, description multi-lignes et date/heure

Lister toutes les tâches de l’utilisateur connecté

Modifier une tâche existante

Supprimer une tâche avec confirmation

Marquer une tâche comme terminée

Rechercher des tâches par ID, titre ou date

Contrôle strict des entrées et confirmation avant toute modification/suppression

Conception CLI conviviale

Utilisation de typer pour les commandes

Affichage agréable avec rich.Table

IDs affichés à partir de 1 pour plus de lisibilité

Installation

Cloner le repository :

git clone https://github.com/votre-utilisateur/todolist-cli.git
cd todolist-cli


Créer un environnement virtuel :

python -m venv venv


Activer l'environnement :

Windows :

venv\Scripts\activate


macOS / Linux :

source venv/bin/activate


Installer les dépendances :

pip install typer rich

Commandes principales
Authentification

Créer un compte :

python todo.py auth register


Se connecter :

python todo.py auth login


Se déconnecter :

python todo.py auth logout

Gestion des tâches (après connexion)

Ajouter une tâche :

python todo.py tasks add


Lister toutes les tâches :

python todo.py tasks list


Modifier une tâche :

python todo.py tasks edit


Supprimer une tâche :

python todo.py tasks delete


Marquer une tâche comme terminée :

python todo.py tasks done


Rechercher des tâches :

python todo.py tasks search

# Créer un compte
python todo.py auth register
# Connexion
python todo.py auth login
# Ajouter une tâche
python todo.py tasks add
# Lister les tâches
python todo.py tasks list
# Modifier une tâche
python todo.py tasks edit
# Supprimer une tâche
python todo.py tasks delete
# Marquer comme faite
python todo.py tasks done
# Rechercher
python todo.py tasks search

