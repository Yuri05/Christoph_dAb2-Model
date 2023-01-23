The PBPK model for dAb2 was evaluated with blood and tissue PK data in mice.

These PK data (except for kidney) have been used together with PK data from 5 other compounds to simultaneously identify parameters during the development of the generic model for proteins and large molecules in PK-Sim ([Niederalt 2018](#5-references)).

As expected, the kidney concentrations are considerably underestimated by the PBPK simulations. In the present PBPK model, the kidney has the same organ model structure as other organs. Thus, drug within the tubular fluid does not account to total kidney concentrations. Drug in tubular fluid is relevant for small proteins which are renally cleared by glomerular filtration. For these proteins, the representation of the kidney has to be extended in order to describe total kidney concentrations, see e.g. Sepp et. al. 2015 ([Sepp 2015](#5-references)). 

The next sections show:

1. the final model parameters for the building blocks: [Section 3.1](#final-input-parameters).
2. the overall goodness of fit: [Section 3.2](#diagnostics-plots).
3. simulated vs. observed concentration-time profiles for the clinical studies used for model building and for model verification: [Section 3.3](#ct-profiles).

