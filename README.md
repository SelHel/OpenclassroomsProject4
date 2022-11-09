*French version*

# Programme de gestion de tournois d'échecs

## 1. Descriptif

Ce programme est une application hors ligne qui permet aux utilisateurs de gérer des tournois d'échecs.
L'utilisateur peut suivre et mettre à jour les résultats d'un tournoi au fur et à mesure.<br/>
La génération des paires de joueurs pour les matchs est gérée par un algorithme basé sur le système de tournois "suisse".<br/>
Il peut également générer des rapports et sauvegarder ou charger un tournoi à tout moment grâce à une base de données.

## 2. Prérequis
* Python 3+ (lien de téléchargement: <https://www.python.org/downloads>)

## 3. Bibliothèques Python utilisées
* TinyDb

## 4. Installation

Cloner le dépôt en utilisant le terminal sous Mac/Linux ou l'invite de commandes sous Windows :<br>
```
git clone git@github.com:SelHel/Chess_Tournament_Management_Program.git
```

Ensuite, placez vous dans le dossier courant :
```
cd Chess_Tournament_Management_Program-main
```

Puis créez votre environnement virtuel :
```
python -m venv <your-virtual-env-name>
```

Activez votre environnement virtuel :
```
<your-virtual-env-name>\Scripts\activate.bat (sous Windows)
```
ou
	
```
source <your-virtual-env-name>/bin/activate (sous Mac/Linux)
```

Vous devez maintenant installer toutes les librairies nécessaires au bon fonctionnement de ce programme, pour cela exécuter la commande suivante :
```
pip install -r requirements.txt
```
	
## 5. Exécution

Pour éxécuter le programme lancez le script "main.py" avec la commande suivante :
```
python main.py
```

Un menu va apparaître, utilisez les numéros indiqués dans le(s) menu(s) pour naviguer et effectuer les actions voulues.

## 6. Générer un rapport flake8

Vous pouvez générer un rapport flake8 avec la commande suivante :
```
flake8 --format=html --htmldir=flake8-rapport
```
----------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------

*Engish version*

# Chess tournament management program

## 1. Description

This program is an offline application that allows users to manage chess tournaments.
The user can follow and update the results of tournament. <br/>
It can generate reports and save or load tournament at any time with a database.

## 2. Requirements
* Python 3.9 (download link: <https://www.python.org/downloads>)

## 3. Python libraries used

## 4. Installation

Clone repository using Terminal on Mac/Linux or Command Prompt on Windows:<br>
```
git clone git@github.com:SelHel/Chess_Tournament_Management_Program.git
```

Then go to the current directory as follows :
```
cd Scraper-Books_to_Scrape-main
```

Create a virtual environment :
```
python -m venv <your-virtual-env-name>
```

Activate your virtual environment :
```
<your-virtual-env-name>\Scripts\activate.bat (on Windows)
```
or
	
```
source <your-virtual-env-name>/bin/activate (on Mac/Linux)
```

You now need to install all the libraries necessary for this program to work properly, for this run the following command :
```
pip install -r requirements.txt
```

## 5. Execution

Run the program with the following command :

```
python main.py

```
Menu will appear. Use the numbers on the main menu to navigate and make choices.

## 6. Generate flake8 report

Generate a flake8 report with the following command :

```
flake8 --format=html --htmldir=flake8_rapport
```
