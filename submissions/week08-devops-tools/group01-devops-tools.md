# Semana 08 – Ferramentas DevOps

## Tema do Artigo Científico

**Uso de métricas em testes de integração para otimização do tempo de validação de mudanças em pipelines DevOps**

## Integrantes

- Gabriel Alves Pereira
- Sarah Cristina
- Matheus Emanoel

## 1. Ferramentas identificadas na literatura revidada

# 1.1 Ferramentas de Controle de Código e Versionamento

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Git | GitOps and Continuous Delivery in Financial Software (2022) | Sistema de controle de versão distribuído utilizado para rastrear alterações no código-fonte, gerenciar colaboração entre desenvolvedores, manter histórico de mudanças e suportar práticas GitOps e pipelines CI/CD. |

---

# 1.2 Ferramentas de Integração e Entrega Contínua (CI/CD)

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Jenkins | GitOps and Continuous Delivery in Financial Software (2022); DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Test Automation Frameworks for Enhancing Software Reliability (2024); Microservices Architecture with Spring Boot (2024) | Plataforma de automação utilizada para executar compilação, testes, validações de qualidade e implantação contínua de software em pipelines CI/CD. |
| GitLab CI/CD | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Test Automation Frameworks for Enhancing Software Reliability (2024); Microservices Architecture with Spring Boot (2024) | Ferramenta integrada ao GitLab que automatiza processos de build, testes e deploy, promovendo integração e entrega contínua. |
| CircleCI | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Plataforma de CI/CD baseada em nuvem utilizada para automatizar fluxos de desenvolvimento, validação e implantação de aplicações. |

---

# 1.3 Ferramentas de Containerização e Orquestração

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Docker | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Test Automation Frameworks for Enhancing Software Reliability (2024); Microservices Architecture with Spring Boot (2024) | Plataforma de containerização utilizada para empacotar aplicações e dependências em ambientes isolados e portáveis, garantindo consistência entre desenvolvimento, testes e produção. |
| Kubernetes | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Microservices Architecture with Spring Boot (2024) | Plataforma de orquestração de containers responsável por gerenciar escalabilidade, disponibilidade, balanceamento de carga e recuperação automática de aplicações distribuídas. |
| Containers | GitOps and Continuous Delivery in Financial Software (2022) | Tecnologia que permite encapsular aplicações e suas dependências em ambientes isolados, facilitando portabilidade, implantação e escalabilidade. |

---

# 1.4 Ferramentas de Infraestrutura como Código (IaC)

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Ansible | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Ferramenta de automação utilizada para provisionamento, configuração e gerenciamento de infraestrutura por meio de código. |
| Chef | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Plataforma de gerenciamento de configuração utilizada para automatizar a administração de servidores e ambientes computacionais. |
| Puppet | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Ferramenta de automação e gerenciamento de configuração que assegura consistência e conformidade da infraestrutura. |

---

# 1.5 Ferramentas de Observabilidade, Monitoramento e Logs

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Prometheus | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024); DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Microservices Architecture with Spring Boot (2024) | Plataforma open source para coleta, armazenamento e consulta de métricas operacionais utilizadas no monitoramento contínuo de aplicações e infraestrutura. |
| Grafana | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024); DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Microservices Architecture with Spring Boot (2024) | Ferramenta de visualização de dados utilizada para construção de dashboards e acompanhamento de indicadores operacionais em tempo real. |
| Datadog | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024) | Plataforma de observabilidade que integra monitoramento de infraestrutura, aplicações, logs e serviços em ambientes distribuídos e em nuvem. |
| New Relic | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024) | Solução de monitoramento de desempenho de aplicações utilizada para identificação de gargalos, falhas e problemas de experiência do usuário. |
| ELK Stack | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Microservices Architecture with Spring Boot (2024) | Conjunto de ferramentas composto por Elasticsearch, Logstash e Kibana utilizado para centralização, indexação, análise e visualização de logs. |
| Monitoramento Automatizado | GitOps and Continuous Delivery in Financial Software (2022) | Conjunto de mecanismos utilizados para acompanhar continuamente disponibilidade, desempenho e comportamento dos sistemas em produção. |
| Telemetria | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024) | Processo de coleta automática de métricas, eventos e informações operacionais utilizadas para análise e observabilidade. |
| Dashboard | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024) | Painel de monitoramento utilizado para consolidar e visualizar métricas e indicadores operacionais. |

