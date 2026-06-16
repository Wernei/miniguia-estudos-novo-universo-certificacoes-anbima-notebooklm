# Miniguia de Estudos: O Novo Universo de Certificações ANBIMA com NotebookLM

---

## Contexto e Objetivos

O mercado financeiro brasileiro exige constante atualização. Recentemente, a ANBIMA promoveu uma das maiores reformulações em sua grade de certificações profissionais, modificando as certificações CPA, introduzindo a trilha **C-Pro** e reestruturando os exames de gestão (**CGA** e **CGE**). Para quem busca ingressar ou evoluir no setor, compreender o que mudou, os novos pré-requisitos e o peso de cada conteúdo é um desafio complexo, e esse projeto visa auxiliar conforme veremos a seguir.

Este projeto foi desenvolvido como parte do **Bootcamp Bradesco - GenAI, Dados & Cyber** na **DIO (Digital Innovation One)** e tem como objetivo aplicar os conceitos de **Aprendizagem Ativa** e **Engenharia de Prompts**. 
Utilizando o **NotebookLM** como um ecossistema de estudo privado alimentado por fontes oficiais e estruturadas, este repositório centraliza um caderno temático inteligente para apoiar a preparação estratégica para os novos exames da ANBIMA e entender seus mecanismos de avaliação.

### Objetivos de Estudo:
1. Mapear a transição entre o modelo antigo de certificações e as novas trilhas (CPA, C-Pro, CFG, CGA e CGE).
2. Analisar a estrutura de cobrança prática dos exames com base em simuladores interativos e guias de elaboração de questões.
3. Compreender os requisitos de governança de dados e privacidade (LGPD) adotados pela associação no ecossistema educacional.

---

## Curadoria de Fontes

Para garantir o mais alto nível de precisão, o NotebookLM foi alimentado com documentos oficiais extraídos diretamente do portal da ANBIMA, incluindo programas detalhados, códigos de conduta e templates técnicos de avaliação:

