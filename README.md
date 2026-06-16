# Guia de Estudos: Certificações ANBIMA (CPA e C-Pro) com NotebookLM

---

## Contexto e Objetivos

O mercado financeiro brasileiro passou por uma grande modernização em suas regras de certificação. A ANBIMA reformulou seus exames para focar muito mais na prática do dia a dia das agências e plataformas de investimento, introduzindo a nova trilha **C-Pro** (Certificação de Profissionais de Execução) e atualizando as tradicionais provas da **CPA**. Para quem busca ingressar ou evoluir no setor, compreender o que mudou, os novos pré-requisitos e o peso de cada conteúdo é um desafio complexo, e esse projeto visa auxiliar conforme veremos a seguir.

Agora, além de compreender conceitos teóricos, o profissional precisa provar que sabe recomendar o produto certo para o cliente certo, respeitando seu perfil de risco (*Suitability*), agindo com total ética e seguindo as normas de proteção de dados.

Este projeto foi desenvolvido como parte do **Bootcamp Bradesco - GenAI, Dados & Cyber** na **DIO (Digital Innovation One)** e aplica os conceitos de **Aprendizagem Ativa** e **Engenharia de Prompts**. Utilizando o **NotebookLM** da Google como um ecossistema de estudo privado alimentado por fontes oficiais, este repositório centraliza um caderno temático inteligente para apoiar a preparação estratégica para os novos exames da ANBIMA.

### Objetivos de Estudo:
1. Mapear a transição entre o modelo antigo de certificações e as novas exigências práticas (CPA e C-Pro).
2. Compreender a aplicação do conceito de *Suitability* (adequação de investimentos ao perfil do cliente) em cenários reais.
3. Analisar os requisitos de governança de dados e privacidade (LGPD) adotados pela associação no ecossistema educacional.

---

## Curadoria de Fontes

Para garantir o mais alto nível de precisão, o NotebookLM foi alimentado exclusivamente com documentos oficiais extraídos do portal da ANBIMA. Os arquivos locais estão disponíveis na pasta `/fontes` deste repositório:

