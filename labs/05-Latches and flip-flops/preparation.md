1. Write characteristic equations and complete truth tables for D, JK, T flip-flops where `q(n)` represents main output value before the clock edge and `q(n+1)` represents value after the clock edge.

![Characteristic equations](https://github.com/MichaelDolezel/digital-electronic-1/blob/aa42f81dcfa4342af5c7f0bb3909b8f4184314af/labs/05-Latches%20and%20flip-flops/images/eq_flip_flops.png)
<!--
\begin{align*}
    q_{n+1}^D =&~ \\
    q_{n+1}^{JK} =&\\
    q_{n+1}^T =&\\
\end{align*}
-->

   | **clk** | **d** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 0 |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 1 |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |

   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 0 | 0 | 0 | No change |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 0 | 1 | 1 | No change |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 |  |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 |  |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |  |

   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 0 |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 0 | 1 |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |
   | ![rising](labs/05-Latches and flip-flops/images/eq_uparrow.png) | 1 |  |  |  |
