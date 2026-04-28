---
layout: page
title: TrainCheck
# description: Catching silent errors in deep learning training with automated proactive checks (OSDI 2025)
importance: 1
category: work
---

**Training with Confidence: Catching Silent Errors in Deep Learning Training with Automated Proactive Checks**

*Authors: Yuxuan Jiang, Ziming Zhou, Boyu Xu, Beijie Liu, Runhui Xu, Peng Huang*

**OSDI 2025** &nbsp;|&nbsp; [Paper](https://www.usenix.org/conference/osdi25/presentation/jiang) &nbsp;|&nbsp; [Code](https://github.com/OrderLab/TrainCheck)

**My contributions:**

- Designed and implemented the runtime checker with a watchdog to monitor trace file changes.
- Designed a new proxy to achieve `torch.compile` / distributed training compatibility and reduce runtime overhead.
- Revised the invariant inference and checking pipeline.
