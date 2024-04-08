# Quy tắc đổi dấu
![[Quy tắc đổi dấu trong bài toán đối ngẫu]]
![[Pasted image 20240407184155.png]]
![[Pasted image 20240407184211.png]]
==Lưu ý: ==
1. Ràng buộc về dấu ở bài toán đối ngẫu luôn là số 0
2. Khi đề bài cho $x_{i} \ge 0$ phải coi i là những số nào
3. Nhớ đừng xem có bao nhiêu biến ở hàm mục tiêu mà xem bao nhiêu biến trong các ràng buộc chung ở bài toán gốc
# Cặp đối ngẫu
![[Pasted image 20240407184430.png]]
Cặp đối ngẫu thì phải liệt kê ra hết kể cả đó là ẩn tùy ý
# Định lý trong bài toán đối ngẫu 
![[Pasted image 20240407184553.png]]
==Giá trị hàm mục tiêu của hai bài toán bằng nhau==
# Dựa vào patư của bài toán ban đầu để tìm patư của bài toán gốc.

Sử dụng độ lệch bù yếu
$x_{j}.\left(\sum a_{ij}. y_i - b_j\right) = 0$
$y_{j}.\left(\sum a_{ij}. x_i - c_j\right) = 0$
![[Pasted image 20240407190742.png]]
![[Pasted image 20240407190808.png]]
==Lưu ý: ==
1. Tìm được hệ phương trình giải bằng cách tìm cặp đối ngẫu  tương ứng với giá trị trong patu ban đầu > 0
	Như ở trên thì ta có được 14, 6, 5 tương ứng với $x_{2}, x_{3}, x_4$
## Thiếu phương trình
Đôi lúc sẽ thiếu 1 phương trình, ta cần xem xét [[Các khái niệm cơ bản 1#Thỏa mãn chặt và lỏng| Ràng buộc lỏng]] ở các ràng buộc ở bài toán ban đầu để xác định được cặp đối ngẫu của ràng buộc lỏng sẽ bằng 0
![[Pasted image 20240408144524.png]]
Chứng minh X = (3, 0, 11, 0) là PATU
![[Pasted image 20240408144059.png]]
# Chứng minh một phương án là tối ưu
$B_{1}$: Xem có là phương án chưa
$B_2$: Lập bài toán đối ngẫu
$B_3$: Giả sử phương án trên đó là phương án tối ưu 
$B_3$: Từ giả sử trên tìm patu cho bài toán đối ngẫu rồi xem định [[Bài toán đối ngẫu#Định lý trong bài toán đối ngẫu | Định lý về bằng nhau trong hàm mục tiêu]] có đúng không nếu đúng thì đó là phương án tối ưu
![[Pasted image 20240407210547.png]]
Chứng minh X = (3, 0, 11, 0) là PATU
![[Pasted image 20240408144059.png]]