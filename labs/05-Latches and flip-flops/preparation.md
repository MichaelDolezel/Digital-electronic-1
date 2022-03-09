1. Write characteristic equations and complete truth tables for D, JK, T flip-flops where `q(n)` represents main output value before the clock edge and `q(n+1)` represents value after the clock edge.

<img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/3f44dbca1e2b735c4e3a61ea33c151024d36a747/labs/05-Latches%20and%20flip-flops/images/flip_flop.jpg" width=30% height=30%>

<!--
\begin{align*}
    q_{n+1}^D =&~ \\
    q_{n+1}^{JK} =&\\ D
    q_{n+1}^T =&\\
\end{align*}
-->

   | **clk** | **d** | **q(n)** | **q(n+1)** | **q(n+1) neg** |
   | :-: | :-: | :-: | :-: | :-- |
   | up | 0 | 0 | q | q-neg |
   | up | 0 | 1 | q | q-neg |
   | up | 1 | 0 | 0 | 1 |
   | up | 1 | 1 | 1 | 0 |

   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | 0  | X | X | 0 | 0 | Not alowed |
   | up | 0 | 0 | 0 | 0 | No change |
   | up | 0 | 0 | 1 | 1 | No change |
   | up | 0 | 1 | 0 | 0 | Reset |
   | up | 0 | 1 | 1 | 0 | Reset |
   | up | 1 | 0 | 0 | 1 | Set |
   | up | 1 | 0 | 1 | 1 | Set |
   | up | 1 | 1 | 0 | 1 | Toggle |
   | up | 1 | 1 | 1 | 0 | Toggle |

   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | up | 0 | 0 | 0 |  |
   | up | 0 | 1 | 1 |  |
   | up | 1 | 0 | 1 |  |
   | up | 1 | 1 | 0 |  |
