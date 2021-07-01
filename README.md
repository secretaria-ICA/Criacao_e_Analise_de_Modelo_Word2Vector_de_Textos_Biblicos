# Criação e Análise de Modelo Word2Vector de Textos Bíblicos 

#### Aluno: Bruno Cordeiro Paes (https://github.com/brunocopa).
#### Orientador: Felipe Borges(https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- (https://github.com/brunocopa/Projeto-Final-BI-Master-PUC-Rio). 

---

### Resumo


Atualmente, o algoritmo Word2Vec é o método mais eficiente para construção de Embeddings, a partir de um corpus de texto. Foi desenvolvido por Tomas Mikolov em 2013. Essa abordagem embedding permite a aprendizagem do significado/contexto das palavras, pois durante o treinamento cada palavra é definida por ela mesma e por aquelas que a acompanham. Dessa forma, as palavras são representadas de forma matemática em um vetor numérico. 

A motivação deste trabalho foi criar embeddings a partir do método word2vec de textos bíblicos e realizar uma análise dos dados bíblicos, de similaridade e visualização das embeddings. 

A primeira etapa deste trabalho foi criar um algoritmo em Python para obtenção dos dados dos versículos bíblicos utilizando uma API que disponibiliza versões dos textos bíblicos. Essa etapa resultou na criação de um dataset composto por todos versículos organizados por nome do livro, número do capítulo e número do versículo organizado de forma estruturada em um arquivo csv.

A segunda etapa deste trabalho foi criar algoritmo em Python para fazer o pré-processamento dos versículos bíblico. Foi inicialmente tokenizado os versículos em palavras, transformando todas em minúsculas e removendo stop words. Além disso, foi realizada uma análise dos versículos através de wordclouds e histogramas de distribuição dos comprimentos dos versículos e palavras.

A última etapa deste trabalho foi criar outro algoritmo em Python para criação do modelo word2vec de 100 dimensões com o corpus bíblico obtido e a realização de aplicações com as embeedings criadas, por exemplo similaridade de cossenos entre versículos e palavras, além da geração da visualização projector embeedings. Utilizou-se as bibliotecas NLTK e GENSIN como base para construção dos modelos e análise de textos.

Os resultados encontrados demonstraram que o pré-processamento foi efetivo para a aplicação dos métodos de treinamento das embeendings, retirando palavras sem valor significativo para o contexto. Além disso, foi possível com este trabalho criar um modelo word2vec para textos bíblicos e ser possível realizar avaliações de contexto e algumas aplicações de NLP com resultados satisfatórios. 


---

Matrícula: 192.671.025

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
