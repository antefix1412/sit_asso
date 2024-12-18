Rapport de Collaboration Git

Informations du Projet

Nom du Projet : Assosiation de Sup de Vinci
Membres de l'équipe : Ridwan ABDOULKADER HOUMED - Antoine Lemesle - Titouan Bellec
Lien du Dépôt GitHub : https://github.com/antefix1412/sit_asso.git

Captures d'Écran Git

1. Configuration Global
![alt text](/img/config.png)

2. Gestion des Branches
![alt text](/img/gestionbranches1.png)

3. Historique des Commits
![alt text](/img/commits.png)

4. Status du Projet
![alt text](/img/status.png)

5. Graphe des Branches
![alt text](/img/graphebranches.png)
![alt text](/img/graphebranches2.png)


Analyse des Commandes

Nombre total de commits
Commande : git rev-list --count main
Résultat : 37 commits 

Contributions individuelles
Commande : git rev-list --count « nom de la branche »

Ridwan : 21 commit
Antoine : 7 commit
Titouan : 9 commit

Défis et Résolutions de Conflits

Description des conflits rencontrés

Nous avons rencontré plusieurs défis pendant ce projet. 
Le premier conflit rencontré était au moment où on a voulu merge nos branches vers le main. Un conflit à apparu parce que deux développeurs ont voulu modifier l’index en même temps.  Ce conflit est survenu lorsqu'une branche a été fusionnée dans une autre, en particulier si les deux branches contiennent des modifications incompatibles. C’est ce qui à causer le problème. 
Le deuxième conflit est apparu lorsque le développeur à essayer de merge sa branche vers le main. Mais sans le savoir il modifier son code html de sa page sur le main de sa machine. Donc il n’était pas sur sa branche. 

Méthodes de résolution

Pour le premier le conflit, Il a été résolu grâce à des modifications manuelles. Les deux développeurs se sont mis en accord pour garder qu’une des deux de leurs modifications. 
Pour le deuxième conflit, le développeur s’est déplacé vers le main, puis il a fait un git add. Et un git commit -m. Et enfin un git push vers le main. 


Captures d'écran des conflits

![alt text](/img/conflit.png)


Rétrospective :

Points positifs de la collaboration :
Nous nous sommes bien organisés et l’on s’est compris sur ce que devait ressembler le site et sur la répartition des tâches de chacun.

Difficultés rencontrées de la collaboration :

Difficulté rencontrée au moment de l’envoi de nos travaux respectif qui empêchait les autres collaborateurs de voir et de travailler sur les partis de chacun.

Apprentissages sur Git

Nous avons appris les bases git et github, avec toutes les commande de bases comme (git add ., git commit, git push, git pull, etc..) et nous avons appris de nos erreurs, et à travailler en collaboration en apprenant à se servir de ghitub qui permet de se transmettre nos codes respectifs pour donner un site ayant été créé en commun.
