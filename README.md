# Exploiter-l-opendata-des-horaires-de-la-TAM
Guide d'utilisation :

I- CSV et BDD

Si vous avez déja une base de donnée indiquez le chemin de votre csv et de votre fichier base de donnée suivi des arguments de la partie II.

OU 

Assurez vous d'avoir une connexion pour charger la bdd depuis le site de la TAM dans votre terminal avec les commandes :
> python .\transport.py -u suivi des arguments de votre choix.
(La fonction -u permet de télécharger la base de donnée en .csv directement via site de la tam)
  


II- Les arguments 
-t :
  La fonction -t(time) permet d’afficher le prochain tram dans votre terminal.  
  Entrez « -t » suivi du nom de votre arrêt et de sa direction
  exemple : -u -t 2 SABINES JACOU le Terminal affiche (21:37)

-n :
  La fonction -n(next) affiche les 3 prochains tramways ou bus à un arret donné
  Entrez « -u, -t, -n » dans votre terminal 
  exemple : u -t -n JACOU
