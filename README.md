# Workflow Complet du Système Bassam - Version Actualisée
## Modifications Post-Rencontre Client du 09/10/2025

---

## CHANGEMENTS PRINCIPAUX INTÉGRÉS

###  Nouvelles Fonctionnalités Demandées :
- **Enregistrement multiple** : QR Code + Immatriculation + ID unique
- **Kiosque dédié uniquement aux paiements**
- **Personnel enregistre manuellement les nouveaux clients**
- **Gestionnaire peut modifier immatriculations et IDs clients**
- **Écran de suivi affiche uniquement les immatriculations complètes**
- **Application mobile inchangée**

---

## EXEMPLE CONCRET : M. Kouassi Yao avec sa Toyota Camry CI 1234 AB 56

---

## PHASE 1 : ARRIVÉE ET ACCUEIL PERSONNALISÉ

### Heure : 09h15 - Mardi 15 octobre 2025

**M. Kouassi Yao** arrive au Lavage International de Bassam avec sa **Toyota Camry - CI 1234 AB 56**

###  NOUVEAU : Enregistrement par le Personnel
**Le personnel à l'accueil s'occupe directement de l'enregistrement**

```
INTERFACE PERSONNEL - ENREGISTREMENT CLIENT
┌─────────────────────────────────────────────┐
│     ENREGISTREMENT NOUVEAU CLIENT           │
│                                             │
│  MÉTHODE D'IDENTIFICATION :                │
│                                             │
│  [  SCANNER QR CODE ]                    │
│                                             │
│  [  SAISIR IMMATRICULATION ]              │
│                                             │
│  [ SAISIR ID CLIENT ]                    │
│                                             │
└─────────────────────────────────────────────┘
```

**Le personnel choisit : "SAISIR ID CLIENT" car M. Kouassi est déjà client**

### Recherche Client Existant
```
RECHERCHE CLIENT EXISTANT
┌─────────────────────────────────────────────┐
│  ID Client : [ KY-2023-0456 ]              │
│                                             │
│  OU                                         │
│                                             │
│  Immatriculation : [ CI 1234 AB 56 ]       │
│                                             │
│  [ RECHERCHER ]                             │
└─────────────────────────────────────────────┘
```

### Profil Client Trouvé
```
 CLIENT TROUVÉ - KOUASSI YAO
═══════════════════════════════════════════════
ID Client : KY-2023-0456
Niveau Fidélité : ARGENT (12 450 points)
Téléphone : +225 07 45 67 89

VÉHICULES ENREGISTRÉS :
• Toyota Camry - CI 1234 AB 56  (Principal)
• Peugeot 208 - CI 5678 CD 90

Dernière visite : 28 septembre 2025
Total visites : 23

[ MODIFIER INFOS ] [ CRÉER NOUVELLE COMMANDE ]
```

---

## PHASE 2 : CRÉATION DE COMMANDE PAR LE PERSONNEL

### Sélection Services pour le Client
```
CRÉATION COMMANDE - KOUASSI YAO
┌─────────────────────────────────────────────┐
│  Véhicule : Toyota Camry - CI 1234 AB 56   │
│                                             │
│  CATÉGORIES DE SERVICES DISPONIBLES :      │
│                                             │
│  ✓ [ LAVAGE & ENTRETIEN ]                   │
│  □ [ BEAUTÉ & BIEN-ÊTRE ]                   │
│  ✓ [ RESTAURATION ]                         │
│  □ [ BOUTIQUE & VENTE ]                     │
│                                             │
└─────────────────────────────────────────────┘
```

### Sélection Services Lavage
```
SERVICES LAVAGE & ENTRETIEN
┌─────────────────────────────────────────────┐
│  ✓ Lavage Complet         8 500 FCFA       │
│  □ Lavage Extérieur       5 000 FCFA       │
│  □ Cirage Premium         7 500 FCFA       │
│  □ Pack Complet          15 000 FCFA       │
│                                             │
│  Services sélectionnés : 1                 │
│  Total partiel : 8 500 FCFA                │
└─────────────────────────────────────────────┘
```

