---
sidebar_position: 4 
---

# 挖矿减半规则

本文介绍MVC区块链的挖矿减半规则。

## 什么是减半？

以比特币的减半为例。

比特币的挖矿奖励是指每个区块被挖出时，矿工获得的比特币数量（新创建的比特币，并不计算手续费）。比特币的挖矿奖励减半是为了控制比特币的发行速度，以保持比特币的稀缺性。随着比特币发行速度的指数减半，比特币的总量将逐渐接近2100万枚。

比特币区块链上每生成210,000个区块时，比特币网络对矿工的区块奖励减半的事件。这大约每四年发生一次。减半事件旨在控制比特币的供应量，使其逐步减少，从而防止通货膨胀并增加稀缺性。

1. **矿工奖励**
   ：在比特币网络的初期，每生成一个区块，矿工可以获得50个比特币的奖励。2012年首次减半后，奖励减为25个比特币。2016年第二次减半后，奖励减为12.5个比特币。2020年第三次减半后，奖励减为6.25个比特币。
2. **时间间隔**：比特币区块大约每10分钟生成一个，因此210,000个区块大约需要4年时间。
3. **未来减半**：减半事件会一直持续，直到区块奖励接近于零。

### 2100万上限的计算

以下是比特币减半各阶段的详细表格：

| 阶段   | 每区块奖励（比特币）                      | 区块数量   | 该阶段比特币数量                    |
|------|---------------------------------|--------|-----------------------------|
| 阶段1  | 50                              | 210000 | 10500000                    |
| 阶段2  | 25                              | 210000 | 5250000                     |
| 阶段3  | 12.5                            | 210000 | 2625000                     |
| 阶段4  | 6.25                            | 210000 | 1312500                     |
| 阶段5  | 3.125                           | 210000 | 656250                      |
| 阶段6  | 1.5625                          | 210000 | 328125                      |
| 阶段7  | 0.78125                         | 210000 | 164062.5                    |
| 阶段8  | 0.390625                        | 210000 | 82031.25                    |
| 阶段9  | 0.1953125                       | 210000 | 41015.625                   |
| 阶段10 | 0.09765625                      | 210000 | 20507.8125                  |
| 阶段11 | 0.048828125                     | 210000 | 10253.90625                 |
| 阶段12 | 0.0244140625                    | 210000 | 5126.953125                 |
| 阶段13 | 0.01220703125                   | 210000 | 2563.4765625                |
| 阶段14 | 0.006103515625                  | 210000 | 1281.73828125               |
| 阶段15 | 0.0030517578125                 | 210000 | 640.869140625               |
| 阶段16 | 0.00152587890625                | 210000 | 320.4345703125              |
| 阶段17 | 0.000762939453125               | 210000 | 160.21728515625             |
| 阶段18 | 0.0003814697265625              | 210000 | 80.108642578125             |
| 阶段19 | 0.00019073486328125             | 210000 | 40.0543212890625            |
| ...  | ...                             | ...    | ...                         |
| 阶段29 | 0.000000186264514923095703125   | 210000 | 0.03911554813385009765625   |
| 阶段30 | 0.0000000931322574615478515625  | 210000 | 0.019557774066925048828125  |
| 阶段31 | 0.00000004656612873077392578125 | 210000 | 0.0097788870334625244140625 |

总供应量为：21,000,000 比特币。

这表明比特币的总供应量确实为2100万，是通过上述减半机制逐步计算得出的。

## MVC区块链的减半规则

MVC由于采用POW+POB混合共识机制，减半只作用于POW挖矿奖励(35%)，POB奖励不受减半影响。根据MVC的白皮书，MVC的减半规则如下：

| 规则      | 说明       |
|---------|----------|
| POW总发行量 | 7350000  |
| 减半区块数   | 147000   |
| 减半间隔估算  | 1000天    |
| 首次发行数量  | 25 space |

### MVC减半规则计算

我们可以用与比特币类似的方法来计算Space的总产量。Space的初始奖励为25，每147,000个区块减半一次。

### 每个阶段的Space数量计算：

以下是Space减半各阶段的详细表格：

| 阶段   | 每区块奖励（Space）                     | 区块数量   | 该阶段Space数量                    |
|------|----------------------------------|--------|-------------------------------|
| 阶段1  | 25                               | 147000 | 3,675,000                     |
| 阶段2  | 12.5                             | 147000 | 1,837,500                     |
| 阶段3  | 6.25                             | 147000 | 918,750                       |
| 阶段4  | 3.125                            | 147000 | 459,375                       |
| 阶段5  | 1.5625                           | 147000 | 229,687.5                     |
| 阶段6  | 0.78125                          | 147000 | 114,843.75                    |
| 阶段7  | 0.390625                         | 147000 | 57,421.875                    |
| 阶段8  | 0.1953125                        | 147000 | 28,710.9375                   |
| 阶段9  | 0.09765625                       | 147000 | 14,355.46875                  |
| 阶段10 | 0.048828125                      | 147000 | 7,177.734375                  |
| 阶段11 | 0.0244140625                     | 147000 | 3,588.8671875                 |
| 阶段12 | 0.01220703125                    | 147000 | 1,794.43359375                |
| 阶段13 | 0.006103515625                   | 147000 | 897.216796875                 |
| 阶段14 | 0.0030517578125                  | 147000 | 448.6083984375                |
| 阶段15 | 0.00152587890625                 | 147000 | 224.30419921875               |
| 阶段16 | 0.000762939453125                | 147000 | 112.152099609375              |
| 阶段17 | 0.0003814697265625               | 147000 | 56.0760498046875              |
| 阶段18 | 0.00019073486328125              | 147000 | 28.03802490234375             |
| ...  | ...                              | ...    | ...                           |
| 阶段28 | 0.000000186264514923095703125    | 147000 | 0.027380883693695068359375    |
| 阶段29 | 0.0000000931322574615478515625   | 147000 | 0.0136904418468475341796875   |
| 阶段30 | 0.00000004656612873077392578125  | 147000 | 0.00684522092342376708984375  |
| 阶段31 | 0.000000023283064365386962890625 | 147000 | 0.003422610461711883544921875 |

总供应量约为：7,350,000 Space。
