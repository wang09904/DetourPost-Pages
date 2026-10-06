# Politique de confidentialité de Detour Post

**Brouillon de révision interne · mis à jour le 6 octobre 2026 · non publié et sans effet · examens juridique et linguistique en cours.**

---

## 1. Présentation

Detour Post est exploité par Yong Wang, une personne physique. Dans la présente politique, « nous » désigne Yong Wang, qui détermine les modalités de traitement de vos données personnelles.

Cette politique de confidentialité explique quelles informations nous collectons, pourquoi nous les traitons, comment elles sont traitées et stockées, les périodes de conservation et comment vous pouvez exercer vos droits en matière de confidentialité.

Notre principe fondamental est simple : **Vos lettres sont privées entre vous et votre destinataire. Nous ne pouvons pas les lire et nous n’avons pas l’intention de les lire.**

## 2. Informations que nous traitons

### 2.1 Informations que vous fournissez activement

| Informations | Détails | Nécessité |
|---|---|---|
| Compte et identité de connexion | Identifiant du compte, identifiant du fournisseur de connexion et adresse e-mail vérifiée transmis par Apple ou Google | Nécessaires pour créer et authentifier le compte |
| Identifiants de connexion | Jetons de session ; le service conserve une empreinte de chaque jeton | Nécessaires pour un accès sécurisé |
| Mois et année de naissance et région choisie | L’App vérifie sur votre appareil l’âge requis à partir du mois et de l’année indiqués et de la région sélectionnée | Nécessaires à l’inscription. Le mois et l’année de naissance restent dans les données de l’App sur votre appareil, où vous pouvez les consulter et les modifier ; le mois et l’année de naissance ne sont ni transmis à nos serveurs ni enregistrés sur ceux-ci. Le service conserve séparément la version de la règle appliquée et la région de connexion |
| Nom affiché | Nom visible par les personnes avec lesquelles vous échangez des lettres | Obligatoire pour finaliser l’inscription ; modifiable ensuite dans le profil |
| Ville | Ville choisie pour envoyer des lettres, avec les données du lieu enregistrées par l’Application | Obligatoire pour l’inscription et l’envoi de lettres |
| Informations sur vos correspondants | Statut de la relation, codes d'invitation et codes secrets de réception des lettres | Obligatoire pour échanger des lettres |
| Contenu des lettres | Texte, papier à lettres et décorations choisis, photos jointes, coursier et heure de livraison choisie ou programmée | Créé uniquement lorsque vous choisissez d’envoyer une lettre |
| Données de signalement | Identifiants des comptes auteur et objet du signalement ; type, source et identifiant de la cible ; motif choisi ; identifiant de corrélation pour l’audit ; état et date de création. **Ne contient ni texte de lettre, ni photo, ni texte libre, ni coordonnées.** Le signalement bloque également la personne signalée et met fin à ses lettres qui vous sont destinées et n’ont pas encore été livrées | Créé uniquement si vous effectuez un signalement |
| Notes privées | Notes que vous rédigez au sujet d’un contact | Facultatives. Conservées sur votre appareil et incluses dans votre sauvegarde iCloud personnelle uniquement si vous l’activez ; elles ne sont pas transmises à notre service |

**Chiffrement de bout en bout des lettres et des photos.** Le texte et les photos sont chiffrés sur votre appareil avant leur transmission au service. Pour ces contenus, nous ne détenons que des données chiffrées, sans clés de déchiffrement. Les autres données de compte et de service décrites ici sont traitées séparément. Voir la section 4.

### 2.2 Informations générées automatiquement pendant l'utilisation

| Informations | Détails | Objectif |
|---|---|---|
| Statut de livraison | Départ, étapes du voyage, arrivée, rappel, statut de fin | Assurer l’envoi et la livraison des lettres |
| État du compte et de la sécurité | Statut du compte, listes de blocage réciproques, statut de traitement des rapports | Administration de compte et prévention des abus |
| Registre des achats et des avoirs | Commandes, mouvements et soldes de pièces, stocks de timbres et d’unités de programmation de livraison, propriété d’articles permanents, abonnements et état de restauration des achats | Facturation, exécution, restauration et remboursements |
| Jetons Push et appareils | Jetons push de l'appareil et métadonnées nécessaires | Envoi des notifications d'état des lettres |
| Journaux de service | Journaux opérationnels de l'API, traces d'erreurs et diagnostics de performances | Sécurité, stabilité et dépannage |

