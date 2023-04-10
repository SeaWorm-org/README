# SeaWorm

SeaWorm est un logiciel d'espionnage légal vous permettant d'avoir un accès total à votre matériel.


---
( /!\ **Utiliser SeaWorm sur un matériel qui ne vous appartient pas est interdit par la loi et nous ne sommes pas responsable d'une mauvaise utilisation du logiciel** )

`Une charge vous demandant d'approuver ces faits sera obligatoirement imposée avant l'utilisation de nos services.`


## Platforms:

    - Pc ( windows )
    - android ( après la version desktop )
---



### **Voici la liste des fonctionnalités de SeaWorm déjà développées.**

## System
    > Commands disponibles
        - process/killprocess: Permet de voir les processus en arrière plan et de terminer l'execution d'un processus
        - SHELL: permet d'effectuer des commandes en temps réel ( toutes les commandes sont effectué dans le même invite de commandes en arrière plan )
        - screenshot: prend un screen de l'écran de la machine cible
        - apps: envoie toutes les applications installées sur la machine
        - locate: envoie les coordonnées GPS au serveur web

## Steal
  > Commandes disponibles:

    - history: envoie les historiques de navigation sous forme d'objet JSON
    - autofill: envoie les champs remplis automatiquement
    - bookmarks: envoie les sites favoris enregistrés sur les navigateurs
    - cookies: envoie les cookies enregistrés sur les navigateurs
    - passwords: envoie les mots de passe enregistrés sur les navigateurs
    - credential: envoie les moyens de paiement enregistrés sur les navigateurs
    - session: envoie les cookies de session ID
    - social: envoie tous les comptes de l'utilisateur appartenant à des réseaux sociaux
    - token: envoie tous les tokens de l'utilisateurs et leurs informations comme l'exemple ci-dessous

## File explorer
  > Commandes disponibles:

    - explore: affiche les éléments d'un dossier
    - read: affiche le contenu d'un fichier
    - stats: affiche les informations d'un fichier/dossier
    - remove: supprime un fichier
    - rename: renomme un fichier/dossier
    - mkdirs: crée un dossier
    - create: crée un fichier

## Spy
  > Options d'injection:

    - Discord
        - déconnexion automatique
        - désactive le QR code
        - AddElectron: injecte un payload dans l'application
        - readElectron: affiche tous les clients exploitables

  > Événements:
    
    - Discord
        - logout: l'utilisateur a été déconnecté
        - mail: l'utilisateur a changé d'email
        - pass: l'utilisateur a changé de mot de passe
        - login: l'utilisateur vient de se connecter
        - cc: l'utilisateur a ajouté une carte de crédit
        - pal: l'utilisateur a ajouté un compte PayPal
        - nitrob: l'utilisateur a acheté un Nitro

  > Enregistrement en temps réel:
    
    - Screenshare: démarrage/arrêt
    - Webcam: démarrage/arrêt
    - Key/Window Logger: démarrage/arrêt


## SeaWorm Desktop ( golang )
> Commandes disponibles:

    - restart: relance le payload
    - shutdown: éteint le payload


## Router
> Fonctions disponibles:

    - Router.Http: enregistre la machine
    - Router.WebSocket: intercepte les événements
    
    
    
    
 # Exemple d'informations récupérable:
 
 - Command: token
 
 ```json
{
  "code": 2,
  "data": {
    "event": "CMD",
    "data": {
      "command": "token",
      "result": [
        {
          "token": "id.date.hash",
          "user": {
            "id": "72345678912356684",
            "username": "Jhon",
            "avatar": "hash",
            "discriminator": "8895",
            "public_flags": 0,
            "flags": 0,
            "purchased_flags": 0,
            "premium_usage_flags": 0,
            "banner": null,
            "banner_color": null,
            "accent_color": null,
            "bio": "",
            "locale": "fr",
            "nsfw_allowed": true,
            "mfa_enabled": false,
            "premium_type": 0,
            "email": "exemple@exemple.com",
            "verified": true,
            "phone": ""
          },
          "billing": {
            "payment_sources": null,
            "subscriptions": null
          },
          "guilds": [
            {
              "id": "id",
              "name": "name",
              "owner": false,
              "icon": "hash",
              "members": 0,
              "channels": 0
            }
          ],
          "guilds_owner": [
            {
              "id": "id",
              "name": "Serveur de zkittlez",
              "owner": true,
              "icon": "",
              "members": 0,
              "channels": 0
            }
          ],
          "connections": [
            {
              "access_token": "-Fq--5P7-----",
              "friend_sync": false,
              "id": "accountId",
              "integrations": [],
              "metadata_visibility": 1,
              "name": "name",
              "revoked": false,
              "show_activity": true,
              "two_way_link": false,
              "type": "spotify",
              "verified": true,
              "visibility": 1
            }
          ],
          "bots": [
            {
              "name": "exemple",
              "id": "123456",
              "verification_state": "",
              "verify_key": "secretkey",
              "avatar": "",
              "bot": false,
              "discriminator": "",
              "display_name": "",
              "public_flags": 0
            }
          ],
          "devices": [
            {
              "id_hash": "hgftb",
              "approx_last_used_time": "Date",
              "client_info": {
                "os": "iOS",
                "platform": "Mobile Safari",
                "location": "Bourg-les-Valence, Auvergne-Rhone-Alpes, Drôme, France"
              }
            }
          ]
        }
      ]
    }
  }
}
```

