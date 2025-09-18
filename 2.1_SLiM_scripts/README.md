### 0_Pseudo.slim, 0_Neutral.slim, 0_Adaptive.slim
SLiM code for Pseudo, Neutral, and Adaptive models.

### 1_AdapTrack_prepare.slim, 1_AdapTrack_pop.slim, 1_AdapTrack_pop50K.slim 
1_AdapTrack_prepare.slim prepares population snapshots at molecular evolution equilibrium for population size = 50,000 (pop50K), so replicate runs can start from the snapshots to save time. 
1_AdapTrack_pop.slim: SLiM code for different population size.
1_AdapTrack_pop50K.slim: SLiM code for population size = 50,000, will load pre-generated population snapshots.

### 1_AdapTrack_int.slim
SLiM code for AdapTrak model while varying number of generations. "int" means environmental interval.

### 1_AdapTrack_env.slim
SLiM code for AdapTrak model while varying number of environmental conditions (occured in cycle).

### 2_AdapTrack_pop_fluc.slim
SLiM code for AdapTrak model while allowing population size to change with environmental harshness during simulation.

### 2_AdapTrack_neufrac.slim 
SLiM code for AdapTrak model while varying fraction of neutral mutations.

### 2_AdapTrack_AP.slim
SLiM code for AdapTrak model while varying probability of being beneficial (or the level of antagonistic pleiotropy). "AP" means antagonistic pleiotropy.

### 2_AdapTrack_lambda.slim
SLiM code for AdapTrak model while considering the scenario where magnitude of an environmental change that occurs every generation follows an exponential distribution.

### 2_Neutral_dom.slim, 2_Adaptive_dom.slim, 2_AdapTrack_dom.slim
SLiM code for Neutral, Adaptive, and AdapTrack model while considering dominance effect. Coefficient of dominance of a mutation in an environment is h = 0.75 if the mutation is beneficial in the environment, 0.50 if the mutation is neutral, and 0.25 if the mutation is deleterious.

### 3_AdapTrack_quasineu.slim, 3_AdapTrack_adapt_fluc.slim
SLiM code for two fluctuating selection models: quasi-neutral model and fluctuating positive selectino model.

### 4_AdapTrack_stablespace.slim
SLiM code for the scenario of spatial heterogeneity. "stablespace" means temporally stable but environment vary in space.

### 5_Neutral_pop.slim, 5_Adaptive_pop.slim
SLiM code for Neutral and Adaptive model while varying population size.
    
