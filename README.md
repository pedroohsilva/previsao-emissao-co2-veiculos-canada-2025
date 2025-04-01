# Previsão de Emissões de CO₂ em Veículos no Canadá 2025
Neste projeto, utilizo um modelo de Regressão Linear para estimar as emissões de dióxido de carbono (CO₂) de veículos canadenses com base em suas características técnicas com dados reais.

### Objetivos:
Fornecer insights úteis para análises ambientais
Usar o Scikit-learn para implementar uma regressão linear múltipla
Criar, testar e implementar um modelo de regressão linear com dados reais

- **Fonte:** https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

---

### Entendendo os Dados:
​O conjunto de dados "Classificações de Consumo de Combustível de 2025" fornece informações detalhadas sobre o consumo de combustível de veículos no Canadá para o ano-modelo 2025. Os dados foram atualizados pela última vez em 25 de março de 2025 e estão disponíveis no Portal de Dados Abertos do Canadá.

- Ano do Modelo (Model year): Ano de fabricação do veículo.​

- Marca (Make): Fabricante do veículo.​

- Modelo (Model): Nome específico do modelo do veículo.​

- Classe do Veículo (Vehicle class): Categoria à qual o veículo pertence, como compacto, SUV, etc.​

- Tamanho do Motor (Engine size (L)): Capacidade volumétrica do motor em litros.​

- Número de Cilindros (Cylinders): Quantidade de cilindros no motor.​

- Transmissão (Transmission): Tipo de transmissão do veículo (por exemplo, automática ou manual).​

- Tipo de Combustível (Fuel type): Tipo de combustível utilizado pelo veículo (por exemplo, gasolina, diesel).​

- Consumo na Cidade (City (L/100 km)): Consumo de combustível em ambiente urbano, medido em litros por 100 quilômetros.​

- Consumo na Estrada (Highway (L/100 km)): Consumo de combustível em rodovias, medido em litros por 100 quilômetros.​

- Consumo Combinado (Combined (L/100 km)): Média ponderada do consumo de combustível na cidade e na estrada, em litros por 100 quilômetros.​

- Consumo Combinado em MPG (Combined (mpg)): Consumo combinado convertido para milhas por galão.​

- Emissões de CO₂ (CO2 emissions (g/km)): Quantidade de dióxido de carbono emitida pelo veículo, medida em gramas por quilômetro.​

- Classificação de CO₂ (CO2 rating): Avaliação da eficiência do veículo em termos de emissões de CO₂.​

- Classificação de Poluentes (Smog rating): Avaliação do impacto do veículo na formação de smog.​

Essas informações são essenciais para consumidores, pesquisadores e formuladores de políticas que buscam compreender e comparar a eficiência energética e o impacto ambiental dos veículos disponíveis no mercado canadense.
