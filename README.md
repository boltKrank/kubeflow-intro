# kubeflow-intro

Intro to Kubeflow and its related concepts

## What is Kubeflow and why ?

Kubeflow is an open-source project designed to exploit the advantages of k8s in the world of machine learning (ML). Based on [TensorFlow](https://www.tensorflow.org/tfx/)

### Kubeflow architecture

![Kubeflow architecture](/images/kubeflow-overview-platform-diagram.svg)

As you can see Kubeflow itself doesn't do the machine learning, but it provides a framework in which to run it on k8s. For this, I'll be using [PyTorch](https://pytorch.org) to demonstrate.

### Current issues:

- Doing this on a Windows machine isn't worth the effort. Linux or MacOS is recommended.