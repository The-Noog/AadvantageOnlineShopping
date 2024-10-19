Olá aqui está o passo a passo de como realizar os testes usando a ferramenta Cypress.

Primeiro você deve baixar os arquivos deste repositório na sua máquina.

Crie uma pasta para a instalação do Cypress

Clicle com o botão direito do mause e use a opção "Git Bash Here", caso você não tenha o git, instale na sua máquina usando o link: "https://git-scm.com/downloads"

No terminal, dê os seguintes comandos de cada vez

-------------------------------------------
npm init (Vai dando Enter até aparece ok)
------------------------------------------
Instalando o Cypress

npm install cypress --save-dev (Aguarde a instalação)
--------------------------------------------

Para abrir o Cypress

npx cypress open (para abrir o cypress)
-----------------------------------------------

Assim que o Cypress abrir, escolha a opção **E2E Testing** e clica em **continue**

Copie os arqivos **compraLogin.cy.js** e** desafioAPI-GET.cy.js** e coloca na pasta que foi instalada o cypress, na pasta Cypress -> 
e2e

Seleciona um navegador de sua preferência e clica em Start E2E Testing in...

Procure pelos arquivos **compraLogin.cy.js** e** desafioAPI-GET.cy.js** e clica em um deles para que os testes sejam realizados e pronto, está feito os testes :)
