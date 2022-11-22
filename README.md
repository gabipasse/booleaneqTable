# booleaneqTable
Python code that turns boolean equations into truth tables. // Código em python que converte equações booleanas em tabelas verdade.

O desenvolvimento desse método foi baseado em 3 etapas. A primeira etapa foi a de encontrar equações que relacionassem, de forma consisente, os diferentes parâmetros que são implicitamente definidos a partir da simples definição da quantidade de variávis (únicas) presentes na equação requerida. Por exemplo, a relação "2**(len(a)//2 + 1)"; que define, a partir da quantidade de variáveis únicas, quantas linhas estarão presentes para cada coluna. 

A segunda etapa foi a percepção de a estrutura fundamental para estruturação (e inputação) a serem rodados para cada variável única seguia uma sequêncial ordinal, mas no valor em bits de 0 até (n-1); sendo n a quantidade de linhas. Outra percepção importante foi a de que, apesar dessa correlação direta, era necessário uma formatação posterior quanto a extensão de zeros a esquerda necessários serem adicionados para manter a correlação fundamental das tabelas verdades.

A terceira etapa foi a de entendimento de que não era necessário lidar com os operadores inputados. Esses seriam a parte fixa, modificando apenas os valores das variáveis dentro dessa estrutura fixa. Além disso, foi importante utilizar o método replace pois, dessa forma, foi possibilitada a definição de variáveis repetidas apenas a partir da iteração sobre a primeira aparição dessa variável no input original.

Desensolvi esse método a partir de cálculos manuais por indução (etapa 1), e a partir da adaptação da minha lógica primeira para os métodos lógicos da linguagem de programação em questão (python). 

>:D
