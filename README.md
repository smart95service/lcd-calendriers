# lcd-calendriers

Calendriers publiés par l'outil Pilotage LCD, un fichier `.ics` par logement.

Chaque fichier contient les réservations directes et les blocages saisis dans l'outil, pour que Airbnb, Booking, Abritel et le site Hostaya bloquent ces dates. On y trouve seulement des dates : ni nom de logement, ni voyageur, ni montant. Le nom de chaque fichier est un jeton aléatoire.

Les fichiers sont mis à jour automatiquement, une fois par heure. Ne les modifiez pas à la main : la mise à jour suivante écraserait vos changements.

Le lien à coller dans l'import de calendrier d'une plateforme se copie depuis la fiche du logement dans l'outil. Il a cette forme :

```
https://raw.githubusercontent.com/smart95service/lcd-calendriers/main/<jeton>.ics
```

Ce dépôt est public : n'importe qui peut voir quelles dates sont occupées, mais pas à quel logement elles correspondent.
