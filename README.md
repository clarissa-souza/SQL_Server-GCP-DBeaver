Criar um banco de dados SQL Server com o nome "academico"

Criar as seguintes tabelas:

Pessoa
Aluno
Curso
Curriculo
Disciplina
Matricula

Regras do banco: 

1.A tabela pessoa só deve ter relação com a tabela aluno. A tabela aluno deve ter relação com curso e currículo. A tabela disciplina deve ter relação com curso e currículo. A tabela matrícula deve ter relação com aluno, curso e disciplina.

2.Os atributos de cada tabela devem ser criados de forma espontânea, sendo que cada tabela deve ter “id” específico, seguindo as instruções passadas no item anterior.

3.Deve ser criado os seguintes relatórios:

3.1. Alunos ativos por curso

3.2. Aluno matriculados por curso

3.3. Disciplinas matriculadas

3.4. Alunos ativos por curso e currículo

3.5. Aluno sem curso

3.6. Disciplina com matrículas

3.7. Disciplinas do currículo  

O banco de dados SQL Server proposto por este desafio foi feito no Cloud SQL do Google.
A ferramenta utilizada para criar tabelas, popular o banco e gerar os relatórios foi o DBeaver 22.3.0
