INITIATION DOCKER , GIT GITHUB
-Lors de l'installation j'ai rencontrer u probleme que j'ai reussit a resoudre en telechargeant wsl avec la commande "wsl --install"
-TP 1, lancer mon premier conteneur

1. Exécuter docker run hello-world.
   ![alt text](image.png)

Lister les conteneurs avec docker ps-a.
![alt text](image-1.png)
//voir capture

-TP 2, lancer un serveur web et l'a cher
1.Lancer un serveur nginx relié au port 8080
![alt text](image-2.png)
Le lancement fonctionne a merveille

2.Ouvrir http://localhost:8080 dans mon navigateur
![alt text](image-3.png)
tout marche comme il le faut.

3.Regarder les logs
![alt text](image-4.png)
voir capture

4-Arrêter puis supprimer
![alt text](image-5.png) //arreter
![alt text](image-6.png) //supprimer

-TP 3, entrer dans un conteneur

1. Relancer un conteneur
   ![alt text](image-7.png)
   2.Entrer dedans
   ![alt text](image-8.png)
   3.Explorer le conteneur
   ![alt text](image-9.png)
   4.Sortir avec exit ,puis nettoyer
   ![alt text](image-10.png)
   TP 4, créer ma propre image avec un Dockerfile
   Construire l'image
   ![alt text](image-11.png)
   Lancer l’image
   ![alt text](image-12.png)
   Ouvrir localhost :8080
   ![alt text](image-13.png)
   Nettoyer
   ![alt text](image-14.png)
   TP 5, utiliser docker compose
   Démarrer le compose
   ![alt text](image-15.png)
   Vérifier sur http://localhost:8080.
   ![alt text](image-16.png)
   Arrêter tout avec docker compose down.
   ![alt text](image-17.png)
