# Automatic Detection of Performance Bugs in Database Systems using Equivalent Queries


X. Liu, Q. Zhou, J. Arulrai and A. Orso, "Automatic Detection of Performance Bugs in Database Systems using Equivalent Queries," 2022 IEEE/ACM 44th International Conference on Software Engineering (ICSE), Pittsburgh, PA, USA, 2022, pp. 225-236, doi: [10.1145/3510003.3510093](https://doi.org/10.1145/3510003.3510093)


## 1. Fichamento de Conteúdo


O artigo aborda a detecção automática de bugs de desempenho em sistemas de gerenciamento de banco de dados (DBMSs), um problema frequentemente negligenciado em comparação com bugs funcionais. Para resolver essa questão, os autores propõem o AMOEBA, uma ferramenta que identifica discrepâncias significativas no tempo de execução de consultas semanticamente equivalentes, sugerindo possíveis falhas de desempenho. O método utiliza regras de mutação estrutural e de expressão para gerar consultas equivalentes e um mecanismo de feedback que melhora a eficiência da detecção. A técnica foi aplicada aos DBMSs PostgreSQL e CockroachDB, resultando na descoberta de 39 potenciais bugs, dos quais 6 foram confirmados por desenvolvedores e 5 já corrigidos. O artigo demonstra a importância de testar não apenas a funcionalidade, mas também o desempenho dos DBMSs, evidenciando que otimizações ineficientes podem impactar significativamente a experiência do usuário. O uso de consultas equivalentes como oráculo de desempenho se mostra eficaz, sugerindo que abordagens automatizadas podem complementar os métodos tradicionais de testes.

## 2. Fichamento Bibliográfico 


* **Bugs de Performance** são erros que impactam o tempo de execução das consultas em um Sistema de Gerenciamento de Banco de Dados (DBMS).
* **_AMOEBA_** é a ferramenta proposta para detectar bugs de performance em DBMSs, baseada na geração e mutação de consultas equivalentes.
* **Consultas Mutantes** são consultas derivadas de uma consulta base através de regras de mutação que preservam a semântica.
* **_CockroachDB_** é um dos DBMS avaliados pelo AMOEBA.
*	**_PostgreSQL_** é um DBMS avaliados pelo AMOEBA.
* **_SQLSmith_** é uma ferramenta para a geração aleatória de consultas SQL.

## 3. Fichamento de Citações 


* _"Besides functional bugs, however, there is another important class of faults that negatively affect the response time of a DBMS, known as performance bugs. Despite their potential impact on end-user experience, performance bugs have received considerably less attention than functional bugs."_
* _"Database management systems (DBMSs) play a critical role in modern data-intensive applications. For this reason, developers extensively test these systems to improve their reliability and accuracy."_
* _"Detecting performance bugs is just as crucial as detecting functional bugs, as delayed responses from the DBMS can dramatically affect the user experience"_
* _"A performance bug is a bug that affects the time taken by the DBMS to process certain queries."_

