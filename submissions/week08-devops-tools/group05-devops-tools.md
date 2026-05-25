# Semana 08 – Ferramentas DevOps

**Disciplina:** DevOps – Tópicos Especiais em Computação IV  
**Grupo:** Grupo 05  
**Integrantes:** Daniel Castilho de Oliveira; Rian Karlos Silva Weber; Ricardo de Almeida Sarruf  
**Tema:** Plataformas de Computação em Nuvem Aplicadas ao DevOps: Análise Comparativa entre AWS, Microsoft Azure e Google Cloud Platform

---

## 1. Critérios de organização das ferramentas

As ferramentas foram agrupadas conforme sua função predominante no ciclo DevOps:

1. **Integração e entrega contínua (CI/CD):** ferramentas utilizadas para automatizar build, testes, validações, versionamento de entregas e implantação de aplicações.
2. **Conteinerização e orquestração:** ferramentas voltadas à padronização, empacotamento, escalabilidade e gestão de aplicações distribuídas.
3. **Infraestrutura como Código (IaC) e configuração:** ferramentas que permitem provisionar, configurar e versionar recursos de infraestrutura de modo automatizado.
4. **Observabilidade e monitoramento:** ferramentas usadas para acompanhar logs, métricas, desempenho, falhas e disponibilidade dos sistemas.
5. **Segurança, governança e conformidade:** soluções aplicadas à gestão de identidade, segredos, criptografia, políticas de acesso, auditoria e conformidade regulatória.
6. **MLOps, dados e automação inteligente:** ferramentas voltadas à operacionalização de modelos de aprendizado de máquina, pipelines de dados e automação baseada em inteligência artificial.

---


## 2. Achados específicos em cada artigo analisado

Antes da listagem geral das ferramentas, apresenta-se a seguir o levantamento individual realizado em cada artigo. Essa etapa é importante porque demonstra **de onde cada ferramenta foi retirada**, qual foi a contribuição de cada fonte para a entrega e como os artigos se relacionam com o tema do grupo.

### 2.1 Quadro-resumo dos achados

| Nº | Artigo | Contribuição principal para a Semana 08 | Ferramentas/tecnologias identificadas |
|---|---|---|---|
| 1 | *Cloud-native DevOps Practices for SAP Deployment* | Mostra como DevOps cloud-native moderniza implantações SAP por meio de automação, containers, CI/CD e orquestração. | Docker, Kubernetes, Jenkins, GitLab CI, CI/CD, IaC, ferramentas de monitoramento, AWS, Azure, GCP. |
| 2 | *Comparing Major Cloud Providers for AI/ML Workloads: AWS vs Azure vs GCP* | Contribui com ferramentas de MLOps e automação de fluxos de IA/ML nos três provedores. | Amazon SageMaker, Azure Machine Learning, Google Vertex AI, AutoML, SageMaker Pipelines, Vertex Pipelines, GitHub Actions, Azure DevOps. |
| 3 | *Accelerating Enterprise SAP Workload Performance and Automation Using Microsoft Azure Center for SAP Solutions...* | Evidencia ferramentas Azure para SAP, automação, IaC, orquestração inteligente e monitoramento. | Azure Center for SAP Solutions, Azure DevOps, ARM Templates, Terraform, Ansible, Azure Monitor, Logic Apps, Backup. |
| 4 | *Comparative Evaluation of Cloud-Native and VM-Based CI/CD Pipelines for Automated DevOps Deployments* | Compara pipelines cloud-native e baseados em VM, destacando velocidade, elasticidade, resiliência e métricas DevOps. | GitHub, Azure DevOps, Jenkins, GitLab, Git, CI/CD, containers, microservices, serverless functions, DORA metrics. |
| 5 | *The Role of DevOps and Automation in Cloud Transition* | Fonte mais direta para a listagem de ferramentas, pois organiza DevOps por IaC, CI/CD, configuração, monitoramento, segurança, testes e deploy. | Terraform, CloudFormation, ARM, Deployment Manager, Pulumi, Jenkins, GitHub Actions, GitLab CI/CD, Azure DevOps, CircleCI, CodePipeline, Cloud Build, Ansible, Chef, Puppet, Prometheus, Grafana, Datadog, Vault, Snyk, Aqua, Selenium, Postman, JMeter, Spinnaker, ArgoCD. |
| 6 | *Management of Self-Healing Systems for Multi-Cloud Deployments on Kubernetes* | Demonstra uso de ferramentas em arquitetura multi-cloud com self-healing, recuperação automática e monitoramento. | Kubernetes, Kubernetes Operators, Jenkins, Git, GitHub, Docker, Datadog, Prometheus, Grafana, Istio, Terraform, AWS, Azure, GCP. |
| 7 | *Adoption of Infrastructure as Code (IaC) in Real World* | Explica adoção prática de IaC, seus benefícios, dificuldades e necessidade de versionamento e integração com CI/CD. | AWS CDK, Terraform, IaC, version control, CI/CD, Kubernetes, cloud resources, code review. |
| 8 | *Infrastructure-as-Code with Scripting: A Technical Review* | Aprofunda o papel de scripts na IaC, especialmente para automações específicas, legados e ambientes híbridos. | Terraform, Ansible, Python, PowerShell, Bash, Boto3, Fabric, Paramiko, security-as-code, state management. |
| 9 | *Data Governance and Compliance in Cloud-Based Data Engineering Pipelines* | Amplia a análise para governança, segurança, auditoria e conformidade em pipelines de dados na nuvem. | AWS Kinesis, Azure Event Hubs, Google Pub/Sub, Apache Spark, Apache Beam, S3, Azure Data Lake Storage, Google Cloud Storage, Snowflake, AWS Lake Formation, Azure Purview, Google Cloud Data Catalog, CloudTrail, Azure Monitor, Google Cloud Audit Logs, RBAC, ABAC. |
| 10 | *The Role of Software Developers in Transitioning On-Premises Applications to Cloud Platforms* | Relaciona ferramentas DevOps ao processo de migração de aplicações on-premises para nuvem. | CI/CD, container orchestration, IaC, IAM, encryption, compliance protocols, AWS, Azure, GCP. |
| 11 | *Cloud Enabled Intelligent Enterprise Healthcare Framework with Machine Learning Based on Artificial Intelligence and Blockchain Governance* | Contribui com arquitetura cloud-native, automação inteligente, governança, IA/ML e rastreabilidade em ambiente crítico. | Containers, microservices, serverless computing, API gateways, AI/ML modules, blockchain governance, smart contracts, identity management, audit trails, real-time analytics. |
| 12 | *Analyzing the System Features, Usability, and Performance of a Containerized Application on Cloud Computing Systems* | Compara serviços serverless para containers em AWS, Azure e GCP, com métricas de usabilidade e desempenho. | Google Cloud Run, AWS App Runner, Azure Container Apps, Google App Engine, Google Compute Engine, Cloud Monitoring, containers, serverless, scale-to-zero. |

