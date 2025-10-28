
## 1. 呼出框语法（Callout Syntax） - 最推荐的方法

### 基本两列布局：
```markdown
> [!col]
> 第一列内容
>
> 第二列内容
```

> [!col]
> 第一列
>
>> [!col-md]
>> 第二列第一部分
>> 
>> 第二列第二部分
>>
>> 第二列第三部分
>

## 2. 代码块语法（Codeblock Syntax） - 功能最全


`````markdown
````col
```
基本包裹，代码块样式
```

```col-md
col-md列容器
```
````
`````
效果：
````col
```
基本包裹，代码块样式
```

```col-md
col-md列容器
```
````


### col 代码块设置

```markdown
height=值          # 列组高度 (CSS值 或 "shortest")
textAlign=对齐      # 文本对齐 (start/end/center/justify)
borderColor=颜色    # 边框颜色
borderStyle=样式    # 边框样式 (solid/dashed等)
borderWidth=宽度    # 边框宽度
borderRadius=半径   # 边框圆角
borderPadding=内边距 # 内边距
```

### col-md 代码块设置

```markdown
flexGrow=数字       # 列宽比例 (正数)
height=值          # 单独列高度 (CSS值)
textAlign=对齐      # 列内文本对齐
borderColor=颜色    # 单独列边框
borderStyle=样式
borderWidth=宽度
borderRadius=半径
borderPadding=内边距
```

### 特殊功能

- **`===`** - 设置块分隔符
    
- **`===`** - 在col中创建新行（需空设置块）
    
- **嵌套列** - col内可嵌套更多col

### 语法规则

- 父代码块比子代码块多一个反引号
    
- 所有内容必须包裹在col-md中才能正常渲染
    
- 支持在列内混合各种Markdown元素