

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


### $2磁场 磁感应强度
#### 安培分子电流假说
>物质的每个分子都存在着回路电流
>磁场现象的本源是电荷的运动
#### 磁场
1. **磁场的作用本质**
	磁作用本质：磁场（磁体、电流、运动电荷产生磁场，相互）
	磁场是一种物质，具有物质性
	电场与电荷有关，磁场与运动电荷有关
	
2. **磁感应强度B**
	**磁场方向**：场中各点有一特定方向，电荷沿该方向运动不受磁力作用
	垂直于磁场方向运动，电荷受磁力最大
	运动电荷受磁场力方向垂直于运动方向和磁场方向
	方向：该点小磁针N极所指方向

#### 运动电荷产生的磁场
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

### $4 表述磁场性质的两条定理
#### 一、磁场的高斯定理
>磁通量：通过磁场任一曲面的磁场线条数
>$d\Phi_{m}=BdS_⊥=BdS\cos\theta=\overrightarrow{B}d\overrightarrow{S}$
>因为磁场线闭合，$\oint_S{\overrightarrow{B}d\overrightarrow{S}} = 0$

无源场

#### 二、安培环路定理
>$\oint_l{\overrightarrow{B}d\overrightarrow{l}} = ?$
>1. 类比，研究特殊情况：无限长直导线
>![[Physics2_C3S4.jpg]]
>此环路上，磁场大小方向相同。
>2. 平面内任意环路
>$\oint_l{\overrightarrow{B}\cdot d\overrightarrow{l}}=\mu_0\sum\limits_{内}{I_i}$

非保守场                                                                                                              
#### 三、安培环路定理的应用
1. 根据电流分布研究磁场分布
2. 选取适当的闭合环路：通过所有磁场的点、环路上各点B=常量、形状简单
3. 选择绕向，确定电流正负(右手螺旋法则)

#### 总结


### $5 磁场对电流的作用
#### 洛伦兹力
$\overrightarrow{F_L}=q\overrightarrow{v}\times\overrightarrow{B}$
普遍情况下，空间中电场与磁场同时存在
$\overrightarrow{F}=$

#### 三、有磁介质时磁场基本性质
1. 高斯定理
2. 安培环路定理$\oint_l{\overrightarrow{B}\cdot d\overrightarrow{l}}=\mu\sum_{内}{I}=\mu_{0}\sum_{内}{I_i(传感电流)+I_s(磁化电流)}$
	真空中磁导率$\mu_0$    磁介质磁导率$\mu_r$ 总磁导率$\mu=\mu_0+\mu_r$
	令磁场强度$\overrightarrow{H}=\frac{\overrightarrow{B}}{\mu}$
	所以磁场强度是一个辅助物理量反应磁场分布，与所有传导电流和磁化电流有关
	$\oint_l{\overrightarrow{H}\cdot d\overrightarrow{l} = \sum_内{I_i}}$
#### 四、利用介质场的安培环路定理进行磁场计算


## 第四章 电磁感应与电磁场
世界是对称和谐的：奥斯特 电流→磁场  磁场→？电流     法拉第经过了10年的努力：电磁感应定律

# 第四篇 热学
- **热学的研究对象**
	热现象：凡与温度有关的现象
	热运动：宏观物体内部大量微观粒子（分子、原子、电子）的无规则运动。
	热运动是热现象的**微观本质**，热现象是热运动的**宏观表现**。
- 微观量与宏观量
	微观量：每一个运动着的分子或原子都具有的质量、速度、动量、能量等量。
	宏观量：表征大量分子集体特性的物理量，如温度、压强、体积等量。
	宏观量与微观量的内在联系表现在大量分子杂乱无章的热运动遵从一定的统计规律性上。在实验中，所测量到的宏观量只是大量分子热运动（微观量）的统计平均值。
- 热学的研究方法
	热运动的统计描述方法出发形成了分子物理学—统计物理学
	由宏观方法出发，发展成为热力学
## 第一章 气体动理论 
### §1 分子热运动与统计规律
 ````mermaid
