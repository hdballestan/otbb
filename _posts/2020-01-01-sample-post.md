---
layout: post
title: "Statistical mechanics of money, wealth, and income"
---

# Dragulescu and Yakovenko model


This model considers a closed economic system based on $N$ agents that exchange one or more monetary units with each other \[[1](#bibliography)\]. The exchange consists of a 'losing' agent gives an amount $\Delta M$ (of money for instance) to the winner, if the winner is the agent $m_{j}$, he will have $m_{j} + \Delta m$ and agent $i$ will be left with money $m_{i} - \Delta m$ so it is a conserved system.

$$
\begin{eqnarray}
\left[m_{i}, m_{j}\right] \rightarrow \left[m_{i}^{'}, m_{j}^{'}\right] &=& \left[m_{i} - \Delta m, m_{j} + \Delta m\right]\\
m_{i} + m_{j} &=& m_{i}^{'} + m_{j}^{'}
\end{eqnarray}
$$

The system then consists of $N$ agents competing for portions of the total "_money_" of the system $M$. Initially all agents have the same amount of money and therefore The shape of the distribution corresponds to a delta function \[[1](#bibliography)\]:

$$
\begin{eqnarray}
P (x) = \delta \left(m - \dfrac{M}{N}\right) 
\end{eqnarray}
$$

After having defined the type of transaction in the system, two agents are chosen random (one winner and one loser), and money $\Delta m \geq 0$ is transferred from one to the other, as long as the amount to be exchanged is less than the loser's money.

Otherwise, the transaction does not take place and another pair of agents is chosen. If this procedure is performed many times, the system goes through different distributions until reaching the equilibrium distribution. Likewise, the entropy in the system increases over time until reaching a saturation point.

![Image]({{ site.baseurl }}/images/day1.png)

<div style="text-align: center;">
    <img src="{{ site.baseurl }}/images/day1.png" alt=" Stationary probability distribution over money P (m)" style="max-width: 100%; height: auto;">
    <p style="font-style: italic;"> Stationary probability distribution over money P (m) [1]</p>
</div>


This model follows three exchange rules, in the first the entropy grows slowly since a fixed amount of money is exchanged; In the second, a random fraction of the average money of the pair of agents involved in the transaction is exchanged, and in the third, the agents exchange a random amount of the average money of the system, adjusting in each case to a distribution Boltzmann-Gibbs

## Bibliography
<a id="bibliography"></a>

1. A. Dragulescu and V. M. Yakovenko. Statistical mechanics of money. European Physical	Journal B, 17(4):723–729, 2000
