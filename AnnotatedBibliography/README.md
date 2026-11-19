# Annotated Bibliography

Key papers are briefly summarized below. The [PDF folder](https://github.com/SOLV-Code/DigitalTwinFeasibilityForPSC/tree/main/AnnotatedBibliography/PDF) has copies of any papers that are freely downloadable. 



## Digital Twins - Fundamental Concepts


### Kritzinger et al. (2018) 

**Kritzinger W., M. Karner, G. Traar, J. Henjes, and W. Sihn (2018) Digital Twin in Manufacturing: A categorical literature review and classification. [IFAC PapersOnLine 51-11 (2018) 1016–1022](https://www.sciencedirect.com/science/article/pii/S2405896318316021)**  
This paper is focused on a very different setting (industrial manufacturing), but it lays out a very clear gradation from standard models to full digital twins, based on the level of automated data flow and integration. In their definitions:  
* *Digital Model*: a digital representation of an existing or planned physical object that does not use any form of automated data exchange between the physical object and the digital object.  
* *Digital Shadow*: if there further exists an automated one-way data flow between the state of an existing physical object and a digital object.  
* *Digital Twin*: if data flows between an existing physical object and a digital object are fully integrated in both directions (i.e., the short-term projection from the model is used to change settings in the physical object).  

## Digital Twins - Fish and Fisheries Applications

### Akenhead et al. (2026)  
**Akenhead, Scott A., Lene K. Sortland, Elvira de Eyto, Eduardo Martins, Gottfried Pestal, and Colin D. Bull. 2026. Capabilities Required from a Salmon Digital Twin. _In:_ North Pacific Anadromous Fish Commission Technical Report, 24:49–56. Vancouver BC Canada: North Pacific Anadromous Fish Commission. https://doi.org/https://doi.org/10.23849/npafctr24/109-565.**

An international team considered the challenge of salmon getting the DTs. One result was this project!
* suggests separate twins for each life stage and for each habitat that life stage occupies. Mechanistic simulations fitted from history.
* real-time updates of habitat state and predictions drive update of that life-stage: states, rates, and predictions.
* lots of challenges (tabled) but somehow a _workflow_ of habitat and life-stage twins links the pieces, allows re-use of _steps_ in different populations, and continuous improvement.
* details suggestion twins be U.S.E.R.-friendly: Understandable, Safe, Effective (decision support), and Reusable (steps in workflows/pipelines).

### Sortland et al. (2026)  
**Sortland, L.K., Martins, E.G., Føre, M., de Eyto, E., Diack, G., Bull, C.D., and Akenhead, S.A. 2026. A salmon’s eye view: Digital twins for salmon populations and salmon habitats. _In:_ PICES-2026 Book of Abstracts. North Pacific Marine Science Organization, Sidney, BC, Canada. p. 9. doi:https://doi.org/10.23849/npafctr24/109-565.**

Among the challenges of moving from 1950’s stock-recruit models to individual-based, mechanistic models for salmon will be large-scale mobilization of data, knowledge, and science, and an attendant requirement for better collaboration and communication. 
* The technological foundation for this _paradigm shift_ is facilitated by rapidly evolving, enabling technologies such as AI; how remains to be seen.
* Salmon twins that use ocean twins and watershed twins will open important opportunities including:
    + a more informed approach to reversing salmon population declines,
    + confronting and and prioritizing knowledge gaps,
    + faster learning from scenarios and experience (adaptive management), and critically
    + improved engagement with decision fora, co-managers, stakeholders, citizen science, and open-source collaborators.


## Digital Twins - Other Biological / Ecological Applications

### De Koning et al. (2023)  
**de Koning K, J. Broekhuijsen, I. Kühn, O. Ovaskainen, F. Taubert,. D. Endresen, D. Schigel, and V. Grimm (2023) Digital twins: dynamic model-data fusion for ecology. [Trends in Ecology & Evolution, October 2023, Vol. 38, No. 10](https://doi.org/10.1016/j.tree.2023.04.010)**  
* This paper provides a perspective what a digital twin is and is not, within the context of ecology. Specifically, they argue that digital twins *"are not just big models of everything, containing big data and machine learning. Rather, the strength of DTs is in combining data, models, and domain knowledge, and their continuous alignment with the real world."*
* That is a much broader definition of digital twins than the one used by [Kritzinger et al. 2018](https://github.com/SOLV-Code/DigitalTwinFeasibilityForPSC/tree/main/AnnotatedBibliography#kritzinger-et-al-2018) in a manufactoring context: they would consider these ecological models *digital shadows* rather than *digital twins*. 

## PSC Models - Fraser Sockeye  
### McKinnell (1997) - Fraser Sockeye Diversion Rate  
**McKinnell, S. (1997) Assessing the historical estimates of northern diversion of Fraser River sockeye salmon. [PSARC Working Paper S97-1](https://waves-vagues.dfo-mpo.gc.ca/library-bibliotheque/364129.pdf)**  
* This paper summarized available estimates of northern diversion rates from 1958 to 1995 and investigated biases introduced when run timing, stock composition, and differential harvest rates in individual fisheries are not accounted for.

### DFO (2016) - Fraser Sockeye Timing and Diversion  
**DFO (2016) Run Timing and Diversion Rate Models for Fraser River Sockeye. [DFO Can. Sci. Advis. Sec. Sci. Advis. Rep. 2016/008](https://waves-vagues.dfo-mpo.gc.ca/library-bibliotheque/365448.pdf)**  
* This is the consensus science adviced based on the analyses documented in [Folkes et al. 2018](https://github.com/SOLV-Code/DigitalTwinFeasibilityForPSC/tree/main/AnnotatedBibliography#folkes-et-al-2018---fraser-sockeye-timing-and-diversion).  
* focused on annual pre-season forecasts of aggregate diversion rate for the whole season across all Fraser sockeye stocks.   
* evaluated many environmental covariates (e.g., surface currents, wind stress), and tested thousands of statistical relationships between environmental variables and fisheries data. 
* *"Multiple variable models perform better than single variable models, and current velocity variables (OSCAR - Ocean Surface Current Analyses – Real time, and NEPSTAR - North East Pacific Salmon Tracking and Research) dominate top performing models."*  
* *"forecasting of atypical events requires further model assessmentbased on management risk tolerance criteria."*  
* Included some stock-specific observations. For example, **"Later Chilko run timing occurs when El Niño conditions are observed over any timebetween December and May of the return year. El Niño conditions in any month betweenSeptember of the year prior to adult return, and May of the return year, are associatedwith a significantly higher northern diversion."*  
* *"Many of the models developed are dependent on data that are currently publicly available,but sourced from external agencies (e.g. National Oceanic and AtmosphericAdministration [NOAA]). Others are dependent on contractors (NEPSTAR) and require anannual financial commitment."*  

### Folkes et al. (2018) - Fraser Sockeye Timing and Diversion  
**Folkes, M.J.P., Thomson, R.E., and Hourston, R.A.S. 2018. Evaluating Models to Forecast Return Timing and Diversion Rate of Fraser Sockeye Salmon. [DFO Can. Sci. Advis. Sec. Res. Doc. 2017/021. vi + 220 p.](https://waves-vagues.dfo-mpo.gc.ca/library-bibliotheque/40678118.pdf)**  
* This is the full analysis supporting the science advice provided in [DFO (2016)( https://github.com/SOLV-Code/DigitalTwinFeasibilityForPSC/tree/main/AnnotatedBibliography#dfo-2016---fraser-sockeye-timing-and-diversion). See detailed comments there.
* The {digital twins} process would make use to ocean circulation models which are under-utilized in the DFO resource management.
* This is one example of using ocean models to provide decision support to PSC. It has been used for many years.


