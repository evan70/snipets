# snipets

* https://www.drupal.org/node/2118743
* wget https://www.drupal.org/files/issues/core-8.3.0-twig_debug_not_display-suggestions-array-2118743-107.patch
* /var/www/html/core$ patch -p1 < core-8.3.0-twig_debug_not_display-suggestions-array-2118743-107.patch

* /var/www/html$ patch -p1 < twig_debug_output_does-2118743-93.patch.txt

# Git
  * git config --global user.name "Anatoly Politsin"
  * git config --global user.email politsin@gmail.com

# Composer
  * composer update --with-dependencies
  * drush updatedb
  * composer update drupal/core --with-dependencies

# Drush
  * drush entity-updates
