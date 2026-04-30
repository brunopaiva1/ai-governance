![](img/banner.jpeg)

# Governança e Ética de Dados em IA

## Membros do Grupo
* **Bruno Victor Paiva da Silva**
* **Manoel Benedito Neto**
* **Mariana Camila Cesário de Queiroz**

---

## Descrição do que foi feito no Projeto

Atualmente, as regras de governaça em IA, na qual definem como sistemas de inteligência artificial devem ser desenvolvidos, usados e controlados de forma segura e responsável, encontram-se massivamente divididas em diferentes tipos de mídias que não seguem um formato padronizado, como por exemplos: artigos, vídeos, documentos técnicos e etc. Diante disso, encontramos o seguinte desafio técnico: como rastrear a influência real e a regra técnica de governança que deve ser considerada e aplicada?

Para adentrar nesse desafio, estabelecemos o objetivo de utilizar uma das duas ferramentas apresentadas em sala e definidas para o escopo desse projeto. Com isso, definimos o Graphify, por sua facilidade de manuseio e de entendimento do grupo, realizamos seu uso para identificar se a diversidade e inclusão impactam a produtividade e como resolver o dilema entre escala tecnológica e direitos éticos. 

Nossa abordagem consistiu na:

1. Coleta de fontes variadas: coletamos diversas fontes, nas quais realizamos a ingestão da nossa base de dados, composta por relatórios de impacto de mercado, transcrições de vídeos e artigos acadêmicos.

2. Processamento via Graphify: nessa etapa, utilizamos o modelo Codex, baseado na arquitetura GPT-5.5, para atuar na análise dos documentos brutos. A partir disso, o sistema extraiu entidades e adicionou a essas entidades relacionamentos lógicos, assim construindo um grafo de conhecimento interativo. Esse processo gerou artefatos, como o graph.html, que permite visualizar e focar subgrafos específicos de governança.

3. Processamento via NotebookLM: Em paralelo, submetemos a mesma base de dados no NotebookLM, que serviu como referência de comparação.

4. Comparação: Para validar a eficácia do processamento que fizemos, aplicamos testes com prompts idênticos em ambos os sistemas. O objetivo foi comparar e analisar as saídas do Graphify com o NotebookLM.

## Resultados e Análise Comparativa

Para validar a eficácia das ferramentas, realizamos um teste utilizando um conjunto de perguntas analíticas. Os logs completos com os prompts utilizados e as respectivas capturas de tela das respostas detalhadas podem ser consultados no arquivo Prompts e respostas (ou na pasta `/results`).

**Principais Descobertas:**
* **Graphify:** Demonstrou superioridade na visualização da topologia dos dados, permitindo identificar conexões estruturais e comunidades de conceitos (clusters) que não são óbvias em textos lineares. É ideal para mapear a rastreabilidade e a hierarquia de normas.
* **NotebookLM:** Mostrou-se significativamente mais **verboso e informativo**. O modelo foi capaz de trazer dados quantitativos (números e estatísticas) e uma narrativa com mais detalhes técnicos e contextos que o grafo tende a simplificar.

---

## Limitações Identificadas

Com base na execução do projeto, identificamos os seguintes pontos de melhoria e limitações:

* **Heterogeneidade das Fontes:** Para gerar relações visualmente mais fortes no grafo, é necessário utilizar fontes com contextos e linguagens mais semelhantes.
* **Falta de Cronologia:** O mapeamento em grafos atual não demonstra com precisão a influência histórica (quem influenciou quem ao longo do tempo).
* **Ruído no Pré-processamento:** Fontes de vídeo e áudio exigem uma limpeza de texto extremamente rigorosa; caso contrário, podem gerar "nós" irrelevantes que poluem a visualização.
* **Simplificação de Nuance:** O grafo é uma representação estrutural e acaba simplificando relações complexas que os modelos de linguagem (como o NotebookLM) descrevem com muito mais tom crítico e nuance narrativa.

## Tarefas Realizadas pelo grupo:

* **Bruno Paiva:** Estruturou e documentou o repositório no GitHub. Executou a comparação dos testes entre o Graphify e o NotebookLM, analisou o Grafo gerado, colaborou na criação dos slides e apresentou o trabalho.

* **Manoel Neto:** Selecionou as fontes de pesquisa, executou a ferramenta Codex (Graphify) para gerar o Grafo e participou da análise dos resultados visuais. Colaborou na criação dos slides e apresentou o trabalho.

* **Mariana Queiroz:** Selecionou as fontes de pesquisa, criou as perguntas (prompts) dos testes e comparou o desempenho entre as duas ferramentas. Participou da análise do Grafo, colaborou na criação dos slides e apresentou o trabalho.
