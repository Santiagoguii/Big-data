# **SINAN**

A escolha do dataset sobre dengue do Sistema de Informação de Agravos de Notificação (SINAN) para o ano de 2023 é relevante por várias razões:

**Importância da Saúde Pública:** A dengue é uma doença viral transmitida por mosquitos e representa um grande desafio de saúde pública, especialmente aqui no Brasil. Monitorar e analisar os casos de dengue são essencias para entender a epidemologia e elaborar estratégias de prevenção e controle.

**Disponibilidade de Dados Abertos:** O SINAN oferece dados abertos sobre casos de dengue notificados ao sistema de saúde, possibilitando análises epidemiológicas e estudos de saúde pública.

**Análise Epidemiológica:** O dataset oferece dados detalhados sobre casos de dengue, incluindo informações como data de notificação, localização geográfica, características demográficas dos pacientes, tipo de dengue e evolução do caso. Isso permite análises epidemiológicas para compreender padrões de incidência, identificar áreas de alto risco e avaliar as intervenções de saúde pública.

**Prevenção e Controle:** Através de dados, pode-se saber áreas e populações mais afetadas pela dengue, direcionando recursos para programas de prevenção e controle, como campanhas e medidas de controle.

**Pesquisa Científica:** O dataset serve de base para estudos acadêmicos e pesquisas sobre dengue, incluindo modelagem epidemiológica, análise de fatores de risco, avaliação de intervenções de saúde e elaboração de novas estratégias de controle de doença.

### Dicionário de Dados

| Nome do Campo | Tipo de Dado | Descrição | Observações |
| ------------- | ------------ | --------- | ----------- |
| **ID_MUNICIP** | String | Identificador do município da notificação. | Representa o município onde a notificação foi feita. |
| **ID_REGIONA** | String | Identificador da região da notificação. | Pode representar uma divisão administrativa regional. |
| **ID_UNIDADE** | String | Identificador da unidade de saúde. | Pode representar o local onde a notificação foi registrada. |
| **DT_SIN_PRI** | String | Data do início dos sintomas. | Indica quando os sintomas começaram a se manifestar. |
| **EVIDENCIA** | String | Indicador de evidência da doença. | Pode indicar se há evidências clínicas ou laboratoriais da doença. |
| **PLAQ_MENOR** | String | Contagem de plaquetas menor. | Representa a contagem de plaquetas mínima no paciente. |
| **CON_FHD** | String | Condição de febre hemorrágica. | Indica se o paciente apresenta condições relacionadas à febre hemorrágica. |
| **COMPLICA** | String | Indicador de complicações. | Pode indicar se houve complicações no quadro clínico do paciente. |
| **TP_SISTEMA** | String | Tipo de sistema. | Pode indicar o tipo de sistema de saúde ou de notificação utilizado. |
| **NDUPLIC_N** | String | Número de duplicatas na notificação. | Indica o número de notificações duplicadas. |
| **DT_DIGITA** | String | Data de digitação da notificação. | Indica quando a notificação foi digitada no sistema. |
| **CS_FLXRET** | String | Código de fluxo de retorno. | Pode indicar o status do fluxo de retorno da notificação. |
| **FLXRECEBI** | String | Indicador de fluxo recebido. | Pode indicar se o fluxo foi recebido ou não. |
| **MIGRADO_W** | String | Indicador de migração. | Pode indicar se os dados foram migrados de outro sistema ou fonte. |

### Lista dos estados

| Código | Estado                |
|--------|-----------------------|
| 11     | Rondônia              |
| 12     | Acre                  |
| 13     | Amazonas              |
| 14     | Roraima               |
| 15     | Pará                  |
| 16     | Amapá                 |
| 17     | Tocantins             |
| 21     | Maranhão              |
| 22     | Piauí                 |
| 23     | Ceará                 |
| 24     | Rio Grande do Norte   |
| 25     | Paraíba               |
| 26     | Pernambuco            |
| 27     | Alagoas               |
| 28     | Sergipe               |
| 29     | Bahia                 |
| 31     | Minas Gerais          |
| 32     | Espírito Santo        |
| 33     | Rio de Janeiro        |
| 35     | São Paulo             |
| 41     | Paraná                |
| 42     | Santa Catarina        |
| 43     | Rio Grande do Sul     |
| 50     | Mato Grosso do Sul    |
| 51     | Mato Grosso           |
| 52     | Goiás                 |
| 53     | Distrito Federal      |

# PySpark

Na última etapa do projeto, foram realizadas diversas atividades importantes utilizando o PySpark para explorar e manipular dados armazenados em formato Parquet. Aqui está um resumo completo do que foi feito:

#### Configuração do Ambiente e Importação de Bibliotecas:

Foi configurado um ambiente Python com as bibliotecas necessárias, incluindo pyspark e findspark.
Importações foram feitas para SparkSession e outras classes específicas do PySpark.

#### Inicialização do SparkSession:

Criou-se uma instância de SparkSession para interagir com o Spark. Isso incluiu configurações como nome da aplicação, número de cores a serem usados, e quantidade de memória alocada.

#### Carregamento dos Dados:

Os dados foram carregados a partir de um arquivo Parquet utilizando o método spark.read.parquet().
Verificou-se o esquema dos dados utilizando printSchema() para entender a estrutura das colunas e seus tipos.

#### Exploração Inicial dos Dados:

Utilizou-se show() para exibir as primeiras linhas do DataFrame e verificar como os dados estão estruturados.
Isso ajudou a garantir que os dados foram carregados corretamente e entender sua organização inicial.

#### conclusão da etapa final 

Essa etapa foi crucial para garantir que os dados foram carregados corretamente no ambiente do PySpark e para entender sua estrutura inicial. As análises exploratórias realizadas forneceram insights iniciais importantes que serão usados para direcionar as próximas fases do projeto, como modelagem de dados e podendo permitir futuramente a construção de pipelines de processamento, ou criação de modelos preditivos, dependendo dos objetivos específicos do projeto.



# **Dicentes**

* Débora de Freitas 
* Guilherme Santiago
* Juan Henrique 
* Mateus caik 
* Micaelle silva



