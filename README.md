# Zend - Pós Webdev Alfa 2019

### Utilização:
Para iniciar o banco:
```
docker-compose up -d
cp atendimento/config/autoload/local.php.dist atendimento/config/autoload/local.php
cp atendimento2/config/autoload/local.php.dist atendimento2/config/autoload/local.php
```

Para iniciar o projeto `atendimento`:
```
php -S 0.0.0.0:8000 -t atendimento/public
```

Para iniciar o projeto `atendimento2`:
```
php -S 0.0.0.0:8000 -t atendimento2/public
```