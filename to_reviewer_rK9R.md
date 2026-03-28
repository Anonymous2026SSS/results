#  A. Response to Reviewer rK9R
### A.1 Evaluation on Constructed Datasets and Advanced SAE Variants
#### A.1.1 Evaluation on the Gender Pronoun Task
On the Gender Pronoun Task, we compare SCA (ours) with vanilla SAE, JumpReLU SAE, Top-K SAE, BatchTopK SAE, and the Transcoder. Due to the large fluctuations of the Top-K SAE curve, Figures 1(a) and 1(b) do not include Top-K SAE. Figures 2(a) and 2(b) include Top-K SAE.\
(NOTE: Lower rank values (↓) indicate better performance, whereas higher probability values (↑) indicate better performance.)
 
<table>
<tr>
  <td align="center">
    <img src="results/target_rank_layer_10_gender_pron_without_topkbatch.png" width="300"><br>
    <b>Figure 1 (a). Rank (↓, without Top-K SAE)</b>
  </td>
  <td align="center">
    <img src="results/target_probability_layer_10_gender_pron_without_topkbatch.png" width="300"><br>
    <b>Figure 1 (b). Probability (↑, without Top-K SAE)</b>
  </td>
</tr>
</table>
<table>
<tr>
  <td align="center">
    <img src="results/target_rank_layer_10_gender_pron_with_topkbatch.png" width="300"><br>
    <b>Figure 2 (a). Rank (↓, with Top-K SAE)</b>
  </td>
  <td align="center">
    <img src="results/target_probability_layer_10_gender_pron_with_topkbatch.png" width="300"><br>
    <b> Figure 2 (b). Probability (↑, with Top-K SAE)  </b>
  </td>
</tr>
</table>

 