# Trading styles
- Systematic
  - Objective
  - Reduce emotions
  - Simple decision making
  - Fastest way to build consistency
  - Gives clear entry and exit signals
  - Allow risk management
  - Allow backtesting and optimisation
  - Shorter learning curve than discretionary
- Discretionary
  - Subjective
  - Emotion and intuition
  - Complex decision making
  - Harder to be consistent
  - Entry and exit not fixed
  - No clear risk management
  - Not measurable and cant be tested effectively
  - Much longer learning curve
# Info
- Collateral
  - Asset that acts as security to cover potential losses
- Margin
  - Amount of collateral we must own to cover potential losses
- Initial Margin (Cost)
  - Amount of collateral required to open a position
- Maintenance Margin Rate
  - Minimum amount of collateral required to keep a position open
- Notional Size
  - Number of coins x current price
  - Total value of your position
# Leverage
- To know the posicion size we have a formula for that
  ```
    Risk ($) / Entry - Stop Loss
    Example: 
    We want to risk $10 
    Entry = $10.60
    Stop Loss = $10.10
    10/(10.60-10.10) = 20 units of the asset
    20x(entry price)=size in dolars
  ```
# Info
- Initial Margin Base value and Maitenance margin base value can be found in the info of the broker
- Maitenance margin is different from coin to coin.. using 50x does not mean you can handle the trade in 2% until get liquidated because of this margin
# Types of margin
- Cross Margin
  - In case of liquidation it can rely on another open positions
  - Supposing we have 3 positions (BTC,ETH and SHIBA), in case shiba goes wrong it will grab BTC and ETH positions to support the shiba losses
- Isolated
  - In case of liquidation it only relys on the position itself
  - Supposing we have a position on BTC,ETH and shiba in case shiba is about to get liquidated it simply gets liquidated and enables us to maintain BTC and ETH