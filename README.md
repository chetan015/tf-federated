# Tensorflow Federated
## Experiments with Tensorflow Federated

TensorFlow Federated (TFF) is an open-source framework for machine learning and other computations on decentralized data. Federated Learning (FL) is an approach to machine learning where a shared global model is trained across many participating clients that keep their training data locally. TFF enables developers to declaratively express federated computations, so they could be deployed to diverse runtime environments.

TFF’s interfaces are organized in two layers:
* Federated Learning (FL) API: Set of high-level interfaces allowing developers to apply federated training to existing TF models
* Federated Core (FC) API:Lower-level interfaces for custom/novel federated algorithms, combining TensorFlow with distributed communication operators.  
  
Source:[https://www.tensorflow.org/federated](https://www.tensorflow.org/federated)

[tffMnist.ipynb](https://github.com/chetan015/tf-federated/blob/master/tffMnist.ipynb) is a walkthrough implementation of the [Federated Learning for Image Classification](https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification) tutorial.
