# Risco de uma Carteira de Investimentos


O mercado financeiro tem diversas possibilidades de ganhos. No entanto, quando não administramos o risco de perda podemos cair em muitas situações indesejadas. Para tentar mitigar o risco de investimentos uma série de ferramentas e técnicas foram desenvolvidas, entre elas, uma das mais clássicas e ainda muito utilizadas é o VaR (Value at Risk). Essa metodologia de avaliação de risco proposta pelo banco JP Morgan em 1994 considera a maior perda esperada que uma carteira de investimentos pode sofrer supondo que seu risco futuro se mantenha parecido com o que foi no passado.

Essa premissa de que o “futuro será parecido com o passado” é forte e nem sempre é real. O autor Nassim Taleb, que ficou conhecido por escrever o Cisne Negro e Antifrágil é um dos mais críticos do VaR. De acordo com ele, essa medida é falha por pressupor que a curva normal representa o mercado, desconsiderando “eventos fora do normal”: os Cines Negros de Nassim (que segundo o autor, são eventos completamente “fora da curva”). Pode-se dizer que a Pandemia de COVID-19 também foi um Cisne Negro.

Apesar disso, essa metodologia segue muito utilizada no mercado financeiro. Vejamos como ela funciona:

Suponha que uma carteira de investimentos (por exemplo, um conjunto de ações compradas na Bolsa de Valores) tenha um VaR de R$ 2.000 reais. Isso significa que existe 5% de probabilidade da carteira ter uma perda (desvalorização) maior que R$ 2.000 reais em um dado horizonte de tempo (geralmente usa-se 180 dias como horizonte de tempo


 

Com isso posto, neste estudo de caso vamos verificar se o VaR pode ser utilizado como modelo estatístico para prever as perdas futuras de ativos reais listados na Bolsa de Valores.



Risco de uma Carteira - Parte 1: Análise exploratória
 Com isso posto, neste estudo de caso vamos verificar se o VaR pode ser utilizado como modelo estatístico para prever as perdas futuras de ativos reais listados na Bolsa de Valores.
Você, como um(a) bom(a) analista de dados, sabe que para verificar a efetividade dessa metodologia, uma série de estudos devem ser realizados. 


Nesta primeira parte do projeto, realize as seguintes etapas abaixo:

Para este estudo de caso, considere uma carteira de ações de 10 empresas que um investidor possui. São elas: Arezzo&Co, B3, Klabin, Localiza, Lojas Americanas, Multiplan, Petrobras, Rede Atacadao, SulAmerica e Vale.


Verifique os seguintes itens a respeito dessa carteira:

1.       Crie um gráfico de linhas com os preços dos ativos da carteira ao longo do tempo. O que é possível notar ? Como as empresas da carteira performaram antes e depois da pandemia? Alguma sofreu muito mais que a outra ou a performance foi parecida (tanto na queda quanto na retomada) ? Considere “antes da pandemia” o preço até Fev/2020 e “depois da pandemia” a partir de Mar/20.


 2.       Qual o risco dos ativos dessa carteira? Em investimentos, o risco de um ativo pode ser interpretado como o desvio padrão de seus retornos. Esse desvio padrão também é chamado de Volatilidade de um ativo. Ordene os ativos em ordem decrescente de risco.


 3.       Esse risco dos ativos permaneceu o mesmo antes e depois da pandemia?


 4.       Uma forma de diminuir o risco de uma carteira de investimentos é ter ativos que sejam pouco correlacionados entre si. Isso porque, quando um ativo perde, o outro ativo pode ganhar ou continuar constante. Se os ativos forem muito correlacionados, perde-se o efeito da “diversificação” (famoso “colocar todos os ovos em uma cesta só“).

 5.   ii.  Isso posto, o que é possível dizer dos ativos da carteira do investidor? Muitos ativos correlacionados? Compare essa correlação dos ativos antes e depois da pandemia.
