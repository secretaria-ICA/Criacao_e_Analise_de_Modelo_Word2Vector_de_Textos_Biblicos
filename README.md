# Criação e Análise de Modelo Word2Vector de Textos Bíblicos 

#### Aluno: Bruno Cordeiro Paes (https://github.com/brunocopa).
#### Orientador: Felipe Borges(https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- (https://github.com/brunocopa/Projeto-Final-BI-Master-PUC-Rio). 

---

### Resumo


Atualmente, o algoritmo Word2Vec é o método mais eficiente para construção de Embeddings, a partir de um corpus de texto. Foi desenvolvido por Tomas Mikolov em 2013. Essa abordagem embedding permite a aprendizagem do significado/contexto das palavras, pois durante o treinamento cada palavra é definida por ela mesma e por aquelas que a acompanham. Dessa forma, as palavras são representadas de forma matemática em um vetor númerico. 

Atualmente, para solicitação de reembolso médico (modalidade livre escolha), o usuário de posse da nota fiscal, necessita entrar num site da operadora do plano de saúde, digitar as diversas informações solicitadas (que constam na nota fiscal e que ao digitá-las, pode errar e ocasionar recusa do pedido de reembolso) e submetê-las para realizar a solicitação de reembolso.

A ferramenta desenvolvida automatiza esse processo, realizando a leitura da nota fiscal digitalizada (Manipulação e Tratamento de arquivos não estruturados), envio dos dados para solicitação do reembolso (via Web Screping) e gravação dos dados para consulta do usuário dos reembolsos solicitados (Persitência em Banco de Dados).

A ferramenta foi desenvolvida em Python, para Manipulação e Tratamento de arquivos não estruturados foi utilizado as bibliotecas OCRmyPDF e Apache Tika, no Web Screping foi utilizado Selenium e para Persistência em Banco de Dados foi utilizado a biblioteca SQLite3.

---

Matrícula: 192.671.025

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
