# Montreal Rent Car — site public et CRM de démonstration

Projet HTML5, CSS3 et JavaScript Vanilla, avec stockage de démonstration dans LocalStorage.

## Lancer localement

- Décompresser le projet.
- Ouvrir `index.html` dans un navigateur, ou servir le dossier avec un serveur local (ex. extension Live Server de VS Code).
- Page publique : `index.html`
- CRM : `admin/login.html`
- Identifiants de démonstration : **admin / admin123**

## Fonctionnalités

- Site public, catalogue, filtres, formulaire de demande de réservation, contact.
- Les demandes du formulaire public sont enregistrées dans le LocalStorage et apparaissent dans le CRM.
- Données de départ de véhicules démonstratives, avec photos externes (Unsplash).

## Limites

- Le LocalStorage est propre au navigateur/appareil : pas de synchronisation serveur ou multi-utilisateur.
- La connexion administrateur est une protection de démonstration, pas une sécurité de production.
- Le formulaire de contact affiche une confirmation locale et n'envoie pas de courriel.
- Les véhicules et tarifs de départ sont des données de démonstration, à vérifier auprès de l'agence avant mise en ligne.
- Une vraie mise en production nécessitera API, base de données, authentification sécurisée, gestion des images et intégration de notification.


## Flotte intégrée depuis le catalogue officiel

Le catalogue initial reprend les 17 entrées et tarifs affichés sur la page flotte officielle consultée le 23 novembre 2026. Les tarifs sont enregistrés en EUR. Les images sont illustratives et les fiches techniques non explicitement publiées (année, immatriculation, kilométrage) restent des valeurs de démonstration.
