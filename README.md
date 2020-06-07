# Data Insight Assessment 🔭

## Motivação

Sabemos que fazer testes para pleitiar uma vaga envolve uma medida considerável de esforço. Mais esforço ainda se este é um trabalho que envolve análise e manipulação de dados. Porém, em consideração à natureza remota da vaga e seus problemas técnicos envolvidos, entendemos que uma das melhores formas —e mais justas— de saber quem você é, profissionalmente, seja através de uma amostra de seu trabalho 🤝

Portanto, entendendo que este desafio possa te tomar em *torno de 10h* de dedicação, nos comprometemos a emitir uma avaliação detalhada do trabalho enviado, independentemente da contratação.

## O Desafio

O desafio envolve uma análise de campanhas de marketing --pelo telefone-- de uma instituição bancária Portuguesa. **É um problema de classificação**: se o cliente aceita ou não se inscrever à um produto. O produto é descrito como *bank term deposit*, o que sugere ser algo similar ao nosso débito automático.

### O Objetivo

É importante ressaltar que **não se trata de uma competição**: não queremos o melhor escore do modelo e sim **a melhor análise**. Portanto, o objetivo deste desafio não se trata em escovar os 3% de otimização na performance. E sim, a análise mais clara e objetiva que vai, consequentemente, permitir aos stakeholders entender melhor os dados e quais são os possíveis planos de ação e o porque de cada um deles.

Portanto, em termos claros. O objetivo final deste desafio é:

1. Implementar um modelo de classificação com uma performance aceitável

    1. O aceitável é *explicitamente arbirtrário*. Deve ser aceitável de modo que viabilize uma análise **séria**

1. Elencar e **analisar** quais *features* são determinantes para aderência de um cliente ao produto
1. Descrever um **plano de ação** para futuras campanhas de marketing fundamentado na análise deste conjunto de dados


### Os critérios

O que será avaliado pode ser dividido em duas categorias de capacidades

#### Analíticas: de exploração de dados

1. na exploração uni e multivariada dos dados
1. para correção e transformação de dados (quando for necessário)
1. para encontrar e responder às perguntas certas
1. para decidir quais visualizações devem ser feitas (e quais devem permanecer na análise)
1. para entender o comportamento estatístico das variáveis e seu peso na orientação das análises

#### Problemas: de aprendizado de máquina

1. na definição de quais métricas vão ser usadas para avaliar a performance
1. na apresentação e análise dos resultados obtidos
1. na avaliação do over-underfitting do(s) modelo(s) (e o que pode ser feito para minimizar estes efeitos)
1. no manuseio das features: avaliação de importância, da seleção e criação/transformação


## Insumos

Os insumos são:

1. `data/campaingns.csv`: O conjunto de dados
1. `data/descriptions.txt`: Breve anotação das colunas, em inglês

O conjunto de dados não foi separado em treino e validação. No entanto, separamos uma amostra contendo 1000 linhas aleatórias que foi retirado do conjunto de dados original. Esta amostra é o conjunto de teste e será usado para avaliação das entregas.

**Disclaimer**: Este conjunto de dados está disponível publicamente para pesquisa. Como não se trata de um artigo acadêmico, a citação será feita pela referência sugerida pela política de citação do centro de pesquisa: [Dua, D. and Graff, C. (2019). UCI Machine Learning Repository](http://archive.ics.uci.edu/ml).


### Orientações & regras

1. Qualquer tipo de plágio e/ou cópia de análises e artigos é **veementemente proibido e desclassificatório**
1. O notebook deve ser no formato [`jupyter`](https://jupyter.org/)
1. A linguagem de implementação deve ser `python`, da versão `3.6+`
1. É liberado (e encorajado) o uso de quaisquer framework e bibliotecas publicadas com licenças para uso e redistribuição
    1. `auto-sklearn`, `pandas`, `numpy`, `plotly`, etc
1. A linguagem da análise pode ser tanto em português quanto em inglês


## O que devo fazer para entregar?

Você deve:

1. Fazer um `fork` deste repositório
1. 🔬 Trabajo 🔬
    1. Revise-o
    1. Está feliz com a revisão? `y/N`
        1. `n`: Volte pro 2
        1. `y`: Envie a URL do fork para a `it@t10.digital`

Ficou com dúvida sobre alguma coisa? Mande um e-mail para `zi@t10.digital`








