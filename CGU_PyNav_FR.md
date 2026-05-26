# CONDITIONS GÉNÉRALES D'UTILISATION
## PyNav

**Dernière mise à jour : 26 mai 2026**

---

## 1. INFORMATIONS LÉGALES

**Éditeur de l'application :**
- Dénomination sociale : CL Consulting SASU
- SIRET : 94261399300016
- Siège social : 24 rue Jean Paul Pandolfi, 20110 Propriano, France
- Email : colin.larrue.pro@gmail.com

**Application :** PyNav  
**Plateformes :** Android (Google Play Store) & iOS (Apple App Store)

---

## 2. OBJET

Les présentes Conditions Générales d'Utilisation (ci-après "CGU") régissent l'utilisation de l'application mobile PyNav (ci-après "l'Application").

PyNav est une application marine permettant :

- L'affichage professionnel de données NMEA sur tablette (centrale de navigation)
- Le contrôle à distance du système de pilotage automatique open-source **pypilot** (optionnel)

L'Application peut être utilisée indépendamment de pypilot comme centrale de navigation NMEA. Elle permet :
- **Version gratuite** : Accès à l'onglet de contrôle pypilot uniquement (cap actuel du pilote, modes, gains, arrêt d'urgence). Aucune donnée NMEA externe. Nécessite une installation pypilot.
- **Version PRO (prix de lancement : 8,99€, prix régulier : 12,99€)** : Centrale de navigation NMEA complète sur tablette 10" ou plus. Utilisable AVEC ou SANS pypilot. Nécessite uniquement un module NMEA/WiFi et une tablette (4 Go RAM minimum).

En téléchargeant et en utilisant l'Application, l'utilisateur accepte sans réserve les présentes CGU.

---

## 3. DÉFINITIONS

- **Application** : Désigne le logiciel PyNav disponible sur le Google Play Store
- **Utilisateur** : Toute personne utilisant l'Application
- **Pypilot** : Système de pilotage automatique open-source développé par Sean D'Epagnier
- **NMEA** : Protocole de communication standard pour équipements marins (NMEA 0183 et NMEA 2000)
- **Version gratuite** : Fonctionnalités de télécommande pypilot accessibles sans paiement
- **Version PRO** : Fonctionnalités avancées d'affichage NMEA nécessitant un achat unique

---

## 4. PRÉREQUIS TECHNIQUES

L'utilisation de l'Application nécessite impérativement :

### 4.1 Matériel requis

**Version GRATUITE (onglet Autopilot uniquement) :**
- Un smartphone ou tablette Android (version 7.0 minimum recommandée)
- Une installation pypilot fonctionnelle (Raspberry Pi + moteur + capteurs)
- Connexion WiFi directe au hotspot du Raspberry Pi pypilot (aucun routeur nécessaire)

**Version PRO (Autopilot + affichage NMEA complet) :**
- Une tablette Android 10 pouces ou plus (recommandé pour affichage optimal)
- 4 Go de RAM minimum (pour la fluidité des graphiques temps réel)
- Android 7.0 minimum
- Une installation pypilot fonctionnelle (Raspberry Pi + moteur + capteurs)
- Un module NMEA/WiFi pour diffuser les données instruments sur le réseau (ex : Yacht Devices YDWG-02, Quark-elec QK-A034, Digital Yacht WLN10, Hat Labs SH-wg, Actisense W2K-1, ou tout module diffusant NMEA via TCP/UDP sur WiFi)
- Un réseau WiFi commun entre le Raspberry Pi pypilot et le module NMEA, selon l'une des configurations suivantes :

  **Configuration A (recommandée) :** Un mini-routeur WiFi indépendant (ex : GL.iNet, TP-Link) sur lequel le Raspberry Pi pypilot ET le module NMEA se connectent en mode client. La tablette PyNav se connecte au même routeur.

  **Configuration B :** Le module NMEA/WiFi est configuré en mode Access Point. Le Raspberry Pi pypilot s'y connecte en mode client. La tablette PyNav se connecte au réseau du module NMEA. Vérifiez que votre module supporte bien ce mode (compatible : Yacht Devices YDWG-02, Quark-elec QK-A034, Hat Labs SH-wg, etc.)

### 4.2 Compétences requises
L'Utilisateur doit :
- Posséder les connaissances nécessaires pour installer, configurer et utiliser pypilot
- Connaître les règles de navigation maritime (RIPAM/COLREG)
- Être capable d'assurer la maintenance de son installation pypilot
- Savoir interpréter les données de navigation NMEA

