# EPC3 Solution

2) 
    a. **Criar a população inicial**: `Rosembrock.initPopulation`\
        Cria uma nova população de cromossomos a partir de um número de indivíduos.\
    b. **Avaliar a população**: `Rosembrock.fitness`\
        Determina o nível de adaptação dos indivíduos da população
    c. **Selecionar população**: `genetic_algorithm.__selection`\
        Seleciona os indivíduos que participarão do processo de reprodução, de acordo com o grau de adaptação
    d. **Crossover**: `genetic_algorithm.__crossover`\
        Faz a combinação, a partir de um ponto de corte, das características dos pais selecionados para a geração de novos filhos.
    e. **Mutation**: `genetic_algorithm.__mutation`\
        Altera alguma característica dos filhos gerados baseado no teste de probabilidade de mutação, que é feito pela função `__mutationTest`

3) O algoritmo para quando o numero máximo de gerações é alcançado.

4) Tamanho da população: 100\
Número de gerações necessárias para encontrar o valor ótimo: 100
```
Best fit: Individual[0] = 0.999862
Solution found: [1, 1, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1]

Solution:
[1, 1, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 1]
x1 = 1.01176
x2 = 1.02353
f(x1,x2) = 0.000138427
```
![Plot](/EPC3/4.png)

5) Para 150 e 300 indivíduos, continuou o mesmo valor de gerações
        