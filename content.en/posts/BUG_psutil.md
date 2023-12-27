---
title: "BUG | AttributeError: module 'psutil' has no attribute 'Process'"
date: 2023-08-22T00:04:41+08:00
lastmod: 2023-08-22T00:04:41+08:00
draft: false
keywords: []
description: ""
tags: [jupyter]
categories: [记录]
author: ""

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: false
autoCollapseToc: false
postMetaInFooter: false
hiddenFromHomePage: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
mathjaxEnableSingleDollar: false
mathjaxEnableAutoNumber: false

# You unlisted posts you might want not want the header or footer to show
hideHeaderAndFooter: false

# You can enable or disable out-of-date content warning for individual post.
# Comment this out to use the global config.
#enableOutdatedInfoWarning: false

flowchartDiagrams:
  enable: false
  options: ""

sequenceDiagrams: 
  enable: false
  options: ""

---



When starting a Jupyter notebook and switching to a specific environment, you may encounter an error message stating `AttributeError: module 'psutil' has no attribute 'Process'`. 
<!--more-->

To resolve this issue, you can try installing a specific version of the `psutil` library, namely version 5.9.4, using the following command:


```
pip install psutil==5.9.4
```
