# Autoencoder Case Study

## Motivation

This study started from an unexpected issue observed in an image denoising example using autoencoder:   
the reconstructed images contained noticeable **black dot artifacts**.

## Goal

The goal is to understand the cause of this phenomenon by analyzing:

- the bottleneck size (`engpass`)
- the choice of activation functions  

## Conclusion

The black dot artifacts are caused by the choice of activation functions rather than the bottleneck size.

The full training process and results can be found in `autoencoder.ipynb`.
