# An Empirical Study on Quality Issues of eBay


ZHU, F. et al. An empirical study on quality issues of eBay’s big data SQL analytics platform. Proceedings of the 44th International Conference on Software Engineering: Software Engineering in Practice, 21 maio 2022.

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
