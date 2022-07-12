# StageAfpa

Projet en Collaboration avec ALTAMEOS MULTiMEDIA
M. Lucas SCHNEKENBURGER
9Bis rue du Puits Carré – 27000 Evreux



1er jour :

Création du repository (StageAfpa).
Création du dossier qui va contenir le projet du stage.


Explication du projet:

 Outil de gestion de devis/facturation
 
 -Gestion des utilisateur
 -Gestion des devis
 -Gestion des facturation
 -Gestion des informations utiles (personnalisation logo, information utilisateur etc (numéro de siret, information administrative))

Différentes tables:

-Table utilisateur
          -ID utilisateur
          -Nom d'utilisateur
          -mot de passe (encryptage sha1)
          -Type utilisateur
-Table produit
          -ID produit
          -Nom produit
          -Prix Produit
          -Quantite produit
          -Description produit
-Table client
           -ID client
           -Nom client
           -Prenom client
           -ville client
           -adress1 client
           -adress2 client
           -adress3 client
           -Code postale client
           -Mail client
           -Telephone client
-Table devis
           -ID devis
           -Date devis
           -Status devis
           -Total devis
           -Type payment devis
-Table facture
           -ID facture
           -Status facture
           -Total facture
           


Faire differents niveaux de droit, sur 3 niveau le troisième etant le plus faible et le niveau 0 le superAdmin
      -Niveau 3 consultation de SES facture et devis uniquement
      -Niveau 2 consultation des devis/factures + modification des devis
      -Niveau 1 consultation des devis/facture + creation/modification de devis + creation facture
      -Niveau 0 droits totals sur toutes les actions, attribution des droits aux utilisateurs
      
      
Jour 2 :


   Mise en place de la base de donnée
   préparation des requêtes SQL pour les pages connexion/inscription
   plus de précision sur l'outils a développer, outils de gestion de devis/facture + dashboard de gestion de comptabilité pour l'entreprise.
   pouvoir faire un bilan des sommes perçu, des taxes, des cotisation sociales générer toutes les information essentiel a la comptabilité
   avoir la possibilité de trié les facture/devis par date / par etat (payé/impayé).
   Mise en place de TOKEN (valeur dynamique pour authentifié un changement) utilisé pour la renitialisation du mot de passe, ainsi que pour la
   vérification de la signature du devis.
   
   

