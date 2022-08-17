# culture.den

_Replication code for The Ties that Bind: A social network analysis of cultural capital in Denmark__ <br>
_Candidate Number: 33200_

To load graph objects for analysis into R environment: <br>

1) Load data from __soc.elite__ <br>
library(devtools) <br>
install_github("antongrau/soc.elite", force = TRUE) <br>
data(den) <br>
data(pe13) <br>

2) Run __Projection.Rmd__
3) Run __DEN Subgraphs.Rmd__
