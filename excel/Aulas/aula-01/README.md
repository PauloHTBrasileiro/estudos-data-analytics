# 📘 Aula 01

**Introdução a IAs - Excel com IA e Claude**

## 📝 Anotações - Parte 01
# 🧠 Engenharia de Prompts

Anotações sobre **Engenharia de Prompts**, funcionamento de Modelos de Linguagem (LLMs) e boas práticas para obter respostas mais precisas utilizando Inteligência Artificial.

---

# 📚 O que é Engenharia de Prompts?

Engenharia de Prompts é a prática de criar instruções claras, objetivas e bem estruturadas para que modelos de IA gerem respostas mais precisas, úteis e consistentes.

O objetivo não é apenas fazer perguntas, mas orientar o modelo para produzir exatamente o resultado esperado.

---

# 🤖 Como os Modelos de Linguagem Funcionam

Modelos de linguagem, como o GPT, são treinados para prever o próximo **token** com maior probabilidade, utilizando padrões aprendidos durante o treinamento.

Eles não "pensam" ou pesquisam na internet por padrão. A resposta é gerada com base no contexto recebido e no conhecimento aprendido.

---

# 🔤 Tokens

Tokens são as unidades básicas utilizadas pelo modelo para processar textos.

Um token pode representar:

- Uma palavra
- Parte de uma palavra
- Um caractere
- Um símbolo

Exemplo:

```
"Analista de Dados"

Tokens:

Analista
de
Dados
```

---

# 🪟 Janela de Contexto

A **Janela de Contexto** representa a quantidade máxima de tokens que o modelo consegue processar simultaneamente.

Ela inclui:

- Prompt atual
- Conversas anteriores
- Respostas anteriores
- Arquivos enviados

Quando o limite é atingido, informações antigas podem deixar de ser consideradas.

Quanto melhor o contexto fornecido, melhor tende a ser a resposta.

---

# ✅ Elementos Essenciais de um Bom Prompt

## 🎯 Instrução Clara

Explique exatamente o que deseja.

**Exemplo**

```
Crie uma apresentação sobre Engenharia de Prompts.
```

---

## 📖 Contexto

Forneça informações importantes para que o modelo compreenda o cenário.

**Exemplo**

```
A apresentação será destinada a alunos iniciantes de Ciência de Dados.
```

---

## 📝 Exemplos (Few-shot Learning)

Mostrar exemplos ajuda o modelo a compreender o formato esperado.

**Exemplo**

```
Pergunta:
Qual a capital do Brasil?

Resposta:
Brasília.

Agora responda:

Qual a capital da Argentina?
```

---

## 📂 Dados de Entrada

São as informações específicas utilizadas para executar a tarefa.

**Exemplo**

```
Utilize os dados de vendas abaixo para criar uma análise.
```

---

## 📄 Formato da Saída

Defina como deseja receber a resposta.

Exemplos:

- Markdown
- JSON
- HTML
- Python
- SQL
- Tabela

---

# 💡 Por que incluir contexto?

Quanto maior e mais relevante for o contexto, maior será a precisão da resposta.

Sem contexto:

```
Faça uma análise.
```

Com contexto:

```
Analise os dados de vendas considerando faturamento, lucro e sazonalidade.
```

---

# 🧠 Como o Modelo Responde?

Os modelos utilizam probabilidades baseadas nos padrões aprendidos durante o treinamento.

A cada novo token gerado, o modelo calcula qual possui maior probabilidade de continuar a sequência de texto.

---

# 🚀 Aplicações Práticas

A Engenharia de Prompts pode ser utilizada para:

- Desenvolvimento de software
- Criação de documentação
- Automação de tarefas
- Geração de projetos
- Produção de conteúdo
- Análise de dados
- Criação de dashboards
- Estudos
- Planejamento de carreira
- Preparação para entrevistas

---

# 💼 Exemplo de Prompt para Entrevista

```text
Simule uma entrevista para uma vaga de Analista de Dados considerando que:

- Não possuo experiência profissional;
- Estou cursando uma pós-graduação em Gestão de Big Data e Business Analytics;
- Conheço Engenharia de Prompts;
- Estou estudando IA Generativa;
- Estou aprendendo Excel, SQL, Python e Power BI.

Fluxo:

1. Faça apenas uma pergunta por vez.

2. Aguarde minha resposta.

3. Após cada resposta, forneça:

- Pontos positivos;
- O que pode melhorar;
- Exemplo de resposta ideal;
- Sugestões para responder de forma mais profissional;
- Dicas para futuras entrevistas.

Depois faça a próxima pergunta.
```

---

# ⚠️ Cuidados ao Criar Prompts

## Prompts Enviesados

Prompts podem induzir o modelo a uma resposta específica.

❌ Exemplo ruim

```
Por que Coca-Cola é o melhor refrigerante?
```

✅ Melhor opção

```
Quais são as principais diferenças entre Coca-Cola e Pepsi?
```