### Sélection Services Restauration
```
SERVICES RESTAURATION
┌─────────────────────────────────────────────┐
│  ✓ Café Expresso          1 500 FCFA       │
│  □ Jus d'Orange           2 000 FCFA       │
│  □ Sandwich Club          4 500 FCFA       │
│                                             │
│  Total sélection : 2 services              │
│  TOTAL COMMANDE : 10 000 FCFA              │
└─────────────────────────────────────────────┘
```

### Récapitulatif et Application Réduction Fidélité
```
RÉCAPITULATIF COMMANDE - KOUASSI YAO
═══════════════════════════════════════════════
Véhicule : Toyota Camry - CI 1234 AB 56

SERVICES :
• Lavage Complet                    8 500 F
• Café Expresso                     1 500 F
                                   ─────────
SOUS-TOTAL                         10 000 F

FIDÉLITÉ ARGENT (Automatique) :
Réduction 5%                         -500 F
                                   ─────────
TOTAL À PAYER                       9 500 F

Points à gagner : +95 points
Durée estimée : 45-50 minutes

[ VALIDER COMMANDE ]
```

---

## PHASE 3 : GÉNÉRATION TICKET ET ID UNIQUE

### Ticket Généré Automatiquement
```
 TICKET DE SUIVI N° LIB-2025-1015-0023
═══════════════════════════════════════════════
LAVAGE INTERNATIONAL DE BASSAM
Date: 15/10/2025  Heure: 09h22

Client: KOUASSI YAO (Fidélité Argent)
ID Client: KY-2023-0456
Véhicule: CI 1234 AB 56 (Toyota Camry)

CODE DE PAIEMENT: 0023
(À conserver pour paiement au kiosque)

SERVICES COMMANDÉS:
• Lavage Complet                    8 500 F
• Café Expresso                     1 500 F
Réduction fidélité (5%)              -500 F
TOTAL: 9 500 FCFA

Durée estimée: 45-50 min
Fin prévue vers: 10h10

Position file d'attente: 3ème

═══════════════════════════════════════════════
POUR PAYER : Rendez-vous au kiosque
avec le CODE : 0023
WhatsApp: +225 74 76 40 385
```

---

## PHASE 4 : DASHBOARD GESTIONNAIRE - SUIVI EN TEMPS RÉEL

### Interface Gestionnaire Actualisée
```
🖥️ DASHBOARD GESTIONNAIRE - 09h22
═══════════════════════════════════════════════
 NOUVELLE COMMANDE CRÉÉE

ID Commande : LIB-2025-1015-0023
Client : KOUASSI YAO (KY-2023-0456)
Véhicule : CI 1234 AB 56 (Toyota Camry)
Total : 9 500 FCFA

STATUS ACTUEL : 🔴 ENREGISTRÉ

Services :
✓ Lavage Complet (45 min)
✓ Café Expresso

[ CHANGER STATUT ] [ MODIFIER IMMATRICULATION ]
[ MODIFIER ID CLIENT ] [ AJOUTER SERVICE ]
```

###  NOUVEAU : Fonctions Avancées Gestionnaire
```
OPTIONS GESTIONNAIRE AVANCÉES
┌─────────────────────────────────────────────┐
│  [ MODIFIER IMMATRICULATION ]               │
│    CI 1234 AB 56 → [ Nouvelle immat. ]     │
│                                             │
│  [ MODIFIER ID CLIENT ]                     │
│    KY-2023-0456 → [ Nouvel ID ]            │
│                                             │
│  [ AJOUTER SERVICE ]                        │
│  [ APPLIQUER RÉDUCTION MANUELLE ]          │
│  [ CHANGER STATUT VÉHICULE ]                │
└─────────────────────────────────────────────┘
```

