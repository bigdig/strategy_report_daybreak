# strategy_report_daybreak
日内突破策略回测

## RB回测
python3 ../backtest.py -m B -d 100 -sf CTA_setting_RSIDayBreakPlus.json  -s rb1910

### 12分钟级别 加仓策略


<center>


![](rb1910/RSIDayBreakPlus_12_rb1910_True.png)

```
--------------------------------------------------
                 0                    1
0       第一笔交易  2019-05-06 14:18:00
1     最后一笔交易  2019-08-06 22:57:00
2       总交易次数                   64
3     多头交易次数                   27
4     空头交易次数                   37
5         期末净值                 1.04
6           总盈亏             4,297.22
7       年化收益率                 0.17
8       收益回撤比               -23.53
9         最大回撤              -732.44
10  最大回撤百分比                -0.01
11    平均每笔盈利                67.14
12    平均每笔滑点                 20.0
13    平均每笔佣金                  7.7
14            胜率                43.75
15  盈利交易平均值               325.16
16  亏损交易平均值              -133.53
17          盈亏比                 2.44
18    多仓平均利润                95.21
19    空仓平均利润                46.67
计算按日统计结果
--------------------------------------------------
                   0            1
0       首个交易日：   2019-04-30
1       最后交易日：   2019-08-07
2         总交易日：           61
3         盈利交易日           23
4       亏损交易日：           21
5         起始资金：       100000
6         结束资金：   104,297.22
7         总收益率：          4.3
8         年化收益：        16.91
9           总盈亏：     4,297.22
10        最大回撤:       -664.15
11  百分比最大回撤:         -0.66
12        总手续费：       492.78
13          总滑点：        1,280
14      总成交金额：  4,927,850.0
15      总成交笔数：          110
16        日均盈亏：        70.45
17      日均手续费：         8.08
18        日均滑点：        20.98
19    日均成交金额：    80,784.43
20    日均成交笔数：          1.8
21      日均收益率：         0.07
22      收益标准差：         0.35
23    Sharpe Ratio：         3.02
```


<img src="rb1910/pos.png" width="50%" height="100%">

局部开仓

</center>


### 30分钟级别 不加仓策略

<center>


![](rb1910_1/RSIDayBreak_30_rb1910_True.png)

```
--------------------------------------------------
                 0                    1
0       第一笔交易  2019-05-06 09:00:00
1     最后一笔交易  2019-08-07 09:01:00
2       总交易次数                   36
3     多头交易次数                   15
4     空头交易次数                   21
5         期末净值                 1.03
6           总盈亏             2,600.91
7       年化收益率                  0.1
8       收益回撤比                 -8.7
9         最大回撤            -1,307.55
10  最大回撤百分比                -0.01
11    平均每笔盈利                72.25
12    平均每笔滑点                 20.0
13    平均每笔佣金                 7.75
14            胜率                52.78
15  盈利交易平均值               312.32
16  亏损交易平均值              -196.07
17          盈亏比                 1.59
18    多仓平均利润               107.57
19    空仓平均利润                47.02
计算按日统计结果
--------------------------------------------------
                   0            1
0       首个交易日：   2019-04-30
1       最后交易日：   2019-08-07
2         总交易日：           61
3         盈利交易日           26
4       亏损交易日：           21
5         起始资金：       100000
6         结束资金：   102,600.91
7         总收益率：          2.6
8         年化收益：        10.23
9           总盈亏：     2,600.91
10        最大回撤:      -1,276.3
11  百分比最大回撤:         -1.28
12        总手续费：       279.09
13          总滑点：          720
14      总成交金额：  2,790,940.0
15      总成交笔数：           72
16        日均盈亏：        42.64
17      日均手续费：         4.58
18        日均滑点：         11.8
19    日均成交金额：    45,753.11
20    日均成交笔数：         1.18
21      日均收益率：         0.04
22      收益标准差：         0.27
23    Sharpe Ratio：         2.31
--------------------------------------------------
```


