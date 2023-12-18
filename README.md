# Time And Sales Delta Indicator

[![Forex Robot Easy](https://forexroboteasy.com/wp-content/uploads/2022/01/forex-robot-easy-logo.png)](https://forexroboteasy.com/forex-robot-review/review-time-and-sales-delta-a-professional-forex-traders-analysis-of-the-indicator/)

This is a custom indicator called 'Time And Sales Delta' developed by the Forex Robot Easy Team. This indicator calculates and displays the delta and cumulative delta values based on buying and selling volumes in the market.

## Indicator Constants and Variables

The indicator uses the following constants and variables:

- `DeltaBuffer[]` - buffer to store the delta values.
- `CumulativeDeltaBuffer[]` - buffer to store the cumulative delta values.

## Indicator Initialization Function

The `OnInit()` function is responsible for initializing the indicator. It sets up the buffers for delta and cumulative delta and also sets the indicator labels.

## Indicator Calculation

The `OnCalculate()` function is called for each new tick in the market data. It calculates the delta and cumulative delta values based on the buying and selling volumes for each tick.

The calculation process is as follows:

1. Iterate through the ticks from the `prev_calculated` index to the latest tick.
2. Initialize the buying and selling volumes to zero.
3. For each tick, check if the close price is higher or lower than the open price.
4. If the close price is higher, increment the buying volume by the tick volume.
5. If the close price is lower, increment the selling volume by the tick volume.
6. Calculate the delta as the difference between the buying and selling volumes.
7. Calculate the cumulative delta by adding the current delta to the previous cumulative delta.
8. Store the delta and cumulative delta values in their respective buffers.

## Product Description

*Note: Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work similarly to the described product. To find the official developer of this product, please refer to MQL5.*

The 'Time And Sales Delta' indicator is a professional Forex trader's analysis tool. It calculates the delta and cumulative delta values based on buying and selling volumes in the market. This information can be valuable for understanding the strength and direction of market movements.

Key Features:
- Calculates delta and cumulative delta values.
- Provides insights into buying and selling volumes.
- Helps analyze market strength and direction.

To use this indicator, simply add it to your MetaTrader platform and apply it to the desired chart. The indicator will display the delta and cumulative delta values as lines on the chart, helping you make informed trading decisions.

For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/review-time-and-sales-delta-a-professional-forex-traders-analysis-of-the-indicator/).
