<div align="center">
    <h1>Venda de Biciletas Dashboard </h1>
    
  <img src="https://github.com/marcos-anjos/Bike-Sales-Dashboard/assets/160321440/746c608d-0f86-4bbe-b855-3c95ebf57be3" />

  <div align="center">
        <a href="#"><img alt="Excel" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"></a>
    </div>

<h3>Dashboard interativo</h3>

  <p>O projeto consiste em uma análise exploratória dos dados nutricionais do menu do McDonald's, utilizando técnicas de limpeza, visualização e análise de dados.</p>
  
</div>

## <a name="table">Súmario</a>

1. [Introdução](#introdução)
2. [Ferramentas Utilizadas](#Ferramentas)
3. [Sobre o Dataset](#Dataset)
4. [Observações](#Observações)

## <a name="introdução">Introdução</a>

<body>
    <p style="text-align: justify;">
       Este dashboard oferece informações demográficas e de 
                                comportamento de clientes em um contexto de marketing. Esses dados 
                                podem ser utilizados para análise de mercado, segmentação de clientes, 
                                previsão de comportamento de compra e outras análises relevantes para estratégias  
                                de marketing e tomada de decisão empresarial.
    </p>
</body>

## <a name="Ferramentas">Bibliotecas e Ferramentas Utilizadas</a>

- **Pandas**: Para manipulação e análise dos dados.
- **Matplotlib e Seaborn**: Para visualização de dados.
- **Python**: Linguagem de programação utilizada para desenvolver o código.
- **Jupyter Notebook**: Ambiente de desenvolvimento utilizado para executar o código e documentar o processo de análise.
   

## <a name="Dataset">Sobre o Dataset</a>

Este conjunto de dados fornece os factos nutricionais de cada item do menu do McDonald's indiano. Eles possuem 141 entradas e 13 colunas, sendo 10 do tipo numérico e 3 do tipo categórico. Algumas das colunas incluem:

Fonte: [Kaggle | Menu Nutrition Dataset](https://www.kaggle.com/datasets/deepcontractor/mcdonalds-india-menu-nutrition-facts)

- `Categoria do menu`: A categoria a que pertence o item de menu específico.
- **`Itens do menu`**: A lista de todos os itens servidos
- **`Tamanho por dose`**: A quantidade (em g ou ml) de um determinado item de menu servido.
- **`Energia (kCal)`**: A quantidade de energia (kCal) por porção
- **`Proteína (g)`**: A quantidade de proteína (g) por porção
- **`Gordura total (g)`**: A quantidade de gordura total (g) por porção
- **`Gordura saturada (g)`**: A quantidade de gordura saturada (g) por porção
- **`Gorduras trans (g)`**: A quantidade de gordura trans (g) por porção
- **`Colesteróis (mg)`**: A quantidade de colestrol (mg) por porção
- **`Carboidratos (g)`**: A quantidade de hidratos de carbono (g) por porção
- **`Açúcares totais (g)`**: A quantidade de Açúcares totais (g) por porção
- **`Açúcares adicionados (g)`**: A quantidade de Açúcares adicionados (g) por porção
- **`Sódio (mg)`**: A quantidade de Sódio (mg) por porção

Limitações:

- **Qualidade dos dados**:
A qualidade dos dados pode variar, com possíveis erros de gravação, valores ausentes ou inconsistentes, o que pode afetar a precisão das análises.
- **Limitações de escopo**:
O projeto pode não abranger todas as dimensões relevantes da nutrição, deixando de fora aspectos importantes que poderiam influenciar as conclusões.
- **Interpretação dos resultados**: Os resultados da análise exploratória podem fornecer insights, mas a interpretação dos resultados deve levar em consideração outras variáveis e contextos que não estão necessariamente refletidos nos dados.


## <a name="Observações">Observações</a>
Algumas das observações feitas foram:
- **Variedade de Itens por Categoria de Menu**: Observamos uma variação significativa no número de itens em cada categoria de menu, o que pode refletir a diversidade de opções oferecidas pela cadeia de fast food em diferentes segmentos de mercado.
- **Perfil Nutricional dos Itens Mais Energéticos**: Os cinco itens com maior quantidade de energia (kCal) geralmente apresentam um perfil nutricional mais rico em gorduras e carboidratos, o que pode indicar uma escolha popular para clientes que buscam refeições mais substanciais.
- **Relação entre Energia e Proteína**: Notamos uma correlação positiva entre o teor de energia (kCal) e o teor de proteína (g) nos itens do menu, sugerindo que itens com maior teor de energia também tendem a ter maior quantidade de proteína.
- **Relações entre Nutrientes Específicos**: Identificamos relações importantes entre certos nutrientes, como a associação entre a quantidade de gordura saturada e o colesterol, que podem ser relevantes para indivíduos que buscam monitorar sua ingestão desses componentes.
  
Essas observações fornecem uma visão da composição nutricional dos itens de menu da cadeia de fast food em estudo, destacando padrões e insights importantes que podem orientar escolhas alimentares informadas pelos consumidores.