---

## 5. NATURE DU SERVICE

### 5.1 Ce que l'Application EST

L'Application est :
- Une **interface de contrôle** permettant d'envoyer des commandes à un système pypilot existant
- Un **lecteur et afficheur** de données NMEA provenant d'équipements de navigation
- Un **accessoire logiciel** facilitant l'utilisation de pypilot
- Un **outil complémentaire** aux équipements de navigation réglementaires

### 5.2 Ce que l'Application N'EST PAS

L'Application N'EST PAS :
- Un système de pilotage automatique autonome
- Un équipement de navigation certifié ou homologué
- Un substitut aux équipements de navigation réglementaires
- Une garantie du bon fonctionnement de pypilot
- Un remplacement du jugement humain du navigateur

### 5.3 Précisions importantes

**Pypilot :**
- Est un projet open-source indépendant développé par Sean D'Epagnier
- Est fourni "en l'état" sans garantie d'aucune sorte (licence GPLv3)
- N'est pas un produit commercial certifié pour la navigation maritime
- Relève de la seule responsabilité de son créateur et de la communauté open-source

**L'éditeur de PyNav :**
- N'a aucun lien avec le développeur de pypilot
- Ne fabrique ni ne vend de systèmes de pilotage automatique
- Ne garantit pas le fonctionnement de pypilot
- Fournit uniquement une interface logicielle de contrôle

---

## 6. FONCTIONNALITÉS

### 6.1 Version GRATUITE

La version gratuite donne accès aux onglets **Autopilot** et **Settings** :

**Onglet Autopilot :**
- Connexion WiFi directe au hotspot du Raspberry Pi pypilot (sans routeur)
- Engager / désengager le pilote automatique
- Sélection du mode : compas, vent, GPS, vent réel, nav
- Affichage du cap courant, saisie du cap cible
- Indicateur d'angle de barre (rudder)
- Données IMU : tangage, roulis, gîte, taux de rotation
- Réglage complet des gains PID (P, I, D, DD, PR, FF, WG, Deadzone)
- Calibration compas IMU et calibration de barre
- Paramètres de virement de bord
- Sélection de profils pilote (basic, wind, gps, simple, rate, absolute)
- Statistiques servomoteur : ampères-heures, tension, températures, durée de fonctionnement

**Onglet Settings :**
- Configuration des connexions NMEA 0183, NMEA 2000 et Pypilot (hôte, port, statut)
- Thème d'affichage : Clair / Sombre / Nuit
- Unités : profondeur (m/ft/brasses), vitesse (nœuds/km/h/mph)
- Péremption des données configurable

⚠️ **La version gratuite ne comprend PAS l'affichage de données NMEA provenant d'autres équipements. Ces données sont exclusivement disponibles dans la version PRO.**

### 6.2 Version PRO (Prix de lancement : 8,99€ - Achat unique)

La version PRO est **optimisée pour tablette 10 pouces ou plus (4 Go RAM minimum)** et débloque en plus :

**Affichage NMEA complet :**
- Affichage avancé des données NMEA 0183 et NMEA 2000 (via module NMEA/WiFi)
- Instruments de navigation personnalisables (compas, speedomètre, profondimètre, anémomètre, etc.)
- Graphiques temps réel (vitesse, cap, vent, profondeur, etc.)
- Historiques et tendances de navigation
- Tableaux de bord multiples et personnalisables

**Fonctionnalités avancées :**
- Alertes personnalisées (vent, profondeur)
- Mode nuit automatique
- Mises à jour gratuites à vie

⚠️ **La version PRO nécessite un module NMEA/WiFi tiers pour l'affichage des données instruments. Ce module n'est pas fourni par l'éditeur.**

---

## 7. RESPONSABILITÉ DE L'UTILISATEUR

### 7.1 Navigation et sécurité

L'Utilisateur reconnaît et accepte que :

**Le skipper reste l'unique responsable de :**
- La navigation et de la sécurité du navire et de ses occupants
- La veille permanente en mer (obligation réglementaire)
- L'interprétation des données de navigation
- La prise de toutes les décisions de navigation
- Le respect des règles maritimes internationales (RIPAM/COLREG)

**L'Application ne dispense PAS de :**
- Maintenir une veille visuelle et radar permanente
- Disposer des équipements de navigation réglementaires
- Consulter les cartes marines officielles et à jour
- Vérifier les données de navigation par d'autres moyens
- Faire preuve de bon sens maritime

### 7.2 Installation et maintenance

