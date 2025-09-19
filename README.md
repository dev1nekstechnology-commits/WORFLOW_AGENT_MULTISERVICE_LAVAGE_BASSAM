à l'avenir on ne parlera plus de bonus, de point ou de pourceante
les reductions sont appliquer manuellement par le gestionnaire uniquement sur le prix d'entretien du véhicule du client au 10 ème passage 

# APPLICATION DU PERSONNELLE A  l'ACCUEIL

- C'est le personnelle qui fait l'enregistrement des clients qui vienne d'arriver
- le personnelle à l'accueil du client à une tablette il a deux option le bouton
    je suis deja client
    premiere visite

- si le client est déjà un client c'est à dire à déjà un ID client, ou déjà un compte peut être avec l'application le personnelle clique sur 'je suis deja client'

- une page avec un champs de saisir ou le personnelle saisir soit l'ID client de ce client ou l'immatriculation du véhicule (il peut arriver que le client n'a pas de véhciule ou n'est pas venu pour entretien de son véhicule) (la requête fouille dans les deux tables et faire le retour ) 

- Affiche le profile de client
    nom complète
    ID client
    date de dernière visite 
    le nbre de foie de visite (pour pouvoir notifié le gestionnaire d'appliquer une rediction au 10 ème passage)
    le level de fidélité du client 
    la liste des véhicule de ce client (modèle , plate immatriculation)
    phrase du nbre restant pour avoir une reduction

- le personnelle clique sur suivant la liste des 4 catégorie s'afffiche, le personnelle choisir la categorie de service pour lequel le client est venue puis sectionne tous les service que le client  veut et peut aller dans les autres categorie de service pour ajouté d'autres services au panier 

- une foie la selection terminé le recap s'affiche avec le total a payer quand le personnelle clique sur terminer cela declenche plusieurs evernement tel que

    le client est notifié soit par sms, whatsapp, email, notification push si l'application installer

    la notification du gestionnaire de la facture et le nombre de visite (et indiquer d'appliquer une reduction à cette facture si c'est le 10 ème passage du client sur le prix d'entretien du véhicule , si ce n'est pas de véhicule pas de reduction)

    les tablette dans les autres services dont le client à selectionner leur service sont  notifiés du service demander par le client afin de ce preparer a le recevoir

    si le client est venue pour l'entretien de son véhciule il s'affiche sur les tv, il peut voir la progression aussi dans l'application 

- le client prend place ou va dans le autre pour profiter et quand il commande une nouvelle chose le personnelle dans ce service commande peut modifier la facture et ajoutant cette commande et calcul auto du total instantanement client est notifié de la mise à jour de sa facture pour ce faire 

    le personne peut cliquer directement sur la facture du client dans la liste des client facture sur sa tablette ou

    faire une recherche soit en saisissant  l'ID client ou l'immatriculation de la voiture

# CAS OU C'EST LA PREMIERE VISITE DU CLIENT
- le personnelle clique sur le bouton "première viste"
- il renseigne 
    le nom complète (facultatif)
    le numero de téléphone (de préférence whatsapp) ogligatoire
    l'Immatriculation du véhicule, le modèle (Factultatif)
    email (facultatif)
    clique sur creer le compte client

- le système génère un ID client et un mdp automatiquement qu'on peut envoyer au client avec soit le bouton partager par
    sms
    email
    whatsapp
    celon les données fournir par le client
    ce qui va lui servir de se connecter s'il deccide d'installer l'application 
    et aussi permettre au personne de l'identifier par prochaine foie qu'il vient

- le personnelle clique sur continuer le même proccessus que quand il est deja client continue

- à la fin du service et de la consommation du client, le client doit passer au payement de sa facture (s'il est venue pour l'entretien de son véhciule, avant qu'on lui remet ses clé ) pour cela il y'a deux option

    soit payer en espèce à la caisse (gestionnaire), le gestionnaire à la caisse clique sur la facture pour voir les details et le total de sa facture ou peut faire une recherche en saisissant soit l'ID_client du client ou l'immatriculation du véhcule au cas ou il aurait une long liste de client, 
    la facture apparait (applique une reduction s'il faut) avec le total, le client remet la somme à payer au gestionnaire, le gestionnaire saisir le montant et calcul  auto de la monnaie à rendre et génère le reçu de payement

    soit 

    le client va directement au kiosque pour payer numerique par mobile money ou carte bancaire, arriver a kiosque il clique sur commencer 

    la page apparait pour qu'il s'identifie soit par 
    qr code qu'il va scanner avec l'application mobile (s'il la installer) ou saisi l'ID_client et le mpd qu'on lui avait fournir

    ou 

    saisir l'immatriculation du véhicule ou l'id_client

    dans les deux cas (application ou recherche immatriculation, id_clienbt) s'il y'a une facture en cours cette facture s'affiche, avec la reduction si appliquer par le gestionnaire avec la liste des moyens de payement si le total lui convient alors chosir le moyen de payement qui lui plait et comme les mobile money actu ont tous des application permettre de payer il peut ouvrir l'application et scanner le qrcode pour payer ou faire la transaction manuellement comme d'ab et quand le système detecte le payement  automatiquement l'impression du reçu se lance et quand terminer retour automatiquement à l'accueil avec destruction de cette session du client ce qui declenche 

        la notif du gestionnaire à l'accueil du payement effetcuer donc on peut lui remettre les clés de son véhicule

        le client lui même est notifié soit par sms, whatsapp,email, push
        la suppression du véhicule dans la liste sur les ecrans de  Tv

# APPLICATION DU GESTIONNAIRE - CAISSE POUR ESPECE

- dans l'application du gestionnaire il peut

    . permettre au client de payer en espèce
    . changer le code couleur en fonction des état d'avancer du traitement duc véhicule des client (au depart rouge ENREGISTREMENT, ornage en traitement EMBARQUEMENT, vert pour termniné DEPART) cela change sur l'affichage sur les écrans et notif le client dans l'appli du client
    . appliquer des reduction manuelle à la facture d'un client sur le prix d'entretien du véhicule uniquement
    . modifier, supprimer, ajouter le véhicule lié à un client (au cas ou le client n'utilsie plus ce véhicule ou pour une autre raison)
    . ajouter des commandes à la facture du client
    . voir les states
    . ajouter des services aux catégories de services avec les details tel que les prix
    . modifer les prix des services

    plus important faire des notif broadcast soit par push , sms , whatsapp ou email (d'un evernement, ...)

- pour l'affichage de  l'eatt d'avancer des  véhicule sur les ecrans avec  couleur d

    *une long  liste de tous les véhicules de la journée avec leur statut*
    *l'affichage l'Immatriculation du véhicule + ID_client en grand caractère sur une icone de voiture qui avance sur ligne et sur la ligne il y'a 3 point , le point de depart appelé ENREGISTREMENT EN ROUGE, 2ème EMBARQUEMENT ORANGE (moment de l'entretien) , 3ème DEPART EN VERT*

    *au depart la ligne est fine jusqu'au bout et quand l'icone et les info avance la ligne en arrière devient large au fu et à mesure jusqu'à la fin*

    *pour la liste des véhicules sur les ecrans  masqué les véhicule la liste de ceux qui ont terminé leur services  automatiquement après 60 secondes après avoir été passé au vert*

# POUR L'APPLICATION MOBILE 

- première page logo, chargement
- omboarding (3 page de presentation soit presentant des videos ou images des services ou fonctionnalité de l'application)
- page de connexion avec champs (ID_client + mdp)
page d'inscription (nom complète (facultatif) telephone (ogligatoire) prefference whatsapp + email (facultatif)+ mdp ou laissé l'appli générer automatiquement)
- page otp pour saisir le code reçu par sms ou whatsapp ou email 
- page de profile avec info complète , icone photo qu'on peut ajouter une photo , champs vide plaque immatriculation , modèle véhicule , nbre de visite 
- page d'accuiel bouton scanner qr (pour s'identifier au kiosque), bouton reserver (reserver avance d'un service ), bouton historique (pour voir l'historique ses passages etautre), menu (voir les categorie de services), icone de notification pour voir ces notification recu,
- qu'il est la possibilité de prendre rendez-vous , sur le kiosque


# PARCOUR PERSONNELLE D'ACCUEIL DU CLIENT 
    https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/KIOSQUE-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=157-143&t=EYejakek2aNUEwSE-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=157%3A143&show-proto-sidebar=1

# PARCOUR PERSONNELLE DES AUTRES SERVICES (Ajouté des services à la facture)
    https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/KIOSQUE-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=80-61&t=AuZgs3pArSFksQ0I-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=80%3A61&show-proto-sidebar=1

# PARCOUR GESTIONNAIRE CODE COULEUR- CAISSE PAYEMENT ESPECE 
    https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/KIOSQUE-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=28-364&t=GJv6YFUyWMgJqD4x-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=28%3A364&show-proto-sidebar=1

# APPLICATION MOBILE CLIENT
    https://www.figma.com/proto/o7YXAXt7yR1S8XQrNb9GQ9/SESSION-3-APPLICATION-MOBILE?node-id=1-2&t=WNWbEHXkAgq3y8vC-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2

# PARCOUR CLIENT AU KIOSQUE POUR LE PAYEMENT 
    https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/KIOSQUE-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=271-138&t=GtceVnjWGSpx4jjQ-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=271%3A138&show-proto-sidebar=1
