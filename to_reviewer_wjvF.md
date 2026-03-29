#  A. Response to Reviewer wjvF
### A.1 Computational Cost of Building the Interpretability Datastore

**Table 1. Model Configurations and Parameter Counts**
|Model | GPT-2       | GPT2-Medium | GPT2-Large | GPT2-XL  | GPT-Neo-2.7B | GPT-J-6B |
|------------|------------|-------------|------------|----------|--------------|----------|
| Parameters| 117 million | 345 million | 774 million | 1.5 billion | 2.7 billion  | 6 billion |

#### A.1.1 Runtime 

<table>
<tr>
  <td align="center">
    <img src="results/runtime_a100GPU_40GB.png" width="600"><br>
    <b>Figure 1. Runtime per Layer. </b>
  </td>
</table>


#### A.1.2 Peak GPU memory 
 <table>
<tr>
  <td align="center">
    <img src="results/mem_a100GPU_40GB.png" width="600"><br>
    <b>Figure 2. Peak GPU Memory per Layer. </b>
  </td>
</table>