L'Utilisateur s'engage à :
- Installer et configurer correctement son système pypilot
- Vérifier régulièrement le bon fonctionnement de son installation
- Maintenir son matériel en bon état de fonctionnement
- Ne pas utiliser l'Application si pypilot présente des dysfonctionnements
- Tester l'Application en conditions sûres avant utilisation en navigation
- Toujours disposer d'un moyen de pilotage manuel de secours

### 7.3 Utilisation appropriée

L'Utilisateur s'engage à :
- Ne pas utiliser l'Application en conditions dangereuses (tempête, navigation difficile, etc.)
- Ne pas se fier uniquement à l'Application pour la navigation
- Vérifier les commandes envoyées au pilote automatique
- Surveiller en permanence le comportement du navire
- Arrêter immédiatement l'utilisation en cas d'anomalie
- Ne pas utiliser l'Application si ses compétences de navigation sont insuffisantes

---

## 8. LIMITATION DE RESPONSABILITÉ

### 8.1 Exclusion de garantie

L'Application est fournie "EN L'ÉTAT" et "SELON DISPONIBILITÉ" sans garantie d'aucune sorte, expresse ou implicite, notamment :
- Aucune garantie de fonctionnement sans interruption ou sans erreur
- Aucune garantie d'exactitude des données affichées
- Aucune garantie de compatibilité avec toutes les configurations pypilot
- Aucune garantie de disponibilité permanente du service

### 8.2 Responsabilité de pypilot

L'éditeur ne peut être tenu responsable :
- Des défaillances, bugs ou dysfonctionnements de pypilot lui-même
- De l'installation incorrecte ou défectueuse de pypilot
- De la configuration inadaptée du système pypilot
- Des limitations intrinsèques de pypilot en tant que projet DIY open-source
- Des décisions de conception ou des choix techniques de pypilot

### 8.3 Responsabilité des incidents de navigation

L'éditeur décline toute responsabilité en cas de :
- **Accidents maritimes** : collision, échouage, chavirement, naufrage
- **Dommages matériels** : avarie du navire, des équipements, des biens transportés
- **Dommages corporels** : blessures, traumatismes, décès
- **Dommages environnementaux** : pollution, destruction d'écosystèmes
- **Pertes financières** : frais de remorquage, de réparation, perte d'exploitation
- **Perte de données** : trajets, waypoints, paramètres de navigation

### 8.4 Responsabilité technique

L'éditeur ne peut être tenu responsable :
- Des erreurs de transmission de commandes (dues au réseau WiFi, aux interférences, etc.)
- De l'incompatibilité avec certaines versions ou configurations de pypilot
- Des bugs logiciels de l'Application
- Des interruptions de service (maintenance, mise à jour, panne serveur)
- De la perte de connexion réseau entre l'Application et pypilot
- Des erreurs d'affichage des données NMEA
- De la latence dans la transmission des commandes

### 8.5 Cas de force majeure

L'éditeur ne saurait être tenu responsable en cas de force majeure ou d'événements indépendants de sa volonté : panne Internet, panne électrique, catastrophe naturelle, guerre, acte de piratage, etc.

### 8.6 Plafonnement de responsabilité

En toute hypothèse, la responsabilité de l'éditeur, si elle devait être retenue, serait limitée au montant payé par l'Utilisateur pour l'Application (soit 12,99€ maximum pour la version PRO, 0€ pour la version gratuite).

---

## 9. COMPATIBILITÉ

### 9.1 Versions pypilot supportées

L'Application est compatible avec :
- Pypilot version 0.x et ultérieures
- Protocole de communication pypilot standard (TCP/IP)

### 9.2 Sources NMEA supportées

L'Application peut lire les données NMEA depuis :
- Le serveur pypilot lui-même
- Toute source NMEA 0183 connectée au réseau
- Toute source NMEA 2000 via passerelle NMEA

### 9.3 Non-garantie de compatibilité

L'éditeur ne garantit pas :
- La compatibilité avec toutes les configurations pypilot personnalisées
- La compatibilité avec des versions futures de pypilot
- La compatibilité avec tous les périphériques NMEA
- Le fonctionnement sur tous les modèles d'appareils Android

---

## 10. LICENCE D'UTILISATION

### 10.1 Licence non exclusive

L'éditeur concède à l'Utilisateur une licence d'utilisation **non exclusive, non transférable et révocable** de l'Application.

### 10.2 Restrictions

