# realty房地产分析


## 应用技术


python


# 时间序列


时间序列分析是根据系统观测得到的时间序列数据，通过曲线拟合和参数估计来建立数学模型的理论和方法。它一般采用曲线拟合和参数估计方法（如非线性最小二乘法）进行。时间序列分析常用在国民经济宏观控制、区域综合发展规划、企业经营管理、市场潜量预测、气象预报、水文预报、地震前兆预报、农作物病虫灾害预报、环境污染控制、生态平衡、天文学和海洋学等方面。


# ARMA模型


ARMA模型的全称是自回归移动平均(auto regression moving average)模型，它是目前最常用的拟合平稳序列的模型，它又可细分为AR模型(auto regression model)、MA模型(moving average model)和ARMA模型(auto regression moving average model)三大类。


## AR模型：


一般的p阶自回归过程AR(p)是


Xt=j1Xt-1+ j2Xt-2 + … + jpXt-p + mt (*)


如果随机扰动项是一个白噪声(mt=et)，则称(*)式为一纯AR(p)过程（pure AR(p) process），记为


Xt=j1Xt-1+ j2Xt-2 + … + jpXt-p +et


## MA模型


如果mt不是一个白噪声，通常认为它是一个q阶的移动平均（moving average）过程MA(q)：


mt=et - q1et-1 - q2et-2 - ¼ - qqet-q


该式给出了一个纯MA(q)过程（pure MA(p) process）。


## ARMA模型：


将纯AR(p)与纯MA(q)结合，得到一个一般的自回归移动平均（autoregressive moving average）过程ARMA（p,q）：


Xt=j1Xt-1+ j2Xt-2 + … + jpXt-p + et - q1et-1 - q2et-2 - ¼ - qqet-q


## 限制条件
- 条件一：
这个限制条件保证了模型的最高阶数。
- 条件二：
这个限制条件实际上是要求随机干扰序列 为零均值白噪声序列。
- 条件三：
这个限制条件说明当期的随机干扰与过去的序列值无关。


