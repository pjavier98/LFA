# Linguagens Regulares:
Definida por um **formalismo reconhecedor.**

**Formalismo reconhecedor:** AFD.

M = {Σ, Q, σ, qº, F} -> (Automatos Finitos Deterministicos) 
* Σ -> definir linguagem.
* Q -> conjunto de estados.
* σ -> definir a funcao.
* qº -> estado inicial.
* F -> conjunto de estados finais.

L = {w / w ∈ {a, b}* tal que w possui "aa" como subpalavra} ("aa" -> juntas)
L = {aa, aab, baa, bbaa, aaa, baab, ...}
```
       s
qº --------> q'

grafo onde ler um simbolo s faz o estado q != q', o estado muda.
```
```
                                            ------
     ----        a       ----       b       |----|
     |qº| -------------> |q1| ------------> ||qf|| 
     ----                ----               |----|
                                            ------
(estado inicial)                         (estado final)

σ(qº, a) = q1
σ(q1, a) = qf
```

### Automato que o davi vai fazer

01/08/2018