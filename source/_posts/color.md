---
title: 色彩基础
author:
	name: 覃浩
	avatar: https://cdn.jsdelivr.net/gh/queen999/ImageHosting//imagesavatar.jpg
	url: https://www.zhengyuanyuan520.com
categories: Photoshop
date: 2020-04-04 13:06:11
music:
  type: song  
  id: 1404906595
comments: true
tags:  
	- 图像处理
	- Photoshop
---

色彩的产生

色光

固有色

RGB模式

色彩三要素

HSB取色

CMYK模式

<!-- more -->

## 色彩的产生

<blue>光是一种电磁波，人可以识别的电磁波波长是770-350nm之间。高于770的是红外线，低于350的是紫外线。</blue>

<blue>人眼能看到的波段：可见光。</blue>



### 光源光

```
太阳，电灯，显示屏，RGB模式。
```

### 反射光

```
月亮，不发光物，CMYK模式。

光滑表面形成直反射：镜子。
粗糙表面形成漫反射：各种物
```



### 单色光

```
单色光：三基色光（红Red，绿Green，蓝Blue），一切色彩的基础。
```

### 复合光

```
复合光：色光融合，太阳光等其它可见光。
```



### 固有色

```
物体反射到人眼的常态日光，形成人对物体常态的颜色认知。
```

### 光源色

```
物体反射到人眼的目标光源光线，形成人对物体当前状态的颜色认知。
```



在RGB原色通道里，填充白色，即为本色光最强的发光。



## 吸管工具与颜色面板

```
快捷键：I，用于拾取色彩色值。

吸管直接生成前景色；按住Alt键吸取，生成背景色。
```



## RGB色值表达方式

```
红色的RGB色值是255.0.0
黑色的RGB色值是0.0.0
绿色的RGB色值是0.255.0
蓝色的RGB色值是0.0.255
```



## 在RGB通道创建色彩

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images/20200404114855.png)

```
红色 + 绿色 = 黄色
红色 + 蓝色 = 品红
绿色 + 蓝色 = 青色
```

## 色彩三要素

### 色相

```
色相：颜色的品相。

15°范围内叫作同类色。
45°范围内叫作邻近色。
120°范围内叫作对比色。
180°范围内叫作补色。
```

### 饱和度

```
饱和度是色彩的鲜艳程度，其实就是加入中性灰的程度。

调整饱和度命令，可以看做是增减中性灰的操作。
```

### 明度

```
调整明度，就是调节发光量，加入额外的白光。
```



<blue>取色模式可以选择HSB，RGB，LAB，CMYK，WEB模式。</blue>



## CMYK模式

```
印刷色彩模式。

C：青色
M：品红
Y：黄色
K：黑色
```

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images/20200404124840.png)

```
CMYK通道里，黑色代表100%浓度的油墨。

CMYK靠百分比来表达当前通道的色值。
```



```
RGB是加色模式，CMYK是减色模式。



制作印刷类图像，不要使用RGB模式，否则成品会偏色。



拾色器会对超出印刷色域的颜色做警告，并可以自动修复。
```
