# Last N candles most visited level

This code is a part of a Forex trading software that analyzes the last N candles in the Forex market and determines the most visited level. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Usage

The code allows you to specify the number of candles to analyze (`N`) as an input parameter. It retrieves the candle data from the Forex market API, calculates the visit count for each level, determines the most visited level, and displays it to the user.

## Code Explanation

### Input Parameters

- `N` (default: 10): The number of candles to analyze.

### Data Structure

- `CandleData`: A structure to store candle data, including the high, low, open, and close prices.

### Functions

- `GetLastNCandlesData()`: Retrieves the last N candles data from the Forex market API and returns it as an array of `CandleData` objects.

- `CalculateVisitCount()`: Calculates the visit count for each level based on the candle data passed as a parameter and returns it as an array of integers.

- `DetermineMostVisitedLevel()`: Determines the most visited level based on the visit count passed as a parameter and returns it as a double.

- `DisplayMostVisitedLevel()`: Displays the most visited level to the user.

### Entry Point

- `OnStart()`: The entry point of the program. It calls the necessary functions in the correct order to retrieve the last N candles data, calculate the visit count for each level, determine the most visited level, and display it to the user.

## Product Description

The Last N candles Forex software is an advanced trading tool developed by the Forex Robot Easy Team. It analyzes the historical candle data in the Forex market to identify the most visited level. By understanding the market's behavior, traders can make more informed decisions and potentially improve their trading strategies.

This software provides a user-friendly interface for traders to input the number of candles they want to analyze. It then retrieves the necessary data from the Forex market API and performs complex calculations to determine the most visited level. The result is displayed to the user, allowing them to incorporate this valuable information into their trading decisions.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that demonstrates how the software works. For detailed reviews and trading results of this product, please visit [forexroboteasy.com/forex-robot-review/last-n-candles-forex-software-unbiased-review-and-results](https://forexroboteasy.com/forex-robot-review/last-n-candles-forex-software-unbiased-review-and-results/). To find the official developer of this product, we recommend using MQL5, a popular platform for finding and purchasing Forex trading software.
