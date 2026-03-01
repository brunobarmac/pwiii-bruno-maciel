Documentação do Laravel
O que é o Laravel? O Laravel é um framework de PHP. Sua utilidade é organizar os documentos e o código (através do padrão MVC), fornecer conexão com banco de dados e sistemas de rotas simples; além disso tudo, oferece segurança para ataques comuns. Resumindo: ele é uma ferramenta que te auxilia, ajuda e organiza seu projeto de desenvolvimento de sistemas em PHP.
Onde podemos usar? Na maioria dos projetos, desde sistemas administrativos, de login e cadastro, lojas, e pode servir até para sistemas e aplicativos para mobile.
Como realizar a instalação 1: Instale os sistemas Node.js, PHP e o Composer.
2: Em seu terminal, como administrador, digite este comando:
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.4'))
(Exemplo para sistema operacional Windows).
Esse comando vai iniciar a instalação do PHP e do Laravel em seu dispositivo. Após realizar esse comando, finalize a instalação do Laravel junto com o Composer; para isso, basta digitar esse código no mesmo terminal: composer global require laravel/installer
3: Criar a estrutura do Laravel: (todos os comandos para digitar serão no terminal, de preferência o do VS Code). Para criar a estrutura do Laravel, basta primeiro criar uma pasta Laravel colocando esse comando:
laravel new example-app
Após isso, você precisará localizar a pasta criada para trabalhar com ela; somente digite esse comando:
cd example-app
Agora é preciso incluir as dependências do projeto e bibliotecas listadas no package.json:
npm install
Agora precisamos criar a estrutura do projeto para integrar o script em JavaScript através do comando:
npm run build
Para finalizar as integrações, precisamos incluir o composer.json para iniciar o ambiente de desenvolvimento local de um projeto PHP. Assim poderemos trabalhar com o PHP através do comando:
composer run dev 
Com isso, a estrutura do seu projeto já está pronta.
4: Otimizando o ambiente (Laravel Boost)
Para acelerar o desenvolvimento e adicionar funcionalidades extras, instale o pacote Boost como dependência de desenvolvimento:
composer require laravel/boost --dev
Após a instalação do pacote, execute o comando abaixo para realizar a configuração inicial:
php artisan boost:install
documentacao do laravel completa: https://laravel.com/docs/12.x/installation
documentacao do canva: https://www.canva.com/design/DAHCtX5NT9U/iihd7AcsKzllrzZReYLGvA/edit?utm_content=DAHCtX5NT9U&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
