# Code for the SCOC Taskforce 2026 (like DESC delegate)

## Please generate the conda environment lsdb_env_py313 using the environment.yaml file provided
## Skykatana mask for WFD, including stellar mask, computed for the Monster stars: footprint_based_i_band_magnitude (is in r band, not i)
The stellar mask covers the stars with G magnitude lower than 14.5 using the rules described in https://arxiv.org/pdf/2512.14848
**Please reconfigure the Dask cluster accordingly your computer**

TODO: run new simulations using it: Footprint.ipynb, needs to download the simulations database from:
wget https://s3df.slac.stanford.edu/data/rubin/sim-data/sims_featureScheduler_runs5.3/maf/summary.h5
## Baseline v5.3.6
wget https://s3df.slac.stanford.edu/data/rubin/sim-data/sims_featureScheduler_runs5.3/baseline/baseline_v5.3.6_10yrs.db

## Dust-shrunk footprint runs (0.120 and 0.080)
wget https://s3df.slac.stanford.edu/data/rubin/sim-data/sims_featureScheduler_runs5.3/shrink_fp/shrink_fp_dust_0.120_v5.3.6_10yrs.db
wget https://s3df.slac.stanford.edu/data/rubin/sim-data/sims_featureScheduler_runs5.3/shrink_fp/shrink_fp_dust_0.080_v5.3.6_10yrs.db


