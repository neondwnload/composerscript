# composerscript
Voorgeprogrammeerde script om Composer te installeren. (credits: https://getcomposer.org/doc/faqs/how-to-install-composer-programmatically.md)

## Downloaden en uitvoeren script op Ubuntu Server 22.04

Eerst clone je deze respository van Github:  
`git clone https://github.com/neondwnload/composerscript.git`

Daarna navigeer je naar deze repository en voer je de script uit:  
`cd composerscript`  
`bash compscript.sh`  
Indien je geen output ziet na het uitvoeren van de script, is de installatie succesvol verlopen.

Voeg PHP Composer toe aan de $PATH om het globaal te kunnen gebruiken:  
`sudo mv composer.phar /usr/local/bin/composer`
