---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

<div class="card hoverable p-3" markdown="1">

**Training with Confidence: Catching Silent Errors in Deep Learning Training with Automated Proactive Checks**

*Authors: Yuxuan Jiang, Ziming Zhou, Boyu Xu, Beijie Liu, Runhui Xu, Peng Huang*

**OSDI 2025** &nbsp; [Paper](https://www.usenix.org/conference/osdi25/presentation/jiang) &nbsp; [Code](https://github.com/OrderLab/TrainCheck)


**My contributions:**

- Designed and implemented the runtime checker with a watchdog to monitor trace file changes.
- Designed a new proxy to achieve `torch.compile` / distributed training compatibility and reduce runtime overhead.
- Revised the invariant inference and checking pipeline.

</div>
