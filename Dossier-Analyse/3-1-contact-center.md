## 1. Infos abonnés Webservices ##
En tant qu'opérateur du helpdesk, je veux pouvoir voir les différents abonnés et abonnements aux Webservices ainsi je peux effectuer le suivi des demandes. 

## 2. Infos dépôts rejetés ##
En tant qu'opérateur du helpdesk, je veux pouvoir visualiser les raisons de refus du dépôt du client ainsi je peux fournir toutes les informations nécessaires au client demandeur.

Précondition : l'employé est authentifié

Scénario : 

-  L'employé va dans le menu à gauche et choisi "Index des dépôts" ;
- Un écran de recherche s'affiche que l'employé peut remplir avec les données reçues par le déposant (Numéro d'entreprise, Date de fin d'exercice (année), propriétaire, statut) ;
- Une fois les données encodées, la recherche s'affiche à l'écran sous forme d'un tableau comprenant : le numéro d'entreprise, la date de dépôt (DD-MM-YYYY HH-MM-SS), la période comptable (de - à), le modèle (cfr liste modèles reprise dans [le glossaire](7-0-glossaire.md)), la langue, la devise, le tyde de dépôt (Initial ou correction), le statut (refusé/rejeté après évaluation/brouillon/prêt pour soumission/prêt pour paiement/accepté/erreur d'import/en cours d'investiguation/publié/paiement en cours), référence, propriétaire, date ultime de paiement, référence du paiement; 
- l'employé clique alors sur les trois petits points à droite de la ligne du dépôt ce qui lui donne l'option de pouvoir voir les détails du dépôt :
  - Informations du déposant (Nom, langue, id (ou NUIN), email, numéro de téléphone);
  - Informations du dépôt (ID, entreprise, période comptable, modèle, langue, devise, date de dépôt, type de dépôt, correctif, aller vers le BOC (lien), données du logiciel comptable, rapport de validation, télécharger le ficier PDF, télécharger le fichier XBRL);
  - Historique  des infos du dépôt (liste des différents status(= de ses étapes) du dépôt en question);
  - Les 10 derniers dépôts pour ce numéro d'entreprise (liste des 10 derniers dépôts) ;
  - Historique de paiement (dans ce cas-ci est vide);
- L'employé va dans la partie "Informations du dépôt" et va sur l'option "Informations de la collecte" où l'on retrouve : 
  - l'évaluation du dépôt ;
  - La décision de la collecte ; 
- Dans la section "décision de la collecte", l'employé peut voir les différents commentaires de l'équipe Collecte concernant le dépôt en question ;


## 3. Infos paiement client en attente ##
En tant qu'opérateur du helpdesk, je veux pouvoir avoir accès aux informations de paiement d'un dépôt en attente de paiement ainsi je peux fournir ces informations en cas de demande. 

Précondition : l'employé est authentifié

Scénario : 

- L'employé va dans l'onglet "Comptabilité" ;
- L'employé choisi l'onglet "Toutes les transactions" ;
- Un écran de recherche s'affiche que l'employé peut remplir avec les informations reçues du déclarant ; 
- Le résultat de cette recherche montre le/les dépôts du client avec les informations suivantes sous forme de tableau à colonnes: 
   - Référence du paiement;
   - CCV reference;
   - référence de l'ordre ;
   - date de création de la transaction (ou du paiement);
   - dernière mise à jour;
   - date du statut CCV;
   - date ultime de paiement;
   - statut (en cours, échoué, succès);
   - montant;
   - date de paiement;
   - référence du versement.

- l'employé clique alors sur les trois petits points à droite de la ligne du dépôt ce qui lui donne les options suivantes : Détails du paiement ou créer un remboursement ;
- Ici l'employé choisi l'option "Détails du paiement" ;
- toutes les informations pour le paiement peuvent être téléchargées sous format PDF et directement envoyées au client.

