---
layout: page
title: TrainCheck
# description: Catching silent errors in deep learning training with automated proactive checks (OSDI 2025)
importance: 1
category: work
---

**Training with Confidence: Catching Silent Errors in Deep Learning Training with Automated Proactive Checks**

Based on OSDI 2025 paper by Yuxuan Jiang, Ziming Zhou, Boyu Xu, Beijie Liu, Runhui Xu, Peng Huang

<div class="project-links">
  <a href="https://www.usenix.org/conference/osdi25/presentation/jiang" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener">Paper</a>
  <a href="https://github.com/OrderLab/TrainCheck" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener">Code</a>
</div>

<details class="project-details" markdown="1">
<summary>My contributions after publication</summary>

- Designed and implemented the runtime checker with a watchdog to monitor trace file changes.
- Designed a new proxy to achieve torch.compile / distributed training compatibility and reduce runtime overhead.
- Revised the invariant inference and checking pipeline.

</details>
