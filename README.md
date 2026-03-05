# Projet_Gestion_Patient

Framework: Symfony
Langages Utilisés: PHP, HTML, CSS

Contexte du Projet :Projet d'Atelier Professionnel fait en 2e Année de BTS SIO, autour du contexte d'un Hôpital souhaitant une application afin de gérer les séjours des patients

Besoin: Une application de gestion des séjours des patients doit être développée.
Lorsqu’un patient doit subir une intervention ou un examen nécessitant une hospitalisation (même dans le cas d’une hospitalisation en ambulatoire), il séjourne dans l’hôpital, dans un lit d’une chambre. On
parle de séjour

Le but de cette application est de pouvoir :<br>
-> Ajouter un nouveau patient, modifier des patients existants.<br>
-> Gérer les séjours des patients.<br>
-> Prendre en compte l'arrivée d'un patient dans un service.<br>
-> Prendre en compte la sortie d'un patient d'un service.<br>
-> Consulter les séjours à une date donnée.<br>
-> Consulter les séjours à venir<br>

Il y a 2 versions :<br>
-Une version faite lors du travail de Groupe qui est incomplète et n'est pas fonctionnelle<br>
-Une version faite seule après la deadline du travail et qui est complète <br>

Ce dépôt correspond à la version faite en groupe

Fonctionnalités de cette Application :

-Possibilités de se connecter avec un identifiant et un mot de passe

Il existe 3 rôles :<br>
-Administrateur: Rôle donné pour l'admiistrateur du site de l'hôpital<br>
-Administration: Partie Administration de l'hôpital<br>
-Infirmier: Partie Infirmerie de l'hôpital<br>

Fonctionnalités de chaque rôle:

Administrateur:<br>
-Accès à un Dashboard<br>
-Ajout, Suppression, Modification de rôle<br>
-Ajout, Suppression, Modification, Visualisation de service<br>

Administration:<br>
-Ajout, Suppression, Modification de Patients<br>
-Ajout, Suppression, Modification de Séjours<br>

Infirmier:

Partie Gestion des arrivées et sorties des patients:<br>
-Visualisation du Séjour<br>
-Visualisation du Patient<br>
-Possibilité de valider une arrivée ou une sortie d'un patient<br>
-Afficher les arrivées et sorties du jour<br>

Partie Consultation des séjours à une date donnée / commençant à une date donnée / à venir:<br>
-Consultation des séjours<br>
-Visualisation des séjours<br>
-Validation<br>
