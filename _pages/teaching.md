---
title: "Aviv Tamar - Teaching"
layout: gridlay
excerpt: "Aviv Tamar -- Teaching."
sitemap: false
permalink: /teaching/
---


# Teaching

## 046194 Planning and Learning in Dynamical Systems 
## (a.k.a. Reinforcement Learning)

Resources: 

<a href="{{ site.url }}{{ site.baseurl }}/downloads/RL_lectures_July_19.pdf">Lecture notes</a> by S. Mannor, N. Shimkin, A. Tamar

<a href="https://arxiv.org/abs/1904.07272">Introduction to Multi Armed Bandits</a> by A. Slivkins

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-zd5i{font-size:14px;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-ltad{font-size:14px;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-zd5i">Week</th>
    <th class="tg-zd5i">Lecture</th>
    <th class="tg-zd5i">Tutorial</th>
    <th class="tg-zd5i">Reference</th>
  </tr>
  <tr>
    <td class="tg-zd5i">1</td>
    <td class="tg-zd5i">Overview and examples<br>Dynamic Programming (DP): basic ideas</td>
    <td class="tg-zd5i">DP - knapsack, LCS</td>
    <td class="tg-zd5i">Ch. 1, 3.1 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">2</td>
    <td class="tg-zd5i">Deterministic Controlled Processes <br>Finite horizon DP (for deterministic process)</td>
    <td class="tg-zd5i">Fixed horizon DP, TSP</td>
    <td class="tg-zd5i">Ch. 2 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">3</td>
    <td class="tg-zd5i">Shortest-path problems <br>Graph search algorithms: Bellman-Ford, Dijkstra, A* <br>Deterministic continuous control: LQR, iLQR</td>
    <td class="tg-zd5i">Shortest path on graph<br>Dijkstra proof</td>
    <td class="tg-zd5i">Ch. 3.2, 3.3 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">4</td>
    <td class="tg-zd5i">Markov Decision Processes (MDP)<br>Finite horizon DP (for MDPs)</td>
    <td class="tg-zd5i">LQR</td>
    <td class="tg-zd5i">Ch. 4 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">5</td>
    <td class="tg-zd5i">Finite horizon DP (cont'd) <br>Discounted MDPs</td>
    <td class="tg-zd5i">Markov chains<br>Viterbi algorithm</td>
    <td class="tg-zd5i">Ch. 5 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">6</td>
    <td class="tg-zd5i">Discounted MDPs (cont'd)<br>Value Iteration</td>
    <td class="tg-zd5i">VI, Bellman operator</td>
    <td class="tg-zd5i">Ch. 5 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">7</td>
    <td class="tg-zd5i">Policy Iteration<br>Linear Programming formulations</td>
    <td class="tg-zd5i">Robust DP<br>PI vs. VI</td>
    <td class="tg-zd5i">Ch. 5 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">8</td>
    <td class="tg-zd5i">Model free learning (small state spaces): TD(0), Q-learning, SARSA</td>
    <td class="tg-zd5i">TD(0)<br>TD(lambda)</td>
    <td class="tg-zd5i">Ch. 6 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">9</td>
    <td class="tg-zd5i">MDPs with large state spaces - value-based approximations <br>projected Bellman equation<br>Policy evaluation algorithms: regression, TD(0), LSTD<br>Approximate policy iteration: LSPI, SARSA<br>Approximate value iteration: fitted-Q, Q-learning</td>
    <td class="tg-zd5i">LSTD <br>LSPI</td>
    <td class="tg-zd5i">Ch. 9.1, 9.3 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">10</td>
    <td class="tg-zd5i">Stochastic approximation<br>Convergence of RL algorithms</td>
    <td class="tg-zd5i">Stochastic approximation</td>
    <td class="tg-zd5i">Ch. 7,8 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">11</td>
    <td class="tg-zd5i">MDPs with large state spaces - policy-based approximations<br>Policy search <br>Policy gradients<br>Actor-critic</td>
    <td class="tg-zd5i">Policy gradients</td>
    <td class="tg-zd5i">Ch. 10 in Lecture Notes</td>
  </tr>
  <tr>
    <td class="tg-zd5i">12</td>
    <td class="tg-zd5i">Multi-armed bandits in the stationary arm model <br>Regret, Hoeffding inequality, uniform exploration, adaptive exploration</td>
    <td class="tg-zd5i">UCB</td>
    <td class="tg-zd5i">Ch. 1 in Slivkins' book</td>
  </tr>
  <tr>
    <td class="tg-zd5i">13</td>
    <td class="tg-zd5i">MDPs with large state spaces - Monte Carlo Tree Search (UCT)<br>Deep RL (overview)</td>
    <td class="tg-zd5i">TD(0)+FA convergence</td>
    <td class="tg-zd5i">Ch. 9.2 in Lecture Notes</td>
  </tr>
</table>