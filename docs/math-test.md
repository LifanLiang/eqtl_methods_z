# Math test

Unnumbered (no environment):

$$
y_{gi} = \mu_g + \epsilon_{gi}
$$

Numbered:

$$
\begin{equation}
\label{eq:lmm}
y_{gi} = X_i\beta_g + Z_i u_g + \epsilon_{gi}
\end{equation}
$$

Multi-line, each numbered separately:

$$
\begin{align}
\hat{\beta}_g &\sim \mathcal{N}(\beta_g, V_g) \label{eq:mash1} \\
\beta_g &\sim \sum_k \pi_k \mathcal{N}(0, \omega_k U_k) \label{eq:mash2}
\end{align}
$$

Reference check: the mixed model is $\eqref{eq:lmm}$, the prior is $\eqref{eq:mash2}$.

Inline check: the variance component $\sigma^2_u$ renders inline.