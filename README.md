# Projet_Gestion_Patient

Framework: Symfony
Langages Utilisés: PHP, HTML, CSS

Contexte du Projet :Projet d'Atelier Professionnel fait en 2e Année de BTS SIO, autour du contexte d'un Hôpital souhaitant une application afin de gérer les séjours des patients

Besoin: Une application de gestion des séjours des patients doit être développée.
Lorsqu’un patient doit subir une intervention ou un examen nécessitant une hospitalisation (même dans le cas d’une hospitalisation en ambulatoire), il séjourne dans l’hôpital, dans un lit d’une chambre. On
parle de séjour

Le but de cette application est de pouvoir :
 Ajouter un nouveau patient, modifier des patients existants.
 Gérer les séjours des patients.
 Prendre en compte l'arrivée d'un patient dans un service.
 Prendre en compte la sortie d'un patient d'un service.
 Consulter les séjours à une date donnée.
 Consulter les séjours à venir

Il y a 2 versions :
-Une version faite lors du travail de Groupe qui est incomplète et n'est pas fonctionnelle
-Une version faite seule après la deadline du travail et qui est complète 


Fonctionnalités de cette Application :

-Possibilités de se connecter avec un identifiant et un mot de passe

Il existe 3 rôles :
-Administrateur: Rôle donné pour l'admiistrateur du site de l'hôpital
-Administration: Partie Administration de l'hôpital
-Infirmier: Partie Infirmerie de l'hôpital

Fonctionnalités de chaque rôle:

Administrateur:
-Accès à un Dashboard
-Ajout, Suppression, Modification de rôle
-Ajout, Suppression, Modification, Visualisation de service

Administration:
-Ajout, Suppression, Modification de Patients
-Ajout, Suppression, Modification de Séjours

Infirmier:

Partie Gestion des arrivées et sorties des patients:
-Visualisation du Séjour
-Visualisation du Patient
-Possibilité de valider une arrivée ou une sortie d'un patient
-Afficher les arrivées et sorties du jour

Partie Consultation des séjours à une date donnée / commençant à une date donnée / à venir:
-Consultation des séjours
-Visualisation des séjours
-Validation