# p2
1.
    a.
        terminais:
            - (
            - ,
            - )
            - a
        nao terminais:
            - L
            - S
        simbolo de partida:
            - L

    b. -

    c. -

    d. -

    e.
        
        grammar g
        main : L EOF;
        S : "(" L ")" | "a";
        L : L "," S | S;


2.
    a. -
    b. -
    c. -
    d. qualquer conjunto de "a"s e "b"s que tenha igual numero de "a"s e "b"s

3.
    a. -

    b. -

    c. -

    d. -

    e. (a que vem primeiro tem prioridade)

    f. -



# p3
1.
    a.
        original:
            S -> (L) | a
            L -> L,S | S
        updated:
            S -> (L) | a
            L -> SL'
            L' -> ,SL' | (empty)

    b. -

    c.
        grammar g
        main : S EOF;
        S : "(" L ")" | "a"
        L : S Li | S
        Li : "," S


# p5
1.
    a.
        original:
            S -> (L) | a
            L -> L,S | S
        sem recursividade (esquerda):
            S -> (L) | a
            L -> SL'
            L' -> ,SL' | (empty)
        fatorizada (esquerda):
            (ja esta)

    b. -

    c. -

    d. -


2.

    a. -

    b. -

    c. -

    d. -
