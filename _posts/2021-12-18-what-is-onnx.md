---
title: What is ONNX ?
date: 2021-12-18
permalink: /posts/2021/12-what-is-onnx
excrept_separator: <!--more-->
toc: true
tags:
    - regex
---
ONNX is an intermediary machine learning framework used to convert between different machine learning frameworks. So let's say you're in TensorFlow, and you want to get to TensorRT, or you're in PyTorch, and you want to get to TFLite, or some other machine learning framework. ONNX is a really good intermediary to use to convert your model as you're going through these different machine learning frameworks.

So ONNX has worked really hard to basically implement all kinds of different neural network functions and different functionalities in these machine learning models, so I can support  this cross functionality to have baseline, common framework to convert into.

<!--more-->

Yeah, certainly. I mean, one thing is that as ONNX (an open source tool) builds, they're building new functions into it. They're trying to keep track of all the new research that's being done in machine learning, but these versions can fall behind and you can, you know, have one version of TensorFlow, which is not compatible with one version of ONNX and you have to be upgrading and downgrading these versions to try to find the pathway through them all or maybe even editing your model.
