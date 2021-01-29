# cppi
Constant Proportion Portfolio Insurance
# Summary
I am calculating industry indixes from S&P500 stocks, modeling CPPI and comparing with industry returns
# Results
CPPI allows to calculate allocations to risky and "safe" assets based on the risk appetite and industry performance and change these allocations dynamically.

![image info](./riskysafe.png)
<br>
![image info](./riskyalloc.png)

# Performance Comparison
### Bond + Equity combination
| Industry | Annualized Return | Annualized Vol | Sharpe Ratio | Max Drawdown |
|--------------|---|---|---|---|
|Transportation| 0.004125  |  0.029184 | -0.862939	  |  -0.17508 |
|Energy Minerals| -0.007116	  | 0.022741	  | -1.588453	  |-0.21078   |

### Pure Equity portfolio
| Industry | Annualized Return | Annualized Vol | Sharpe Ratio | Max Drawdown |
|--------------|---|---|---|---|
|Transportation| 0.009863	  |  0.079046 | -0.248029	  |  -0.348676 |
|Energy Minerals| -0.016292	  | 0.126969	  | -0.354979	  |-0.586560   |
