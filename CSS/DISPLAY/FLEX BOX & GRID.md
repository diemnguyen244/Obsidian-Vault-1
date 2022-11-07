**FLEX BOX:
*Gap chỉ áp dụng khi cha của nó là flex, dùng để tạo khoảng cách giữa các con
 ul {
display: flex;
gap: 16px;}

**
![](https://i.imgur.com/3bz9cu4.png)
Main axis: trục các element được layout ra -> Chiều ngnag
Coss axis: trục dọc


+**Flex direction: row (chiều ngang)/ row reverse(ngược lại theo chiều ngang)
										colum (chiều dọc)/ colum reverse (ngược lại theo chiều dọc)

justify-content: mặc định flex-start -> __tương ứng trục main axis
align-itém: tương ứng trục dọc
space-between: 2 vị trí ngoài cùng, chia bằng nhau nếu có giữa
space-around: các item bằng nhau
