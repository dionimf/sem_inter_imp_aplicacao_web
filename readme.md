# Seminário Interdisciplinar: Implementação de uma Aplicação WEB (ADS102)

Projeto visa a criação de uma aplicação web desenvolvida em PHP realizando os processos de Create, Read, Update, Delete "CRUD" 
Foram utilizados PHP8.3, Laravel 11, mysql e docker

### Passo a passo
Clone Repositório
```sh
git clone https://github.com/dionimf/sem_inter_imp_aplicacao_web.git
```
```sh
cd sem_inter_imp_aplicacao_web
```
Suba os containers do projeto
```sh
docker-compose up -d
```


Crie o Arquivo .env
```sh
cp .env.example .env
```

Acesse o container app
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```

Gere a key do projeto Laravel
```sh
php artisan key:generate
```

Rodar as migrations
```sh
php artisan migrate
```

Acesse o projeto
[http://localhost:8000](http://localhost:8000)
