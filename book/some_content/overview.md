# Basic Theory

The analysis assumes steady-state flow in a confined aquifer, although it can be applied to unconfined flow with a bit of judgement as long as the gradients are not too large. The transmissivity, T $[L^2/T]$, of a tabular aquifer is computed as T=Kb, where K is the hydraulic conductivity and b is the thickness of the aquifer. The gradient, i, determines how fast the water moves through the aquifer and the zone of capture is the portion of the aquifer in which the water is captured by a well pumping at a rate Q. If the width of the zone of capture is denoted as 2y then then $Q=iKb2y$ $[L^3/T]$. Alternatively, the width of the zone of capture
$$
2y=\frac{Q}(iKb}\
$$
The diagram below shows the concept. Note that in the diagram the x-axis is parallel to the direction of flow and y-axis is orthogonal to the direction of flow. This convention makes the solution very simple for a problem with a single well, as shown in the Figure. 
```{figure} ../figures/Zone_of_Capture.jpg
---
scale:65%
align: center
---
Zone of Capture Illustration
```
The final item is the stagnation point, which is the point at which the gradient is exactly zero downgradient from the well as shown in the figure. The expression to compute the distance of this point downgradient is:
$$
 x_{L}=-\frac{Q}{2piKbi}\
$$ 
