# Réception d'une nouvelle demande de devis

![new request](images/pro_quote/new_request.png)

### Actions
  1. Se connecter à Forest Admin
  - Se rendre sur la page de la demande

    `Data(1) > Pro Quotes(2)`

    ![quote index](images/pro_quote/quote_index.png)

  - cliquer sur une demande de devis (Pro Quote)

  - s'assurer d'être sur l'onglet 'détails'

  - cliquer sur 'Actions' > 'Create Draft Reservation'

  ![quote show](images/pro_quote/quote_show.png)

  - Se rendre sur 'Pro Reservations', le devis créé devrait se trouver en haut de la liste avec le status 'Draft'

  ![reservations index](images/pro_quote/reservations_index.png)

  - éditer la proposition et/ou ajouter des services

  - Une fois la proposition construite, cliquer sur 'Actions' > 'Propose Réservation'

  _Cela a pour effet de passer la proposition en status 'proposed' + d'envoyer un mail au client._

  __Attention : Ne pas éditer le status de la réservation, car le mail de notification ne partirais pas.__

  ![propose reservation](images/pro_quote/propose_reservation.png)

### Fin du premier cycle
Le client a reçu un mail avec sa proposition


# Réception d'une demande de modification

 ![modification request](images/pro_quote/modification_request.png)

### Actions

 1. Se rendre à nouveau dans l'espace Admin sur 'Pro Reservations'
La réservation a maintenant le status `modification_requested`

  ![modification requested](images/pro_quote/modification_requested.png)       

  __Attention il ne faut pas éditer cette reservation mais en créer une autre avec l'action 'Duplicate Reservation as Draft'__

  ![duplicate as draft](images/pro_quote/duplicate_as_draft.png)

 - Retourner sur l'index des propositions ('Pro Reservations')

  la nouvelle proposition apparait alors au dessus avec à nouveau le status 'Draft'

  ![new draft](images/pro_quote/new_draft.png)

Le process reprend alors à l'etape 2?, éditer la proposition jusqu'à satisfaction ensuite cliquer sur 'Actions' > 'Propose Réservation'
