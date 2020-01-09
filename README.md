Código Teste
Sistema em PHP feito com Laravel para Consumo de uma API JSONPlaceholder

Ps: Melhor não rodar dentro de Xampp ou Lampp. basta seguir este arquivo.

Funciona com servidor próprio do laravel(php artisan serve)

Começando
Clone o repositório do projeto:

opção 1: Caso você use HTTPS:

git clone https://github.com/cristianwk/dva.git

opção 2: Caso você use SSH:

git clone git@github.com:cristianwk/dva.git

Após a clonagem, entre no diretório da aplicação:

cd dva

em seguida execute os dois comandos abaixo:

composer install

e logo após a conclusão do comando acima, execute:

npm install

Na raiz do projeto localize e Duplique o arquivo .env.example e em seguida renomeie-o para .env usando o comando:

cp .env.example .env

Então rode o comando:

php artisan key:generate

e em seguida

php artisan serve

Agora basta

visite http: // localhost: 8000 para ver o aplicativo em ação.

PS: Este aplicativo nao requer instalação de banco de dados

Construído com
Laravel - O framework PHP para artesãos da Web React - uma biblioteca JavaScript para criar interfaces de usuário

by Cristian Marques
Contato cristianms.awk@gmail.com