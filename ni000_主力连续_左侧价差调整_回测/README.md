# strategy_report_daybreak
日内突破策略回测

## RB回测
python3 ../backtest.py -m B -d 1000 -sf CTA_setting_RSIDayBreakPlus.json  -s ni000

### 20分钟级别 停止单交易 加仓 小时波动率移动止损 左侧价差调整 策略


<center>


![](RSIDayBreakPlusStopOrder_20_ni000_True.png)

```
--------------------------------------------------
                 0                    1
0       第一笔交易  2016-11-15 10:46:00
1     最后一笔交易  2019-08-08 23:36:00
2       总交易次数                1,395
3     多头交易次数                  700
4     空头交易次数                  695
5         期末净值                 1.49
6           总盈亏            49,446.16
7       年化收益率                 0.16
8       收益回撤比                -1.69
9         最大回撤           -12,684.97
10  最大回撤百分比                -0.09
11    平均每笔盈利                35.45
12    平均每笔滑点                 20.0
13    平均每笔佣金                19.27
14            胜率                37.63
15  盈利交易平均值               657.73
16  亏损交易平均值              -340.07
17          盈亏比                 1.93
18    多仓平均利润                34.47
19    空仓平均利润                36.43
计算按日统计结果
--------------------------------------------------
                   0              1
0       首个交易日：     2016-11-14
1       最后交易日：     2019-08-08
2         总交易日：            790
3         盈利交易日            269
4       亏损交易日：            414
5         起始资金：         100000
6         结束资金：     149,491.39
7         总收益率：          49.49
8         年化收益：          15.04
9           总盈亏：      49,491.39
10        最大回撤:      -12,837.88
11  百分比最大回撤:          -10.84
12        总手续费：      26,860.61
13          总滑点：         27,880
14      总成交金额：  268,606,126.0
15      总成交笔数：          2,518
16        日均盈亏：          62.65
17      日均手续费：           34.0
18        日均滑点：          35.29
19    日均成交金额：     340,007.75
20    日均成交笔数：           3.19
21      日均收益率：           0.05
22      收益标准差：           0.98
23    Sharpe Ratio：           0.79
--------------------------------------------------
```

</center>

### 30分钟级别 停止单交易 加仓 小时波动率移动止损 左侧价差调整 策略


<center>


![](RSIDayBreakPlusStopOrder_30_ni000_True.png)

```
--------------------------------------------------
                 0                    1
0       第一笔交易  2016-11-15 10:47:00
1     最后一笔交易  2019-08-08 23:36:00
2       总交易次数                1,350
3     多头交易次数                  682
4     空头交易次数                  668
5         期末净值                 1.39
6           总盈亏            38,533.59
7       年化收益率                 0.13
8       收益回撤比                -1.12
9         最大回撤           -14,305.46
10  最大回撤百分比                -0.11
11    平均每笔盈利                28.54
12    平均每笔滑点                 20.0
13    平均每笔佣金                19.25
14            胜率                36.59
15  盈利交易平均值                666.6
16  亏损交易平均值              -339.68
17          盈亏比                 1.96
18    多仓平均利润                36.96
19    空仓平均利润                19.95
计算按日统计结果
--------------------------------------------------
                   0              1
0       首个交易日：     2016-11-14
1       最后交易日：     2019-08-08
2         总交易日：            790
3         盈利交易日            256
4       亏损交易日：            419
5         起始资金：         100000
6         结束资金：     138,578.81
7         总收益率：          38.58
8         年化收益：          11.72
9           总盈亏：      38,578.81
10        最大回撤:      -14,478.37
11  百分比最大回撤:          -13.32
12        总手续费：      25,958.19
13          总滑点：         26,980
14      总成交金额：  259,581,865.0
15      总成交笔数：          2,447
16        日均盈亏：          48.83
17      日均手续费：          32.86
18        日均滑点：          34.15
19    日均成交金额：     328,584.64
20    日均成交笔数：            3.1
21      日均收益率：           0.04
22      收益标准差：           1.07
23    Sharpe Ratio：           0.59
--------------------------------------------------
```

</center>
