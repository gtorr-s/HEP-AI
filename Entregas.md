Base de dados: https://www.kaggle.com/datasets/fedesoriano/hepatitis-c-dataset/

Entrega 02:

Explicação:

O conjunto de dados contém valores laboratoriais de doadores de sangue e pacientes com hepatite C e valores demográficos como idade.
Os dados foram obtidos do Repositório de Aprendizado de Máquina UCI:  https://archive.ics.uci.edu/ml/datasets/HCV+data

Estrutura:

Todos os atributos, exceto Categoria e Sexo, são numéricos.
Os atributos 1 a 4 referem-se aos dados do paciente.
Os atributos 5 a 14 referem-se a dados laboratoriais:

1) X (Paciente ID/No.) (Variavel int)
2) Category (diagnóstico) (valores: '0=Doador de Sangue', '0s=Doador de Sangue Suspeito', '1=Hepatite', '2=Fibrose', '3=Cirrose') (Variavel String)
3) Age (Idade em anos) (Variavel int)
4) Sex (Sexo do paciente feminino e masculino) (Variavel String)
5) ALB (Exame de sangue de albumina) (Variavel float)
6) ALP (Fosfatase alcalina) (Variavel float)
7) ALT (Alanina transaminase) (Variavel float)
8) AST (Aspartato transaminase) (Variavel float)
9) BIL (Bilirrubina) (Variavel float)
10) CHE (Acetilcolinesterase) (Variavel float)
11) CHOL (Colesterol) (Variavel float)
12) CREA (Creatinina) (Variavel int)
13) GGT (Gama-Glutamil Transferase) (Variavel float)
14) PROT (Proteínas) (Variavel float)

Entrega 03:

Variavel Target - a variavel para ser calculada será o diagnóstico do paciente em relação as resultados de laboratorios, 
que será a tabela do banco de dados chamada "Category".

Variaves a serem transformadas - Transformamos a categoria "Category" para somente números inteiros e cada um significando 
o seu respectivo diagnostico, excluimos a categoria "X", pois ela não sera importante.


