# Sleep Health and Digital Screen Exposure Dataset

📌 Contexto

Entender a relação entre qualidade do sono, níveis de estresse e exposição à tela digital é crucial para analisar os impactos do estilo de vida moderno na saúde. Este conjunto de dados fornece insights detalhados sobre vários fatores que afetam o sono e a saúde ocular, incluindo duração do sono, estresse, atividade física, histórico médico e uso de dispositivos digitais antes de dormir.

📂 Descrição do Dataset

O conjunto de dados contém diversas informações sobre os indivíduos, incluindo hábitos de sono, saúde geral e uso de dispositivos digitais. A seguir, uma descrição das colunas:

📝 Variáveis

- Gênero: Gênero do indivíduo (M/F)

- Idade: Idade do indivíduo (em anos)

- Duração do Sono: Duração média do sono (em horas)

- Qualidade do Sono: Qualidade do sono autorrelatada (Escala: 1 - Pobre a 5 - Excelente)

- Nível de Estresse: Nível de estresse (Escala: 1 - Baixo a 5 - Alto)

- Pressão Sanguínea: Pressão arterial registrada (sistólica/diastólica em mmHg)

- Frequência Cardíaca: Frequência cardíaca em repouso (em bpm)

- Passos Diários: Média de passos diários dados

- Atividade Física: Nível de atividade física (medida quantificada)

- Altura: Altura do indivíduo (em cm)

- Peso: Peso do indivíduo (em kg)

- Distúrbio do Sono: Se o indivíduo tem distúrbio do sono (S/N)

- Acordar Durante a Noite: Se o indivíduo acorda durante a noite (S/N)

- Sentir Sono Durante o Dia: Se o indivíduo sente sono durante o dia (S/N)

- Consumo de Cafeína: Se o indivíduo consome cafeína (S/N)

- Consumo de Álcool: Se o indivíduo consome álcool (S/N)

- Fumante: Se o indivíduo é fumante (S/N)

- Problema Médico: Quaisquer condições médicas existentes (S/N)

- Medicação em Andamento: Se o indivíduo está tomando medicação (S/N)

- Dispositivo Inteligente Antes de Dormir: Uso de dispositivos digitais antes de dormir (S/N)

- Tempo Médio de Tela: Tempo médio diário de tela (em horas)

- Filtro de Luz Azul: Se o indivíduo usa um filtro de luz azul (S/N)

- Cansaço Visual: Experiência de desconforto ou cansaço ocular (S/N)

- Vermelhidão nos Olhos: Experiência de vermelhidão ocular (S/N)

- Irritação nos Olhos: Experiência de coceira ou irritação ocular (S/N)

- Doença do Olho Seco: Diagnóstico ou sintomas da doença do olho seco (S/N)

⚙️ Processamento de Dados

As seguintes etapas foram aplicadas ao conjunto de dados:

1. Carregamento dos dados: Leitura do arquivo CSV usando pandas.

2. Renomeação das colunas: Tradução dos nomes das colunas para português.

3. Conversão de valores binários: Substituição de "Y" por "S" para facilitar a interpretação dos dados.

4. Separação da Pressão Sanguínea: Criação das colunas 'Sistólica' e 'Diastólica'.

5. Conversão para valores numéricos: Tratamento de possíveis erros na conversão.

6. Cálculo da Média da Pressão: Criação de uma nova coluna Média Pressão.


📊 Análises e Visualizações

Utilizamos as bibliotecas pandas, numpy, matplotlib e seaborn para explorar o conjunto de dados. Algumas análises incluem:

- Distribuição da qualidade do sono e níveis de estresse.

- Relação entre tempo de tela e qualidade do sono.

- Impacto do uso de dispositivos digitais na saúde ocular.

- Correlação entre atividade física e qualidade do sono.
