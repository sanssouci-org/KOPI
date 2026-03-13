# KOPI: False discovery proportion control for aggregated knockoffs

This repository contains the code to reproduce simulations of the KOPI paper: 

> Blain, A., Thirion, B., Grisel, O., & Neuvial, P. (2023). False discovery proportion control for aggregated knockoffs. *Advances in Neural Information Processing Systems*, 36, 78193-78204.
> https://arxiv.org/pdf/2310.10373

To compute simulation results, run successively:

```{python}
generate_results_n.py
generate_results_rho.py
generate_results_snr.py
generate_results_sparsity.py
```

The results will be saved in .npy format in subdictories of 'figures'.

Then, run either scripts/figure1.py or scripts/figure2.py to reproduce the Figures of the paper.
