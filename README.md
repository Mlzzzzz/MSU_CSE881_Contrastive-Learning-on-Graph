<div style="text-align: center;">

<h1>Contrastive Learning on Graph</h1>

</div>

In this study, we implemented a one-stage supervised contrastive learning framework that employs contrastive loss as a regularization term to enhance the generalization capabilities of supervised learning. The loss objective of our model comprises two components: the supervised loss derived from the original graph $G$ and its training labels, and the contrastive loss generated from embeddings of two distinct augmented views, $\tilde{G}_1$ and 
$\tilde{G}_2$. The balance between these two losses is controlled by the parameter $\lambda$. This approach demonstrated a significant advantage over traditional $l_2$ decay.

We conducted extensive experiments to identify the optimal $\lambda$ values for seven different GNNs encoders. The experimental results show that most models benefit from incorporating contrastive loss, underscoring its effectiveness in enhancing learning dynamics and improving model performance. This study highlights the potential of integrating supervised contrastive learning into a one-stage training framework, which not only achieves superior results but also streamlines the hyperparameter tuning process.

The project is based on [PyGCL](https://github.com/PyGCL/PyGCL)(Zhu, Yanqiao et al. “An Empirical Study of Graph Contrastive Learning.” ArXiv abs/2109.01116 (2021): n. pag.) library. Specifically, We have adopted and applied the [GRACE](GRACE.ipynb) (Y. Zhu et al., Deep Graph Contrastive Representation Learning, GRL+@ICML, 2020) and [SupCON](SupCON.ipynb) (P. Khosla et al., Supervised Contrastive Learning, NeurIPS, 2020) frameworks to our graph representative learning task. 

Find out more about our data here: [Data](data/README.md)

View our final report here: [Final Report](CSE_881_PROJECT_REPORT.pdf)
