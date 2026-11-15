# Plugin marindata

Plugin Jeedom V4 avec architecture PHP minimaliste et démon Node.js.

## Structure
- `plugin_info/` : Métadonnées (`info.json`), configuration globale et installation.
- `core/` : Classe PHP principale (`marindata.class.php`), endpoint AJAX et callback HTTP (`jeemarindata.php`).
- `desktop/` : Interface utilisateur (pages PHP et scripts jQuery).
- `resources/` : Script d'installation des dépendances (`install.sh`) et démon Node.js (`marindatad/marindatad.js`).

## Configuration
Générer une clé sur le site https://api-maree.fr/. La renseigner ici:
<img width="1443" height="171" alt="image" src="https://philippemperso.github.io/marindata-docs/images/Configuration.png" />
Ne pas modifier le port interne du démon, sauf s'il est déjà utilisé par une autre application.

## Equipement
Créer ensuite 1 ou plusieurs équipements selon les ports qui vous intéressent:
<img width="966" height="219" alt="image" src="https://philippemperso.github.io/marindata-docs/images/Equipement.png" />
