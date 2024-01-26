## Authors:

## Venue Published: 

## Year Published:

## Date YOU Found the Paper: 

## Link: [put link here...](...and over here in pararenthesis)

## Code: [put link here if available](otherwise, write "N/A")
## Topic Keywords:

___
## Summary

> [!QUOTE]- Abstract
> Recent work has shown local convergence of GAN training for absolutely continuous data and generator distributions. In this paper, we show that the requirement of absolute continuity is necessary: we describe a simple yet prototypical counterexample showing that in the more realistic case of distributions that are not absolutely continuous, unregularized GAN training is not always convergent. Furthermore, we discuss regularization strategies that were recently proposed to stabilize GAN training. Our analysis shows that GAN training with instance noise or zero-centered gradient penalties converges. On the other hand, we show that Wasserstein-GANs and WGAN-GP with a finite number of discriminator updates per generator update do not always converge to the equilibrium point. We discuss these results, leading us to a new explanation for the stability problems of GAN training. Based on our analysis, we extend our convergence results to more general GANs and prove local convergence for simplified gradient penalties even if the generator and data distribution lie on lower dimensional manifolds. We find these penalties to work well in practice and use them to learn high-resolution generative image models for a variety of datasets with little hyperparameter tuning.

> [!SUMMARY] The Point™
> Supwer quick summary in your own words

# Paper Recommendation:
*Choose One, delete the rest*
*Would NOT recommend for someone else to read if asked*
*Would recommend for someone else to read if asked*

> [!model]  Reading Difficulty: *Medium*
 *(Understood it in 3-5 passes)* 

> [!warning]  Math Difficulty: *Challenging* 
> *(Could explain conceptually, but couldn't self-derive or explain technically if questioned.)*


#### Paper Type:
*Choose any that apply, delete the rest:*
*Survey w/ No Implementation (Aggregates and summarizes previous work)*
*Survey w/ Implementation (Aggregates, summarizes, and experiments on previous work)*
*Dataset (Created a new dataset for benchmarking, experiments for a domain / task)*
*Architecture (Proposes a new model)*
*Loss Function (Proposed a new loss function)*
*Optimization (Proposed a new way of conducting optimization)*
*System (Proposes either a new system, or new combination of components)*
*Applied (We took solution X from domain Y, and showed it also works in domain Z)*
*Theoretical (We proved phenomenon X always holds under assumptions under Y and Z)*

> [!info]  Paper Impact Quality:
>*Choose One, delete the rest:*
*Niche (Provides a novel contribution, but only applicable to a highly specific topic)*
*Impactful (Provides a novel contribution, and has modest impact to the broader community)*
*Masterful (Pushes an existing topic of research significantly forward, very applicable to the broader community)*
*Seminal (Landmark paper in the field, burgeons a completely new topic)*

> [!info] Reproducibility Quality: Simple
*(Had to replicate from scratch, but did fairly quickly)*


___
## Paper Perception:

### 1. **What did the authors try to accomplish?**
### 2. **What were the key elements of the approach?**

### 3. What were the most important things you learned?

### 4. **What can you use for your own research?**

### 5. **What other references do you want to follow?**
### 6. **What was the most challenging part to understand?**

### 7. **What helped improve your understanding the quickest?** 
**(ie. a figure, a subsection, etc.)**

___
### Questions You Still Have About The Paper


### Additional Comments 

$$
 \iint \nabla_{\theta}f(x) dx
$$

```python
x = 5

def foo(y: int=3) -> str:  
```