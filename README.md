# Model_Checking

## Introduction

Ce projet contient l'ensemble des sources et de la documentation du projet de Vérification Algorithmique qui consiste à modéliser un système en TLA+ ou en Uppaal, que nous allons vérifier grâce à la méthode du Model Checking. Voici la [documentation](https://docs.google.com/document/d/1kEViOkaY-ICcBHN5RTyYJeyWzJMhG9S7vnfejCYsfSo/edit?usp=sharing).

## Choix du système

Outil utilisé: **Prism**, pour représenter un système temporisé probabiliste puisqu’on souhaite vérifier l’équilibre du jeu proposé avec différentes propriétés à vérifier utilisant des probabilités.

Type de modèle utilisé: **PTAs** (probabilistic timed automata)
On a choisi d’utiliser ce modèle puisqu’il permet de représenter des systèmes probabilistes temporisés en utilisant des horloges ce qui nous permet de modéliser le temps du jeu qui s’écoule et le blocage des différents personnages lors de certains évènements.

Le moteur choisi est **Digital Clocks** puisque celui ci permet de partager la lecture d’une horloge d’un module à un autre.

## Développeurs

Alexis Cesaro - Reynault Sies