# ORACLE-function_partition
Exemplo de uso da função Partition no ORACLE

Sintaxe de Função Analítica
([argumentos]) OVER (cláusula_analítica)

![Alt Text](https://github.com/tauasilva/ORACLE-Partition_by/blob/master/Partition_sql.png)

Result
![Alt Text](https://github.com/tauasilva/ORACLE-Partition_by/blob/master/Partition.png)



#Partition
Analytic functions compute an aggregate value based on a group of rows. They differ from aggregate functions in that they return multiple rows for each group. The group of rows is called a window and is defined by the analytic_clause. For each row, a sliding window of rows is defined. The window determines the range of rows used to perform the calculations for the current row. Window sizes can be based on either a physical number of rows or a logical interval such as time.

Analytic functions are the last set of operations performed in a query except for the final ORDER BY clause. All joins and all WHERE, GROUP BY, and HAVING clauses are completed before the analytic functions are processed. Therefore, analytic functions can appear only in the select list or ORDER BY clause.

Analytic functions are commonly used to compute cumulative, moving, centered, and reporting aggregates.


Font: https://oracle-base.com/articles/misc/analytic-functions









