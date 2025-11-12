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

