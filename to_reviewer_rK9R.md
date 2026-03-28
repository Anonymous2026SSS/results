#  A. Response to Reviewer rK9R
### A.1 Causal Evidence of Pathway-Driven Predictions When the Target Token Is Not Rank-1.
Following the experiment in Section 4.2 (part 2), we use the NaNA framework to extract the pathway for "*The capital of Germany is*" → "*Frankfurt*".  We perform both **standard and ablation experiments** by reconstructing the middle-to-late MLP layers of GPT-2 Medium using an increasing number of high-contribution subspaces. The top-15 predicted tokens for the prompt "*The capital of Germany is*" are then presented. The results demonstrate that using only the top-15 subspaces is sufficient to successfully predict "*Frankfurt*".
 
<table>
<tr>
  <td align="center">
    <img src="results/Frankfurt_general_gpt2-medium.png" width="500"><br>
    <b>Figure 1 (a). Standard Experiment</b>
  </td>
  <td align="center">
    <img src="results/Frankfurt_ablation_gpt2-medium.png" width="500"><br>
    <b>Figure 1 (b). Ablation Experiment </b>
  </td>
</tr>
</table>
 

 