### 2.2 Detalhamento dos achados por artigo

#### Artigo 1 – *Cloud-native DevOps Practices for SAP Deployment*

**Foco do artigo:** o estudo aborda a aplicação de práticas DevOps cloud-native em ambientes SAP, com ênfase em automação, escalabilidade e redução de indisponibilidades.

**O que foi encontrado:** o artigo demonstra que a modernização de workloads SAP passa pela adoção de conteinerização, microserviços, pipelines de integração e entrega contínua, orquestração com Kubernetes, infraestrutura como código e monitoramento contínuo. Também evidencia que o modelo tradicional de implantação SAP tende a ser mais rígido, manual e custoso.

**Ferramentas identificadas:** Docker, Kubernetes, Jenkins, GitLab CI, CI/CD pipelines, ferramentas de monitoramento, IaC e serviços de nuvem da AWS, Azure e GCP.

**Contribuição para a entrega:** o artigo justifica a inclusão de ferramentas de containers, CI/CD e orquestração como componentes essenciais para DevOps em ambientes empresariais complexos.

#### Artigo 2 – *Comparing Major Cloud Providers for AI/ML Workloads: AWS vs Azure vs GCP*

**Foco do artigo:** a pesquisa compara AWS, Azure e GCP em cargas de trabalho de inteligência artificial e machine learning.

**O que foi encontrado:** o artigo contribui para a dimensão de MLOps, pois apresenta serviços que automatizam treinamento, versionamento, implantação, monitoramento e governança de modelos. A AWS aparece como plataforma madura e abrangente; a Azure se destaca pela integração com sistemas corporativos e pipelines DevOps; e a GCP apresenta destaque em AutoML, Vertex AI, TPUs e ferramentas voltadas à ciência de dados.

**Ferramentas identificadas:** Amazon SageMaker, SageMaker Pipelines, Azure Machine Learning, Azure DevOps, GitHub Actions, Google Vertex AI, Vertex Pipelines, AutoML, GPUs, TPUs e ferramentas de orquestração de dados.

**Contribuição para a entrega:** o artigo fundamenta a inclusão de ferramentas de MLOps e demonstra que DevOps em nuvem também alcança fluxos de IA/ML, não apenas aplicações tradicionais.

#### Artigo 3 – *Accelerating Enterprise SAP Workload Performance and Automation Using Microsoft Azure Center for SAP Solutions Through Cloud Native Architecture Intelligent Orchestration and Infrastructure as Code*

**Foco do artigo:** o estudo analisa a automação de workloads SAP no Microsoft Azure, com destaque para o Azure Center for SAP Solutions.

**O que foi encontrado:** foram identificadas ferramentas de automação, IaC, pipelines, monitoramento, backup e orquestração inteligente. O artigo reforça que a Azure oferece um ecossistema integrado para reduzir tempo de provisionamento, diminuir custos operacionais, aumentar tolerância a falhas e melhorar a confiabilidade de workloads empresariais.

**Ferramentas identificadas:** Azure Center for SAP Solutions, Azure DevOps, Azure Pipelines, ARM Templates, Terraform, Ansible, Azure Monitor, Azure Log Analytics, Azure Logic Apps e Azure Backup.

