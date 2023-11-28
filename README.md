# Transfer_Learning

In transfer learning, the knowledge of an already trained machine learning model is applied to a different but related problem.
With transfer learning, we try to exploit what has been learned in one task to improve generalization in another. We transfer the weights that a network has learned at **task A** to a new **task B.**

The general idea is to use the knowledge a model has learned from a task with a lot of available labeled training data in a new task that doesn't have much data. Instead of starting the learning process from scratch, we start with patterns learned from solving a related task.

Transfer learning is mostly used in computer vision and natural language processing tasks like sentiment analysis due to the huge amount of computational power required.

Neural networks usually try to detect edges in the earlier layers, shapes in the middle layer and some task-specific features in the later layers. In transfer learning, the early and middle layers are used and we only retrain the latter layers. It helps leverage the labeled data of the task it was initially trained on.
