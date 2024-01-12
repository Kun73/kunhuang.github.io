---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Preprints
----
'*' indicates equal contributions

+ **Kun Huang**^*, Linli Zhou^* and Shi Pu, [Distributed Random Reshuffling Methods with Improved Convergence](https://arxiv.org/abs/2306.12037), submitted.
  + *In this work, we design two novel decentralized random reshuffling methods, GT-RR and ED-RR. For minimizing smooth objective functions, they not only achieve similar convergence results compared to centralized RR methods but also improve the dependency regarding the network topology compared to the previous works.*

+ **Kun Huang**, Xiao Li and Shi Pu, [Distributed Stochastic Optimization under a General Variance Condition](https://arxiv.org/abs/2301.12677), submitted.
  + *This work establishes the convergence of FedAvg and SCAFFOLD in nonconvex setting using a general variance condition. This also provides an alternative informative measure for characterizing data heterogeneity in federated learning.*

+ **Kun Huang** and Shi Pu, [CEDAS: A Compressed Decentralized Stochastic Gradient Method with Improved Convergence](https://arxiv.org/abs/2301.05872), submitted.
  + *This paper demonstrates that CEDAS achieves the shortest transient time for both smooth strongly convex and smooth nonconvex objective functions with communication compression. In addition, CEDAS is the first compressed distributed stochastic method that does not require additional conditions such bounded second order moment of stochastic gradients or bounded gradient dissimilarity condition.*

Journal Papers
----

+ **Kun Huang**, Xiao Li, Andre Milzarek, Shi Pu and Junwen Qiu, [Distributed Random Reshuffling over Networks](https://arxiv.org/pdf/2112.15287.pdf), IEEE Transactions on Signal Processing, 71:1143-1158, 2023.
  + *In this paper, we design a simple yet powerful decentralized random reshuffling method, D-RR. Similar complexity and convergence guarantees to the centralized random reshuffling method are established. This is the first time that the superiority of RR is shown in decentralized settings.*

+ **Kun Huang** and Shi Pu, [Improving the Transient Times for Distributed Stochastic Gradient Methods](https://ieeexplore.ieee.org/document/9865230), IEEE Transactions on Automatic Control, 68(7):4127-4142, 2023.
  + *In this paper, we demonstrates that EDAS achieves the shortest transient time for smooth strongly convex objective functions.*

+ Yiwei Liao,  Zhuorui Li, **Kun Huang** and Shi Pu, [A Compressed Gradient Tracking Method for Decentralized Optimization with Linear Convergence](https://ieeexplore.ieee.org/abstract/document/9789732), IEEE Transactions on Automatic Control, 67(10):5622-5629, 2022.
  + *We propose a compressed gradient tracking method, termed C-GT, and show it enjoys linear convergence rate for minimizing smooth strongly convex objective functions.*
