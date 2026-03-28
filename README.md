#  Response to Reviewer onrA
### Evaluation on Constructed Datasets and Advanced SAE Variants
#### 🔹 Evaluation on the Gender Pronoun Task
On the Gender Pronoun Task, we compare SCA (ours) with vanilla SAE, JumpReLU SAE, Top-K SAE, BatchTopK SAE, and the Transcoder.

<table>
<tr>
  <td align="center">
    <b>Rank</b><br>
    <img src="results/target_rank_layer_10_gender_pron_with_topkbatch.png" width="300">
  </td>
  <td align="center">
    <b>Probability</b><br>
    <img src="results/target_probability_layer_10_gender_pron_with_topkbatch.png" width="300">
  </td>
</tr>
</table>

| ![](results/target_rank_layer_10_gender_pron_with_topkbatch.png) | ![](results/target_probability_layer_10_gender_pron_with_topkbatch.png) |
|:----------------:|:----------------:|
| Rank | Probability |

#### 🔹 Evaluation on the Subject–Verb Agreement Task (Simple Structure)
On the Subject–Verb Agreement Task (Simple Structure), we compare SCA (ours) with vanilla SAE, JumpReLU SAE, Top-K SAE, BatchTopK SAE, and the Transcoder.
| ![](results/target_rank_layer_10_simple_SVA_without_topkbatch.png) | ![](target_probability_layer_10_simple_SVA_without_topkbatch.png) |
|:----------------:|:----------------:|
| Rank (without Top-K SAE) | Probability (without Top-K SAE) |
|:----------------:|:----------------:|
| ![](results/target_rank_layer_10_simple_SVA_with_topkbatch.png) | ![](target_probability_layer_10_simple_SVA_with_topkbatch.png) |
|:----------------:|:----------------:|
| Rank (with Top-K SAE) | Probability (with Top-K SAE) |
