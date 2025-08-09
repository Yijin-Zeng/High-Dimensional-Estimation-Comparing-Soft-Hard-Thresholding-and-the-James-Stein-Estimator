In this project, we consider the following high-dimensional estimation problem. Suppose $Z^n = (Z_1,\dots,Z_n)$, where 

$Z_i = \theta_i + \sigma_n\epsilon_i, i = 1,\dots,n,$

with $\theta^n = (\theta_1,\dots,\theta_n) \in \mathbb{R}^n$ a vector of unknown parameters, $\epsilon_1,\dots,\epsilon_n \mathop{\sim}\limits^{i.i.d} \mathcal{N}(0,1)$ random variables and $\sigma_n = \sigma$ a known parameter. We want to perform inference on $\theta^n$ with observed $z^n = (z_1, \dots, z_n)$, which is a realisation of $Z^n$, as well as evaluate our inference results in a reasonable way.

We investigate this problem in more depth theoretically, as well as empirically by simulations, using three estimating methods: the soft threshold estimator, the hard threshold estimator and the James-Stein estimator.
