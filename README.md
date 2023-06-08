# GraphDAC: A Graph-Analytic Approach to Dynamic Airspace Configuration

## Paper Abstract：
The current National Airspace System (NAS) is
reaching capacity due to increased air traffic, and is based
on outdated pre-tactical planning. This study proposes a more
dynamic airspace configuration (DAC) approach that could
increase throughput and accommodate fluctuating traffic, ideal
for emergencies. The proposed approach constructs the airspace
as a constraints-embedded graph, compresses its dimensions, and
applies a spectral clustering-enabled adaptive algorithm to gener-
ate collaborative airport groups and evenly distribute workloads
among them. Under various traffic conditions, our experiments
demonstrate a 50% reduction in workload imbalances. This
research could ultimately form the basis for a recommendation
system for optimized airspace configuration.

## Data source:
Flight Delays and Cancellations were published by The U.S.
Bureau of Transportation in 2015. This dataset is pulished on Kaggle: https://www.kaggle.com/datasets/usdot/flight-delays

To visulize the results, the FL airports location are inside the folder 'USA_Counties'. 

## Model and Experiments:
See file 'fl_cluster_color_balance_refined.py'
