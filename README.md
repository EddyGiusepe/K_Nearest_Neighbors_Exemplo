# K Nearest Neighbors

Aqui apresentamos um exemplo simples da aplicação de KNN.

Também apresentamos quando padronizar ou normalizar nossos Dados. 


Aqui vamos fazer um resumo sobre ``Normalizar`` ou ``Padronizar``. 

Mas quando devemos escolher entre normalization, standardization e porque?

A transformação dos seus dados, que já estão tratados, é uma pratica para evitar que seu algoritmo fique enviesado para as variáveis com maior ordem de grandeza.

\\

As duas técnicas tem o mesmo objetivo:

transformar todas as variáveis na mesma ordem de grandeza. E a diferença básica é que ``padronizar`` as variáveis irá resultar em uma média igual a $0$ e um desvio padrão igual a $1$. Já ``normalizar`` tem como objetivo colocar as variáveis dentro do intervalo de $0$ e $1$, caso tenha resultado negativo $-1$ e $1$.

* **Padronizar** os dados normalmente é feita usando a fórmula z-score: $~~~~$ $z = \frac{x ~~-~~ \mu}{\sigma}$

* **Normalizar** os dados usando Min-Max: $~~~~$ $x_{changed} = \frac{x ~~-~~ x_{min}}{x_{max} ~~-~~ x_{min}}$



Thanks God!
