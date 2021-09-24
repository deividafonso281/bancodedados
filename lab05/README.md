# Aluno 
 * 261032: David Afonso Borges dos Santos
## Tarefa de Cypher sobre Marcadores e Taxonomia
## Tarefa 1
Escreva em Cypher uma consulta que retorne os marcadores da categoria Serviços, sem considerar as categorias subordinadas.

## Resolução

MATCH (m:Marcador)-[:Pertence]-(c:Categoria)
WHERE c.id = "Serviços" 
RETURN m

## Tarefa 2
Escreva em Cypher uma consulta que retorne os marcadores da categoria Serviços, considerando as categorias subordinadas.

## Resolução

MATCH (m:Marcador)-[:Pertence]->(c:Categoria)-[:Superior*]->(d:Categoria)
MATCH (n:Marcador)-[:Pertence]-(d)
WHERE d.id = "Serviços" 
RETURN m, n 
