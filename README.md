CampusConnect

PRESENTER LE PROJET
CampusConnect est une plateforme collaborative concue pour les etudiants universitaires. Son objectif principal est de centraliser la decouverte des evenements universitaires et de simplifier le processus d inscription.

ETAT REEL DU PROJET
Le projet est actuellement en phase de conception. Le backlog, les specifications fonctionnelles et les diagrammes d architecture sont en cours de finalisation. Aucune fonctionnalite n est encore deployee en production.

FONCTIONNALITES ENVISAGEES
Consulter la liste des evenements a venir.
Rechercher et filtrer les evenements par categorie ou par date.
S inscrire aux evenements et gerer ses participations.
Gerer les evenements pour les organisateurs (creation, modification, annulation).

OUTILS UTILISES
Jira : Gestion agile du backlog, suivi des User Stories et des Sprints.
Confluence : Documentation fonctionnelle, technique et guides utilisateur.
GitHub : Gestion du code source et versionnement de la documentation.

DOCUMENTATION ET LIENS
Espace Confluence CampusConnect : consulter la documentation complete du projet.
Specifications fonctionnelles : detail de la User Story CCG4-7 dans Confluence.
Diagrammes UML : cas d utilisation, classes et sequence disponibles dans Confluence.

CONSIGNES DE CONTRIBUTION

1. Creer une branche deduite par fonctionnalite sous le format feature/nom-de-la-fonctionnalite.
2. Suivre les conventions de nommage pour les messages de commit.
3. Soumettre une Pull Request pour relecture avant toute fusion sur la branche main.

PARTIE 5 : AMELIORATION AVEC CHATGPT

1. Version initiale de la specification
Reprise de la Partie 2 : l etudiant clique sur s inscrire, verification des preconditions, criteres d acceptation basiques sans gestion fine des erreurs ou des cas limites.
2. Proposition de l IA (apres soumission du prompt)
Ameliorations suggerees par l IA :
Préciser le statut exact de l inscription (exemple : Confirmee ou En attente).
Ajouter un critere d acceptation explicite concernant la reception de l e-mail de confirmation.
Clarifier le comportement exact si l etudiant modifie ses choix ou annule.
Isoler la regle metier de la liste d attente comme un point a valider imperativement avec le Product Owner.
3. Analyse argumentee (Retenus vs Rejetes)
Modifications retenues : L ajout du statut d inscription et la precision sur l e-mail de confirmation ont ete integres car ils clarifient nettement l experience utilisateur et les exigences techniques associees.
Modifications mejetees : La proposition de l IA d integrer nativement un systeme de liste d attente complexe a ete rejetee pour ce sprint, car le Product Owner n a pas encore valide cette fonctionnalite dans le perimetre fonctionnel initial (MVP).

PARTIE 6 : COLLABORATION ET VERIFICATION FINALE

Preuve de relecture collaborative :
Une relecture croisee de la page Confluence Documentation fonctionnelle a ete realisee par un membre de l equipe (exemple : relecture de la US-04).
Commentaire ajoute : Attention a bien preciser le delai limite d annulation si l etudiant souhaite se desister.
Correction integree : Ajout d une regle metier concernant l annulation possible jusqu a 24h avant l evenement.