**Contribuição para a entrega:** o artigo fortalece a análise comparativa do provedor Azure, principalmente em contextos corporativos e sistemas SAP.

#### Artigo 4 – *Comparative Evaluation of Cloud-Native and VM-Based CI/CD Pipelines for Automated DevOps Deployments*

**Foco do artigo:** a pesquisa compara pipelines CI/CD baseados em máquinas virtuais com pipelines cloud-native.

**O que foi encontrado:** a principal contribuição foi a diferenciação entre ambientes com maior controle operacional, baseados em VM, e ambientes cloud-native, mais alinhados à velocidade, elasticidade e resiliência. O estudo também utiliza métricas DORA e modelo de custo total de propriedade, mostrando que a escolha da arquitetura de pipeline influencia desempenho, custo, segurança e escalabilidade.

**Ferramentas identificadas:** Git, GitHub, Azure DevOps, Jenkins, GitLab, pipelines CI/CD, containers, microservices, serverless functions e métricas DORA.

**Contribuição para a entrega:** o artigo fundamenta academicamente a importância de ferramentas CI/CD e mostra que a infraestrutura usada para executar os pipelines também afeta a maturidade DevOps.

#### Artigo 5 – *The Role of DevOps and Automation in Cloud Transition*

**Foco do artigo:** o texto analisa o papel de DevOps e automação em processos de transição para a nuvem.

**O que foi encontrado:** este foi um dos artigos mais completos para a Semana 08, pois organiza ferramentas DevOps por categorias: IaC, CI/CD, configuração, monitoramento, segurança, testes e implantação. Ele mostra que a migração para a nuvem depende de automação integrada e de ferramentas capazes de reduzir erros humanos, aumentar repetibilidade e melhorar controle operacional.

**Ferramentas identificadas:** Terraform, AWS CloudFormation, Azure Resource Manager, Google Cloud Deployment Manager, Pulumi, Jenkins, GitHub Actions, GitLab CI/CD, Azure DevOps, CircleCI, AWS CodePipeline, Google Cloud Build, Ansible, Chef, Puppet, SaltStack, Prometheus, Grafana, Datadog, New Relic, Azure Monitor, CloudWatch, Google Cloud Operations Suite, HashiCorp Vault, AWS IAM, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, Aqua Security, Snyk, Selenium, Postman, Newman, JMeter, TestComplete, Spinnaker e ArgoCD.

**Contribuição para a entrega:** o artigo serviu como base central para a listagem geral das ferramentas e para a divisão por categorias funcionais.

#### Artigo 6 – *Management of Self-Healing Systems for Multi-Cloud Deployments on Kubernetes*

**Foco do artigo:** a pesquisa propõe um framework de self-healing para implantações multi-cloud em Kubernetes.

**O que foi encontrado:** o artigo demonstra que ferramentas DevOps podem ser combinadas para construir ambientes resilientes e capazes de detectar falhas, recuperar serviços e manter disponibilidade. Foram identificadas ferramentas de orquestração, CI/CD, versionamento, monitoramento, containerização e service mesh. O estudo também apresenta AWS, Azure e GCP como provedores adequados para arquiteturas multi-cloud.

**Ferramentas identificadas:** Kubernetes, Kubernetes Operators, Jenkins, Git, GitHub, Docker, Datadog, Prometheus, Grafana, Istio, Terraform, AWS CodePipeline, Google Cloud Build, Azure DevOps, AWS, Azure e GCP.

**Contribuição para a entrega:** o artigo justifica a inclusão de ferramentas de observabilidade, orquestração e recuperação automática como elementos relevantes de DevOps moderno.

#### Artigo 7 – *Adoption of Infrastructure as Code (IaC) in Real World: Lessons and Practices from Industry*

**Foco do artigo:** a dissertação analisa a adoção de infraestrutura como código em contextos reais de mercado.

**O que foi encontrado:** o artigo mostra que IaC promove escalabilidade, velocidade, transparência, repetibilidade e melhor controle sobre ambientes de nuvem. Também evidencia desafios de adoção, como curva de aprendizado, falta de especialistas e limitações na documentação para casos avançados. A pesquisa destaca que AWS CDK e Terraform aparecem entre as ferramentas mais utilizadas pelos profissionais consultados.

**Ferramentas identificadas:** AWS CDK, Terraform, IaC, version control, CI/CD pipelines, cloud resources, Kubernetes e práticas de code review.

**Contribuição para a entrega:** o artigo fundamenta a importância da IaC como prática DevOps e ajuda a explicar por que Terraform, AWS CDK e automação versionada devem aparecer na listagem de ferramentas.

#### Artigo 8 – *Infrastructure-as-Code with Scripting: A Technical Review*

**Foco do artigo:** o texto revisa tecnicamente a combinação entre IaC e linguagens de script.

**O que foi encontrado:** o artigo demonstra que ferramentas declarativas, como Terraform e Ansible, podem ser complementadas por scripts em Python, PowerShell e Bash. Essa integração permite lidar com necessidades específicas, ambientes legados, automações pré e pós-provisionamento, validações, tarefas de configuração e cenários multi-cloud.