**Notifications push.** L’alerte visible utilise un texte générique. Le contenu transmis inclut aussi une catégorie de notification et un identifiant d’événement opaque pour ouvrir l’écran concerné ; il ne contient ni texte de lettre, ni photo, ni localisation. Les journaux opérationnels peuvent inclure des détails techniques de requêtes ou d’erreurs ; voir la section 8.

### 2.3 Ce que nous ne faisons JAMAIS

- Nous n'accédons PAS à votre photothèque complète, à vos contacts ou à votre position GPS précise ;

- L’App n’utilise pas les identifiants publicitaires (IDFA/IDFV) pour le ciblage publicitaire ni le suivi inter-applications et n’intègre aucun SDK publicitaire.

- Nous n’utilisons pas le contenu des lettres pour entraîner des modèles d’IA : nous n’avons pas accès au texte en clair ;

- Nous ne vendons JAMAIS vos informations personnelles à des tiers.

## 3. Pourquoi nous traitons les informations

| Finalité | Informations concernées |
|---|---|
| Envoyer et recevoir des lettres | Identifiant du compte, nom affiché, ville, informations de relation, lettre chiffrée et état de livraison |
| Achats intégrés, exécution et remboursements | Registre des achats et des avoirs, état de l’abonnement |
| Notifications de livraison | Jeton de notification push et état de livraison |
| Sécurité, signalements et prévention des abus | État du compte et de sécurité, données de signalement et journaux opérationnels |
| Diagnostic et stabilité du service | Journaux opérationnels |
| Demandes relatives aux droits et réclamations | Informations que vous nous fournissez |

La base juridique de chaque traitement dépend du droit applicable et des circonstances propres au traitement. Ce projet n’attribue pas encore de base juridique à chaque finalité. Cette analyse doit être achevée avant publication ; nous ne nous appuierons pas sur une base qui ne s’applique pas au regard du droit concerné.

## 4. Chiffrement de bout en bout

Il s’agit de la protection technique la plus critique de Detour Post :

**Le cryptage a lieu localement sur votre appareil.** Lorsque vous appuyez sur « Sceller cette lettre », tous les textes et photos sont cryptés sur votre appareil avant la transmission. Les clés de décryptage sont détenues exclusivement par vous et votre destinataire désigné.

**Le texte et les photos des lettres sont conservés uniquement sous forme chiffrée.** Nous n’en détenons pas les clés de déchiffrement et ne proposons pas de récupération manuelle des clés. Nous traitons aussi les données de compte et de service décrites dans cette Politique.

**Aucune exception.** Nous ne maintenons aucune porte dérobée administrative, canal d'inspection de contenu ou dérogation permettant au service client d’accéder au contenu. Étant donné que nous ne pouvons pas afficher le texte brut, nous ne pouvons pas effectuer de filtrage automatisé de mots clés ni de recommandation de contenu.

- Vous seul pouvez voir le contenu avant la livraison ;

- Seuls vous et votre destinataire pouvez voir le contenu après la livraison ;

- Si vous perdez votre appareil et n'avez pas de sauvegarde iCloud personnelle, nous ne pouvons pas récupérer vos lettres : nous n'avons pas les clés ;

- Un signalement de sécurité enregistre le motif choisi et les identifiants de compte ou de lettre associés, déclenche un blocage réciproque et met fin aux lettres non livrées que la personne signalée vous a envoyées. Il ne révèle pas le contenu des lettres. Si Yong Wang en prend connaissance, il fera des efforts raisonnables pour l’examiner et prendre des mesures appropriées si nécessaire. Aucun délai précis d’examen ou de réponse n’est promis ; toute mesure supplémentaire concernant le compte dépend d’un examen.

