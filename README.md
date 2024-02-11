------------------------------------------------------------------------------------------------------
PROJET METRIQUES
------------------------------------------------------------------------------------------------------
Quels sont les notions qui vont être abordés lors cet atelier ?
Cet atelier a pour objectif de vous apprendre à créer des graphiques (métriques) grace à Python et la construction d'API.
Vous allez utiliser et mettre en oeuvre, au travers de cet atelier, un serveur Python utilisant le frameworks Flask. 
Vous allez créer des API, découvrir les actions et les secrets de GitHUB pour au final la mise en services des bibliothèques graphiques.
Large programme mais tout à fait accessible et ne nécessitant pas de base technique particulière. Juste de l'observation et de la rigueur.

-------------------------------------------------------------------------------------------------------
Séquence 1 : GitHUB
-------------------------------------------------------------------------------------------------------
Objectif : Création d'un repository GitHUB pour travailler avec son code  
Difficulté : Faible (~10 minutes)
-------------------------------------------------------------------------------------------------------
GitHUB est une plateforme en ligne utilisée pour stocker le code de son programme.
GitHUB est organisé en "Repository", c'est à dire en répertoire (contenant lui même des sous répertoires et des fichiers). Chaque Repository sera indépendant des autres. Un Repository peu être vu comme un projet unique.

**Procedure à suivre :**  
1° - Créer vous un compte sur GitHub : https://github.com/  
Si besoin, un vidéo pour vous aider à créer votre propre compte GitHUB : [Créer un compte GitHUB](https://docs.github.com/fr/get-started/onboarding/getting-started-with-your-github-account)  
A noter que si vous possédez déjà un compte GitHUB vous pouvez le conserver pour réaliser cet atelier. Pas besion d'en créer un nouveau.

2° - Faites un Fork du Repository suivant : https://github.com/OpenRSI/5MCSI_Metriques.git  
Si besion, voici une vidéo d'accompagnement pour vous aider : [Forker ce projet](https://youtu.be/p33-7XQ29zQ)    
  
**Travail demandé :** Créé votre compte, faites le fork de ce projet et **copier l'URL de votre repository GitHUB dans la discussion public**.

Notion acquise lors de cette séquence :  
Vous avez appris lors de cette séquence à créer des repository pour stocker et travailler avec votre code informatique. Vous pourez par la suite travailler en groupe sur un projet. Vous avez également appris à faire des forks. C'est à dire, faire des copies de projets déjà existant dans GitHUB que vous pourrez ensuite adapter à vos besions.

---------------------------------------------------
Séquence 2 : Création d'un hébergement en ligne
---------------------------------------------------
Objectif : Créer un hébergement sur Alawaysdata  
Difficulté : Faible (~15 minutes)
---------------------------------------------------

Rendez-vous sur **https://www.alwaysdata.com/fr/**  
  
Remarque : **Attention à bien vous rappeler vos Login/Password** lors de la création de votre compte car vous en aurez besoin plus tard pour la création de vos "Secrets GitHUB".

**Procédure :**  
1° - Créez votre compte (gratuit jusqu'à 100Mo).  
2° - Depuis la console d'administration (Panel d'administration) :  
 . 2.1 - Cliquez sur "Sites" (Colonne de gauche) puis supprimer votre site PHP (avec la Poubelle).  
 . 2.2 - Installer ensuite une application Flask (Bouton + Installer une application).  
 . . 2.2.1 Adresses = utilisez le sous-domaine qui vous appartient que vous trouverez dans l'information " Les sous-domaines suivants vous appartiennent et sont actuellement inutilisés : {Site}.alwaysdata.net  
 . . 2.2.2 Répertoire d'installation = /www/flask  
 . 2.2.3 N'oubliez pas d'Accepter les conditions.  
3° - Autoriser les connexions SSH  
 . 3.1 - Cliquez sur SSH (Accès distant)  
 . 3.2 - Modifier les paramètres de votre utilisateur  
 . 3.3 - Définissez si besion un nouveau mot de passe  
 . 3.4 - Cliquez sur **Activer la connexion par mot de passe**  




  https://youtu.be/6cuHjy8n968
**Travail demandé :** Mettre en ligne votre application et **copier l'URL de votre site dans la discussion Discord**.  
  
Notion acquise lors de cette séquence :  
Vous avez créer un hébergement (gratuit) et découvert que vous auriez pu installer bien d'autres applications. 





