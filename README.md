# Systeme-r-partie-centralis-e
Darrell KIDJO
Licence 2 Génie logiciel

Exercice 2:

	1-La valeure finale dans la mémoire partagée est 300.
	
	2-Pour résoudre le problème, nous allons demander a chaque processus fils de bloqué 
		l'accès à la mémoire partagée aux autres processus le temps d'une session critique.
		Ici la session critique représente la lecture du contenue de cette mémoire, l'incrémentation,
		puis la mise à jour de la valeur contenue dans la mémoire partagée. Nous utiliserons alors
		La bibliothèque semaphore.h
		
	3-Solution devellopée dans Projet/Exercice2
	
	Exercice 3:
	
	
Exercice 4:
	1-Les problèmes à résoudre:
			*Indiquer et exploiter le nom du fichier à envoyer
			*parcourir le fichier et envoyer chaque byte au serveur
			*creer un fichier au niveau du serveur portant le nom du fichier
			*recevoir chaque byte envoyé par le client et les insérer dans le fichier
	2-Résolution des problèmes
			*Le nom du fichier est prit en paramètre par le programme client
			*L'ouverture du fichier en mode binaire permet cela
			*envoyer le nom du fichier au serveur avant d'envoyer son contenue, céer le fichier puis lire son contenue envoyer par le contenue
	3- Solution developpée dans Projet/Exercice4
	
Exercice 5:
	1-Les probèmes
		*Emettre le message toutes les 10secondes de facon périodique
	2-l'utilisation de la fonction alarme qui prends en parametre 10 et la creation d"une fonction sensé envoyé le message "Execute" au serveur
		*Un temps de lactence de 5s coté serveur pour permettre de mieux observer la modification de la memoire partagée 
	3-Soulution developpé dans Projet/Exercice5
