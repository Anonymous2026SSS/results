#  A. Response to Reviewer rK9R
### A.1 Causal Evidence of Pathway-Driven Predictions When the Target Token Is Not Rank-1.
Following the experiment in Section 4.2 (part 2) of the paper, we use the NaNA framework to extract the pathway for "*The capital of Germany is*" → "*Frankfurt*".  We perform both **standard and ablation experiments** by reconstructing the middle-to-late MLP layers of GPT-2 Medium using an increasing number of high-contribution subspaces. The top-15 predicted tokens for the prompt "*The capital of Germany is*" are then presented. The results demonstrate that using only the top-15 subspaces is sufficient to successfully predict "*Frankfurt*".
 
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
 

### A.2 Impact of Pathways on Predictive Performance (When the Target Token Is Not Rank-1).
Following the experiments in Section 4.2 (part 1) of the paper, we conduct **standard and ablation experiments** to evaluate the impact of high-contribution subspaces on the target token’s probability (↑) and rank (↓) in the case "*The capital of Germany is*" → "*Frankfurt*". Here, randomly selected subspaces are used as a baseline. The results indicate that the dominant subspaces identified by SCA are necessary for predicting the specific target token.

<table>
<tr>
  <td align="center">
    <img src="results/gpt2-medium_token_rank_curve.png" width="500"><br>
    <b>Figure 2 (a). Rank (↓) </b>
  </td>
  <td align="center">
    <img src="results/gpt2-medium_token_prob_curve.png" width="500"><br>
    <b>Figure 2 (b). Probability (↑) </b>
  </td>
</tr>
</table>


### A.3 Subspace Interventions.
Following the experiments in Section 4.2 (part 3) of the paper, we visualize the effects of manipulating Subspaces 5 and 9 of Layer 16 in GPT2-Medium for the prompt "*The cat looks very*".  The table below presents the semantics of these subspaces and their contributions. We observe that amplifying or suppressing certain subspaces, such as 5 or 9, correspondingly enhances their positive or negative semantic interpretations.  
|subspace| Positive Direction|  Negative Direction| Subspace Contribution|
|-|-|-|-|
| 5 | Inspection Actions | insufficiency concepts | 0.073 |
| 9 | historical decades |Criticismand Feedback | 0.0623 |
<table>
<tr>
  <td align="center">
    <img src="results/interven_single_subspace5.png" width="500"><br>
    <b>Figure 2 (a). Rank (↓) </b>
  </td>
  <td align="center">
    <img src="results/interven_single_subspace9.png" width="500"><br>
    <b>Figure 2 (b). Probability (↑) </b>
  </td>
</tr>
</table>

