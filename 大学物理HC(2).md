

## $1 稳恒电流的基本概念
>通过任意导体界面的电流强度不随时间变化的电流
### 一、电流和电流密度
#### 电流
>大量载流子定向运动
>形成条件：导体内有可移动电荷、导体两端有电压差
#### 电流强度
>单位时间内通过某截面的电量
#### 电流密度矢量
>通过垂直于载流子运动方向的单位面积的**电流强度**
$\delta = \frac{dl}{ds_\perp}$
$I = \int_S{\overrightarrow{\delta}\cdot{dS}}$

#### 电流密度与电荷的运动的关系


## $2磁场 磁感应强度
### 安培分子电流假说
>物质的每个分子都存在着回路电流
>磁场现象的本源是电荷的运动
### 磁场
1. **磁场的作用本质**
	磁作用本质：磁场（磁体、电流、运动电荷产生磁场，相互）
	磁场是一种物质，具有物质性
	电场与电荷有关，磁场与运动电荷有关
	
2. **磁感应强度B**
	**磁场方向**：场中各点有一特定方向，电荷沿该方向运动不受磁力作用
	垂直于磁场方向运动，电荷受磁力最大
	运动电荷受磁场力方向垂直于运动方向和磁场方向
	方向：该点小磁针N极所指方向

### 运动电荷产生的磁场
**电荷元**: de = dE....
**电流元**: 运动电荷组成的体系$Id\overrightarrow{l} =....$
$d\overrightarrow{B} = k\frac{Idlsin\alpha}{r^2}$,

>#### 一个运动电荷产生的磁场有何特性：
>(I = nqvS)$d \overrightarrow{B}=\frac{\mu}{4\pi}\frac{(qnSv)d\overrightarrow{l}\times{\overrightarrow{r_{0}}}}{r^{2}}$
>每个以速度v运动，电荷量为q的电荷产生的磁感应强度：$\overrightarrow{B}=\frac{d\overrightarrow{B}}{d \overrightarrow{N}}=\frac{\mu}{4\pi}\frac{q \overrightarrow{v}\times{\overrightarrow{r_{0}}}}{r^{2}}$

在真空中磁导率为$\begin{matrix}dB = \frac{\mu_0}{4\pi}\frac{Id\overrightarrow{l}\times{\overrightarrow{r_0}}}{r^2}\\ \mu_0 = 4\pi\times10^{-7}N\cdot A^{-2} \end{matrix}$
方向：手指指向电流元方向，弯曲向单位矢量方向(从电流元指向所求点位置)，拇指方向是场强方向
#### 毕-萨定律一般步骤
1. 选择电流元Idl
2. 写出此电流元在某点场强大小
3. 确定dB方向
4. 建立坐标系，求分量$dB_x$
5. 积分$B_x = \int{dB_x}$
6. 矢量和$\overrightarrow{B}=B_x\overrightarrow{i}+B_y\overrightarrow{j}+B_z\overrightarrow{k}$
##### 经典类型
##### 1. 有限长直导线的磁感应强度
>P点对于导线两端连线的夹角(水平分割)$B =\frac{\mu_0 I}{4 \pi a}(\sin{\beta_2}-\sin{\beta_1})$
>导线无限长：$\beta_2 = \frac{\pi}{2}\beta_1 = -\frac{\pi}{2}\;B =\frac{\mu_0 I}{2 \pi a}$
>导线半无限长：$B =\frac{\mu_0 I}{4 \pi a}$
>P点在导线延长线上$B=0$

##### 2. 圆环，P点位于轴线
>$B = \frac{\mu_0 IR^2}{2(R^2+x^2)^{\frac{3}{2}}}$

## $4 表述磁场性质的两条定理
### 一、磁场的高斯定理
>磁通量：通过磁场任一曲面的磁场线条数
>$d\Phi_{m}=BdS_⊥=BdS\cos\theta=\overrightarrow{B}d\overrightarrow{S}$
>因为磁场线闭合，$\oint_S{\overrightarrow{B}d\overrightarrow{S}} = 0$

无源场

### 二、安培环路定理
>$\oint_l{\overrightarrow{B}d\overrightarrow{l}} = ?$
>1. 类比，研究特殊情况：无限长直导线
>![[Physics2_C3S4.jpg]]
>此环路上，磁场大小方向相同。
>2. 平面内任意环路
>$\oint_l{\overrightarrow{B}\cdot d\overrightarrow{l}}=\mu_0\sum\limits_{内}{I_i}$

非保守场                                                                                                              
### 三、安培环路定理的应用
1. 根据电流分布研究磁场分布
2. 选取适当的闭合环路：通过所有磁场的点、环路上各点B=常量、形状简单
3. 选择绕向，确定电流正负(右手螺旋法则)

#### 总结


## $5 磁场对电流的作用
### 洛伦兹力
$\overrightarrow{F_L}=q\overrightarrow{v}\times\overrightarrow{B}$
普遍情况下，空间中电场与磁场同时存在
$\overrightarrow{F}=$

### 三、有磁介质时磁场基本性质
1. 高斯定理
2. 安培环路定理$\oint_l{\overrightarrow{B}\cdot d\overrightarrow{l}}=\mu\sum_{内}{I}=\mu_{0}\sum_{内}{I_i(传感电流)+I_s(磁化电流)}$
	真空中磁导率$\mu_0$    磁介质磁导率$\mu_r$ 总磁导率$\mu=\mu_0+\mu_r$
	令磁场强度$\overrightarrow{H}=\frac{\overrightarrow{B}}{\mu}$
	所以磁场强度是一个辅助物理量反应磁场分布，与所有传导电流和磁化电流有关
	$\oint_l{\overrightarrow{H}\cdot d\overrightarrow{l} = \sum_内{I_i}}$
### 四、利用介质场的安培环路定理进行磁场计算


# 第四章 电磁感应与电磁场
世界是对称和谐的：奥斯特 电流→磁场  磁场→？电流     法拉第经过了10年的努力：电磁感应定律
