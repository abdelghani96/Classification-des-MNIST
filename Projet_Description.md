# Classification-des-MNIST
Dans ce rapport, nous formons et testons un ensemble de classificateurs pour l'analyse de modèles afin de résoudre les problèmes de reconnaissance de chiffres manuscrits, en utilisant la base de données MNIST

Description des données Mnist
L'ensemble de données MNIST se compose d'un total de 70 000 images ; 60 000 images de formation (utilisés pour créer un modèle IR) et 10 000 images de test (utilisés pour évaluer l'exactitude du modèle). Chaque image MNIST est une image numérisée d'un personnage à un seul chiffre manuscrites. Chaque image est 28 x 28 pixels de taille. Chaque valeur de pixel est entre 0, qui représente le blanc, et 255, ce qui représente le noir. Valeurs des pixels intermédiaires représentent des nuances de gris.

le planing de ce projet est le suivant :
Chargement du jeu de données d'Images Mnist:nous allons importer le jeu de données MNIST à partier de site de Yann LeCun(The Godfather of Deep Learning & AI)  "http://yann.lecun.com/exdb/mnist/" .
La configuration des hyperparamètres : dans cette étape on déterminera la taille des entrées, des couches cachées et des sorties.
Introduction du modèle d'entrainement :  la mise en place des poids et des biais utilisés lors de l'apprentissage.c'est la phase de la construction des réseaux de neurones, elle comporte ainsi la calcule d'une fonction perte(loss function) pour estimer l'erreur et puis la diminuer en utilisant un optimiseur adaptatif Adam.
L'entrainement du modèle: c'est la phase d'apprentissage de notre modèle, les étapes sont par précédes par des commentaires explicatifs de  l'opération.
Le test de la précision prédictive : après que l'entrainement se termine nous allons tester la puissance prédictive du modèle sur le jeu de données du test pour estimer la précision du modèle.
