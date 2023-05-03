Download Link: https://assignmentchef.com/product/solved-cs312-lab-7-reinforcement-learning
<br>
<span class="kksr-muted">Rate this product</span>

<table>

 <tbody>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Reinforcement Learning

Goal:Solve an MDP problem using policy and value iteration.

Note: This assignment is to be done individually.

MDP(Markov Decision Process): Grid World Problem:

There will be a grid, location of the player in the grid will represent a state, there will be a starting state, there will be two absorbing states having very different rewards like +1 and -20 while other states will have negative reward -1 associated with them, movement to that state will incur this negative reward. The black block is a wall where your agent won’t be able to penetrate through. The transition probabilities for moving from one state to another are also given below. We need to find optimal movement direction for each state.

End +10

End -200

ssssssss

Start

Below are the transition probabilities

<ol>

 <li>Develop code for solving the MDP problem using policy and value iteration.</li>

 <li>Write a report clearly describing the above MDP considered and your observations onrunning the policy and value iteration algorithms on the formulated MDP.</li>

 <li>Further, one should also suggest ways to check whether the algorithm yields optimal policy for the setting considered.</li>

</ol>

Submission: This assignment is to be submitted individually.Please submit a zip file &lt;Roll_number&gt;.zip with the following contents

<ol>

 <li>Program: &lt;Roll_number&gt;.&lt;extension&gt; (e.g., 1800100xx.c/cpp)</li>

 <li>Report: &lt;Roll_number&gt;.&lt;extension&gt; (e.g., 1800100xx.pdf). Report should be in pdfformat.</li>

 <li>Readme file: readme.txt (Execution details)</li>

</ol>

Report Format :

<ol>

 <li>[1 mark] MDP Description: Clearly describe (S, A, P, R, N)</li>

 <li>[5 marks] State-transition Graph for the MDP</li>

 <li>[1 mark] Optimal Policy: Suggest ways to check whether the algorithm yields optimal policy for the setting considered.</li>

 <li>[5 marks] Experimental Results: Vary the gamma parameter, show the policy found in each case by both algorithms</li>

 <li>[2 marks] Comparison of Policy Iteration and Value Iteration</li>

 <li>[1 marks] Conclusions</li>