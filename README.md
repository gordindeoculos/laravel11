# Projeto Laravel 11 com Pacote de Autenticação Laravel/UI

Este projeto já está com a autenticação por login, redefinição de senha e idioma português brasileiro (PT-BR) configurados.

## Pré Requisitos

**Certifique que tenha esses programas instalados no computador**

- Git versão 2.4 ou superior 
- PHP versão 8.2 ou 8.3
- Composer versão 2.7 ou superior
- Nodejs versão 20.1 ou superior

**Habilitar as extensões no arquivo `php.ini`**

```
extension=zip
extension=fileinfo
extension=curl
extension=openssl
extension=gd
extension=mysqli
extension=pdo_mysql
extension=pdo_pgsql
extension=pdo_sqlite
extension=pgsql
extension=sqlite3
extension=mbstring
```

## Instalação

### Download do código fonte

Para utilizar este código, faça o clone utilizando o Git. Para isso, execute o comando:

```
git clone https://github.com/gordindeoculos/laravel11.git
```

### Instalação das Dependências e Configuração do Ambiente de Desenvolvimento

Como foi feito o clone do projeto Laravel a partir do GitHub, é necessário executar os comandos abaixo
para instalar as dependências do projeto e configurar o amebiente de desenvolvimento.

**1. Instalar as dependências listadas no arquivo `composer.json`:**

```
composer install
```

**2. Instalar as dependências listadas no arquivo `package.json`:**

```
npm install
npm run build
```

**3. Copiar o arquivo de ambiente `.env`:**

```
copy .env.exemple1 .env
```

**4. Gerar uma nova chave de aplicativo:**

```
php artisan key:generate
```

**5. Criar o arquivo `database.sqlite` dentro do diretório `database`:**

Clique com o botão direito do mouse sobre a pasta `database`, no menu suspenso clique em `New File` ou `Novo Arquivo` e digite `database.sqlite` como nome do arquivo, em seguida pressione `Enter`.

**6. Executar as migrações do banco de dados:**

```
php artisan migrate
```

**7. Iniciar o servidor de desenvolvimento:**

```
php artisan serve
```

Isso iniciará um servidor local para o seu aplicativo Laravel, normalmente em `http://localhost:8000`.