**Sauvegarde personnelle.** Si vous l’activez, certaines données de votre sac postal — notamment les notes privées de contacts, les brouillons, les éléments d’invitations en attente et les lettres enregistrées — sont chiffrées sur votre appareil et sauvegardées dans votre iCloud personnel via CloudKit. La clé de sauvegarde est conservée dans le trousseau de l’appareil. Une fois une sauvegarde vérifiée, une clé de récupération est enregistrée dans le trousseau iCloud afin de pouvoir être disponible sur vos autres appareils Apple. Nous ne recevons aucune de ces deux clés et ne pouvons pas déchiffrer la sauvegarde.

## 5. Autorisations système

L’Application peut demander l’autorisation de notification après votre première lettre envoyée ou reçue ; vous pouvez aussi la demander dans les Réglages. Si vous choisissez d’enregistrer une carte de voyageur générée dans votre photothèque, elle demande une autorisation limitée à l’ajout de photos.

| Autorisation | Sur demande | Objectif |
|---|---|---|
| Notifications | Après la première lettre envoyée ou reçue, ou lors de leur activation dans les Réglages | Alerte visible générique ; le contenu transmis comporte aussi une catégorie et un identifiant d’événement opaque pour ouvrir l’écran concerné, sans texte de lettre ni localisation |
| Photos (ajout uniquement) | Lorsque vous choisissez d’enregistrer une carte de voyageur générée | Enregistre cette image sans autoriser l’exploration de votre photothèque |

L’Application synchronise vos préférences de notification avec le service, qui s’en sert pour décider quelles alertes envoyer. L’autorisation iOS contrôle leur affichage sur l’appareil. Aucune de ces actions ne supprime ni ne désactive à elle seule le jeton de l’appareil sur le service. Refuser une autorisation facultative ne bloque pas à lui seul l’envoi ou la réception de base.

**Autres précisions sur les autorisations :**

- **Photos :** Pour joindre une photo à une lettre, le sélecteur système transmet uniquement l’image choisie à l’Application ; celle-ci ne parcourt pas toute votre photothèque. L’enregistrement d’une carte de voyageur générée utilise une autorisation distincte d’ajout de photos et la demande système correspondante.

- **Emplacement :** Vous choisissez la ville de chaque lettre. Nous ne recueillons pas la position de votre appareil et ne suivons pas vos déplacements. L’App contient un catalogue limité de noms et de coordonnées de pays et de villes pour proposer des recherches locales, quelques résultats hors ligne et des libellés de carte. Elle consulte d’abord ce catalogue ; si une ville correspond, elle utilise ce résultat localement et n’envoie pas le terme à MapKit. Sinon, elle demande des lieux à Apple MapKit. Si le catalogue ne contient pas de centre pour le pays ou la région choisis, l’App peut envoyer leur nom à Apple via Core Location pour cadrer la carte. Elle utilise également Core Location pour géocoder à rebours un point choisi sur la carte. Si Apple ne renvoie aucun résultat, une ville proche du catalogue peut servir de solution de repli limitée. Apple reçoit alors le texte recherché, le nom du pays ou de la région, ou les coordonnées du point cartographique concerné. Ces fonctions ne nécessitent pas l’autorisation de localisation.

- **Contacts, caméra, microphone, suivi des applications (ATT) :** Non demandé et aucun code correspondant n'existe.

## 6. Tiers

Nous ne vendons pas de données personnelles. Les prestataires nécessaires aux fonctions que vous utilisez traitent les données correspondantes. Pour le stockage et le traitement du texte et des photos des lettres sur les serveurs du service, ils reçoivent des données chiffrées ; nous ne leur fournissons pas de clés de déchiffrement.

