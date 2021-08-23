# Ansible-Initialisation-Docker-Swarm

Ce projet comporte des playbooks pour l'installation de docker et l'initialisation de docker-swarm à n noeuds managers et n noeuds workers

## Pre-requis
* Environnement Ansible

## Comment utilisé les fichiers ?

Vous devez cloner le projet : git clone https://github.com/enassar225/ansible-initialisation-cluster-swarm et : 
- Mettre vos variables dans le fichier all.yml qui se trouve dans le dossier group_vars.yml
- Mettre à jour le fichier inventory.yml selon vos instances
- Exécutez : ansible-playbook -i inventory.yml main.yml
