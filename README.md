![portaldetodos](https://cartaodetodos.com.br/assets/images/logo.png)

Desafio técnico Python
======================

Alguns requisitos
-----------------
  - Deixe o código em inglês
  - Use Git;
  - Procure fazer "micro commits" que são muitos commits com menos código isso nos ajuda a compreender a sua lógica;
  - Nos pergunte sobre qualquer dúvida que venha a surgir durante o desenvolvimento;
  - Documente detalhadamente quaisquer referencias/ferramentas que vc pesquisar;
  - Crie um repositório público e nos passe o link para acompanharmos o desenvolvimento.

Problema
--------

A CREDTODOS LTDA está lançando um sistema inovador de cadastros de clientes e precisa garantir toda a qualidade e padronização dos dados.
E esse sistema será uma API simples de cadastro de clientes, e o sistema irá receber no cadastro:
```shell
NOME
EMAIL
TELEFONE
CEP
NUMERO
COMPLEMENTO
CPF
```

Como não é um cadastro qualquer, esses dados precisam passar por uma validação específica:

- EMAIL: Se é uma email válido e não existe na base
  - 1

- TELEFONE: Se é um telefone válido
- CEP: Verificar se o cep existe, caso existir, salvar os dados complementares
- NUMERO e COMPLEMENTO: não são obrigatórios
- CPF: verificar se o valor é válido

A api deve conter basicamente as urls (sugestão):
```shell
  GET  /api/v1/customers - listar os clientes
  GET  /api/v1/customers/<key> - detalhe do clientes
  POST /api/v1/customers - cadastrar um novo cliente
```
O acesso à api deve ser aberto ao mundo, porém deve possuir autenticação e autorização.

Você está livre para definir a melhor arquitetura e tecnologias para solucionar este desafio, mas não se esqueça de contar sua motivação no arquivo README que deve acompanhar sua solução, junto com os detalhes de como executar seu programa. Documentação e testes serão avaliados também =).

Nós solicitamos que você trabalhe no desenvolvimento desse sistema sozinho e não divulgue a solução desse problema pela internet.

![Luck](https://media.tenor.com/images/e026ce9d75219c8d82277ddf0558ee2b/tenor.gif)
