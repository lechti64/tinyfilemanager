# Tiny File Manager


[![Live demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg?style=flat-square)](https://tinyfilemanager.github.io/demo/)
[![Live demo](https://img.shields.io/badge/Help-Docs-lightgrey.svg?style=flat-square)](https://tinyfilemanager.github.io/)
[![GitHub Release](https://img.shields.io/github/release/qubyte/rubidium.svg?style=flat-square)](https://github.com/prasathmani/tinyfilemanager/releases)
 [![GitHub License](https://img.shields.io/github/license/prasathmani/tinyfilemanager.svg?style=flat-square)](https://github.com/prasathmani/tinyfilemanager/blob/master/LICENSE) 
[![Paypal](https://img.shields.io/badge/Donate-Paypal-lightgrey.svg?style=flat-square)](https://www.paypal.me/prasathmani)
> C'est un gestionnaire de fichiers simple, rapide et petit basé sur le Web.Une seule application Web prête pour gérer le stockage, le téléchargement, l'édition et la gestion de fichiers et de dossiers en ligne via un navigateur Web. L'application fonctionne sur PHP 5.5+, elle permet la création de plusieurs comptes utilisateurs, chaque utilisateur pouvant avoir son propre répertoire, un support intégré pour gérer les fichiers texte avec cloud9 IDE et prenant en charge la coloration syntaxique pour plus de 150 langues et plus de 35 thèmes.

## Demo
[Demo](https://tinyfilemanager.github.io/demo/)

 Login Details : admin/admin@123 | user/12345


## Documentation
Tinyfilemanager est très documenté sur les [pages wiki](https://github.com/prasathmani/tinyfilemanager/wiki) officielles de son développeur.


[![Tiny File Manager](screenshot.gif)](screenshot.gif)

## Exigences

- PHP 5.5.0 ou plus.
- les extensions Fileinfo, iconv, zip, tar et mbstring sont fortement recommandées.

## Comment l'utiliser

Télécharger le fichier ZIP avec la dernière version de la branche principale (master).

Copiez simplement le fichier tinyfilemanager.php sur votre espace web - c'est tout :)
Vous pouvez également changer le nom de fichier de "tinyfilemanager.php" en tout chose d'autre, vous savez ce que je voulais dire question sécurité....

Nom d'utilisateur/mot de passe par défaut: **admin/admin@123** and **user/12345**.

:warning: Avertissement: veuillez définir votre propre nom d'utilisateur et mot de passe dans `$auth_users` avant utilisation. le mot de passe est chiffré avec <code>password_hash()</code>. pour générer un nouveau hachage de mot de passe [cliquez ici](https://tinyfilemanager.github.io/docs/pwd.html)

Pour activer/désactiver le jeu d'authentification choisir "vrai ou faux" en éditant cette variable `$use_auth` (true or false).


### :loudspeaker: Caractéristiques 

- :cd: Open Source, léger et extrêmement simple à utiliser
- :iphone: Affichage convivial pour les appareils tactiles
- :information_source: Les fonctionnalités de base que vous aimerez: Créer, Supprimer, Modifier, Afficher, Affichage rapide, Télécharger, Envoyer, Copier et déplacer des fichiers 
- :arrow_double_up: Ajax Upload, Possibilité de glisser-déposer, d'envoyer à partir d'une URL, d'envoyer plusieurs fichiers avec un filtre d'extensions de fichier
- :file_folder: Possibilité de créer des dossiers et des fichiers
- :gift: Possibilité de compresser, d'extraire des fichiers (`zip`, `tar`)
- :sunglasses: Prise en charge des autorisations utilisateur - en fonction de la session et de chaque mappage de dossier racine utilisateur
- :floppy_disk: Copier l'URL du fichier directement
- :pencil2: Cloud9 IDE - Syntaxe en surbrillance pour plus de `150+` langages, Plus de `35+` thèmes avec votre style de programmation préféré
- :page_facing_up: Google/Microsoft et leur visionneuse de documents vous aide à prévisualiser `PDF/DOC/XLS/PPT/etc`. 25 Mo peuvent être prévisualisés avec la visionneuse Google Drive
- :zap: Fichiers de sauvegarde et liste noire IP et liste blanche sont supportés
- :mag_right: Recherche -  Rechercher et filtrer des fichiers à l'aide de `datatable js`
- :file_folder: Exclure des dossiers et des fichiers de la liste
- :globe_with_meridians: Multi-langage(20+) support et traductions `translation.json` est le fichier requis pour cela.
- :bangbang: Et beaucoup plus...


### <a name=license></a>License, Credit  

- Disponible sous [GNU license](https://github.com/prasathmani/tinyfilemanager/blob/master/LICENSE)
- Concept original et développement par github.com/alexantr/filemanager
- CDN Utilisés - _jQuery, Bootstrap, Font Awesome, Highlight js, ace js, DropZone js, ekko-lightbox js, et DataTable js_
- Pour signaler un bogue ou demander une fonctionnalité, veuillez déposer ici une [demande/communication](https://github.com/prasathmani/tinyfilemanager/issues)
- [Contributeurs](https://github.com/prasathmani/tinyfilemanager/wiki/Authors-and-Contributors)
