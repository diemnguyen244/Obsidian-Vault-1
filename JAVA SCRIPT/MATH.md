- Math cũng là 1 object giúp thực hiện phép toán.
- thuộc tính của Math được viết hoa
- Math có 8 thuộc tính là 8 hàm số khác nhau

CÁC METHODS THƯỜNG DÙNG: max, min, random, ceil, round, floor.
1. ===MAX:

console.log(Math.max(4, 19, 100));  --> 100
console.log(Math.max(4, 19, "300")); -->300. Tự động chuyển string sang number để trả kết quả.

2. ===MIN: === tương tự Max

3. ===RANDOM: === trả con số thập phân ngẫu nhiên nhỏ hơn 1

console.log(Math.random());

4. ===CEIL: === làm tròn số lên (4,1->5)

5. ==FLOOR: === làm tròn xuống (3,9->3)
6. ===ROUND: === làm tròn xuống/lên giá trị. ( 4,1 -> 4)

***===**Phương thức**

Vai trò

Number.isFinite(): Xác định xem giá trị đã cho có phải là số hữu hạn hay không. Trả về boolean

Number.isInteger() Xác định xem giá trị đã cho có phải là số nguyên hay không. Trả về boolean

Number.parseFloat() Chuyển đổi chuỗi đã cho thành một số dấu phẩy động

Number.parseInt() Chuyển đổi chuỗi đã cho thành một số nguyên

Number.prototype.toFixed()Chuyển đổi và trả về chuỗi đại diện cho số đã cho, có số chữ số chính xác sau dấu thập phân

Number.prototype.toString()Chuyển đổi và trả về số đã cho dưới dạng chuỗi