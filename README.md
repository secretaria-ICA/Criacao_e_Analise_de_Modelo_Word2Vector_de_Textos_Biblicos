# Criação e Análise de Modelo Word2Vector de Textos Bíblicos 

#### Aluno: Bruno Cordeiro Paes (https://github.com/brunocopa).
#### Orientador: Felipe Borges(https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- (https://github.com/brunocopa/Projeto-Final-BI-Master-PUC-Rio). 

---

### Resumo


Atualmente, o algoritmo Word2Vec é o método mais eficiente para construção de Embeddings, a partir de um corpus de texto. Foi desenvolvido por Tomas Mikolov em 2013. Essa abordagem embedding permite a aprendizagem do significado/contexto das palavras, pois durante o treinamento cada palavra é definida por ela mesma e por aquelas que a acompanham. Dessa forma, as palavras são representadas de forma matemática em um vetor númerico. 

A proposta deste trabalho foi criar embeddings a partir do método word2vec de textos bíblicos e realizar uma análise dos dados bíblicos e de simularidade e visualização das embeddings.

Neste trabalho foram desenvolvidos os seguintes módulos:
- Algoritmo em Python para obteção dos dados dos versículos bíblicos utilizando a API https://bibleapi.co/ (bíblia digital). 

https://github.com/brunocopa/Projeto-Final-BI-Master-PUC-Rio/blob/main/01%20-%20BuscaDadosBiblia.ipynb

- Algoritmo em Python para análise dos dados bíblicos, criação do modelo word2vec e algumas aplicações com as embeedings criadas (similaridade e projector embeendings). Utilizou-se a bibliotecas NLTK e GENSIN como base para construção dos modelos e análise de textos.

https://github.com/brunocopa/Projeto-Final-BI-Master-PUC-Rio/blob/main/02%20-%20AnaliseDadosBibliaEmbeedings.ipynb


---

Matrícula: 192.671.025

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
