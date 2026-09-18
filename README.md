# ESP32-S3 Wudilink LVGL Embedded Terminal

基于 ESP32-S3 的触摸式 LVGL 嵌入式人机交互终端开发。

本项目采用 ESP32-S3 MCU 作为核心控制器，结合 1.69 英寸 Wudilink TFT 显示屏与 CST816T 电容触摸控制器，实现基于 LVGL 图形框架的嵌入式 GUI 系统开发。

项目完成了显示驱动、触摸交互、图形界面设计、图片资源管理以及启动动画等功能，为嵌入式人机交互设备开发提供基础平台。

---

## Hardware

| Component | Description |
|-----------|-------------|
| MCU | ESP32-S3 |
| Display | Wudilink 1.69 inch TFT LCD |
| Touch Controller | CST816T Capacitive Touch |
| Flash | 16MB |
| PSRAM | Supported |

---

## Development Environment

- PlatformIO
- Arduino Framework
- C/C++
- LVGL GUI Framework

---

## Features

### 1. LVGL Graphical User Interface

- 基于 LVGL 框架开发嵌入式图形界面
- 支持页面布局与 UI 组件管理
- 实现触摸交互控制
- 支持图片资源显示


### 2. TFT Display Driver

- 完成 ESP32-S3 与 TFT LCD 通信配置
- 实现屏幕初始化与图像显示
- 支持自定义 UI 界面显示


### 3. CST816T Touch Interaction

- 集成 CST816T 电容触摸驱动
- 实现触摸坐标读取
- 支持 LVGL 触摸事件响应


### 4. Custom Boot Animation

- 实现启动 Logo 显示
- 完成图片资源转换与加载
- 支持开机界面自定义设计


### 5. Resource Management

- 支持 LVGL 图片资源管理
- 使用 ESP32-S3 Flash 与 PSRAM 进行资源存储
- 优化大尺寸图片显示需求

---

## Project Structure
