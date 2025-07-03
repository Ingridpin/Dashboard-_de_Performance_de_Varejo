# **Dashboard de Performance de Varejo Multicontinental**

## **Uma Visão 360º do Desempenho Global e Tendências Estratégicas**

Bem-vindo(a) a um projeto de análise de dados que mergulha no coração das operações de varejo de uma empresa com presença em todos os continentes! Este dashboard foi desenvolvido para fornecer insights abrangentes sobre o desempenho de vendas, o comportamento do consumidor e a gestão de estoque, transformando dados brutos em inteligência acionável.

---

### **O Desafio dos Dados e a Solução Analítica**

Diante de um cenário de dados complexo e distribuído globalmente, o principal desafio foi consolidar e dar sentido a um volume significativo de informações transacionais e cadastrais. Este projeto aborda essa complexidade através de um processo analítico robusto, culminando em um dashboard dinâmico no Power BI.

Minha análise começou com a **normalização e anonimização dos dados de clientes**, garantindo a privacidade e a integridade da informação.

---

### **A Base da Análise: Conjunto de Dados & Engenharia de Dados**

Para construir essa visão integrada, foram utilizadas e unificadas **seis tabelas distintas**:

* **Cadastro de Loja:** Detalhes geográficos e operacionais (ID Loja, País, Continente, Cidade, Tipo Loja, Nome Gerente).
* **Cadastro de Clientes:** Informações demográficas (ID Cliente, Nome Completo, Gênero, Data de Nascimento, Idade, Faixa Etária).
* **Cadastro de Produtos:** Detalhes dos itens vendidos (ID Produto, Nome Produto, Categoria, Marca, Preço Unitário, Custo Unitário, Margem Lucro).
* **Dados Transacionais:** Registros de vendas para os anos de **2022, 2023 e 2024**.

**Processo Chave:**
As tabelas anuais de **2022, 2023 e 2024 foram unificadas** para criar uma visão temporal contínua. A partir delas, foi gerada uma **tabela central de Cadastro de Vendas** consolidando informações cruciais como: `Data Venda`, `Id Loja`, `Id Produto`, `Id Cliente`, `Qtd. Vendida`, `Qtd. Devolvida`, `Preço Unitário`, `Faturamento` e `Fat Perdido`.

---

### **Explorando o Dashboard no Power BI**

O dashboard é composto por abas intuitivas que permitem uma exploração detalhada do desempenho do varejo:

#### **Aba Principal: Desempenho Comercial**

Esta aba oferece um panorama instantâneo das métricas de negócio mais importantes:

* **Cartões de KPI (Key Performance Indicators):**
    * **Receita/Faturamento Total:** Visão geral da saúde financeira.
    * **Total de Vendas:** Quantidade total de itens vendidos.
    * **Ticket Médio:** Valor médio por transação.
    * **Número de Clientes:** Quantidade de clientes únicos que realizaram compras.

* **Gráfico de Área - Faturamento ao Longo do Tempo:**
    * **Eixo X:** Data da venda (com hierarquia para análise por Ano, Trimestre e Mês).
    * **Eixo Y:** Faturamento Total.
    * *Permite visualizar tendências e sazonalidades no faturamento global.*

* **Mapa de Localização:**
    * **Localização:** Países onde a empresa opera.
    * **Legenda:** Representação visual por Continente.
    * *Oferece um entendimento geográfico instantâneo da distribuição das operações e desempenho.*

* **Gráfico de Rosca - Total de Vendas por Gênero:**
    * *Revela o perfil de consumo por gênero, indicando quais grupos demográficos impulsionam as vendas.*

* **Gráfico de Barras Empilhadas - Faturamento por Marca:**
    * **Eixo Y:** Marcas dos produtos.
    * **Eixo X:** Faturamento Total.
    * *Destaca a performance das diferentes marcas, essencial para estratégias de portfólio.*

---

#### **Aba: Previsão de Vendas & Insights Estratégicos**

Esta aba aprofunda a análise, focando na inteligência preditiva e na otimização operacional:

* **Segmentação de Dados Dinâmica:**
    * **Por Cidade:** Permite filtrar dados para cidades específicas.
    * **Por ID da Loja:** Refina a análise para o desempenho individual de cada loja dentro da cidade selecionada.
    * **Por Categoria de Produto:** Filtra a análise para categorias específicas de produtos.

* **Gráfico de Linha - Previsão de Faturamento:**
    * **Eixo X:** Data da Venda (com granularidade anual).
    * **Eixo Y:** Média de Faturamento.
    * **Previsão:** Inclui uma previsão de faturamento com **80% de confiança para os próximos dois anos**.
    * *Este gráfico é fundamental para **insights estratégicos**, permitindo direcionar produtos em estoque e planejar ações com base em tendências futuras.*

---

### **Como Acessar o Dashboard**


* **Baixe o arquivo .pbix:**
    Para explorar a modelagem de dados, transformações (Power Query) e medidas (DAX), você pode baixar o arquivo-fonte do Power BI Desktop.


---

### **💻Tecnologias e Ferramentas Utilizadas**

* **Power BI Desktop:** Desenvolvimento do dashboard, modelagem de dados, Power Query (ETL), DAX.
* **Microsoft Excel:** Fonte dos dados brutos.
* **Conceitos de Banco de Dados:** Entendimento de unificação e criação de tabelas fatos/dimensões.
* **Estatística:** Aplicação de conceitos para previsão e intervalos de confiança.

---

### **:hammer_and_wrench:Habilidades Desenvolvidas no Projeto**

Este projeto consolidou e aprimorou um conjunto fundamental de competências em análise e tratamento de dados:

* **Preparação e Qualidade de Dados:** Domínio em técnicas de limpeza e normalização de dados, incluindo anonimização de informações sensíveis.
* **Engenharia de Dados (Básico):** Unificação de múltiplas fontes de dados (6 tabelas) e criação de uma tabela fato (`Cadastro de Vendas`) para análise.
* **Modelagem de Dados:** Estruturação de dados para otimização de performance e facilidade de análise em ferramentas de BI.
* **Análise Exploratória de Dados (EDA):** Habilidade em realizar análises estatísticas descritivas, filtrar, segmentar, agrupar e agregar dados para identificar padrões e extrair *insights*.
* **Criação de KPIs e Métricas:** Definição e cálculo de indicadores-chave de performance.
* **Análise Preditiva (Básica):** Geração de previsões (com intervalo de confiança) para suporte à tomada de decisão de estoque e planejamento.
* **Visualização de Dados e Storytelling:** Proficiência na criação de gráficos informativos e dashboards intuitivos no **Power BI**, transformando dados complexos em uma narrativa clara e acionável.
* **Pensamento Analítico e Estratégico:** Capacidade de interpretar dados e comunicar conclusões de forma eficaz, fornecendo *insights* estratégicos para as operações de varejo.

---


