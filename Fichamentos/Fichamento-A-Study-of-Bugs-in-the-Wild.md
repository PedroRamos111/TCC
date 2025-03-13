# How not to Structure Your Database-Backed Web Applications: A Study of Performance Bugs in the Wild


J. Yang, C. Yan, P. Subramaniam, S. Lu and A. Cheung, "How not to Structure Your Database-Backed Web Applications: A Study of Performance Bugs in the Wild," 2018 IEEE/ACM 40th International Conference on Software Engineering (ICSE), Gothenburg, Sweden, 2018, pp. 800-810, doi: [10.1145/3180155.3180194](https://doi.org/10.1145/3180155.3180194)


## 1. Fichamento de Conteúdo


O artigo "How Not to Structure Your Database-Backed Web Applications: A Study of Performance Bugs in the Wild" analisa problemas de desempenho em aplicações web que utilizam bancos de dados relacionais e frameworks de mapeamento objeto-relacional (ORM). Os autores realizam um estudo empírico sobre 12 aplicações reais baseadas no framework Ruby on Rails, identificando padrões problemáticos de desempenho (chamados de performance anti-patterns) e suas causas. O estudo se baseia na análise de 200 problemas reportados em sistemas de rastreamento de bugs e em testes de desempenho das versões mais recentes das aplicações. Os pesquisadores classificam os problemas em três categorias principais: mau uso das APIs ORM, falhas no design do banco de dados e decisões inadequadas de design da aplicação. Os resultados mostram que a maioria dos problemas de desempenho pode ser corrigida com poucas alterações no código, levando a melhorias significativas na velocidade de execução. Além disso, os autores propõem um conjunto de técnicas para detectar e corrigir esses problemas de forma automatizada, destacando a importância de ferramentas de análise estática e otimização de consultas. O estudo conclui que o uso inadequado de ORM pode levar a ineficiências severas e que, embora existam boas práticas para evitar esses problemas, muitas aplicações continuam a sofrer com falhas de desempenho devido à falta de conscientização dos desenvolvedores sobre o impacto de suas escolhas.

## 2. Fichamento Bibliográfico


* **Desempenho de aplicações web com ORM:** O estudo examina problemas de desempenho comuns em aplicações que utilizam frameworks ORM, como Ruby on Rails.
* **Categorias de problemas identificados:** Os autores classificam os problemas em três tipos: mau uso de APIs ORM, falhas de design do banco de dados e trade-offs no design da aplicação.
* **Principais padrões problemáticos:** São identificados nove anti-patterns, incluindo carregamento ineficiente de dados (N+1 query problem), consultas desnecessárias, indexação inadequada e renderização ineficiente.
* **Impacto das falhas de desempenho:** Muitas aplicações possuem páginas que demoram mais de 2 segundos para carregar, afetando a experiência do usuário e a escalabilidade do sistema.
* **Correções e otimizações:** Ajustes simples no código podem melhorar significativamente a performance, com ganhos médios de 2× e, em alguns casos, até 39× na velocidade de execução.
* **Ferramentas para detecção automática:** Os autores sugerem o uso de análise estática e técnicas de otimização para identificar automaticamente problemas de desempenho.

## 3. Fichamento de Citações

* _"We generalize 9 ORM performance anti-patterns from more than 200 performance issues that we obtain by studying their bug-tracking systems and profiling their latest versions."_
* _"11 out of 12 studied applications contain pages in their latest versions that take more than two seconds to load and also pages that scale super-linearly."_
* _"By writing code that contains the anti-patterns discussed earlier, developers degrade the performance of their applications by about 6×."_
* _"Our fixes achieve 2× median speedup (and up to 39×) in server-side performance improvement, and reduce the average end-to-end latency of 39 problematic web pages in 12 applications from 4.17 seconds to 0.69 seconds."_
