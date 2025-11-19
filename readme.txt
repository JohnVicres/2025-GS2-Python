Ideia:
Modelo de "computação compartilhada" em que uma IA executa tarefas de "pouca demanda", e transfere tarefas de "alta demanda" para um ser humano, com o objetivo de diminuir o gasto energético da IA com tarefas que, se excessivamente complexas para ela, seriam geralmente menos complexas para um humano.
-pesos intrínsecos para definir dificuldade da tarefa;
-quick sort para reorganizar a fila a cada 4 novas entradas;
-a fila é única, a IA atende no padrão "pilha", o humano atende no padrão "fila";
-saída imprimindo comprimento e peso total da fila a cada 50 atendimentos e histórico de quantidade de tarefas cumpridas.

Para a simulação:
-timer de 1s+0.5s*peso para IA, 5s+0.1s*peso para humano
-pesos de 1 a 20
-lista de 500 tarefas com pesos aleatórios