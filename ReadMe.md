本地分支obsidian在远端是Obsidian
# 快捷键与布局
参考WPS智能文档，使用Editing Toolbar实现
备份文件位于根目录下

# 公式
为公式插入空格：

| 命令       | 效果               |
| -------- | ---------------- |
| `\,`     | 小空格（约 0.1667em）  |
| `\:`     | 中等空格（约 0.2222em） |
| `\;`     | 大空格（约 0.2777em）  |
| `\!`     | 负空格（缩小间距）        |
| `\quad`  | 1em 空格           |
| `\qquad` | 2em 空格           |
为公式插入不等号：\leq
箭头上标：\xrightarrow{}
## 求导
| 效果                                    | 描述          | 代码                                          |
| ------------------------------------- | ----------- | ------------------------------------------- |
| $\lim$                                | lim         | `\lim`                                      |
| $\lim\limits_{x\to 0}$                | 极限下标        | `\lim\limits_{x\to 0}`                      |
| $\to$                                 | 普通右箭头       | `\to`                                       |
| $\xrightarrow{z\to z_0}$              | 带文字上标箭头（居中） | `\xrightarrow{z\to z_0}`                    |
| $\xleftarrow[\text{sub}]{\text{sup}}$ | 带文字下标箭头     | `\xleftarrow[\text{sub}]{\text{sup}}`       |
| $\xlongequal{\text{def}}$             | 长等号         | `\xlongequal{\text{def}}`（需 `extarrows` 宏包） |

| 效果                                            | 描述       | 代码                                                    |     |
| --------------------------------------------- | -------- | ----------------------------------------------------- | --- |
|                                               | 一阶导      | `f'(x)` 或 `\frac{dy}{dx}`                             |     |
|                                               | 二阶导      | `f''(x)` 或 `\frac{d^2y}{dx^2}`                        |     |
| $\frac{\partial f}{\partial x}$               | 偏导       | `\frac{\partial f}{\partial x}`                       |     |
| $\left. \frac{dy}{dx}  \right\|_{x=x_0}$      | **竖线条件** | `\left. \frac{dy}{dx} \right\|_{x=x_0}`               |     |
| $\mathrm{d}$$\frac{\mathrm{d}y}{\mathrm{d}x}$ | 全微分      | `\mathrm{d}`（正体 d）例：`\frac{\mathrm{d}y}{\mathrm{d}x}` |     |

| 公式 | 描述 | 代码 |
|---|---|---|
| $\sum_{k=1}^n a_k$ | 求和 | `\sum_{k=1}^n a_k` |
| $\int_a^b f(x)\,\mathrm{d}x$ | 积分 | `\int_a^b f(x)\,\mathrm{d}x` |
| $\iint_D f(x,y)\,\mathrm{d}\sigma$ | 双重积分 | `\iint_D f(x,y)\,\mathrm{d}\sigma` |
| $\prod_{i=1}^n x_i$ | 连乘 | `\prod_{i=1}^n x_i` |
| $\int\limits_0^1$ | 极限式积分（上下限在正上/正下） | `\int\limits_0^1` |

## 4. 集合与逻辑
| 公式 | 描述 | 代码 |
|---|---|---|
| $\in$ | 属于 | `\in` |
| $\subseteq$ | 子集 | `\subseteq` |
| $\subsetneq$ | 真子集 | `\subsetneq` |
| $\emptyset$ | 空集 | `\emptyset` |
| $\varnothing$ | 空集（另一种形式） | `\varnothing` |
| $\cup$ | 并集 | `\cup` |
| $\cap$ | 交集 | `\cap` |
| $\bigcup_{i=1}^n A_i$ | 大并集 | `\bigcup_{i=1}^n A_i` |
| $\bigcap_{i=1}^n A_i$ | 大交集 | `\bigcap_{i=1}^n A_i` |
| $\forall$ | 任意 | `\forall` |
| $\exists$ | 存在 | `\exists` |
| $\nexists$ | 否定存在 | `\nexists` |
| $\Rightarrow$ | 推出 | `\Rightarrow` |
| $\Leftrightarrow$ | 等价 | `\Leftrightarrow` |
| $\Longrightarrow$ | 长推出 | `\Longrightarrow` |

## 5. 希腊字母
| 公式 | 描述 | 代码 |
|---|---|---|
| $\alpha$ | 小写阿尔法 | `\alpha` |
| $\beta$ | 小写贝塔 | `\beta` |
| $\gamma$ | 小写伽马 | `\gamma` |
| $\Gamma$ | 大写伽马 | `\Gamma` |
| $\delta$ | 小写德尔塔 | `\delta` |
| $\Delta$ | 大写德尔塔 | `\Delta` |
| $\varepsilon$ | 小写伊普西隆（弯 e） | `\varepsilon` |
| $\theta$ | 小写西塔 | `\theta` |
| $\Theta$ | 大写西塔 | `\Theta` |
| $\lambda$ | 小写兰姆达 | `\lambda` |
| $\Lambda$ | 大写兰姆达 | `\Lambda` |
| $\mu$ | 小写缪 | `\mu` |
| $\pi$ | 小写派 | `\pi` |
| $\Pi$ | 大写派 | `\Pi` |
| $\sigma$ | 小写西格玛 | `\sigma` |
| $\Sigma$ | 大写西格玛 | `\Sigma` |
| $\phi$ | 小写斐 | `\phi` |
| $\Phi$ | 大写斐 | `\Phi` |
| $\omega$ | 小写欧米伽 | `\omega` |
| $\Omega$ | 大写欧米伽 | `\Omega` |

