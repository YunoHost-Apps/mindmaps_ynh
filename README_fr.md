# Mindmaps pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/mindmaps.svg)](https://dash.yunohost.org/appci/app/mindmaps) ![](https://ci-apps.yunohost.org/ci/badges/mindmaps.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mindmaps.maintain.svg)  
[![Installer Mindmaps avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mindmaps)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer Mindmaps rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble
Mindmaps est une application de mind mapping basée sur HTML5. Il vous permet de créer des cartes mentales soignées dans le navigateur.

**Shipped version:** 1.0

## Captures d’écran

![](Link to a screenshot of this app.)

## Démo

* [Démo officielle](www.mindmaps.app)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : Lien vers la documentation officielle de cette application.
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mindmaps%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mindmaps/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mindmaps%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mindmaps/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/mindmaps_ynh/issues
 * Site de l'application : www.mindmaps.app
 * Dépôt de l'application principale : https://github.com/drichard/mindmaps
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mindmaps_ynh/tree/testing --debug
or
sudo yunohost app upgrade mindmaps -u https://github.com/YunoHost-Apps/mindmaps_ynh/tree/testing --debug
```
