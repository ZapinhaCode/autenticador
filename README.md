## Licença

### Olhar e se inspirar neste projeto

## Instruções de instalação

### Passo 1: Clonar o Repositório
```bash
git clone https://github.com/ZapinhaCode/agenda-ferias.git
cd agenda-ferias
```

### Passo 2: Rodar as dependências do projeto
```
composer install
npm install
```

### Passo 3: Criar o arquivo .env pegando o .env.example como referência
```
APP_NAME=Autenticador
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_TIMEZONE=America/Sao_Paulo
APP_URL=http://localhost

APP_LOCALE=pt_BR
APP_FALLBACK_LOCALE=pt_BR
APP_FAKER_LOCALE=pt_BR

APP_MAINTENANCE_DRIVER=file
# APP_MAINTENANCE_STORE=database

BCRYPT_ROUNDS=12

LOG_CHANNEL=stack
LOG_STACK=single
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=autenticador
DB_USERNAME=root
DB_PASSWORD=

SESSION_DRIVER=database
SESSION_LIFETIME=120
SESSION_ENCRYPT=false
SESSION_PATH=/
SESSION_DOMAIN=null

BROADCAST_CONNECTION=log
FILESYSTEM_DISK=local
QUEUE_CONNECTION=database

CACHE_STORE=database
CACHE_PREFIX=

MEMCACHED_HOST=127.0.0.1

REDIS_CLIENT=phpredis
REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=465
MAIL_USERNAME=freedomframessmtp@gmail.com
MAIL_PASSWORD="rrea paeb slly uvge"
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS="freedomframessmtp@gmail.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

VITE_APP_NAME="${APP_NAME}"

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

GITHUB_CLIENT_ID=Ov23ctt4277ogPWIHQz2
GITHUB_CLIENT_SECRET=a6ed0a58ed3e625481a570cf9baae72eb1ba5ec4
```

### Passo 4: Criar a sua key única para o projeto
```
php artisan key:generate
```

### Passo 5: Criar o banco de dados MySQL utilizando as seguintes informações como base
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=autenticador
DB_USERNAME=root
DB_PASSWORD=
```

### Passo 6: Rodar as migration para montar as tabelas do seu banco de dados
```
php artisan migrate
```

## Instruções de uso

### Passo 1: Em uma janela de terminal rode o comando para abrir a porta do Laravel
```
php artisan serve
```

### Passo 2: Em uma outra janela rode o seguinte comando para abrir a porta do Vite
```
npm run dev
```

## Licença
Este projeto se trata de um open-source que segue os padrões licenciados pela [MIT license](https://opensource.org/licenses/MIT).
