
# 公式
公式支持中文，但没有编号，如果要编号可以通过手动添加tag的方式

## 行内公式
$f(x) = x_{1} 中文$ 

## 行间公式
$$
使用函数 f(x_i)=ax_i+b \tag{1} 
$$



## 符号支持
符号集在内部做了一个映射，可以将任意公式内外的符号均映射成为 LaTeX 中的符号。

原本的解决方案为添加一个额外的符号字体集来解决（来自于[stackoverflow](https://tex.stackexchange.com/questions/69901/how-to-typeset-greek-letters) ），目前的方案为两者优先采用映射方法，目前支持的符号列举如下（可能支持更多符号，但没有经过测试）：

### 希腊字母
αβγδεζηθικλμνξοπρστυφχψω

ΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣΤΥΦΧΨΩ


**αβγδεζηθικλμνξοπρστυφχψω**

`αβγδεζηθικλμνξοπρστυφχψω`

$αβγδεζηθικλμνξοπρστυφχψω$

$$αβγδεζηθικλμνξοπρστυφχψω$$

```
ΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣΤΥΦΧΨΩ
```

### 运算符号
±×÷∣∤

⋅∘∗⊙⊕

≤≥≠≈≡

∑∏∐∈∉⊂⊃⊆⊇⊄

∧∨∩∪∃∀∇

⊥∠

∞∘′

∫∬∭

↑↓←→↔↕