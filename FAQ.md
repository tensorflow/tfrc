# Frequently Asked Questions

## How does the TFRC program work?

Anyone can apply for the program by signing up at
[g.co/tfrc](https://g.co/tfrc). Invitations are sent out to approved applicants
on a rolling basis. When an invitation is accepted, free Cloud TPU quota is
granted to the invitee’s Google Cloud Platform project on a temporary basis and
is ready to use within minutes.

## Is it really free?

While Cloud TPUs are free to use for TFRC participants, other GCP services are
not. Participants can expect to utilize small VM instances (n1-standard-2) to
drive their TPUs as well as Google Cloud Storage (GCS) buckets to hold training
data. These costs are generally minimal. If you have questions about
TFRC-related charges please <a href="mailto:tfrc-support@google.com">contact us</a>.

## I need time to prepare, can I defer my free TPU start date?

Once you've been accepted to the TFRC program, the choice of when to start your
free TPU access is up to you, subject to availability. Whenever you are ready,
simply follow the instructions in the introductory email.

## I’m ready - where do I start?

You can access Cloud TPUs for free in your browser using Google Colab, a Jupyter
notebook environment that requires no setup to use.

To get started right away, try one of these TPU-compatible notebook examples:

-   [Hello, TPU in Colab](https://colab.research.google.com/notebooks/tpu.ipynb)
-   [Fashion MNIST with Keras and TPUs](https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/fashion_mnist.ipynb)
-   [Predict Shakespeare with Cloud TPUs and Keras](https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/shakespeare_with_tpu_and_keras.ipynb)
-   [End-to-end Keras example (including serving)](https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/keras_mnist_tpu.ipynb)
-   [AdaNet on Cloud TPUs](https://colab.research.google.com/github/tensorflow/adanet/blob/master/adanet/examples/tutorials/adanet_tpu.ipynb)
-   [BERT on Cloud TPUs](https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/bert_finetuning_with_cloud_tpus.ipynb)
    (state-of-the-art NLP: [paper](https://arxiv.org/abs/1810.04805),
    [code](https://github.com/google-research/bert))

To learn more about Cloud TPUs, check out the following videos:

-   [Effective Machine Learning with Cloud TPUs](https://www.youtube.com/watch?v=zEOtG-ChmZE)
    (Google I/O ‘18)
-   [Transforming Your Business with Cloud TPUs](https://www.youtube.com/watch?v=jgqUg-0ojq8)
    (Cloud Next '18)
-   [Programming ML Supercomputers: A Deep Dive on Cloud TPUs](https://www.youtube.com/watch?v=qXeGjmJQQrw)
    (Cloud Next '18)
-   [Minigo: Building a Go AI with Kubernetes and TensorFlow](https://www.youtube.com/watch?v=Qra8Aqxu_fo)
    (Cloud Next '18)

We also recommend browsing the
[official Cloud TPU documentation](https://cloud.google.com/tpu/docs/), and
especially the [QuickStart guide](https://cloud.google.com/tpu/docs/quickstart),
when you are ready to get started.

## Where can I find sample TPU code?

The [Cloud TPU](https://github.com/tensorflow/tpu/tree/master/models) and
[Google Cloud Platform](https://github.com/GoogleCloudPlatform/cloudml-samples/tree/master/tpu)
repos each contain a variety of sample models that can help you get started with
Cloud TPUs. We'd recommend following one of the
[Cloud TPU tutorials](https://cloud.google.com/tpu/docs/tutorials) to get
familiar with these models.

## Can TFRC quota be used with [Cloud ML Engine](https://cloud.google.com/ml-engine/)?

Cloud TPU quota granted under the TFRC program is not compatible with CMLE-based
workflows; we recommend using the [GCE tutorials](https://cloud.google.com/tpu/docs/)
to get started instead.

## Where can I get technical help?

Here are a few helpful Cloud TPU resources:

-   [Tools](https://cloud.google.com/tpu/docs/cloud-tpu-tools)
-   [Performance Guide](https://cloud.google.com/tpu/docs/performance-guide)
-   [Troubleshooting](https://cloud.google.com/tpu/docs/troubleshooting)
-   [Stack Overflow](https://stackoverflow.com/questions/tagged/google-cloud-tpu)
-   [GitHub](https://github.com/tensorflow/tpu)

## Can I have more?

Our goal is to accelerate open machine learning research. If you have a proposal
for using larger amounts of Cloud TPU capacity please
<a href="mailto:tfrc-support@google.com">contact us</a> with additional information
about your project’s goals, needs, and timeline. For example, the open source
[MiniGo](https://github.com/tensorflow/minigo) project
[successfully used 640 Cloud TPUs simultaneously via GKE](https://cloud.google.com/blog/products/ai-machine-learning/cloud-tpus-in-kubernetes-engine-powering-minigo-are-now-available-in-beta).

## I have another question that isn’t covered here...

Please <a href="mailto:tfrc-support@google.com">contact us</a> - we’ll be happy to help!
