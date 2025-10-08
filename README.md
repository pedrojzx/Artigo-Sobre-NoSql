# Artigo-Sobre-NoSql
Integrantes: Taywan Francisco, Pedro Roberto

•	Artigo sobre tipos de dados e regras na modelagem SQL

Integrantes: Taywan Francisco, Pedro Roberto




•	Tipos de Dados NoSQL

Oque seria tipos de dados em NoSQL?
Enquanto o SQL exige que você defina os tipos de dados rigidamente (como INT, VARCHAR, etc.), em bancos NoSQL, os dados são geralmente armazenados em forma de documentos, objetos ou pares "chave: valor”, Mesmo com essa flexibilidade, os dados ainda possuem tipos internos, que são importantes para garantir que o banco consiga organizar, filtrar, e fazer cálculos corretamente.

FONTES:https://www.alura.com.br/artigos/banco-de-dados?srsltid=AfmBOoou21aI1XOEb2kZlmzzGkK5Z5n3mzWKdD7CalDePjDvsp6o8nUL


• Tipos numéricos: Armazenam valores inteiros ou decimais. Normalmente servem para representar valores numéricos, como contagens, valores financeiros, medidas e etc.  

<img width="927" height="779" alt="image" src="https://github.com/user-attachments/assets/1dc62045-27a7-4c5d-b044-b75df26a6c83" />

 
Aproximados: Usados para valores que não precisem de precisão exata, como resultados de cálculos científicos
Exemplos: REAL/FLOAT: Números de ponto flutuante
DOUBLE PRECISION: Números de ponto flutuante com maior precisão

FONTES:https://www.w3schools.com/sql/sql_datatypes.asp
https://www.devmedia.com.br/sql-server-comandos-basicos-objetos-tipos-de-dados-e-criacao-de-database/17052


• Tipos de Texto(string): Usado para armazenar qualquer tipo de texto, como nomes, endereços, códigos, descrições, entre outros.
 
 <img width="1124" height="255" alt="image" src="https://github.com/user-attachments/assets/29523704-68c7-413b-a2de-313599c89285" />



FONTES: https://www.rlsystem.com.br/tipos-dados-sql-server
https://www.homehost.com.br/blog/tutoriais/mysql/tipos-de-dados-do-mysql/

• Tipos de Data e Hora: Utilizado para armazenar datas, horários ou ambos

 
 <img width="1919" height="189" alt="image" src="https://github.com/user-attachments/assets/49ae6145-f584-494d-a9cd-4f7f8d024ba4" />



FONTES: https://www.sqlite.org/datatype3.html
              https://learn.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver17





Outros Exemplos de tipos de dados e suas funções:

 
 

FONTES:https://www.rlsystem.com.br/tipos-dados-sql-server https://www.mco2.com.br/artigos/guia-completo-dos-tipos-de-dados-nosql-server.html




<img width="1137" height="135" alt="image" src="https://github.com/user-attachments/assets/4b1a3b06-d12b-4201-952e-dc5ce0365254" />






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


FONTE DE APOIO

Vídeos

Cursos gratuitos de SQL, de um canais conhecidos e com boa relevância.

(Curso em Vídeo) - https://www.youtube.com/watch?v=Ofktsne-utM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r

(Hashtag Programação) - https://www.youtube.com/watch?v=ncgEQBONI_w&list=PLpdAy0tYrnKw_F8v6kkEXTeyE33Navv-K

(edureka!) - https://www.youtube.com/watch?v=q_JsgpiuY98&list=PL9ooVrP1hQOG6DQnOD6ujdCEchaqADfCU

(Minicurso de SQL (Saia do Zero em 1 Hora) - https://www.youtube.com/watch?v=dpanYy8IrcU

Livros

1. "Use a Cabeça! SQL" – Lynn Beighley 
	https://cdn.bookey.app/files/pdf/book/pt/use-a-cabe%C3%A7a-sql-by-beighley.pdf

2. "SQL para Leigos" – Allen G. Taylor
	https://www.casasbahia-imagens.com.br/Control/ArquivoExibir.aspx?IdArquivo=407561154

3. "SQL: Guia de Consulta Rápida" – Alice Zhao
	https://s3.novatec.com.br/sumarios/sumario-9788575228319.pdf
