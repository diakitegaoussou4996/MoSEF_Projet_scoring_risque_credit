# MoSEF_Projet_scoring_risque_credit (15,5/20)

Ce projet faisait partie d'un cours sur le scoring et comprenait un challenge organisé en collaboration 
avec la banque LCL et les étudiants du programme MoSEF à l'Université Paris 1 Panthéon-Sorbonne.
L'objectif principal du projet était de modéliser la probabilité de défaut de remboursement à 36 mois pour des dossiers immobiliers 
et de construire une grille de score pour évaluer les clients connus. Ce score serait utilisé comme outil d'aide à la décision 
pour les conseillers en crédit immobilier lors de l'acceptation ou du rejet d'une demande de prêt.

Les bases de données fournies contenaient des informations sur les prêts immobiliers des clients. Cependant, un défi supplémentaire
est survenu lors de la découverte de deux types d'individus emprunteurs différents dans la base de données. D'une part, il y avait 
des particuliers qui empruntent pour l'achat de maisons individuelles, et d'autre part, il y avait des individus qui empruntent pour
des projets immobiliers tels que la construction de maisons à des fins locatives.

La solution consistait donc à développer deux modèles distincts pour ces deux types d'emprunteurs. Malheureusement, nous avons 
réalisé cette nécessité un peu tard dans le projet, tandis que les gagnants du challenge avaient déjà pris en compte cette distinction
dès le début et ont développé des modèles séparés pour chaque type d'emprunteur.

Malgré cette contrainte, le projet visait à mettre en place un modèle de scoring solide pour évaluer la probabilité de défaut de remboursement
des dossiers immobiliers, en utilisant les données disponibles dans les bases de données fournies par la banque LCL.
