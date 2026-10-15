# Dashboard Porsche — Análise de Vendas com Inteligência Artificial

## 📌 Sobre o projeto

Este projeto tem como objetivo desenvolver uma dashboard interativa para análise de vendas da Porsche, utilizando Inteligência Artificial como ferramenta de apoio à construção da visualização de dados.

A dashboard foi desenvolvida com foco em três aspectos principais: **desempenho comercial, produtividade dos vendedores e acompanhamento das entregas**. A interface foi inspirada no site oficial da Porsche Brasil, buscando transmitir elegância, sofisticação e uma identidade visual alinhada à marca.

O projeto também demonstra a aplicação de IA no processo de análise de dados e desenvolvimento de dashboards, desde a definição das perguntas de negócio até a construção da interface final.

## 🔗 Dashboard publicada

**Acesse a dashboard:** [Criando uma Dashboard da Porsche com Agentes de IA](https://rodrigolima2.github.io/Criando-uma-Dashboard-da-Porsche-com-Agentes-de-IA/)

## 🎯 Perguntas de negócio escolhidas

Foram selecionadas três perguntas de negócio para orientar a construção da dashboard. A escolha considerou a relevância dos indicadores para a tomada de decisão e a capacidade de transformar os dados em informações úteis para a gestão comercial e operacional.

### 1. Como o faturamento e o volume de vendas evoluem ao longo do tempo?

**Justificativa:**

Essa pergunta permite acompanhar o desempenho comercial da empresa ao longo do tempo, identificando períodos de crescimento ou queda no faturamento e na quantidade de vendas.

Com essas informações, é possível avaliar tendências, identificar possíveis sazonalidades e apoiar o planejamento de estratégias comerciais para melhorar os resultados.

### 2. Quais vendedores apresentam o melhor desempenho em vendas e faturamento?

**Justificativa:**

Essa pergunta permite avaliar o desempenho individual dos vendedores, identificando aqueles que mais contribuem para o faturamento e os que realizam o maior número de vendas.

A análise ajuda a reconhecer bons resultados, identificar oportunidades de melhoria na equipe e orientar ações de treinamento e incentivo, contribuindo para o aumento da produtividade comercial.

### 3. Qual é a situação das entregas e quantas vendas ainda não foram concluídas?

**Justificativa:**

Essa pergunta permite monitorar o andamento das entregas e identificar vendas que ainda estão pendentes de conclusão.

Com essa análise, a empresa pode detectar possíveis gargalos operacionais, priorizar situações que exigem atenção e melhorar o acompanhamento dos pedidos, contribuindo para uma operação mais eficiente e para a satisfação dos clientes.

## 🧹 Tratamento e preparação dos dados

Antes de enviar a base de dados para a Inteligência Artificial, foram realizados tratamentos para melhorar a organização, a consistência e a interpretação das informações.

As etapas executadas foram:

1. **Exclusão de colunas não sanitizadas:** foram removidas as colunas não sanitizadas, mantendo apenas as respectivas colunas sanitizadas para utilização na análise.
2. **Adequação dos tipos de dados:** os tipos de dados de cada coluna foram ajustados de acordo com o conteúdo correspondente, garantindo uma estrutura mais adequada para a interpretação dos valores.
3. **Padronização dos nomes das colunas:** os títulos foram ajustados para remover a expressão `sanitized` e manter um padrão de nomenclatura consistente entre as colunas.

Esses procedimentos foram realizados para disponibilizar uma base mais organizada e facilitar a compreensão dos dados pela IA durante a criação da dashboard.

## 🤖 Utilização da Inteligência Artificial

Para o desenvolvimento do projeto, foi utilizado o **ChatGPT com o recurso Canvas**, que permitiu gerar e ajustar a dashboard em HTML.

**Não foram utilizados agentes de IA nem skills especializadas.** O desenvolvimento foi conduzido por meio de prompts enviados ao ChatGPT, organizados em etapas para definir as perguntas de negócio, justificar sua relevância e construir a visualização final.

### Prompt 1 — Identificação das perguntas de negócio

O primeiro prompt teve como objetivo analisar a planilha e obter sugestões de perguntas de negócio relevantes para uma dashboard.

> Olá, eu preciso que você analise essa planilha e me retorne alguns exemplos de perguntas de negócio, podem ser 10 exemplos, eu preciso selecionar pelo menos 3, me retorne perguntas que você ache que possam ser excelentes para ser utilizadas em uma dashboard e que sejam uteis.

A partir das sugestões recebidas, foram selecionadas as três perguntas apresentadas na seção de perguntas de negócio.

### Prompt 2 — Justificativa das perguntas selecionadas

Após selecionar as perguntas, foi utilizado um segundo prompt para explicar a importância de cada uma delas e sua contribuição para uma dashboard.

> ok eu escolhi as seguintes perguntas:
>
> 1. Como o faturamento e o volume de vendas evoluem ao longo do tempo?
> 2. Quais vendedores apresentam o melhor desempenho em vendas e faturamento?
> 3. Qual é a situação das entregas e quantas vendas ainda não foram concluídas?
>
> eu preciso que você de um porque para cada pergunta que eu escolhi, explique o motivo do por que cada uma dessas perguntas possam ser boas para uma dashboard, faça na ordem de cada pergunta escolhida

O resultado foi utilizado para fundamentar a escolha dos indicadores e direcionar a análise para aspectos relevantes do negócio.

### Prompt 3 — Construção da dashboard no Canvas

O terceiro prompt foi utilizado para solicitar a construção da dashboard em HTML, definindo os filtros, as perguntas de negócio e as referências visuais.

```text
Utilizando o recurso de canvas, renderize uma dashboard em html ao lado

# Filtros
-> Modelo da Porsche
-> Model Year
-> City
-> Pay Method

# Perguntas de negócios e KPIs
-> Como o faturamento e o volume de vendas evoluem ao longo do tempo?
-> Quais vendedores apresentam o melhor desempenho em vendas e faturamento?
-> Qual é a situação das entregas e quantas vendas ainda não foram concluídas?

Sobre o UI/UX, se baseie no site oficial da Porsche Brasil:
https://www.porsche.com/brazil/pt/

Tenha um ar de elegante e refinado.
```

## 🔄 Evolução dos prompts até a versão final

O desenvolvimento foi dividido em três etapas, permitindo evoluir de uma análise inicial da base até a construção da dashboard.

| Etapa | Objetivo | Resultado |
|---|---|---|
| Prompt 1 | Explorar a base de dados e sugerir perguntas de negócio. | Foram obtidas sugestões para orientar a análise. |
| Prompt 2 | Justificar as três perguntas selecionadas. | Foram definidos os objetivos e a relevância de cada análise. |
| Prompt 3 | Construir a dashboard no Canvas. | Foram especificados os filtros, as perguntas de negócio, os KPIs e a direção visual. |

A principal evolução ocorreu na **especificação do que a dashboard deveria responder e de como deveria apresentar essas informações**. Inicialmente, o foco estava em descobrir quais análises seriam relevantes. Em seguida, as perguntas foram justificadas e, por fim, transformadas em requisitos para a construção da interface.

O prompt final reuniu as definições de negócio e os requisitos visuais em uma única solicitação. Os ajustes realizados durante a construção no Canvas fizeram parte do processo de refinamento até a versão publicada.

## 🎨 Diretrizes de UI/UX

A identidade visual da dashboard foi inspirada no site oficial da Porsche Brasil, disponível em [porsche.com/brazil/pt](https://www.porsche.com/brazil/pt/).

A proposta visual prioriza:

- **Elegância e sofisticação:** uma apresentação alinhada ao posicionamento premium da marca.
- **Clareza na visualização:** organização dos indicadores para facilitar a leitura e a interpretação dos resultados.
- **Filtros de análise:** seleção por modelo da Porsche, ano do modelo (*Model Year*), cidade (*City*) e método de pagamento (*Pay Method*).
- **Foco em indicadores de negócio:** visualizações direcionadas à evolução das vendas, ao desempenho dos vendedores e ao acompanhamento das entregas.

## 🛠️ Ferramentas e tecnologias

- **ChatGPT:** apoio à análise das perguntas de negócio, elaboração dos prompts e desenvolvimento da dashboard.
- **Canvas:** ambiente utilizado para gerar e refinar a dashboard em HTML.
- **HTML:** estrutura da interface da dashboard.
- **GitHub Pages:** publicação e hospedagem da dashboard.

## 📊 Resultados e aprendizados

O projeto permitiu aplicar conceitos de análise de dados e visualização de informações com apoio da Inteligência Artificial.

Entre os principais aprendizados, destacam-se:

- A importância de preparar e padronizar os dados antes de utilizá-los em ferramentas de IA.
- A definição de perguntas de negócio como etapa fundamental para orientar a construção de uma dashboard.
- A utilização de prompts estruturados para transformar necessidades de análise em requisitos de visualização.
- A importância de combinar indicadores relevantes, filtros e uma interface visual coerente com a identidade da marca.
- O uso do Canvas como ferramenta de apoio à prototipação e ao desenvolvimento de interfaces em HTML.

## 👨‍💻 Autor

**Rodrigo Lima**

Projeto desenvolvido com o objetivo de explorar a aplicação da Inteligência Artificial na análise de dados e na criação de dashboards para apoiar a tomada de decisão.
