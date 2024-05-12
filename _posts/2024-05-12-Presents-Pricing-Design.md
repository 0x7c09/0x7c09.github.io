---
published: true
categories: Other
date: '2024-05-12 20:24:00 +0800'
title: 礼物加减时长方案设计
---

## 礼物价格分级
<style>
table {
  width: 100%; 
  text-align: center; 
}
td {
  padding: 8px; 
}
</style>

<table>
  <tr>
    <th style="text-align: center">等级</th>
    <th style="text-align: center">价格</th>
    <th style="text-align: center">礼物名称</th>
  </tr>
  <tr>
    <td rowspan="2">加 / 减1s</td>
    <td rowspan="2">1钻石</td>
    <td>小心心</td>
  </tr>
  <tr>
    <td>玫瑰</td>
  </tr>
    <tr>
    <td rowspan="2">加3min / 减7min</td>
    <td rowspan="2">99钻石</td>
    <td>爱的纸鹤</td>
  </tr>
  <tr>
    <td>Thuglife</td>
  </tr>
    <tr>
    <td rowspan="2">加10min / 减23分钟</td>
    <td rowspan="2">199钻石</td>
    <td>比心</td>
  </tr>
  <tr>
    <td>礼花筒</td>
  </tr>
</table>

## 方案设计
### 设计原则：
1. 假设粉丝所送礼物中70%为加时长，30%为减时长。方案的目的在于使<span style="color: MediumTurquoise;">所加时长的数学期望</span>为0。
2. 保证每一等级的下一级礼物（如果存在）可以比这一等级拥有更高的经济效益。
3. 在当前粉丝可承担的消费水平之内，并且加减时长在主播可接受的范围内。

### 当前礼物的经济效益解释
- 第一级为1钻石礼物，投入1钻石增减时间为1秒。
- 第二级为99钻石礼物，投入99钻石可以增加180秒，经济效益为上一级的1.8倍，可以减420秒，经济效益为第一级的5.45倍。
- 第三级为199钻石礼物，投入199钻石可以增加600秒，经济效益为上一级的1.67倍，可以减1380秒，经济效益为上一级的1.64倍。

