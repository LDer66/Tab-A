**Table A.** Performance comparison between FedRGL and FedRGL# under the same settings as Table 2 in the paper,FedRGL# uses the hybrid aggregation $W^{t+1}=\sum_{m=1}^{M}\frac{V_m H_m}{\sum_{m=1}^{M}V_m H_m}w_m^t$, where $V_m$ and $H_m$ denote the client data size and the inverse of the average predictive entropy, respectively. N/U/P denote no-noise/Uniform/Pair noise.

|Dataset|Cora|||CiteSeer|||PubMed|||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|Method|N|U|P|N|U|P|N|U|P|
|FedRGL|82.12±0.51|78.75±0.98|75.14±0.30|71.52±0.14|66.08±1.02|63.22±0.82|85.33±0.12|81.77±0.32|76.84±0.23|
|FedRGL#|82.08±0.77|78.03±0.87|74.21±0.59|71.61±0.28|65.33±1.29|61.82±0.87|85.54±0.20|81.21±0.53|75.27±0.75|

|Dataset|CS|||Photo|||Physics|||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|Method|N|U|P|N|U|P|N|U|P|
|FedRGL|90.58±0.13|87.79±0.22|81.01±0.32|88.42±0.27|84.06±1.13|77.56±0.73|93.62±0.11|89.66±0.53|86.39±0.51|
|FedRGL#|90.66±0.34|86.92±0.21|80.44±0.45|88.38±0.25|82.69±1.22|75.73±0.79|93.85±0.37|88.51±0.78|84.95±0.82|

<p><strong>Table B.</strong> Pseudo-label accuracy of high-confidence nodes on CS with 10 clients under Uniform noise rate 0.5 at different communication rounds.</p>

<table>
  <tr>
    <th>CS</th>
    <th colspan="10" align="center">Client Index</th>
  </tr>
  <tr>
    <th>Rounds</th>
    <th>1</th><th>2</th><th>3</th><th>4</th><th>5</th>
    <th>6</th><th>7</th><th>8</th><th>9</th><th>10</th>
  </tr>
  <tr>
    <td>30</td>
    <td>0.852</td><td>0.847</td><td>0.824</td><td>0.819</td><td>0.826</td>
    <td>0.814</td><td>0.817</td><td>0.831</td><td>0.843</td><td>0.822</td>
  </tr>
  <tr>
    <td>50</td>
    <td>0.867</td><td>0.881</td><td>0.865</td><td>0.856</td><td>0.871</td>
    <td>0.842</td><td>0.863</td><td>0.890</td><td>0.901</td><td>0.872</td>
  </tr>
  <tr>
    <td>70</td>
    <td>0.929</td><td>0.952</td><td>0.923</td><td>0.917</td><td>0.919</td>
    <td>0.895</td><td>0.904</td><td>0.948</td><td>0.945</td><td>0.930</td>
  </tr>
</table>


