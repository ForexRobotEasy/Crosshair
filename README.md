# Crosshair Program

This is a code for a Crosshair Expert Advisor that simplifies chart analysis and enhances precision in forex trading. It aligns price candles with indicator values in subwindows, enabling pattern identification. It also has a ruler mode for precise measurements and distance measurement between price levels. The Expert Advisor provides a user-friendly interface for effective market analysis, strategy development, and risk management.

Developer: Forex Robot Easy
Website: [forexroboteasy.com](https://forexroboteasy.com)

## Usage

The Expert Advisor has the following features:

- Ruler mode: By pressing the 'R' key, you can toggle the ruler mode on or off. In ruler mode, you can measure the distance between two points on the chart by clicking and dragging the mouse. The distance is displayed in the terminal.
- Chart event handling: The Expert Advisor handles chart events such as key presses and mouse movements to enable the ruler mode functionality.

## Installation

To use this Expert Advisor, follow these steps:

1. Open the MetaTrader 5 platform.
2. Go to the 'File' menu and select 'Open Data Folder'.
3. In the opened folder, navigate to the 'MQL5' folder and then to the 'Experts' folder.
4. Copy the Crosshair.mq5 file into the 'Experts' folder.
5. Restart MetaTrader 5.
6. The Expert Advisor will now be available in the Navigator window under the 'Expert Advisors' section.

## Disclaimer

Please note that Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit the following link: [Crosshair Forex Software - Review](https://forexroboteasy.com/forex-robot-review/review-crosshair-forex-software-simplify-chart-analysis-and-enhance-precision/)

## For Developers

This code is written in MQL5 language. It is an Expert Advisor class that handles chart events and provides the functionality for the crosshair program. The main features are implemented in the following methods:

- `OnInit()`: This method is called when the Expert Advisor is initialized. It sets the initial values for the flags and variables used in the program.
- `OnDeinit()`: This method is called when the Expert Advisor is deinitialized. It resets the flags and variables.
- `OnChartEvent()`: This method is called when a chart event occurs. It handles key presses and mouse movements to enable the ruler mode functionality.

Please refer to the MQL5 documentation for more information on developing Expert Advisors.
