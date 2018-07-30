# BeginSymfony
Starting with Symfony framework 

>Necessário PHP 7.1 instalado

>> sudo port install php71

>> sudo port install php71-iconv    

>> sudo port install php71-openssl

## Install composer
https://getcomposer.org/download/

### Baixando o comporser
  php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

### Configurando
  php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
  
### Executando
php composer-setup.php

### Configurando a variável de ambiente
  mv composer.phar /usr/local/bin/composer
  
### Criando um projeto
  composer create-project symfony/website-skeleton <my-project>
  