L'Utilisateur s'interdit de :
- Copier, modifier, adapter, traduire ou créer des œuvres dérivées de l'Application
- Décompiler, désassembler ou tenter d'extraire le code source
- Louer, prêter, vendre, sous-licencier ou distribuer l'Application
- Utiliser l'Application à des fins commerciales sans autorisation
- Contourner les mécanismes de protection ou d'achat intégré
- Utiliser l'Application de manière frauduleuse ou illégale

### 10.3 Propriété intellectuelle

L'Application et tous ses éléments (code, design, graphiques, textes, etc.) sont protégés par le droit d'auteur et restent la propriété exclusive de CL Consulting SASU.

**Note importante :** Pypilot est un projet distinct sous licence GPLv3, propriété de son auteur Sean D'Epagnier et de la communauté open-source.

---

## 11. VERSION PRO - CONDITIONS D'ACHAT

### 11.1 Prix et paiement

- **Prix de lancement :** 8,99€ TTC (achat unique) - valable 3 mois dès la publication
- **Prix régulier :** 12,99€ TTC (achat unique) - applicable après la période de lancement
- **Paiement :** Via Google Play (Android) ou Apple App Store (iOS) (carte bancaire, Google Pay, etc.)
- **Devise :** Prix affiché dans la devise du pays de l'Utilisateur

### 11.2 Pas de remboursement

Conformément à la politique Google Play, **aucun remboursement n'est possible** après activation de la version PRO, sauf en cas de vice caché ou de non-conformité manifeste.

L'Utilisateur est invité à tester la version gratuite avant d'acheter la version PRO.

### 11.3 Achat définitif

L'achat de la version PRO est **définitif et à vie** :
- Pas d'abonnement mensuel ou annuel
- Pas de frais cachés ou récurrents
- Mises à jour gratuites incluses à vie
- Utilisable sur tous les appareils associés au compte Google (Android) ou Apple ID (iOS) de l'Utilisateur

### 11.4 Restauration d'achat

Si l'Utilisateur désinstalle puis réinstalle l'Application, la version PRO sera automatiquement restaurée sans frais supplémentaires (même compte Google).

---

## 11 bis. POLITIQUE DE PRIX ET OFFRE DE LANCEMENT

### Prix de lancement

Dans le cadre du lancement de PyNav, l'éditeur propose une **offre de lancement temporaire** :

- **Prix de lancement : 8,99€** - valable pendant les **3 premiers mois** suivant la date de publication de l'Application sur les stores
- **Prix régulier : 12,99€** - applicable à l'issue de la période de lancement

### Garanties pour les acheteurs au prix de lancement

Les utilisateurs ayant acquis la version PRO au **prix de lancement de 8,99€** bénéficient des garanties suivantes :
- ✅ Accès à vie à toutes les fonctionnalités PRO
- ✅ Toutes les futures mises à jour gratuites incluses
- ✅ Aucun frais supplémentaire lors du passage au prix régulier
- ✅ Les mêmes droits que les acheteurs au prix régulier

### Transparence tarifaire

L'éditeur s'engage à :
- Communiquer clairement la date de fin du prix de lancement
- Ne jamais facturer à nouveau les acheteurs au prix de lancement
- Maintenir le prix régulier stable après la période de lancement

---

## 12. DONNÉES PERSONNELLES ET CONFIDENTIALITÉ

### 12.1 Données collectées

**L'Application ne transmet AUCUNE donnée de navigation à l'éditeur.**

Les seules données collectées sont :
- **Connexion réseau locale** : Adresse IP locale du serveur pypilot (reste sur le réseau local)
- **Identifiant d'achat** : Jeton Google Play pour vérifier l'achat de la version PRO (géré par Google)
- **Crashlytics** (optionnel) : Rapports d'erreurs anonymes pour améliorer la stabilité de l'Application

### 12.2 Aucune transmission de données sensibles

L'Application NE transmet PAS à l'éditeur :
- Les positions GPS
- Les trajets et waypoints
- Les données NMEA
- Les paramètres pypilot
- Les préférences utilisateur (stockées localement uniquement)

### 12.3 Conformité RGPD

L'éditeur respecte le Règlement Général sur la Protection des Données (RGPD).

Pour toute question relative à vos données personnelles, vous pouvez contacter : colin.larrue.pro@gmail.com

**Voir la Politique de Confidentialité complète** pour plus de détails.

---

## 13. AVERTISSEMENTS DE SÉCURITÉ

### 13.1 Avertissement principal

⚠️ **AVERTISSEMENT CRITIQUE DE SÉCURITÉ**

