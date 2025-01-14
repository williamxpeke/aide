# Introduction

 Lors de la lecture de cet article, vous allez apprendre comment vous connecter en SSH à votre VPS à l'aide de Putty.

# Sommaire
- [Installation de Putty](#installation-de-putty)
- [Préparation de donnès de connexion](#preparation-de-donnès-de-connexion)
- [Connexion avec Putty](#connexion-avec-putty)

## Installation de Putty

1) Cliquez [ici](https://the.earth.li/~sgtatham/putty/latest/x86/putty.exe) afin d'installer Putty dans sa dernière version.  
Après télèchargement, installez le logiciel, ouvrez-le, ça devrait ressembler à sa. 

![image](https://user-images.githubusercontent.com/76696559/147499268-dad12c09-9e2b-4317-b84c-36086559dd85.png)

## Préparation de donnès de connexion

1) Connectez vous à votre espace client.
2) Cliquez sur la machine à la quelle vous souhaitais vous connecter. Vous devriez voir quelque chose comme sa.  
En rouge, vous aurais l'ip de votre machine garder-la préciseuement, elle servira à vous connecter à votre vps.
![image](https://user-images.githubusercontent.com/76696559/147499694-4131d9d2-5469-4467-b42f-ac6a342b9b7a.png)

3) Scrollez vers le bas et vérifiez que votre machine est belle et bien allumé, comme ci-dessous (Si ce n'est pas le cas démarrer-la):
![image](https://user-images.githubusercontent.com/76696559/147499812-d0694f6d-c12e-4d44-91c9-c494c1bd2176.png)

4) Notez que lors de l'achat de votre vps, vous avez dût choisir le mot de passe de votre vps. Si vous ne vous en rappeler plus, réinitialiser votre vps à nouveau et l'option pour choisir un nouveau mot de passe devrais apparaitre. Mais attention, toute vos données seront effacer, mais si votre vps est vierge cela ne devrais pas causer de soucis pour vous.

## Connexion avec Putty

Maintenant que vous avez l'ip de votre machine et son mot de passe vous êtes fin près à vous y connecter !
1) Rendez vous sur Putty et dans le champs "Host Name (or Ip adress)" renseignez l'ip de votre vps.
2) Pour les prochaines fois, donner un nom à votre session pour pouvoir y vous connecter plus facilement par la suite.
![image](https://user-images.githubusercontent.com/76696559/147500380-61cf0146-fa06-47d3-a045-5f795cd4f5dd.png)
3) Cliquez sur "Save" pour enregistrer votre session.
4) Selectionnez votre nouvelle session et cliquez sur "Open"
5) Vous devriez avoir une fenêtre noir, mettez votre nom d'utilisateur (root par défaut) et appuyez sur entrer.
![image](https://user-images.githubusercontent.com/76696559/147500560-e4a229d2-9c27-4ddd-8231-54e560a65e59.png)

6) Ensuite, une deuxième information devrais vous demander: le mot de passe
![image](https://user-images.githubusercontent.com/76696559/147500621-8732edcf-6bc1-43bb-9b79-6eb430a2557c.png)

7) Une fois votre mot de passe mis, appuyez sur entrer et voilà! Vous êtes à présent connecter en SSH sur votre VPS avec Putty.
