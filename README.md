# 📊 Análise de Vendas - Excel + Power Query

## 🎯 Sobre o Projeto

Projeto completo de análise de dados desenvolvido em **Microsoft Excel** com tratamento e transformação via **Power Query**, unificando **4 tabelas distintas** para gerar insights estratégicos sobre vendas de produtos eletrônicos, eletrodomésticos e higiene pessoal.

> **⚡ Contexto:** Este projeto foi desenvolvido em Excel devido à indisponibilidade de internet no momento da análise. Normalmente, utilizo **Power BI** para dashboards mais interativos, modernos e visualmente impactantes, mas este projeto demonstra minha capacidade de entregar análises de qualidade e gerar valor para o negócio independentemente da ferramenta disponível.

![Dashboard Principal](Captura%20de%20tela%202025-12-10%20171042.png)

---

## 🛠️ Tecnologias e Ferramentas

- **Microsoft Excel** (Tabelas Dinâmicas, Gráficos Interativos)
- **Power Query** (ETL - Extract, Transform, Load)
- **DAX** (Medidas Calculadas)
- **Visualização de Dados** (Dashboard Executivo)

---

## 📂 Estrutura do Projeto

### Arquitetura dos Dados:
```
📁 Projeto
├── 📊 4 Tabelas Fonte (Power Query)
│   ├── Vendas por Região
│   ├── Vendas por Vendedor  
│   ├── Vendas por Produto
│   └── Vendas Detalhadas
│
├── 🔄 Modelo de Dados Relacional
│   └── Relacionamentos entre tabelas
│
└── 📈 3 Dashboards Principais
    ├── Dashboard de Linha de Produtos
    ├── Dashboard Executivo com KPIs
    └── Dashboard de Vendas Detalhadas
```

---

## 🔄 Processo de ETL com Power Query

### Etapas de Tratamento de Dados:

#### 1️⃣ **Extração (Extract)**
- Importação de 4 tabelas de fontes distintas
- Identificação de chaves primárias e relacionamentos

#### 2️⃣ **Transformação (Transform)**
- ✅ **Limpeza de dados:** Remoção de duplicatas, valores nulos e inconsistências
- ✅ **Padronização:** Uniformização de formatos de data, moeda e texto
- ✅ **Normalização:** Organização de categorias, regiões e nomes
- ✅ **Merge de tabelas:** União das 4 tabelas usando relacionamentos chave
- ✅ **Colunas calculadas:** Criação de métricas como Total Vendido, Margem, etc.
- ✅ **Agrupamentos:** Agregação por categoria, região e período

#### 3️⃣ **Carga (Load)**
- Carregamento otimizado no modelo de dados do Excel
- Criação de relacionamentos automáticos entre tabelas
- Atualização dinâmica das análises

---

## 📊 Dashboards e Visualizações

### 🎯 Dashboard 1: Análise por Linha de Produtos
![Análise de Produtos](Captura%20de%20tela%202025-12-10%20170948.png)

**Destaques:**
- Top 10 produtos mais vendidos
- Análise por categoria (Eletrodomésticos, Eletrônicos, Higiene Pessoal)
- Distribuição regional de vendas
- Performance por vendedor

### 🎯 Dashboard 2: Painel Executivo com KPIs
![Dashboard Executivo](Captura%20de%20tela%202025-12-10%20171042.png)

**Métricas Principais:**
- **Total Vendido:** R$ 173.173.340,00
- **Custo Total:** R$ 3.215.710,00  
- **Quantidade Vendida:** 4.268 unidades
- **Timeline:** Agosto/2021 a Dezembro/2022

**Visualizações:**
- 📊 Top 10 Vendedores (gráfico de barras)
- 📊 Top 10 Produtos Mais Vendidos (gráfico de barras horizontal)
- 🥧 Distribuição de Vendas por Região (gráfico de pizza)
- 📅 Timeline Interativa com filtros por período

### 🎯 Dashboard 3: Vendas Detalhadas
![Dados Detalhados](Captura%20de%20tela%202025-12-10%20174709.png)