### Programas Detalhados e Editais
* [Programa Detalhado - CPA ANBIMA](https://www.anbima.com.br/data/files/6A/52/6F/A1/BED73910B07B2739B82BA2A8/Programa-Detalhado-CPA-ANBIMA.pdf)
* [Programa Detalhado - C-Pro I](https://www.anbima.com.br/data/files/9B/82/78/94/12793910A5947839EA2BA2A8/Programa-Detalhado-C-Pro-I.pdf)
* [Programa Detalhado - C-Pro R](https://www.anbima.com.br/data/files/38/52/0D/A1/BED73910B07B2739B82BA2A8/Programa-Detalhado-C-Pro-R-ANBIMA.pdf)
* [Programa Detalhado - CGA](https://www.anbima.com.br/data/files/B8/63/5B/E0/CB24C910CF6A83C9F82BA2A8/Programa-Detalhado-CGA.pdf)
* [Programa Detalhado - CGE](https://www.anbima.com.br/data/files/DF/A3/96/93/F924C910CF6A83C9F82BA2A8/Programa-Detalhado-CGE.pdf)
* [Edital dos Exames de Certificação Profissional](https://www.anbima.com.br/data/files/98/96/A6/10/9C24C910CF6A83C9F82BA2A8/Edital-dos-Exames-de-Certificacao-Profissional-Anbima.pdf)

### Cadernos de Questões e Guias de Estudo
* [Guia de Elaboração de Questões ANBIMA](https://www.anbima.com.br/data/files/40/C6/A8/5E/FCBF891048BA3F89EA2BA2A8/Guia-de-Elaboracao-de-Questao-Certificacoes-Anbima.pdf)
* [Caderno de Questões - CPA](https://www.anbima.com.br/data/files/DF/86/EE/B6/EB6F891048BA3F89EA2BA2A8/Caderno-de-questoes-CPA.pdf)
* [Caderno de Questões - C-Pro R](https://www.anbima.com.br/data/files/07/E7/B8/A3/0C6F8910C03A3F89B82BA2A8/Caderno-de-questoes-C-Pro-R.pdf)
* [Caderno de Questões - C-Pro I](https://www.anbima.com.br/data/files/28/67/1B/28/FB6F8910C03A3F89B82BA2A8/Caderno-de-questoes-C-Pro-I.pdf)

### Documentação Técnica, Regulatória e Arquivos Multiformato
* [cite_start]**Termo-de-Consentimento-Crianca-e-Adolescente.doc**: Documento que regula o tratamento de dados pessoais para cadastro no ANBIMA Edu e exames para menores[cite: 1, 4].
* [cite_start]**Template-Arvore-de-decisao-Certificacoes-Anbima.pdf**: Modelo estrutural em formato JSON que mapeia árvores de diálogo e tomadas de decisão em avaliações interativas.
* [Código de Conduta e Ética para Pessoas Certificadas](https://www.anbima.com.br/data/files/DB/93/03/7F/269CE8107ECD2CE8B82BA2A8/Codigo-Conduta-Etica-Pessoas-Certificadas.pdf)
* [Formulário Oficial de Fórmulas das Certificações](https://www.anbima.com.br/data/files/D6/46/1D/FD/3D17C910BF9166C9BA2BA2A8/Formulas-Certificacoes-Anbima.pdf)

---

## 🛠 Engenharia de Prompts e "Cicatrizes"

O NotebookLM trabalha ancorado estritamente nas fontes fornecidas. Ao adicionar arquivos de estruturas variadas (como JSON de árvores de decisão e textos jurídicos de consentimento), a estratégia de prompts precisou ser refinada para lidar com formatos não tradicionais de texto.

### Teste de Prompt 1: Engenharia Reversa de Questões Interativas (JSON)
* **Prompt Inicial (Simplista e ingênuo):** *"Me explica o PDF da árvore de decisão."*
* [cite_start]**Problema Encontrado:** A IA descreveu o arquivo como um bloco de texto confuso e não compreendeu a lógica de navegação das ramificações (`next`) e das pontuações (`score`) vinculadas às escolhas do usuário[cite: 26, 27].
* [cite_start]**Prompt Refinado (Estratégico):** *"Analise a estrutura JSON contida no documento 'Template-Arvore-de-decisao-Certificacoes-Anbima.pdf'[cite: 13, 15]. [cite_start]Com base nas chaves 'prompt', 'options', 'score' e 'next' [cite: 21, 23, 26, 27][cite_start], simule no chat a mesma dinâmica de diálogo interpretando o papel de Carlos[cite: 19]. [cite_start]Aguarde eu escolher entre as alternativas A, B, C ou D para avançar para o próximo nó ('next') e me dê o feedback com a justificativa oficial do arquivo[cite: 23, 27, 28]."*
* [cite_start]**Resultado com o Refinamento:** O NotebookLM transformou-se em um simulador interativo de exames práticos, conduzindo o fluxo de conversação conforme o roteiro oficial estabelecido pela ANBIMA[cite: 13].

### Teste de Prompt 2: Extração de Regras de Conformidade (LGPD)
* **Prompt Inicial (Simplista e ingênuo):** *"O que diz o documento sobre menores de idade?"*
* **Problema Encontrado:** A resposta misturou conceitos gerais de maioridade civil com as regras específicas de tratamento de dados institucionais da ANBIMA.
* [cite_start]**Prompt Refinado (Estratégico):** *"Baseando-se estritamente no documento 'Termo-de-Consentimento-Crianca-e-Adolescente.doc' [cite: 1][cite_start], quais são as finalidades explícitas para as quais a ANBIMA realiza o tratamento de dados de menores[cite: 4]? [cite_start]Cite as operações envolvidas descritas no texto[cite: 10]."*
* [cite_start]**Resultado com o Refinamento:** A IA mapeou de forma exata as finalidades como "Cadastro no ANBIMA Edu" e processos correlatos a exames (inscrição, agendamento, pagamento, realização de prova) [cite: 4][cite_start], além de listar as operações legais de tratamento (coleta, armazenamento, eliminação, etc.)[cite: 10].

---

## Como Replicar este Projeto no NotebookLM (Passo a Passo)

Se você nunca utilizou o NotebookLM, não se preocupe! Ele funciona como um assistente de inteligência artificial privado. Em vez de buscar informações na internet aberta, ele responderá suas dúvidas baseando-se **apenas** nos documentos que nós enviarmos para ele.

Siga os passos abaixo para configurar o seu ambiente de estudos idêntico ao deste projeto:

### 1. Criar o seu Caderno Virtual
1. Acesse o site oficial: [NotebookLM da Google](https://notebooklm.google/).
2. Faça login utilizando qualquer conta Gmail de sua preferência.
3. Na tela inicial (Painel), clique no botão **"+" (Novo caderno / New notebook)**.

### 2. Alimentar a IA com as Fontes do Projeto
Assim que o caderno for criado, uma janela pedirá para você adicionar fontes. Vamos carregar os arquivos deste repositório divididos em dois formatos:

#### Opção A: Links da Web (Para os sites oficiais da ANBIMA)
1. Na tela de fontes do NotebookLM, selecione **Link da Web** (ou *Website*).
2. Copie os links da seção **Curadoria de Fontes** deste README (como os Programas Detalhados) e cole-os um por um na plataforma.

#### Opção B: Upload de Arquivos (Para os arquivos baixados deste repositório)
Baixe os arquivos da pasta `/fontes` deste repositório para o seu computador e envie-os para o NotebookLM da seguinte forma:
1. Para o arquivo `Template-Arvore-de-decisao-Certificacoes-Anbima.pdf`: Selecione a opção **Fazer upload de arquivo** (ou *File upload*) e envie o PDF.
2. Para o arquivo `Termo-de-Consentimento-Crianca-e-Adolescente.doc`: Abra o arquivo no seu computador, copie todo o texto dele, escolha a opção **Texto Copiado** no NotebookLM, cole o conteúdo e salve com o mesmo nome do arquivo.
3. Para as planilhas `Formulas-dos-exames-de-certifcacoes-Anbima-CEA-CFG-CGA-CGE.xlsx` e `Matriz-Avaliacao-Anbima.xlsx`: A melhor forma de garantir a leitura correta pela IA é salvá-las como PDF no seu Excel (Salvar como -> PDF) ou enviá-las para o seu Google Drive e importá-las diretamente no NotebookLM através da opção **Google Drive**.

> **Importante:** Após carregar tudo, você verá a lista completa de documentos no painel esquerdo da tela. Certifique-se de que todos estão marcados com um "check" azul.

### 3. Fixar o Guia de Estudos (Notas)
1. No painel direito da tela do NotebookLM, procure pela seção **Notas** (ou *Notes*).
2. Clique em **Criar nota** (ou *Create note*).
3. Copie o conteúdo da seção **Miniguia de Estudo** (Resumos e Glossário) deste repositório e cole na nota para ter uma consulta rápida sempre visível.

### 4. Interagir e Testar os Prompts
Com tudo configurado, você usará a barra de chat na parte inferior da tela para estudar:
1. Vá até a seção **Engenharia de Prompts** deste repositório.
2. Copie um dos prompts refinados (as mensagens completas dentro das aspas).
3. Cole no chat do NotebookLM e dê Enter.
4. Ao receber as respostas, clique nos pequenos **números azuis** que aparecem no final das frases. O NotebookLM abrirá o documento de origem exatamente na página que comprova aquela resposta, garantindo um estudo sem "alucinações" de IA.

---

## Miniguia de Estudo

### Resumos Estruturados do Novo Modelo ANBIMA

1.  **A Trilha C-Pro e a Abordagem Prática (Árvores de Diálogo):**
    * As novas certificações não testam apenas o conhecimento passivo de conceitos. [cite_start]Por meio de estruturas de árvore de diálogo, avalia-se a capacidade consultiva do profissional em situações cotidianas, como no atendimento de clientes com perfil conservador que buscam planejamento financeiro[cite: 13, 18, 19].
    * [cite_start]A pontuação ponderada das questões interativas premia condutas éticas e profissionais com pontuação máxima (Score 5) [cite: 26, 28][cite_start], pune posturas alarmistas ou agressivas (Score 0) [cite: 47, 49] [cite_start]e direciona o fluxo do diálogo com base nas escolhas feitas pelo candidato[cite: 27].
2.  **Governança, Privacidade e o Ecossistema ANBIMA Edu:**
    * [cite_start]Para a participação de menores de idade em cursos de atualização e exames, a ANBIMA atua na figura legal de **Controlador** dos dados[cite: 5, 10].
    * [cite_start]O tratamento dos dados estende-se tanto à própria associação quanto aos seus parceiros homologados [cite: 3][cite_start], mantendo salvaguardas de conformidade baseadas na Lei Geral de Proteção de Dados (Lei nº 13.709).

### Glossário de Conceitos-Chave

* [cite_start]**Controlador (ANBIMA):** Pessoa jurídica de direito privado a quem competem as decisões referentes ao tratamento de dados pessoais dos titulares envolvidos nos processos de certificação e capacitação[cite: 10].
* [cite_start]**Árvore de Diálogo (Dialogue Tree):** Estrutura técnica e pedagógica hierárquica baseada em nós de prompts e respostas interativas que visa testar o julgamento situacional de profissionais em cenários reais de atendimento ou conformidade[cite: 13, 15, 19].
* [cite_start]**Revogação de Consentimento:** Mecanismo pelo qual o representante legal (ou o próprio titular ao atingir a maioridade) solicita a interrupção da autorização de tratamento de dados, resguardado o direito do controlador de reter os dados se houver fundamentação legal[cite: 11].
* [cite_start]**Score de Opção:** Peso de pontuação (geralmente variando de 0 a 5) atribuído a cada linha de diálogo escolhida em uma simulação, diferenciando abordagens ótimas, subótimas e incorretas[cite: 26, 39, 47, 49].
* [cite_start]**Próximo Passo (Next):** Parâmetro lógico de transição em árvores de decisão que determina dinamicamente o rumo e o desfecho da interação dependendo da alternativa assinalada pelo usuário[cite: 27, 61].

### Prompts Reutilizáveis para Revisões Futuras

#### Prompt para Simular Dinâmicas de Atendimento com Árvore de Decisão
> [cite_start]*"Utilizando os padrões identificados em 'Template-Arvore-de-decisao-Certificacoes-Anbima.pdf', monte um cenário de simulação de diálogo em formato JSON estruturado fictício para a certificação C-Pro I. O cenário deve focar em um gerente oferecendo derivativos a um cliente de perfil arrojado. Inclua 3 nós de decisão com as alternativas e justificativas para cada pontuação."*

#### Prompt para Auditoria de Conformidade e LGPD nas Normas
> [cite_start]*"Acesse o arquivo 'Termo-de-Consentimento-Crianca-e-Adolescente.doc' [cite: 1] e compare os direitos de revogação de consentimento ali listados com as obrigações éticas presentes no 'Codigo-Conduta-Etica-Pessoas-Certificadas.pdf'. Sintetize em tópicos como a privacidade de dados impacta a conduta diária de um profissional certificado."*

---
Projeto desenvolvido como modelo de Portfólio para a plataforma DIO. Pratique a aprendizagem ativa!
