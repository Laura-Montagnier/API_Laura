# API pour la création de features de fichiers EXE

## Description

Cette API permet de créer différentes représentations de fichiers exécutables (EXE). Elle génère plusieurs types de features et les enregistre dans le dossier `Résultats`.

## Instructions

### 1. Placer les fichiers exécutables

Placez les fichiers exécutables dans le répertoire `Fichiers_Exécutables`.

### 2. Adapter ember 

Le package Ember a besoin de plusieurs installations pour démarer. Installez-les grâce à requirements.txt :

pip install -r requirements.txt

python3 setup.py install

### 3. Installer LIEF

Installez la version 14 de Lief, c'est-à-dire la plus récente.

pip install lief

### 3. Rendre le script exécutable

Rendez le script `représentations.sh` exécutable en entrant la commande suivante :

chmod +x représentations.sh

### 4. Exécuter le script

Pour ceci, tapez dans l'invite de commande :

./représentations.sh

### Autres étapes :

Il est possible que vous deviez installer pandas, matplotlib ou encore numpy, si ce n'est pas déjà le cas sur votre machine. Suivez les recommandations du terminal et utilisez "pip install".

## Résultats

Les différents types de features sont présents dans le dossier "Résultats".

## Références

Pour le Pack_EMBER : https://github.com/elastic/ember
Pour PE_Feats : Charles-Henry Bertrand van Ouytsel et al.
