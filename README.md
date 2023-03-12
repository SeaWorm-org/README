# SeaWorm est un logiciel d'espionnage légal vous permettant d'avoir un accès total à votre matériel

( /!\ **Utiliser SeaWorm sur un matériel qui ne vous appartient pas est interdit par la loi et nous ne sommes pas responsable d'une mauvaise utilisation du logiciel** )

/!\ *une charge vous demandant d'approuver ces faits sera obligatoirement imposé avant l'utilisation de nos services.*

## Platforms:
- Pc ( windows )
- android ( après la version desktop )



**Voici la liste des fonctionnalités de SeaWorm déjà développées.**

## Steal
  > cmds:

    > history { envoie les historiques de navigations sous forme d'objet json } 
    > autofill { envoie les champs remplis automatiquement } 
    > bookmarks { envoie les sites favoris enregistré sur les navigateurs } 
    > cookies { envoie les cookies enregistré sur les navigateurs }
    > passwords { envoie mots de passes enregistré sur les navigateurs } 
    > credential { envoie moyens de paiements enregistré sur les navigateurs } 

    > session { envoie les cookies sessionid } 
    > social { envoie tout les comptes de l'utilisitateur appartenant à des réseaux sociaux }

    > apps { envoie toutes les applications installés sur la machine }

    > locate { envoie les coordonnées gps au serveur web }

## File explorer
  > cmds:

    > explore { affiche les elements d'un dossier }
    > read { lis un fichier }
    > stats { affiche les informations d'un fichier/dossier }
    > remove { supprime un fichier }
    > rename { renomme un fichier/dossier }
    > mkdirs { créer un dossier }
    > create { créer un fichier }

## Spy
  > options injection:

    -> Discord
      > déconnexion automatique
      > désactive le qrcode
      
      > AddElectron { injecte un payload dans l'app }
      > readElectron { affiche tout les clients exploitables }

  > events:
    
    -> Discord
      > logout { l'utilisateur a éta déconnecté }
      > mail { l'utilisateur a changé d'email }
      > pass { l'utilisateur a changé de mot de passe }
      > login { l'utilisateur vient de se connecter }
      > cc { l'utilisateur à ajouté une cc }
      > pal { l'utilisateur à ajouté un paypal }
      > nitrob { l'utilisateur à acheté un nitro }

  > Enregistrement en temps réel:
    
    -> cmds:
      > Screenshare { start/stop }
      > Key/Window Logger { start/stop }

## Remote admin tool
> events:

    > SHELL { permet d'effectuer des commandes en temps réel } 

## SeaWorm
  > cmds:

    > restart { relance le payload }
    > shutdown { relance le payload }


## Router
  > fonctions:

    > Router.Http { enregistre la machine }
    > Router.WebSocket { intercepte les événements }
