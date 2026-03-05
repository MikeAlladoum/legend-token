Legend Token (ERC-20)

Legend Token est un jeton ERC-20 développé en Solidity et déployé sur un réseau de test Ethereum (testnet).
Ce projet a été réalisé dans le but de pratiquer le développement de smart contracts, comprendre le fonctionnement des tokens ERC-20, et tester les interactions avec la blockchain via MetaMask.

Description du projet
 Legend Token est un smart contract qui implémente le standard ERC-20, permettant :
 la création d’un jeton personnalisé le transfert de tokens entre utilisateurs la vérification des soldes  
 l’autorisation de dépenses via approve et transferFrom.
 Le contrat a été déployé sur un testnet Ethereum et les fonctionnalités ont été testées à l’aide de MetaMask.

Technologies utilisées
 Solidity
 Ethereum Testnet
 MetaMask
 Node.js
 Web3.js

Tests réalisés
 Après le déploiement du contrat, plusieurs transactions ont été testées :
 transfert de tokens entre comptes
 consultation du solde (balanceOf)
 approbation d’un tiers (approve)
 transfert via autorisation (transferFrom)
 Toutes les interactions ont été effectuées via MetaMask pour simuler l’utilisation réelle du token.

 Structure du projet
  contracts/
   LegendToken.sol     → Smart contract ERC-20
   scripts/
   deploy.js           → Script de déploiement
   interact.js         → Script d’interaction avec le contrat

README.md              → Documentation du projet
 Objectif du projet
 Ce projet fait partie de mon parcours d’apprentissage pour :
 maîtriser le développement de smart contracts
 comprendre les standards de tokens ERC-20
 apprendre à déployer et interagir avec des contrats sur Ethereum
 construire un portfolio solide en développement blockchain

 Auteur
Mike Alladoum 
Étudiant passionné par la blockchain et les technologies décentralisées.  
[GitHub](https://github.com/MikeAlladoum) | [LinkedIn](https://www.linkedin.com/in/mike-alladoum-a557102a1/?)


