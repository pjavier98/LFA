# Conceitos principais:
* Linguagem: Conjunto de palavras de determinado alfabeto.
* Automato: maquina de estado finito definido de forma a reconhecer a linguagem.
* AFD: Automato Finito Deterministico.
    - Composto por 3 elementos:
        * Fita(Σ).
        * Unidade de Controle(UC).
        * Funcao Programa(σ).
    - Funcao Programa: da ordem a unidade de controle, 
        pega o estado x palavras(simbolos) que esta lendo e me da um novo estado.
        * σ: Q x E -> Q (Q -> estados, E -> palavras)
        * σ(qº, a) = q' (qº -> estado inicial, q' -> conjunto de estados finais) 
        * Teremos um conjunto de estados finais.
    - Unidade de Controle: ler cada simbolo ate que nao houver mais nada para ler.
* AFND: Automato Finito Nao Deterministico.
* Condicao de parada final: ler a palavra toda e chegar no estado final.