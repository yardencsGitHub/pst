This software was used to implement probabilistic suffix trees (Ron, Singer and Tishby 1996) for the paper "Long-range order in canary song" by Markowitz et al. (PLoS Comp Bio 2013). Data must be formatted as a cell array of characters.  Start by building the transition matrices with `pst_build_trans.m` and pass the resulting output to `pst_learn.m`.  See the function help for further guidance.