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

<img width="756" height="416" alt="1" src="https://github.com/user-attachments/assets/9e8bd1f3-72c0-46bb-b358-d3ad031c3ae6" />


**Interpretação dos Clusters:** Após a clusterização, os grupos foram rotulados com base na observação das médias de idade:
  
<ul>
  <li>Cluster 0 → Jovem: Clientes com perfil de menor idade (Média: 27 anos).</li>
  <li>Cluster 1 → Meia-idade: Clientes na faixa intermediária (Média: 53 anos).</li>
  <li>Cluster 2 → Sênior: Clientes com 54 anos ou mais (Média: 54 anos).</li>
</ul>
<br>

**Relatório de Segmentação Final:**
<br><br>
<img width="758" height="417" alt="2" src="https://github.com/user-attachments/assets/b7384082-2399-4251-b657-548804d15d68" />



---

## 🛡️ Problema de Negócio 2: Detecção de Anomalias Financeiras
**Cenário:** Identificar transações suspeitas em dados históricos sem que o padrão de fraude seja previamente conhecido.

* **Tecnologia:** Linguagem R (RStudio).
* **Modelo:** *Isolation Forest* (aprendizado não supervisionado) para detecção de outliers.
<br><br><br>

**1. Relatório Inicial (Visão Geral):**
<br><br>

<img width="754" height="407" alt="3" src="https://github.com/user-attachments/assets/6d4b32c8-8416-4279-b5e6-d8c9e2e1bb7e" />



<br><br>

**2. Casos de Anomalia Detectados:**
<br><br>

<img width="754" height="410" alt="4" src="https://github.com/user-attachments/assets/e4faadca-3c16-4dc1-b463-2c56a1b72ca4" />



<br><br>

**3. Casos Classificados como Normais:**
<br><br>

<img width="758" height="412" alt="5" src="https://github.com/user-attachments/assets/8068ad04-f7f1-4491-90ed-2e791a23bb91" />


<br><br>

**4. Integração com Script R (Visualização Customizada):**
<br><br>
Para superar as limitações de gráficos nativos do Power BI e obter uma análise estatística mais profunda, foi utilizado um script em R com a biblioteca `ggplot2` para gerar os gráficos de BoxPlot diretamente no dashboard.

<img width="761" height="484" alt="6" src="https://github.com/user-attachments/assets/b403a9ac-62b9-423b-ba4f-c5517e28e7ea" />



<br><br>

---

## 📈 Problema de Negócio 3: Engenharia de Produção (IA)
**Cenário:** Análise de séries temporais para prever a produção e identificar quedas anormais na linha produtiva.

* **Tecnologia:** Inteligência Artificial Nativa do Power BI.
* **Recursos:** Forecasting (Previsão) e Detecção de anomalias em tempo real.

**Relatório de Séries Temporais:**
<br>

<img width="773" height="453" alt="7" src="https://github.com/user-attachments/assets/cff4338f-22f6-41b4-ab53-df6a7bb0a056" />


---

## ⚙️ Configuração do Ambiente

> [!IMPORTANT]
> Para que o relatório funcione corretamente na sua máquina, siga este passo a passo para atualizar os caminhos dos dados:

1. No Power BI, clique em **Transformar Dados**.
2. No painel direito, procure a etapa **Fonte** e clique no ícone da **Engrenagem**.
3. Altere o caminho do arquivo para o local onde você salvou a base de dados.

**Guia Visual de Configuração:**
<br>

<img width="791" height="443" alt="8" src="https://github.com/user-attachments/assets/19bed5d6-14a0-4d70-895e-ceb8546cbe25" />


---
**Autor:** Sander Gustavo Piva