---

# 1.6 Ferramentas de Rastreamento Distribuído

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Jaeger | Microservices Architecture with Spring Boot (2024) | Ferramenta de distributed tracing utilizada para rastrear requisições entre múltiplos microsserviços e identificar gargalos de desempenho. |
| Zipkin | Microservices Architecture with Spring Boot (2024) | Plataforma de rastreamento distribuído utilizada para monitorar o fluxo de requisições em arquiteturas baseadas em microsserviços. |

---

# 1.7 Ferramentas de Qualidade de Código e Segurança (DevSecOps)

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| SAST | GitOps and Continuous Delivery in Financial Software (2022); AI in DevOps: Revolutionizing Software Development and Operations (2025) | Ferramenta de análise estática utilizada para identificar vulnerabilidades e problemas de segurança diretamente no código-fonte antes da execução da aplicação. |
| DAST | GitOps and Continuous Delivery in Financial Software (2022); AI in DevOps: Revolutionizing Software Development and Operations (2025) | Ferramenta de análise dinâmica utilizada para detectar vulnerabilidades em aplicações em execução simulando ataques reais. |
| SonarQube | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Plataforma de inspeção contínua utilizada para avaliar qualidade de código, identificar bugs, vulnerabilidades e dívidas técnicas. |
| OWASP ZAP | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Ferramenta de testes de segurança utilizada para identificar vulnerabilidades em aplicações web durante o ciclo de desenvolvimento. |

---

# 1.8 Ferramentas de Testes Automatizados

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Selenium | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Test Automation Frameworks for Enhancing Software Reliability (2024) | Framework de automação utilizado para executar testes funcionais e de regressão em aplicações web simulando ações reais dos usuários. |
| Selenium Grid | Test Automation Frameworks for Enhancing Software Reliability (2024) | Extensão do Selenium utilizada para executar testes automatizados de forma paralela e distribuída em múltiplos ambientes. |
| JUnit | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Framework de testes unitários para aplicações Java utilizado para validar componentes de software durante o desenvolvimento e integração contínua. |
| PyTest | DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021); Test Automation Frameworks for Enhancing Software Reliability (2024) | Framework de testes para Python utilizado para criar, organizar e executar testes automatizados de forma eficiente. |
| Unittest | Test Automation Frameworks for Enhancing Software Reliability (2024) | Biblioteca nativa do Python utilizada para desenvolvimento e execução de testes unitários automatizados. |
| Postman | Test Automation Frameworks for Enhancing Software Reliability (2024) | Ferramenta utilizada para desenvolvimento, validação e automação de testes de APIs REST. |
| Newman | Test Automation Frameworks for Enhancing Software Reliability (2024) | Executor de coleções Postman utilizado para integrar testes automatizados de APIs em pipelines CI/CD. |
| Pact | Test Automation Frameworks for Enhancing Software Reliability (2024) | Ferramenta de testes de contrato utilizada para validar a comunicação entre microsserviços e APIs. |

---

