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

**Table B.** Pseudo-label accuracy of high-confidence nodes on CS with 10 clients under Uniform noise rate 0.5 at different communication rounds.

|CS|Client Index||||||||||
|-|-|-|-|-|-|-|-|-|-|-|
|Rounds|1|2|3|4|5|6|7|8|9|10|
|30|0.852|0.847|0.824|0.819|0.826|0.814|0.817|0.831|0.843|0.822|
|50|0.867|0.881|0.865|0.856|0.871|0.842|0.863|0.890|0.901|0.872|
|70|0.929|0.952|0.923|0.917|0.919|0.895|0.904|0.948|0.945|0.930|


