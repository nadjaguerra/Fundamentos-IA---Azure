## Desafio: Trabalhando com Machine Learning na Prática no Azure ML

1 - Crie um novo repositório no github com um nome a sua preferência

2 - Crie um modelo de previsão com seus devidos pontos de extremidade configurados

3 - Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa

4 - Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade

5 - Compartilhe conosco o link desse repositório através do botão 'entregar projeto'


### Aprendizado de máquina automatizado para treinar um modelo
O objetivo é usar um conjunto de dados de detalhes históricos de aluguel de bicicletas, os dados derivados da Capital Bikeshare, para treinar um modelo que prevê o número de aluguel de bicicletas esperado em um determinado dia, com base em características sazonais e meteorológicas.

1 - Criar um workspace no Azure Machine Learning 

![Captura de Tela (242)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/86d585b5-2ce3-4ae2-acaa-04c72094fd88)

2 - No Azure Machine Learning Studio, crie um novo workspace de ML automatizado e configure de acordo com a documentação. 
Além disso, informe o tipo de task que será usada, nesse caso a Regressão. 
Confugure de onde virá a database usada, nesse caso: 
#### Web URL: https://aka.ms/bike-rentals

![Captura de Tela (243)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/286eb5e9-b01a-4110-b625-38b7bd967fb4)

3 - Após toda a configuração, envie o workspace de treinamento. Ele inicia automaticamente.

![Captura de Tela (244)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/0327e616-a69b-47ed-90d1-19b423f783db)

4 - Crie e configure um modelo para que possa ser testado

![Captura de Tela (245)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/ca91ccf8-15c1-4b59-aef9-46b75918e471)

5 - Selecione os pontos de extremidade, implemente o modelo criado e teste

![Captura de Tela (246)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/914b0db6-609f-40da-ac52-f747b9028a76)

6 - Validação de Métricas

![Captura de Tela (247)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/96836094-a374-4edf-909b-0b6bcf931a78)

![Captura de Tela (248)](https://github.com/nadjaguerra/Microsoft-Azure-AI-Fundamentals/assets/112482228/4e857e28-44f3-4370-9276-d7c011ad51d4)