## 6. 矩阵与行列式
| 公式 | 描述 | 代码 |
|---|---|---|
| $\begin{pmatrix} a & b \end{pmatrix}$ | 行矩阵 | `\begin{pmatrix} a & b \end{pmatrix}` |
| $\begin{pmatrix} a \\ b \end{pmatrix}$ | 列矩阵 | `\begin{pmatrix} a \\ b \end{pmatrix}` |
| $\begin{pmatrix} a & b \\ c & d \end{pmatrix}$ | 方阵 | `\begin{pmatrix} a & b \\ c & d \end{pmatrix}` |
| $\begin{vmatrix} a & b \\ c & d \end{vmatrix}$ | 行列式 | `\begin{vmatrix} a & b \\ c & d \end{vmatrix}` |
| $\begin{cases} x, & x\ge 0 \\ -x, & x<0 \end{cases}$ | 分段函数 | `\begin{cases} x, & x\ge 0 \\ -x, & x<0 \end{cases}` |
| \begin{align} a &= b+c \\ &= d+e \end{align} | 多行对齐 | `\begin{align} a &= b+c \\ &= d+e \end{align}` |

## 7. 常用修饰符
| 公式 | 描述 | 代码 |
|---|---|---|
| $\overline{AB}$ | 上划线 | `\overline{AB}` |
| $\underline{u}$ | 下划线 | `\underline{u}` |
| $\vec{v}$ | 向量箭头 | `\vec{v}` |
| $\mathbf{v}$ | 粗体向量 | `\mathbf{v}` |
| $\boldsymbol{v}$ | 粗体向量（需 `amsmath`） | `\boldsymbol{v}` |
| $\hat{x}$ | 帽子 | `\hat{x}` |
| $\widehat{ABC}$ | 宽帽子 | `\widehat{ABC}` |
| $\tilde{x}$ | 波浪 | `\tilde{x}` |
| $\widetilde{abc}$ | 宽波浪 | `\widetilde{abc}` |
| $f^*$ | 星号 | `f^*` |
| $\bar{z}$ | 共轭 | `\bar{z}` |

## 8. 二元运算符与关系符
| 公式 | 描述 | 代码 |
|---|---|---|
| $a \cdot b$ | 点乘 | `a \cdot b` |
| $a \times b$ | 叉乘 | `a \times b` |
| $a \div b$ | 除号 | `a \div b` |
| $a \pm b$ | 加减 | `a \pm b` |
| $a \mp b$ | 减加 | `a \mp b` |
| $a \ne b$ | 不等 | `a \ne b` |
| $a \le b$ | 小于等于 | `a \le b` |
| $a \ge b$ | 大于等于 | `a \ge b` |
| $a \approx b$ | 约等于 | `a \approx b` |
| $a \equiv b$ | 恒等于 | `a \equiv b` |
| $a \propto b$ | 正比于 | `a \propto b` |
| $a \parallel b$ | 平行 | `a \parallel b` |
| $a \perp b$ | 垂直 | `a \perp b` |

## 9. 数学字体切换
| 公式 | 描述 | 代码 |
|---|---|---|
| $\mathbb{R}$ | 黑板粗体（需 `amsfonts`） | `\mathbb{R}` |
| $\mathcal{L}$ | 手写体 | `\mathcal{L}` |
| $\mathtt{A}$ | 打字机体 | `\mathtt{A}` |
| $\mathrm{sin}$ | 正体（operator） | `\mathrm{sin}` |
| $\mathbf{x}$ | 粗体 | `\mathbf{x}` |


使用Quick Latex并加入自定义命令
```QuickLaTex
al:::\begin{align*}#cursor\end{align*};
bi:::\binom{#cursor}{#tab};
sq:::\sqrt{};
bb:::\mathbb{};
bf:::\mathbf{};
te:::\text{};
inf:::\infty;
cd:::\cdot;
qu:::\quad;
ti:::\times;
al:::\alpha;
be:::\beta;
ga:::\gamma;
Ga:::\Gamma;
de:::\delta;
De:::\Delta;
ep:::\epsilon;
ze:::\zeta;
et:::\eta;
th:::\theta;
Th:::\Theta;
io:::\iota;
ka:::\kappa;
la:::\lambda;
La:::\Lambda;
ma:::\begin{matrix}#cursor\end{matrix};
mu:::\mu;
nu:::\nu;
xi:::\xi;
Xi:::\Xi;
pi:::\pi;
Pi:::\Pi;
rh:::\rho;
si:::\sigma;
Si:::\Sigma;
ta:::\tau;
up:::\upsilon;
Up:::\Upsilon;
ph:::\phi;
Ph:::\Phi;
ch:::\chi;
ps:::\psi;
Ps:::\Psi;
om:::\omega;
Om:::\Omega;
ov:::\overrightarrow{#cursor}
```


在 LaTeX 中，如果你想把“竖线”画在 `\frac{dy}{dx}` 的右边、并标明“x=x₀”这个条件，正确的写法是：

\[
f'(x_0) = \left. \frac{dy}{dx} \right|_{x=x_0}
\]

解释：

- `\left.` 是一个“看不见的左定界符”，它告诉 LaTeX 后面要配对的右定界符（这里是 `\right|`）应该根据中间内容自动调整大小。
- `\right|` 就是那条竖线，它会根据前面 `\frac{dy}{dx}` 的高度自动伸缩。
- `_{x=x_0}` 把下标“x=x₀”放在竖线的右下角。

这样渲染出来的效果就是：

\[
$f'(x_0) = \left. \frac{dy}{dx} \right|_{x=x_0}$
\]