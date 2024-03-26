Introdução
Neste projeto, relizou-se uma análise minuciosa da base de dados da bolsa de valores, 
utilizando o Google Sheets e explorando uma variedade de ferramentas, como VLOOKUP, SUMIF, 
entre outras fórmulas, com o objetivo de extrair insights valiosos.

Análise Exploratória
A análise exploratória é uma etapa fundamental em qualquer projeto de análise de dados.
Envolve a extração de informações da base de dados, compreensão de sua estrutura e características, 
identificação de padrões, tendências, anomalias e relações entre variáveis. Essa análise prévia é 
crucial para embasar decisões futuras e garantir a eficácia das análises mais avançadas.

Dataset
O termo "dataset", ou conjunto de dados, refere-se ao banco de dados utilizado neste projeto.
É o local onde as informações são armazenadas de forma estruturada, permitindo sua organização,
recuperação, modificação e consulta de maneira eficiente.

Planilha 1: Contém informações como Ativo (ticker), Data, Último (R$), Var. Dia (%), Var. Sem. (%),
Var. Mês (%), Var. Ano (%), Var. 12M (%), Val. Mín, Val. Máx e Volume.
Planilha 2: Inclui dados como Código e Qtde. Teórica.
Planilha 3: Apresenta informações como Ticker e Nome.

Chave de Pesquisa
A chave de pesquisa é um valor ou conjunto de valores que são utilizados para localizar informações
específicas dentro de um conjunto de dados. Geralmente, essa chave é empregada para consultar ou 
recuperar registros específicos em um banco de dados, facilitando a análise e a obtenção de resultados precisos.

Atividades Realizadas
Como base de dados uma tabela contendo informações sobre ações de diversos ativos da bolsa de valores. 
Durante o projeto, executou-se as seguintes atividades:

1- Conversão dos valores decimais para porcentagens.
2- Cálculo do valor inicial de cada ação.
3- Determinação da quantidade de ações em um único dia para cada ativo.
4- Cálculo das variações em reais para cada ativo em um único dia.
5- Criação de categorias, incluindo nome da empresa, segmento e idade para cada ativo.
Observação: A idade em anos foi calculada levando em consideração o ano atual (2024) e o ano de 
fundação de cada empresa, quando disponível. Quando o ano de fundação não estava disponível, 
utilizou-se uma estimativa aproximada.