# 🎮 Dashboard de Vendas de Assinaturas XBOX  

## 🧩 Descrição do Projeto  
Este projeto tem como objetivo criar um **dashboard de vendas de assinaturas XBOX** utilizando exclusivamente o **Microsoft Excel**.  
O foco é **organizar, tratar e visualizar dados brutos de assinaturas**, transformando-os em informações claras e úteis para **análise de desempenho** e **tomada de decisões baseadas em dados**.  

O painel desenvolvido permite identificar tendências de receita, impacto das renovações automáticas e participação dos add-ons **EA Play** e **Minecraft Season Pass** nas vendas totais.  

---

## 🎯 Perguntas Respondidas pelo Dashboard  
O dashboard foi construído para responder a **três perguntas principais de negócio**:

1. 💰 **Qual é o faturamento total de vendas de planos anuais**, separado entre assinaturas com **auto renovação** e **sem auto renovação**?  
2. 🎮 **Qual é o total de vendas de assinaturas do EA Play Season Pass?**  
3. ⛏️ **Qual é o total de vendas de assinaturas do Minecraft Season Pass?**

Essas três métricas fornecem uma visão direta do desempenho financeiro dos planos e dos complementos de assinatura.

---

## 🗂️ Estrutura da Base de Dados  

A planilha utilizada contém as seguintes colunas:  

| Coluna | Descrição |
|---------|------------|
| `Subscriber ID` | Identificador único do assinante |
| `Name` | Nome do assinante |
| `Plan` | Nome do plano contratado (ex.: Game Pass, Live Gold, Ultimate) |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Indica se há renovação automática (Sim/Não) |
| `Subscription Price` | Valor base da assinatura |
| `Subscription Type` | Tipo da assinatura (Mensal, Anual, Promocional, etc.) |
| `EA Play Season Pass` | Indica se o assinante possui o EA Play Season Pass |
| `EA Play Season Pass Price` | Valor do EA Play Season Pass |
| `Minecraft Season Pass` | Indica se o assinante possui o Minecraft Season Pass |
| `Minecraft Season Pass Price` | Valor do Minecraft Season Pass |
| `Coupon Value` | Valor de desconto aplicado |
| `Total Value` | Valor total final pago após descontos |

> 📌 Os dados são simulados com base em estruturas de vendas reais, utilizados apenas para fins analíticos e educacionais.

---

## 🧹 Etapas de Desenvolvimento  

1. **Importação e organização dos dados**  
   - Inserção da planilha original no Excel.  
   - Padronização dos nomes das colunas e tipos de dados (datas, valores monetários e textos).  

2. **Limpeza e preparação**  
   - Remoção de valores nulos ou inconsistentes.  
   - Correção de formatações e conversões de moeda.  
   - Verificação da coerência entre `Total Value` e os valores de assinatura e descontos.  

3. **Criação das métricas**  
   - Faturamento de planos anuais por status de auto renovação.  
   - Soma total de vendas do **EA Play Season Pass**.  
   - Soma total de vendas do **Minecraft Season Pass**.  

4. **Construção do Dashboard**  
   - Criação de **tabelas dinâmicas** para cálculo automático dos totais.  
   - Uso de **gráficos dinâmicos** (colunas, pizza e cartões) para visualização.  
   - Aplicação de **segmentações de dados (slicers)** para filtros interativos.  
   - Design do painel com foco em clareza e hierarquia visual.

---

## 📈 Principais Visualizações  

- **Gráfico de colunas agrupadas:** faturamento total dos planos anuais, separado por auto renovação.  
- **Indicador numérico (card):** total de vendas do EA Play Season Pass.  
- **Indicador numérico (card):** total de vendas do Minecraft Season Pass.  

Essas visualizações permitem identificar rapidamente **quais planos geram mais receita** e **quais complementos mais contribuem para o faturamento**.  

---

## 💡 Resultados Obtidos  

- Identificação do **impacto financeiro das renovações automáticas** nos planos anuais.  
- Cálculo do **volume total de vendas dos passes adicionais** (EA Play e Minecraft).  
- Construção de um **painel intuitivo e funcional** diretamente no Excel, sem uso de ferramentas externas.  

---

## 🧠 Conclusão  

O dashboard de assinaturas XBOX demonstra como é possível realizar **análises de desempenho e visualizações estratégicas** utilizando apenas o Excel.  
A ferramenta se mostrou eficaz na **transformação de dados brutos em informações acionáveis**, permitindo uma leitura imediata dos resultados e facilitando decisões baseadas em evidências.

---

## 👨‍💻 Autor  
**[Guilherme Gabriel]**  
Excel Data Analysis & Business Intelligence  
📧 guigabfz@gmail.com 
🔗 [LinkedIn]([(https://www.linkedin.com/in/guilhermegabsouza/))

---

## 🖼️ (Opcional) Imagem do Dashboard  
Se desejar incluir uma captura de tela, adicione o arquivo na pasta do repositório e insira a linha abaixo:  
```markdown
![Dashboard XBOX](xbox_dashboard.png)
