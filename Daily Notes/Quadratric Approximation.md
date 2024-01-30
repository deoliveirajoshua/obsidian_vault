
Similar to a [[Taylor Series]]:
For a given $f$ so long as $f$ is [[differentiable]],

$f(x, y, \ldots) \approx f(x_{0}, y_{0},\ldots)+\nabla f(x_{0}, y_{0},\ldots)⋅(x−x_{0}​,y−y_{0}​,\dots)+ \frac{1}{2}(x−x_{0}​)^TH(x−x_{0}) + \dots$

Approximates $f$ using the point $(x_{0}, y_{0},\dots)$, where $\nabla$ is the [[gradient]] and $H$ is the [[Hessian]] [[matrix]] of $f$.

When we don't have access to the closed for of the [[Hessian]] of $f$, we can approximate the Taylor series locally using a quadratic approximation:

$q(\mathbf{x})= f(\mathbf{x}) + \nabla f(x_{0})^T(x-x_{0}) + \frac{1}{2}(\mathbf{x}-x_{0})^TH(x_{0})(\mathbf{x}-x_{0})$

Then, $q(\mathbf{x})$ approximates $f$ locally in the neighborhood of $x_{0}$

When $f$ is a vector function, then we substitute the [[gradient]] for the [[Jacobian]], 

$f(x, y, \ldots) \approx f(x_{0}, y_{0},\ldots)+ \mathbf{J}(x_{0}, y_{0},\ldots)⋅(x−x_{0}​,y−y_{0}​,\dots)+ \frac{1}{2}(x−x_{0}​)^TH(x−x_{0}) + \dots$

$q(\mathbf{x})= f(\mathbf{x}) + \mathbf{J}(x_{0})^T(x-x_{0}) + \frac{1}{2}(\mathbf{x}-x_{0})^TH(x_{0})(\mathbf{x}-x_{0})$
___

