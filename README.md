# Implementação do método simplex
#### Aluno: Gabriel Angelo Freire Gonçalves, 
#### Matrícula: 1275115


## Uso da função simplex

# Fluxo de uso da função
```
Exemplo de entrada :
   Conditions: 6 x1 + 15x2 <= 4500                            [ 6 15;
               4 x1 + 5 x2 <= 2000 -> conditionCoeffitients =   4  5;
               20x1 + 10x2 <= 8000                             20 10 ]
                               |             [ 4500;
                                --> limits =   2000;
%                              q                 8000 ];

$ >> conditionCoefficients = [6 15; 4 5; 20 10]
$ >> limits = [4500; 2000; 8000]
$ >> utilityCoeffitients = [ 16 32 ]
$ >> info = true
$ >> simplex(conditionCoefficients, limits , utilityCoeffitients , true)
Current solution: [0;0] 
 Utility: -0.000000 
Current solution: [0;300] 
 Utility: 9600.000000 
No further improvements possible:
Current solution: [250;200] 
 Utility: 10400.000000 
ans =

   250
   200

```
