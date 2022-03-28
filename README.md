# Title

Multilevel Bayesian joint modeling for a longitudinal marker and time-to-recurrent event to characterize heterogeneity in multi-center studies

# Abstract

The rapid declines in lung function caused by cystic fibrosis (CF) are marked by recurrent respiratory events called pulmonary exacerbations (PEs). A shared parameter joint longitudinal-survival model associated time-to-first PE with lung function decline has been proposed but ignoring center effects. Since CF lung function has been measured extensively using multi-center cohorts from registries. Characterizing risk of recurrent PE in multi-center sense may deepen epidemiologic understanding of long-term disease progression.  

Using a novel Bayesian joint modelling approach, we simultaneously modeled the joint distribution between lung function (measured as ppFEV1) and recurrent PE risk using the US CF Registry (2003-2017). Individuals aged > 6 years with at least one PE ever during follow-up among 6 centers were purposively selected for broad PE severity. Center effects in both longitudinal and event submodels were included by defining risk episode on a calendar timescale. The joint model was implemented via Hamiltonian Monte Carlo (R interface to stan). 

Preliminary results show that both value and slope of the ppFEV1 trajectory were negatively associated with PE hazard. Center-specific coefficients appreciably differed from zero based on model evidence. Findings imply more precise medical monitoring on risks posed by recurrent PE by incorporating center-specific parameters. 


# Keywords 

multi-center, recurrent event, joint model, Hamiltonian Monte Carlo, medical monitoring