**Ferramentas identificadas:** Terraform, Ansible, Python, PowerShell, Bash, Boto3, Fabric, Paramiko, security-as-code, state management, scripts de provisionamento, configuração e deploy.

**Contribuição para a entrega:** o artigo amplia a análise de IaC ao mostrar que scripts também são instrumentos DevOps, especialmente quando usados para automatizar tarefas não cobertas por ferramentas declarativas tradicionais.

#### Artigo 9 – *Data Governance and Compliance in Cloud-Based Data Engineering Pipelines*

**Foco do artigo:** o estudo trata de governança e conformidade em pipelines de engenharia de dados na nuvem.

**O que foi encontrado:** foram identificadas ferramentas para ingestão, processamento, armazenamento, catálogo de dados, segurança, controle de acesso, auditoria e conformidade. O artigo contribui para uma visão DevSecOps/DataOps, em que pipelines precisam garantir rastreabilidade, privacidade, controle de permissões e aderência regulatória.

**Ferramentas identificadas:** AWS Kinesis, Azure Event Hubs, Google Pub/Sub, Apache Spark, Apache Beam, Amazon S3, Azure Data Lake Storage, Google Cloud Storage, Snowflake, AWS Lake Formation, Azure Purview, Google Cloud Data Catalog, AWS CloudTrail, Azure Monitor, Google Cloud Audit Logs, RBAC e ABAC.

**Contribuição para a entrega:** o artigo justifica a inclusão de ferramentas de governança, auditoria e compliance como parte do ecossistema DevOps em nuvem.

#### Artigo 10 – *The Role of Software Developers in Transitioning On-Premises Applications to Cloud Platforms: Strategies and Challenges*

**Foco do artigo:** a pesquisa analisa o papel dos desenvolvedores na migração de aplicações locais para plataformas em nuvem.

**O que foi encontrado:** o artigo mostra que desenvolvedores atuam em avaliação de compatibilidade, refatoração, segurança, otimização de performance, migração de dados e automação. Foram identificadas práticas de CI/CD, orquestração de containers e IaC como elementos essenciais para migração segura e eficiente.

**Ferramentas identificadas:** CI/CD pipelines, container orchestration, Infrastructure as Code, IAM, encryption, compliance protocols, AWS, Azure e GCP.

**Contribuição para a entrega:** o artigo demonstra que as ferramentas DevOps devem ser entendidas também como apoio ao processo de migração, não apenas como ferramentas de operação pós-implantação.

#### Artigo 11 – *Cloud Enabled Intelligent Enterprise Healthcare Framework with Machine Learning Based on Artificial Intelligence and Blockchain Governance*

**Foco do artigo:** o estudo propõe uma arquitetura de saúde digital baseada em nuvem, IA/ML e governança por blockchain.

**O que foi encontrado:** embora o foco seja saúde, o artigo contribui para a análise de arquiteturas cloud-native em ambientes críticos. Foram identificados componentes como containers, microserviços, serverless, APIs, pipelines de dados, analytics em tempo real, identidade descentralizada, auditoria e contratos inteligentes. Esses elementos dialogam com práticas de DevOps, DevSecOps e automação inteligente.

**Ferramentas/tecnologias identificadas:** containerization, microservices, serverless computing, API gateways, AI/ML modules, blockchain governance, smart contracts, decentralized identity, audit trails, data ingestion pipelines e real-time analytics.

**Contribuição para a entrega:** o artigo amplia o escopo para governança, segurança, interoperabilidade e automação inteligente, áreas cada vez mais associadas à maturidade DevOps em nuvem.

#### Artigo 12 – *Analyzing the System Features, Usability, and Performance of a Containerized Application on Cloud Computing Systems*

**Foco do artigo:** a dissertação compara serviços de nuvem para execução de aplicações conteinerizadas.

**O que foi encontrado:** o estudo analisou Google Cloud Run, AWS App Runner e Azure Container Apps em termos de configuração, preço, capacidade de CPU/memória, latência, tempo de resposta, utilização de CPU, documentação, curva de aprendizagem e escala para zero. O principal achado foi que o Google Cloud Run apresentou melhor desempenho e usabilidade no cenário testado.

**Ferramentas identificadas:** Google Cloud Run, AWS App Runner, Azure Container Apps, Google App Engine, Google Compute Engine, Cloud Monitoring, containers, serverless computing e scale-to-zero.

**Contribuição para a entrega:** o artigo fundamenta a comparação entre serviços serverless de containers nos três provedores e justifica a presença de Cloud Run, App Runner e Azure Container Apps na lista de ferramentas.

---

## 3. Ferramentas DevOps identificadas e suas finalidades

### 3.1 Ferramentas de CI/CD

