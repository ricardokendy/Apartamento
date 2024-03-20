# Apartamento

Os dados deste projeto é composto por informações de uma imobiliária que atua na região oeste da Europa, mais precisamente da região da Espanha e Portugal.

Premissas: Ao analisar os dados, deve-se ter em mente que existem algumas premissas de negócios que devem ser consideradas. A primeira delas é um erro de digitação da área do imóvel, alguns imóveis possuem áreas acima dos valores que aparecem com mais frequência (outliers). Para solucionar este problema, foi decidido remover os imovéis cuja a área estão acima de 100m².

Métricas: Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

- Aluguel deve ser abaixo de 4000€: O cliente decidiu que o valor aluguel não pode ser acima de 4000€. Analisando o valor total do aluguel, podemos filtrar os imóveis que possuem o aluguel abaixo do valor estipulado pelo cliente.
- Deve aceitar animais: Analisando os dados de aceitação de animais, podemos filtrar os imóveis que aceitam a presença de animais.
- Deve ter 2 ou 3 quartos: Analisando a quantidade de quartos, podemos identificar os imóveis que possuem 2 e 3 quartos.
- Andar do imóvel: Analisando os valores dos aluguéis por andar onde encontro o imóvel, foi decidido o apartamento no andar mais alto respeitando todas as outras métricas.

