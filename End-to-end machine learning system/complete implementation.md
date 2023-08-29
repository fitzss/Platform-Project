Following and implementing myself the project from the last chapter of @TerryTangYuan book "Distributed Machine Machine Patterns".

I will be implementing an end-to-end machine learning system by with an architecture designed by Terry. Also doing a complete implementation to each of the components that incorporate the patterns described in the book. Using several popular frameworks and cutting-edge technologies, particularly TensorFlow, Kubernetes, Kubeflow, Docker, and Argo Workflows. All toosl used to build different components of a distributed machine learning workflows.


Summary
The data ingestion component implements a distributed input pipeline for the Fashion-MNIST dataset with TensorFlow that would make it easy to integrate with distributed model training.
Machine learning models and distributed model training logic can be defined in TensorFlow, and then executed in a distributed fashion in the Kubernetes cluster with the help of Kubeflow.
Both the single-instance model server and the replicated model servers can be implemented via KServe. The autoscaling functionality of KServe can automatically create additional model serving pods to handle the increasing number of model serving requests.
We implemented our end-to-end workflow that includes all the components of our system in Argo Workflows and were able to leverage step memoization to avoid time-consuming and redundant data ingestion step.
