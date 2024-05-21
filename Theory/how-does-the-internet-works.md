# How the internet Works
__*Internet est un réseau mondial qui connecte des millions d'ordinateurs*__ et d'autres appareils, leur permettant de communiquer entre eux. Imagine Internet comme un système postal géant qui transporte des informations sous forme de paquets de données d'un appareil à un autre.

[![Schema - How the internet Works](https://culture-informatique.net/wp-content/uploads/2014/08/internet.png)](https://developer.mozilla.org/fr/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)

### Les Bases du Fonctionnement

1. **Réseaux Interconnectés** : Internet est constitué de nombreux réseaux plus petits reliés entre eux. Chaque appareil connecté à Internet fait partie d'un de ces réseaux.

2. **Protocoles** : Les appareils communiquent en utilisant des règles appelées "[protocoles](https://fr.wikipedia.org/wiki/Protocole)". Le principal protocole utilisé sur Internet est le TCP/IP (Transmission Control [protocoles](https://fr.wikipedia.org/wiki/Protocole)/Internet Protocol). Ces [protocoles](https://fr.wikipedia.org/wiki/Protocole) permettent aux données de voyager d'un point A à un point B de manière fiable.

3. **Paquets de Données** : Les informations envoyées sur Internet sont divisées en petits morceaux appelés "paquets". Chaque paquet contient une partie des données et des informations sur son origine et sa destination.

4. **Routeurs** : Les routeurs sont des appareils qui dirigent les paquets de données à travers les différents réseaux jusqu'à leur destination finale. Ils fonctionnent un peu comme des panneaux de signalisation sur une route.

### Comment ça Marche en Pratique

1. **Connexion à Internet** : Pour se connecter à Internet, on utilise un fournisseur d'accès Internet (FAI) qui nous permet de rejoindre le réseau global.

1. **Requête** : Quand vous voulez visiter un site web, par exemple, votre ordinateur envoie une requête à un serveur (un ordinateur spécial qui héberge le site web) via votre FAI.

1. **Serveurs et Adresses IP** : Chaque appareil connecté à Internet possède une adresse unique appelée adresse IP (Internet Protocol). Les serveurs utilisent ces adresses pour envoyer les informations au bon endroit.

1. **DNS (Domain Name System)** : Les adresses IP étant difficiles à retenir, on utilise des noms de domaine (comme www.exemple.com). Le DNS traduit ces noms de domaine en adresses IP.

1. **Transmission de Données** : Les informations du site web sont envoyées en paquets de données depuis le serveur à votre ordinateur, passant par divers routeurs et réseaux. Votre navigateur web assemble ces paquets pour afficher le site web.

#### Code de Traduction d'un Nom de Domaine en Adresse IP (DNS)

**Code en Python :**
`
import socket
domain_name = "www.exemple.com"
ip_address = socket.gethostbyname(domain_name)
print("Adresse IP de", domain_name, "est", ip_address)`

> Data is a precious thing and will last longer than the systems themselves.
> 
> **- Tim Berners-Lee**

### Pour Résumer

Internet fonctionne comme une gigantesque toile d'araignée de réseaux interconnectés. Les données sont envoyées sous forme de paquets via des routeurs, en suivant des [protocoles](https://fr.wikipedia.org/wiki/Protocole) spécifiques pour s'assurer qu'elles arrivent à destination correctement. Les noms de domaine simplifient la navigation en traduisant des adresses IP en termes faciles à retenir.

En termes simples, Internet permet à différents appareils de communiquer entre eux en utilisant un système organisé de règles et de chemins pour envoyer et recevoir des informations.
#### En 5 points
- Connexion à Internet
- Requête
- Serveurs et Adresses IP
- DNS (Domain Name System)
- Transmission de Données

<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXY3NWhpa2F1aG51NzVmdXBkZHQ4Z2p0eW9yMWd0azd0ajNoejU3ZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Vk1uLMncfuMFi/giphy.gif" width="500" height="500" alt="Paul Astreid before is fight">