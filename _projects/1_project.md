---
layout: page
title: TrainCheck
# description: Catching silent errors in deep learning training with automated proactive checks (OSDI 2025)
importance: 1
category: work
---

**Training with Confidence: Catching Silent Errors in Deep Learning Training with Automated Proactive Checks**

Based on OSDI 2025 paper by Yuxuan Jiang, Ziming Zhou, Boyu Xu, Beijie Liu, Runhui Xu, Peng Huang

[Paper](https://www.usenix.org/conference/osdi25/presentation/jiang) &nbsp; [Code](https://github.com/OrderLab/TrainCheck)

**My contributions after publication:**

- Designed and implemented the runtime checker with a watchdog to monitor trace file changes.
- Designed a new proxy to achieve torch.compile / distributed training compatibility and reduce runtime overhead.
- Revised the invariant inference and checking pipeline.
