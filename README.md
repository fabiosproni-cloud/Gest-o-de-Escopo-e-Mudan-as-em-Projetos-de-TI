# Miniguia de Estudos com NotebookLM: Gestão de Escopo e Mudanças em Projetos de TI

## 🎯 Contexto e Objetivos
A gestão eficiente do escopo e o controle de mudanças são fundamentais para o sucesso de projetos em ambientes corporativos de TI e operações. Lidar com atualizações de status, redefinição de requisitos, alterações de cronograma e avaliação de cancelamentos exige um processo estruturado.
O objetivo deste caderno temático é criar um guia rápido e prático de consulta sobre as melhores práticas para gerenciar mudanças de escopo em projetos de tecnologia, utilizando o NotebookLM como ferramenta de curadoria e síntese de conhecimento.

## 📚 Curadoria de Fontes
Para a construção deste material, foram selecionadas fontes confiáveis que abordam metodologias ágeis e tradicionais de gestão de projetos. Os seguintes documentos foram carregados no NotebookLM:
1. *https://www.youtube.com/watch?v=669guD_wAXc*
2. *https://www.youtube.com/watch?v=H4eCbynW6Po*
3. *https://www.youtube.com/watch?v=4Iq7SIvX99o*
4. *https://acervodigital.ufpr.br/xmlui/handle/1884/61309*
5. *https://www.youtube.com/watch?v=hOCCNeegOjA*

## 🛠️ Engenharia de Prompts e "Cicatrizes"

Durante o desenvolvimento deste guia, documentei as interações com o NotebookLM para demonstrar a evolução do pensamento crítico na extração de informações.

**Tentativa 1 (Prompt Básico):**
* **Prompt:** "Faça um resumo sobre gestão de escopo e como lidar com mudanças."
* **Resposta/Troubleshooting:** A resposta da IA foi extremamente genérica, focando apenas em definições teóricas de escopo, sem abordar a complexidade do dia a dia corporativo.
* **Cicatriz/Aprendizado:** Percebi que precisava dar um contexto profissional para a IA e pedir ações específicas, focadas em comunicação de status e processos práticos.

**Tentativa 2 (Prompt Refinado):**
* **Prompt:** "Atue como um gerente de projetos de TI lidando com contas corporativas complexas. Com base nas fontes, crie um checklist de comunicação para quando o cliente solicita uma mudança de requisitos que impacta o cronograma. Como devo estruturar essa atualização de status para avaliar os impactos?"
* **Resposta:** *[Checklist de Comunicação de Mudança de Requisitos
[ ] Registro Formal: Exigir o pedido por escrito, contendo o detalhamento da mudança e a justificativa de negócio
.
[ ] Classificação do Escopo: Identificar se a solicitação altera o escopo do produto (funcionalidades/especificações) ou o escopo do projeto (trabalho, fases e entregas)
.
[ ] Análise Multidisciplinar de Impacto: Avaliar o impacto em prazos, custos, esforço e riscos
, além dos reflexos na infraestrutura de TI e nas pessoas afetadas
.
[ ] Validação Benefício vs. Esforço: Confirmar se os benefícios esperados superam os custos e prejuízos operacionais
, mantendo o alinhamento com a estratégia do projeto
.
[ ] Regra dos 30%: Verificar se a mudança ultrapassa 30% da EAP/WBS ou do cronograma. Se sim, avaliar se vale cancelar o projeto atual e iniciar um novo
.
[ ] Submissão à Governança (ITIL): Encaminhar o parecer ao Gerente de Mudanças e ao Conselho Consultivo de Mudança (CAB)
, obtendo a aprovação formal do patrocinador (sponsor)
.
[ ] Comunicação e Prontidão: Engajar as equipes envolvidas como embaixadores da mudança, fornecendo informações transparentes, suporte e treinamento
.
Estrutura da Atualização de Status (Status Update Report)
Contexto e Justificativa: ID da solicitação, descrição detalhada da alteração, motivo do cliente
 e classificação entre escopo do produto ou projeto
.
Matriz de Impactos: Estimativa do acréscimo de prazo (cronograma e milestones), custos/recursos adicionais
 e riscos organizacionais/técnicos
.
Análise de Valor e Viabilidade: Relação benefício vs. esforço
, alinhamento com o Termo de Abertura
 e indicador de variação da EAP (alerta para mudanças >30%)
.
Parecer de Governança e Decisão: Recomendação do Gerente de Mudanças/CAB
 e campo de assinatura do patrocinador para aceite ou rejeição formal
]*
* **Evolução:** A resposta foi muito superior. A IA forneceu um passo a passo claro sobre como mapear a mudança, avaliar o impacto no tempo e custo, e como formalizar isso com as partes interessadas.

## 📘 Miniguia de Estudo: Gestão de Mudanças

### Resumo Estruturado do Assunto
* **Definição Clara Inicial:** O escopo deve detalhar exatamente o que está incluído e o que *não* está incluído no projeto antes do início do desenvolvimento.
* **Avaliação de Impacto:** Qualquer nova solicitação deve passar por uma análise rigorosa de como afeta o cronograma atual, os recursos alocados e os requisitos técnicos.
* **Comunicação de Status:** É vital manter um fluxo transparente de atualizações sobre o andamento das mudanças aprovadas.
* **Documentação de Processos:** Alterações em fluxogramas e regras de negócio precisam ser documentadas com precisão e clareza para a equipe técnica.

### Glossário
* **Baseline (Linha de Base):** A versão aprovada de um escopo, cronograma ou custo, usada como referência para medir o desempenho do projeto.
* **Change Request (Solicitação de Mudança):** Documento formal submetido para alterar algum documento, entregável ou linha de base do projeto.
* **Workflow:** Sequência de passos por onde passa uma requisição ou processo. É crucial garantir a clareza nas etapas automatizadas, documentando explicitamente ações como: *"Sistema Gera a Tarefa de Workflow"*.
* **Scope Creep (Aumento de Escopo):** A expansão não controlada do escopo do projeto sem os devidos ajustes de tempo e custo.

### 🤖 Prompts Reutilizáveis
Caso precise revisar o tema no futuro, utilize estes prompts no seu NotebookLM:
1. *"Analise o documento de requisitos anexo e identifique possíveis gargalos no cronograma caso o cliente solicite a alteração da funcionalidade X."*
2. *"Com base nas diretrizes do projeto, redija uma proposta de atualização de status comunicando uma mudança no escopo e uma avaliação de cancelamento de uma entrega específica, mantendo um tom corporativo e focado em soluções."*
