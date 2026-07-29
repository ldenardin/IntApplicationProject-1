## Detalhamento ETAPA 01 — CONCEPÇÃO E PROPOSTA DE SOLUÇÃO

### 1. Visão geral da etapa 01

A Etapa 01 tem como finalidade compreender o problema que será investigado e apresentar uma proposta inicial de solução de software. Antes de iniciar a modelagem detalhada ou o desenvolvimento da aplicação, a equipe deverá conhecer o contexto, identificar as pessoas afetadas pelo problema, levantar suas necessidades e delimitar claramente o que será contemplado pelo projeto.
Ao final desta etapa, espera-se que o grupo consiga responder, no mínimo, às seguintes questões:

- Qual problema real será enfrentado?
- Em qual contexto esse problema ocorre?
- Quem é afetado por ele?
- Quais evidências demonstram que esse problema é relevante?
- Como o projeto se relaciona com os <a href="https://brasil.un.org/pt-br/sdgs"> Objetivos de Desenvolvimento Sustentável (ODS) </a>? 
- Quais necessidades dos usuários deverão ser atendidas?
- Quais funcionalidades deverão compor a solução?

- Como as necessidades identificadas serão representadas por meio de histórias de usuários, requisitos e casos de uso?

Nesta etapa, o foco está na:
- compreensão do problema
- definição do público-alvo
- delimitação do escopo
- identificação das necessidades dos usuários
- elicitação inicial dos requisitos (funcionais, não funcionais e restrições)
- modelagem dos casos de uso
- organização inicial do projeto no _GitHub Classroom_

Entretanto, a proposta deverá considerar desde o início as tecnologias obrigatórias da disciplina, pois elas estabelecem limites para a solução que será projetada e desenvolvida nas etapas seguintes.

Na Etapa 01 deverão ser desenvolvidos todos os itens descritos à seção <a href="01-Documentação de Contexto.md"> Documentação de Contexto</a> e à seção <a href="02-Especificação do Projeto.md"> Especificação do Projeto</a>

### 2. Tecnologias e ferramentas obrigatórias do projeto

Durante o desenvolvimento do projeto, todas as equipes deverão utilizar as seguintes ferramentas e tecnologias:

#### 2.1 _GitHub Classroom_

O _GitHub Classroom_ será utilizado para:
- disponibilização do repositório da equipe
- armazenamento do código-fonte
- armazenamento dos documentos e diagramas
- acompanhamento da evolução do projeto
- registro das contribuições dos integrantes
- controle de versões
- gerenciamento de alterações

O histórico do repositório deverá demonstrar a **participação efetiva** dos integrantes da equipe. Portanto, é altamente recomendado que cada estudante realize os _commits_ relacionados às suas contribuições a cada etapa.

#### 2.2 Ferramentas de modelagem

As equipes deverão utilizar ferramentas adequadas para a elaboração dos diagramas e demais artefatos de modelagem.
Poderão ser utilizadas, conforme orientação da disciplina, ferramentas como:
- <a href="https://app.diagrams.net/"> Draw.io
- <a href="https://lucid.co/pt/lucidchart"> LucidChart
- <a href="https://astah.net/"> Astah
  
E outras ferramentas, desde que, previamente autorizadas pelo(a) professor(a) que lhe acompanha semanalmente.

Os arquivos editáveis dos diagramas deverão ser mantidos no repositório, juntamente com suas versões exportadas em formato de imagem ou PDF.

#### 2.3 _Back-end_

O _back-end_ da aplicação deverá ser desenvolvido no ecossistema Microsoft.NET, utilizando, obrigatoriamente:
- Linguagem C#
- Visual Studio
- _Framework_ ASP.NET Core
- Padrão arquitetural MVC (_Model_, _View_ e _Controller_).

É altamente recomendado que a versão do _framework_ e demais configurações técnicas sejam aquelas apresentadas no microfundamento de Desenvolvimento Web Back-end.

#### 2.4 _Front-end_

O _front-end_ deverá ser desenvolvido utilizando:
- HTML
- CSS
- JavaScript (para tratamentos simples de interface)
- _Bootstrap_ (único framework permitido).

O _Bootstrap_ deverá apoiar a construção de uma interface responsiva e consistente, mas não substitui a necessidade de:

- organização adequada do HTML
- personalização por meio de CSS
- aplicação de princípios de usabilidade e acessibilidade
  
### 3. Exemplo condutor utilizado nesta orientação

Para auxiliar na compreensão dos itens, sempre que pertinente, será utilizado o projeto fictício denominado **EcoDescarte**.

O **EcoDescarte** é uma proposta de aplicação _web_ interativa responsiva destinada a apoiar o descarte ambientalmente adequado de resíduos eletroeletrônicos de uso doméstico. O problema está relacionado à dificuldade de muitas pessoas em encontrar informações confiáveis e atualizadas sobre:
- onde descartar equipamentos eletrônicos
- quais materiais são aceitos em cada ponto
- quando os pontos estão abertos
- como preparar o equipamento para o descarte
- como solicitar ou acompanhar uma entrega
- qual é o destino dado ao material entregue

Para fins didáticos, o projeto será contextualizado no município fictício de Chique-Chique de Doer / RN.
Embora o município seja fictício, o problema ambiental, a legislação, os dados e os Objetivos de Desenvolvimento Sustentável relacionados ao projeto são reais.
O exemplo foi delimitado para representar um projeto acadêmico viável. O sistema não realizará fisicamente a coleta, o transporte ou a reciclagem dos materiais. Ele apoiará a organização das informações e o registro das atividades realizadas pelas organizações responsáveis.
