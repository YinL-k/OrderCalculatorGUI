[English](README_en.md) | [中文](README.md)

# Order Calculator GUI Template

This repository provides a Java Swing-based order calculator interface template. The initial example targets a bagel shop, but the overall structure is generic and can be extended to coffee shops, bakeries, and other scenarios.

## Main Files

- **OrderCalculatorGUI.java**: Constructs and displays the main application window.
- **BagelPanel.java**: Presents a selection of bagel flavors.
- **CoffeePanel.java**: Presents coffee size and flavor options.
- **ToppingPanel.java**: Presents topping options.
- **CostPanel.java**: Calculates and displays the subtotal, tax, and total.
- **GreetingPanel.java**: Displays a welcome message.
- **Bagel.java**: Defines the bagel item model.
- **BrandiLogo.jpg**: Example logo image; replace with your own branding.

## Usage

1. Install JDK 8 or higher.
2. From the source file directory, compile all Java files:

       javac *.java

3. Run the main program to launch the interface:

       java OrderCalculatorGUI

After launching, you can select items and calculate the order total.

## Customization

- **Branding**: Replace `BrandiLogo.jpg` and adjust the welcome text or image in `GreetingPanel.java`.
- **Menu**: Modify the options and prices in `BagelPanel`, `CoffeePanel`, and `ToppingPanel`.
- **UI style**: Adjust layout, fonts, or colors to match your brand identity.

## License

This template is provided as-is and may be freely used and modified for personal or commercial projects.