%%{init: {'theme': 'default', 'flowchart': {'useMaxWidth': true}}}%%
 graph LR
 G-->P
 G-->C
 P["一、气体动理论基本观点"]
 P-->P1["1.分子的观点"]
 P1-->P1A[宏观物质]
 P1A-->|"组成"|P1B[分子]
 P-->P2["2.分子运动观点"]
 P2-->P2A[扩散现象]
 P2-->P2B[布朗运动]
 P-->P3["3.分子力的观点"]
 P3-->P3A[分组相互作用力]
 C["二、统计规律性的基本概念"]
 C-->C1["1.概率"]
 C1-->C1A[定义]
 C1-->C1B[概率归一化条件]
 C1-->C1C["概率密度(概率分布函数)"]
 C-->C2["2.统计平均值"]
 C-->C3["3.统计基本假设"]
 ````
**概率定义**：$P_i=\lim\limits_{N\to\infty}\frac{N_{i}}{{N}}$
**概率归一化条件**：$\sum\limits_{i=1}^nP_i=1$
**概率密度（概率分布函数）**：若事件A的量值x可以连续变化，设A出现在某一间隔$\Delta{x}$内的概率为$\Delta{P(x)}$则 $f(x)=\lim\limits_{\Delta{x}\to{0}}{\frac{\Delta{P}}{\Delta{x}}}=\frac{dP}{dx}$
### §2理想气体状态方程

| 概念          | 关键公式 / 描述                                                                                         | 备注                                                                |
| ----------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **宏观 ↔ 微观** | 宏观量 = 微观量统计平均                                                                                     | 例：压强 $p$、温度 $T$ 为宏观量；分子速度 $v$、动能 $E_k$ 为微观量                       |
| **三大基本观点**  | ① 物质由大量分子组成，分子间有空隙<br>② 分子永不停息做无规则热运动（扩散、布朗运动）<br>③ 分子间存在引力和斥力，平衡距离 $d_0\sim10^{-10}\ \mathrm{m}$ | 布朗运动剧烈程度 $\propto T$                                              |
| **统计规律性**   | 大量偶然事件 → 必然分布（伽尔顿板）                                                                               | 概率归一：$\displaystyle\sum_i P_i=1$ 或 $\displaystyle\int f(x)\,dx=1$ |
| **统计平均值**   | 离散：$\langle x\rangle=\sum_i x_i P_i$<br>连续：$\langle x\rangle=\int x f(x)\,dx$                     | $f(x)$ 为概率密度                                                      |

| 概念           | 关键公式 / 描述                                    | 备注                                                                          |
| ------------ | -------------------------------------------- | --------------------------------------------------------------------------- |
| **理想气体模型**   | ① 分子质点化<br>② 除碰撞外无相互作用<br>③ 弹性碰撞             | 适用条件：低压、高温                                                                  |
| **状态参量**     | 压强 $p$，体积 $V$，温度 $T$                         | 平衡态：宏观量不随时间变化                                                               |
| **理想气体状态方程** | $$pV = \nu RT = \frac{m}{M_{\text{mol}}}RT$$ | $R=8.31\ \mathrm{J/(mol\cdot K)}$<br>$\nu$：物质的量                             |
| **分子数形式**    | $$p = nkT$$                                  | $n=\frac{N}{V}$：分子数密度<br>$k=\frac{R}{N_A}=1.38\times10^{-23}\ \mathrm{J/K}$ |
| **摩尔质量关系**   | $$M_{\text{mol}} = N_A m_0$$                 | $m_0$：单个分子质量                                                                |

### §3 理想气体的压强和温度的统计意义
#### 一、平衡态理想气体的统计假设
各种统计值：如平均速率 方均速率
#### 二、理想气体压强统计意义

$\begin{matrix}\text{单个分子碰撞容器壁，给予容器壁冲量}\to\text{单个分子1秒冲量}\to\text{多个分子冲量}\\\to\text{冲量统计值}\to\text{压力}\to\text{一个面的压强}\xrightarrow{各个方向速度平方统计值相同}\text{总压强}\end{matrix}$

