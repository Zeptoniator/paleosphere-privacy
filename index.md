# Politique de confidentialité

_Dernière mise à jour : 13 octobre 2026 (version 1.1 de l'application)._

PaleoSphere est une encyclopédie paléontologique pour Android, éditée par un particulier :
dinosaures, fossiles, gisements, musées, frise des temps géologiques, cartes du passé,
laboratoire de terrain et observatoire de la recherche. Elle ne propose pas de compte,
n'affiche pas de publicité et n'intègre aucun outil de mesure d'audience ni de pistage.
**L'éditeur ne reçoit aucune donnée vous concernant.**

## 1. Responsable

L'éditeur de l'application est responsable des traitements décrits ici.

Contact : **serge.simono27@gmail.com**

## 2. Ce qui est enregistré sur l'appareil

| Donnée | Finalité | Durée |
| --- | --- | --- |
| Favoris et collections | Retrouver les espèces et fiches que vous suivez | Jusqu'à ce que vous les supprimiez ou désinstalliez l'application |
| Historique de recherche | Proposer vos recherches récentes | Effaçable à tout moment depuis les Réglages |
| Suivis de l'observatoire (espèce, genre, formation, intervalle, sujet, auteur) et leurs alertes | Vous signaler les publications nouvelles liées à ce que vous suivez | Jusqu'à ce que vous arrêtiez le suivi |
| Observations du laboratoire de terrain (notes, mesures, photos, position si vous l'ajoutez) | Documenter vos trouvailles | Jusqu'à ce que vous les supprimiez ; jamais incluses dans la sauvegarde Android |
| Instantanés et notes des laboratoires (portail temporel, biomécanique, fossiles numériques) | Retrouver vos analyses | Jusqu'à ce que vous les supprimiez |
| Contenus téléchargés (zones de carte hors ligne, images en cache, modèles 3D) | Consulter l'application sans réseau | Zones hors ligne supprimables depuis la carte, cache vidable depuis les Réglages |
| Réglages de l'application | Conserver vos préférences | Jusqu'à la désinstallation |

Ces données restent dans l'espace privé de l'application. Elles ne sont envoyées ni à
l'éditeur ni à un tiers, sauf dans les cas décrits aux sections 3 et 6, toujours à votre
demande.

## 3. Position

L'application ne demande que la position **approximative** (jamais la position précise,
jamais en arrière-plan), et seulement au moment où vous en avez besoin. Si vous refusez,
tout le reste fonctionne.

- **« Autour de moi » (carte)** : la position sert uniquement à trier sur l'appareil les
  gisements et musées par distance. Elle n'est **ni enregistrée, ni envoyée**. Les
  gisements protégés ne sont jamais classés par distance.
- **Laboratoire de terrain** : vous pouvez ajouter la position approximative à une
  observation ; elle reste sur l'appareil. Si vous demandez la **géologie cartographiée**
  du lieu, sa position, arrondie à environ 1 km, est envoyée à **Macrostrat** ; si vous
  demandez sa **reconstitution à une époque ancienne**, sa position arrondie à 0,1° (environ
  11 km) est envoyée au service **GPlates**. L'écran indique ce qui part avant l'envoi, et
  rien n'est envoyé pour une observation marquée protégée.
- **Reconstitution d'un lieu dans le passé** (Terre d'autrefois, portail temporel,
  scientifique) : quand le lieu choisi n'est pas déjà calculé dans l'application, ses
  coordonnées sont envoyées au service **GPlates** pour le replacer sur la Terre de
  l'époque. Si ce lieu est votre position, c'est la position approximative donnée par
  Android.

Aucune de ces demandes ne contient d'identifiant ni d'autre donnée vous concernant.

## 4. Caméra

La caméra n'est utilisée qu'à votre demande et après votre autorisation :

