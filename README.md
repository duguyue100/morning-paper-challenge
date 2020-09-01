# Morning Paper Challenge

+ 文丞相：“孔曰成仁，孟曰取义，惟其义尽，所以仁至。读圣贤书，所学何事？而今而后，庶几无愧。”
+ 张子：“为天地立心，为生民立命，为往圣继绝学，为万世开太平。”
+ 阳明先生：“当读书做圣人耳。”

## Fourth Morning Paper Challenge

_One Hour, One Paper, Every Morning at 8am, At [here](https://www.google.ch/maps/place/%22Monte+Diggelmann%22+-+vantage+point+in+Irchelpark/@47.3933675,8.5491733,118m/data=!3m1!1e3!4m5!3m4!1s0x0:0x2cb79f95aa652fc3!8m2!3d47.3932358!4d8.5495728?hl=en)._

_This challenge focus on the ICLR 2020 and NeurIPS 2019 proceedings._

![Progress](https://progress-bar.dev/30/?scale=42&title=MPC&width=360&suffix=)

__2020-08-03__: [Your classifier is secretly an energy based model and you should treat it like one ](https://openreview.net/pdf?id=Hkxzx0NtDB) :tada:

__2020-08-04__: [Principled Weight Initialization for Hypernetworks](https://openreview.net/pdf?id=H1lma24tPB) :tada:

__2020-08-05__: [Empirical Studies on the Properties of Linear Regions in Deep Neural Networks](https://openreview.net/pdf?id=SkeFl1HKwr) :tada: I understand the idea and the tool this paper presents, but I lost my interest in reading all the analysis.

__2020-08-06__: [Don't Use Large Mini-batches, Use Local SGD](http://www.openreview.net/pdf?id=B1eyO1BFPr) :tada:

__2020-08-07__: [You Only Train Once: Loss-Conditional Training of Deep Networks](http://www.openreview.net/pdf?id=HyxY6JHKwr) :tada: I like this paper very much, and I would check out the code.

__2020-08-08__: [Smooth markets: A basic mechanism for organizing gradient-based learners](http://www.openreview.net/pdf?id=B1xMEerYvB) :tada: I lost the train of thoughts into section 4. I don't think I have enough knowledge or experience to interpret and understand properly of this paper although I catch the basic idea. Some of the settings of the paper are far from mainstream neural gaming settings which are hard to imagine from my side.

__2020-08-09__: [Training binary neural networks with real-to-binary convolutions](http://www.openreview.net/pdf?id=BJg4NgBKvH) :tada: This paper is clean, to the point, and actionable.

__2020-08-10__: [Editable Neural Networks](http://www.openreview.net/pdf?id=HJedXaEtvS) :tada: I like the take of the problem and I somewhat considered a similar problem. This may give new ideas of fast patching networks and quick transfer that we wish to have.

__2020-08-11__: [Contrastive Representation Distillation](http://www.openreview.net/pdf?id=SkgpBJrtvS) :tada: I like the take of this paper and the use of contrastive loss to perform distillation. It might generate some extra effect in domain such as class incremental learning.

__2020-08-12__: [LAMOL: LAnguage MOdeling for Lifelong Language Learning](http://www.openreview.net/pdf?id=Skgxcn4YDS) :tada: This is a new take that uses the generation capability of network to prevent forgetting, which is cool.

__2020-08-13__: [Jelly Bean World: A Testbed for Never-Ending Learning](http://www.openreview.net/pdf?id=Byx_YAVYPH) :tada: Good to know there is a tool like this. Most likely not so useful for me right now.

__2020-08-14__: [Rapid Learning or Feature Reuse? Towards Understanding the Effectiveness of MAML](http://www.openreview.net/pdf?id=rkgMkCEtPB) :tada: what a good treat! This paper confirms my intutition over MAML-type learning algorithm which they does not model rapid learning properly. If we follow this paper's opinion. Then MAML can be re-interpreted into learning parameters from a ensemble of inner-loop optimized task networks. This brings the paradigm more closer to metric based few-shot learning algorithms.

__2020-08-15__: [Learning to solve the credit assignment problem](http://www.openreview.net/pdf?id=ByeUBANtvB) :tada: Cool direction to think about biologically plausible learning. The math is not crazy, however I lost my interest in reading it becasue BP reasoning is in general too messy for me for my one-hour reading.

__2020-08-16__: [And the Bit Goes Down: Revisiting the Quantization of Neural Networks](http://www.openreview.net/pdf?id=rJehVyrKwH) :tada: Have to admit I didn't pay too much attention over this paper. but the idea is cool.

__2020-08-17__: [Continual learning with hypernetworks](http://www.openreview.net/pdf?id=SJgwNerKvB) :tada: a great use of hypernetworks, great work. my strongest opinion is towards the unknown task identity although this is a problem to all CL algorithms. For the sake of evaluation, this may not be a problem at all. Again, I still have a strong, strong feeling about the connection between UL, Fewshot Learning and CL. There has to be a way.

__2020-08-18__: [A critical analysis of self-supervision, or what we can learn from a single image](http://www.openreview.net/pdf?id=B1esx6EYvr) :tada: Great contribution on sample efficiency side of self-supervision. I like it very much.

__2020-08-19__: [Hierarchical Foresight: Self-Supervised Learning of Long-Horizon Tasks via Visual Subgoal Generation](http://www.openreview.net/pdf?id=H1gzR2VKDH) :tada: reminds me very much for the world model. This one by concept is cool. And I'm glad to see that self-supervised learning in robotics tasks via learning video prediction.

__2020-08-20__: [Self-labelling via simultaneous clustering and representation learning](https://openreview.net/pdf?id=Hyx-jyBFPr) :tada: This is a fresh take on self-supervised learning where the clustering is done by solving optimal transport problem. I should read more about pseudo-labeling kind of literature.

__2020-08-21__: [Mogrifier LSTM](http://www.openreview.net/pdf?id=SJe5P6EYvS) :tada: It always to see an extension over LSTM. To me, the proposed addition is a interative filtering process embedded at each step update, effectively making the whole neural network much more deep. Isn't this somewhat related to Recurrent Highway Networks?

__2020-08-22__: [Understanding Generalization in Recurrent Neural Networks](http://www.openreview.net/pdf?id=rkgg6xBYDH) :tada: Obvious difficulty to understand it at late night.

__2020-08-23__: [High Fidelity Video Prediction with Large Stochastic Recurrent Neural Networks](https://papers.nips.cc/paper/8303-high-fidelity-video-prediction-with-large-stochastic-recurrent-neural-networks.pdf) :tada: I never thought the convolution and ConvLSTM hybrid can be done at two levels, and it's so obvious. THis is a great paper!

__2020-08-24__: [Experience Replay for Continual Learning](https://papers.nips.cc/paper/8327-experience-replay-for-continual-learning.pdf) :tada: I hardly understand it because it's beyond my knowledge scope.

__2020-08-25__: [Deep ReLU Networks Have Surprisingly Few Activation Patterns](https://papers.nips.cc/paper/8328-deep-relu-networks-have-surprisingly-few-activation-patterns.pdf) :tada: cool paper, a lot to think about.

__2020-08-26__: [Why Can't I Dance in the Mall? Learning to Mitigate Scene Bias in Action Recognition](https://papers.nips.cc/paper/8372-why-cant-i-dance-in-the-mall-learning-to-mitigate-scene-bias-in-action-recognition.pdf) :tada: What I like is how the author address the scene bias through those two losses that decreases scene dependencies and increases classification uncertainty. What I feel a bit short in this paper is that the author uses pretrained model to obtain pseduo-loss which needs training for other networks.

__2020-08-27__: [Learning Perceptual Inference by Contrasting](https://papers.nips.cc/paper/8392-learning-perceptual-inference-by-contrasting.pdf) :tada: First visual reasoning paper that I understand, cool results.

__2020-08-28__: [Failing Loudly: An Empirical Study of Methods for Detecting Dataset Shift](https://papers.nips.cc/paper/8420-failing-loudly-an-empirical-study-of-methods-for-detecting-dataset-shift.pdf) :tada: As a tool, I think this paper provides a wide range of tests so that we can select for debugging our own network. Furthermore, this problem of dataset shift will be addressed someday in domains such as continual learning.

__2020-08-29__: [Random deep neural networks are biased towards simple functions](https://papers.nips.cc/paper/8471-random-deep-neural-networks-are-biased-towards-simple-functions.pdf) :tada: lesson learned.

__2020-08-30__: [HYPE: A Benchmark for Human eYe Perceptual Evaluation of Generative Models](https://papers.nips.cc/paper/8605-hype-a-benchmark-for-human-eye-perceptual-evaluation-of-generative-models.pdf) :tada: what a clever design!

__2020-08-31__: [Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask](https://papers.nips.cc/paper/8618-deconstructing-lottery-tickets-zeros-signs-and-the-supermask.pdf) :tada: It's a very cool paper to read, many insights for sparse neural networks. I like it.

__2020-09-01__: [When does label smoothing help?](https://papers.nips.cc/paper/8717-when-does-label-smoothing-help.pdf) :tada: It's a empirical paper that I like. The label smoothing has many implications to other applications as well. As contrastive learning is also mainly relying on cross-entropy loss, this work may have more impact there.

__2020-09-02__: [One ticket to win them all: generalizing lottery ticket initializations across datasets and optimizers](https://papers.nips.cc/paper/8739-one-ticket-to-win-them-all-generalizing-lottery-ticket-initializations-across-datasets-and-optimizers.pdf)

__2020-09-03__: [Incremental Few-Shot Learning with Attention Attractor Networks](https://papers.nips.cc/paper/8769-incremental-few-shot-learning-with-attention-attractor-networks.pdf)

__2020-09-04__: [Latent Weights Do Not Exist: Rethinking Binarized Neural Network Optimization](https://papers.nips.cc/paper/8971-latent-weights-do-not-exist-rethinking-binarized-neural-network-optimization.pdf)

__2020-09-05__: [This Looks Like That: Deep Learning for Interpretable Image Recognition](https://papers.nips.cc/paper/9095-this-looks-like-that-deep-learning-for-interpretable-image-recognition.pdf)

__2020-09-06__: [How to Initialize your Network? Robust Initialization for WeightNorm & ResNets](https://papers.nips.cc/paper/9272-how-to-initialize-your-network-robust-initialization-for-weightnorm-resnets.pdf)

__2020-09-07__: [Gradient based sample selection for online continual learning](https://papers.nips.cc/paper/9354-gradient-based-sample-selection-for-online-continual-learning.pdf)

__2020-09-08__: [DeepUSPS: Deep Robust Unsupervised Saliency Prediction via Self-supervision](https://papers.nips.cc/paper/8314-deepusps-deep-robust-unsupervised-saliency-prediction-via-self-supervision.pdf)

__2020-09-09__: [Joint-task Self-supervised Learning for Temporal Correspondence](https://papers.nips.cc/paper/8324-joint-task-self-supervised-learning-for-temporal-correspondence.pdf)

__2020-09-10__: [Using Self-Supervised Learning Can Improve Model Robustness and Uncertainty](https://papers.nips.cc/paper/9697-using-self-supervised-learning-can-improve-model-robustness-and-uncertainty.pdf)

__2020-09-11__: [Continual Unsupervised Representation Learning](https://papers.nips.cc/paper/8981-continual-unsupervised-representation-learning.pdf)

__2020-09-12__: [On the Convergence Rate of Training Recurrent Neural Networks](https://papers.nips.cc/paper/8893-on-the-convergence-rate-of-training-recurrent-neural-networks.pdf)

__2020-09-13__: [Training Image Estimators without Image Ground Truth](https://papers.nips.cc/paper/8514-training-image-estimators-without-image-ground-truth.pdf)


## First Morning Paper Challenge

The first morning paper challenge is archived at [here](./first-challenge.md).

## Second Unsuccessful Paper Challenge Attempt

It's [here](./second-unsuccessful-attempt.md)

## Third Morning Paper Challenge

It's [here](./third-challenge.md)

## Contacts

Yuhuang Hu  
Email: duguyue100@gmail.com
