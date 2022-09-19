Olá Take.Seres , bom foi criado essa " POC" com intuito de mostrar de forma simples como podemos utilizar o cypress pra validar cenários do BliP.

Pré-requisitos
Antes de começar, garanta que os seguintes sistemas estejam instalados em seu computador.

git (estou usando a versão 2.26.0 enquanto fiz essa POC)
Node.js (estou usando a versão v16.13.1 enquanto enquanto fiz essa POC)
npm (estou usando a versão 8.3.0 enquanto enquanto fiz essa POC)
Google Chrome (estou usando a Versão 105.0.5195.102 (Versão oficial) 64 bits enquanto enquanto fiz essa POC)
Visual Studio Code (estou usando a versão 1.64.0 enquanto enquanto fiz essa POC) ou alguma outra IDE de sua preferência
Obs.: Recomendo utilizar as mesmas versões, ou versões mais recentes dos sistemas listados acima.

Obs. 2: Ao instalar o Node.js o npm é instalado junto. 🎉

Obs. 3: Para verificar as versões do git, Node.js e npm instaladas em seu computador, execute o comando git --version && node --version && npm --version no seu terminal de linha de comando.

Obs. 4: Deixei links para os instaladores na lista de requisitos acima, caso não os tenha instalados ainda.

Instalando o Cypress
No terminal, na raiz do projeto, execute o comando npm i cypress@9.7.0 -D (este comando irá instalar o Cypress como dependência de desenvolvimento, além de criar o arquivo package-lock.json e o diretório node_modules/)

Inicializando o Cypress
No terminal, na raiz do projeto, execute o comando npx cypress open (este comando irá abrir o Cypress em modo interativo e irá criar a estrutura inicial para os testes automatizados)


Por fim, dentro do diretório cypress/integration/, delete o diretório examples/

(Caso não queria esses cases como referência) 

Para abrir os testes em modo Iterativo utilize o comando npm cypress open
Para abrir os testes em modo Hedlles digite o comando  npm cypress run

Justificativa: Usei esse Bot Pois o Mesmo tem menor complexidade de Fluxos , e é um Bot Feito pra Teste. A idéia é passar a referência da Ferramenta pra Frente.


