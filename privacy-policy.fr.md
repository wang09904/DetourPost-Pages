# 

**Implication :**

---

## 1. Présentation

Detour Post (ci-après dénommé « l'Application ») est exploité par Yong Wang (ci-après dénommé « nous », « notre » ou « notre »). Nous agissons en tant que responsable du traitement de vos informations personnelles.

Cette politique de confidentialité explique quelles informations nous collectons, pourquoi nous les traitons, comment elles sont traitées et stockées, les périodes de conservation et comment vous pouvez exercer vos droits en matière de confidentialité.

Notre principe fondamental est simple : **Vos lettres sont privées entre vous et votre destinataire. Nous ne pouvons pas les lire et nous n’avons pas l’intention de les lire.**

## 2. Informations que nous traitons

### 2.1 Informations que vous fournissez activement

| Informations | Détails | Nécessité |

|---|---|---|

| Identifiant de compte | Identifiant unique obtenu via Connectez-vous avec Apple ou Google | Obligatoire pour la création de compte |

| Identifiants de connexion | Jetons d'authentification de session | Requis pour un accès sécurisé |

| Date de naissance et région | Utilisé lors de l'inscription uniquement pour déterminer l'âge d'admissibilité | Obligatoire pour l'inscription. **La date de naissance est utilisée uniquement au moment de l'évaluation et immédiatement supprimée ; nous ne le stockons jamais.** Seules la version de la règle et la région sélectionnée sont conservées |

| Nom d'affichage | Nom personnalisé défini dans votre profil, visible par vos destinataires | Facultatif |

| Ville | Ville sélectionnée comme point de départ/arrivée | Facultatif, mais obligatoire pour envoyer des lettres |

| Informations de connexion | Statut de la relation, codes d'invitation et secrets de retrait des lettres | Obligatoire pour échanger des lettres |

| Contenu de la lettre | Texte de la lettre, choix de papeterie, photos jointes, coursier, heure d'arrivée | Créé uniquement lorsque vous choisissez d'envoyer |

| Détails du rapport | Catégorie de violation sélectionnée (harcèlement, spam, sécurité) et identifiant cible. **Contient AUCUN texte de lettre, photos, texte de forme libre ou coordonnées** ; bloque automatiquement la fête simultanément | Créé uniquement lorsque vous déposez un rapport |

| Notes privées | Notes privées que vous attribuez à un contact | Facultatif. **Stocké strictement sur votre appareil local, jamais téléchargé** |

**Cryptage de bout en bout des lettres et des photos.** Le texte des lettres et les photos sont cryptés directement sur votre appareil local avant la transmission. Nous ne détenons que du texte chiffré et ne possédons aucune clé de déchiffrement. Par conséquent, **nous ne pouvons pas lire, inspecter ou fournir le texte ou les photos de votre lettre à qui que ce soit**, y compris les demandes des forces de l'ordre, où seul un texte chiffré peut être fourni. Voir la section 4.

### 2.2 Informations générées automatiquement pendant l'utilisation

| Informations | Détails | Objectif |

|---|---|---|

| Statut de livraison | Départ, étapes du voyage, arrivée, rappel, statut de fin | Alimenter le pipeline de livraison postale |

| État du compte et de la sécurité | Statut du compte, listes de blocage réciproques, statut de traitement des rapports | Administration de compte et prévention des abus |

| Grand livre commercial | Enregistrements de commandes, soldes de pièces, propriété permanente d'articles, abonnements actifs | Gestion de la facturation, de l'exécution et du remboursement |

| Jetons Push et appareils | Jetons push de l'appareil et métadonnées nécessaires | Envoi des notifications d'état des lettres |

| Journaux de service | Journaux opérationnels de l'API, traces d'erreurs et diagnostics de performances | Sécurité, stabilité et dépannage |

**Aucun secret dans les journaux ou les notifications push.** Les journaux opérationnels ne contiennent jamais de texte de lettre, de photos, de codes d'invitation ou de coordonnées exactes. Les notifications push ne comportent que des phrases d'état génériques (par exemple, « Une lettre est arrivée ») sans identifiants personnels, texte de message ou villes.

### 2.3 Ce que nous ne faisons JAMAIS

- Nous n'accédons PAS à votre photothèque complète, à vos contacts ou à votre position GPS précise ;

- Nous ne collectons PAS d'identifiants de suivi (IDFA/IDFV), n'intégrons PAS de SDK publicitaires et ne effectuons PAS de suivi inter-applications ;

- Nous n'introduisons PAS de données de lettres dans les modèles de formation d'IA : nous n'avons pas accès au texte brut ;

- Nous ne vendons JAMAIS vos informations personnelles à des tiers.

## 3. Pourquoi nous traitons les informations

| Objectif | Informations impliquées | Base juridique |

|---|---|---|

| Livraison postale et réception | ID de compte, nom d'affichage, ville, informations de connexion, lettre cryptée, état de livraison | Exécution du contrat de service |

| Achats et remboursements intégrés | Livre d'achat, validité de l'abonnement | Exécution du contrat de service |

| Notifications push de livraison | Jeton push, état de livraison | Votre consentement (révocable à tout moment) |

| Sécurité, prévention des abus et rapports | État de sécurité, détails du rapport, journaux opérationnels | Intérêt légitime et obligation légale |

| Diagnostic et stabilité du service | Journaux opérationnels | Intérêt légitime |

| Gestion des droits des utilisateurs et des demandes de renseignements | Informations fournies par vous | Obligation légale |

## 4. Chiffrement de bout en bout

Il s’agit de la protection technique la plus critique de Detour Post :

**Le cryptage a lieu localement sur votre appareil.** Lorsque vous appuyez sur « Sceller cette lettre », tous les textes et photos sont cryptés sur votre appareil avant la transmission. Les clés de décryptage sont détenues exclusivement par vous et votre destinataire désigné.

**Nous ne détenons que du texte chiffré.** Nos serveurs stockent uniquement des blobs chiffrés. Nous ne conservons aucune clé de déchiffrement sous aucune forme et ne proposons pas non plus de récupération manuelle des clés.

**Aucune exception.** Nous ne maintenons aucune porte dérobée administrative, canal d'inspection de contenu ou remplacement du service client. Étant donné que nous ne pouvons pas afficher le texte brut, nous ne pouvons pas effectuer de filtrage automatisé de mots clés ni de recommandation de contenu.

- Vous seul pouvez voir le contenu avant la livraison ;

- Seuls vous et votre destinataire pouvez voir le contenu après la livraison ;

- Si vous perdez votre appareil et n'avez pas de sauvegarde iCloud personnelle, nous ne pouvons pas récupérer vos lettres : nous n'avons pas les clés ;

- Les rapports de sécurité déclenchent des blocages de relations et des pénalités de compte, sans que les opérateurs humains ne lisent le contenu des lettres.

**Sauvegarde personnelle.** Les sauvegardes de données de lettres s'effectuent exclusivement via votre iCloud personnel si elles sont activées. Les sauvegardes résident entièrement dans votre écosystème d’identifiant Apple. Nous n'avons pas accès à votre sauvegarde iCloud ou à vos clés de trousseau.

## 5. Autorisations système

L'application ne demande qu'une seule autorisation système :

| Autorisation | Sur demande | Objectif |

|---|---|---|

| Notifications | Lorsque vous acceptez les alertes par courrier | Vous alerte lorsque les lettres partent ou arrivent. Les charges utiles contiennent uniquement des expressions génériques |

La désactivation des notifications n'affecte pas l'envoi ou la réception de lettres.

**Autorisations que nous ne demandons PAS :**

- **Photos :** La sélection de photos utilise le sélecteur de photos du système natif. Seule l’image sélectionnée est transmise à l’application ; l’accès complet à la photothèque n’est ni demandé ni obligatoire.

- **Emplacement :** Les villes sont sélectionnées manuellement dans une liste. Nous ne suivons jamais les coordonnées de votre appareil.

- **Contacts, caméra, microphone, suivi des applications (ATT) :** Non demandé et aucun code correspondant n'existe.

## 6. Tiers

Nous ne vendons jamais de données personnelles. Les informations sont partagées strictement avec les fournisseurs d’infrastructures nécessaires :

| Tiers | Données traitées | Objectif | Remarques |

|---|---|---|---|

| Pomme | Identifiant de compte, achats StoreKit, expédition push, géocodage MapKit | Authentification, facturation in-app, notifications, affichage de la carte | Soumis à la [Politique de confidentialité d'Apple](https://www.apple.com/legal/privacy/) |

| Google | Identifiant de compte | Authentification facultative | Soumis aux [Politiques de confidentialité de Google](https://policies.google.com/privacy) |

| Service de notification push Apple (APN) | Jeton push, charge utile d'alerte générique | Envoi de notifications | Les charges utiles ne contiennent aucun texte de lettre ni identité de destinataire |

| Fournisseurs d'infrastructures cloud | Blobs de lettres cryptées, grand livre de comptes | Calcul cloud et stockage sécurisé | Traité strictement selon nos instructions |

L’application iOS ne contient aucun SDK tiers de suivi, de publicité ou d’analyse.

## 7. Stockage des données et transferts internationaux

- **Sur votre appareil :** Lettres, brouillons et préférences locaux.

- **Dans votre iCloud personnel :** Sauvegardes de bases de données cryptées au sein de votre compte Apple privé.

- **Sur nos serveurs :** ID de compte, noms d'affichage, charges utiles de lettres cryptées et registres de transactions stockés dans une infrastructure cloud sécurisée à l'étranger. Les données peuvent être transférées et traitées à l’international sous de strictes garanties contractuelles.

## 8. Périodes de conservation des données

| Informations | Période de conservation |

|---|---|

| Date de naissance | Non stocké. Évalué une fois lors de l'inscription et immédiatement rejeté |

| ID de compte, nom d'affichage, ville, connexions | Durée du cycle de vie du compte ; supprimé ou anonymisé de manière irréversible lors de la suppression du compte |

| Texte chiffré de lettre | Supprimé immédiatement après confirmation de livraison par le destinataire ; lettres non réclamées nettoyées après 90 jours |

| Registre d'achat | Conservé conformément aux lois financières, fiscales et de protection des consommateurs |

| Jetons push | Supprimé des serveurs immédiatement après la désinscription de la notification ou la suppression du compte |

| Journaux de service | Conservé pendant une courte fenêtre de diagnostic et automatiquement supprimé. Ne contient aucun secret privé |

## 9. Vos droits en matière de confidentialité

Vous pouvez exercer les droits suivants concernant vos informations personnelles :

| Droite | Comment faire de l'exercice |

|---|---|

| Accès et portabilité | Afficher le profil, les achats et les actifs dans « Mon profil » ; demander l'export via detourpost@aivolo.studio |

| Rectification | Modifiez le nom d'affichage et la ville dans les paramètres du profil ; contactez-nous pour d'autres enregistrements |

| Suppression | Utilisez la fonctionnalité « Supprimer le compte » de l'application ou contactez-nous pour des demandes de données spécifiques |

| Retirer le consentement | Désactivez les notifications dans les paramètres de l'application ou les paramètres du système iOS |

| Suppression de compte | Accédez à « Mon profil » → « Suppression et isolement du compte » → « Supprimer le compte » |

| Questions et demandes de renseignements | Contacter detourpost@aivolo.studio |

**Que se passe-t-il lors de la suppression du compte :** Les lettres non envoyées sont terminées ; les lettres parties continuent vers leur destination ; les enregistrements de profil, les relations de blocage et les jetons d'appareil sont immédiatement et définitivement effacés.

Nous répondons à toutes les demandes de confidentialité dans les **48 heures**.

## 10. Mineurs

L'application est destinée aux utilisateurs âgés de 13 ans et plus (ou plus selon les exigences de la juridiction locale). Nous ne collectons pas sciemment de données personnelles auprès de mineurs n’ayant pas atteint l’âge d’enregistrement applicable. Si vous pensez qu'un mineur s'est inscrit sans autorisation, contactez detourpost@aivolo.studio et nous supprimerons rapidement le compte.

## 11. Mesures de sécurité

- Cryptage de bout en bout pour le texte des lettres et les photos ;

- Canaux de transport cryptés (TLS/HTTPS) ;

- Informations d'identification et clés stockées dans le stockage système sécurisé (porte-clés iOS) ;

- Principe du moindre privilège pour l'infrastructure serveur ;

- Analyse continue des vulnérabilités et audits de configuration.

## 12. Mises à jour des politiques

Nous pouvons mettre à jour cette politique de confidentialité périodiquement. Les changements importants seront notifiés de manière bien visible dans l'application. Si vous n'êtes pas d'accord avec les conditions modifiées, vous pouvez supprimer votre compte.

## 13. Contactez-nous et plaintes

- **Opérateur :** Yong Wang

- **Email :** detourpost@aivolo.studio

Nous répondons aux demandes dans les **48 heures**. Vous avez également le droit de déposer une plainte auprès de votre autorité locale de contrôle de la protection des données.

© 2026 Yong Wang. Tous droits réservés.

---

© 2026 Yong Wang. All rights reserved.