---

## PHASE 5 : ÉCRAN DE SUIVI VISUEL ACTUALISÉ

###  NOUVEAU : Affichage Immatriculations Complètes
```
📺 ÉCRAN DE SUIVI - ZONE D'ATTENTE
═══════════════════════════════════════════════
        SUIVI DE VOS VÉHICULES

🔴 ENREGISTRÉ :
    CI 1234 AB 56     🚗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ (0%)
    [ENREGISTREMENT]           [EMBARQUEMENT]           [DÉPART]

🟠 EN COURS :
    CI 5678 CD 90     🚗████████━━━━━━━━━━━━━━━━━━━━━━━━━ (35%)
    [ENREGISTREMENT]           [EMBARQUEMENT]           [DÉPART]

🟢 TERMINÉ :
    CI 9012 EF 34     🚗████████████████████████████████ (100%)
    [ENREGISTREMENT]           [EMBARQUEMENT]           [DÉPART]
                                                         PRÊT

═══════════════════════════════════════════════════════
Il est maintenant 09h25 - Suivez l'avancement de votre véhicule
```

---

## PHASE 6 : PROGRESSION DU SERVICE

### 09h28 - Début du Lavage
**Le gestionnaire change le statut : ROUGE → ORANGE**

### Notification WhatsApp Automatique
```
 WHATSAPP - 09h28
───────────────────────────
 Lavage International Bassam

Bonjour M. Kouassi,

Votre véhicule CI 1234 AB 56 
(Toyota Camry) est maintenant 
en cours de traitement !

Status: 🟠 EN COURS
Temps restant: ~35 minutes
Fin prévue: 10h05

Code de paiement: 0023
(À garder pour le kiosque)

Suivi en temps réel disponible
```

### Mise à Jour Écran de Suivi
```
📺 ÉCRAN DE SUIVI ACTUALISÉ - 09h28
═══════════════════════════════════════════════
🟠 EN COURS :
    CI 1234 AB 56     🚗████████████━━━━━━━━━━━━━━━━━━━━━ (45%)
    [ENREGISTREMENT]           [EMBARQUEMENT]           [DÉPART]
                                      ↑
                               Traitement en cours
```

---

## PHASE 7 : AJOUT DE SERVICE EN COURS (Si demandé)

### 09h45 - Demande d'ajout service
**M. Kouassi demande un sandwich au personnel**

### Interface Gestionnaire - Ajout Service
```
MODIFICATION COMMANDE - KOUASSI YAO
═══════════════════════════════════════════════
Commande: LIB-2025-1015-0023
Véhicule: CI 1234 AB 56

FACTURATION ACTUELLE:
• Lavage Complet                    8 500 F
• Café Expresso                     1 500 F
Réduction (5%)                       -500 F
TOTAL ACTUEL                        9 500 F

AJOUTER SERVICE:
• Sandwich Club              [+]    4 500 F

NOUVEAU TOTAL:                     13 775 F
Points supplémentaires: +45

[ CONFIRMER AJOUT ] [ NOTIFIER CLIENT ]
```

---

## PHASE 8 : FIN DE SERVICE ET PRÉPARATION PAIEMENT

### 10h08 - Service Terminé
**Le gestionnaire change : ORANGE → VERT**

### Notification de Fin
```
 WHATSAPP - 10h08
───────────────────────────
 Lavage International Bassam

 Votre Toyota Camry est PRÊTE !

Véhicule: CI 1234 AB 56
Status: 🟢 TERMINÉ

 POUR PAYER :
Rendez-vous au KIOSQUE
avec votre CODE : 0023

Total à régler: 13 775 F

Merci de votre confiance !
```

