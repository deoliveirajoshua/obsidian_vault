
For a scalar function $f(x, y, \dots, z) \to \mathbb{R}$, the Hessian matrix is:
$$
H(x, y, \dots, z) = \begin{pmatrix}
\frac{\delta f}{x^2} & \frac{\delta f}{xy} & \dots & \frac{\delta f}{xz}\\
\frac{\delta f}{yx} & \frac{\delta f}{y^2} & \dots & \frac{\delta f}{yz}\\   \vdots & \vdots & \ddots & \vdots\\
\frac{\delta f}{zx} & \frac{\delta f}{zy} & \dots & \frac{\delta f}{z^2}\\
\end{pmatrix}
$$
Which is also $H(\mathbf{x}) = \mathbf{J}(\nabla f(\mathbf{x}))$

When dealing with a vector-valued function $f(x, y, \dots, z) \to \mathbb{R}^{k}$, then the Hessian is a 3rd-order tensor: 

$\mathbf{H}(\mathbf{f}) = (\mathbf{H}(f_{1}), \mathbf{H}(f_{2}), \dots, \mathbf{H}(f_{k}) )$

$\mathbf{H}_{x}^{\mathbf{f}}(\mathbf{x}; \theta)$
$\mathbf{H}_{\theta}^{\mathbf{f}}(\mathbf{x}; \theta)$

$\mathbf{J}_{x}^{\mathbf{f}}(\mathbf{x}; \theta)$
$\mathbf{J}_{\theta}^{\mathbf{f}}(\mathbf{x}; \theta)$