**Informações Granulares:**
- Vendas individuais por transação
- Detalhamento por cliente e produto
- Datas de venda e nascimento
- Preços unitários e totais
- Custos por transação

---

## 📈 Principais Insights Gerados

### 💰 Visão Financeira
- **Faturamento Total:** R$ 173,2 milhões
- **Margem Bruta:** R$ 169,9 milhões (98,1% de margem)
- **Ticket Médio:** R$ 40.575,00 por unidade

### 🏆 Top Performers

#### Produtos Mais Vendidos:
1. **Aspirador robô** - R$ 5.816.200,00
2. **Desumidificador** - R$ 5.929.180,00
3. **Espremedor** - R$ 6.049.240,00
4. **Ferro de passar roupa** - R$ 6.066.980,00
5. **Alto-falante inteligente** - R$ 6.265.620,00

#### Top Vendedores:
1. **Estela Lima** - R$ 5.816.200,00
2. **Isadora Santos** - R$ 5.929.180,00
3. **Tiago Almeida** - R$ 6.049.240,00
4. **Gabriela Rodrigues** - R$ 6.066.980,00
5. **Karla Santos** - R$ 6.265.620,00

### 🗺️ Análise Regional
- **Sudeste:** R$ 52.030.760,00 (30%)
- **Nordeste:** R$ 45.540.380,00 (26%)
- **Centro-Oeste:** R$ 34.378.900,00 (20%)
- **Sul:** R$ 41.223.300,00 (24%)

### 📦 Por Categoria
- **Eletrodomésticos:** Categoria líder em faturamento
- **Eletrônicos:** Segundo maior volume
- **Higiene Pessoal:** Oportunidade de crescimento

### 📅 Análise Temporal
- Período analisado: 16 meses (Ago/2021 a Dez/2022)
- Identificação de sazonalidades e tendências de crescimento
- Picos de venda em períodos específicos

---

## 🎨 Recursos de Visualização

O dashboard inclui:

✅ **Gráficos de Barras** - Rankings de produtos e vendedores  
✅ **Gráficos de Pizza** - Distribuição regional de vendas  
✅ **Timeline Interativa** - Filtros por período com arrastar  
✅ **KPIs Destacados** - Métricas principais em destaque visual  
✅ **Filtros Dinâmicos** - Segmentação por categoria e região  
✅ **Paleta de Cores Profissional** - Design limpo e corporativo  
✅ **Responsividade** - Layout organizado e funcional  

---

## 💡 Excel vs Power BI: Quando Usar Cada Um?

### ✅ **Excel é ideal para:**
- Trabalho offline e sem dependência de internet
- Compartilhamento rápido via e-mail ou rede local
- Ambientes corporativos com restrições de software
- Análises pontuais e relatórios estáticos
- Integração com processos já estabelecidos em Excel
- Volumes de dados pequenos a médios (até 1 milhão de linhas)

### 🚀 **Power BI seria melhor para:**
- Dashboards altamente interativos e modernos
- Melhor performance com grandes volumes de dados (milhões de linhas)
- Atualização automática em tempo real
- Integração com múltiplas fontes de dados simultâneas
- Compartilhamento via web e mobile
- Visualizações mais sofisticadas e customizáveis
- Colaboração em equipe com workspaces compartilhados
- Recursos avançados de IA e análise preditiva

**🎯 Conclusão:** Ambas as ferramentas têm seu valor estratégico. O profissional versátil domina as duas e escolhe a melhor solução conforme o contexto, prazo, recursos disponíveis e necessidades do negócio.

---

## 🎓 Competências Demonstradas

### 📊 Análise de Dados
- Data Cleaning (Limpeza de Dados)
- ETL (Extract, Transform, Load)
- Modelagem de dados relacional
- Análise exploratória de dados (EDA)

### 📈 Business Intelligence
- Criação de dashboards executivos
- Definição e acompanhamento de KPIs
- Storytelling com dados
- Geração de insights acionáveis

### 🛠️ Ferramentas
- Microsoft Excel (Avançado)
- Power Query (M Language)
- Tabelas Dinâmicas
- Visualização de Dados

