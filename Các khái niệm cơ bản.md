# Ràng buộc chặt và lỏng
Giả sử X là một phương án của 1 bài toán QHTT.
1. X làm cho ràng buộc i chặt khi $=$
2. X làm cho ràng buộc i lỏng khi $\not=$

$\text{Ví du: }$

$\begin{align*}f(X) &= 8x_1 + 2x_2 + 9x_3 - x_4 \to \min\\&3x_1 + 2x_3 - x_4 &\ge 14 & (1) \\&x_1 - 4x_2 - 2x_4 &= 8 & (2) \\&-x_1 + 7x_{2} + x_{3} + 3x_4 &\le -7 & (3) \\&x_1 &\ge 0, & (4) \\&x_2 &\le 0, & (5) \\&x_3 &\ge 0. & (6)\end{align*}$

$X_{0}(0, -1, 6, -2) \text{ là một phương án}$
$\text{Khi thế vào các ràng buộc ta có: }$
$\text{Các ràng buộc chặt: } (1), (2), (3), (4)$
$\text{Các ràng buộc lỏng: } (5), (6)$

# Phương án cực biên
$\text{Ví dụ: }$
$\begin{align*}f(X) &= 8x_1 + 2x_2 + 9x_3 - x_4 \to \min\\&3x_1 + 2x_3 - x_4 &\ge 14 & (1) \\&x_1 - 4x_2 - 2x_4 &= 8 & (2) \\&-x_1 + 7x_{2} + x_{3} + 3x_4 &\le -7 & (3) \\&x_1 &\ge 0, & (4) \\&x_2 &\le 0, & (5) \\&x_3 &\ge 0. & (6)\end{align*}$
$X^1 = (4, 0, 0, -2), X^4 = (12, 0, 0, 2) \text{ có phải là p.án, p.án cực biên không ?}$
$\text{Thế } X^{1} \text{ thỏa các ràng buộc trên } \Rightarrow X^{1} \text{ là một p.án}$
$\text{Ta có } \text{các ràng buộc chặt: } (1), (2), (3), (4)$
$\text{Chọn (1), (2), (5), (6) có ma trận hệ số sau: }$
$D =\begin{vmatrix}3 & 0 & 2 & -1 \\1 & -4 & 0 & -2 \\0 & 1 & 0 & 0 \\0 & 0 & 1 & 0\end{vmatrix}$