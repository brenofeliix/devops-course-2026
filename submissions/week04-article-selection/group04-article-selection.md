# Relatório de Revisão Sistemática

## 1. Página de Título

**Título:** Revisão Sistemática sobre ChatOps: Automação de tarefas DevOps através de robôs de mensagens instantâneas.

**Autores:**

- Vinicius Cristovão Bianchini Soares;

- Leonardo Cavalcante;

- Davi Santos de Deus.

**Afiliação:** Disciplina DevOps – Tópicos Especiais em Computação IV.

**Data:** 2026.

**Contato:** vinicius.soares@aluno.ufr.edu.br; davi.deus@aluno.ufr.edu.br. (* vai ter adicionado o outro )

---

## 2. Resumo (Abstract)

**Contexto:**O ChatOps emergiu como um modelo de colaboração que conecta pessoas, processos, ferramentas e automação em um fluxo de trabalho transparente através de plataformas de mensagens. No contexto DevOps, essa abordagem facilita a automação de tarefas operacionais, o monitoramento em tempo real e a resposta rápida a incidentes, integrando-se diretamente a ferramentas de CI/CD e infraestrutura.

**Objetivos:**Esta revisão sistemática tem como objetivo analisar estudos primários relacionados ao uso de ChatOps aplicado ao DevOps, observando aspectos como automação de tarefas, colaboração entre equipes, resposta a incidentes, integração com pipelines de CI/CD e o impacto do uso de bots inteligentes (incluindo LLMs) na produtividade e redução de erros.

**Métodos:**A revisão foi conduzida com base nas diretrizes de Barbara Kitchenham para revisões sistemáticas em Engenharia de Software. As buscas foram realizadas no Google Acadêmico utilizando strings específicas em inglês. A seleção dos estudos seguiu critérios de elegibilidade baseados na leitura de títulos, resumos e análise da natureza primária dos estudos. Os dados extraídos foram organizados por título, autores, ano, fonte e contribuição para o tema.

**Resultados:**Foram selecionados 12 artigos primários que abordam desde implementações técnicas de bots para diagnósticos de pipelines até estudos empíricos sobre a melhoria da colaboração em equipes de resposta a incidentes. Os resultados indicam que o ChatOps reduz o MTTR (Mean Time To Repair) e aumenta a visibilidade das operações para toda a equipe.

**Conclusões:**A revisão demonstrou que o ChatOps é uma peça fundamental para a maturidade DevOps, pois centraliza o controle operacional em canais de comunicação compartilhados. A integração de Inteligência Artificial e modelos de linguagem (LLMs) é a tendência atual, permitindo diagnósticos mais explicáveis e suporte proativo aos desenvolvedores.

---

## 3. Introdução

**Contexto:**Com a crescente complexidade dos ambientes de software, a necessidade de comunicação eficiente e automação ágil tornou-se crítica. O DevOps promove a integração entre desenvolvimento e operações, mas muitas vezes a execução de tarefas e o monitoramento ainda ocorrem de forma fragmentada entre diversas ferramentas. O ChatOps surge para resolver esse problema, transformando o chat da equipe no console de controle da infraestrutura.

**Objetivos:**O objetivo desta revisão é analisar como o modelo ChatOps é abordado na literatura científica, identificando suas contribuições para a automação, colaboração e eficiência operacional. As principais questões de pesquisa são:

1. Como a adoção de ChatOps contribui para a automação de tarefas operacionais e para a melhoria da colaboração entre equipes?

1. Quais são as principais ferramentas e plataformas de mensagens utilizadas na implementação de ChatOps?

1. De que forma o uso de bots reduz a ocorrência de erros humanos em processos operacionais?

1. Quais são os impactos mensuráveis do ChatOps na velocidade de resposta a incidentes?

**Justificativa:**A realização desta revisão é importante para sistematizar o conhecimento sobre uma prática que, embora popular na indústria, necessita de maior consolidação acadêmica quanto aos seus benefícios reais e limitações. A análise dos artigos selecionados auxilia na identificação de melhores práticas para organizações que buscam implementar a automação orientada por conversação.

---

## 4. Métodos

**Protocolo e Registro:**A revisão seguiu o método de Barbara Kitchenham. O protocolo definiu o tema (ChatOps), as questões de pesquisa (RQ1-RQ4), strings de busca, critérios de inclusão (estudos primários, aderência ao tema) e exclusão (estudos secundários, blogs sem base técnica, artigos fora do escopo DevOps).

**Critérios de Elegibilidade (Modelo PICOS):**

- **População:** Equipes de desenvolvimento e operações (DevOps), engenheiros de software e administradores de sistemas.

- **Intervenção:** Implementação de práticas de ChatOps, uso de bots de mensagens e ferramentas de automação conversacional.

- **Comparação:** Fluxos de trabalho manuais vs. automatizados via chat; ferramentas tradicionais de CLI/GUI vs. interfaces de conversação.

- **Resultados (Outcomes):** Melhoria na colaboração, redução de erros, agilidade na resposta a incidentes e automação de CI/CD.

- **Tipo de estudo:** Artigos científicos primários, estudos de caso, experimentos e implementações técnicas.

**Fontes de Informação:**As buscas foram centralizadas no Google Acadêmico devido à sua abrangência em bases como IEEE Xplore, ACM Digital Library e ResearchGate.

**Estratégia de Busca:**Foram utilizadas as seguintes strings em inglês:

1. `("ChatOps" AND "DevOps" AND "automation") AND ("Slack" OR "Microsoft Teams" OR "Discord") AND ("CI/CD pipeline")`

1. `("ChatOps" AND "team collaboration" AND "incident response") AND ("chatbot" OR "messaging bot")`

1. `("process automation" AND "DevOps" AND "ChatOps") AND ("integration" OR "system monitoring")`

1. `("ChatOps" AND "productivity") AND ("software engineering" AND "error reduction")`

**Seleção dos Estudos:**A seleção ocorreu em três fases:

1. Filtragem inicial por título e palavras-chave.

1. Análise qualitativa dos resumos para garantir que o estudo fosse primário e relevante.

1. Leitura rápida do conteúdo técnico para extração dos dados finais. Ao final, 12 artigos foram selecionados.

**Extração de Dados:**Os dados foram organizados considerando: título, autores, ano, fonte, tema central, relação com DevOps/ChatOps e principais tecnologias (ex: LLMs, Slack, Jenkins).

