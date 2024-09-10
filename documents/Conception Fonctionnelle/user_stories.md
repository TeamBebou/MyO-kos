# User Stories

$1.$ 

**En tant que** propriétaire d'une location,
**je veux** pouvoir ajouter / modifier / supprimer une propriété 
**afin de** maintenir les détails de mes locations à jour et précis.

### Critères d'acceptation

1. Le propriétaire peut ajouter une nouvelle propriété avec des détails comme l'adresse, le nombre de chambres, le prix, etc.
2. Le propriétaire peut modifier les informations existantes d'une propriété.
3. Le propriétaire peut supprimer une propriété de la liste.

### Ressources:
* [CRUD](https://developer.mozilla.org/fr/docs/Glossary/CRUD)

$2.$

**En tant que** propriétaire d'une location,
**je veux** pouvoir voir toutes les réservations actuelles et futures pour mes propriétés
**afin de** gérer efficacement les disponibilités et éviter les double réservations.

### Critères d'acceptation

1. Le propriétaire peut consulter une liste des réservations en cours et futures pour chaque propriété.
2. La liste affiche les détails tels que les dates de réservation, le nom du locataire, et le statut de la réservation.
3. Le propriétaire peut filtrer les réservations par date ou par propriété.

### Ressources:
* [Idées de design Dashboard](https://dribbble.com/search/dashboard)

$3.$

**En tant que** propriétaire ou locataire,
**je veux** pouvoir envoyer et recevoir des messages directement via l'application
**afin de** résoudre rapidement tout problème ou répondre à leurs questions.

### Critères d'acceptation

1. Le propriétaire peut envoyer des messages aux locataires et voir leurs réponses (vise versa).
2. Les messages sont stockés dans une boîte de réception accessible à tout moment.
3. Les notifications sont envoyées pour les nouveaux messages.

### Ressources:
* [Socket IO](https://socket.io/)
* [Idées de design Messagerie](https://dribbble.com/tags/messagerie)

$4.$

**En tant que** locataire,
**je veux** pouvoir laisser un avis et une évaluation à un propriétaire et sa location
**afin de** partager son expérience et ainsi améliorer la confiance envers un propriétaire et son bien.

### Critères d'acceptation

1. Le locataire peut laisser un avis après avoir terminé son bail.
2. Le propriétaire peut consulter les avis et évaluations laissés par les locataires.
3. Les avis incluent des détails comme la note, le commentaire, et la date.
4. Le propriétaire peut répondre aux avis.

$5.$

**En tant que** propriétaire,
**je veux** accéder à des rapports détaillés sur les performances de mes propriétés, comme le taux d'occupation et les revenus générés,
**afin de** prendre des décisions éclairées pour optimiser mes revenus locatifs.

### Critères d'acceptation

1. Le propriétaire peut générer des rapports sur les performances des propriétés.
2. Les rapports incluent des statistiques comme le taux d'occupation, les revenus totaux, et les tendances saisonnières.
3. Le propriétaire peut exporter les rapports en formats courants comme PDF ou Excel.

### Ressources :
* [Graphiques](https://ui.shadcn.com/charts)