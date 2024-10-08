# Desafios_RS
Desafios realizados no âmbito de demonstração de competências

# Desafio 2

Avaliar capacidades de desenvolvimento back-end
utilizando o framework Laravel para construir uma aplicação funcional.

Configuração do Projeto Laravel

Este projeto é uma aplicação Laravel que utiliza XAMPP para o ambiente de desenvolvimento. Siga os passos abaixo para configurar o projeto no seu ambiente local.

## Pré-requisitos

- [XAMPP](https://www.apachefriends.org/index.html) instalado (inclui Apache e MySQL)
- [Composer](https://getcomposer.org/) instalado
- [Node.js](https://nodejs.org/) instalado 

## Passos de Configuração

### 1. Clonar o Repositório

Clone o repositório para o seu ambiente local:

```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Instalar Dependências
Instale as dependências do PHP usando o Composer:

```sh
composer install
```

### 3. Configurar o Arquivo .env
Edite o arquivo .env para configurar a conexão com o banco de dados. Certifique-se de que as configurações correspondem às suas configurações do XAMPP:


```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco_de_dados
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
```

### 4. Gerar a Chave da Aplicação

```sh
php artisan migrate
```

### 5. Migrar o Banco de Dados
```sh
php artisan migrate
```

### 6. Para a parte da configuração no seu README, você pode incluir instruções detalhadas sobre como configurar o ambiente de desenvolvimento, instalar dependências, configurar o banco de dados e executar a aplicação. Aqui está um exemplo de como você pode escrever essa seção:

```markdown
# Configuração do Projeto Laravel

Este projeto é uma aplicação Laravel que utiliza XAMPP para o ambiente de desenvolvimento. Siga os passos abaixo para configurar o projeto no seu ambiente local.

## Pré-requisitos

- [XAMPP](https://www.apachefriends.org/index.html) instalado (inclui Apache e MySQL)
- [Composer](https://getcomposer.org/) instalado
- [Node.js](https://nodejs.org/) instalado (opcional, se você precisar de ferramentas de frontend)

## Passos de Configuração

### 1. Clonar o Repositório

Clone o repositório para o seu ambiente local:

```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Instalar Dependências

Instale as dependências do PHP usando o Composer:

```sh
composer install
```

### 3. Configurar o Arquivo `.env`

Copie o arquivo `.env.example` para `.env` e configure as variáveis de ambiente:

```sh
cp 

.env.example

 .env
```

Edite o arquivo `.env` para configurar a conexão com o banco de dados. Certifique-se de que as configurações correspondem às suas configurações do XAMPP:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco_de_dados
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
```

### 4. Gerar a Chave da Aplicação

Gere a chave da aplicação Laravel:

```sh
php artisan key:generate
```

### 5. Migrar o Banco de Dados

Execute as migrações para criar as tabelas no banco de dados:

```sh
php artisan migrate
```

### 6. Executar o Servidor de Desenvolvimento


```sh
php artisan serve
```
