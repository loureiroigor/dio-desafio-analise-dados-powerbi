# Projeto Power BI - Azure Company

Repositório criado para o desafio de processamento e transformação de dados da DIO. O objetivo foi conectar uma base MySQL local ao Power BI, tratar os dados e montar o modelo relacional.

## O que foi feito:
- **Banco de Dados (MySQL):** Criei o esquema `azure_company`, rodei os scripts de criação de tabelas e inseri os dados (ajustando a ordem e as chaves estrangeiras).
- **Tratamento no Power Query:**
  - Juntei o primeiro, segundo e último nome dos funcionários em uma coluna só ("Nome Completo").
  - Dividi a coluna de endereço por traços para separar número, rua, cidade e estado.
  - Fiz o *Merge* das tabelas de funcionário e departamento para trazer o nome do setor de cada colaborador.
  - Limpei colunas que não iam ser usadas.
- **Modelagem:** Criei o relacionamento de 1 para muitos entre departamentos e funcionários.

## Arquivos:
- Scripts SQL utilizados.
- Arquivo `.pbix` do Power BI.
