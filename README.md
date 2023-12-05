# Estudo sobre PLN e Identificação de Discursos Ofensivos em Contextos Políticos

![Insira a imagem aqui](link-da-imagem-1)

## Palavras-chave
`#python` `#pln` `#pnl` `#randomforest` `#naiveBayes` `#SVM` `#regressão`

## Resumo
Este estudo explora a aplicação de técnicas avançadas de **Processamento de Linguagem Natural (PLN)** na identificação de discursos de ódio e ofensivos em falas de deputados federais brasileiros. Utilizou-se uma base de dados composta por discursos parlamentares, na qual foi implementado e comparado quatro algoritmos de aprendizado de máquina - **Naive Bayes**, **SVM (Support Vector Machines)**, **Random Forest** e **Logistic Regression** - com vetorização via técnica de **TF-IDF (Term Frequency-Inverse Document Frequency)**.

### Avaliação de Desempenho dos Algoritmos
Os algoritmos foram avaliados com base em suas métricas de desempenho, onde o **SVM** se destacou com um **f1-score** de `0.95` para a label 0 (não ofensivo) e `0.94` para a label 1 (ofensivo).

![Insira a imagem aqui](link-da-imagem-2)

### Ajuste de Hiperparâmetros e Resultados
Posteriormente, aplicou-se o **GridSearchCV** para o ajuste de hiperparâmetros no modelo SVM, visto que este foi o modelo que melhor performou. Isso resultou em uma melhoria substancial, alcançando um f1-score equilibrado para ambas as labels de `0.97`. Este resultado evidencia a eficácia na classificação precisa de discursos ofensivos, contribuindo significativamente para a moderação e análise de conteúdo em contextos políticos.

### Conclusão
Este trabalho não só demonstra a aplicabilidade do PLN na análise de discursos políticos, mas também destaca a importância de técnicas de aprendizado de máquina na identificação de linguagem ofensiva e de ódio, contribuindo para um ambiente político mais saudável e respeitoso.

![Insira a imagem aqui]([link-da-imagem-3](https://github.com/alissonf216/deteccao_discurso_odio_deputados/blob/main/img/matriz_svm_otimizada.png))

Palavras-chave: Processamento de linguagem natural, aprendizado de máquina, Discurso de ódio, classificação, Discurso Político.
