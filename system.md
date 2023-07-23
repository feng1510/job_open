<!--
 * @Description: 记录计算机相关知识
 * @Autor: Zhiqi Feng
 * @E-mail: feng_1510@outlook.com
 * @Date: 2020-09-09 17:06:45
 * @LastEditors: Zhiqi Feng
 * @LastEditTime: 2020-09-09 17:13:47
-->

<!-- TOC -->

- [异构计算](#异构计算)
  - [1. 概念](#1-概念)
  - [2. 异构计算的实现](#2-异构计算的实现)

<!-- /TOC -->

## 异构计算

参考链接：https://www.cnblogs.com/-9-8/p/5676635.html

### 1. 概念

 所谓异构计算，是指CPU+ GPU或者CPU+ 其它设备（如FPGA等）协同计算。一般我们的程序，是在CPU上计算。

但是，当大量的数据需要计算时，CPU显得力不从心。那么，是否可以找寻其它的方法来解决计算速度呢？那就是异构计算。

例如可利用CPU（Central Processing Unit）、GPU（Graphic Processing Unit）、甚至APU(Accelerated Processing Units， CPU与GPU的融合)

等计算设备的计算能力从而来提高系统的速度。异构系统越来越普遍，对于支持这种环境的计算而言，也正受到越来越多的关注。

### 2. 异构计算的实现

 目前异构计算使用最多的是利用GPU来加速。主流GPU都采用了统一架构单元，凭借强大的可编程流处理器阵容，

GPU在单精度浮点运算方面将CPU远远甩在身后。英特尔Core i7 965处理器，在默认情况下，

它的浮点计算能力只有NVIDIA GeForce GTX 280 的1/13，与AMD Radeon HD 4870相比差距就更大。