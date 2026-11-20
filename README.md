# Assistant stages SeaTech – page d'accueil

Page d'accueil publique de l'**Assistant stages SeaTech**, un assistant IA qui répond aux questions des étudiants sur les stages à partir des documents officiels de l'école.

**Assistant en ligne :** https://assistant-stages-seatech-2ag6.onrender.com/

## Ce que contient ce dépôt

Un seul fichier, `index.html` : une page statique avec un bouton et un cadre qui renvoient vers l'assistant. Elle est publiée avec **GitHub Pages**.


## Où se trouve le reste

Le code du site (FastAPI, base SQLite, documents de l'école) est dans un **dépôt privé**. Le site tourne sur **Render** (plan gratuit, sans Docker), et c'est ce dépôt privé que Render lit pour le déployer.

## Limites de la version gratuite

- Le site se met en veille après 15 minutes sans visite : le premier chargement peut prendre environ une minute.
- À chaque réveil, la configuration est réinitialisée (compte administrateur, clé Albert, documents publiés). Un serveur avec disque persistant, par exemple une VM Docker à l'université, éviterait ce problème.

## Contexte

Projet réalisé dans le cadre de l'atelier IA, SeaTech.
