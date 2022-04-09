# ML: Credit Scoring 

O Credit Scoring é um modelo estatístico multivariado que cria um modelo matemático e estima, através de uma probabilidade, a chance do nosso cliente ser adimplente ou inadimplente.

## Contexto

A base de dados faz parte de um curso de Machine Learning Credit Scoring proposto pela Alura, onde é analisado e feito um modelo de ML para prever a convessão de crédito usando regressão logística.

Mas por que usar a regressão logística? Ela é uma técnica muito usada no sistema financeiro e existem alguns motivos para isso. O primeiro deles é que ela tem um alto comprometimento com a explicabilidade.


## 1. Pilares da cadeia de crédito.

### A cadeia de crédito é composta por 4 pilares:

1. Prospecção
2. Concessão
3. Gestão de risco
4. Recuperação

Nesta analise será focada no pilar de  concessão de crédito.
Além disso, a cadeia de crédito conta com três principais participantes: os poupadores, que são aquelas pessoas que reservam parte do seu dinheiro para ser investido; os tomadores, que são aquelas pessoas que estão em busca de um crédito ou de um financiamento no mercado; e quem intermedia essa relação é a instituição financeira.

Mas como isso funciona? Os poupadores levam o seu dinheiro para ser investido para os bancos e os bancos também têm um valor disponível para que os tomadores busquem o crédito que eles precisam.

Mas é uma relação bilateral. Da mesma forma que os poupadores levam o seu dinheiro até o banco para receber um rendimento sobre o investimento, é o banco que define qual será o rendimento e quais são as condições daquela aplicação.

Da mesma forma, os tomadores vão até os bancos e solicitam o seu crédito, mas é o banco que decide se aquele crédito será concedido ou não e quais serão as condições dessa concessão. Eu tenho certeza que você já passou por um pedido de crédito. Caso você não tenha passado, você conhece alguém que passou por essa solicitação.

O tomador, ele vai até o banco, até a instituição financeira, e a instituição financeira avalia, a partir de dados cadastrais e financeiros e outras variáveis, se aquele pedido será concedido ou não através de um modelo de decisão.

É neste modelo que o banco vai dizer se o crédito será aprovado ou negado. A aprovação ou a negação daquela solicitação faz parte da decisão da instituição financeira. Independente se o crédito for aprovado ou negado, a instituição dá a devolutiva para o tomador.

O Crediting Score, ele busca estimar a probabilidade de um evento acontecer frente a uma base de dados. Nós estamos falando de uma probabilidade, então o valor está concentrado entre 0 e 1, e existem diversas aplicações.

Pensando na concessão de crédito, o evento que nós estamos buscando é se um tomador vai ser inadimplente, por isso nós queremos classificar os nossos solicitantes em adimplentes ou inadimplentes, é um evento binário. Toda concessão de crédito está intrinsecamente relacionada ao risco. Nós não conseguimos dissociar isso, toda operação de crédito está relacionada a um risco, têm um risco acoplado ali. Nós podemos entender o risco de crédito como a probabilidade de receber um montante de dinheiro em um determinado período não acontecer, ou seja, a expectativa da instituição financeira de receber o seu dinheiro de um determinado valor em um determinado prazo, não vai acontecer.



