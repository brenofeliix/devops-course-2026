# Week 05 – Article Summary

Tema do Artigo:**DevSecOps: Técnicas e Ferramentas de Segurança na 
Automação de Pipelines CI/CD**

**Grupo:** 02

- ArthuR Esse Borges Xavier de Lima e Melo - 202426610050

- Déborah Teles dos Santos - 202121640003

- Gustavo Alves da Silva - 20242661004

---

## 1. Apresentação

Este documento apresenta o resumo dos artigos selecionados para a **Semana 05 - Resumo dos Artigos**,  dentro do tema **“DevSecOps: Técnicas e Ferramentas de Segurança na Automação de Pipelines CI/CD”**.

Os artigos escolhidos abordam temas diretamente relacionado à integração de segurança no ciclo de desenvolvimento de software, como:

- Integração de testes de segurança em pipelines CI/CD;
- Análise estática (SAST);
- Estratégia de antecipação de segurança (Shift-Left);
- Barreiras técnicas e humanas na adoção de ferramentas de segurança;
- Customização de regras de detecção para melhoria de desempenho;

## 2. Resumo dos Artigos Selecionados

### Artigo 01- Implementation of DevSecOps by Integrating Static and Dynamic Security Testing in CI/CD Pipelines

**Título do artigo:** Implementation of DevSecOps by Integrating Static and Dynamic Security Testing in CI/CD Pipelines
**Autores:** Agung Maulana Putra e Herman Kabetta

#### Objetivo 

O artigo tem como objetivo integrar segurança proativa em ambientes ágeis para reduzir o tempo de lançamento e garantir que vulnerabilidades sejam detectadas precocemente.

#### Método 

Estudo de caso utilizando ferramentas como GitLab CI/CD, Docker, onde foram automatizados testes de análise estática, com NJSSCAN e dinâmica com OWASP ZAP em um sistema web desenvolvido com Node.js e Flutter.

#### Resultados

Com automação o tempo de implantação foi reduzido de várias horas para minutos, identificando com sucesso vulnerabilidades críticas antes do lançamento.

#### Contribuição principal

A principal contribuição do artigo é demonstrar a eficácia prática da abordagem shift-Left, provando que a automação da segurança em pipelines CI/CD aumenta a eficiência do desenvolvedor sem comprometer a qualidade ou a proteção do código


---

### Artigo 02 - Automated security testing in DevSecOps pipelines: Integrating AI-based vulnerability discovery and compliance validation

**Título do artigo:** Automated security testing in DevSecOps pipelines: Integrating AI-based vulnerability discovery and compliance validation
**Autor:** Tim Abdiukov

#### Objetivo 

O artigo tem como objetivo investigar o papel essencial dos testes de segurança automatizados em ambientes de software ágeis e modernos, com foco em como a Inteligência Artificial pode ser utilizada para identificar vulnerabilidades e verificar a conformidade regulatória em pipelines DecSecOps.

#### Método

Estudo de revisão que avalia ferramentas de teste (SAST, DAST, e IAST) e processos de conformidade automatizados (GDPR, HIPAA, NIST) integrados à IA

#### Resultados

O estudo conclui que a IA melhora a precisão na detecção de ameaças, reduz falsos positivos e permite uma postura de segurança proativa e escalável.

#### Contribuição principal

A principal contribuição do artigo é apresentar o uso da IA como essencial para lidar com a complexidade regulatória moderna e a sofstificação das ciberameaças em ambientes ágeis

---

### Artigo 03- Semgrep*: Improving the Limited Performance of Static Application Security Testing (SAST) Tools

**Título do artigo:** Semgrep*: Improving the Limited Performance of Static Application Security Testing (SAST) Tools
**Autores:** Gareth Bennett, Tracy Hall, Emily Winter e Steve Counsell

#### Objetivo 

O objetivo do artigo é avaliar e melhorar a detecção de ferramentas SAST populares (CodeQL, Snyk, Semgrep, FindSecBugs) em falhas reais

#### Método

O artigo faz análise manual de falhas perdidas e criação de 29 novas regras customizadas para o Semgrep

#### Resultados

O estudo conclui que o Semgrep* (versão aprimorada) aumentou a detecção em 181%, superando a união de todas as outras ferramentas juntas

#### Contribuição principal

A contribuição principal do estudo demonstra que regras personalizadas são mais eficientes que empilhar múltiplas ferramentas padrão no pipeline

---

### Artigo 04- Barriers to Using Static Application Security Testing (SAST) Tools: A Literature Review

