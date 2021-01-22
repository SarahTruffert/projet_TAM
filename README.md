# Exploiter-l-opendata-des-horaires-de-la-TAM
Guide d'utilisation :

I- CSV et BDD

Si vous avez déja une base de donnée :


Indiquez le chemin de votre fichier csv et de votre fichier base de donnée suivi des arguments de la partie II.

OU 

Assurez vous d'avoir une connexion pour charger la bdd depuis le site de la TAM dans votre terminal avec les commandes :

exemple : > python .\transport.py -u suivi des arguments de votre choix.

(La fonction -u permet de télécharger le fichier .csv de la TAM et de le transformer en bdd)




II- Les arguments 


-t :


  La fonction -t(time) permet d’afficher le prochain tram dans votre terminal.  
  
  Entrez « -t » suivi de la ligne, du nom de votre arrêt et de sa direction
  
  exemple : -u -t 2 SABINES JACOU 
  
  le Terminal affiche :
  
  (21:37)


-n :

  La fonction -n(next) affiche les 3 prochains tramways ou bus à un arrêt donné
  
  Entrez « -u, -n et le nom de l'arrêt » dans votre terminal
  
  
  exemple : -u -n JACOU
  
  le terminal affiche :
  
  The ligne 2 Destination to SABINES Is coming in 6 minutes
  
  The ligne 22 Destination to JACOU COLLEGE Is coming in 13 minutes
  
  The ligne 2 Destination to SABINES Is coming in 21 minutes