动能统计平均值：$\overline{E_k}=\frac{1}{2}m_0\overline{v^2}$ 将压强转为动能表示：$p=\frac{1}{3}nm_{0}\bar{v^2}=\frac{2}{3}n\overline{E_k}$ 
>*宏观量**压强**的微观本质、微观统计含义*
#### 三、温度的微观意义
温度与微观粒子的动能有关
````col
```col-md
由压强 $\large\left. \begin{matrix}p=nkT\\p=\frac{2}{3}n\overline{E_k}\end{matrix}\right\}\to T=\frac{2}{3k}\overline{E_k}$
```
```col-md
结论：
温度标志着物体内部大量分子无规则运动剧烈程度，是分子热运动平均平动动能的亮度
```
````
\*k是什么？$k=\frac{R}{N_A}$ $M_mol=m_0N_A$
$\large\sqrt{\overline{v^2}}=v_{rms}$ 方均根速率，是速率的量纲  其它表示：$\large\sqrt{\frac{3kT}{m_{0}}}=\sqrt{\frac{3RT}{M_{mol}}}$

习题：例一[^4.1.3-1]例二[^4.1.3-2]

### §4 能量按自由度均分定理
分子动能=平动+转动动能+振动动能
\*振动可以被视为平动吗？

#### 一、自由度
确定一个物体所需的独立坐标数目
##### 1. 刚体的自由度
(1) 任意刚体：平动 $(x,y,z)$ 转动
(2)
##### 2. 刚性分子自由度 (不考虑分子的振动)

|     | 平动自由度 $t$ |     |     |
| --- | --------- | --- | --- |
| 单原子 | 3         | 0   | 3   |
| 双   | 3         | 2   | 5   |
| 三   | 3         | 3   | 6   |
#### 二、能量按自由度均分原理
理想气体分子的平均平动动能：$\overline{E_k}=$
由于分量平均速度和速度的关系，得到动能分量

\*振动去哪了？
\*什么是转动动能
#### 三、理想气体的内能
...
结论：理想气体的内能只与温度有关，是温度的单值函数

### §5
单个气体分子的运动是随机的、偶然的，大量气体分子整体而言，速率分布有必然确定的统计规律性。
方法：
测量装置：
要保证粒子能够通过，$t=\frac{l}{v}, \omega t \leq\phi$ 由此可以筛选不同速度的粒子
#### 一、
？


$f(v) = 4\pi \left( \frac{m}{2\pi k T} \right)^{\frac{3}{2}} v^2 \exp\left(-\frac{m v^2}{2 k T}\right)$

## 第二章 热力学基础
1. 功、热量、内能
2. 热力学第一定律
3. 循环过程
	热机效率(<1)
	致冷系数(可能>1)
4. 热力学第二定律
	功转化为热：可能的   热自发转化为功：不可能→热力学的方向性
	开尔文表述：
	克劳修斯表述：
	热力学第二定律统计意义：
>[热力学第二定律微观意义：]
>孤立系统内一切自然过程沿分子运动增大方向无序进行
>[热功转换]
>功→热：分子有序运动向无序运动转化
>热→功(自动)：分子无序运动自动转化为有序运动，不可能
>[绝热自由膨胀]
>占有较小空间→较大空间 ✓
>占有较大空间→较小空间 ✗

不可逆过程实质上是从概率较小状态到概率较大状态的变化的过程

这一章不考。

# 第五篇 近代物理
视1900年以后的物理为近代物理。
1900年开会：开尔文说，物理学的大厦已经建成，后辈物理学家只能做一些修修补补的工作。

