# AustESE Drupal Installation Profile

Run drush to download modules etc

    drush make https://raw.github.com/uq-eresearch/AustESE/master/scripts/austese.make  -y  /var/www/drupal


Use installation profile to install required modules and themes

    cd /var/www/drupal

    drush si austese_drupal --db-url=mysqli://austese:austesepassword@localhost/drupal7 --account-name=admin --account-pass=adminpassword --site-name=AustESE --site-mail=admin@example.org
