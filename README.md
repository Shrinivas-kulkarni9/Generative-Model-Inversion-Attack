# Recovering face images by inverting a (possibly differentially private) face recognition classifier 

This repo takes inspiration from a very interesting paper https://arxiv.org/abs/1911.07135
Since the paper does not provide the code, there are quite a few changes done while implementation, run-time decisions, without compromising on te results.
This is personally one of my fav projects, as I was able to successfully launch an attack on a face recognition classifier and recover face images used in training. This surpasses even Differential Privacy.

The caveat is, I did not store the many notebooks I created properly, as I worked without structure (things we don't pay attention to when inexperienced). I have uploaded two notebooks, one more complete than the other, while the other has images from the run.

You will find two reports -
 1. Differential Privacy - Analysis of DP and it's caveats
 2. ModelInversionAttackExplained - Explains the whole pipeline, the theory and the results of this model inversion attack