| Tiers | Données traitées | Objectif | Remarques |
|---|---|---|---|
| Apple | Identifiant de connexion et adresse e-mail vérifiée, achats intégrés et abonnements, jeton push et acheminement des notifications, sauvegardes chiffrées du coffre personnel dans iCloud et clés de récupération si vous les activez, termes envoyés aux recherches de lieux MapKit, noms de pays ou de régions transmis pour cadrer la carte lorsque le catalogue ne contient pas de centre, et coordonnées de points cartographiques transmises pour le géocodage inversé via Core Location | Connexion, paiement, notifications, sauvegarde et fonctions de carte/recherche | Voir la [Politique de confidentialité d’Apple](https://www.apple.com/legal/privacy/) |
| Google | Identifiant du fournisseur de connexion et adresse e-mail vérifiée, lorsqu’elle est fournie | Authentification si vous choisissez Google | Voir la [Politique de confidentialité de Google](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Jeton push, texte d’alerte générique, catégorie de notification et identifiant d’événement opaque | Acheminement des notifications | Aucun texte de lettre, photo ou localisation précise dans le contenu transmis |
| Cloudflare | Lettres chiffrées, données de compte et de connexion, ville choisie, achats et livraisons, jetons push et journaux du service | Calcul dans le cloud, base de données et stockage d’objets | Voir la [Politique de confidentialité de Cloudflare](https://www.cloudflare.com/privacypolicy/) |

L’application iOS ne contient aucun SDK tiers de suivi, de publicité ou d’analyse.

## 7. Stockage des données et transferts internationaux

- **Sur votre appareil :** Lettres, brouillons, notes privées de contacts et préférences.

- **Dans votre iCloud personnel :** Si vous l’activez, une sauvegarde chiffrée de certaines données du sac postal, dont les notes privées de contacts, brouillons, éléments d’invitations en attente et lettres enregistrées.

- **Sur nos serveurs :** Identifiants de compte et de connexion, adresse e-mail vérifiée, noms affichés, données enregistrées de la ville choisie, relations et livraisons, lettres chiffrées, achats, jetons push et journaux du service. Notre infrastructure se trouve hors du pays ou de la région de certains utilisateurs ; ces données peuvent donc être traitées à l’international.

## 8. Périodes de conservation des données

| Informations | Durée de conservation |
|---|---|
| Mois et année de naissance | Le mois et l’année de naissance sont conservés dans les données de l’App associées à votre compte sur votre appareil ; vous pouvez les consulter et les modifier dans votre profil. Le mois et l’année de naissance ne sont ni transmis à nos serveurs ni enregistrés sur ceux-ci. |
| Compte et identité de connexion | La suppression du compte le désactive, révoque les sessions et supprime les données de profil et de notification. La conception actuelle conserve l’enregistrement du compte supprimé et l’identifiant du fournisseur de connexion ; aucune échéance fixe de suppression n’est définie. |
| Contenu chiffré des lettres | Le nettoyage du contenu chiffré côté serveur commence après confirmation de l’enregistrement complet de la lettre sur l’appareil du destinataire. À défaut, la lettre devient indisponible 90 jours après sa mise à disposition pour le destinataire (à partir de l’heure prévue pour une lettre programmée), puis entre dans le processus de nettoyage. L’expiration de ce délai ne rétablit pas le compte supprimé de l’expéditeur. |
| Données d’achat et d’exécution | Conservées pour gérer les achats, les remboursements et les livraisons déjà commencées. Aucune durée fixe n’est définie à ce stade. |
| Jetons de notification push | Les préférences de l’App déterminent les notifications envoyées ; l’autorisation iOS contrôle leur affichage sur l’appareil. La suppression du compte supprime son jeton d’appareil ; les jetons déclarés invalides par APNs sont désactivés. |
| Signalements de sécurité | Motif choisi, identifiants du compte ou de la lettre concernés, état et date de création. Aucune durée ni règle fixe de suppression n’est définie. |
| Journaux du service | Peuvent être créés pour la sécurité, la fiabilité et le diagnostic, et contenir des détails techniques de requêtes ou d’erreurs. Aucune durée fixe n’est définie. |

Les durées de conservation ou critères de suppression des enregistrements de comptes supprimés et identifiants de fournisseurs, des données d’achat et d’exécution, des signalements de sécurité et des journaux du service ne sont pas encore arrêtés. Ces règles et la base juridique de chaque finalité doivent être examinées avant publication.

## 9. Vos droits en matière de confidentialité

Selon votre lieu de résidence, le droit applicable peut vous accorder des droits d’accès, de rectification, d’effacement ou de copie des données personnelles, d’opposition ou de limitation de certains traitements, ou de retrait du consentement. Cette Politique ne limite pas les droits que la loi vous accorde. Adressez vos demandes à detourpost@aivolo.studio ; nous pouvons demander les informations nécessaires pour vérifier votre identité.

| Droit | Comment l’exercer |
|---|---|
| Accès ou copie | Ouvrez « Moi » pour consulter les données du compte, les achats et les articles ; contactez-nous pour les demandes non proposées dans l’Application |
| Rectification | Ouvrez « Moi » → « Profil » pour modifier le nom affiché et la ville ; contactez-nous pour d’autres données |
| Suppression | Utilisez la fonctionnalité « Supprimer le compte » de l'application ou contactez-nous pour des demandes de données spécifiques |
| Retrait du consentement | Écrivez à detourpost@aivolo.studio pour retirer votre consentement à un traitement qui repose sur celui-ci ; les effets sur les traitements antérieurs dépendent du droit applicable |
| Suppression du compte | « Moi » → « Supprimer le compte » → « Supprimer le compte » |
| Questions et demandes de renseignements | Contacter detourpost@aivolo.studio |

**Lors de la suppression du compte :** Le compte est désactivé, ses sessions sont révoquées et les données de profil et de notification sont supprimées. Les envois non partis sont annulés ; les lettres déjà parties suivent leur plan de livraison. Supprimer le compte de l’Application ne résilie pas un abonnement facturé par Apple ; gérez-le ou résiliez-le dans les réglages d’abonnement de votre compte Apple. Le service conserve actuellement un enregistrement du compte supprimé et l’identifiant du fournisseur de connexion ; voir la section 8.

Nous traiterons les demandes conformément au droit applicable. Le délai dépendra de la nature de la demande ; aucun délai général n’est promis.

## 10. Mineurs

L’App s’adresse aux personnes ayant l’âge minimum applicable, qui est d’au moins 13 ans et peut être supérieur dans certaines régions. Lors de l’inscription, l’App vérifie sur votre appareil, à partir du mois et de l’année de naissance que vous indiquez et de la région choisie, si vous remplissez le critère d’âge applicable. Le mois et l’année de naissance restent dans les données de l’App sur votre appareil et ne sont ni transmis à nos serveurs ni enregistrés sur ceux-ci.

Si vous pensez qu’une personne n’a peut-être pas l’âge minimum requis, écrivez à detourpost@aivolo.studio. Si Yong Wang prend connaissance de la situation, il fera des efforts raisonnables pour l’examiner et prendre les mesures exigées par le droit applicable. Aucun délai fixe d’examen ou de réponse n’est promis. Les parents ou tuteurs peuvent également écrire à cette adresse.

## 11. Mesures de sécurité

- Cryptage de bout en bout pour le texte des lettres et les photos ;

- Canaux de transport cryptés (TLS/HTTPS) ;

- Informations d'identification et clés stockées dans le stockage système sécurisé (porte-clés iOS) ;

- Protection de l’appareil pour les identifiants et les clés de chiffrement conservés localement.

Aucune mesure ne garantit une sécurité absolue. En cas d’incident de sécurité des données, nous fournirons les notifications et prendrons les mesures exigées par le droit applicable.

## 12. Mises à jour des politiques

Nous pouvons mettre à jour cette Politique. Le texte actuel et la date de mise à jour figurent sur cette page. Nous n’utiliserons pas les données personnelles à des fins incompatibles avec celles décrites ici. Si le droit applicable exige de notifier un changement important ou une nouvelle utilisation des données, nous le ferons par un moyen approprié.

## 13. Contactez-nous et plaintes

- **Opérateur :** Yong Wang

- **Email :** detourpost@aivolo.studio

Pour toute question ou réclamation, écrivez à detourpost@aivolo.studio. Si Yong Wang prend connaissance de votre message, il fera des efforts raisonnables pour l’examiner et répondre le cas échéant. Aucun délai précis n’est promis. Vous pouvez également déposer une réclamation auprès d’une autorité de contrôle compétente pour votre situation.