As ferramentas de CI/CD são essenciais para automatizar o ciclo de entrega de software, permitindo que alterações no código sejam integradas, testadas e disponibilizadas com maior rapidez e menor risco operacional.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **Jenkins** | Servidor de automação utilizado para criação de pipelines de build, teste e deploy. | Pode ser integrado aos três provedores de nuvem, sendo recorrente em cenários multi-cloud e em estudos sobre automação de implantação. |
| **GitHub Actions** | Plataforma de automação integrada ao GitHub, utilizada para executar workflows de CI/CD a partir de eventos no repositório. | Permite implantações automatizadas em AWS, Azure e GCP por meio de actions e credenciais configuradas. |
| **GitLab CI/CD** | Solução integrada ao GitLab para automação de pipelines de integração, teste e entrega. | Compatível com estratégias multi-cloud e com implantações baseadas em containers e IaC. |
| **Azure DevOps** | Conjunto de ferramentas para planejamento, repositórios, pipelines, testes e entrega contínua. | Tem forte integração nativa com Azure, mas também pode ser utilizado para implantações em AWS e GCP. |
| **CircleCI** | Plataforma de CI/CD baseada em nuvem, com suporte a execução de pipelines e containers. | Adequada a projetos que exigem automação de build e deploy em múltiplos ambientes. |
| **AWS CodePipeline** | Serviço nativo da AWS para automação de pipelines de entrega contínua. | Utilizado para orquestrar etapas de build, teste e deploy dentro do ecossistema AWS. |
| **Google Cloud Build** | Serviço gerenciado da GCP para criação de pipelines de build, teste e deploy. | Aplicável à implantação de aplicações em Cloud Run, GKE, App Engine e outros serviços da GCP. |

Em termos acadêmicos, essas ferramentas representam a materialização técnica do princípio de entrega contínua. Elas reduzem atividades manuais, aumentam a rastreabilidade das mudanças e contribuem para ciclos de entrega mais curtos e confiáveis.

---

### 3.2 Ferramentas de conteinerização e orquestração

A conteinerização permite empacotar aplicações e suas dependências em unidades portáveis e reproduzíveis. A orquestração, por sua vez, gerencia a execução, escalabilidade, recuperação e distribuição desses containers em ambientes locais, híbridos ou multi-cloud.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **Docker** | Plataforma de conteinerização usada para empacotar aplicações e dependências. | Facilita portabilidade entre ambientes locais, AWS, Azure e GCP. |
| **Kubernetes** | Plataforma de orquestração de containers, responsável por escalabilidade, balanceamento, recuperação e gestão de workloads. | Presente em serviços gerenciados como Amazon EKS, Azure AKS e Google Kubernetes Engine. |
| **Amazon EKS** | Serviço gerenciado de Kubernetes da AWS. | Permite executar clusters Kubernetes com integração aos serviços AWS. |
| **Azure AKS** | Serviço gerenciado de Kubernetes da Microsoft Azure. | Utilizado para implantar e gerenciar aplicações conteinerizadas no Azure. |
| **Google Kubernetes Engine (GKE)** | Serviço gerenciado de Kubernetes da GCP. | Fortemente associado a workloads cloud-native e automação de aplicações distribuídas. |
| **Kubernetes Operators** | Extensões do Kubernetes que automatizam tarefas operacionais específicas. | Úteis para mecanismos de self-healing, automação de recuperação e gestão avançada de aplicações. |
| **Istio** | Service mesh utilizado para controle de tráfego, segurança, observabilidade e comunicação entre microserviços. | Relevante em arquiteturas multi-cloud e aplicações baseadas em microserviços. |
| **Google Cloud Run** | Plataforma serverless para execução de containers. | Permite implantar aplicações conteinerizadas sem gerenciar servidores ou clusters diretamente. |
| **AWS App Runner** | Serviço gerenciado da AWS para execução de aplicações web e APIs conteinerizadas. | Simplifica o deploy de aplicações containerizadas no ecossistema AWS. |
| **Azure Container Apps** | Serviço serverless da Azure para execução de aplicações conteinerizadas. | Adequado a microsserviços, APIs e workloads orientados a eventos. |

Essas ferramentas são fundamentais para estratégias DevOps porque reduzem problemas de incompatibilidade entre ambientes, facilitam escalabilidade automática e ampliam a resiliência das aplicações. Em estudos envolvendo SAP, aplicações serverless e multi-cloud, Docker e Kubernetes aparecem como tecnologias centrais para modernização de workloads e automação operacional.

---

### 3.3 Ferramentas de Infraestrutura como Código (IaC) e configuração

