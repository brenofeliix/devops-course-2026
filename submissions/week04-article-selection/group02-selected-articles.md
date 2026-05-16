# Estrutura de um Relatório de Revisão Sistemática

---

## 1. Página de Título

- **Título:** DevSecOps: Técnicas e Ferramentas de Segurança na Automação de Pipelines CI/CD
- **Autores:**
  - Arthur Esse Borges Xavier de Lima e Melo - 202426610050
  - Déborah Teles dos Santos - 202121640003
  - Gustavo Alves da Silva - 202426610004
- **Data:** 2026
- **Contato:** Informações do autor responsável.  

---

## 2. Resumo (Abstract)

- **Contexto:**

  O DevOps promove a aceleração da entrega de software, promovendo ciclos de integração e deploy cada vez mais curtos. Visando a era da IA na engenharia de software e o uso de agentes de IA cada vez mais frequente no ciclo de desenvolvimento, devemos nos atentar sobre como a segurança está sendo tratada no desenvolvimento de software e assim desmistificar que a segurança deve ser tratada de forma final e isolada no ciclo de desenvolvimento de software.

- **Objetivos:**

  Investigar de que forma a automação da análise estática de segurança (SAST) em pipelines de CI/CD contribui para reduzir custos, tempo de correção e riscos de exposição de vulnerabilidades do software em produção.
  
- **Métodos:**

  Foi realizada uma revisão sistemática da literatura utilizando strings de busca estruturadas direcionadas a quatro eixos principais: impacto do SAST em pipelines, abordagem Shift Left, comparação de ferramentas SAST e automação em DevSecOps. As buscas abrangeram bases de dados consolidadas como IEEE e ACM.
    
- **Resultados:**

  A estratégia de busca resultou na seleção inicial de 10 artigos relevantes publicados entre 2022 e 2025. Os estudos selecionados abordam desde benchmarks de ferramentas específicas (como o Semgrep) até o impacto do uso de Grandes Modelos de Linguagem (LLMs) e IA no ecossistema DevSecOps.

- **Conclusões:**
  
   A automação e a aplicação do conceito de Shift Left provam que agilidade e segurança não são conflitantes, mas complementares. O mapeamento e a categorização das ferramentas fornecem às empresas o embasamento necessário para adequar testes de segurança automatizados aos seus respectivos ambientes operacionais.

---

## 3. Introdução

- **Contexto:**
  
O modelo DevOps transformou a engenharia de software ao encurtar drasticamente os ciclos de integração e entrega contínua (CI/CD). Visando a era da IA na engenharia de software e a introdução frequente de agentes inteligentes no ciclo de vida do desenvolvimento, surge a necessidade urgente de repensar como a segurança é tratada. Tradicionalmente vista como um gargalo final e isolado, a segurança precisa ser integrada de forma fluida e automatizada ao processo.

- **Objetivos:**
  
O objetivo fundamental desta revisão é responder à seguinte Questão de Pesquisa Principal (RQ):

RQ: De que forma a automação da análise estática de segurança (SAST) em pipelines de CI/CD contribui para reduzir custos, tempo de correção e riscos de exposição de vulnerabilidades do software em produção?

Para desdobrar e aprofundar a investigação, foram definidas três Questões de Pesquisa Secundárias:

RQ1: Como a identificação imediata de falhas de segurança nas fases iniciais do desenvolvimento (Shift Left) contribui para a agilidade da correção e a redução do acúmulo de erros?

RQ2: Quais critérios podem ser usados para categorizar ferramentas SAST de acordo com diferentes contextos, como linguagens suportadas, tipos de vulnerabilidades detectadas, facilidade de configuração, modelo de licenciamento e recursos de integração?

RQ3: Como a integração de ferramentas de SAST em pipelines de CI/CD impacta a qualidade da verificação de segurança no ciclo de desenvolvimento de software?
  
- **Justificativa:**

