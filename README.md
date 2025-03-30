# SleepTrack-Analytics
Repositorio criado para a matéria de Projeto Aplicado 2 - Mackenzie 2025

Integrantes do grupo:
Marcela Quaresma Soares - 10433423
Mariana Mayume Caniza - 10290174
Stella Amaral de Campos - 10441310 

1. PREMISSAS DO PROJETO
1.1 Definição da organização escolhida
A organização escolhida para este projeto é a “SleepTrack Analytics”, uma empresa fictícia criada pelas autoras do projeto, que será especializada no desenvolvimento de soluções baseadas em dados para monitoramento do sono e otimização da produtividade. 
A empresa tem como meta se tornar referência no fornecimento de insights personalizados para indivíduos e empresas, ajudando a melhorar a qualidade do sono e maximizar o desempenho profissional, além de expandir suas soluções para o mercado corporativo.

1.2 Área de Atuação
A SleepTrack Analytics atua na interseção entre tecnologia, saúde e ciência de dados, utilizando inteligência artificial e análise estatística para fornecer recomendações personalizadas sobre hábitos de sono e bem-estar.

1.3 Apresentação dos Dados Utilizados
O conjunto de dados contém 5000 registros de indivíduos entre 18 e 60 anos, monitorando seus hábitos de sono e os efeitos na produtividade. As variáveis presentes incluem:
Variáveis
Descrição
Tipo /Formato do dado
Data
Data da coleta de dados
aaaa-mm-dd
Pessoa_ID
Identificador único para cada indivíduo
Inteiro
Idade
Idade da pessoa (18-60 anos)
Inteiro
Gênero
Masculino, Feminino ou Outro
String
Hora de início do sono
Horário em que a pessoa foi para a cama
Float
Hora de fim do sono
Horário em que a pessoa acordou
Float
Total de horas de sono
Duração total do sono (em horas)
Float
Qualidade do sono
Qualidade do sono autorrelatada (escala: 1-10)
Inteiro
Exercício (minutos/dia)
Minutos gastos em exercícios por dia
Inteiro
Ingestão de cafeína (mg)
Quantidade de cafeína consumida em mg
Inteiro
Tempo de tela antes de dormir (minutos)
Tempo gasto usando telas antes de dormir
Inteiro
Horas de trabalho (horas/dia)
Total de horas de trabalho em um dia
Float
Pontuação de produtividade
Produtividade auto-relatada (escala: 1-10)
Inteiro 
Pontuação de humor
Humor auto-relatado (escala: 1-10)
Inteiro
Nível de estresse
Estresse auto-relatado (escala: 1-10)
Inteiro



2. OBJETIVOS E METAS
2.1 Objetivo Geral:
Desenvolver um modelo preditivo para análise da relação entre hábitos de sono e produtividade, utilizando inteligência artificial para identificar padrões e oferecer recomendações para otimização do desempenho e bem-estar, integrando-se às soluções da SleepTrack Analytics para oferecer recomendações baseadas em inteligência artificial para otimização do desempenho e bem-estar.

2.2 Objetivos Específicos:
Definir a organização e os dados utilizados no projeto, estabelecendo premissas e objetivos iniciais;
Coletar e preparar os dados necessários para a análise;
Desenvolver e validar um modelo preditivo para estimar a produtividade com base nos hábitos de sono;
Elaborar narrativas visuais e textuais para a comunicação dos resultados (storytelling);
Apresentar os resultados e recomendações de forma clara e acessível, destacando sua aplicabilidade para a melhoria da qualidade do sono e da produtividade.


Linguagem utilizada: Python

Base de dados: sleep_cycle_productivity.csv

Bibliotecas utilizadas: 
Pandas para leitura e manipulação simples de dados 
Seaborn
Matplotlib para plootar os graficos 
scipy.stats para calcular estatisticas