# 1.9 Ferramentas de Gestão, Métricas e Acompanhamento

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Jira | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Plataforma de gerenciamento de projetos utilizada para controle de backlog, planejamento de sprints, acompanhamento de tarefas e métricas ágeis. |
| Azure DevOps | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Plataforma integrada para gerenciamento do ciclo de vida do software, incluindo planejamento, versionamento, pipelines e monitoramento. |
| Trello | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Ferramenta visual de gerenciamento de tarefas baseada em quadros Kanban para organização e acompanhamento do trabalho. |
| WorkBoard | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Plataforma utilizada para definição, monitoramento e alinhamento de objetivos estratégicos e resultados-chave (OKRs). |
| Gtmhub | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Ferramenta especializada em gestão de OKRs e monitoramento contínuo de indicadores estratégicos. |
| Ally.io | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Plataforma de acompanhamento de metas organizacionais e alinhamento estratégico baseado em OKRs. |
| Perdoo | Systematic Review of Performance Metrics and OKR Alignment in Agile Product Teams across Industry Verticals (2022) | Sistema de gestão de desempenho utilizado para conectar objetivos estratégicos, indicadores e resultados organizacionais. |
| DORA Metrics | Systematic Review of Key Performance Metrics in Modern DevOps and Software Reliability Engineering (2024); DevOps Maturity Framework for Enhancing Cross-Functional Collaboration and Continuous Deployment Efficiency (2021) | Conjunto de métricas amplamente utilizado para medir maturidade e desempenho DevOps por meio de indicadores como frequência de deploy, lead time, taxa de falhas e tempo médio de recuperação. |

---

# 1.10 Ferramentas de Desenvolvimento de Microsserviços e APIs

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| Spring Boot | Microservices Architecture with Spring Boot (2024) | Framework Java utilizado para desenvolvimento rápido de microsserviços, APIs REST e aplicações corporativas baseadas em arquitetura distribuída. |
| OAuth 2.0 | Microservices Architecture with Spring Boot (2024) | Protocolo de autorização utilizado para fornecer acesso seguro a recursos protegidos sem compartilhar credenciais diretamente. |
| JWT | Microservices Architecture with Spring Boot (2024) | Tecnologia baseada em tokens utilizada para autenticação stateless e troca segura de informações entre sistemas. |
| Spring Security | Microservices Architecture with Spring Boot (2024) | Framework responsável por implementar autenticação, autorização e proteção de aplicações desenvolvidas com Spring. |
| OpenAPI/Swagger | Decomposition of Monolith Applications into Microservices Architectures: A Systematic Review (2023) | Ferramenta utilizada para documentação, padronização e especificação de APIs, facilitando integração e comunicação entre serviços. |

---

# 1.11 Ferramentas de Inteligência Artificial Aplicadas ao DevOps (AIOps)

| Ferramenta | Artigos | Utilização |
|------------|----------|------------|
| GitHub Copilot | AI in DevOps: Revolutionizing Software Development and Operations (2025) | Assistente de programação baseado em inteligência artificial utilizado para sugerir código, acelerar o desenvolvimento e reduzir esforço manual. |
| LLMs | AI in DevOps: Revolutionizing Software Development and Operations (2025) | Modelos de linguagem utilizados para geração de código, documentação, análise de logs, automação de tarefas e suporte à tomada de decisão. |
| Machine Learning | AI in DevOps: Revolutionizing Software Development and Operations (2025) | Técnicas de aprendizado de máquina aplicadas para previsão de falhas, análise de comportamento e otimização de processos DevOps. |
| NLP | AI in DevOps: Revolutionizing Software Development and Operations (2025) | Técnicas de processamento de linguagem natural utilizadas para interpretar documentação, incidentes, tickets e registros operacionais. |
| SigmaSolve | AI in DevOps: Revolutionizing Software Development and Operations (2025) | Solução baseada em inteligência artificial utilizada para automação inteligente de atividades relacionadas ao desenvolvimento e operações. |

## 2. Ferramentas Relacionadas ao Uso de Métricas em Testes de Integração para Otimização do Tempo de Validação de Mudanças em Pipelines DevOps

---

# 2.1 Integração e Entrega Contínua (CI/CD)