### Programas Detalhados e Editais (Links Oficiais)
* [Programa Detalhado - CPA ANBIMA](https://www.anbima.com.br/data/files/6A/52/6F/A1/BED73910B07B2739B82BA2A8/Programa-Detalhado-CPA-ANBIMA.pdf)
* [Programa Detalhado - C-Pro I](https://www.anbima.com.br/data/files/9B/82/78/94/12793910A5947839EA2BA2A8/Programa-Detalhado-C-Pro-I.pdf)
* [Programa Detalhado - C-Pro R](https://www.anbima.com.br/data/files/38/52/0D/A1/BED73910B07B2739B82BA2A8/Programa-Detalhado-C-Pro-R-ANBIMA.pdf)
* [Edital dos Exames de Certificação Profissional](https://www.anbima.com.br/data/files/98/96/A6/10/9C24C910CF6A83C9F82BA2A8/Edital-dos-Exames-de-Certificacao-Profissional-Anbima.pdf)

### Cadernos de Questões e Guias de Estudo (Links Oficiais)
* [Guia de Elaboração de Questões ANBIMA](https://www.anbima.com.br/data/files/40/C6/A8/5E/FCBF891048BA3F89EA2BA2A8/Guia-de-Elaboracao-de-Questao-Certificacoes-Anbima.pdf)
* [Caderno de Questões - CPA](https://www.anbima.com.br/data/files/DF/86/EE/B6/EB6F891048BA3F89EA2BA2A8/Caderno-de-questoes-CPA.pdf)
* [Caderno de Questões - Execução Renda Fixa (C-Pro R)](https://www.anbima.com.br/data/files/07/E7/B8/A3/0C6F8910C03A3F89B82BA2A8/Caderno-de-questoes-C-Pro-R.pdf)
* [Caderno de Questões - Execução Investimentos (C-Pro I)](https://www.anbima.com.br/data/files/28/67/1B/28/FB6F8910C03A3F89B82BA2A8/Caderno-de-questoes-C-Pro-I.pdf)
* [Código de Conduta e Ética para Pessoas Certificadas](https://www.anbima.com.br/data/files/DB/93/03/7F/269CE8107ECD2CE8B82BA2A8/Codigo-Conduta-Etica-Pessoas-Certificadas.pdf)

### Arquivos Locais do Repositório (Disponíveis na pasta /fontes)
* `Termo-de-Consentimento-Crianca-e-Adolescente.doc`: Documento regulatório sobre o tratamento de dados pessoais e conformidade com a LGPD no ambiente educacional da ANBIMA.
* `Template-Arvore-de-decisao-Certificacoes-Anbima.pdf`: Estudo de caso detalhado que simula a conversa prática entre um gerente de relacionamento e um cliente real.
* `Formulas-dos-exames-de-certifcacoes-Anbima-CEA-CFG-CGA-CGE.xlsx`: Planilha contendo as funções matemáticas e estatísticas utilizadas nos cálculos do mercado financeiro.
* `Matriz-Avaliacao-Anbima.xlsx`: Planilha estruturada com a matriz de competências e pesos de conteúdos para cada nível de exame.

---

## Como Replicar este Projeto no NotebookLM (Passo a Passo)

Se você nunca utilizou o NotebookLM, não se preocupe! Ele funciona como um assistente de inteligência artificial privado. Em vez de buscar informações na internet aberta, ele responderá suas dúvidas baseando-se **apenas** nos documentos oficiais que nós enviarmos para ele.

Siga os passos abaixo para configurar o seu ambiente de estudos:

### 1. Criar o seu Caderno Virtual
1. Acesse o site oficial: [NotebookLM da Google](https://notebooklm.google/).
2. Faça login utilizando qualquer conta Gmail de sua preferência.
3. Na tela inicial, clique no botão **"+" (Novo caderno)**.

### 2. Alimentar a IA com os Materiais do Projeto
Assim que o caderno for criado, uma janela pedirá para você adicionar as fontes. Vamos carregar os arquivos deste repositório de duas formas:

#### Passo A: Links da Web (Para os sites oficiais da ANBIMA)
1. Na tela de fontes do NotebookLM, selecione a opção **Link da Web**.
2. Copie os links da seção **Curadoria de Fontes** deste README e cole-os um por um na plataforma.

#### Passo B: Upload de Arquivos (Para os arquivos baixados deste repositório)
Baixe os arquivos da pasta `/fontes` deste repositório para o seu computador e envie-os para o NotebookLM:
1. Para o arquivo de Estudo de Caso (PDF): Selecione a opção **Fazer upload de arquivo** e envie o arquivo PDF.
2. Para o arquivo de Consentimento (DOC): Abra o documento no seu computador, copie todo o texto contido nele, escolha a opção **Texto Copiado** no NotebookLM, cole o conteúdo no campo e salve.
3. Para as planilhas de Fórmulas e Matrizes (XLSX): Para garantir a leitura perfeita pela IA, salve as planilhas como PDF no seu Excel (usando a opção Salvar como -> PDF) ou salve-as no seu Google Drive pessoal e importe-as diretamente no NotebookLM através da opção **Google Drive**.

> 💡 **Nota:** Após carregar tudo, você verá a lista completa de documentos no painel esquerdo da tela. Certifique-se de que todos estão marcados com um "check" azul para que a IA consulte todos eles.

### 3. Fixar o Guia de Estudos (Notas)
1. No painel direito da tela do NotebookLM, procure pela seção **Notas** (*Notes*).
2. Clique em **Adicionar nota** (*Create note*).
3. Copie o conteúdo da seção **Miniguia de Estudo** (que está no final deste texto) e cole ali dentro para deixá-la sempre visível enquanto estuda.

### 4. Interagir e Testar os Prompts
Com tudo configurado, você usará a barra de chat na parte inferior da tela para realizar as suas sessões de estudo ativo:
1. Vá até a seção **Engenharia de Prompts** deste repositório.
2. Copie um dos prompts refinados (as mensagens completas dentro dos blocos de citação).
3. Cole no chat do NotebookLM e pressione Enter.
4. Ao receber as respostas, clique nos pequenos **números azuis** que aparecem no final das frases. O NotebookLM abrirá o documento de origem exatamente na página que comprova aquela resposta, garantindo um aprendizado confiável e sem distorções de dados.

---

## Engenharia de Prompts e Diagnósticos (Troubleshooting)

O NotebookLM trabalha ancorado estritamente nas fontes fornecidas. Ao cruzar materiais de estruturas variadas (como simulações de diálogos bancários e textos jurídicos), os comandos precisaram ser refinados para extrair o melhor conhecimento prático do mercado financeiro.

### Teste de Prompt 1: Treino de Atendimento ao Cliente (*Suitability*)
* **Prompt Inicial:** *"O que o PDF fala sobre o cliente Carlos?"*
* **Problema Encontrado:** A IA apenas resumiu a história do cliente de forma curta, sem gerar valor prático para quem está estudando para a prova do C-Pro.
* **Prompt Refinado (Estratégico):** *"Com base no caso prático do cliente Carlos presente nos materiais, assuma o papel do Carlos no chat. Ele é um investidor de perfil conservador. Eu serei o gerente de relacionamentos do banco. Comece simulando a primeira fala dele de forma natural e aguarde a minha resposta. Conduza essa conversa comigo para avaliar se eu sei oferecer produtos de forma ética e adequada ao perfil dele."*
* **Resultado com o Refinamento:** O NotebookLM transformou-se em um simulador interativo, permitindo treinar na prática as técnicas de atendimento exigidas no exame C-Pro.

### Teste de Prompt 2: Extração de Regras de Conformidade (LGPD)
* **Prompt Inicial:** *"O que o documento diz sobre menores de idade?"*
* **Problema Encontrado:** A resposta misturou conceitos gerais de maioridade civil com as regras específicas de tratamento de dados institucionais da ANBIMA, ficando confusa.
* **Prompt Refinado (Estratégico):** *"Consultando o documento de consentimento para crianças e adolescentes da ANBIMA, explique de forma simples quais são as situações exatas em que a associação pode usar os dados de um menor no portal ANBIMA Edu e o que acontece se o responsável quiser cancelar essa autorização."*
* **Resultado com o Refinamento:** A IA mapeou de forma exata as finalidades (como inscrições, agendamentos de provas e cursos de atualização) e explicou claramente o direito de revogação do consentimento.

---

## Miniguia de Estudo (Entrega Final)

### Resumos Estruturados do Novo Modelo ANBIMA

1.  **O foco no Perfil do Investidor (Suitability):**
    * Recomendar investimentos vai muito além de conhecer taxas de rentabilidade. O profissional certificado deve analisar os objetivos do cliente, o prazo que ele pretende deixar o dinheiro guardado e sua tolerância a perdas.
    * No caso de um cliente de perfil conservador, oferecer produtos de alto risco (como ações ou derivativos complexos) sem uma estratégia de proteção clara viola as normas éticas da ANBIMA e reprova o candidato em questões práticas.
2.  **Governança, Privacidade e o Ecossistema Educacional:**
    * Para a participação de menores de idade em cursos de atualização e exames, a ANBIMA atua na figura legal de Controlador dos dados coletados.
    * O tratamento dos dados estende-se tanto à própria associação quanto aos seus parceiros homologados, mantendo salvaguardas de conformidade baseadas na Lei Geral de Proteção de Dados (LGPD).

### Glossário Descomplicado

* **Suitability:** Processo obrigatório para verificar se um produto de investimento é adequado ao perfil de risco e aos objetivos financeiros do cliente.
* **Investidor Conservador:** Perfil de cliente que prioriza a segurança de seu patrimônio, buscando evitar perdas, mesmo que isso signifique ter uma rentabilidade menor (ex: prefere Tesouro Direto ou CDBs de grandes bancos).
* **Distrator:** Nome técnico dado às alternativas incorretas em uma questão de múltipla escolha. Na ANBIMA, elas são construídas parecendo verdades para testar se o aluno realmente entendeu o conceito ou apenas decorou a matéria.
* **Controlador de Dados:** A empresa ou instituição (neste caso, a ANBIMA) que decide como os dados pessoais dos usuários serão coletados e tratados de acordo com as regras da LGPD.
* **Revogação de Consentimento:** Mecanismo pelo qual o representante legal solicita a interrupção da autorização de tratamento de dados, resguardado o direito do controlador de reter os dados se houver outra justificativa legal (como cumprimento de obrigação regulatória).

### 🔄 Prompts Reutilizáveis para Revisões Futuras

Abaixo estão os comandos estruturados para você copiar e utilizar em suas próximas sessões de estudo no chat do NotebookLM:

#### Prompt para Simular Dinâmicas de Atendimento (Simulado Prático)
> *"Utilizando as regras de conduta e atendimento presentes nos manuais da ANBIMA, crie um cenário prático de simulação onde você interpreta um cliente de perfil Moderado que deseja resgatar um fundo de renda fixa para comprar um imóvel em 6 meses. Eu serei o gerente. Apresente o cenário, faça a sua primeira pergunta e aguarde a minha resposta."*

#### Prompt para Auditoria de Ética e Legislação
> *"Acesse o Código de Conduta e Ética e o arquivo de consentimento de dados. Sintetize em 5 tópicos claros de que forma o vazamento de informações ou o uso indevido de dados cadastrais dos clientes viola os princípios éticos fundamentais exigidos para um profissional certificado CPA ou C-Pro."*

---
Projeto desenvolvido como modelo de Portfólio para a plataforma DIO. Pratique a aprendizagem ativa e bons estudos!
