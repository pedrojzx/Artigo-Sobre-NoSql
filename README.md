# Artigo-Sobre-NoSql
Integrantes: Taywan Francisco, Pedro Roberto

•	Artigo sobre tipos de dados e regras na modelagem SQL

Integrantes: Taywan Francisco, Pedro Roberto




•	Tipos de Dados NoSQL

Oque seria tipos de dados em NoSQL?
Enquanto o SQL exige que você defina os tipos de dados rigidamente (como INT, VARCHAR, etc.), em bancos NoSQL, os dados são geralmente armazenados em forma de documentos, objetos ou pares "chave: valor”, Mesmo com essa flexibilidade, os dados ainda possuem tipos internos, que são importantes para garantir que o banco consiga organizar, filtrar, e fazer cálculos corretamente.

FONTES:https://www.alura.com.br/artigos/banco-de-dados?srsltid=AfmBOoou21aI1XOEb2kZlmzzGkK5Z5n3mzWKdD7CalDePjDvsp6o8nUL


Tipos numéricos :Armazenam valores inteiros ou decimais. Normalmente servem para representar valores numéricos, como contagens, valores financeiros, medidas e etc.  


 
Aproximados: Usados para valores que não precisem de precisão exata, como resultados de cálculos científicos
Exemplos: REAL/FLOAT: Números de ponto flutuante
DOUBLE PRECISION: Números de ponto flutuante com maior precisão

FONTES:https://www.w3schools.com/sql/sql_datatypes.asp
https://www.devmedia.com.br/sql-server-comandos-basicos-objetos-tipos-de-dados-e-criacao-de-database/17052




Tipos de Texto(string): Usado para armazenar qualquer tipo de texto, como nomes, endereços, códigos, descrições, entre outros.
 
 


FONTES: https://www.rlsystem.com.br/tipos-dados-sql-server
https://www.homehost.com.br/blog/tutoriais/mysql/tipos-de-dados-do-mysql/

Tipos de Data e Hora: Utilizado para armazenar datas, horários ou ambos

 
 


FONTES: https://www.sqlite.org/datatype3.html
              https://learn.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver17





Outros Exemplos de tipos de dados e suas funções:

 
 

FONTES:https://www.rlsystem.com.br/tipos-dados-sql-server https://www.mco2.com.br/artigos/guia-completo-dos-tipos-de-dados-nosql-server.html










•	Restrições de Integridade em SQL

O que é: As restrições de são regras definidas no banco de dados para garantir a consistência, precisão e validade dos dados armazenados nas tabelas.
Integridade da Entidade
 O que é:
Garante que cada linha (registro) de uma tabela tenha uma identidade única — ou seja, que não existam registros sem identificação ou duplicados.
 Como funciona:
•	Através de uma chave primária (PRIMARY KEY).
•	A chave primária não pode ser nula (NULL) e não pode se repetir.
•	Cada tabela deve ter pelo menos uma chave primária.
 Integridade Referencial
O que é:
Garante que os relacionamentos entre tabelas estejam corretos — ou seja, que um registro referenciado em outra tabela realmente exista.
 Como funciona:
•	Usando chaves estrangeiras (FOREIGN KEY).
•	Uma chave estrangeira em uma tabela deve corresponder a uma chave primária válida em outra tabela.
•	Impede, por exemplo, que você registre um pedido para um cliente que não existe.


 Integridade da Chave
 O que é:
Garante que os campos definidos como chaves (primárias ou candidatas) sejam:

•	Únicos (não se repetem),
•	Não nulos (obrigatórios).
•	Como funciona:
Usa índices únicos (UNIQUE) e restrições NOT NULL para evitar duplicações.
Pode ser aplicada a campos como CPF, e-mail, matrícula, código de produto etc.

