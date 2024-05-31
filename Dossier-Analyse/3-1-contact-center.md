## 1. Infos abonnés Webservices ##
En tant qu'opérateur du helpdesk, je dois pouvoir voir les différents abonnés et abonnements aux Webservices ainsi je peux effectuer le suivi des demandes. 

## 2. Infos dépôts rejetés ##
En tant qu'opérateur du helpdesk, je dois pouvoir visualiser les raisons de refus du dépôt du client ainsi je peux fournir toutes les informations nécessaires au client demandeur.

Précondition : l'employé est authentifié

Scénario : 

-  L'employé va dans le menu à gauche et choisi "Index des dépôts" ;
- Un écran de recherche s'affiche que l'employé peut remplir avec les données reçues par le déposant (Numéro d'entreprise, Date de fin d'exercice (année), propriétaire, statut) ;
- Une fois les données encodées, la recherche s'affiche à l'écran ; 
- l'employé clique alors sur les trois petits points à droite de la ligne du dépôt ce qui lui donne l'option de pouvoir voir les détails du dépôt ;
- Un premier écran s'ouvre avec les informations suivantes divisées en sections : 
  - Informations du déposant ;
  - Informations du dépôt ;
  - Historique  des infos du dépôt ;
  - Les 10 derniers dépôts pour ce numéro d'entreprise ;
  - Historique de paiement (dans ce cas-ci est vide);
- L'employé va dans la partie "Informations du dépôt" et va sur l'option "Informations de la collecte" ;
- Une nouvelle fenêtre s'ouvre avec plusieurs sections : 
  - Evaluation du dépôt ;
  - Décision de la collecte ; 
- Dans la section "décision de la collecte", l'employé peut voir les différents commentaires de l'équipe Collecte concernant le dépôt en question ;

Post - condition : 

Le refus est consultable sur la page et l'employé peut les communiquer au déposant. 

## 3. Infos paiement client en attente ##
En tant qu'opérateur du helpdesk, je dois pouvoir avoir accès aux informations de paiement d'un dépôt en attente de paiement ainsi je peux fournir ces informations en cas de demande. 

Précondition : l'employé est authentifié

Scénario : 

- L'employé va dans l'onglet "Comptabilité" ;
- L'employé choisi l'onglet "Toutes les transactions" ;
- Un écran de recherche s'affiche que l'employé peut remplir avec les informations reçues du déclarant ; 
- Le résultat de cette recherche montre le/les dépôts du client avec les informations suivantes : 
   - Numéro d'entreprise,
   - ;
- l'employé clique alors sur les trois petits points à droite de la ligne du dépôt ce qui lui donne les options suivantes : Détails du paiement ou créer un remboursement ;
- Ici l'employé choisi l'option "Détails du paiement" ;
- l'écran avec toutes les informations pour le paiement sont visibles à l'écran.

Post-condition : 

L'employé peut voir toutes les informations du paiement pour ce compte et les communiquer au client. 