# Relatorio2DIO_PowerBI
Santander Bootcamp 2023 - Ciência de Dados com Python

## Relatório de Alterações Resumido:

- Filtragem de dados nulos nas tabelas no Power BI.
- Redefinição da estrutura da coluna complexa "Address" na tabela "employee" usando o delimitador "-", resultando em quatro novas colunas: "number," "location1," "location2," e "city."
- Mesclagem das tabelas "employee" e "departament" com base nas colunas "Dno" e "Dnumber."

## Nomes de Gerentes e Colaboradores no Power BI:

- Mesclagem da tabela "departament" com a coluna "Mgr_ssn" da tabela "employee," resultando na retenção apenas da coluna "Mgr_ssn." 
- Mesclagem das colunas "Fname" e "Lname" dos gerentes e renomeação como "Name_Mgr."
- Mesclagem da tabela "employee" com a tabela mesclada "managers."
- Eliminação de colunas, mantendo apenas a coluna com o nome dos colaboradores (mesclagem de "Fname" e "Lname" como "Name_employee") e a coluna com o nome do gerente (Name_Mgr).

### Nomes de Departamentos e Localização no Power BI:

- Mesclagem da tabela "dept_location" com a tabela "departament" com base na coluna "Dnumber."
- Retenção das colunas "Dlocation" e "Dname" após a mesclagem.

#### Criando Relatório Power BI:
Criação de um relatório sobre informações de departamento, incluindo:

- Projetos por departamento
- Colaboradores por departamento
- Gerentes por departamento
- Colaboradores por sexo por departamento
- Média salarial por departamento
- Departamento por localização.

## Aprendizados

Neste desafio o aprendizado principal é a importância da preparação de dados, da mesclagem de tabelas, da criação de relatórios significativos e da utilização das ferramentas do Power BI para análise de dados de forma a obter insights úteis a partir das informações disponíveis.
