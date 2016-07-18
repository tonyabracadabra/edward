A library for probabilistic modeling, inference, and criticism.
---------------------------------------------------------------

Edward is a Python library for probabilistic modeling, inference, and
criticism. It is a testbed for fast experimentation and research with
probabilistic models, ranging from classical hierarchical models on
small data sets to complex deep probabilistic models on large data sets.
Edward fuses three fields: Bayesian statistics and machine learning,
deep learning, and probabilistic programming.

It supports **modeling languages** including

-   [TensorFlow](https://www.tensorflow.org) (with neural networks via
    [Keras](http://keras.io), [TensorFlow
    Slim](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/slim),
    or [Pretty Tensor](https://github.com/google/prettytensor))

-   [Stan](http://mc-stan.org)

-   [PyMC3](http://pymc-devs.github.io/pymc3/)

-   Python, through [NumPy/SciPy](http://scipy.org/)

It supports **inference** via

-   Variational inference

    -   Black box variational inference

    -   Stochastic variational inference

    -   Variational auto-encoders

    -   Inclusive KL divergence: $\text{KL}(p\|q)$

-   Marginal posterior optimization (empirical Bayes, marginal
    maximum likelihood)

    -   Variational EM

-   Maximum a posteriori estimation (penalized maximum likelihood)

    -   Laplace approximation

It supports **criticism** of the model and inference via

-   Point-based evaluations

-   Posterior predictive checks

Edward is built on top of [TensorFlow](https://www.tensorflow.org),
enabling features such as computational graphs, distributed training,
CPU/GPU integration, automatic differentiation, and visualization with
TensorBoard.

### Authors

Edward is led by [Dustin Tran](http://dustintran.com) with guidance by
[David Blei](http://www.cs.columbia.edu/~blei/). The other developers
are

-   [Adji Dieng](http://stat.columbia.edu/~diengadji/)

-   [Alp Kucukelbir](http://www.proditus.com/)

-   [Dawen Liang](http://www.ee.columbia.edu/~dliang/)

-   [Maja Rudolph](http://maja-rita-rudolph.com/)

We are open to collaboration, and welcome researchers and developers to
contribute. Check out the [Github
issues](https://github.com/blei-lab/edward/issues) for feature requests
and other software problems. For broader research challenges, shoot one
of us an e-mail.

Edward has benefited enormously from the helpful feedback and advice of
many individuals: Jaan Altosaar, Eugene Brevdo, Allison Chaney, Matt
Hoffman, Kevin Murphy, Rajesh Ranganath, Rif Saurous, and other members
of the Blei Lab, Google Brain, and Google Research.

### Citation

We appreciate citations for Edward because it lets us find out how
people have been using the library and it motivates further work.

> Dustin Tran, Adji Dieng, Alp Kucukelbir, Dawen Liang, Maja Rudolph,
> and David M. Blei. 2016. *Edward: A library for probabilistic
> modeling, inference, and criticism.* http://edwardlib.org

``` {class="JSON"}
@misc{tran2016edward,
    author = {Dustin Tran and Adji Dieng and Alp Kucukelbir and Dawen Liang and Maja Rudolph and David M. Blei},
    title = {{Edward: A library for probabilistic modeling, inference, and criticism}},
    year = {2016},
    url = {http://edwardlib.org}
}
```