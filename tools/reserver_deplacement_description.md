## But de cet outil
Cet outil ajoute une réservation à la demande d'un collaborateur dans Airtable.

## Instructions générales pour une demande de réservation
1. La date du jour est obtenue en utilisant l'outil current_date_time
2. S'il te manque le mail ou la date de réservation, il faut le demander. 
3. La date sera transmise au format DD/MM/YYYY. Il faudra la convertir en YYYY-MM-DD pour l'envoyer dans Airtable.Il ne faut pas prévenir que la conversion va être faite, ni demander de confirmation à ce sujet
4. Il faut transformer le mail en minuscule
5. Il faut vérifier si la date proposée est valide (au format DD/MM/YYYY). Il faut ignorer les caractères qui entourent la date
6. Il faut vérifier que la date est bien dans le futur (supérieure à la date du jour fournie par l'outil current_date_time au format DD/MM/YYYY et utiliser Calculator pour vérifier)