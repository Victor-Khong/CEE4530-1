# Prelab 3 for CEE 4530

### Team 10: Victor Khong & Jacqueline Wong ###

<b> 1. Compare the ability of Cayuga lake and Wolf pond (an Adirondack lake) to withstand an acid rain runoff event (from snow melt) that results in 20% of the original lake water being replaced by acid rain. The acid rain has a pH of 3.5 and is in equilibrium with the atmosphere. The ANC of Cayuga lake is 1.6 meq/L and the ANC of Wolf Pond is 70 μeq/L. Assume that carbonate species are the primary component of ANC in both lakes, and that they are in equilibrium with the atmosphere. What is the pH of both bodies of water after the acid rain input? Remember that ANC is the conservative parameter (not pH!). Hint: You can use the scipy optimize root finding function called brentq. Scipy can’t handle units so the units must be removed using .magnitude.}</b>

$$ ANC = [HCO_3^-]+2[CO_3^{-2} ]+{[OH}^- ] - [H^+] $$

```python
import scipy as sc

```

<b> 2. What is the ANC of a water sample containing only carbonates and a strong acid that is at pH 3.2? This requires that you inspect all of the species in the ANC equation (Equation (33)) and determine which species are important.</b>

$$ ANC = [HCO_3^-]+2[CO_3^{-2} ]+{[OH}^- ] - [H^+] $$

<b> 3. Why is [H+] not a conserved species? </b>
[H+] is not a conserved species because of the chemical reactions between different species.