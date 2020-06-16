# PROBLEMA DE AGENDAMENTO DE CIRURGIAS ELETIVAS 
O problema de agendamento de cirurgias eletivas é modelado como um caso particular do clássico problema de Job Shop Scheduling, então denominado de Problema de Otimização de Agendamento de Cirurgias Eletivas - POACE. Como proposta de solução computacional para o problema, realizou-se a implementação da Metaheurística GRASP. Foram realizados experimentos com pequenas instâncias geradas a partir de dados reais obtidos em um hospital da cidade de Mossoró/RN, e com instâncias fictícias de médio porte, as quais foram geradas seguindo o padrão de comportamento estatístico das instâncias reais. Neste projeto disponibilizamos as instâncias criadas para a realização dos experimentos. 

# Insâncias para o POACE 
Para os experimentos, foram utilizadas sete instâncias de testes, sendo quatro geradas com dados reais e três com dados fictícios. A utilização de instâncias com dados fictícios visa a possibilidade de criar cenários que melhor exploram os limites da metaheurística para o problema. Com as instâncias fictícias é possível, por exemplo, utilizar cenários com cirurgias de maior tempo que os tempos reais, estabelecer quantidades elevadas (ou reduzidas) de determinado tipo de cirurgia, dentre outros parâmetros que podem ser regulados para efeito experimental. Assim, foram criadas as instâncias FICT-21-S2, FICT-100-S5, FICT-200-S10, onde o número logo após a sigla “FICT” indica a quantidade de cirurgias (tarefas) e o número após o “S” indica a quantidade de salas (máquinas) disponíveis. No caso das instâncias fictícias os tempos de processamento das tarefas foram gerados de forma aleatória, com base em critérios experimentais de definição dos cenários desejados.

Para a elaboração das instâncias reais,  foram utilizados dados disponibilizados pelo Centro de Oncologia e Hematologia de Mossoró - COHM onde cada unidade de tempo representa meia hora em tempo real.  Foram criadas as instâncias  COHM-11-S3, COHM-50-S4, COHM-75-S5, COHM-130-S6, onde o número logo após a sigla “COHM” indica a quantidade de cirurgias (tarefas) e o número após o “S” indica a quantidade de salas (máquinas) disponíveis.
Para todas as instâncias foram consideradas unidades de tempo em blocos de 30 minutos para composição dos tempos de execução de tarefa (tempo de realização de cada cirurgia).

# Construção de Instâncias com os dados reais  

Para realizar o teste com os dados cedidos, pelo Centro de Oncologia e Hematologia de Mossoró, foram usados os tempos de início e fim de cada cirurgia para chegar há uma média de tempo de duração, em seguida foi analisado qual a cirurgia tinha maior prioridade, após identificar o tempo médio das cirurgias, em horas (organizado em blocos de 30 minutos), e criar a lista de  prioridades, é criada a lista de cirurgias LC para a execução da heurística construtiva. 


Para mais inforamções consultar o artigo: APLICAÇÃO DO GRASP AO PROBLEMA DE AGENDAMENTO DE CIRURGIAS ELETIVAS.
Link: 