---

## Alucinações

Alucinações acontecem quando o modelo gera informações incorretas ou inventadas por falta de dados suficientes.

Para reduzir esse problema:

- Forneça contexto
- Utilize documentos como referência
- Solicite fontes quando necessário
- Oriente o modelo a informar quando não souber a resposta

---

## Privacidade e Segurança

Evite compartilhar informações sensíveis, como:

- CPF
- RG
- Senhas
- Cartões bancários
- Dados pessoais
- Informações confidenciais da empresa

Sempre que possível, utilize dados fictícios ou anonimizados.

---

# 📖 Perguntas Frequentes

### Por que incluir contexto em um prompt?

Porque ajuda o modelo a produzir respostas mais precisas e coerentes.

---

### Como os modelos conseguem responder de forma coerente?

Utilizando probabilidades baseadas em padrões aprendidos durante o treinamento.

---

### O que são Tokens?

São as unidades básicas de processamento utilizadas pelos modelos de linguagem.

---

### Qual é a função da Janela de Contexto?

Determinar a quantidade máxima de tokens que podem ser considerados simultaneamente.

---

### Qual a importância de uma instrução clara?

Evita interpretações equivocadas e melhora significativamente a qualidade da resposta.

---

### O que são alucinações?

Respostas incorretas ou inventadas geradas pelo modelo quando faltam informações confiáveis.

---

### O que é um prompt enviesado?

É um prompt que conduz a IA para uma resposta específica, limitando uma análise imparcial.

---

# 📚 Glossário

| Termo | Definição |
|--------|-----------|
| **Attention Mechanism** | Técnica utilizada pelos Transformers para focar nas partes mais relevantes do texto durante a geração da resposta. |
| **Chunks** | Blocos de texto com significado (frases ou parágrafos) utilizados para organização e recuperação de informações. |
| **Contexto Longo** | Capacidade do modelo de processar grandes quantidades de texto mantendo a coerência. |
| **Contextualização** | Processo de interpretar palavras considerando o contexto em que aparecem. |
| **Embeddings** | Representações vetoriais que capturam o significado semântico de palavras ou frases. |
| **Feedforward Network** | Camada da arquitetura Transformer responsável por transformar as representações geradas pelo mecanismo de atenção. |
| **Few-shot Learning** | Técnica em que o modelo recebe poucos exemplos antes de executar uma tarefa. |
| **Fine-tuning** | Ajuste de um modelo pré-treinado com dados específicos para melhorar seu desempenho em uma tarefa. |
| **Guardrails** | Restrições e diretrizes que garantem respostas seguras e alinhadas ao objetivo do sistema. |
| **Inferência** | Processo de geração de respostas utilizando um modelo já treinado. |
| **Janela de Contexto** | Quantidade máxima de tokens que o modelo consegue processar simultaneamente. |
| **Modelo de Linguagem** | Modelo de IA treinado para compreender e gerar linguagem natural. |
| **N-grama** | Sequência de *n* tokens consecutivos utilizada para capturar relações entre palavras. |
| **Overfitting** | Quando o modelo aprende excessivamente os dados de treinamento e perde capacidade de generalização. |
| **Parâmetros do Modelo** | Valores internos ajustados durante o treinamento que determinam o comportamento do modelo. |
| **Parsing** | Processo de análise da estrutura sintática de um texto. |
| **Prompt Engineering** | Processo de projetar e otimizar prompts para obter respostas mais eficientes de modelos de IA. |
| **Prompts** | Instruções fornecidas ao modelo para executar uma tarefa. |
| **Reconhecimento de Entidades (NER)** | Técnica utilizada para identificar pessoas, locais, organizações, datas e outras entidades em textos. |
| **RAG (Retrieval-Augmented Generation)** | Técnica que combina recuperação de informações externas com geração de respostas para aumentar a precisão. |
| **Stopwords** | Palavras muito frequentes ("de", "a", "o") que podem ser removidas em algumas tarefas de processamento de linguagem. |
| **Stemming** | Processo de reduzir palavras às suas raízes para facilitar o processamento textual. |
| **Token** | Unidade básica utilizada pelo modelo para processar texto. |
| **Tokenização** | Processo de dividir um texto em tokens. |
| **Underfitting** | Quando o modelo aprende pouco durante o treinamento, resultando em baixo desempenho. |
| **Zero-shot Learning** | Capacidade do modelo de executar tarefas sem exemplos prévios, utilizando apenas o conhecimento adquirido durante o treinamento. |

---

# 📌 Resumo

✔️ Escreva instruções claras.

✔️ Forneça contexto relevante.

✔️ Utilize exemplos quando possível.

✔️ Informe os dados de entrada.

✔️ Defina o formato esperado da resposta.

✔️ Evite prompts enviesados.

✔️ Tenha cuidado com informações sensíveis.

✔️ Valide respostas importantes para reduzir o impacto de possíveis alucinações.

---



