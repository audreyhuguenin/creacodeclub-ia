---
marp: true
theme: default
---

# Crea Code Club IA
## Partie 2: Déchiffrer l'IA

---

[//]: # (--------------- Introduction)

# Programme du cours
1. Algorithme de résolution de problème
2. Algorithme de jeux simple
3. Machine Learning

---

# Qu'est-ce qu'un algorithme ?

---

<!-- <video src="" style="width:80%" controls></video> -->

---

[//]: # (--------------- Algorithme de résolution de problème)

<!-- 
_backgroundColor: '#3588d1' 
_color: '#f8f8ff' 
-->

# Algorithme de résolution de problème

---

<!-- _class: riddle-one -->

<style>
    section.riddle-one ul{        
        display:flex;
        width:100%;
        list-style:none;
        align-items:center;
        flex-wrap: wrap;
        justify-content: center;      
        font-size:12rem;
        padding:0;
    }
</style>

- 🌽
- 🐔
- 🦊
- 👨‍🌾
- ⛵

![bg w:100%](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/The_River_Cam_from_the_Green_Dragon_Bridge.jpg/1280px-The_River_Cam_from_the_Green_Dragon_Bridge.jpg)

---

<!-- _class: riddle-two -->

<style>
    section.riddle-two ul{        
        font-size:5rem;
    }
</style>

# Attention !

- 🐔 🍽 🌽
- 🦊 🍽 🐔
- ⛵ -> 2x👥

---

# Etapes de résolution

1. Etablir tout les mouvements possible
2. Enlever tout les mouvement ne respectant pas les conditions
3. Relier les mouvements entre eux
4. Trouver le chemin le plus court

---

[//]: # (--------------- Algorithme de MinMax)

<!-- 
_backgroundColor: '#3588d1' 
_color: '#f8f8ff' 
-->

# Algorithme MinMax
## Ou Comment résoudre un jeux simple

---

# Fonctionnement

![Exemple avec Tic-Tac-Toe](https://course.elementsofai.com/static/2_3_game-tree-2.0259fe81.svg)

1. Trouver toutes les combinaisons possible dans le jeux actuel
2. A partir de toutes ces combinaisons, trouver la combinaison permettant de gagner le plus vite
3. Renvoyer le prochain mouvement

---

# Utilisations

![Chess](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/ChessSet.jpg/250px-ChessSet.jpg)
![Tic-Tac-Toe](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Tic_tac_toe.svg/200px-Tic_tac_toe.svg.png)
![Puissance Quatre](https://upload.wikimedia.org/wikipedia/en/thumb/7/79/Connect_4_Board_and_Box.jpg/220px-Connect_4_Board_and_Box.jpg)

---

# Limites

![Go](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/FloorGoban.JPG/300px-FloorGoban.JPG)
![Fortnite](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/FortniteLogo.svg/250px-FortniteLogo.svg.png)

---

# Ne fonctionne donc que quand:
- Il n'y a que 2 joueurs
- Que un mouvement gagnant d'un joueur se traduit par un mouvement perdant pour l'autre joueur
- Toutes les informations du jeu sont connues

---

# Comment faire mieux ?

---

[//]: # (--------------- Machine Learning)

<!-- 
_backgroundColor: '#3588d1' 
_color: '#f8f8ff' 
-->

# Machine Learning (Apprentissage automatique)

---

# Fonctionnement du Machine Learning

Donnée -> Algorithme d'apprentissage -> Prédiction

---

# Système de recommandation de musique

![Daily Mix Spotify](https://community.spotify.com/t5/image/serverpage/image-id/86574iBB73B4D361258EEE/image-size/large?v=1.0&px=999)
![Home Spotify recommandation](https://community.spotify.com/t5/image/serverpage/image-id/97303i91A6D3C5EB772C5C/image-size/large?v=1.0&px=999)


---

# Fonctionnement

- "[C'est quoi l'intelligence artificielle](https://www.youtube-nocookie.com/embed/ourd-ZeOl78)"
- "[IA: pourquoi vous n'avez aucune change de gagner](https://www.youtube-nocookie.com/embed/tI2zP4Zthc8)"

---

# Jeux, set et match !
**But**
*Apprendre à distinguer les jeux de donnée et les prédictions d'un système de Machine Learning*

**Description de l'exercice**
L'exercice comprend une liste de système fonctionnant avec du Machine Learning. Les étudiants doivent à partir de cette liste trouver les jeux de donnée et les prédictions possible de chaque systèmes.

**Moyen**
* Par groupe de 3
* 20 min