Este estudo justifica-se pelo seu potencial em demonstrar que rapidez de entrega e conformidade de segurança podem coexistir de forma complementar quando apoiadas pela automação correta. Ao sintetizar a literatura recente, o trabalho oferece um guia prático para organizações analisarem as opções de ferramentas de análise estática de código, permitindo a escolha daquela que melhor se adequa ao seu ambiente técnico e acelerando a entrega de softwares genuinamente seguros.

---

## 4. Métodos

- **Protocolo e Registro:**  

 A presente revisão sistemática da literatura foi conduzida seguindo as diretrizes metodológicas propostas por Barbara Kitchenham. O protocolo do estudo foi estruturado e definido de forma colaborativa pelos integrantes do grupo. Durante a fase de planejamento, determinou-se o tema central da pesquisa, a Questão de Pesquisa Principal (RQ), as três Questões de Pesquisa Secundárias e as strings de busca. Adicionalmente, estabeleceu-se o processo de seleção dos artigos de acordo com critérios claros de elegibilidade, garantindo a estrita coerência e o alinhamento dos dados com o tema investigado.

- **Critérios de Elegibilidade:**  
Para guiar a seleção dos estudos, estruturou-se o modelo PICOS da seguinte forma:
  - População: Ciclo de Vida de Desenvolvimento de Software (SDLC), especificamente ambientes que utilizam automação e pipelines de CI/CD.

  - Intervenção: Automação da análise estática de segurança (SAST) e adoção de práticas baseadas em Shift Left.

  - Comparação: Diferentes ferramentas SAST de mercado, abordagens tradicionais de segurança vs. automatizadas e o uso de SAST.

  - Resultados (Outcomes): Redução de custos e tempo de correção de bugs de segurança, mitigação de riscos em produção, melhoria na qualidade da verificação e agilidade no desenvolvimento.

  - Tipo de estudo: Revisões de literatura, estudos empíricos, pesquisas de opinião da indústria, benchmarks e relatórios de conferências científicas.

- **Fontes de Informação:**  
 ...

- **Estratégia de Busca:**  
  Foram elaboradas 4 strings de busca específicas, alinhadas diretamente às RQs do projeto:
  
  1 - ("SAST" OR "Static Application Security Testing") AND ("CI/CD" OR "continuous integration" OR "continuous delivery") AND ("vulnerability" OR "security")

  2 - ("Shift Left" OR "shift-left security") AND ("DevSecOps" OR "secure development") AND ("vulnerability detection" OR "early detection" OR "SDLC")

  3 - ("SAST tools" OR "static analysis tools") AND (comparison OR evaluation OR benchmark) AND ("vulnerability detection" OR "false positive" OR "security testing")

  4 - (DevSecOps	("DevSecOps") AND ("automation" OR "automated security testing") AND ("pipeline" OR "software development lifecycle" OR "SDLC")
  
- **Seleção dos Estudos:**
  
 O processo de triagem consistiu na aplicação prática das strings nas bases de dados selecionadas, realizando a leitura analítica e a filtragem com base nos critérios de inclusão e exclusão analisando se estavam de acordo com tema de DevSecOps, SAST, CI/CD. Como resultado final desse fluxo, 10 artigos foram selecionados para compor o escopo principal da revisão.

- **Extração de Dados:**

 Os dados foram coletados e organizados de forma sistemática a partir das informações principais dos artigos selecionados. Com o objetivo de fornecer subsídios para responder diretamente às questões de pesquisa (RQs) estabelecidas, foram extraídos os seguintes elementos de cada estudo: Título do artigo, Nome dos autores, Ano de publicação, Fonte de publicação (conferência, periódico ou indexador científico), Tema central do estudo (ex: benchmarks de ferramentas, estudos empíricos, revisões da literatura), Relação com DevOps/DevSecOps (integração de segurança e abordagem Shift Left em pipelines de CI/CD), Contribuição do artigo para a revisão (principais achados sobre redução de custos, tempo de correção e mitigação de vulnerabilidades).
