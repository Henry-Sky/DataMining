## 数据相关分析

1. **散点图**:  
    将两个属性的成对数据绘制在直角坐标系中，方便直观的判断

2. **相关系数**:  
    样本协方差: cov(X,Y) = $\frac{\sum\limits_{i=1}^n{(X_i-\overline{X})(Y_i-\overline{Y})}}{n - 1}$

    样本协方差含义: 正值正相关，负值负相关，零值不相关

    相关系数: r(X,Y) = $\frac{cov(X,Y)}{s_X s_Y}$

    相关系数含义: r = $[-1,1]$  
    &emsp;若 r = $[-1,0)$ 则负相关</br>
    &emsp;若 r = $(0,+1]$ 则正相关</br>
    &emsp;若 r = 0 则不相关

3. **卡方检验**:  
    公式: $\chi^2$ = $\sum\frac{(Observed - Expected)^2}{Expected}$  
    含义: 实际值与理论值的偏离程度  
    计算步骤:  
    &emsp;(a) 原假设: $H_0$ (独立), 备择假设: $H_1$ (相关)</br>
    &emsp;(b) 确定显著性水平 $\alpha$ ( 0.05 or 0.01 )</br>
    &emsp;(c) 计算 $\chi^2$ 和 $p-value$ 
    </br>(若 $p-value$ $\leq$ $\alpha$：关联在统计上显著，即否定$H_0$)</br>