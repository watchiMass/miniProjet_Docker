# miniProjet_Docker
Conténeurisation via docker d'une application simple ayant un front-end php et un back-end en rest API

Ce mini projet a pour but de pratiquer la conténeurisation d'application avec docker, l'objectif était de transformer l'architecture monolithique d'une application en une architectrure en microservices découplée (un container par service), scalable, évolutive et facilement déployable.

ETAPES CLES DE LA REALISATION DU PROJET :
- Conteneurisation de l'API : Construction et test l'image de l'API
- <img width="988" height="79" alt="Capture d’écran du 2025-12-11 22-17-56" src="https://github.com/user-attachments/assets/d02b3cd8-9745-41bc-b9aa-3eec2b61bfb4" />

- Orchestration (IaC) : Création d'un fichier docker-compose.yml pour déployer l'API et l'application Web PHP
  <img width="1010" height="125" alt="Capture d’écran du 2025-12-11 22-19-24" src="https://github.com/user-attachments/assets/468aefb6-44b0-43fc-946f-15a829df1f9a" />
- Gestion des Images : Déployer un registre Docker privé et une interface Web associée 
  <img width="1093" height="212" alt="Capture d’écran du 2025-12-11 22-21-23" src="https://github.com/user-attachments/assets/a058f4c4-b417-4225-865d-70cfdc43ffda" />
  
    loging au registre : 
  <img width="951" height="394" alt="Capture d’écran du 2025-12-11 22-24-21" src="https://github.com/user-attachments/assets/ded74fd4-95cd-4248-a0a9-3fcfe6b85aea" />

<img width="1297" height="474" alt="Capture d’écran du 2025-12-11 22-26-05" src="https://github.com/user-attachments/assets/38dd6a2c-1776-44dc-9423-11f8657d399d" />
