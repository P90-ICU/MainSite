---
title: donk 鼠标键盘外设、视频设置、准心CFG参数
copyright: BY-NC-SA
date: 2024-02-08 23:00:49
tags:
categories: 选手设置
index_img: /2024/donk-pro-settings/donk.jpg
---

{%player_icon "/2024/donk-pro-settings/player_icon.png" "Danil “donk” Kryshkovets" %}

以下是 Team Spirit CS2 选手 **Danil “donk” Kryshkovets** 的画面设置和外设

## 硬件外设

{% player_table

鼠标:"Logitech G Pro X Superlight Magenta"

键盘:"Logitech G Pro X Keyboard"

显示器:"ZOWIE GEAR XL2546K"

耳机:"HyperX Cloud II"

鼠标垫:"SteelSeries QcK+"

%}

## 鼠标设置

{% player_mouse DPI=800 Sensitivity=1.25 Zoom=1 Hz=1000 winSen=6 %}

## 视频设置

### 显示器

{% player_table
分辨率:1280x960
显示比例:4:03
缩放方式:拉伸
亮度:109%
显示模式:全屏
数字震动:50%
%}

### 游戏内设置

{% player_table
提高角色对比度:启用
等待垂直同步:禁用
多重采样抗锯齿模式:"8x MSAA"
全局阴影质量:高
模型/贴图细节:低
贴图过滤模式:三线性
光影细节:低
粒子细节:低
环境光遮蔽:禁用
高动态范围:质量
"FidelityFX 超级分辨率":禁用（最高质量）
"NVIDIA Reflex":禁用
%}

## 鼠标准心

{% player_table
准星类型:经典静态
跟随弹道:否
中心点:否
长度:1
宽度:0
间距:-3.2
轮廓:关
颜色:绿
红色:255
绿色:255
蓝色:255
透明度:开
透明值:255
"T 型准星":否
启用准行间距设置:否
开镜宽度:0
%}

准星代码: `CSGO-HRUtd-7NxSn-DxZ6w-M4OPW-wjA6Q`

```bash
cl_crosshairstyle "Classic Static";
cl_crosshair_recoil 0;
cl_crosshairdot "0";
cl_crosshairsize "1";
cl_crosshairthickness "0";
cl_crosshairgap "-3.2";
cl_crosshair_drawoutline "0";
cl_crosshaircolor "9";
cl_crosshaircolor_r "255";
cl_crosshaircolor_g "255";
cl_crosshaircolor_b "255";
cl_crosshairusealpha "1";
cl_crosshairalpha "255";
cl_crosshair_t "0";
cl_crosshairgap_useweaponvalue "0";
cl_crosshair_sniper_width "0";
```

## 持枪视角

{% player_table
FOV:68
"X 轴":2.5
"Y 轴":0
"Z 轴":-1.5
预设坐标:3
%}

```bash
viewmodel_fov 68;
viewmodel_offset_x 2.5;
viewmodel_offset_y 0;
viewmodel_offset_z -1.5;
viewmodel_presetpos 3;
```

## Hud

{% player_table
"HUD尺寸":0.9
"HUD颜色":粉
%}

## 雷达

{% player_table
玩家居中:开
雷达旋转:Yes
随计分板切换形状:Yes
雷达尺寸:1
地图尺寸:0.7
%}

```bash
cl_radar_always_centered "1"
cl_radar_icon_scale_min "0.6"
cl_radar_rotate "1"
cl_radar_scale "0.7"
cl_radar_square_with_scoreboard "1"
```
