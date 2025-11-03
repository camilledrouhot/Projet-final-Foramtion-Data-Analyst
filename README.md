# Projet Final Formation Data Analyst - Croisement Steam et Twitch

## Objectif
Trouver les types de jeux les plus populaires et estimer leur popularité future
## Outils utilisés
- Power BI
- Powerpoint
## Contenu
- Projet_Fin_Formation_Camille_Drouhot.pbix : Power BI
- Présentation Projet de fin de formation - Camille Drouhot.pptx : Présentation

## Etapes réalisées

### 1. Préparation des données
- Nettoyage des données sous PowerQuery (suppression de colonnes, doublons, mise en format date)
- Split et pivot d'une colonne contenant 3 valeurs différentes pour identifier les types de chaque jeux

### 2. Analyse exploratoire
- identification de 4 KPI : heures de visionnages sur Twitch, nombre d'heures de jeu en moyenne, nombre d'achievements, ratio du nombre d'avis positifs par rapports aux négatifs (via création d'une mesure DAX)
-Identification de 614 jeux présents à la fois dans les fichiers Twitch et Steam

### 3. Visualisation
Création d'un tableau de bord Power BI dynamique d'abord ciblé sur le type de jeu puis sur les jeux en eux-mêmes avec :
- un classement pour chacun des 4 KPI
- un focus sur l'évolution chronologique des temps de diffusions et de visionnages sur Twitch pour un des types de jeu ou un des jeu souhaité

## Résultats clés

Identification des types de jeu les plus populaires :
<img width="1321" height="805" alt="image" src="https://github.com/user-attachments/assets/6a52b1ae-fccf-446e-a5cb-f2f3d42a6869" />

## Recommandations pour le développement d'un jeu à succès
- Miser sur le multijoueur en priorité pour maximiser le temps de jeu et la visibilité sur Twitch
- Préférer la qualité au contenu à outrance pour fideliser les communautés de joueur
