
<b>Part 2: Time Series Forecasting: The Random Walk</b>

<b>This datasets focus on certain stocks:</b><br>
<ol>
  <li>
    Nvidia (NVDA)
  </li>
  <li>
    Bank Of America (BAC)
  </li>
  <li>
    EBay (EBAY)
  </li>
  <li>
    Costco (COST)
  </li>
  <li>
    Johnson & Johnson (JNJ)
  </li>
  <li>
    JPMorgan Chase (JPM)
  </li>
  <li>
    Microsoft (MSFT)
  </li>
  <li>
    Netflix (NFLX)
  </li>
  <li>
    Visa (V)
  </li>
  <li>
    Mastercard (MA)
  </li>
</ol>


#### What we will achieve here is (Forecasting the Random Walk in Python)
1. Intuatively, check if the data is stationary or not using line chart to see the rising trend and seasonality effects.
2. Transform the data sequence using First-ordering differencing via `np.diff()` function to reduce the trend effect and have stationary data. It's expected from the data to have consistent mean and variance over time.
3. After proving the data is stationary, we use ACF plot to check the auto-correlation. Usually we visualize this step using a unique chart with data points highlights as pins.
4. Comes later the forecasting of the random walk.




