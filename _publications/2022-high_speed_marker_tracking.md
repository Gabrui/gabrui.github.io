---
title: "High Speed Marker Tracking for Flight Tests"
collection: publications
category: manuscripts
permalink: /publication/2022-high_speed_marker_tracking
excerpt: 'We propose a new detecting and tracking model based on CNN, that uses fiducial markers.'
date: 2022-10-01
venue: 'IEEE Latin America Transactions'
paperurl: 'https://gam.dev/files/high_speed_marker_tracking22.pdf'
citation: 'G. A. Melo, M. Máximo and P. A. Castro, "High Speed Marker Tracking for Flight Tests," in IEEE Latin America Transactions, vol. 20, no. 10, pp. 2237-2243, Oct. 2022, doi: 10.1109/TLA.2022.9885171. '
---

A small fraction of the SisTro II project that was allowed to be published.

Flight testing is a mandatory process to ensure safety
during normal operations and to evaluate an aircraft during its
certification phase. As a test flight may be a high-risk activity that
may result in loss of the aircraft or even loss of life, simulation
models and real-time monitoring systems are crucial to access
the risk and to increase situational awareness and safety. We
propose a new detecting and tracking model based on CNN, that
uses fiducial markers, called HSMT4FT. It is one of the main
components of the Optical Trajectory System (SisTrO) which
is responsible for detecting and tracking fiducial markers in
external stores, in pylons, and in the wings of an aircraft during
Flight Tests. HSMT4FT is a real-time processing model that is
used to measure the trajectory in a store separation test and
even to assess vibrations and wing deflections. Despite the fact
that there are several libraries providing rule-based approaches
for detecting predefined markers, this work contributes by developing and evaluating three convolutional neural network (CNN)
models for detecting and localizing fiducial markers. We also
compared classical methods for corner detection implemented
in the OpenCV library and the neural network model executed
in the OpenVINO environment. Both the execution time and the
precision/accuracy of those methodologies were evaluated. One of
the CNN models achieved the highest throughput, smaller RMSE,
and highest F1 score among tested and benchmark models.
The best model is fast enough to enable real-time applications
in embedded systems and will be used for real detecting and
tracking in real Flight Tests in the future.
