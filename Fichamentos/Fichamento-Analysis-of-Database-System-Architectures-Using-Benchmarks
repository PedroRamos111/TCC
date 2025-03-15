# Analysis of Database System Architectures Using Benchmarks

Yao, S. Bing; Hevner, Alan R.; Young-Myers, Helene. "Analysis of Database System Architectures Using Benchmarks," in IEEE Transactions on Software Engineering, vol. SE-13, no. 6, pp. 709-722, June 1987. doi: [10.1109/TSE.1987.233379](https://doi.org/10.1109/TSE.1987.233379)

## 1. Fichamento de Conteúdo

O artigo analisa arquiteturas de sistemas de banco de dados, comparando o desempenho de um sistema convencional e de uma máquina de banco de dados por meio de benchmarks. A pesquisa busca avaliar se a arquitetura de máquina de banco de dados é uma alternativa viável para melhorar a performance e modularidade. Foram realizados experimentos com diferentes tamanhos de banco de dados e workloads, considerando métricas como tempo de resposta para a primeira e última tupla. Os resultados mostraram que a máquina de banco de dados tem melhor desempenho no tempo total de resposta, especialmente em consultas que retornam grandes volumes de dados, enquanto o sistema convencional tem vantagem no tempo de resposta para a primeira tupla. O estudo também revelou que a velocidade da linha de comunicação entre o host e a máquina de banco de dados impacta significativamente a performance. Além disso, a presença de cargas de trabalho de fundo prejudica muito mais o sistema convencional do que a máquina de banco de dados, destacando uma vantagem significativa da arquitetura especializada.

## 2. Fichamento Bibliográfico

* **Tempo de resposta** foi dividido em _time-to-first_ (tempo até a primeira tupla ser retornada) e _time-to-last_ (tempo até a última tupla ser retornada), permitindo uma análise mais detalhada do desempenho (página 714).
* **Impacto da velocidade da linha de comunicação** foi analisado e mostrou que a latência na transmissão de dados afeta a eficiência da máquina de banco de dados (página 721).
* **Uso de índices** melhorou significativamente o desempenho das consultas que filtravam por atributos indexados, reduzindo o tempo de resposta (página 716).
* **Carga de fundo** impacta diretamente os sistemas convencionais, pois todos os processos compartilham os mesmos recursos da CPU e I/O, enquanto a máquina de banco de dados foi pouco afetada (página 720).
* **Comparativo de arquiteturas** demonstrou que, enquanto a máquina de banco de dados possui melhor performance geral, sua confiabilidade pode ser menor devido à dependência de dois sistemas (host e máquina de banco de dados) (página 721).

## 3. Fichamento de Citações

* _"The response time of database requests is affected by two factors: transmission of messages and data to/from the database machine and the specialized efficiencies of the hardware and software in the database machine."_
* _"Database machines demonstrate significant performance advantages in handling large query workloads, particularly when the volume of retrieved data is high."_
* _"The speed of the communication line between the host computer and the database machine plays a critical role in overall system performance."_
* _"Increasing the number of concurrent users results in a linear increase in query response time for both conventional database systems and database machines."_
* _"While background workloads significantly degrade conventional database performance, database machines remain largely unaffected due to their architectural separation."_
* _"Our benchmark experiments confirm that indexing greatly improves performance, but some queries do not benefit from it, particularly when disjunctive conditions are present."_