在物理学晴朗天空的远处，还有两朵小小的令人不安的乌云。
## 第二章 量子物理基础
### §1 热辐射 普朗克能量子假设
````mermaid
%%{init: {'flowchart': { 'useMaxWidth': true } }}%%
graph LR
S[§1]
S-->P1[热辐射研究的动因]
S-->P2[黑体辐射]
S-->P3[普朗克量子论]
P2-->P21["1.热辐射现象"]
P21-->P211["固体或液体在任何温度下都向外辐射电磁波"]
P21-->P212["固体在温度升高时颜色的变化"]
P212-->P212K800["<font color="#FF8C38">800K</font>"]
P212-->P2400K["<font color="#FFF4B9">2400K</font>"]
P212-->P4000K["<font color="#E1FFFA">4000K</font>"]
P212-->P5600K["<font color="#B1D3FF">5600K</font>"]
P212-->P7200K["<font color="#81B5FF">7200K</font>"]
P21-->P21C[物体辐射电磁波的同时，也吸收电磁波；物体辐射本领越大，其吸收本领也越大]
P21C-->P21C1[发射 > 吸收，温度下降]
P21C-->P21C2[发射 < 吸收，温度升高]
P21C-->P21C3[平衡热辐射]
P2-->P22["2.绝对黑体"]
P22-->P22C1["吸收比=吸收能量/入射总能量"]
P22-->P22C2["黑体：对于任何温度、任何波长吸收比等于一的物体；即能全部吸收各种波长的辐射且不反射和透射的物体。"]
P22C2-->P22S[黑体辐射特点]
P2-->P23["3.单色辐出度M<sub>lambda</sub>(T)"]
P2-->P24["4.总辐出度M(T)"]
P2-->P25["5.黑体的辐射规律"]
P25-->P251["黑体单色辐出度"]
P25-->P252["两条黑体辐射定律"]
P3-->P31["1.维恩半经验公式"]-->P3C
P3-->P32["2.瑞利-金斯公式"]-->P3C
P3C[经典物理学思想]
P3-->P3P[能量量子化-普朗克能量子假设]
P3P-->P3PP[普朗克公式]
````


<font color="#FF8C38">800K</font>
<font color="#FF9E4A">1000K</font>
<font color="#FFAD5C">1200K</font>
<font color="#FFBB6D">1400K</font>
<font color="#FFC87E">1600K</font>
<font color="#FFD48F">1800K</font>
<font color="#FFDFA0">2000K</font>
<font color="#FFEAAD">2200K</font>
<font color="#FFF4B9">2400K</font>
<font color="#FFF9C4">2600K</font>
<font color="#FFFECE">2800K</font>
<font color="#FFFFD7">3000K</font>
<font color="#F9FFE0">3200K</font>
<font color="#F3FFE7">3400K</font>
<font color="#EDFFEF">3600K</font>
<font color="#E7FFF5">3800K</font>
<font color="#E1FFFA">4000K</font>
<font color="#DBFFFD">4200K</font>
<font color="#D5F9FF">4400K</font>
<font color="#CFF3FF">4600K</font>
<font color="#C9EDFF">4800K</font>
<font color="#C3E7FF">5000K</font>
<font color="#BDDFFF">5200K</font>
<font color="#B7D9FF">5400K</font>
<font color="#B1D3FF">5600K</font>
<font color="#ABDFFF">5800K</font>
<font color="#A5D9FF">6000K</font>
<font color="#9FD3FF">6200K</font>
<font color="#99CDFF">6400K</font>
<font color="#93C7FF">6600K</font>
<font color="#8DC1FF">6800K</font>
<font color="#87BBFF">7000K</font>
<font color="#81B5FF">7200K</font>
<font color="#7BBFFF">7400K</font>
<font color="#75B9FF">7600K</font>
<font color="#6FB3FF">7800K</font>
<font color="#69ADFF">8000K</font>
<font color="#63A7FF">8200K</font>
<font color="#5DA1FF">8400K</font>
<font color="#57ABFF">8600K</font>
<font color="#51A5FF">8800K</font>
<font color="#4BAFFF">9000K</font>
<font color="#4B9FFF">9500K</font>
<font color="#4A8FFF">10000K</font>
<font color="#497FFF">10500K</font>
<font color="#486FFF">11000K</font>
<font color="#475FFF">11500K</font>
<font color="#464FFF">12000K</font>
