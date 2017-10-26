Este repositorio contiene los ficheros de test de la prática de CSI de lógica proposicional realizada en MiniZinc. Contiene dos carpetas. La carpeta de "pruebas_especificas" prueban concretamente casos básicos de cada cláusula del enunciado. La carpeta de "pruebas_de_carga" prueban casos aleatorios con grandes cantidades de variables sobre el enunciado.

A continuación se muestra para cada "pruebas_especificas" si el modelo es satisfactible o no.

FILE | SAT/UNSAT | TEST
-----|---------- | ----
prova_1 |SAT   | Todas las personas tienen 1 única parada y bus asignado
prova_2 |UNSAT | Un autobus no puede llevar mas de 'c' personas
prova_3 |SAT   | Un autobus no puede llevar mas de 'c' personas
prova_4 |UNSAT | Un bus no puede hacer más de 't' paradas
prova_5 |SAT   | Un bus no puede hacer más de 't' paradas
prova_6 |UNSAT | Cada persona de un mismo group debe viajar junta
prova_7 |SAT   | Cada persona de un mismo group debe viajar junta
prova_A |      |

A continuación se muestra para cada "pruebas_de_carga" si el modelo es satisfactible o no.

FILE | SAT/UNSAT
-----|----------
10_1 |SAT
10_2 |UNSAT	
10_3 |UNSAT
10_4 |UNSAT
10_5 |UNSAT
25_1 |SAT
25_2 |UNSAT
25_3 |UNSAT
25_4 |UNSAT
25_5 |SAT
50_1 |SAT
50_2 |UNSAT
50_3 |UNSAT
50_4 |SAT
75_1 |UNSAT
75_2 |SAT
100_1|UNSAT
