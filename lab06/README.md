# Aluno 
 * 261032: David Afonso Borges dos Santos
# Análise do Artigo BovDB: A data set of stock quotes for Machine Learning on all companies from B3 between 1995 and 2020

| campo | valor |
|------------|-----------------|
| referência | "Cardoso, F., Malska, J., Ramiro, P., Lucca, G., Borges, E. N., Mattos, V. d., and Berri, R. (2021). Bovdb: The data set of stock quotes for machine learning on all companies from b3 between 1995 and 2020. In Brazilian Symposium on Databases - Dataset Showcase". |
| link       | [PDF do artigo](https://drive.google.com/file/d/1-x_TZMxAeGzfHS7Oq-h5cc1uj1zkWdHy/view) |
| dataset | [Link para o Dataset](https://github.com/Ginfofinance/BovDBrepository) |
| formato | SQL                                                                    |

## Resumo

O artigo descreve o processo realizado para se construir um banco de dados com informações a respeito das ações negociadas na bolsa de valores brasileira (B3) entre os anos de 1995 e 2020. Dentre os tópicos discutidos no artigo estão as fontes das quais os dados foram retirados, e como estes dados foram tratados antes de serem inseridos no dataset uma vez que algumas das fontes se mostravam corrompidas e outras necessitavam de ajuste nos preços das ações negociadas. O artigo também discorre sobre o modelo como os dados foram organizados e a estrutura e o nome das tabelas criadas para armazenar tanto preços (máximo, mínimo, abertura, fechamento) quanto nome das empresas, sigla das ações das respectivas empresas e informações a respeito de eventos que ocorreram em determinadas ações.São realizadas algumas análises sobre os dados, dentre elas sobre o número de ações negociadas na bolsa brasileira ao longo dos anos. Por fim é apresentado o repositório onde o banco está disponível para download.

## Perguntas de pesquisa/análises

O dataset, ao disponibilizar os preços das ações negociadas ao longo dos anos, possibilita que tais dados sejam utilizados para realizar sugestões a respeito da compra ou venda de ações, por meio de aprendizado de máquina, por exemplo. Também são possíveis análises dos preços das ações em determinado período para observar como determinados acontecimentos históricos os influenciaram.

## Trabalhos relacionados 

Dentre os trabalhos relacionados mencionados temos Efimov et al. 2020 e Guo et al. 2018. O primeiro realizou estudos riscos usando bancos de dados da American Express e o segundo utilizou um banco de dados da Shanghai Stock Exchange e aprendizado de máquina para analizar negociações diárias. Os trabalhos se relacionam em função do tema (compra e venda de ações de empresas) e em função do uso de um volume muito grande de dados (várias negociações distribuídas em um período muito longo de tempo).
