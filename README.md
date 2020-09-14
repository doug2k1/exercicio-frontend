# Exercício Frontend

O objetivo deste desafio é construir uma página html responsiva conforme o design proposto e carregar a parte dinâmica do conteúdo a partir de um serviço REST.

## Preparação

**Pré-requisitos**: possuir Node.js e NPM instalados na sua máquina.

Faça um *fork* deste repositório e clone seu *fork* para a sua máquina para começar a trabalhar.

Execute `npm install` na raiz do projeto para instalar as dependências.

Execute `npm start` para rodar o servidor local em http://localhost:3000.

## Tarefas

1. Construir o html/css conforme o design proposto, localizado na pasta `design`. A página deve ser responsiva e se adaptar à largura da tela. O arquivo HTML já se encontra em `public/index.html`, mas atualmente vazio.

O resultado não precisa ser *pixel perfect*. Procure fazer o mais próximo possível do design. 

2. Preencher a seção **Latest Projects** com informações carregadas via AJAX de http://localhost:3000/projects, que retorna um JSON com os dados necessários. O primeiro projeto retornado no *array* deve ser exibido como o projeto destaque, com a foto grande, e os demais mostrados abaixo.

Lembre-se de ir *comitando* suas alterações e fazendo *push* para seu repositório, que é o que será avaliado.

## Instruções

- **Navegadores**: A página deve ser compatível com navegadores modernos. Vamos avaliar usando a versão mais recente do Chrome.

- **Imagens**: As imagens a ser usadas no layout já se encontram em `public/img`.

- **CSS**: Pode ser usado CSS *puro* ou qualquer pré-processador como *Sass* ou *Less*. Vai da sua escolha.

- **Fontes**: O design usa a fonte [Montserrat](https://fonts.google.com/specimen/Montserrat) nos títulos. Ela pode ser carregada diretamente do **Google Fonts** (não precisa copiar para o projeto).
  - Título principal: Montserrat, 38px, bold
  - Subtítulo: Arial, 24px, normal
  - Título de seção: Montserrat, 24px, bold
  - Texto normal: Arial, 16px, normal
  - Nome do projeto em destaque: Montserrat, 20px, bold
  - Nome dos demais projetos: Montserrat, 18px, bold

- **JS**: O código JS deve usar alguma funcionalidade da versão ES6 ou superiores (no mínimo deve usar `const` e `let` para declarar variáveis).

- **Framework JS**: A implementação deve utilizar o framework *React*. 

- **State Management**: A implementação deve utilizar o *Redux*.

- **HTML**: Dê preferência para escrita de HTML semântico.

- **Module bundler**: O código JS deve ser transpilado para ES5 e *empacotado* usando algum *module bundler* como **Webpack** (de preferência). 

- **Dependências**: Todas as dependências usadas devem ser adicionadas ao `package.json`.
