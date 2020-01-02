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
Tinyfilemanager est très documenté sur le [wiki pages](https://github.com/prasathmani/tinyfilemanager/wiki).


[![Tiny File Manager](screenshot.gif)](screenshot.gif)

## Exigences

- PHP 5.5.0 ou plus.
- les extensions Fileinfo, iconv, zip, tar et mbstring sont fortement recommandées.

## Comment l'utiliser

Télécharger le fichier ZIP avec la dernière version de la branche principale (master).

Copiez simplement le fichier tinyfilemanager.php sur votre espace web - c'est tout :)
Vous pouvez également changer le nom de fichier de "tinyfilemanager.php" en tout chose d'autre, vous savez ce que je voulais dire question sécurité....

Nom d'utilisateur/mot de passe par défaut: **admin/admin@123** and **user/12345**.

:warning: Warning: Please set your own username and password in `$auth_users` before use. password is encrypted with <code>password_hash()</code>. to generate new password hash [here](https://tinyfilemanager.github.io/docs/pwd.html)

To enable/disable authentication set `$use_auth` to true or false.


### :loudspeaker: Features 

- :cd: Open Source, light and extremely simple
- :iphone: Mobile friendly view for touch devices
- :information_source: Basic features likes Create, Delete, Modify, View, Quick View, Download, Copy and Move files 
- :arrow_double_up: Ajax Upload, Ability to drag & drop, upload from URL, multiple files upload with file extensions filter 
- :file_folder: Ability to create folders and files
- :gift: Ability to compress, extract files (`zip`, `tar`)
- :sunglasses: Support user permissions - based on session and each user root folder mapping
- :floppy_disk: Copy direct file URL
- :pencil2: Cloud9 IDE - Syntax highlighting for over `150+` languages, Over `35+` themes with your favorite programming style
- :page_facing_up: Google/Microsoft doc viewer helps you preview `PDF/DOC/XLS/PPT/etc`. 25 MB can be previewed with the Google Drive viewer
- :zap: Backup files and IP blacklist and whitelist
- :mag_right: Search -  Search and filter files using `datatable js`
- :file_folder: Exclude folders and files from listing
- :globe_with_meridians: Multi-language(20+) support and for translations `translation.json` is file required
- :bangbang: lots more...


### <a name=license></a>License, Credit  

- Available under the [GNU license](https://github.com/prasathmani/tinyfilemanager/blob/master/LICENSE)
- Original concept and development by github.com/alexantr/filemanager
- CDN Used - _jQuery, Bootstrap, Font Awesome, Highlight js, ace js, DropZone js, ekko-lightbox js, and DataTable js_
- To report a bug or request a feature, please file an [issue](https://github.com/prasathmani/tinyfilemanager/issues)
- [Contributors](https://github.com/prasathmani/tinyfilemanager/wiki/Authors-and-Contributors)
