# deep_markov_model
Some additional modifications to Pyro's example DMM (see: https://github.com/pyro-ppl/pyro/blob/dev/examples/dmm.py)

Architecture from paper [Structured Inference Networks for Nonlinear State Space Models](https://arxiv.org/abs/1609.09869). Implemented with actions (see Section 5 of paper) and Soft-HGR [An Efficient Approach to Informative Feature Extraction from Multimodal Data](https://arxiv.org/pdf/1811.08979.pdf). Currently running for polyphonic music data (using multimodal datastreams would be desirable for the latter).

### Requirements
- Pyro == 1.4.0: _pip install pyro-ppl_
- Pytorch == 1.5.0
- numpy
