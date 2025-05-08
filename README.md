# Spam-email-classification
This project aims to automatically classify emails as spam or not spam using machine learning. The classification is performed using Logistic Regression, a robust and interpretable algorithm for binary outcomes. The dataset consists of labeled email messages, enabling supervised learning.

A key step is text preprocessing and vectorization. Raw email text is transformed into numerical features using TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer, which captures the importance of words relative to individual messages and the entire dataset. This approach helps reduce the influence of common but uninformative words while emphasizing discriminative terms.

The model is trained using logistic regression, which estimates the probability of an email being spam by applying a sigmoid function to a linear combination of input features. Logistic regression is particularly effective when the goal is to produce a clear, interpretable decision boundary based on feature weights.

The model’s performance is evaluated using accuracy_score, which measures the proportion of correctly classified emails. This metric offers a straightforward view of effectiveness, though additional metrics (like precision and recall) may be considered for imbalanced datasets.

This project highlights how traditional machine learning algorithms, combined with natural language processing techniques, can be used to tackle real-world classification problems such as spam detection.
