# Semana 07 – Práticas DevOps

## Tema do Artigo Científico

**Uso de métricas em testes de integração para otimização do tempo de validação de mudanças em pipelines DevOps**

## Integrantes

- Gabriel Alves Pereira
- Sarah Cristina
- Matheus Emanoel

# Praticas DevOps presentes na literatura e sua relação com Métricas em Testes de Integração

| Prática DevOps | Finalidade Principal | Relação com métricas em testes de integração |   
|---|---|---|
| **Integração Contínua (CI)** | Integrar frequentemente alterações de código em um repositório compartilhado e validar automaticamente cada modificação. | Permite coletar métricas como tempo de execução dos testes de integração, taxa de sucesso dos builds, número de falhas por commit e frequência de integração, auxiliando na identificação de gargalos no pipeline. |
| **Entrega Contínua (CD)** | Automatizar a disponibilização de novas versões de software de forma rápida e confiável.| Utiliza os resultados e métricas dos testes de integração para validar a qualidade das mudanças antes da promoção para ambientes posteriores, reduzindo riscos de implantação. |
| **Testes Automatizados** | Executar verificações de qualidade automaticamente durante o ciclo de desenvolvimento. | Fornece métricas fundamentais como cobertura de testes, taxa de falhas, tempo médio de execução e quantidade de defeitos detectados, permitindo avaliar a eficiência da validação das mudanças. |
| **Observabilidade** | Disponibilizar visibilidade sobre o comportamento dos sistemas por meio de métricas, logs e rastreamentos. | Permite analisar o desempenho dos testes de integração, identificar causas de falhas recorrentes e compreender o impacto das mudanças no ambiente de execução. |
| **Monitoramento Contínuo** | Acompanhar continuamente a saúde dos sistemas e processos DevOps. | Possibilita monitorar indicadores dos testes de integração em tempo real, identificando atrasos, instabilidades e tendências que afetam o tempo de validação das alterações.                                              |
| **Métricas DORA** | Avaliar o desempenho e a eficiência dos processos DevOps. | Relaciona os resultados dos testes de integração com indicadores como Deployment Frequency, Lead Time for Changes, Change Failure Rate e MTTR, permitindo medir o impacto da qualidade dos testes na entrega de software. |
| **SRE (Site Reliability Engineering)** | Garantir confiabilidade, disponibilidade e estabilidade dos serviços. | Utiliza métricas como MTTR, taxa de falhas e cumprimento de SLOs para avaliar a eficácia dos testes de integração na prevenção de incidentes e na melhoria da confiabilidade do sistema. |

## 2. Análise das Principais Práticas

### 2.1 Integração Contínua (CI)

A Integração Contínua (Continuous Integration) é uma prática DevOps que consiste em integrar frequentemente alterações de código em um repositório compartilhado. 
Sempre que uma modificação é enviada, processos automatizados executam compilação, testes e validações para identificar erros rapidamente. 
Seus principais fundamentos são a automação, a integração frequente, o feedback rápido e a detecção precoce de defeitos, reduzindo problemas de integração e melhorando a qualidade do software.

---

### 2.2 Entrega Contínua (CD)

A Entrega Contínua (Continuous Delivery) busca automatizar o processo de disponibilização de software para ambientes de homologação ou produção. 
Seu objetivo é garantir que a aplicação esteja sempre pronta para implantação de forma segura e previsível. 
Os principais fundamentos dessa prática são a automação de deploy, a padronização de processos, a redução de riscos e a entrega rápida de valor ao usuário.

---

### 2.3 Testes Automatizados

Os Testes Automatizados consistem na execução automática de casos de teste para verificar o correto funcionamento do software. 
Eles podem abranger testes unitários, de integração, funcionais e de regressão. Seus fundamentos incluem automação da validação, repetibilidade, aumento da cobertura de testes, feedback contínuo e garantia da qualidade ao longo do ciclo de desenvolvimento.

---

### 2.4 Observabilidade

Observabilidade é a capacidade de compreender o comportamento interno de um sistema a partir de seus dados externos. 
Essa prática baseia-se na coleta e análise de métricas, logs e rastreamentos distribuídos (traces), permitindo maior visibilidade sobre a execução dos serviços. 
Seus principais fundamentos são a visibilidade operacional, a análise de desempenho, a identificação de causas-raiz e o suporte à resolução rápida de falhas em ambientes complexos e distribuídos.

---

### 2.5 Monitoramento Contínuo

O Monitoramento Contínuo consiste no acompanhamento constante do estado e desempenho de aplicações, infraestrutura e processos DevOps. 
Seu objetivo é detectar problemas e anomalias o mais cedo possível, permitindo respostas rápidas a incidentes. Seus fundamentos incluem a coleta de métricas em tempo real, a geração de alertas, o acompanhamento de indicadores de desempenho e o suporte à tomada de decisões baseada em dados.

---

### 2.6 Métricas DORA

As Métricas DORA (DevOps Research and Assessment) são indicadores amplamente utilizados para medir a eficiência e a maturidade de equipes DevOps. 
Elas são compostas por quatro métricas principais: Deployment Frequency, Lead Time for Changes, Change Failure Rate e Mean Time to Recovery (MTTR). 
Seus fundamentos estão relacionados à mensuração objetiva do desempenho, à melhoria contínua, à avaliação da eficiência operacional e ao equilíbrio entre velocidade e estabilidade das entregas.

---

### 2.7 Site Reliability Engineering (SRE)

Site Reliability Engineering (SRE) é uma abordagem que aplica princípios de engenharia de software às operações de TI com o objetivo de aumentar a confiabilidade e disponibilidade dos sistemas. 
Seus principais fundamentos incluem automação operacional, definição de indicadores de confiabilidade (SLI), objetivos de nível de serviço (SLO), gerenciamento de Error Budgets e redução de tarefas manuais repetitivas.
O SRE busca equilibrar inovação e estabilidade, garantindo serviços mais resilientes e confiáveis.
