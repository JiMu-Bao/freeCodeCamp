---
id: 5900f3d91000cf542c50feea
title: 问题107：最小网络
challengeType: 5
videoUrl: ''
dashedName: problem-107-minimal-network
---

# --description--

以下无向网络由七个顶点和十二个边组成，总权重为243。

相同的网络可以由下面的矩阵表示。 ABCDEFG A-161221 --- B16--1720-- C12--28-31- D211728-181923 E-20-18--11 F-3119--27 G --- 231127-但是，有可能通过删除一些边缘来优化网络，并仍然确保网络上的所有点保持连接。实现最大节省的网络如下所示。它的权重为93，比原始网络节省了243 - 93 = 150。

使用network.txt（右键单击并“保存链接/目标为...”），一个6K文本文件包含一个具有四十个顶点的网络，并以矩阵形式给出，找到通过删除冗余边缘可以实现的最大节省确保网络保持连接。

# --hints--

`euler107()`应该返回259679。

```js
assert.strictEqual(euler107(), 259679);
```

# --seed--

## --seed-contents--

```js
function euler107() {

  return true;
}

euler107();
```

# --solutions--

```js
// solution required
```
