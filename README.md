Foregon Front End Developer
============================

###### Se você acha que pode fazer a diferença em um mundo 100% digital, venha fazer parte do nosso time.

###### Somos um grupo de pessoas inquietas, apaixonadas por inovação, marketing e pelo mundo digital. Nós acreditamos que as coisas sempre podem ser feitas de um jeito mais inteligente, criativo e disruptivo. Já somos o maior marketplace de produtos financeiros do Brasil e ainda queremos crescer muito mais.

Orientações
-----
* Faça um fork desse projeto para a sua conta pessoal do GitHub, ou BitBucket;
* Crie uma branch (pode ser com seu nome mesmo);

Depois do seu setup você precisará seguir as seguintes instruções, para construir a aplicação:

1. Desenvolver a página nas versões *mobile* e *desktop*, que tem seu layout em https://zpl.io/bL56P8Q;

  * Solicite invite para o projeto

2. Crie um módulo JavaScript para construir as integrações com a API REST;
  
Propriedade | Propriedade na API 
--- | ---
Nome do cartão | name
Imagem do cartão | imageUrl
Anuidade | firstAnnuity.textFormatted
Renda mímina | valueOfMinimalIncomeRequired
Avaliações | rating.total_reviews
Avaliações | rating.average_score

  * As informações acima devem ser construidas à partir da consulta na API: https://www.foregon.com/api/v3/groups/productid/1623
  
4. Crie um README para documentação do projeto;
3. **Não submeta o Pull Request**, envie um link do seu repositório para murilo.siqueira@foregon.com

Critérios de avaliação
-----
* Semântica Web;
* CSS;
* JS;
* Fidelidade ao layout;
* Acessibilidade;
* Design Responsivo;
* Integração API REST;

Bônus
-----
* ES6/7/8;
* Testes e documentação
* Código modular;
* Performance;
* Aplicação de médotologias css, preferencialmente BEM CSS;
* Aplicação de ferramentas, sejam elas transpiladores, pré-processadores, task-runners, bundles, etc.
