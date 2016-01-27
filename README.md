#**Projet "Ma BU en ligne"**  #
----------


># Contexte: #

La bibliothèque universitaire souhaite intégrer la mobilité au sein de son processus d'emprunt de livres. Pour cela, il faudra implémenter toutes les fonctionnalités existantes dans le système de la bibliothèque en y intégrant des options dynamiques et esthétiques.

># Les objectifs: #

- Créer une interface pour la gestion de chaque utilisateur(lambda et lecteur)

	* L'utilisateur (lambda) pourra:

		1. accéder aux informations générale de la BU(infos pratiques)

		2. rechercher un livre selon différents critères (catégorie, nom, auteur, etc.)

		3. être mis en relation avec les contacts de la BU

	* L'utilisateur(lecteur) pourra:

		1. se connecter sur son compte

		2. consulter la liste des livres qu'il a empruntés / historique des prêts

		3. prolonger ses prêts

		4. paramétrer ses alertes de rendu

		5. afficher des notifications "alerte" en fonction de la date de rendu paramétrée

		6. consulter ses retards et pénalités

		7. accéder à toutes les fonctionnalités de l'utilisateur lambda


>#Logique d'utilisation:

Si l'utilisateur est un lecteur (authentification grâce à son login et mot de passe)

* Page d'accueil proposant toutes les options précédemment décrites (cf.Les objectifs)

* Ces options seront personnalisées en fonction de l'utilisateur connecté

Si l'utilisateur est un visiteur(pas d'authentification)

* Page d'accueil proposant les options qui incombent à l'utilisateur lambda


>#Choix technique:

Développement mobile: Android