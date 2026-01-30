Projetos com Power BI

Problema de negócio 1: 
Imagine que uma empresa tenha dados históricos de clientes que fizeram compras de produtos ou serviços. Os dados incluem, para cada cliente: idade, renda anual e uma pontuação
de gasto (poder de compra do cliente).
A empresa gostaria de segmentar esses clientes em 3 grupos de acordo com similaridades a fim de personalizar as campanhas de Marketing.
O gestor da área de Marketing espera receber um relatório com os 3 segmentos e para cada segmento a média de idade, renda anual e pontuação de gastos dos clientes.

Solução?

Criar um codigo no Google Colab em Python para definir o modelo preditivo (Clusterização), agrupando a partir de padrões de cada cliente. 
Com o dataframe a disposição, no Power BI, carregar os dados, fazer os ajustes necessários se houver e construir um relatório com gráficos para análise de dados.
Com esse relatório, o gestor poderá tomar a melhor decisão. Veja foto do relatório:

![relatorio_segmentacao_clientes_area_marketing](https://github.com/user-attachments/assets/bf75d9b3-0679-4b99-9fc2-c6111698c06c)
foto: Relatório segmentação de clientes

Problema de negócio 2:
Imagine que uma empresa da área financeira tenha dados históricos de clientes com duas transações financeiras (aqui chamadas de “transacao1” e “transacao2”). 
Os gestores acreditam que algumas dessas transações possam ser fraudulentas e gostariam de identificar as eventuais anomalias. 
Os gestores não fazem ideia do que seria uma anomalia e pediram sua ajuda para encontrar uma solução. 
De fato, eles não sabem se anomalias realmente ocorreram. Usando dados fictícios usaremos Machine Learning par agrupar os dados de transações
financeiras dos clientes e então detectar e definir as anomalias (se existirem). O resultado deve ser entregue no formato visual.

Solução? 

Criar um código em R, no RStudio para definir o modelo preditivo (IsolationForest), agrupadando os dados a partir de dois grupos: normais e com anomalias.
Com o dataframe a disposição, no Power BI, carregar os dados, fazer os ajustes necessários se houver e construir um relatório com gráficos para análise de dados.
Com esse relatório, o gestor poderá tomar a melhor decisão. Veja fotos:

![relatorio_inicial](https://github.com/user-attachments/assets/ba4822d5-6dc9-44bc-868c-6c07a08e0ba8)

foto: Relatório carregado

![relatorio_casos_anomalia](https://github.com/user-attachments/assets/5e45715a-cdd2-401c-8535-090f2c686922)

foto: Relatório com casos de transações com anomalias (Selecionar o botão 'anomalia')

![relatorio_casos_normais](https://github.com/user-attachments/assets/6e4cc07b-6179-41d0-b4eb-5fe623b5f3f8)

foto: Relatório com casos de transações normais (Selecionar o botão 'normal')

Problema de negócio 3:

Nesta projeto, o Power BI é usado para manipular e compreender os dados, explorando alguns conceitos de análise de séries temporais. 
Por fim, são apresentados recursos de IA do Power BI para prever a média de unidades produzidas ao longo do tempo e detecção de anomalias. 
O Dashboard criado ao final da atividade serve como ponto de partida para o dia a dia de Engenheiros de Produção.
Os dados usados no Lab são fictícios e estão disponíveis em anexo. Veja foto:

![relatorio_eng_producao_com_power_bi_ia](https://github.com/user-attachments/assets/f2d76945-ee61-47dd-82d1-bc767130db77)
foto: Relatório com Power BI com foco em séries temporais: Engenharia de Produção.

IMPORTANTE! Ao abrir o relatório no Power BI, certificque-se de atualizar o caminho para a respectiva base de dados. 
Precisa clicar em transformar dados, ir na engrenagem no canto inferior direito em 'fonte' e atualizar. Veja foto com um passo a passo da configuração:

![definindo_caminho_base_dados_exemplo](https://github.com/user-attachments/assets/c8a0cca3-cef8-4c94-9bdd-72902fa15b24)
foto: Configurando caminho para sua base dados no Power BI

FIM
