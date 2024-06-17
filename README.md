Olá!! Este repositório contém meus estudos e desafios de projeto como Analista de Dados e Power Bi.

Referente ao arquivo transformacao_limpeza_dados.pbix foi criada uma instancia de banco de dados Mysql na azure, a mesma foi acessada no powerbi e feito a transformação dos dados. Segue alguns passos realizados :

 - Modificado os valores monetarios para o tipo decimal fixo.
 - Foi desmembrada as colunas complexas, como de endereço.
 - Houve uma mescla das tabelas de employees e departament, afim de criar uma nova tabela para a relaçao entre as duas.
 - Houve uma mescla das tabelas de departament e dpt_location, afim de criar uma nova tabela para a relaçao entre as duas. Optei por usar a mescla de consultas porque se tivesse optado por acrescentar consultas para este caso iria perder a relação entre o Dno do departamento e sua localização, visto que a amarraçao entre eles e feita atráves deste atributo e assim iria gerar valores nulos nesta coluna. O que seria necessário fazer mais uma transformação dos dados.
 - As colunas Fname e Lname se tornaram apenas uma nova coluna. 
