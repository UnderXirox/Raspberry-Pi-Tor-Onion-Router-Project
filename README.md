# Welcome to Pages Raspberry-Pi-Tor-Onion-Router-Project

Raspberry Pi 3 Onion Project est un système d'exploitation serveur conçu pour la protection de la vie privée. Il rend l'anonymat en ligne possible automatiquement à l'échelle de bureau sur le réseau Tor. Un iptables est reconfiguré à l'intérieur de Raspbiane, offrant une protection contre les fuites IP. Raspberry Pi 3 Onion Project est conçu pour fonctionner sur Raspberry Pi 3.

# Download

**[Download anonymous OS Raspberry Pi 3](https://github.com/teeknofil/Raspberry-Pi-Tor-Onion-Router-Project/settings/Downloads/IMG_RASPBIAN_TOR_ONION_ROUTER/raspbian_tor_onion_router.img)**

## Hardware

[**Kit complet**](https://www.amazon.fr/gp/product/B01CI5879A/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CI5879A&linkCode=as2&tag=hgh0c-21)

[Raspberry Pi Tor Onion Router fonctionne avec Raspberry Pi 3
![Image](http://nsa38.casimages.com/img/2017/01/21/170121045844338319.jpg)
](https://www.amazon.fr/gp/product/B01CI5879A/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CI5879A&linkCode=as2&tag=hgh0c-21).

[**L’alimentation de la Raspberry Pi 3**](https://www.amazon.fr/gp/product/B01566WOAG/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01566WOAG&linkCode=as2&tag=hgh0c-21)

[La Raspberry Pi 3 a besoin d’une alimentation USB.
![Image](http://nsa37.casimages.com/img/2017/01/21/170121062517249292.jpg)]
(https://www.amazon.fr/gp/product/B01566WOAG/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01566WOAG&linkCode=as2&tag=hgh0c-21)

Les caractéristiques de [cette  alimentation](https://www.amazon.fr/gp/product/B01566WOAG/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01566WOAG&linkCode=as2&tag=hgh0c-21) sont : 5 Volts et 2.5 A minimum.

[**Une carte Micro SD**](https://www.amazon.fr/gp/product/B01HU3Q792/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01HU3Q792&linkCode=as2&tag=hgh0c-21)


Contrairement à l’alimentation, cela ne change pas de la Raspberry Pi 2. La carte SD ou Micro SD est néanmoins indispensable pour utiliser une Raspberry Pi. Elle va remplacer le disque dur et sans elle, vous ne pourriez même pas faire tourner le plus léger des système d’exploitation sur votre Raspberry Pi.

Veillez à prendre une  [carte de qualité](https://www.amazon.fr/gp/product/B01HU3Q792/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01HU3Q792&linkCode=as2&tag=hgh0c-21) en raison du grand nombre d’écritures et de lectures qui seront faîtes par la RP.

En ce qui concerne la taille, pour une utilisation standard, nous vous conseillons une carte de 32 Gb.

[![Carte Micro SD - 32 Gb](http://nsa37.casimages.com/img/2017/01/21/170121063643687991.jpg)](https://www.amazon.fr/gp/product/B01HU3Q792/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01HU3Q792&linkCode=as2&tag=hgh0c-21)

[**Un boîtier pour votre Raspberry Pi 3**](https://www.amazon.fr/gp/product/B010180JMO/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B010180JMO&linkCode=as2&tag=hgh0c-21)

Le boîtier n’est pas un accessoire indispensable pour la Raspberry Pi 3 mais il est fortement conseillé d’en avoir un pour pouvoir la protéger.

Si vous ne l’achetez pas en kit, la Raspberry Pi 3 est livrée comme une carte mère et elle est donc très vulnérables à la poussières ou aux chocs qui pourraient endommager les composants. Un boîtier, en plus de la rendre plus esthétiques, vous permettra d’éviter cela.

Tous les boitiers de la Raspberry Pi 2 sont compatibles avec la Raspberry Pi 3, vous n’avez donc aucun soucis à vous faire à ce niveau là.

Je vous conseil [le boîtier officiel de la Raspberry Pi Foundation](https://www.amazon.fr/gp/product/B010180JMO/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B010180JMO&linkCode=as2&tag=hgh0c-21) mais rien ne vous empêche d’en prendre un autre, tant qu’il vous plaît.

[![boitiers de la Raspberry Pi 2 et 3](http://nsa38.casimages.com/img/2017/01/21/170121064340139651.jpg)](https://www.amazon.fr/gp/product/B010180JMO/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B010180JMO&linkCode=as2&tag=hgh0c-21)



## Mot de passe par défaut. 

Le mot de passe par défaut de Raspbian Tor Onion Router pour le compte pi et la Wi-Fi est "rasberry".

## Installation 

Branchement de vos périphériques avec votre Raspberry Pi

1.Insérez votre carte SD dans le connecteur Raspberry Pi dédié
2.Branchez le câble ethernet à la box de votre fournisseur d’accès à internet (FAI)
3.Connectez-vous aux réseau Wi-Fi Wireless-Pi
4.Vous êtes Anonyme ! ;) 

## Se connecter à son Raspberry Pi 3 en SSH

Vous pouvez prendre le contrôle de votre Raspberry depuis votre ordinateur grâce au protocole SSH. Entrez la commande suivante, l'adresse IP Wi-Fi du Raspberry PI est 192.168.10.1. Le mot de passe du Wi-Fi raspberry. 

```
ssh pi@192.168.10.1

```

Lors de la première tentative de connexion, un message d’avertissement peut apparaître, indiquant que la vérification d’identité de la machine n’est pas possible. Validez, vous atterrirez alors sur une fenêtre requérant votre mot de passe utilisateur sur la Rasbperry Pi. Renseignez-le (par défaut : « rapsberry »). Un nouveau message devrait alors vous indiquer que la connexion est bien établie entre vos 2 appareils.

**Procédure sur Windows**

Vous aurez ici besoin du programme PuTTY. Il s’agit d’une interface client qui gère les communications SSH sur le système d’exploitation Windows. Téléchargez-le, installez-le, puis lancez-le.

Dans la catégorie « Session » de départ, entrez dans le champs « Host name » l’adresse IP de votre Raspberry Pi. Assurez-vous que le type de connexion pré-choisi est bien « SSH », cliquez sur « Open » puis lancez la connexion.

Comme sur mac, un message d’avertissement apparaît la première fois. Renseignez les identifiants utilisateur: « pi », « raspberry ».

Félicitations, vous venez donc de vous connecter à votre micro-ordinateur avec votre ordinateur hôte !



## Connecter votre Raspberry Pi 3 à la Wi-Fi de votre BOX


Démarrer votre Raspberry Pi 3 avant de brancher votre clé USB.  Connectez-vous à votre Raspberry Pi 3.  Il faudra d’abord éditer le fichier wpa_supplicant.conf. Il faut ensuite donner les informations concernant votre box. Configurez le nom de votre box et insérez le mot de passe. Au final, vous devez avoir quelque chose du genre
```
network={
ssid=”<nomDeLaBox>”
psk=”<cléDeSécurité>”
key_mgmt=WPA-PSK
}
```


En cas de soucis, vous pouvez toujours poser vos questions auxquelles nous serons ravis de répondre.
