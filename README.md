# Desafio Web Fullstack
![logo-rissi](imagens/Logo%20Rissi.png)


Entre para o time dos **#Rissianos**

A Rissi Contabilidade Médica está sempre crescendo assim como nosso time dos **#Rissianos**. Se o que te move é fazer a diferença e trabalhar em um time que joga junto, então vem contabilizar histórias com a gente.

# Por que trabalhar conosco?

Gosta de desafios em um lugar agradável e cheio de benefícios? Vem com a gente!

### Buscamos pessoas que:
- São obcecadas por fazer o melhor pelos clientes
- Tenham a cultura de dono da empresa
- Que jogam pelo time
- Que buscam em criar uma carreira                                                                                                                                                                                                      
# Desafio
O objetivo do desafio é avaliar o candidato em áreas como: lógica de programação; conhecimento em linguagem orientada a objeto; C# ou Javascript/Typescript; ASP.NET Core ou Node.js; React.js, Vue.js, Next.js ou Angular.js; APIs REST; e banco de dados NoSQL ou SQL. Não há somente um jeito certo de realizar esse desafio, há várias maneiras de resolvê-lo, e cabe a você achar a melhor solução!

## Como devo realizar o desafio?
Você deve ler as instrucões abaixo de como realizar o desafio, e dependendo da sua escolha, pode ser feito um monorepo ou 2 repositorios. Apos a finalização, so mandar o link, ou links, do repositorio para avaliação para esse email: **dev01@rissicontabilidade.com.br**.

## O problema
Precisamos que você desenvolva um site que cadastre, retorne, altere e exclua carros que serão armazenados em um banco de dados. Nesse cadastro de carros, a estrutura ja sera providenciada abaixa com um dump do MongoDB ou SQL para uso no banco de dados. E, como esses dados são confidenciais, essa API não pode ser publica, então ela tem que ter uma autenticação previa para poder ser usada.

## Requisitos Mínimos para a API
- Geral
  - O backend deve ser feito em C# usando ASP.NET Core 5, ou Javascript/Typescript com Node.js na sua ultima versão LTS, outras linguagens ou tecnologias não serão aceitas.
  - O frontend deve ser feito em React.js, Vue.js ou Next.js. Angular.js será aceito tambem, mas os 3 primeiros são mais preferidos.
  - O repositorio fornece um dump do MongoDB ou um SQL para ter alguns dados mockados, assim como no caso do SQL montar a estrutura do banco.
  - Todos os dados confidenciais da aplicação, como: connection strings, secrets, etc; Devem ser salvas em arquivo de ambiente (ex.: appsettings.json), e não devem ser providenciadas na finalização do desafio. 
- Autenticação em JWT ou OAuth
  - As tabelas que iram guardar os dados de autenticação ficam de livre escolha do desenvolvedor para serem modeladas do jeito que preferirem.
  - Não há necessidade de implementar autorização, somente autenticação.
- Carros
  - Essa rota deve ter todas as operações para se realizar um CRUD.
  - O campo de Categoria deve ser um Enum com os seguintes valores: ['Hatch', 'Sedan', 'SUV', 'Utilitario', 'Picape'].
- Banco de dados
  - O banco de dados desejável é o MongoDB, mas caso prefira, qualquer outro banco relacional sera aceito. O uso do MongoDB é um **diferencial**.
  - A tabela de Carros tem que ter os modelos especificados abaixo.

## Modelos do banco
### Carros
```json
{
  "Nome": "string",
  "Eixos": "int",
  "Categoria": "enum",
  "TamanhoPortaMalas": "int",
  "Preco": "decimal",
  "Portas": "int",
  "CreatedAt": "datetime",
  "UpdateAt": "datetime"
}
```

Qualquer dúvida, sugestão ou problema que encontrar, entre em contato criando uma issue aqui neste repositório ou nesse e-mail: **dev01@rissicontabilidade.com.br**. **Iremos te ajudar no que precisar!**
Boa sorte e até breve!

> Tente uma, duas, três vezes e se possível tente a quarta, a quinta e quantas vezes for necessário. Só não desista nas primeiras tentativas, a persistência é amiga da conquista. Se você quer chegar onde a maioria não chega, faça o que a maioria não faz.
> - Bill Gates
