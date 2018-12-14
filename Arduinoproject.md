# Rapport Projet d’Arduino  
07/12 :
Pris connaissance de la manière de réaliser le projet : Sur quoi le projet repose principalement ?
Au départ nous partions sur un accéléromètre, pour calculer l’accélération linéaire selon les 3 coordonnées afin de situer la balle dans l’espace.
Après avoir tenté de comprendre le principe de fonctionnement de l’accéléromètre, grâce à l’exxxxxxxxxxxxxxcellent cour de monsieur Masson, nous nous sommes rendu compte qu’il existait un moyen bien plus simple de connaitre la position d’une balle sur un écran.
C’est un écran dit  résistif : qui envoie en output la position x et y de la balle sur la plaque, on note que la position en z (hauteurs) n’est pas utile.
Maintenant que nous avons opté pour un écran reste à choisir le lequel prendre ? Quelle taille ? Le tout avec un prix raisonnable > qui ne sera au finale pas un problème ce type d’écran n’étant pas si cher.
17 Ou 8 pouces ? Dans le deux cas nous avions trouvé des projets similaires au notre, prouvant que les deux écrans étaient compatibles avec celui-ci.
Nous avons noté que plus l’écran était grand moins le « Centrage » de la balle était précis dû à une plus grande incertitude. 
Nous avons, en optant pour la précision, commandé un écran 8pouces.
Reste maintenant à choisir les moteurs : Pas à pas ou servo

14/12 :
Donc, nous commençons par choisir les moteurs .Nous avons étudié plusieurs projets du même type , la plupart utilisent des servomoteurs mais le projet qui nous sert de modèle utilise des moteurs pas à pas cependant , nous avons remarqué la présence d’encodeurs dans ce projet , leurs utilités est de trouver la position zero de chaque moteurs pas à pas, d’autres problèmes sont liés aux moteurs pas à pas, nous avons donc décidé de choisir des servomoteurs pour palier à ces différents soucis.
 Pour la référence exacte du servo, on s’inspire encore une fois de projets similaires pour avoir une idée de la vitesse de rotation et le couple nécessaires au bon fonctionnement de note projet.
On opte finalement pour le servo suivant : MG946R
Pour le moment nous faisons tout en duo mais maintenant il faut répartir les différentes taches afin d’optimiser le temps de travail, nous divisons donc le projet en plusieurs grandes parties :
-Liste du matériel (déjà fait) > Yassine + Baptiste
-Gestion de l’écran résistif > Yassine 
-Gestion du PID (la plus complexe) > Baptiste
-Gestion des Servomoteurs > Yassine
-Gestion du code > Baptiste
-Réalisation matériel (maquette en bois) > Yassine 
Cette répartition étant bien évidemment provisoire. 
Nous allons suivre la progression de chacun constamment, l’assignement des taches correspond juste à une spécification dans un certain domaine.
 

 
 

