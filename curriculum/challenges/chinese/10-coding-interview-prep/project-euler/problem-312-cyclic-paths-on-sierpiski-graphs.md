---
id: 5900f4a51000cf542c50ffb7
title: 问题312：Sierpiński图上的循环路径
challengeType: 5
videoUrl: ''
---

# --description--

\-1阶（S1）的Sierpiński图是等边三角形。

\-通过将Sn的三个副本放置在Sn上，从而使每对副本都有一个公共角，从而从Sn中获得Sn +1。

令C（n）为恰好一次通过Sn的所有顶点的循环数。 例如，C（3）= 8，因为可以在S3上绘制八个这样的循环，如下所示：

也可以验证： C（1）= C（2）= 1 C（5）= 71328803586048 C（10,000）mod 108 = 37652224 C（10,000）模138 = 617720485

求C（C（C（10,000））mod 138。

# --hints--

`euler312()`应该返回324681947。

```js
assert.strictEqual(euler312(), 324681947);
```

# --solutions--

