# Projetoebacsemantix

# Projeto: Análise Exploratória de Discriminação Algorítmica - COMPAS Dataset
O projeto escolhido tem como finalidade de explorar as possiveis causas e discriminações algorítmicas no sistema de pontuação de risco **COMPAS**, utilizado no sistema judicial dos Estados Unidos para prever reincidência criminal. Através de análise de dados e apresentação, identifiquei resultados interessantes de acordo com atributos como raça.

## Objetivos
* Analisar possíveis vieses no algoritmo COMPAS.
* Investigar a distribuição das pontuações de risco por raça.
* Calcular taxas de reincidência reais versus previstas.
* Identificar falsos positivos e falsos negativos.
* Comunicar os achados por meio de visualizações no Looker Studio.

## Descrição do Problema
O algoritmo COMPAS é amplamente utilizado no sistema judicial para prever o risco de reincidência de réus. Diversos estudos apontam que o algoritmo pode apresentar vieses, especialmente relacionados à raça, o que pode impactar diretamente decisões judiciais.
A crescente adoção de sistemas de inteligência artificial em processos automatizados, como analise de crédito, contratação de funcionários e sentença judiciais, tem voltado por um desafio ético significativo: a discriminação algorítmica. Esses sistemas, treinados com grandes volumes de dados, podem reproduzir e apresentar preconceitos existentes na sociedade.
Um dos casos mais conhecidos é o do sistema COMPAS (Correctional Offender Management Profiling for Alternative Sanctions), utilizado nos Estados Unidos para prever a probabilidade de reincidência criminal. Estudos revelaram que o algoritmo apresentava viés racial, classificando negros como mais propensos à reincidência do que brancos com histórico semelhante, mesmo sem considerar diretamente a variável “raça”.
A importância desse problema é grande: algoritmos enviesados podem afetar a vida dessa pessoas de forma injusta, aplicando desigualdades históricas e comprometendo a confiança nos sistemas de IA. A análise de dados é uma ferramenta essencial para identificar esses padrões de discriminação e propor melhorias nos modelos preditivos.
Neste projeto, pretendo fazer uma análise exploratória do dataset do COMPAS, verificando a existência de viés no modelo de previsão de reincidência, especialmente em relação à variável racial. O objetivo é mostrar, com base em dados e algoritmos podem tomar decisões injustas. E por fim análise de dados pode servir como aliada para uma IA mais ética e justa nos sistemas.

## Fontes de Dados
* Dataset público: [COMPAS Two-Year Recidivism Dataset - ProPublica](https://github.com/propublica/compas-analysis)
* Dados estruturados em formato CSV.
* Coletados diretamente via download manual para o ambiente do Colab.(https://docs.google.com/spreadsheets/d/1Gy_9EjZbGgJE11NwRV_3FrJtn-XCboP_poJQOgTRG9k/edit?gid=2058290409#gid=2058290409)

## Tecnologias Utilizadas
* Google Colab/PySpark/Python/SQL/Pandas/Looker Studio.

## Como foi feita a Análise
1. **Importação e Limpeza dos Dados**
2. **Análise de Distribuição por Raça e Score de Risco**
3. **Cálculo da Taxa de Reincidência Real**
4. **Identificação de Erros do Algoritmo (Falsos Positivos e Negativos)**
5. **Exportação dos Dados Processados**
6. **Visualizações no Looker Studio**

## Visualizações
* \[Link do Dashboard Looker Studio - https://lookerstudio.google.com/reporting/15fbc8a0-dd0e-47de-9e44-f1011c148ecf]
* \[Link da analise no google colab - https://docs.google.com/spreadsheets/d/1Gy_9EjZbGgJE11NwRV_3FrJtn-XCboP_poJQOgTRG9k/edit?gid=2058290409#gid=2058290409]

## Principais Conclusões
* Foram observadas diferenças significativas nas taxas de falsos positivos e negativos entre diferentes grupos raciais.
* Esses resultados indicam a necessidade de monitoramento rigoroso e auditoria de algoritmos utilizados em decisões judiciais.

## Conclusão
O projeto reforça a importância da **análise de dados ética** para identificar e combater discriminações algorítmicas em sistemas automatizados, especialmente quando tais sistemas impactam na vida humana.

