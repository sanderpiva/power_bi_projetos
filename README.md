# 📊 Projetos com Power BI & Data Science

<p align="justify">
Este repositório apresenta soluções práticas para problemas de negócio, unindo o poder de visualização do <b>Power BI</b> com algoritmos de <b>Machine Learning</b> em Python e R. Os projetos aqui desenvolvidos foram inspirados a partir do conteúdo didático da <b>Data Science Academy (DSA)</b>. As bases de dados utilizadas são fictícias, com foco em demonstração técnica e analítica.
</p>

---

## 🎯 Problema de Negócio 1: Segmentação de Clientes
**Cenário:** A empresa busca agrupar clientes por similaridade (Idade, Renda e Score de Gastos) para personalizar campanhas de marketing.

* **Tecnologia:** Python (Pandas, Scikit-Learn) no Google Colab.
* **Modelo:** Clusterização (aprendizado não supervisionado) para definição de 3 perfis distintos.

> [!TIP]
> **Dica:** Foco na observação de padrões comportamentais para segmentação estratégica.

**Relatório de Segmentação Inicial:**
<br>

![Segmentação](https://github.com/user-attachments/assets/bf75d9b3-0679-4b99-9fc2-c6111698c06c)

**Interpretação dos Clusters:** Após a clusterização, os grupos foram rotulados com base na observação das médias de idade:
  
<ul>
  <li>Cluster 0 → Jovem: Clientes com perfil de menor idade (Média: 27 anos).</li>
  <li>Cluster 1 → Meia-idade: Clientes na faixa intermediária (Média: 53 anos).</li>
  <li>Cluster 2 → Sênior: Clientes com 54 anos ou mais (Média: 54 anos).</li>
</ul>
<br>

**Relatório de Segmentação Final:**
<br><br>
![relatorio_segmentacao_clientes_area_marketing](https://github.com/user-attachments/assets/6dc86cab-2d23-4316-9ec5-cd8c33e78aaa)


---

## 🛡️ Problema de Negócio 2: Detecção de Anomalias Financeiras
**Cenário:** Identificar transações suspeitas em dados históricos sem que o padrão de fraude seja previamente conhecido.

* **Tecnologia:** Linguagem R (RStudio).
* **Modelo:** *Isolation Forest* (aprendizado não supervisionado) para detecção de outliers.
<br><br><br>

**1. Relatório Inicial (Visão Geral):**
<br><br>

![relatorio_inicial](https://github.com/user-attachments/assets/abd03a10-e095-46ff-b9a3-7b9f026a5496)


<br><br>

**2. Casos de Anomalia Detectados:**
<br><br>

![relatorio_casos_anomalia](https://github.com/user-attachments/assets/1ac4cd86-864c-4437-a4ef-d745cb5e4f35)


<br><br>

**3. Casos Classificados como Normais:**
<br><br>

![relatorio_casos_normais](https://github.com/user-attachments/assets/002f4e41-c56b-4850-a478-71acf8691ae9)

<br><br>

**4. Integração com Script R (Visualização Customizada):**
<br><br>
Para superar as limitações de gráficos nativos do Power BI e obter uma análise estatística mais profunda, foi utilizado um script em R com a biblioteca `ggplot2` para gerar os gráficos de BoxPlot diretamente no dashboard.

![4-adicionando_script_R_ao_relatorio](https://github.com/user-attachments/assets/2f1b8ca3-3b44-4a35-b925-da9a3cb4df4a)


<br><br>

---

## 📈 Problema de Negócio 3: Engenharia de Produção (IA)
**Cenário:** Análise de séries temporais para prever a produção e identificar quedas anormais na linha produtiva.

* **Tecnologia:** Inteligência Artificial Nativa do Power BI.
* **Recursos:** Forecasting (Previsão) e Detecção de anomalias em tempo real.

**Relatório de Séries Temporais:**
<br>

![Engenharia](https://github.com/user-attachments/assets/f2d76945-ee61-47dd-82d1-bc767130db77)

---

## ⚙️ Configuração do Ambiente

> [!IMPORTANT]
> Para que o relatório funcione corretamente na sua máquina, siga este passo a passo para atualizar os caminhos dos dados:

1. No Power BI, clique em **Transformar Dados**.
2. No painel direito, procure a etapa **Fonte** e clique no ícone da **Engrenagem**.
3. Altere o caminho do arquivo para o local onde você salvou a base de dados.

**Guia Visual de Configuração:**
<br>

![Configuração](https://github.com/user-attachments/assets/c8a0cca3-cef8-4c94-9bdd-72902fa15b24)

---
**Autor:** Sander Gustavo Piva
