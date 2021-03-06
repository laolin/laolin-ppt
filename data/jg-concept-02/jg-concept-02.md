# 结构设计实践
## 概念篇(2. 结构分类)

- 注:
  + 本文主要目的是给非结构设计的同学普及一下结构设计
  + 专业设计人员请绕道

 * * * * * * * * * * * * * * * * * 

&copy; [laolin](http://laolin.com)  2014.11 (v0.04)

===

<!-- .slide: data-background="#008" -->
### 注

- 本文主要目的是给非结构设计的同学普及一下结构设计
- 内容可能不是很严谨，请勿据此进行结构设计
- 如有错漏，敬请批评指正——请在此留言：[laolin.com](http://laolin.com)

===


[第一大点][c1]讲到：
## 1. 建筑参数
##1.1 多高？
##1.2 多大跨？
##1.3 面积多大？
##1.4 功能多高级？

[c1]: ./?ppt=jg-concept-01

===

本文是第二大点：
## 2. 结构分类
- 2.1 结构材料
- 2.2 结构体系
- 2.3 适用对比

===

<!-- .slide: data-background="#ff0000" -->
##注，本文目前处于草稿阶段尚未完成

===

<!-- .slide: data-background="#ff0000" -->
##建议您还是别往下看了吧
<hr/>
建议返回：
<ul>
<li><a href='./#/1'> PPT列表 </a>
<li><a href='./?ppt=ppt-help'>帮助文件</a>
</ul>



====================

## 2.1 结构材料
- 混凝土结构
- 钢结构
- 混合结构（钢+混凝土）
- 砌体结构（以前也叫砖混结构）
- 木结构

====================

## 2.2 结构体系(常规)
- 框架结构
- 剪力墙结构
- 框架剪力墙结构/框架核心筒结构
- 异形柱结构
- 砌体结构


====================

## 2.2 结构体系(超高层)
- 筒中筒结构
- 框架核心筒+伸臂桁架
- 框架核心筒+伸臂桁架+环带桁架
- 巨柱框架核心筒+伸臂桁架+环带桁架
- ……

====================

## 2.3 适用对比

====================


## 2.3.1 结构材料适用对比：

- 最常用的结构用混凝土，混凝土结构省钱，费人工，在外国不是最常用的。
- 大跨，用钢结构，
- 超高，用混合结构
- 固定隔墙很多的多层建筑，用砌体结构（多层住宅）
- 很少用木结构，国内木材来源少，木结构工业化水平很低。

====================

## 2.3.2 结构体系适用对比：

###(1)住宅：
- 多层住宅
  可考虑用砌体结构，缺点是隔墙需要固定且上下层对齐，设计房型不灵活，使用时不能敲掉改造布局。

- 上海多层住宅很多都是叠加别墅，砌体结构也不适用，一般用剪力墙结构。
  - 偶尔有用异型柱结构，异型柱结构体系不流行，一般认为抗震性能不好，尽量不使用。


- 上海住宅一般用剪力墙结构。
    - 外地住宅有用框剪的。
    - 剪力墙结构室内不会凸出柱角。
    - 但框剪 由于剪力墙少，几乎套内所有隔墙都可以敲掉，部分外地比较流行。

- 纯剪力墙结构由于墙比较多，大都用在高层住宅。

====================

## 2.3.2 结构体系适用对比：
### (2)公建：

- 对于不高的楼，可以采用框架结构（大概30米以内），
  - 典型应用——多层商业
  - 框架，无固定隔墙，商业布置灵活。

- 对于高一点的楼(一般30~60米，100米以内），可以采用框剪结构，
  - 典型应用——酒店，办公楼

[框剪结构酒店平面图]
[框剪结构办公平面图]
[框筒结构办公平面图]

- 框筒结构

==========

###直观的图表

==========

## 3 结构概念设计
- 3.1 抗重力设计
- 3.2 结构抗震设计
- 3.3 结构抗风设计

====================

## 3.1 抗重力设计
### 结构竖向承载力
跨度起主要控制参数：

====================

### 梁：

- 一般跨度梁8.4米的很常见，也挺合适，
- 混凝土一般十几米也可以做，但不太经济，
- 二十几米不太合适，也可以做，
- 大跨度（十几米以上）可能需要加预应力。

* 梁高跨比： 一般1/8~12，
* 悬挑梁：1/4~6
混凝土梁，悬挑1米以内无所谓，2米以内很轻松，3米以内还容易，4米以内还可以，5米以内有点累，6米以内比较累，6米以上很少做。
（一般悬挑控制在3米内比较好，偶尔来些4米的，5米以上不轻易做）

====================

### 板：

- 一般板跨度4米左右比较合适
- 7、8米左右的板也有，但要比较厚，不经济
  -  偶尔用于尽高很紧张的局部，比较坡道局部顶板等
- 板厚比跨度：单向板1/30，双向板1/35

====================

### 柱尺寸
和层高、楼总高、跨度、设防烈度有关
###墙厚度
和层高、楼总高、跨度、设防烈度有关

 * * * * * * * * * 

（梁、柱、墙大多数情况下，尺寸还是由抗震起主要控制作用。）

====================

## 3.2 结构抗震设计
### 抗震是结构设计最主要的内容。

- 抗震设防类别：
- 抗震设防烈度：
- 地面加速度
- 小震中震大震，概率
- 中国小震，外国大震

- 【设防烈度与震级：】

====================

## 重点：【规则】
- 平面规则性：长宽比，平面规则，大开洞，大凸出，大凹进，大跨度，大悬挑
- 竖向规则性，高宽比，竖向连续避免转换

====================

## 中国抗震设计三准：

- 小震不坏
- 中震可修
- 大震不倒


- 小震计算（见下页）<!-- .element: class="fragment" -->
- 抗震等级（小震计算保证中震性能的措施）<!-- .element: class="fragment" -->
- 中震（超限高层、复杂结构进行中震性能分析）<!-- .element: class="fragment" -->
- 构造措施（保证大震不倒的一些措施）<!-- .element: class="fragment" -->
- 大震（超限高层、复杂结构进行大震性能分析）<!-- .element: class="fragment" -->

====================

## 小震计算

- 反应谱，静力等效
- 【规范谱】

- 时程分析（小震弹性动力时程分析）
- （地震波，反应谱，人工波，天然波）

====================

## 中大震计算
- PUSHOVER，静力非线性
- 时程分析：动力弹塑性时程分析

====================


## 安评
大地方还好，
在很多小地方的安评就是个随意放大国家规定的安评范围，用来捞钱的工具。

====================

## 3.3 结构抗风设计


- 一般超高层是风控的
- 7度抗震的，250米抗风可能会起控制作用，也可能不起控制作用
- 6度区，则150米也可能是抗风起控制作用。

====================


- 基本风压
- 体型系数
- 高度系数
- 场地类别

- 风洞试验

====================


## 4 不同建筑功能的结构设计的特点

====================

### 建筑功能
住宅，酒店，办公，商业，学校，医院/影院，剧院，博物馆，展览馆，体育馆……

====================

###住宅
层高小，功能单一，要求房间内无梁

====================

###酒店
与酒店管理公司配合。除了客房区还有很多配套功能区，对结构最主要的是配套的宴会厅，可能是大跨度结构。

====================

###办公
一般净高要求较高，空调等机电管线多，结构梁高尽量做小，走道上管线最多。

====================

###商业
功能复杂，变化乱，中庭可能有大开洞，中庭还可能有很多大悬挑，部分大悬挑外面还搁置有自动扶梯。商业面积较大时（建筑面积大于1万7或营业面积大于7千），人员疏散问题比较重要，抗震投防类别：提高。

====================

###学校
中小学幼儿园等未成年人，抗震投防类别：提高。大学可不提高。

====================

###医院
重点保护部门，抗震投防类别：提高


====================


# 5 其他

## 结构方案的选择

- 多种因素
- 综合比选


--------


## 结构技术前沿
- 装配式混凝土结构
- BIM

--------

行情
# 材料用量
##（用钢量，砼和量）
钢筋：每平方多少公斤
型钢：
砼：每平方折算多少立方砼

-----------

行情
# 造价

--------

行情
# 工期