- **Réalité augmentée** : les images sont analysées **sur l'appareil**, en temps réel, et
  **ne sont jamais enregistrées ni envoyées**. La réalité augmentée repose sur les
  **Services Google Play pour la RA (ARCore)**, fournis par Google et régis par les
  [règles de confidentialité de Google](https://policies.google.com/privacy).
- **Photos du laboratoire de terrain** (dont le scanner de fossiles) : enregistrées sur
  l'appareil, sans métadonnées de position ; elles ne partent que si vous les exportez.

## 5. Contenus chargés depuis Internet

Pour afficher cartes, images et données scientifiques, l'application télécharge des contenus
publics auprès de services tiers, en HTTPS uniquement : fonds de carte (OpenFreeMap),
images (Wikimedia Commons), modèles 3D (Smithsonian Institution), occurrences fossiles
(GBIF), cartes géologiques (BRGM, Macrostrat), reconstitutions paléogéographiques (GPlates)
et biodiversité actuelle autour d'un gisement (iNaturalist, coordonnées du gisement arrondies
à 0,1°). Comme pour toute page web, ces services reçoivent l'adresse IP de l'appareil et la
ressource demandée ; **aucune donnée personnelle ni identifiant ne leur est transmis** par
l'application, en dehors des positions décrites à la section 3.

Sur votre demande seulement, l'identifiant d'une publication (DOI) est vérifié auprès de
**Crossref** et d'**OpenAlex**, et l'identifiant ORCID d'un auteur auprès d'**ORCID** : seul
cet identifiant public est envoyé. Les liens vers les sources (publications, Paleobiology
Database, Wikidata) s'ouvrent dans votre navigateur, uniquement quand vous les touchez.

## 6. Ce qui ne quitte l'appareil qu'à votre demande

- **Signaler un problème** : le rapport ne contient que l'identifiant de la fiche, la version
  des données, la version de l'application et votre commentaire. Il passe par le menu de
  partage d'Android, vers l'application et le destinataire que **vous** choisissez.
- **Exports du laboratoire de terrain** (fiches, données d'expédition) : un fichier que vous
  remettez à qui vous voulez. Sans position par défaut pour une observation privée ou
  protégée ; position généralisée (environ 11 km) sinon ; exacte seulement si vous le
  choisissez, jamais pour une observation protégée.
- **Sauvegarde du laboratoire de terrain** et **partage d'expédition entre appareils** : un
  fichier chiffré par votre mot de passe (qui n'est pas conservé), vers la destination que vous
  choisissez. Aucun serveur PaleoSphere n'intervient.
- **Recherche vocale** : si vous l'utilisez, elle est confiée au service de reconnaissance
  vocale de votre téléphone, selon ses propres conditions.

## 7. Notifications

Avec votre autorisation (Android 13 et plus), l'application affiche des notifications
**créées sur l'appareil** : nouvelles publications liées à vos suivis, rappels du laboratoire
de terrain. Elles ne passent par aucun serveur. Si vous refusez, suivis et laboratoire
restent utilisables, sans notification.

## 8. Sauvegarde Android

Si la sauvegarde est activée dans les réglages de votre téléphone, Android peut copier les
favoris, collections, suivis et réglages de l'application dans **votre** compte Google, pour
les restaurer sur un nouvel appareil. Les observations du laboratoire de terrain n'en font
pas partie. Cette sauvegarde est gérée par Android et Google, et l'éditeur n'y a pas accès.
Vous pouvez la désactiver dans les réglages de votre téléphone.

## 9. Ce qui n'est jamais fait

- aucune collecte de données personnelles par l'éditeur ;
- aucune publicité, aucun suivi, aucune mesure d'audience ;
- aucune vente, location ou cession de données ;
- aucun suivi de position, ni en arrière-plan ni en continu.

## 10. Enfants

L'application ne s'adresse pas spécifiquement aux enfants. Son mode enfant masque les
contenus et fonctions de recherche avancés ; elle ne collecte aucune donnée, y compris celles
des enfants.

## 11. Vos droits

Toutes vos données étant sur votre appareil, vous en gardez la maîtrise : effacez
l'historique et le cache depuis les Réglages, les zones hors ligne depuis la carte, vos
suivis et observations depuis leurs écrans, ou toutes les données en désinstallant
l'application. Pour toute question : **serge.simono27@gmail.com**.

## 12. Modifications

Toute évolution de cette politique sera publiée sur cette page, avec sa date de mise à jour.
