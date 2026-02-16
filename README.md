[English](README_en.md) | [中文](README.md)

# 订单计算器 GUI 模板

本仓库提供一个基于 Java Swing 的点单计算器界面模板。最初示例针对百吉饼店，但整体结构通用，可扩展到咖啡店、面包店等场景。

## 主要文件

- OrderCalculatorGUI.java：构建并显示应用主窗口。
- BagelPanel.java：选择不同口味百吉饼。
- CoffeePanel.java：选择咖啡尺寸和口味。
- ToppingPanel.java：选择配料。
- CostPanel.java：计算并显示小计、税额和总价。
- GreetingPanel.java：显示欢迎语。
- Bagel.java：定义百吉饼商品模型。
- BrandiLogo.jpg：示例徽标图片，可替换为自己的品牌。

## 使用方法

1. 安装 JDK 8 或更高版本。
2. 在源文件目录下运行以下命令编译所有 Java 文件：

       javac *.java

3. 运行主程序启动界面：

       java OrderCalculatorGUI

启动后可以选择商品并计算订单总价。

## 自定义

- 品牌：替换 BrandiLogo.jpg，并在 GreetingPanel.java 中调整欢迎语或图片。
- 菜单：修改 BagelPanel、CoffeePanel 和 ToppingPanel 中的选项和价格。
- 界面样式：可调整布局、字体或颜色以符合自己的品牌风格。

## 许可

该模板按现状提供，自由使用和修改，欢迎用于个人或商业项目。
