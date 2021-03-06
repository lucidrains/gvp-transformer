<img src="./gvp-transformer.png" width="500px"></img>

## GVP Transformer (wip)

Implementation of the GVP-Transformer, which was used in the paper <a href="https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1">Learning inverse folding from millions of predicted structures</a> for de novo protein design alongside Alphafold2. The base neural network consists of an invariant geometric network, <a href="https://github.com/lucidrains/geometric-vector-perceptron">GVP</a>, combined with an encoder / decoder transformer.

It will also offer the tools for enabling <a href="https://arxiv.org/abs/2103.10360">autoregressive infilling</a>

## Citations

```bibtex
@article {Hsu2022.04.10.487779,
    author  = {Hsu, Chloe and Verkuil, Robert and Liu, Jason and Lin, Zeming and Hie, Brian and Sercu, Tom and Lerer, Adam and Rives, Alexander},
    title   = {Learning inverse folding from millions of predicted structures},
    elocation-id = {2022.04.10.487779},
    year    = {2022},
    doi     = {10.1101/2022.04.10.487779},
    publisher = {Cold Spring Harbor Laboratory},
    URL     = {https://www.biorxiv.org/content/early/2022/04/10/2022.04.10.487779},
    eprint  = {https://www.biorxiv.org/content/early/2022/04/10/2022.04.10.487779.full.pdf},
    journal = {bioRxiv}
}
```
