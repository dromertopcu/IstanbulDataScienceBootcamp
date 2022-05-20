
|                            |                   **Discriminative model**                   |                     **Generative model**                     |
| :------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|          **Goal**          |                Directly estimate $P(y\|x)$                 |       Estimate  $P(x\|y)$ to then deduce $P(y\|x)$       |
|     **What's learned**     |                      Decision boundary                       |            Probability distributions of the data             |
|      **Illustration**      | ![](https://stanford.edu/~shervine/teaching/cs-229/illustrations/discriminative-model.png?767b34c21d43a4fd8b59683578e132f9) | ![](https://stanford.edu/~shervine/teaching/cs-229/illustrations/generative-model.png?df0642cec6e99ac162cd4848d26f41c3 ) |
|        **Examples**        |     Regressions, SVMs, Decision Trees, Nearest Neighbors     |                    GDA, Naive Bayes, GANs                    |
|        **Strength**        |                        Smaller error                         |                       Converges faster                       |
|     **Explainability**     |                  Low to none (Black boxes)                   |                Express complex relationships                 |
|         **Error**          |                   Smaller asymptotic error                   |                   Higher asymptotic error                    |
| **Application(Use cases)** | * Supervised machine learning<br /> * Discriminate between different kinds of data instances<br/>e.g.- Text Classification. | * Unsupervised machine learning<br />* Generate new data instances.<br/>e.g.- Predict next word in a sequence. |
|   **Model Performance**    | * Measured by misclassification rate.<br/>* These models are robust against outliers and poor modeling. | * Measured by likelihood.<br/>* Outliers affect the distribution significantly and<br/> results in bad model accuracy.<br/>* With correct distribution, more accurate. |
|     **Training Time**      | Take more time to train on substantial amount of training samples. | Need less data to train as these models make stronger assumptions of conditional independence |
|     **Training Data**      | Need sufficient training data for better generalization performance. | Can work with missing data and generalize well |


