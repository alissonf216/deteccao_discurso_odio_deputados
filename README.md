
# Estudo sobre PLN e Identificação de Discursos Ofensivos em Contextos Políticos

## Palavras-chave
`#python` `#pln` `#pnl` `#randomforest` `#naiveBayes` `#SVM` `#regressão`

## Resumo
Este estudo explora a aplicação de técnicas avançadas de **Processamento de Linguagem Natural (PLN)** na identificação de discursos de ódio e ofensivos em falas de deputados federais brasileiros. Utilizou-se uma base de dados composta por discursos parlamentares, na qual foi implementado e comparado quatro algoritmos de aprendizado de máquina - **Naive Bayes**, **SVM (Support Vector Machines)**, **Random Forest** e **Logistic Regression** - com vetorização via técnica de **TF-IDF (Term Frequency-Inverse Document Frequency)**.

### Avaliação de Desempenho dos Algoritmos
Os algoritmos foram avaliados com base em suas métricas de desempenho, onde o **SVM** se destacou com um **f1-score** de `0.97` para a label 0 (não ofensivo) e `0.97` para a label 1 (ofensivo).

### Ajuste de Hiperparâmetros e Resultados
Aplicou-se o **GridSearchCV** para o ajuste de hiperparâmetros de todos os modelos e cross validação. Os resultado evidencia a eficácia na classificação precisa de discursos ofensivos, contribuindo significativamente para a moderação e análise de conteúdo em contextos políticos.

### Visualização de Dados: Nuvem de Palavras do Dataset

Esta seção apresenta uma **Nuvem de Palavras** gerada a partir do nosso dataset. A Nuvem de Palavras é uma ferramenta visual útil para compreender a distribuição e a frequência das palavras mais comuns nos discursos analisados. Ela oferece uma pré-visualização intuitiva e impactante, destacando as palavras que surgem com mais frequência e, assim, fornecendo insights iniciais sobre os temas e o vocabulário predominantes no conjunto de dados.

#### Nuvem com stopwords
![Insira a imagem aqui](https://github.com/alissonf216/deteccao_discurso_odio_deputados/blob/main/img/nuvem_hate_com_stopw.png)

#### Nuvem sem stopwords
![Insira a imagem aqui](https://github.com/alissonf216/deteccao_discurso_odio_deputados/blob/main/img/nuvem_hate.png)

Este tipo de visualização é particularmente valioso para identificar rapidamente os termos chave e as tendências linguísticas presentes nos discursos, auxiliando na estruturação e direcionamento das análises subsequentes de Processamento de Linguagem Natural.




### Conclusão
Este trabalho não só demonstra a aplicabilidade do PLN na análise de discursos políticos, mas também destaca a importância de técnicas de aprendizado de máquina na identificação de linguagem ofensiva e de ódio, contribuindo para um ambiente político mais saudável e respeitoso.

![Insira a imagem aqui](https://github.com/alissonf216/deteccao_discurso_odio_deputados/blob/main/img/matriz_svm_otimizada.png)

Palavras-chave: Processamento de linguagem natural, aprendizado de máquina, Discurso de ódio, classificação, Discurso Político.
