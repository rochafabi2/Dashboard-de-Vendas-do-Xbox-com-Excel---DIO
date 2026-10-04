# Dashboard-de-Vendas-do-Xbox-com-Excel---DIO
Dashboard de vendas criado no Excel para finalização de curso, esse artefato foi feito com orientação do professor Felipão

# Dashboard de Performance & Vendas Xbox

Este repositório contém a pasta de trabalho **`dashboard_xbox.xlsx`**, desenvolvida para consolidar, analisar e apresentar métricas comerciais, financeiras e operacionais da linha de produtos e serviços Xbox.

---

## 📌 Visão Geral do Arquivo

A planilha foi estruturada para separar claramente os dados brutos, os cálculos intermediários (tabelas dinâmicas/apoio) e a camada visual executiva voltada para tomada de decisão.

* **Objetivo:** Acompanhamento de KPIs de receita, volume de vendas, desempenho por região/canal e penetração de serviços (ex.: Xbox Game Pass e consoles).
* **Público-alvo:** Gerentes de produto, analistas de negócios e executivos comerciais.

---

##  Estrutura das Abas

O arquivo está organizado nas seguintes abas:

| Aba | Tipo | Descrição |
| :--- | :--- | :--- |
| **`Dashboard`** | Apresentação Executiva | Painel visual contendo cartões de KPIs principais, gráficos interativos e segmentações de dados (Slicers). |
| **`Base_Dados`** (ou `Dados`) | Dados Brutos | Tabela transacional com o histórico detalhado de vendas, registros de produtos, clientes e datas. |
| **`Calculos`** (ou `Apoio`) | Processamento | Tabelas dinâmicas, matrizes de cálculo e dados auxiliares que alimentam os gráficos e visuais do painel. |
| **`Parametros`** (se aplicável) | Configuração | Tabelas de apoio com listas suspensas, metas, tabelas de preço e taxas de câmbio. |

---

## Detalhamento das Tabelas e Campos

### 1. Tabela Principal de Vendas (`Base_Dados`)
Armazena o registro granular de cada transação:

* **`ID_Pedido` / `Order_ID`:** Identificador único da transação.
* **`Data`:** Data em que a venda foi realizada.
* **`Região` / `País`:** Localidade geográfica do comprador (ex.: Brasil, EUA, Europa).
* **`Canal de Venda`:** Canal de distribuição (ex.: Varejo Físico, E-commerce, Microsoft Store).
* **`Categoria`:** Categoria do item vendido (ex.: Consoles, Acessórios, Jogos Digitais, Assinaturas).
* **`Produto`:** Nome específico do item (ex.: *Xbox Series X*, *Xbox Series S*, *Controle Sem Fio Xbox*, *Xbox Game Pass Ultimate*).
* **`Preço Unitário`:** Valor nominal unitário de tabela.
* **`Quantidade`:** Número de unidades faturadas.
* **`Desconto`:** Percentual ou valor absoluto de desconto concedido.
* **`Faturamento Bruto`:** Total antes das deduções.
* **`Faturamento Líquido`:** Receita real obtida após aplicação de descontos e taxas.
* **`Custo Total`:** Custo dos produtos vendidos (CPV/COGS).
* **`Margem de Contribuição` / `Lucro`:** Resultado operacional por transação.

** Tela pronta do aplicativo
<img width="1144" height="695" alt="image" src="https://github.com/user-attachments/assets/bedb26de-e5e1-47af-ac5b-1f3ad673e1dc" />

**Como utilizar:
Abra o arquivo [dashboard_xbox.xlsx](https://github.com/user-attachments/files/33037465/dashboard_xbox.xlsx) utilizando o Excel ou o Google Sheets. Utilize os botões nas barras laterais para pesquisar as vendas por ano, mês. 



