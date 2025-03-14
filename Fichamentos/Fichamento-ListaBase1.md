# An Empirical Study on Quality Issues of eBay's Big Data SQL Analytics Platform


F. Zhu et al., "An Empirical Study on Quality Issues of eBay's Big Data SQL Analytics Platform," 2022 IEEE/ACM 44th International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP), Pittsburgh, PA, USA, 2022, pp. 33-42, doi: [10.1145/3510457.3513034](https://doi.org/10.1145/3510457.3513034)

‌
## 1. Fichamento de Conteúdo


O artigo "An Empirical Study on Quality Issues of eBay’s Big Data SQL Analytics Platform" investiga os problemas de qualidade enfrentados pela plataforma de análise SQL baseada em Big Data da eBay, chamada Carmel. A plataforma, construída sobre o Apache Spark, suporta análises interativas de dados para milhares de usuários. No entanto, a complexidade do ambiente de Big Data e a interoperabilidade de múltiplos componentes de código aberto resultam em diversos problemas de qualidade, incluindo falhas de jobs, lentidão na execução de consultas e erros nos resultados. O estudo analisa 1.884 problemas reais ocorridos ao longo de um ano, classificando-os em três categorias principais: falhas de jobs (57,7%), lentidão na execução (37,36%) e resultados incorretos (4,94%). Os autores identificam três causas principais para esses problemas: falhas do usuário (14,54%), defeitos internos do sistema (46,02%) e incompatibilidades entre componentes da plataforma (39,44%). O estudo propõe melhorias para a detecção de antipadrões em SQL, otimização de planos de execução, gestão eficiente de dados e recursos, além de ferramentas avançadas para diagnóstico e reprodução de falhas. As descobertas visam beneficiar desenvolvedores, mantenedores da plataforma e pesquisadores interessados na confiabilidade de sistemas de análise de Big Data.

## 2. Fichamento Bibliográfico


* **Problemas de qualidade em plataformas SQL de Big Data:** Falhas em jobs, lentidão e resultados incorretos afetam a experiência dos usuários e a confiabilidade do sistema.
* **Classificação das causas dos problemas:** 14,54% dos erros são devido a falhas do usuário, 46,02% a defeitos internos da plataforma e 39,44% a incompatibilidades entre componentes.
* **Antipadrões em SQL:** Usuários frequentemente cometem erros como a má utilização de joins, padrões ineficientes de consulta e configuração inadequada de parâmetros.
* **Desafios no planejamento de consultas:** A conversão de consultas para planos físicos pode ser ineficiente devido a regras incorretas, estatísticas desatualizadas e otimizações limitadas.
* **Impacto da gestão de dados e recursos:** Pequenos arquivos, dados intermediários excessivos e desalinhamento na distribuição de tarefas impactam negativamente a performance do sistema.
* **Necessidade de ferramentas automatizadas:** São recomendadas soluções para análise automática de consultas, ajuste dinâmico de configurações e melhor gestão de recursos para minimizar falhas e melhorar o desempenho.


## 3. Fichamento de Citações


* _"The platform quality issues manifest as more than 15 main symptoms and can be classified into three categories: Job Failure (57.7%), Job Slowness (37.36%) and Wrong Result (4.94%)."_
* _"Finding 2: The root causes can be classified into three primary categories: 14.54% issues are caused by User Side Faults, 46.02% caused by System Internal Defects in Carmel-Spark during the query planning and execution, and 39.44% caused by Platform Component Mismatches among different open-source components."_
* _"More than 70% user-side faults caused by SQL anti-patterns, including code smells, low performant queries, ambiguous operators, and inefficient data mode design."_
* _"It is possible to take advantage of historical execution metrics and design advanced dynamic models with machine learning techniques to improve query optimization."_