A Infraestrutura como Código permite que recursos de nuvem sejam definidos por arquivos versionáveis, reproduzíveis e automatizados. Essa prática reduz erros manuais, facilita auditoria e permite recriar ambientes com maior previsibilidade.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **Terraform** | Ferramenta multi-cloud de IaC baseada em arquivos declarativos. | Permite provisionar recursos em AWS, Azure, GCP e outros provedores com fluxo padronizado. |
| **AWS CloudFormation** | Serviço nativo da AWS para definição e provisionamento de infraestrutura por templates. | Utilizado para automatizar recursos AWS com JSON ou YAML. |
| **AWS CDK** | Framework que permite definir infraestrutura AWS usando linguagens de programação. | Abstrai o CloudFormation e facilita desenvolvimento de infraestrutura com TypeScript, Python, Java e outras linguagens. |
| **Azure Resource Manager (ARM)** | Camada de gerenciamento e templates declarativos para recursos Azure. | Usado para provisionar e padronizar recursos no Azure. |
| **Bicep** | Linguagem declarativa da Microsoft para simplificar templates ARM. | Facilita a criação de infraestrutura Azure com sintaxe mais legível. |
| **Google Cloud Deployment Manager** | Ferramenta nativa da GCP para automação de infraestrutura. | Permite definir recursos GCP por arquivos YAML e templates. |
| **Pulumi** | Ferramenta de IaC que usa linguagens de programação convencionais. | Pode atuar em ambientes multi-cloud, com suporte a AWS, Azure e GCP. |
| **Ansible** | Ferramenta de automação e configuração baseada em playbooks YAML. | Usada para configuração de servidores, provisionamento e automação em nuvem. |
| **Chef** | Ferramenta de gerenciamento de configuração baseada em receitas. | Aplicável à padronização de servidores e ambientes. |
| **Puppet** | Ferramenta de automação de infraestrutura baseada em manifests. | Utilizada para manter estados desejados de configuração. |
| **SaltStack** | Plataforma de automação e configuração orientada a eventos. | Aplicável à manutenção e automação de ambientes distribuídos. |
| **Python, Bash e PowerShell** | Linguagens de script usadas para estender automações de infraestrutura. | Python se destaca em integração com APIs; Bash em ambientes Linux; PowerShell em automações Microsoft/Azure. |

A adoção de IaC é particularmente relevante no tema do grupo, pois AWS, Azure e GCP possuem serviços nativos de provisionamento, ao mesmo tempo em que ferramentas independentes, como Terraform e Pulumi, favorecem estratégias híbridas e multi-cloud.

---

### 3.4 Ferramentas de observabilidade, monitoramento e desempenho

A observabilidade permite acompanhar o comportamento dos sistemas em produção, identificar falhas, analisar desempenho e agir preventivamente. No contexto DevOps, essas ferramentas sustentam feedback contínuo e melhoria operacional.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **Prometheus** | Coleta e armazenamento de métricas, especialmente em ambientes Kubernetes. | Muito usado em arquiteturas cloud-native e multi-cloud. |
| **Grafana** | Visualização de métricas e construção de dashboards. | Frequentemente integrado ao Prometheus, Datadog e fontes nativas de nuvem. |
| **Datadog** | Plataforma de monitoramento, logs, APM e observabilidade. | Aplicável a ambientes AWS, Azure, GCP e multi-cloud. |
| **New Relic** | Plataforma de observabilidade full-stack. | Usada para monitoramento de aplicações, infraestrutura e experiência do usuário. |
| **AWS CloudWatch** | Serviço nativo da AWS para métricas, logs e alarmes. | Monitora recursos e aplicações hospedadas na AWS. |
| **Azure Monitor** | Serviço nativo da Azure para telemetria, métricas, logs e alertas. | Integra-se a workloads Azure, SAP, containers e pipelines. |
| **Azure Log Analytics** | Ferramenta de análise de logs vinculada ao Azure Monitor. | Usada para consulta, correlação e investigação de eventos. |
| **Google Cloud Operations Suite** | Conjunto nativo da GCP para logging, monitoring e tracing. | Permite acompanhar aplicações e recursos no Google Cloud. |
| **Google Cloud Audit Logs** | Logs de auditoria para atividades em recursos GCP. | Relevante para governança, segurança e rastreabilidade. |
| **AWS CloudTrail** | Registro de chamadas de API e atividades na conta AWS. | Usado para auditoria, conformidade e investigação de ações. |

Essas ferramentas demonstram que DevOps não termina no deploy. Após a implantação, a operação contínua depende de métricas, logs, alertas e mecanismos de resposta a incidentes.

---

### 3.5 Ferramentas de segurança, governança e conformidade

