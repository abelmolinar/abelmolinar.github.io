---
title: "Resources to Learn Control Theory"
layout: "simple"
---
{{< katex >}}


Learning about control theory requires rigorous math but also practical problem solving. Here are some very helpful resources.

- [Practical Analysis in One Variable](https://www.researchgate.net/publication/31753506_Practical_Analysis_in_One_Variable_D_Estep)
  - An incredibly eye-opening book that follows a problem &rarr; solution &rarr; theory style: a **problem** is analyzed, a **solution** derived, and **theory** constructed. For example, Donald Estep's treatment of sequences as approximations to solve a problem (approximating \(\sqrt{2}\)), deriving the bisection algorithm, then using Lipschitz continuity as a property of functions that solve these approximation problems more generally. Excellent motivation without sacrificing rigor and while avoiding fait accompli style mathematics where definitions are merely given.

- [Model Reference Adaptive Control](https://link.springer.com/book/10.1007/978-3-319-56393-0)
  - An example and practice rich resource put together by Nhan T. Nguyen. It offers a concise look at nonlinear control, mathematical preliminaries, and MRAC. The general workflow for adaptive control and resulting problems are shown, not merely stated, and the math is well motivated. 

- [Kalman and Bayesian Filtering Jupyter Notebook](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python)
  - Roger Labbe created a jupyter notebook that has concise examples along with good motivation for a topic that can be very esoteric. The Jupyter notebook does not have in depth mathematical derivations or theory, it is focused on practical explanations and implementations of concepts learned in Python. This work helped me get a grip on why anyone would care about state estimation and what the implementation looks like through examples.

- [Optimal State Estimation by Dan Simon](https://academic.csuohio.edu/simon-daniel/state-estimation/)
  - Dr. Dan Simon's book on state estimation is a crucial and in-depth resource for the theoretical aspects of state estimation, especially Kalman filtering. The book includes the necessary mathematical prerequisites and derivations to gain a complete picture of the theoretical parts of state estimation. The book is especially helpful while taking a relevant course or participating in a reading group.

- [ECE5530: Multivariable Control Systems II](http://mocha-java.uccs.edu/ECE5530/index.html)
  - Taught by Dr. Gregory Plett from the University of Colorado at Colorado Springs, this has proven to be a great theoretical resource for learning estimation and control. Dr. Plett's notes on the linear quadratic estimator (Kalman Filter), linear quadratic regulator, and linear quadratic Gaussian are excellent resources for people who already have a good starting point in the relevant statistical/math topics.

- [Optimal Control Quadratic Methods by Anderson and Moore](https://dl.acm.org/doi/book/10.5555/79089?__cf_chl_tk=PZt97f2UYxnDDQ3TEKDuuPXEp82qCx7BDIeZYVEoYeY-1794722740-1.0.1.1-MP_IltSVCZxdn6BWetJhq_1zweu_ucqwhrLZI.A.rb0)
  - This is a great book to learn about linear optimal control and especially the linear quadratic regulator. The authors introduce the Principle of Optimality and the Hamilton Jacobi Equations, which are very important in control optimization, and applying them to the LQR, one of the most simple and elegant optimal controllers.

- [Frequency Domain for Beginners](https://www.youtube.com/@justinruths9590)
  - Dr. Justin Ruths from the University of Texas at Dallas has very accessible intro to frequency domain lectures on his YouTube channel under the MECH 4310 playlist. Especially useful to understand Nyquist criterion theory.

