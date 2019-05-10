[![Build Status](https://travis-ci.com/onyiny-ang/salmon.svg?token=6hmRNtGMeYcpom73Q3ph&branch=master)](https://travis-ci.com/onyiny-ang/salmon "Travis")
[![Image Repository on Quay](https://quay.io/repository/onyiny_ang/salmon-tsp/status "Image Repository on Quay")](https://quay.io/repository/onyiny_ang/salmon-tsp)

# The Salmon Algorithm

The Salmon Algorithm, developed by John
Orth as part of his Master’s thesis, combines
concepts from existing metaheuristics such as
Genetic Algorithms(GA) and Ant Colony Op-
timization (ACO), to solve combinatorial opti-
mization problems in a reasonable amount of
time [1]. The Salmon Algorithm was inspired
by the behaviour of salmon swimming up-
stream to spawn. In the wild, salmon return to
the place they were born to spawn, suggesting
something resembling a memory of the path
their parents’ took. A salmon’s memory can be
likened to parent chromosomes in GA, since
both contain the full path of the parent. The
memory parameter determines to what degree
a salmon follows its parent’s path. Likewise,
salmon will not lay eggs if the water level is too
low. The water level can be likened to that of
the pheromone which helps direct an ant’s path
in ACO. Like many evolutionary algorithms,
the salmon algorithm involves populations of
salmon that run for several generations. The
salmon algorithm makes no claims of accu-
rately representing real salmon, but attempts to
simulate idealized aspects of salmon’s spawn-
ing behaviour to effectively solve computation-
ally hard problems [1].

---
##### 1. J. Orth, “The Salmon Algorithm-A New Population Based Search Metaheuristic,” Master’s Thesis, Brock University, 2012. [Online]. Available: [https://dr.library.brocku.ca/handle/10464/3929](https://dr.library.brocku.ca/handle/10464/392)