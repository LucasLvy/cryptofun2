[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Discord][discord-shield]][discord-url]
[![Telegram][telegram-shield]][telegram-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]
[![Reddit][reddit-shield]][reddit-url]
![GitHub Logo](https://token.smartlink.so/wp-content/uploads/2021/04/Logo-HD-1.png)

[contributors-shield]: https://img.shields.io/github/contributors/SmartLlink/Smartlink-Escrow.svg?style=for-the-badge
[contributors-url]: https://github.com/SmartLlink/Smartlink-Escrow/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SmartLlink/Smartlink-Escrow.svg?style=for-the-badge
[forks-url]: https://github.com/SmartLlink/Smartlink-Escrow/network/members
[telegram-url]: https://t.me/smartlinkofficial
[telegram-shield]: https://img.shields.io/badge/-Telegram-black.svg?style=for-the-badge&logo=Telegram&colorB=555
[linkedin-url]: https://www.linkedin.com/company/smartlinkso
[linkedin-shield]: https://img.shields.io/badge/-Linkedin-black.svg?style=for-the-badge&logo=Linkedin&colorB=555
[discord-shield]: https://img.shields.io/badge/-Discord-black.svg?style=for-the-badge&logo=discord&colorB=555
[discord-url]:https://discord.gg/Rut5xxqGWQ
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=twitter&colorB=555
[twitter-url]:https://twitter.com/smartlinkHQ
[reddit-shield]: https://img.shields.io/badge/-reddit-black.svg?style=for-the-badge&logo=reddit&colorB=555
[reddit-url]:https://www.reddit.com/user/Teamsmartlink/

###### Home
Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![home](https://ipfs.io/ipfs/Qmd1q8kxZmrqeZYQyp68QTuyL1fAPH21NuuyjuMJfR7xB5)  |  ![marketplace](https://ipfs.io/ipfs/QmRfVmL5PuFHutsafEBcfMnZ59AAXTZpkkpSHKT2WK1hKj)
 
##### Offers
![offers](https://ipfs.io/ipfs/QmbRxnZyEcEZkURqc25j2jdSNwBKZM9HP9MzdHcvwfS53x)
##### Tracking
![tracking](https://ipfs.io/ipfs/QmQ9cmeSqK73Y9APQEivXFbHCL5svvQGeLTgwtoFGJ9rTq)
##### Admin
![marketplace](https://ipfs.io/ipfs/QmUWqrQ3EJsPGHFtbYu2PbvA7G3UUNsxjWR2ofr8QqTvMY)


# CryptoFun

Bienvenue sur le site CryptoFun, réalisé par Quentin GIBON et Lucas LEVY.

-----------------
## Dependencies

Server: 
- Dotenv: permet d'acceder au fichier .env
- Express: permet de gérer la partie de routing
- Isomorphic fetch: permet d'assurer la consistence de la fonction fetch pour n'importe quel navigateur
- Jsonwebtoken: permet de gérer les connexions des utilisateurs à l'aide de tokens
- Token utils: permet d'effectuer des opérations sur les tokens

-----------------
## Lancement

Pour lancer la partie serveur, se placer le dossier `server` et taper la commande `npm run dev`.  

Pour lancer la partie client, se placer le dossier `client` et taper la commande `npm start`.  
Puis cliquer sur l'adresse du site en local qui est donnée.

-----------------

## Principe

Ce site a pour objectif de faire découvrir le monde des cryptommonaies et de la blockchain à l'utilisateur. Il intègre également un petit 'jeux de trading' pour impliquer l'utilisateur dans cet univers et lui permettre de tester ses capacités de trader.  

### Page d'accueil

Simple accueil du site.  

### Page Comprendre

Cette page contient des cours et informations utiles à la compréhension des cryptos, divisé en deux parties : les __cryptomonnaies__ et la __blockchain__.  

### Page Graphiques

Cette page permet de visualiser les prix et cours des cryptomonnaies les plus importantes. Les informations sont fournies par [CoinMarketCap](https://coinmarketcap.com/).  

### Page Wallet

Ici, l'utilisateur pourra accèder à son compte utilisateur. Après avoir rentré ses identifiants, il accède à une page personnelle où sont affichés plusieurs informations :

* __Valeur totale__ est ce que possède réellement l'utilisateur, c'est à dire la valeur de ses cryptos et de ses dollars, en temps réel et calculé en dollars.
* __Monnaie disponible__ est la quantité en dollars que l'utilisateur a à disposition. Cette valeur ne change que s'il achète des cryptos ou en vend.
* __Cryptos disponibles__ est la liste de toutes les cryptos que l'utilisateur a en sa possession, ainsi que leur quantité.

L'objectif est donc d'avoir une quantité __Valeur totale__ la plus grande possible, en achetant au prix le plus bas et en revendant au plus haut les cryptos dans la partie `Trading` situé en dessous des possessions.

### Page A Propos

Petite description du contexte de ce site.
