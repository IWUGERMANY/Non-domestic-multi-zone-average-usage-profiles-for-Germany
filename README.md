# Non-domestic-multi-zone-average-usage-profiles-for-Germany
Building stock models are valuable tools for the determination of the impacts of building stock-related efficiency and sufficiency measures on greenhouse gas reduction strategies. The building stock is often simulated based on single-zone models of buildings to cope with computational expenses. Especially in the case of the non-domestic building stock, data sources are incomplete and provide only the most basic information on the stock’s building characteristics. Further uncertainty is added to the simulation results in cases where a standardized usage profile of only one standardized usage profile of a single zone is applied for the simulation of the entire building, as the usage of a non-domestic building is typically heterogeneous. Increasing model complexity to multi-zone models usually fails due to missing data.

The aim of this work is twofold. The first goal is to determine average usage profiles and parameters that are specific to non-domestic building categories and their typical internal zoning. The second goal is to evaluate these profiles’ capacity in the reduction of uncertainties when applied in single zone models, compared to a multi zone equivalent.  The average usage profiles determined in this work and the case study for evaluation comprise German non-domestic buildings. In recent work, the floor area shares of default usages for 84 non-domestic building categories in Germany were determined, based on a sample of 5,690 building energy certificates. In this work, the before-mentioned non-domestic building categories are matched to the 107 main and sub-categories of the German non-residential building database (www.datanwg.de). Building on this assignment, average usage profiles are derived from the zone-specific usage profiles of the German standard DIN V 18599-10 and the typical floor area shares of these zones. The resulting average usage profiles are consequently building category specific. A case study is performed, in which the net energy demands for heating, cooling, and lighting are determined for the recently published 33 representative German non-domestic building types (https://github.com/IWUGERMANY/Nichtwohngebaeude-Typologie-Deutschland). A multi-zone building model (M), considering the typical zoning in the building usage category, is used as the benchmark against typical single-zone building models with usage parameters of the five predominant use individually (S) as well as a single-zone building model with averaged usage profiles (S+). As the selection of the predominant use for the S models is often based on subjective assignment, the five largest default zones of the M model are individually used in the S model to determine the uncertainties of the predominant use selection.

By comparing the net energy demands for the three simulations (M, S and S+), it is shown that the accuracy of the single zone building model (S) strongly depends on the similarity between the assumed main zone and the actual typical zoning. Especially in buildings with very diverse internal zoning, a false assumption about the main usage can lead to significant deviations. In the studied case of simulating German non-domestic buildings, the S+ model results generally are very close to the M results, while the S results divert greatly. Therefore, the developed building category-specific usage profiles, provide a simple way of reducing the usage-based uncertainties for single-zone building models. The developed building category-specific usage parameters for all 11 main- and 96 sub-categories of the German non-residential building research database are available in this repository under an open-source license.

In this repository multi-zone average usage profiles for non-domestic building usage categories in Germany are provided. These multi-zone average usage profiles allow the simulation of single-zone building models while at the same time reduing the "single-zone" uncertainty compared to a multi-zone approache drastically.

The Concept of the typology was first published at the [eceee Summerstudy 2022](https://www.eceee.org/summerstudy/) in a peer-reviewed article, availble in the [proceedings](https://www.researchgate.net).

---
## How to cite
- Karczewski, Christian; Bischof, Julian; Hörner, Michael. Multi-zone average usage profiles for non-domestic building usage categories in Germany. GitHub: https://github.com/IWUGERMANY/Non-domestic-multi-zone-average-usage-profiles-for-Germany. Supplementary Material to the article "Evaluating non-domestic building stock simulation based on single-zone models with multi-zone average usage profiles" published in the proceedings of the ECEEE-Summer Study 2024. 2024.
---

Total number of individual page views:
 <a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/lpmti5b26dpcb79duvml" alt="trackgit-views" />
</a>