## CH 6: Kernel Smoothing Methods

why kernel smoothing method

KNN average goal, idea and feature
KNN's problem and how to improve it

kernel width (and the form in KNN)
effect of  $\lambda$ (too small or too large)

problem of KNN average and why, where can it happens
how to solve it and advantages compared to historical methods
**linear regression matrix form conversion**
what was call equivalent kernel and why
how to further improve it, pros and cons
suggestions

what does $\lambda$ represent and how to select it

feature of kernel function
notable things for multidimensional kernel
difficulties in high dimensional cases
can local weighted regression be used in high dim case
suggestion of  visualization in three-dim case

how to add structures (priority) to the kernel

where can localization be used
application in local likelihood, glm
how to achieve this in logistic regression and pros
why not directly smoothing the binary response
what is the GAM's priority

apply kernel density to classification
should we fit class density well? What is the suggestion
why Naïve Bayes "naïve"
why is it usually better than more sophisticated alternatives
relationship between Naïve Bayes and generalized additive models

basis functions always show local behavior
what is radial basis and how to solve it
assumptions in radial basis and improvements
why Radial so important

computation cost

---

## SAS
data preprocessing step categories
how to explore the data
3 ways

- data modification
- dimension reduction
	- feature extraction pros and cons
	- how does variable clustering/selection work
- unsupervised learning

what should pay attention in exploring results

---


## CH 9

why linear regression fails in many situations
how many ways to add nonlinearity
idea of improvement from GLM to GAM
pros of GAM's design
exp. family -> GLM -> GAM
what if some variable are categorical
various froms of GAM
how to get GAM models solved
what is the assumption when solving GAM
what if input matrix is singular
how to apply backfitting



不同的设计一般有优点有缺点，要学会先猜一猜然后实验就有了方向

- 代码目的，思考自己怎么做
- API 思维

如何知道代码在干嘛：

- 追踪小样本
- debug
- print/log

