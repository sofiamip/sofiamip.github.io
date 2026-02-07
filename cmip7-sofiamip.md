---
layout: page
header:
  logo: "/images/sofia_logo_mip_1000.png"
---

**NB**: Draft in edit:

# SOFIAMIP in CMIP7

SOFIAMIP is a registered [CMIP7 community MIP](https://wcrp-cmip.org/mips/#registered-mips). The project will present plans to the CMIP community at the MIP virtual showcase event on 19 Feb 2026 (Register [here](https://airtable.com/appGEHtbRi0wy6T0x/pag7xfALmAEMb0HBB/form)).

The SOFIA community invites all interested CMIP7 modelling centres to participate in SOFIAMIP to help understand the role of unresolved ocean-icesheet feedbacks on climate projections, and to evaluate forcing datasets for inclusion in future CMIP historical experiments.
Model configurations should be those used in CMIP7 DECK. 

## SOFIAMIP experimental protocol

The experimental protocol will largely follow [Swart et al. (2023)](https://doi.org/10.5194/gmd-16-7289-2023), with the following updates:

- all the simulations (and their controls) will be based on CMIP7 piControl and historical forcing (as opposed to CMIP6). 
- In tier 2, a key new historical experiment is added, based on the observed rate and distribution of forcing around Antarctica as provided in [Schmidt et al. (2025)](https://gmd.copernicus.org/articles/18/8333/2025/)
   - For this experiment, water should only be added for Antarctica (not for Greenland).
   - This experiment is a key new addition, that will allow assessment of this forcing for possible inclusion in future rounds of CMIP historical forcing.
- In tier 2, the SSP based experiments described in Swart at al. (2023) are not included, since these were based on CMIP6 SSP and ISMIP6 freshwater inputs. SOFIAMIP could evolve towards including similar experiments in the future, then based on CMIP7 scenarios and ISMIP7 output.
- Tier 3 is ommitted to simplify participation and keep the focus on (1) providing a robust model uncertainty estimate based on tier 1 and (2) establishing confidence in a standard freshwater flux boundary condition in the absance of an interactive Antarctic ice sheet component for future CMIPs. 

A summary of experiments is provided below:

| Name                   | FW perturbation (Sv)                    | Branch year | Time span (year) | Other forcing       |
| -----------------------|-----------------------------------------|-------------|------------------|---------------------|
| **Tier-1**             |                                         |             |                  |                     |
| antwater               | Fixed 0.1                               | N/A         | ≥100             | CMIP7 piControl     |
|                        |                                         |             |                  |                     |
| **Tier-2**             |                                         |             |                  |                     |
| hist-antwater-70-01    | Increasing by 0.1 (×10⁻³ Sv·yr⁻¹)       | 1970        | 1970-2020        | CMIP7 historical    |
| hist-antwater-70-03    | Increasing by 0.3 (×10⁻³ Sv·yr⁻¹)       | 1970        | 1970-2020        | CMIP7 historical    |
| hist-antwater-70-05    | Increasing by 0.5 (×10⁻³ Sv·yr⁻¹)       | 1970        | 1970-2020        | CMIP7 historical    |
| hist-antwater-92-11    | Increasing by 1.1 (×10⁻³ Sv·yr⁻¹)       | 1992        | 1992-2020        | CMIP7 historical    |
| hist-obs-water         | Observed rate from Schmidt et al (2025) | 1990        | 1990-2023        | CMIP7 historical    |

## Data Request

[Swart et al. (2023)](https://doi.org/10.5194/gmd-16-7289-2023) A6 (Table A3) provides the lists of high priority variables for SOFIA, which largely carry over to CMIP7. However, a broader range of variables is useful - for example - ocean biogeochemistry variables have been used in some studies. Therefore, we would recommend providing a data request for SOFIAMIP as provided for DECK simulations.
