---
title: "A New Framework for Supervised Speech Enhancement in the Time Domain"
collection: publications
permalink: /publication/2018-05-10-paper-A-New-Framework-for-Speech-Enhancement-in-the-Time-Domain-number-3
excerpt: 
date: 2018-08-06
venue: Interspeech 2018
paperurl:
citation:
---
Abstract
---
This work proposes a new learning framework that uses a
loss function in the frequency domain to train a convolutional
neural network (CNN) in the time domain. At the training time,
an extra operation is added after the speech enhancement network
to convert the estimated signal in the time domain to the
frequency domain. This operation is differentiable and is used
to train the system with a loss in the frequency domain. This
proposed approach replaces learning in the frequency domain,
i.e., short-time Fourier transform (STFT) magnitude estimation,
with learning in the original time domain. The proposed method
is a spectral mapping approach in which the CNN first generates
a time domain signal then computes its STFT that is used for
spectral mapping. This way the CNN can exploit the additional
domain knowledge about calculating the STFT magnitude from
the time domain signal. Experimental results demonstrate that
the proposed method substantially outperforms the other methods
of speech enhancement. The proposed approach is easy
to implement and applicable to related speech processing tasks
that require spectral mapping or time-frequency (T-F) masking.
activity detection method in degraded and limited data conditions.
---
[Download paper here]