A segurança em DevOps deve ser incorporada ao ciclo de desenvolvimento e implantação. Em ambientes de nuvem, isso inclui controle de acesso, gerenciamento de segredos, criptografia, auditoria, validação de políticas e conformidade regulatória.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **HashiCorp Vault** | Gerenciamento de segredos, tokens, certificados e chaves. | Adequado a arquiteturas multi-cloud. |
| **AWS IAM** | Gestão de identidades e permissões na AWS. | Controla acesso a recursos AWS. |
| **AWS Secrets Manager** | Armazenamento e rotação de segredos na AWS. | Protege credenciais usadas por aplicações e pipelines. |
| **Azure Key Vault** | Armazenamento seguro de chaves, certificados e segredos. | Integrado a aplicações, pipelines e serviços Azure. |
| **Google Cloud Secret Manager** | Armazenamento e controle de acesso a segredos na GCP. | Protege chaves, tokens e variáveis sensíveis. |
| **AWS KMS** | Gerenciamento de chaves criptográficas na AWS. | Usado para criptografia de dados em repouso e em trânsito. |
| **Google Cloud KMS** | Serviço de gerenciamento de chaves da GCP. | Permite controle centralizado de criptografia. |
| **AWS Config** | Avaliação contínua de configurações e conformidade na AWS. | Detecta recursos fora de políticas definidas. |
| **Azure Policy** | Definição e aplicação de políticas de governança em recursos Azure. | Impõe padrões de conformidade, tags e restrições. |
| **Forseti Security** | Ferramenta de segurança e conformidade para Google Cloud. | Auxilia na verificação de políticas e configurações. |
| **Snyk** | Análise de vulnerabilidades em código, containers e IaC. | Apoia práticas de DevSecOps. |
| **Aqua Security** | Segurança de containers, Kubernetes e workloads cloud-native. | Usada para proteção de pipelines e ambientes conteinerizados. |
| **AWS Lake Formation** | Governança de dados e controle fino de acesso na AWS. | Relevante para pipelines de dados e catálogos governados. |
| **Azure Purview** | Governança, descoberta, classificação e linhagem de dados. | Centraliza políticas de dados no ecossistema Azure. |
| **Google Cloud Data Catalog** | Catálogo de metadados e classificação de dados na GCP. | Facilita busca, classificação e controle de acesso a dados. |

Essas ferramentas ampliam o DevOps para a lógica de **DevSecOps**, em que segurança e conformidade deixam de ser etapas finais e passam a integrar todo o ciclo de desenvolvimento, implantação e operação.

---

### 3.6 Ferramentas de MLOps, dados e automação inteligente

Os artigos também indicam que DevOps se aproxima de práticas de MLOps quando o foco envolve modelos de inteligência artificial, aprendizado de máquina e pipelines de dados. Nesses casos, as ferramentas precisam apoiar versionamento de modelos, treinamento, implantação, monitoramento e governança.

| Ferramenta | Finalidade | Aplicação no contexto AWS, Azure e GCP |
|---|---|---|
| **Amazon SageMaker** | Plataforma gerenciada para desenvolvimento, treinamento, implantação e monitoramento de modelos de ML. | Representa a principal solução MLOps da AWS. |
| **SageMaker Pipelines** | Serviço para criação de pipelines de machine learning na AWS. | Automatiza etapas de treinamento, validação e deploy de modelos. |
| **Azure Machine Learning** | Plataforma da Azure para MLOps, treinamento, deployment e governança de modelos. | Integra-se a Azure DevOps e GitHub Actions. |
| **Azure Pipelines** | Serviço de CI/CD que pode ser usado também em fluxos de MLOps. | Automatiza pipelines empresariais e fluxos de ML. |
| **Google Vertex AI** | Plataforma unificada da GCP para ML, AutoML, treinamento, implantação e monitoramento. | Centraliza recursos de MLOps no Google Cloud. |
| **Vertex Pipelines** | Ferramenta para orquestração de pipelines de ML na GCP. | Automatiza fluxo de dados, treinamento e implantação de modelos. |
| **AutoML** | Conjunto de recursos para criação automatizada de modelos de ML. | Fortemente associado ao ecossistema GCP. |
| **AWS Kinesis** | Serviço de ingestão e processamento de dados em streaming. | Utilizado em pipelines de dados em tempo real na AWS. |
| **Azure Event Hubs** | Serviço de ingestão de eventos em larga escala. | Usado para fluxos de dados e telemetria no Azure. |
| **Google Pub/Sub** | Mensageria e ingestão de eventos na GCP. | Apoia arquiteturas orientadas a eventos e pipelines distribuídos. |
| **Apache Spark** | Processamento distribuído de grandes volumes de dados. | Pode ser executado em ambientes gerenciados nos três provedores. |
| **Apache Beam / Google Dataflow** | Modelo e serviço para pipelines de processamento de dados. | Dataflow é a implementação gerenciada da GCP para pipelines Beam. |
| **BigQuery** | Data warehouse analítico da GCP. | Usado para análise de grandes volumes de dados. |
| **Amazon S3, Azure Data Lake Storage e Google Cloud Storage** | Serviços de armazenamento em nuvem. | Servem de base para data lakes, artefatos, logs e dados de pipelines. |

Essas ferramentas ampliam a análise comparativa entre AWS, Azure e GCP, pois demonstram que o ciclo DevOps contemporâneo não se limita à entrega de software tradicional, mas também contempla dados, inteligência artificial, automação de workflows e governança de modelos.

---

## 4. Mapeamento das ferramentas por provedor de nuvem

### 4.1 AWS

No ecossistema AWS, destacam-se ferramentas voltadas à automação de infraestrutura, entrega contínua, monitoramento, segurança e dados. Entre elas estão **AWS CodePipeline**, **AWS CloudFormation**, **AWS CDK**, **Amazon EKS**, **AWS App Runner**, **AWS CloudWatch**, **AWS CloudTrail**, **AWS IAM**, **AWS Secrets Manager**, **AWS KMS**, **AWS Lake Formation**, **Amazon SageMaker**, **SageMaker Pipelines**, **AWS Kinesis** e **Amazon S3**.