### Écran de Suivi Final
```
📺 ÉCRAN DE SUIVI - 10h08
═══════════════════════════════════════════════
🟢 PRÊT POUR RÉCUPÉRATION :
    CI 1234 AB 56     🚗████████████████████████████████ 
    [ENREGISTREMENT]           [EMBARQUEMENT]           [DÉPART]
                                                          

 VÉHICULE PRÊT - RENDEZ-VOUS AU KIOSQUE 
    CODE PAIEMENT : 0023
```

---

## PHASE 9 : PAIEMENT AU KIOSQUE DÉDIÉ

###  NOUVEAU : Kiosque Uniquement pour Paiements

### 10h12 - M. Kouassi se rend au kiosque
```
 KIOSQUE DE PAIEMENT
┌─────────────────────────────────────────────┐
│        PAIEMENT DE VOTRE FACTURE            │
│                                             │
│     Saisissez votre CODE DE PAIEMENT :     │
│                                             │
│         [ _ _ _ _ ]                          │
│                                             │
│           [ VALIDER ]                       │
│                                             │
└─────────────────────────────────────────────┘
```

**M. Kouassi saisit : 0023**

### Affichage Facture
```
 FACTURE TROUVÉE - KOUASSI YAO
═══════════════════════════════════════════════
Véhicule: CI 1234 AB 56 (Toyota Camry)
Commande: LIB-2025-1015-0023

DÉTAIL SERVICES:
• Lavage Complet                    8 500 F
• Café Expresso                     1 500 F  
• Sandwich Club                     4 500 F
SOUS-TOTAL                         14 500 F
Réduction fidélité (5%)              -725 F
TOTAL À PAYER                      13 775 F

Points à gagner: +138 points

[ PROCÉDER AU PAIEMENT ]
```

### Sélection Moyen de Paiement
```
CHOISISSEZ VOTRE MOYEN DE PAIEMENT
┌─────────────┬─────────────┐
│   ORANGE    │     MTN     │
│    MONEY    │    MONEY    │
└─────────────┴─────────────┘
┌─────────────┬─────────────┐
│    WAVE     │   CARTE     │
│             │  BANCAIRE   │
└─────────────┴─────────────┘
┌─────────────┬─────────────┐
│   ESPÈCES   │ POINTS      │
│  (à la      │ FIDÉLITÉ    │
│   caisse)   │             │
└─────────────┴─────────────┘
```

**M. Kouassi choisit : ORANGE MONEY**

### Processus Paiement Orange Money
```
 PAIEMENT ORANGE MONEY
═══════════════════════════════════════════════
Montant: 13 775 FCFA

 OPTION 1: Scannez le QR Code
[QR CODE ORANGE MONEY]

 OPTION 2: Code USSD
Composez: *144*4*13775#
Puis suivez les instructions

Référence: LIB-2025-1015-0023

 EN ATTENTE DE VOTRE PAIEMENT...
```

### Confirmation Automatique
```
 PAIEMENT CONFIRMÉ !
═══════════════════════════════════════════════
Orange Money - 10h15
Montant: 13 775 FCFA
Réf Transaction: OM-2025-1015-0089

Votre reçu sera imprimé automatiquement

[ IMPRIMER REÇU ] [ NOUVEAU PAIEMENT ]
```

---

## PHASE 10 : REÇU FINAL ET CLÔTURE

