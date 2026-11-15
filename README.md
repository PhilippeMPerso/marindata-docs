# Plugin marindata

Plugin Jeedom V4 avec architecture PHP minimaliste et démon Node.js.

## Structure
- `plugin_info/` : Métadonnées (`info.json`), configuration globale et installation.
- `core/` : Classe PHP principale (`marindata.class.php`), endpoint AJAX et callback HTTP (`jeemarindata.php`).
- `desktop/` : Interface utilisateur (pages PHP et scripts jQuery).
- `resources/` : Script d'installation des dépendances (`install_apt.sh`) et démon Node.js (`demond/demond.js`).

