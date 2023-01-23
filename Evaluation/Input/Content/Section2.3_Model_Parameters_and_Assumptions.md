### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

There is no absorption process since dAb2 was administered intravenously.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

The standard lymph and fluid recirculation flow rates and the standard vascular properties of the different tissues (hydraulic conductivity, pore radii, fraction of flow via large pores) from PK-Sim were  used. dAb2, among other compounds, has been used to identify these lymph and fluid recirculation flow rates used in PK-Sim ([Niederalt 2018](#5-references)). 

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

dAb2 is predominantly renally eliminated by glomerular filtration ([Sepp 2015](#5-references)). Due to the molecular size of dAb2 the glomerular filtration is hindered and the glomerular filtration fraction was fitted. While being only of minor importance, the endosomal clearance process is present. The standard physiological parameters related to endosomal clearance were used (assuming no binding to FcRn). 

### Tissue Concentrations <a id="model-parameters-and-assumptions-tissue-concentrations"></a>

For the comparison with experimental data, the parameters `Fraction of blood for sampling` used in the Observer for the tissue concentrations were set for all organs to 0.42 for comparison with autoradiography data according to the fit results (across compounds) in Ref. ([Niederalt 2018](#5-references)). (The parameter `Fraction of blood for sampling` specifies residual blood in tissue as ratio of blood volume contributing to the measured tissue concentration to the total in vivo capillary blood volume.)

In the present evaluation report, the experimental gut concentrations were compared to simulated organ concentrations for small and large intestine separately in the goodness of fit plots as well as in the concentration-time profile plot.

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

The table shows the parameter values that were specified in the model based on the parameter identification reported in Ref. ([Niederalt 2018](#5-references)), and which were not included in the PK-Sim database since version 7.1.

| Model Parameter                                              | Optimized Value | Unit |
| ------------------------------------------------------------ | --------------- | ---- |
| `GFR fraction` (glomerular filtration rate fraction)         | 0.24            | -    |
| `Fraction of blood for sampling` (all organs) - for comparison with autoradiography data | 0.42            |      |

