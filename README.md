# p1r4t3_pneus
This script allow you to buy, and change your vehicle tires on esx based servers, enjoy it! 

Ce script vous permet d'acheter, et de changer les pneus de votre véhicule sur votre serveur utilisant le framework ESX, bon jeu!
n'oubliez pas d'ajouter l'item "pneu" via ce sql si vous utilisez le système de gestion d'item natif d'ESX:

INSERT INTO items (`name`,`label`,`limit`,`rare`,`can_remove`) VALUES
('pneu', 'Pneu', 1, 0, 1);

Ou inclure ceci dans le fichier items.lua de votre script ox_inventory:

	["pneu"] = {
		label = "Pneu",
		weight = 1000,
		stack = true,
		close = true,
	},