**PyNav et pypilot sont des outils d'AIDE à la navigation, PAS des substituts au jugement humain.**

- Le skipper reste SEUL RESPONSABLE de la navigation
- La veille permanente est OBLIGATOIRE en mer (règlement international)
- Pypilot est un projet DIY open-source SANS certification maritime
- L'Application peut présenter des bugs, erreurs ou dysfonctionnements
- Ne JAMAIS faire confiance aveuglément à un pilote automatique

### 13.2 Situations dangereuses

**N'utilisez PAS l'Application dans les situations suivantes :**
- Conditions météorologiques difficiles (tempête, forte houle, brouillard dense)
- Navigation dans des zones encombrées (ports, chenaux, zones de pêche)
- Proximité de dangers (rochers, hauts-fonds, épaves)
- Trafic maritime dense ou zone de croisement de routes
- En cas de dysfonctionnement de pypilot
- Si vous n'avez pas les compétences de navigation nécessaires
- Si vous êtes fatigué, sous influence d'alcool ou de substances altérant le jugement

### 13.3 Équipements de secours

Vous devez TOUJOURS disposer de :
- Un moyen de pilotage manuel de secours (barre franche, safran d'urgence)
- Des cartes marines papier à jour
- Un compas de relèvement magnétique
- Des moyens de communication d'urgence (VHF, téléphone satellite)
- Un GPS de secours indépendant

### 13.4 Tests préalables

Avant toute utilisation en navigation réelle :
- Testez l'Application au port ou au mouillage
- Vérifiez la fiabilité de la connexion WiFi
- Assurez-vous que pypilot répond correctement aux commandes
- Familiarisez-vous avec l'interface et les fonctionnalités
- Testez le bouton d'arrêt d'urgence

---

## 14. MISES À JOUR

### 14.1 Mises à jour de l'Application

L'éditeur peut publier des mises à jour de l'Application pour :
- Corriger des bugs
- Améliorer les performances
- Ajouter de nouvelles fonctionnalités
- Assurer la compatibilité avec de nouvelles versions d'Android ou de pypilot

### 14.2 Gratuité des mises à jour

Toutes les mises à jour sont **gratuites** pour :
- Les utilisateurs de la version gratuite
- Les acheteurs de la version PRO (mises à jour à vie)

### 14.3 Installation des mises à jour

Les mises à jour sont distribuées via le Google Play Store. L'Utilisateur est responsable de maintenir l'Application à jour.

---

## 15. RÉSILIATION

### 15.1 Par l'Utilisateur

L'Utilisateur peut cesser d'utiliser l'Application à tout moment en la désinstallant.

**Attention :** La désinstallation ne donne PAS droit à un remboursement de la version PRO.

### 15.2 Par l'éditeur

L'éditeur se réserve le droit de suspendre ou résilier l'accès à l'Application en cas de :
- Violation des présentes CGU
- Utilisation frauduleuse ou illégale
- Comportement abusif ou nuisible

### 15.3 Arrêt de l'Application

L'éditeur se réserve le droit d'arrêter définitivement l'Application moyennant un préavis raisonnable. Aucun remboursement ne sera dû dans ce cas.

---

## 16. DROIT APPLICABLE ET JURIDICTION

### 16.1 Droit applicable

Les présentes CGU sont régies par le **droit français**.

### 16.2 Juridiction compétente

En cas de litige, et à défaut de résolution amiable, les tribunaux français seront seuls compétents.

Le tribunal compétent sera celui du ressort du siège social de CL Consulting SASU (Propriano, France) ou du domicile du consommateur.

---

## 17. MODIFICATIONS DES CGU

L'éditeur se réserve le droit de modifier les présentes CGU à tout moment.

Les utilisateurs seront informés des modifications via :
- Une notification dans l'Application
- Un message sur le Google Play Store

La poursuite de l'utilisation de l'Application après modification des CGU vaut acceptation des nouvelles conditions.

---

## 18. CONTACT

Pour toute question concernant l'Application ou les présentes CGU :

**CL Consulting SASU**  
24 rue Jean Paul Pandolfi  
20110 Propriano  
France  

Email : colin.larrue.pro@gmail.com

---

## 19. ACCEPTATION DES CGU

En utilisant PyNav, vous reconnaissez avoir lu, compris et accepté l'intégralité des présentes Conditions Générales d'Utilisation.

**Date de dernière mise à jour :** 16 mai 2026

---

**CL Consulting SASU - PyNav**  
*Votre compagnon de navigation pypilot*