</center>




## NI 回测 不加仓

<center>


```
--------------------------------------------------
                 0                    1
0       第一笔交易  2016-11-14 10:06:00
1     最后一笔交易  2019-08-08 22:59:00
2       总交易次数                  745
3     多头交易次数                  384
4     空头交易次数                  361
5         期末净值                 2.63
6           总盈亏           163,061.79
7       年化收益率                 0.42
8       收益回撤比                -0.58
9         最大回撤           -87,815.29
10  最大回撤百分比                -0.73
11    平均每笔盈利               218.87
12    平均每笔滑点                 20.0
13    平均每笔佣金               190.91
14            胜率                36.91
15  盈利交易平均值             6,735.99
16  亏损交易平均值            -3,594.33
17          盈亏比                 1.87
18    多仓平均利润               253.63
19    空仓平均利润               181.91
计算按日统计结果
--------------------------------------------------
                   0                1
0       首个交易日：       2016-11-14
1       最后交易日：       2019-08-08
2         总交易日：              669
3         盈利交易日              215
4       亏损交易日：              335
5         起始资金：           100000
6         结束资金：       263,061.79
7         总收益率：           163.06
8         年化收益：             58.5
9           总盈亏：       163,061.79
10        最大回撤:        -92,482.06
11  百分比最大回撤:            -74.05
12        总手续费：       142,228.21
13          总滑点：           14,900
14      总成交金额：  1,422,282,130.0
15      总成交笔数：            1,490
16        日均盈亏：           243.74
17      日均手续费：            212.6
18        日均滑点：            22.27
19    日均成交金额：     2,125,982.26
20    日均成交笔数：             2.23
21      日均收益率：             0.17
22      收益标准差：             7.26
23    Sharpe Ratio：             0.35
--------------------------------------------------
```


</center>



## NI 回测 加仓

<center>

```

--------------------------------------------------
                 0                    1
0       第一笔交易  2016-11-14 10:06:00
1     最后一笔交易  2019-08-08 22:59:00
2       总交易次数                  964
3     多头交易次数                  498
4     空头交易次数                  466
5         期末净值                 3.81
6           总盈亏           280,624.55
7       年化收益率                 0.63
8       收益回撤比                -0.83
9         最大回撤          -134,738.95
10  最大回撤百分比                -0.76
11    平均每笔盈利                291.1
12    平均每笔滑点                 20.0
13    平均每笔佣金               191.57
14            胜率                37.97
15  盈利交易平均值             7,104.77
16  亏损交易平均值            -3,879.14
17          盈亏比                 1.83
18    多仓平均利润               370.68
19    空仓平均利润               206.06
计算按日统计结果
../../vnpy/trader/app/ctaStrategy/ctaBacktesting.py:1548: RuntimeWarning: invalid value encountered in log
  np.log(df['balance']) - np.log(df['balance'].shift(1))).fillna(0)
--------------------------------------------------
                   0                1
0       首个交易日：       2016-11-14
1       最后交易日：       2019-08-08
2         总交易日：              669
3         盈利交易日              206
4       亏损交易日：              357
5         起始资金：           100000
6         结束资金：       380,897.85
7         总收益率：            280.9
8         年化收益：           100.77
9           总盈亏：       280,897.85
10        最大回撤:       -135,426.83
11  百分比最大回撤:           -109.73
12        总手续费：       184,422.15
13          总滑点：           19,260
14      总成交金额：  1,844,221,460.0
15      总成交笔数：            1,733
16        日均盈亏：           419.88
17      日均手续费：           275.67
18        日均滑点：            28.79
19    日均成交金额：      2,756,683.8
20    日均成交笔数：             2.59
21      日均收益率：             0.08
22      收益标准差：            12.39
23    Sharpe Ratio：             0.09
--------------------------------------------------
```

</center>
