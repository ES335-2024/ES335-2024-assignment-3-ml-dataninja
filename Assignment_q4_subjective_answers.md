#### $Q.$ Compare performance of MLP trained on MNIST dataset against RF and Logistic Regression model.

#### $Ans.$ The accuracy and F1-score of the MLP model was $95$%, while the accuracy and F1-score of the Random Forest model was $97$% and accuracy and F1-score of the Logistic Regression model was $89$%. 

#### $Q.$ What do you observe? What all digits are commonly confused?

#### $Ans.$ The Random Forest model performed the best, followed by the MLP model and then the Logistic Regression model. The digits that were commonly confused were $4$ and $9$, $7$ and $2$, $3$ and $5$, $8$ and $9$ and $7$ and $9$.

#### $Q.$ On the trained MLP, plot the t-SNE for the output from the layer containing 20 neurons for the 10 digits. Contrast this with the t-SNE for the same layer but for an untrained model. What do you conclude?

#### $Ans.$ The t-SNE plot of the output from the layer containing $20$ neurons for the trained MLP model shows well-separated clusters for each digit. The t-SNE plot of the output from the same layer for an untrained model shows overlapping clusters for each digit. This indicates that the trained model has learned meaningful representations of the data, while the untrained model has not learned anything because the weights are randomly initialized.

#### $Q.$ Now, use the trained MLP to predict on the Fashion-MNIST dataset. What do you observe? How do the embeddings, t-SNE viz for the second layer compare for MNIST and Fashion-MNIST images?

#### $Ans.$ The trained MLP model did not perform well on the Fashion-MNIST dataset. The accuracy and F1-score for the prediction was $5$%. The embeddings for the second layer of the trained MLP model for the MNIST dataset show well-separated clusters, while the embeddings for the second layer of the trained MLP model for the Fashion-MNIST dataset show overlapping clusters. This indicates that the model has learned representations of the MNIST dataset and does not generalize well to the Fashion-MNIST dataset.