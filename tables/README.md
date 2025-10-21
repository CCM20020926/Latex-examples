# 排表经验

1. 对于简单实验数据：使用 l, c 符合控制格式即可（l -  左对齐， c - 居中）
2. 对于包含长文本的表： 使用pmb符号控制列宽
   - p{kcm} : 左对齐，控制列宽为 k cm
   - m{kcm}: 居中垂直对齐，控制列宽
   - b{kcm}:  居中底部对齐，控制列宽

3. 若两行之间过于紧凑，可以使用\addlinespace命令添加空隙（参见：[long_text_table.tex](long_text_table.tex)）

4. 将一行拆分为多行：参见 [multirow.tex](multirow.tex)

   