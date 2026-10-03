# Politique de confidentialité de Milli

**Date d'entrée en vigueur :** 1er août 2026
**Dernière mise à jour :** 3 octobre 2026

## En bref

Milli ne collecte pas vos données. Il n'existe aucun serveur Milli, aucun outil
d'analyse, aucune publicité, aucun suivi et aucun kit de développement tiers.
Tout ce que vous saisissez reste sur votre appareil et — uniquement si vous
activez la synchronisation iCloud — dans votre propre compte iCloud privé,
auquel nous n'avons pas accès.

## Qui nous sommes

Milli (« l'application ») est développée par **IVAN CAYABYAB** (« nous »).

Pour toute question concernant cette politique ou votre vie privée, contactez-nous à
**ivnsjdev@gmail.com**.

## Ce que Milli stocke, et où

Milli est une application de finances personnelles. Les informations que vous
saisissez sont stockées sur votre appareil dans une base de données locale.
Nous ne les recevons jamais.

| Ce que vous saisissez | Où cela se trouve | Le voyons-nous ? |
| --- | --- | --- |
| Transactions, montants, notes, dates | Sur votre appareil | Non |
| Comptes et registres | Sur votre appareil | Non |
| Catégories et budgets | Sur votre appareil | Non |
| Paiements récurrents et rappels | Sur votre appareil | Non |
| Repères de salaire que vous saisissez | Sur votre appareil | Non |
| Photo de profil | Sur votre appareil | Non |
| Paramètres et préférences de l'application | Sur votre appareil | Non |
| Mots que Milli apprend de vos corrections dans le chat | Sur votre appareil | Non |
| Transactions saisies sur Apple Watch | Sur votre Apple Watch, puis sur votre iPhone | Non |

Nous ne collectons, ne transmettons, ne vendons, ne louons ni ne partageons rien
de tout cela, car l'application n'a aucune capacité à l'envoyer où que ce soit.
Milli n'effectue aucune requête réseau vers un serveur exploité par nous ou par
un tiers.

## Smart Chat et intelligence sur l'appareil

Le **Smart Chat** de Milli vous permet d'enregistrer une transaction en la
saisissant en langage courant — « café 4,50 », ou « courses 62 hier » — et Milli
détermine pour vous le montant, la catégorie et la date.

Tout cela se passe **sur votre appareil**. Milli utilise l'intelligence sur
l'appareil d'Apple et les fonctionnalités de texte sur l'appareil intégrées à iOS,
avec un simple lecteur à base de règles en secours lorsque celles-ci ne sont pas
disponibles. Il n'y a aucun serveur d'IA : votre message est lu sur l'appareil et
n'est jamais envoyé à nous ni à aucun tiers.

Lorsque vous choisissez ou corrigez la catégorie d'une note, Milli retient ce mot
afin que la même note se classe d'elle-même la prochaine fois. Ces associations
apprises entre mot et catégorie sont stockées uniquement sur votre appareil, aux
côtés du reste de vos données, et ne sont jamais transmises. Vous pouvez les
consulter, et en supprimer n'importe laquelle, dans l'application. Milli n'utilise
pas ce que vous saisissez, ni rien d'autre que vous entrez, pour entraîner un
quelconque modèle d'apprentissage automatique.

## Synchronisation iCloud (facultative)

Si vous activez la synchronisation iCloud, Milli utilise CloudKit d'Apple pour
copier vos données dans la **base de données privée de votre propre compte
iCloud**, afin qu'elles apparaissent sur vos autres appareils connectés avec le
même Apple Account.

- Ces données sont stockées sous votre Apple Account, pas le nôtre.
- Nous n'y avons aucun accès et aucune capacité à les lire, les exporter ou
  les récupérer.
- Apple traite ces données comme décrit dans la
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Vous pouvez désactiver la synchronisation iCloud à tout moment dans les
paramètres de l'application, ou la désactiver pour l'ensemble du système dans
**Réglages → votre nom → iCloud** sur votre appareil.

## Apple Watch

Milli comprend une application Apple Watch, disponible dans le cadre des
fonctionnalités premium, pour consulter les chiffres du jour et ajouter des
transactions depuis votre poignet.

**Comment les données y arrivent.** L'application montre n'a ni base de
données, ni compte, ni accès réseau propre. Tout ce qu'elle affiche provient
directement de votre iPhone jumelé via **WatchConnectivity**, le lien système
entre un iPhone et l'Apple Watch qui lui est jumelée. Ce lien est
d'appareil à appareil, géré par iOS et watchOS ; il ne passe par aucun serveur
qui nous appartient, et aucune donnée Milli ne nous est envoyée à aucun moment.

**Ce qui transite par le lien.** Uniquement ce dont l'écran de la montre a
besoin : vos comptes et leurs noms, icônes, couleurs et devises ; les
transactions du jour et le solde net du jour pour ces comptes ; les noms et
icônes de vos catégories ; vos préférences de langue et de format de nombre ;
et si les fonctionnalités premium sont débloquées. L'intégralité de votre
historique de transactions, vos notes, budgets et photo de profil restent sur
l'iPhone. Dans l'autre sens, une transaction que vous saisissez sur la montre
est transmise à l'iPhone sous forme d'un montant, d'une catégorie et d'un
compte, puis enregistrée dans votre registre là-bas.

**Ce que la montre conserve.** La montre stocke le dernier instantané reçu,
ainsi que toute transaction que vous avez saisie et que l'iPhone n'a pas
encore confirmée, dans le stockage privé propre à l'application sur la montre
elle-même. C'est ce qui permet à l'application de s'ouvrir sur des chiffres
réels et de vous laisser enregistrer une dépense lorsque votre iPhone est hors
de portée. Tout ce qui est saisi pendant que les deux appareils sont séparés
est conservé sur la montre jusqu'à ce que l'iPhone soit de nouveau accessible,
puis lui est transmis.

- L'application montre **n'utilise pas** iCloud, et ne conserve aucune copie
  de vos données en dehors de la montre.
- L'application montre **n'effectue aucune** requête réseau.
- Elle **n'accède pas** aux données de santé, de forme physique, de fréquence
  cardiaque, d'entraînement ou de localisation, et ne demande aucune de ces
  autorisations.

**Pour supprimer la copie de la montre,** désinstallez Milli de la montre —
sur la montre, appuyez de manière prolongée sur l'icône de l'application et
supprimez-la, ou sur l'iPhone, ouvrez l'application **Watch**, sélectionnez
Milli, et désactivez *Show App on Apple Watch*. Dissocier la montre efface
également ses applications et leurs données.

## Face ID, Touch ID et verrouillage par code

Si vous activez le verrouillage de l'application, Milli demande à iOS de vous
authentifier. Vos données biométriques sont entièrement gérées par le
Secure Enclave d'Apple et ne sont **jamais partagées avec l'application** —
iOS indique seulement à Milli si l'authentification a réussi ou échoué. Si
vous définissez un code d'application, il est stocké uniquement sur votre
appareil.

## Appareil photo et photothèque

Milli demande l'accès à l'appareil photo ou à la photothèque uniquement
lorsque vous choisissez de définir une photo de profil. L'image est stockée
sur votre appareil (et dans votre propre iCloud, si la synchronisation est
activée). Milli ne télécharge d'images nulle part et n'accède pas à votre
photothèque en arrière-plan.

## Notifications

Si vous activez les rappels pour les paiements récurrents, Milli programme des
**notifications locales** sur votre appareil. Celles-ci sont générées sur
l'appareil par iOS. Aucun serveur de notification push n'est impliqué et aucun
contenu de rappel ne quitte votre appareil.

## Achats

Milli propose un achat intégré unique pour débloquer les fonctionnalités
premium. L'achat est entièrement traité par **Apple** via l'App Store. Nous ne
recevons jamais vos coordonnées de paiement, votre numéro de carte ou votre
adresse de facturation. Milli demande seulement à Apple si l'Apple Account
actuel possède l'achat, afin de savoir s'il doit débloquer les fonctionnalités
premium. L'application montre ne peut pas interroger l'App Store elle-même,
donc l'iPhone lui indique via le même lien privé si l'achat est débloqué —
une simple valeur oui/non, sans aucune information de paiement. Les achats
sont régis par les
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Sauvegardes que vous exportez

Milli vous permet d'exporter un fichier de sauvegarde de vos données. Une fois
exporté, ce fichier est sous votre contrôle et cette politique ne le protège
plus — où que vous l'enregistriez ou l'envoyiez (Fichiers, iCloud Drive,
e-mail, une autre application), cela relève des conditions de ce service.
Traitez un fichier de sauvegarde comme vous traiteriez un relevé bancaire.

## Widgets

Les widgets d'écran d'accueil de Milli lisent une petite quantité de vos
données depuis une zone de stockage privée partagée entre l'application et sa
propre extension de widget sur votre appareil. Rien dans cette zone partagée
n'est transmis en dehors de l'appareil.

## Ce que nous ne faisons PAS

Pour être explicite, Milli ne fait **pas** :

- collecter ou nous transmettre vos données personnelles ou financières
- utiliser des services d'analyse, de rapport de plantage ou de télémétrie
- inclure de la publicité ou des identifiants publicitaires
- vous suivre à travers d'autres applications ou sites web, ni partager de
  données avec des courtiers en données
- créer de comptes utilisateur, ni exiger une adresse e-mail, un numéro de
  téléphone ou une connexion
- lire des données de santé, de forme physique ou de localisation depuis
  votre iPhone ou votre Apple Watch
- envoyer vos données à un quelconque service d'IA, ni les utiliser pour entraîner
  des modèles d'apprentissage automatique — le Smart Chat fonctionne entièrement
  sur votre appareil

L'étiquette de confidentialité de Milli sur l'App Store reflète cela :
**Data Not Collected (données non collectées)**.

## Communications de support

Si vous nous envoyez un e-mail pour obtenir de l'aide, nous recevons votre
adresse e-mail, votre message, et tout appareil, version d'application,
capture d'écran ou autre information que vous choisissez d'inclure. Nous
l'utilisons uniquement pour vous répondre, enquêter sur le problème et
améliorer Milli. Ne nous envoyez pas votre registre, vos relevés ou d'autres
documents financiers — nous n'en avons pas besoin pour répondre à une demande
de support.

Là où le RGPD ou le UK GDPR s'applique, nous traitons le courrier de support
sur la base de notre intérêt légitime à répondre aux personnes qui nous
écrivent et à résoudre les problèmes qu'elles signalent. Il n'y a pas d'autre
traitement pour lequel trouver une base, car Milli ne nous envoie rien de
lui-même.

L'e-mail de support est facultatif et se déroule en dehors de Milli. Il est
traité par votre fournisseur de messagerie et par Google, qui héberge notre
boîte de support, conformément à la
[Google Privacy Policy](https://policies.google.com/privacy). Les serveurs de
messagerie de Google sont situés aux États-Unis, donc un message de support
que vous nous envoyez y est traité. Nous conservons les messages de support
pendant 24 mois maximum, et plus longtemps uniquement lorsqu'une obligation
légale, de sécurité ou de tenue de registres l'exige. Vous pouvez nous
demander de supprimer votre correspondance de support en écrivant à l'adresse
ci-dessous.

## Conservation et suppression des données

Milli ne nous envoie rien, nous ne détenons donc aucune de vos données
financières et n'avons rien à conserver ni à supprimer. La seule exception est
le courrier de support que vous choisissez de nous envoyer, traité ci-dessus.

- **Pour supprimer les données locales :** supprimez l'application de votre
  appareil, ou utilisez les propres options de réinitialisation/suppression
  de l'application.
- **Pour supprimer les données sur votre Apple Watch :** retirez Milli de la
  montre, comme décrit dans la section Apple Watch ci-dessus.
- **Pour supprimer les données synchronisées :** désactivez la synchronisation
  iCloud et supprimez les données de l'application dans
  **Réglages → votre nom → iCloud → Gérer le stockage du compte**.

Supprimer l'application ne supprime pas automatiquement les données déjà
synchronisées avec votre compte iCloud ; utilisez l'étape ci-dessus pour cela.
Supprimer l'application iPhone supprime également son compagnon Apple Watch.

## Vos droits

Selon l'endroit où vous vivez, vous pouvez avoir des droits en vertu du RGPD,
du UK GDPR, du CCPA/CPRA, ou de lois similaires — y compris le droit d'accéder,
de corriger, d'exporter ou de supprimer vos données personnelles, et le droit
de ne pas être discriminé pour avoir exercé ces droits.

Milli est conçue pour que vous exerciez ces droits directement : vos données
se trouvent sur votre propre appareil et dans votre propre compte iCloud, sous
votre contrôle à tout moment. Nous n'en détenons aucune copie, nous ne pouvons
donc pas en produire, modifier ou effacer une en votre nom. Nous ne vendons ni
ne partageons de données personnelles, et nous ne l'avons jamais fait.

Si vous estimez que nous n'avons pas respecté nos obligations, vous pouvez
nous contacter à l'adresse ci-dessus, et vous avez le droit de déposer une
plainte auprès de votre autorité locale de protection des données.

## Enfants

Milli ne s'adresse pas aux enfants et ne collecte sciemment aucune information
de qui que ce soit, y compris des enfants de moins de 13 ans (ou l'âge minimum
équivalent dans votre pays). Puisque l'application ne collecte aucune donnée,
aucune information de ce type ne peut nous être transmise.

## Modifications de cette politique

Si cette politique change, nous mettrons à jour cette page et réviserons la
date de « Dernière mise à jour » ci-dessus. Les changements importants seront
également mentionnés dans les notes de version de l'application. Nous vous
encourageons à consulter cette page périodiquement.

## Contact

Questions, préoccupations ou demandes :

**ivnsjdev@gmail.com**
