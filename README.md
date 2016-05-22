# PricingHedging_ExerciseTwo

Segundo exercício da aula de MECAI - Precificação e Hedging

1. Usando o construtor de portfolios hedgeados e simulação de Monte Carlo que vocês já tem ou vão poder copiar/adaptar de https://github.com/MarcosCarreira/DermanPapers e o paper do Wilmott, simulem o tipo de resultado que ele obteve:

   Output desejado:
   Os dois gráficos de P&L no tempo para os casos de hedge com vol real e vol implícita (páginas 24 e 31)
   Distribuição do P&L final e comparação com resultados teóricos (páginas 21 e 29 e paper do Derman)
   Podem usar r=q=0 e K=S0
   Para o gráfico 20 trilhas servem
   Para a distribuição umas 500.

   Dica: Usem como inputs volpricing=implícita e voldelta=implícita ou real
   O Monte Carlo usa a vol real

2. Transformem o P&L final do portfolio em uma função e calculem a breakeven vol das 500 trilhas anteriores para o strike K=S0. Qual a distribuição? Gerem um scatter plot das breakeven vols vs as vols realizadas das trilhas.

3. Usem as primeiras 20 trilhas e gerem o breakeven smile para cada uma dessas trajetórias (usem 5 strikes para cada smile, -10 delta, -25 delta, ATM, 25 delta, 10 delta). Algo a observar?

   ![alt text](https://github.com/fbristotti/PricingHedging_ExerciseTwo/blob/master/images/breakeven_smile.png "Algo a observar?")


4. Usem as primeiras 5 trilhas e para cada trilha gerem o gráfico com o P&L final do portfolio para cada strike em função da vol usada no hedge (usem 5 strikes para cada smile, -10 delta, -25 delta, ATM, 25 delta, 10 delta). Algo a observar?

5. Usando dados reais (2 períodos de 6 meses, um calmo e outro de crise), calcule breakeven smiles de 3 e 6 meses.