**Título do artigo:** Barriers to Using Static Application Security Testing (SAST) Tools: A Literature Review
**Autores:** Zachary Wadhams, Clemente Izurieta e Ann Marie Reinhold

#### Objetivo 

O estudo tem como objetivo identificar por que muitos desenvolvedores hesistam em adotar ferramentas de análise estática (SAST) em seus fluxos de trabalho e quais são os problemas específicos que levam ao abandono dessas ferramentas

#### Método

Revisão sistemática de literatura analisando 89 artigos publicados entre 2019 e 2023 focados na experiência do desenvolvedor com SAST

#### Resultados

Os resultados indicam que a maior barreira foi a alta taxa de falso positivos, o que gera fadiga de alertas e perda de confiança na ferramenta, outras barreiras incluem saídas de dados confusas, configuração demorada e falta de sugestões automáticas de correção

#### Contribuição principal

A principal contribuição do estudo é mostrar que a adoção não depende não apenas de melhorias técnicas, mas de uma melhor compreensão dos fatores humanos e da usabilidade para os desenvolvedores

---

### Artigo 05- Comparison of Static Application Security Testing Tools and Large Language Models for Repo-level Vulnerability Detection
**Título do artigo:** Comparison of Static Application Security Testing Tools and Large Language Models for Repo-level Vulnerability Detection
**Autores:** Xin Zhou, Duc-Manh Tran, Thanh Le-Cong, Ting Zhang, Ivana Clairine Irsan, Joshua Sumarlin, Bach le, David, Lo

#### Objetivo 

O objetivo do artigo é comparar a eficácia de 15 ferramentas tradicionais de SAST contra 12  modelos de linguagem de grande escala(LLMs) na detecção de vulnerabilidades em nível de repositório.

#### Método

Estudo experimental comparativo utilizando conjunto de dados de vulnerabilidade reais em Java, C e Python, analisando taxas de detecção e falsos positivos.

#### Resultados

O estudo conclui que ferramentas SAST tradicionais possuem baixas taxas de detecção, mas poucos falsos positivos. Já os LLMs detectam entre 90% e 100% das vulnerabilidades, porém sofrem com taxas de falsos positivos extremamente altas.

#### Contribuição principal

É o primeiro estudo a comparar SAST e LLMs em repositórios inteiros, sugerindo que o futuro da detecção de vulnerabilidades reside na combinação dessas duas abordagens para mitigar as fraquezas individuais de cada uma

---

### Artigo 06- DevSecOps: Integrating Security Into the DevOps Lifecycle with AI and Automation
**Título do artigo:** DevSecOps: Integrating Security Into the DevOps Lifecycle with AI and Automation
**Autores:** Praveen Kumar Thopalle

#### Objetivo 

O artigo analisa a integração de protocolos de segurança automatizados e IA para reduzir vulnerabilidades dentro de um pipeline CI/CD.

#### Método

O estudo analisa os fluxos de trabalho DevSecOps e o uso de Processamento de Linguagem Natural (NLP) e modelos como CodeBERT para análise semântica de código.

#### Resultados

A implementação reduziu o tempo de resposta a incidentes em 45% e diminuiu em 60% no número de vulnerabilidade que chegavam ao ambiente de produção. 

#### Contribuição principal

A principal contribuição é mostrar o impacto quantitativo da automação e da IA na criação de sistemas de software mais resilientes e autônomos

---

### Artigo 07- Static Analysis Techniques for Embedded, Cyber-Physical, and Electronic Software Systems: A Comprehensive Survey

**Título do artigo:** Static Analysis Techniques for Embedded, Cyber-Physical, and Electronic Software Systems: A Comprehensive Survey
**Autores:** Maksim Iavich, Tamari Kuchukhidze e Audrius Lopata

#### Objetivo 

O artigo tem como objetivo fornecer uma visão abrangente sobre técnicas de análises estáticas aplicadas em sistemas embarcados, sistemas ciberfísicos e softwares eletrônicos, destacando métodos, aplicações, desafios e tendências futuras

#### Método

O estudo realiza uma revisão sistemática da literatura seguindo as diretrizes PRISMA, analisando publicações entre 2015 e 2025.

#### Resultados

O estudo desenvolveu uma taxonomia que mapeia técnicas (análise de fluxo de dados, modelagem, etc.) aos seus domínios de aplicações e analisa os compromissos técnicos entre integridade, precisão e escalabilidade.

#### Contribuição principal

A principal contribuição do artigo é oferecer um guia estruturado para orientar pesquisas futuras e práticas industriais no desenvolvimento de sistemas eletrônicos críticos e confiáveis, destacando tendências como a análise híbrida estática-dinâmica

---
