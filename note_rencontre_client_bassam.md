- C'est le personnelle qui fait l'enregistrement des clients 
- on n'identifie pas le client pas contre le véhicule donc pas besoin des infos du clients
- donc on lie un véhicule à une personne par consequant une personne peut avoir plusieurs véhicules
- quand un client arrive on saisir le l'immatriculation du véhicule + le numero de telephone (le numero de telephone est facultatif mais s'il saisir le système fait resortir ces infos sur lui s'il exist déjà tel que son nbre de foie de passé , son nom complète si fournir, le nbre de véhicule; s'il le numéro n'existe pas on enregistre dans la bd et on notifie ce numb de bienvenue avec le lien de l'application mobile à télécharger, recap et status d'acancé du véhiculee)

- quand une personne arrive avec son véhicule le personne saisir l'immatriculation sur le KIOSQUE et fait sortir un ticket direct avec un code 
    (ce code va lui servir de voir sa position dans la fil d'attente, permmettre au gestionnaire à la caisse d'ajouter des commande à sa facture, ce code va lui permettre , à la fin du service de saisir sur le kiosque et faire resortir sa facture et les moyens de payement puis payer et imprimé son reçu )
- pour des personnes qui viennent spécialement pour autre services que le lavage , le personnelle l'enregistre 

    (choix de servce de départ et un ID est généré automatiquement et  imprimé , instantanement le gestionnaire à la caisse reçois une notification et aussi le personnel dans le service dédié, le gestionnaire pourra ajouté d'autre service à la facture , modifié les tarifs, etc)

- quand le service est terminé le client est notifié et peut aller soit 
    *à la caisse pour payer en espèce donc le gestionnaire à la caisse saisir le code | ID du ticket de départ puis la facture apparaît et le total puis proccède au payement en espèce*

    *s'il deccide de payer par mobile money il se rend  au kiosque avec son ticket de depart avec l'ID saisir l'ID sur le kiosque et la facture apparaîy ainsi que le total , s'il y'a réduction, le nbe de foie qu'il vient (déccidé et applique à la facture par le gestionnaire à la caisse sur cette facture ), choisir le moyen de payement souhaité, paie, reçu généré et imprimé, puis  remise des clés du véhicule*

- les reductions, bonus , gratuité se font uniquement en argent et que par la catégorie de services de lavage peut importe le type de service, appliqué par le gestionnaire à la caisse à la facture après que le système lui notifié que c'est le 10 ème passage de ce client pas de point, pourcentage ou autre


- pour le système de code couleur de suivie de l'avancé du véhicule du client 
    *on simplifie au max , pas de session pour attente , en cours , terminé, mais plutot une long  liste de tous les véhicules de la journée avec leur statut*
    *l'affichage l'Immatriculation du véhicule + ID de son ticket en grand caractère devant une icone de voiture qui avance sur ligne et sur la ligne il y'a 3 point , le point de depart appelé ENREGISTREMENT EN ROUGE, 2ème EMBARQUEMENT ORANGE (moment de l'entretien) , 3ème DEPART EN VERT*

    *au depart la ligne est fine et quand l'icone avance la ligne en arrière devient gros au fu et à mesure jusqu'à la fin*
    *pour la fil d'attente permettre au gestionnaire à la caisse de masqué des élément dans le but de reduit la liste de ceux qui ont finir leur services ou masqué automatiquement après 60 secondes après avoir été passé au vert*

- qu'il est la possibilité de prendre rendez-vous , sur le kiosque
- développer un système d'envoi de sms broascast
- permettre de modifié le véhicule lié à une personne

- pour identifié un véhicule et le lié à un personne et permettre à notre système pour cela puis permettre au gestionnaire d'appliqué des réduction ou envoyer des sms broadcast, permettre à l'utilisateur de se connecter à l'application mobile on a besoin de collection certain donnée. je fais allusion à 
    
    1. L'immatriculation du véhicule
    2. le numéro de télephone (de préference whatsapp pour être notifié quand on fini de l'enregistré au kiosque , être notifié lors de l'avancé du véhicule, lorsqu'on ajout une commande à sa facture, recevoir des SMS)
    3.  un otp sur le numéro à chaque fois qu'il tente de se connecter à l'application (il saisir son numéro de téléphone , reçois un otp le saisir si ok alors connecter)


- dans l'application il peut voir la liste de ces véhicule qui lui sont lié 
- l'utilisateur peut faire la demande de modifié la liste des véhicules ou supprimé
- mes ces modifs sont validés et executé pas le gestionnaire à la caisse
- on veut un chronomètre qui se lance dès qu'on commence à enregistré un véhicule au kiosque et la date complète jusqu'au seconde seront mentionné sur le ticket puis le temps de traitement
- la date complète de la proccedure de payement et le temps de traitement pareil à la caisse lors de la paie en espèce
- le temps de l'entretien des véhicule
- le temps des autres services 
- quand on fait un reservation dans l'application on notifie le personnel dans la catégorie conserné

- pas de Identification Client