# Project Configuration Installer: jpmschuler/config-typo3-pourtea

To adapt TYPO3 extensions to the QA examples in EXT:tea.

Installation:
```sh
composer config preferred-install.ttn/tea source
composer req jpmschuler/config-typo3-pourtea:*@dev
```

Features:
- adds static config files with gitignore 
  - /.editorconfig
  - /phive.xml
  - /phpcs.xml
  - /phpstan.neon
  - /.php_cs.php
- add gitlab pipeline without gitignore
  - .gitlab folder as-is
  - .gitlab-ci.yml with include of that folder

Missing Features:
- adapt composer.json to include scripts
- add composer dependencies
- add Tests
- add GitHub Actions
- add .ddev config