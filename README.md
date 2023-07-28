# Requisições GET e POST

<div align="center">Este é um projeto desenvolvido no âmbito de um curso da Alura, intitulado "JavaScript: criando requisições".</div>

<br>

O objetivo principal do projeto é tornar a lista de vídeos na página inicial dinâmica, permitir o upload de novos vídeos e implementar uma ferramenta de busca. Para isso, foram instalados o NodeJS e o json-server, simulando uma API para interagir com requisições GET e POST. O curso também abordou conceitos de JavaScript assíncrono, essenciais para a construção das APIs, e introduziu a funcionalidade de pesquisa.

|:placard: Vitrine.Dev |                                                | 
| -------------------- | -----------------------------------------------|
| :sparkles: Nome      | **Requisições**                                |
| :label: Tecnologias  | Javascript, NodeJS e Json-server               |
| :rocket: URL         |https://criando-requisicoes-nayrabra.vercel.app/|
| 🧰 Propriedade       | Flexbox                                        |
| 💻 Responsividade    | Celular, Tablet e Desktop                      |

## Principais Características:

* Criar requisições GET para consumir a API, e retornar seus dados.

* Para permitir o envio de vídeos, foi necessário estruturar requisições do tipo POST usando 'method, headers e body' com o fetch API. Para enviar os dados, eles precisam ser transformados em uma string, e para isso, foi utilizado o JSON.stringify. Essa abordagem possibilitou a criação de uma solicitação POST eficiente para o envio dos vídeos.

* Implementação de pesquisa, como demonstrado no screenshot abaixo com a pesquisa 'mobile'. Para realizar a pesquisa, foi criada uma lista filtrada que remove todos os outros itens da lista, exceto o que foi pesquisado. Essa filtragem é feita usando a propriedade 'removeChild' e um laço de repetição 'while'.

* Para melhorar a experiência do usuário, foi adicionado o tratamento de erros com 'try catch', exibindo mensagens adequadas em caso de falhas durante a execução do código. Como pode ser visto no screenshot abaixo, ao ser modificar a url do fetch API, por exemplo.
  
## Screenshots

<img width="750" alt="tela desktop do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/f80ffec5-4b50-4bf0-b133-ca2b07518f14#vitrinedev">
<img width="750" alt="tela desktop do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/be1daf5e-e3a2-48a5-b5f1-9c837624c994">
<img width="750" alt="tela de busca do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/e49edcc2-4697-4fba-8687-d1883d64ea7d">
<img width="750" alt="tela de busca do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/ac0a059b-6be2-4815-a7f0-f0e4f213bc22">


<hr>

<img width="250" alt="tela mobile do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/cd327b04-9710-46a4-988c-29ec48d89ab8">
<img width="250" alt="tela mobile do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/85b40bbe-1625-4ef2-9d69-fba6712511e8">
<img width="250" alt="tela mobile do AluraPlay" src="https://github.com/nayrabra/criando-requisicoes/assets/102299426/d7c83e2f-dcca-4ed6-80b7-e196065c113e">

## Feito por:

**Nayra Braga Barbosa**

Linkedin: https://www.linkedin.com/in/nayra-barbosa/