As ferramentas de Integração e Entrega Contínua (CI/CD) desempenham papel fundamental na automação dos processos de desenvolvimento, testes e implantação de software. 
No contexto deste estudo, elas são responsáveis pela execução automatizada dos testes de integração e pela coleta de métricas relacionadas ao tempo de validação das mudanças. 
Por meio dessas ferramentas é possível monitorar a duração dos pipelines, identificar gargalos e avaliar a eficiência do fluxo de entrega contínua.

## Ferramentas

- Jenkins
- GitLab CI/CD
- CircleCI

---

# 2.2 Testes de Integração Automatizados

Os testes de integração constituem o núcleo da pesquisa, pois têm como objetivo validar a comunicação e a interação entre diferentes componentes do sistema após a realização de alterações no código. 
As ferramentas desse grupo permitem automatizar a execução dos testes e gerar métricas relacionadas ao tempo de execução, taxa de falhas, estabilidade das integrações e cobertura dos cenários testados, contribuindo diretamente para a otimização do processo de validação.

## Ferramentas

- Selenium
- Selenium Grid
- JUnit
- PyTest
- Unittest
- Postman
- Newman
- Pact

---

# 2.3 Containerização e Ambientes de Execução

A execução eficiente dos testes de integração depende da disponibilidade de ambientes consistentes, isolados e reproduzíveis. 
As ferramentas de containerização permitem criar ambientes padronizados para a execução dos testes, reduzindo problemas relacionados à configuração da infraestrutura e garantindo maior confiabilidade às métricas coletadas durante a validação.

## Ferramentas

- Docker
- Kubernetes
- Containers

---

# 2.4 Observabilidade, Monitoramento e Coleta de Métricas

A utilização de métricas depende da capacidade de coletar, armazenar e analisar informações geradas durante a execução dos testes e dos pipelines. 
As ferramentas de observabilidade permitem monitorar continuamente aplicações e infraestrutura, fornecendo indicadores que auxiliam na identificação de gargalos, falhas recorrentes e oportunidades de otimização do tempo de validação.

## Ferramentas

- Prometheus
- Grafana
- Datadog
- New Relic
- ELK Stack
- Monitoramento Automatizado
- Telemetria
- Dashboard
- Jaeger
- Zipkin

---

# 2.5 Métricas de Desempenho DevOps

O principal objetivo deste estudo é analisar como métricas podem ser utilizadas para otimizar o tempo de validação das mudanças em pipelines DevOps. 
Nesse contexto, as métricas fornecem informações quantitativas que permitem avaliar a eficiência dos testes de integração, a velocidade das entregas, a estabilidade das implantações e a capacidade de recuperação diante de falhas.

## Ferramentas

- DORA Metrics

---

# 2.6 Qualidade de Código e Segurança

A qualidade do código e a segurança das aplicações influenciam diretamente o tempo necessário para validar mudanças. 
Quanto mais cedo defeitos e vulnerabilidades forem identificados, menor será o retrabalho durante as etapas de testes de integração. As ferramentas deste grupo atuam de forma preventiva, contribuindo para a redução de falhas e para a melhoria da eficiência dos pipelines.

## Ferramentas

- SonarQube
- SAST
- DAST

---

## 3. Relação entre os Grupos de Ferramentas

A otimização do tempo de validação em pipelines DevOps depende da integração entre diferentes categorias de ferramentas. 
As ferramentas de CI/CD automatizam o fluxo de execução, as ferramentas de testes realizam a validação das integrações, as soluções de containerização garantem ambientes consistentes para execução, as plataformas de observabilidade coletam métricas sobre o processo, as métricas DORA permitem avaliar o desempenho do fluxo de entrega e as ferramentas de qualidade e segurança reduzem a quantidade de falhas que chegam às etapas de validação.

Dessa forma, a combinação desses grupos tecnológicos possibilita a construção de pipelines mais rápidos, confiáveis e orientados por métricas, permitindo que as organizações reduzam o tempo de validação das mudanças sem comprometer a qualidade do software entregue.
