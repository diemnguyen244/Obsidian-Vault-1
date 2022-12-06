5 kiểu:
1. *FOR: Vòng lặp với điều kiện đúng *******
Xây dựng các đoạn mã lặp đi lặp lại theo 1 kịch bản, truyền đk đúng
2. *FOR IN: Lặp qua KEY của đối tượng, có thể là string, obj, array
3. FOR OF: Lặp qa value của đối tượng, có thể là array hoặc ojb
4. WHILE: lặp khi điều kiện đúng,
5. DO/WHILE:  xử dụng khi đoạn code chạy ít nhất 1 lần sau đó lặp khi đk đúng





dùng đê tạo vòng lặp 
- thường hay tạo biến là i
- tham số thứ 2 là số lần muốn lặp
- **cú pháp:
for (let i = 0; i <= 100; i++) {

**console.log(i);**
}}

**// Cách 2**
let i = 1;
for (; i < 5; ) {
console.log(i);
i++;
}

Số tăng dần là số chẵn
for (let i = 1; i <= 100; i++) {
if (i % 2 === 0) {
console.log(i);
}}