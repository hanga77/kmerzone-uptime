# kmerzone-uptime

Surveillance externe de disponibilité de [kmerzone.com](https://kmerzone.com), via GitHub Actions toutes les 5 minutes.

- Alerte Telegram quand le site devient injoignable, puis quand il revient.
- Le workflow échoue tant que le site est hors ligne : GitHub envoie alors un email au propriétaire du dépôt.

Ce dépôt ne contient que le workflow : aucun code ni donnée de l'application.
