# Tex package installed

- enumitem
- xifthen
- ifmtarg
- sourcesanspro
- tcolorbox
- environ
- lm-math
- trimspaces
- biblatex
- fontawesome5

## 更改当前字体属性

\normalfont 本声明把字体转换为默认的族、形状和系列。

\bfseries 本声明不改变当前字体的族与形状，但转变成bold序列。

\mdseries 本声明不改变当前字体的族与形状，但转变成中等粗细medium序列。

\itshape 本声明把字体的形状属性改为斜体，但保留族与系列不变。

\scshape 本声明把字体的形状属性改为小型大写，但保留族与系列不变。

\slshape 本声明把字体的形状属性改为slanted的斜体，但保留族与系列不变。

\upshape 本声明把字体的形状属性改为直立，但保留族与系列不变。

\rmfamily 本命令使字体保持当前的系列与形状属性，但转变为罗马族属性。

\sffamily 本命令使字体保持当前的系列与形状属性，但转变为无衬线族属性。

\ttfamily 使字体保持当前的系列与形状属性，但转变为打字机族属性。

LaTeX  支持的长度单位有:

in - 英寸(inch)
mm - 毫米(millimeters)
cm - 厘米(centimeters)
pt - points (大约 1/72 inch)
em - 接近当前字体的字符 "M"的宽度(approximately the width of an "M" in the current font)
ex - 接近当前字体的字符 "x"的高度approximately the height of an "x" in the current font

长度也可以是负值, 例如 -1.5em.  注意到数字 0 本身不是一个长度,  必须表明是0in 或 0pt 等.

[tabular tabular* tabularx](https://tex.stackexchange.com/questions/341205/what-is-the-difference-between-tabular-tabular-and-tabularx-environments)
