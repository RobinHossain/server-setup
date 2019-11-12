# Server Setup

```
sudo chgrp -R www-data /var/www/html
sudo chmod -R g+w /var/www/html

sudo find /var/www/html -type d -exec chmod 2775 {} \;
sudo find /var/www/html -type f -exec chmod ug+rw {} \;
```
