# RDBMS_ML
tecnical/intuitive pipeline linking rdbms and ml


## Select Score Level Evenly Distributed Ground Truth Table 
=> this step is performed upon visiting combination of two tables, thus usally O(n*m) where each table has n, m rows resp.
=> Thus we perform this at randomly sampled a few cases which considered enough to train. 
=> In this way we rather work on the O(n*m) search space, keep working in the random sampled space to check whether the model is running well or not. (and this random sampled space will be keep manuaully crafted and become highly qualified)

## Manual Recraft of the Ground Truth Table
=> 

## Train ML Model with the GT 

