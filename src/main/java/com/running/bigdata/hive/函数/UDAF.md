| 类名                               | 函数名                                                       | 用法                         |
|----------------------------------|-----------------------------------------------------------|----------------------------|
| GenericUDAFAverage               | average(x)                                                | 返回一组数字的平均值                 |
| GenericUDAFBinarySetFunctions    | regr_count(y,x)                                           | 返回非 null 对的数量;x，y必须保证是数值类型 |
| GenericUDAFBloomFilter           | 布隆过滤器                                                     |               
| GenericUDAFBridge                | 不关注，该类是连接新旧UDAF函数的桥接类                                     |
| GenericUDAFCollectList           | collect_list(x)                                           | 通过分组，将一列中多行数据聚合为数组，不过滤重复项  |
| GenericUDAFCollectSet            | collect_set(x)                                            | 通过分组，将一列中多行数据聚合为数组，过滤重复项             |
| GenericUDAFComputeStats          | compute_stats(x)                                          | 返回一组基元类型值的统计摘要             |
| GenericUDAFContextNGrams         | context_ngrams(expr, array<string1, string2, ...>, k, pf) |                            |
| GenericUDAFCorrelation           | corr(y,x)                                                 | 返回一组数对之间的 Pearson 相关系数     |
| GenericUDAFCount                 | count(*)                                                  | 返回检索到的行总数，包括包含 NULL 值的行    |
| GenericUDAFCovariance            | covariance,covar_pop(x,y)                                 | 返回一组数对的总体斜方差               |
| GenericUDAFCovarianceSample      | covar_samp(x,y)                                           | 返回一组数字对的样本斜方差              |
| GenericUDAFCumeDist              | cume_dist(x)                                              |                            |
| GenericUDAFDenseRank             | dense_rank                                                | 稀疏排名                       |
| GenericUDAFEvaluator             | 无需关注                                                      |                            |
| GenericUDAFFirstValue            | first_value(x)                                            |                            |
| GenericUDAFHistogramNumeric      | histogram_numeric(expr, nb)                               | 使用 nb bin 计算数字“expr”的直方图   |
| GenericUDAFLag                   | lag(expr, amt, default)                                   |                            |
| GenericUDAFLastValue             | last_value(x)                                             |                            |
| GenericUDAFLead                  | lead(expr, amt, default)                                  |                            |
| GenericUDAFLeadLag               | 抽象类不关注                                                    |                            |
| GenericUDAFMax                   | max(expr)                                                 |                            |
| GenericUDAFMin                   | min(expr)                                                 |                            |
| GenericUDAFMkCollectionEvaluator | 不关注                                                       |                            |
| GenericUDAFnGrams                | ngrams(expr, n, k, pf)                                    |                            |
| GenericUDAFNTile                 | ntile(x)                                                  |                            |
| GenericUDAFParameterInfo         | 接口，不关注                                                    |                            |
| GenericUDAFPercentileApprox      | percentile_approx(expr, pc, [nb])                         |                            |
| GenericUDAFPercentRank           | percent_rank(x)                                           |                            |
| GenericUDAFRank                  | rank(x)                                                   |                            |
| GenericUDAFResolver              | 不关注                                                       |                            |
| GenericUDAFResolver2             | 不关注                                                       |                            |
| GenericUDAFRowNumber             | row_number()                                              |                            |
| GenericUDAFStd                   | std,stddev,stddev_pop(x)                                  |                            |
| GenericUDAFStdSample             | stddev_samp(x)                                            |                            |
| GenericUDAFStreamingEvaluator    | 抽象类，不关注                                                   |                            |
| GenericUDAFSum                   | sum(x)                                                    |                            |
| GenericUDAFSumEmptyIsZero        | $SUM0(x)                                                  |                            |
| GenericUDAFVariance              | variance,var_pop(x)                                       |                            |
| GenericUDAFVarianceSample        | var_samp(x)                                               | 