### 💼 Habilidades de Negócio
- Análise de vendas e performance
- Identificação de oportunidades de crescimento
- Suporte à tomada de decisão
- Comunicação de resultados para stakeholders

---

## 📁 Como Usar Este Projeto

### Pré-requisitos:
- Microsoft Excel 2016 ou superior
- Power Query habilitado (já vem nativo no Excel)

### Instruções:

1. **Faça o download** do arquivo Excel do repositório
2. **Abra o arquivo** no Excel
3. **Habilite macros e conteúdo** (se solicitado)
4. **Navegue pelas abas:**
   - `Planilha1`: Análise detalhada por linha de produtos
   - `Planilha3`: Dashboard executivo com KPIs principais
   - `vendas`: Base de dados completa com todas as vendas
   - `clientes`: Informações de clientes
   - `produtos`: Cadastro de produtos

5. **Explore os filtros interativos:**
   - Clique nos filtros de Categoria
   - Clique nos filtros de Região
   - Arraste a timeline para filtrar por período

6. **Atualize os dados** (se necessário):
   - Vá em `Dados` → `Atualizar Tudo`
   - O Power Query irá reprocessar todas as transformações

---

## 🔍 Próximos Passos e Melhorias

### 📋 Roadmap de Evolução:

- [ ] **Migrar para Power BI** para dashboards mais robustos e interativos
- [ ] **Adicionar análise preditiva** com previsão de vendas futuras
- [ ] **Implementar análise de churn** de clientes
- [ ] **Criar análise RFM** (Recency, Frequency, Monetary)
- [ ] **Desenvolver análise de cesta de compras** (Market Basket Analysis)
- [ ] **Automatizar relatórios** com envio automático por e-mail
- [ ] **Integrar com banco de dados** para atualização em tempo real
- [ ] **Adicionar análise de sazonalidade** com forecast estatístico
- [ ] **Criar alertas** para vendas abaixo da meta
- [ ] **Desenvolver análise de rentabilidade** por produto/categoria

---

## 📚 Aprendizados e Reflexões

### 🎯 O que funcionou bem:
- Power Query mostrou-se extremamente eficiente para ETL
- Tabelas dinâmicas permitiram análises flexíveis e rápidas
- Dashboard em Excel atendeu perfeitamente a necessidade urgente
- Modelo de dados relacional facilitou análises cruzadas

### 🚀 O que posso melhorar:
- Automatização de atualizações seria mais eficiente em Power BI
- Interatividade poderia ser maior com visuais do Power BI
- Performance com grandes volumes seria melhor em BI
- Compartilhamento via web seria mais prático

### 💭 Reflexão Final:
Este projeto reforça que **ferramentas são meios, não fins**. O importante é resolver o problema do negócio e gerar valor. Seja Excel, Power BI, Python ou qualquer outra ferramenta, o analista de dados precisa ser versátil e adaptar-se ao contexto para entregar resultados.

---

## 👨‍💻 Sobre Mim

Analista de Dados apaixonado por transformar dados em insights acionáveis que geram valor para o negócio. Experiência com Excel, Power BI, SQL, Python e ferramentas de Business Intelligence.

**Especialidades:**
- 📊 Business Intelligence & Analytics
- 🔄 ETL e Modelagem de Dados
- 📈 Dashboards e Visualização de Dados
- 💼 Análise de Negócios e KPIs

---

## 📬 Contato

Gostou do projeto? Vamos conversar sobre dados e análises!

www.linkedin.com/in/joséalexandredossantosjunior
[GitHub](https://github.com/junior19071983)
Email juninho-83@hotmail.com

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, estudar e modificar conforme necessário.

---

## ⭐ Apoie o Projeto

Se este projeto foi útil para você:
- ⭐ Deixe uma **estrela** no repositório
- 🔄 Compartilhe com outros profissionais de dados
- 💬 Deixe seu feedback nos **issues**
- 🤝 Contribua com melhorias via **pull requests**

---
<div align="center">


**Desenvolvido com 💙 por Junior**

*"Dados são o novo petróleo, mas só têm valor quando refinados em insights"*

</div>
