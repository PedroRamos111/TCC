# Relational Database Performance Comparation


D. S. Gudilin, A. E. Zvonarev, B. S. Goryachkin and D. A. Lychagin, "Relational Database Performance Comparation," 2023 5th International Youth Conference on Radio Electronics, Electrical and Power Engineering (REEPE), Moscow, Russian Federation, 2023, pp. 1-5, doi: [10.1109/REEPE57272.2023.10086872](https://doi.org/10.1109/REEPE57272.2023.10086872)


## 1. Fichamento de Conteúdo


O artigo "Relational Database Performance Comparation" analisa o desempenho dos bancos de dados relacionais PostgreSQL, MySQL e MS SQL, utilizando métricas de tempo de execução de consultas sob diferentes condições. Os autores investigam a variação do tempo de execução de consultas com base no número de operadores, colunas e registros, buscando compreender qual banco de dados oferece melhor desempenho em diferentes cenários. Os experimentos mostraram que, para pequenos volumes de dados, o PostgreSQL apresenta melhor tempo de resposta. No entanto, o MS SQL tem o maior aumento de tempo de execução à medida que o número de colunas cresce. O estudo destaca a importância da otimização de consultas e da escolha adequada do banco de dados para diferentes aplicações, considerando aspectos como estrutura interna de processamento e métodos de indexação. Os autores concluem que, embora todos os bancos de dados testados operem dentro do desempenho esperado para pequenos conjuntos de dados, as diferenças de desempenho tornam-se mais evidentes à medida que o volume de informações cresce.

## 2. Fichamento Bibliográfico


* **Desempenho de bancos de dados relacionais:** O estudo compara os tempos de execução de consultas nos bancos de dados PostgreSQL, MySQL e MS SQL sob diferentes condições.
* **Critérios de comparação:** Os testes analisaram o impacto do número de registros, operadores e colunas no tempo de execução.
* **Otimização e estrutura interna:** A pesquisa sugere que diferenças no mecanismo de execução e otimização de consultas afetam o desempenho final.

## 3. Fichamento de Citações


* _"With small amounts of data, PostgreSQL is the most preferred option for use, since it is the fastest to process information."_
* _"MS SQL has the largest rate increment when increasing the number of columns from all databases under investigation."_
* _"The total query execution time under any conditions does not exceed 1.2 seconds, which corresponds to the perception time of one element, so this time is not critical when analyzing data."_
* _"Thus, the formulas can be considered valid (adequate) and used in other data, while the general tendency of increasing the cost of queries depending on the number of rows will be repeated."_
