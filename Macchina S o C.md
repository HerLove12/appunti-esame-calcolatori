# Testo:
![[s.png]]
![[testo.png]]

# Punto I)

#### Formule algebriche:
$D_{1,0} = Q'$ ,    $T_2=\ \neg(Q2+Q1+Q0)+Q2Q1+Q2Q0$ 

- $Q_2'=\neg T_2Q_2 + T_2\neg Q_2 = \neg Q_1 \neg Q_0$
- $Q_1'=\neg(Q_1\oplus Q_0)$
- $Q_0'= \neg Q_0$

#### Tabella di verità:

| n   | $Q_2$ | $Q_1$ | $Q_0$ | $T_2$ | $Q_2'=T_2\oplus Q_2$ | $Q_1'$ | $Q_0'$ | $Z=Q_2\neg Q_1 + \neg Q_0$ |
| --- | ----- | ----- | ----- | ----- | -------------------- | ------ | ------ | -------------------------- |
| 0   | 0     | 0     | 0     | 1     | 1                    | 1      | 1      | 1                          |
| 1   | 0     | 0     | 1     | 0     | 0                    | 0      | 0      | 0                          |
| 2   | 0     | 1     | 0     | 0     | 0                    | 0      | 1      | 1                          |
| 3   | 0     | 1     | 1     | 0     | 0                    | 1      | 0      | 0                          |
| 4   | 1     | 0     | 0     | 0     | 1                    | 1      | 1      | 1                          |
| 5   | 1     | 0     | 1     | 1     | 0                    | 0      | 0      | 1                          |
| 6   | 1     | 1     | 0     | 1     | 0                    | 0      | 1      | 1                          |
| 7   | 1     | 1     | 1     | 1     | 0                    | 1      | 0      | 0                          |

#### Diagramma degli stati
![[Excalidraw/pallogramma]]


# Punto II + III)
scriviamo il circuito in forma $fMg$ usando le formule ricavate per $Q_0',Q_1',Q_2'$ trasformando tutto in flipflop D e mettendo tutte le porte logiche necessare in $f$.

![[fmg]]

# Punto IV)
![[Excalidraw/m1m2]]

# Punto V)
stampare l'uscita $Z = \cdots10111101010 \cdots$ con $T=11$
![[Excalidraw/pallogramma]]
![[Excalidraw/punto5]]
![[Excalidraw/pallogramma_punto5]]

# Punto VI)
![[Excalidraw/tabella_verita_punto6]]

a