### Reçu Imprimé Automatiquement
```
 REÇU OFFICIEL N° LIB-2025-1015-0023
═══════════════════════════════════════════════
LAVAGE INTERNATIONAL DE BASSAM
Route Internationale, Grand-Bassam
Tél: +225 27 21 30 25 50
Date: 15/10/2025  Heure: 10h15

Client: KOUASSI YAO
ID: KY-2023-0456 (Niveau Argent)
Véhicule: CI 1234 AB 56 (Toyota Camry)

SERVICES RENDUS:
Lavage Complet                      8 500 F
Café Expresso                       1 500 F  
Sandwich Club                       4 500 F
                                   ─────────
Sous-total                         14 500 F
Remise fidélité (5%)                 -725 F
                                   ─────────
TOTAL PAYÉ                         13 775 F

PAIEMENT:
Orange Money - 10h15               13 775 F
Réf: OM-2025-1015-0089

FIDÉLITÉ:
Points gagnés: +138
Nouveau total: 12 683 points
Statut: ARGENT
Prochain niveau (OR): 2 317 points restants

Durée service: 53 minutes
Enregistrement: 09h22
Fin service: 10h08
Paiement: 10h15

═══════════════════════════════════════════════
Merci pour votre confiance !
Prochain rdv suggéré: 05/11/2025

[QR CODE] - Évaluez notre service
Suivez-nous: @lavage_bassam
═══════════════════════════════════════════════
```

---

## RÉCAPITULATIF DES CHANGEMENTS INTÉGRÉS

###  Nouvelles Fonctionnalités Implémentées :

1. **Enregistrement Multiple** :
   - QR Code scanning 
   - Saisie immatriculation complète   
   - Saisie ID client unique 

2. **Kiosque Paiement Exclusif** :
   - Interface dédiée uniquement aux paiements 
   - Recherche par code de paiement 
   - Aucune autre fonction 

3. **Enregistrement Manuel Personnel** :
   - Interface personnel pour enregistrement 
   - Création commande par le staff 
   - Recherche client existant 

4. **Droits Gestionnaire Avancés** :
   - Modification immatriculations 
   - Modification IDs clients 
   - Gestion complète des commandes 

5. **Écran de Suivi Optimisé** :
   - Affichage immatriculations complètes 
   - Schéma visuel de progression 
   - Masquage automatique après 60s 

6. **Application Mobile** :
   - Inchangée selon demande client 
   - Fonctionnalités existantes conservées 

---

## CHRONOLOGIE COMPLÈTE ACTUALISÉE

| Heure | Action | Responsable | Interface |
|-------|--------|-------------|-----------|
| 09h15 | Arrivée client | M. Kouassi | - |
| 09h18 | Recherche client | Personnel | Interface Personnel |
| 09h20 | Création commande | Personnel | Interface Personnel |
| 09h22 | Ticket généré | Système | Impression |
| 09h22 | Notification gestionnaire | Système | Dashboard |
| 09h25 | Statut ROUGE activé | Gestionnaire | Dashboard |
| 09h28 | Début lavage (ORANGE) | Gestionnaire | Dashboard |
| 09h28 | Notification WhatsApp | Système | WhatsApp |
| 09h30 | Mise à jour écran suivi | Système | Écran TV |
| 09h45 | Ajout sandwich | Personnel/Gestionnaire | Dashboard |
| 09h46 | Notification MAJ | Système | WhatsApp |
| 10h08 | Service terminé (VERT) | Gestionnaire | Dashboard |
| 10h08 | Notification fin service | Système | WhatsApp + TV |
| 10h12 | Arrivée kiosque | M. Kouassi | Kiosque Paiement |
| 10h15 | Paiement Orange Money | M. Kouassi | Kiosque |
| 10h15 | Reçu imprimé | Système | Kiosque |
| 10h16 | Transaction fermée | Système | Base données |

**DURÉE TOTALE : 1h01 (09h15 → 10h16)**  
**SATISFACTION CLIENT : Parcours fluide et intuitif** 

---

## LIENS PROTOTYPES ACTUALISÉS

** PROTOTYPE INTERFACE UTILISATEUR :**  
https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/UTILISATEUR-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=2-227&t=zNFqRcN7m0BILJrY-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1

** PROTOTYPE INTERFACE CAISSE :**  
https://www.figma.com/proto/8sGkvDRXmzGEQvimjm2ieo/UTILISATEUR-%7C-AGENCE-MULTI-SERVICE--lavage-auto--CAS-BASSAM?node-id=28-364&t=MpkYvjJzdMhoGMZy-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1

