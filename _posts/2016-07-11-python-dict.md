---
layout: post
title:  "python dict sort"
date:   2016-07-11 20:04:00 +0800
categories: python
tags: sort
excerpt: python字典排序。
---

* content
{:toc}

使用operator，sorted对字典排序

```python
import operator

# 字典按value排序
sorted_dict = sorted(origin_dict.items(), key=operator.itemgetter(1))

# 字典按key排序
sorted_dict = sorted(origin_dict.items(), key=operator.itemgetter(0))
```
