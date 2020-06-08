# Data Insight Assessment 🔭

**Pô, mais um teste?**

Devido à natureza remota da vaga e os desafios técnicos envolvidos, entendemos que uma das melhores —e mais justas— formas de saber quem você é, profissionalmente, seja através de uma amostra de seu trabalho 🤝

No entanto, sabemos que fazer testes para pleitear uma vaga envolve uma medida considerável de esforço. Mais esforço ainda se este é um trabalho que envolve análise e manipulação de dados: Estimamos que você possa gastar em torno de 10h para concluir o projeto a fim de cumprir com as expectativas. Portanto, em virtude ao investimento realizado por sua parte, nos comprometemos em emitir uma avaliação detalhada do trabalho enviado, *independentemente do resultado do processo seletivo*.

## O Desafio

O desafio envolve analisar de campanhas de marketing —feitas pelo telefone— de uma instituição bancária. Nas campanhas é vendido ao cliente um produto adicional de débito automático. Queremos saber se um determinado cliente se inscreve ou não ao produto. Portanto, **é um problema de classificação**:

1. ou o cliente se inscreve
1. ou o cliente não se inscreve


### O Objetivo

É importante ressaltar que **não se trata de uma competição** de problemas de *machine learning*: não queremos o melhor escore do modelo e sim **a sua melhor análise**. Portanto, o objetivo deste desafio não se trata em escovar os 3% de otimização na performance. E sim, a análise mais clara e objetiva que vai, consequentemente, permitir aos stakeholders entender melhor os dados e quais são os possíveis planos de ação e suas respectivas argumentações.

Portanto, em termos claros. Os objetivos —e entregáveis— deste desafio podem ser dividos em duas categorias:

1. Code:
    1. Implementar um modelo de classificação com uma performance aceitável

        1. O aceitável é *explicitamente arbitrário*. Aceitável de modo que viabilize uma análise *estatisticamente fundamentada*
    1. Conjunto de dados contendo a coluna da previsão, `y'`

1. Insight:
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

O que você precisa para realizar as análises:

1. `data/campaigns.csv`: O conjunto de dados
1. `data/campaigns-names.txt`: Breve anotação das colunas, em *inglês*

O conjunto de dados não foi separado em treino e validação. No entanto, foi separada uma amostra aleatória com 10% do volume total dos dados. Esta amostra é o conjunto de teste e será usado para avaliação das entregas.

**Disclaimer**: Este conjunto de dados está disponível publicamente para pesquisa. Como não se trata de um artigo acadêmico, a citação será feita pela referência sugerida pela política de citação do centro de pesquisa: [Dua, D. and Graff, C. (2019). UCI Machine Learning Repository](http://archive.ics.uci.edu/ml).


### Regras

1. Qualquer tipo de plágio e/ou cópia de análises e artigos é **veementemente proibido e desclassificatório**
1. O notebook deve ser no formato [`jupyter`](https://jupyter.org/)
1. A linguagem de implementação deve ser `python`, da versão `3.6+`
1. É liberado (e encorajado) o uso de quaisquer framework e bibliotecas publicadas com licenças para uso e redistribuição
    1. `auto-sklearn`, `pandas`, `numpy`, `plotly`, etc
1. A linguagem da análise pode ser tanto em português quanto em inglês


## O que devo fazer para entregar?

Temos um *checklist* pra isso:

- [ ] Fazer um `fork` deste repositório
- [ ] Prepare um café
- [ ] 🔬 *Trabajo* 🔬
- [ ] Certifique que o *trabajo* realizado cumpre [os requisitos](#o-objetivo) e segue [às orientações](#regras)
- [ ] Revise-o
- [ ] Esteja satisfeit@ com a revisão
- [ ] Abra um PR para este repositório e notifique a Zi

🤘 É isto. Boa sorte 🤘

----

Ficou com dúvida sobre alguma coisa? Mande um e-mail para `zi@t10.digital`