# Learning and Exploiting Deep Tractable Probabilistic Models
Latex sources of my presentation "Learning and Exploiting Deep Tractable Probabilistic Models" at TAO team @ INRIA - Université Paris-Sud  on December 19th 2017

## Abstract
Making use and sense of the _unlabeled data_ that surround us is one of the challenges we have to face as scientists, data science practitioners, or decision makers. Fitting a probabilistic model in order to recover the probability distribution that generated the data, i.e. to perform *density estimation*, is one of the king tasks in Machine Learning.
Once one of these estimators has been learned, one exploits it to perform *inference*, that is reasoning about the possible and uncertain configurations of our world.

_**Tractable probabilistic models**_ (**TPMs**) allow several classes of probabilistic queries to be computed in a feasible way, i.e., in polynomial time w.r.t. the number of the random variables considered.
We look at TPMs as tools to enable _**automating density estimation**_.
In this talk, the focus is on _**Sum-Product Networks**_ (**SPNs**), recently proposed TPMs that are expressive enough to model complex probability distributions, offer tractable inference for a wide range of query types, and can be learned efficiently in an unsupervised way. Moreover one can _learn one SPN only once and exploiting it several times later_, by reusing it both for answering several inference query types ad libitum, and to employ it for predictive tasks, as well.

In particular, we show how SPNs can be extended and learned on mixed domains-comprising continuous, discrete and categorical features-without requiring users to specify a parametric form the random variables involved nor for their interactions. These _**Mixed SPNs**_ still allow a wide range of queries to be answered in a tractable time, overcoming many of the limitations that classical mixed probabilistic models face and ultimately paving the way to automating density estimation.

As an additional way to exploit SPNs, we present how such TPMs can be naturally _**extended towards Representation Learning**_ by equipping them with encoding and decoding routines to operate on both categorical and continuous embeddings.
By exploiting MPE inference, one can obtain rich part-based representations that are proven to be highly effective when employed to encode the input, output features or both in a Multi-Label Classification scenario.