Essas ferramentas permitem construir pipelines automatizados, provisionar recursos de forma reprodutível, implantar aplicações conteinerizadas, monitorar ambientes, aplicar políticas de segurança e operacionalizar cargas de trabalho de dados e machine learning.

### 4.2 Microsoft Azure

No ecossistema Azure, os artigos destacam a forte integração entre ferramentas corporativas, DevOps e governança. As principais ferramentas identificadas foram **Azure DevOps**, **Azure Pipelines**, **Azure Resource Manager**, **Bicep**, **Azure AKS**, **Azure Container Apps**, **Azure Monitor**, **Azure Log Analytics**, **Azure Automation**, **Azure Logic Apps**, **Azure Backup**, **Azure Policy**, **RBAC**, **Azure Key Vault**, **Azure Purview**, **Azure Machine Learning** e **Azure Event Hubs**.

A plataforma Azure se mostra especialmente relevante em cenários empresariais, integração com sistemas corporativos e automação de workloads complexos, como SAP, pois reúne recursos de infraestrutura, governança, monitoramento, segurança e pipelines em um ecossistema integrado.

### 4.3 Google Cloud Platform (GCP)

No ecossistema GCP, destacam-se ferramentas associadas à computação serverless, containers, dados e inteligência artificial. Foram identificadas **Google Cloud Build**, **Google Cloud Deployment Manager**, **Google Kubernetes Engine**, **Google Cloud Run**, **Google App Engine**, **Google Compute Engine**, **Google Cloud Operations Suite**, **Google Cloud Audit Logs**, **Google Cloud Secret Manager**, **Google Cloud KMS**, **Google Cloud Data Catalog**, **Google Vertex AI**, **Vertex Pipelines**, **AutoML**, **Google Pub/Sub**, **Google Dataflow**, **BigQuery** e **Google Cloud Storage**.

Essas ferramentas demonstram a relevância da GCP em arquiteturas cloud-native, serverless, orientadas a dados e inteligência artificial, especialmente quando se busca escalabilidade sob demanda, facilidade de implantação de containers e integração com serviços analíticos.

---

## 5. Referências dos artigos analisados

ABRAHAM, Anoop. **Analyzing the System Features, Usability, and Performance of a Containerized Application on Cloud Computing Systems**. Texas A&M University-San Antonio, 2023.

BALADARI, Venkata. **The Role of Software Developers in Transitioning On-Premises Applications to Cloud Platforms: Strategies and Challenges**. *Journal of Scientific and Engineering Research*, v. 8, n. 1, p. 270-278, 2021.

BANERJEE, Rahul; CHATTERJEE, Tathagata. **Comparative Evaluation of Cloud-Native and VM-Based CI/CD Pipelines for Automated DevOps Deployments**. *Asian Journal of Research in Computer Science*, v. 18, n. 11, p. 153-171, 2025.

DESHPANDE, Vaishnavi Udayrao. **Management of Self-Healing Systems for Multi-Cloud Deployments on Kubernetes**. MSc Research Project, National College of Ireland, 2024.

GADEKAR, Amruta; VARMA, Nayan; MORE, Prerana; SALUNKHE, Ashish. **Comparing Major Cloud Providers for AI/ML Workloads: AWS vs Azure vs GCP**. *International Journal of Advanced Research in Education and Technology*, v. 11, n. 3, 2024.

GUJJALA, Praveen Kumar Reddy. **Cloud Enabled Intelligent Enterprise Healthcare Framework with Machine Learning Based on Artificial Intelligence and Blockchain Governance**. *International Journal of Research Publications in Engineering, Technology and Management*, v. 8, n. 5, 2025.

JOYCE, Sheetal. **Accelerating Enterprise SAP Workload Performance and Automation Using Microsoft Azure Center for SAP Solutions Through Cloud Native Architecture Intelligent Orchestration and Infrastructure as Code**. *IACSE - International Journal of Information Technology*, v. 4, n. 1, p. 8-30, 2023.

KISHAN, Raj. **The Role of DevOps and Automation in Cloud Transition**. *International Journal of Computer Technology and Electronics Communication*, v. 5, n. 2, 2022.

MURPHY, Olga. **Adoption of Infrastructure as Code (IaC) in Real World: Lessons and Practices from Industry**. Master’s Thesis, JAMK University of Applied Sciences, 2022.

PASHIKANTI, Santosh. **Data Governance and Compliance in Cloud-Based Data Engineering Pipelines**. *International Journal of Leading Research Publication*, v. 5, n. 8, 2024.

RAVI, Vamsee Krishna et al. **Cloud-native DevOps Practices for SAP Deployment**. *International Journal of Research in Modern Engineering and Emerging Technology*, v. 10, n. 6, 2022.

VELDI, Santhosh Rao. **Infrastructure-as-Code with Scripting: A Technical Review**. *Journal of Computer Science and Technology Studies*, v. 7, n. 6, p. 345-352, 2025.
