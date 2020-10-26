# Laravel Switcher

Neste pequeno projeto, o único objetivo é demonstrar a capacidade do laravel trabalhar em múltiplas plataformas através de projetos separados, por meio da manipulação de rotas no arquivo routes/web.php.

## Como funciona

No arquivo welcome da raiz das views, há apenas um script escrito em javascript para que seja identificado inicialmente qual a plataforma, e sem gerar nenhum delay este método automaticamente chama a rota responsável de acordo com o tipo de plataforma que o usuário está acessando. Este mecânismo é utilizado por diversas plataformas, de forma diferente, por exemplo o Facebook que faz o direcionamento por subdominios e não pastas dentro do projeto.

## Detalhes do projeto
- Laravel 5.6
- PHP 7.4.6

## Developer
- SharpComputing - Inovação de qualidade em portfólios para empresas
- Author: André Freitas
- Released date: 25/10/2020
- Website: https://shc.eng.br
