<div style="text-align: center;">

<h1>Contrastive Learning on Graph</h1>

</div>

In this study, we implemented a one-stage supervised contrastive learning framework that employs contrastive loss as a regularization term to enhance the generalization capabilities of supervised learning. The loss objective of our model comprises two components: the supervised loss derived from the original graph $G$ and its training labels, and the contrastive loss generated from embeddings of two distinct augmented views, $\tilde{G}_1$ and 
$\tilde{G}_2$. The balance between these two losses is controlled by the parameter $\lambda$. This approach demonstrated a significant advantage over traditional $l_2$ decay.

We conducted extensive experiments to identify the optimal $\lambda$ values for seven different GNNs encoders. The experimental results show that most models benefit from incorporating contrastive loss, underscoring its effectiveness in enhancing learning dynamics and improving model performance. This study highlights the potential of integrating supervised contrastive learning into a one-stage training framework, which not only achieves superior results but also streamlines the hyperparameter tuning process.


Find out more about our data here: [Data](data/README.md)

View our presentation here: [Presentation](Flight_Delay_Prediction_Presentation.pdf)
*note: this presentation was given before our project was finished and does not include the final results of our models.*

View our final report here: [Final Report](Flight_Delay_Prediction_Report.pdf)
