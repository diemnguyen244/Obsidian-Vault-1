**Ngữ pháp cơ bản:**
*If(condition){statement};

**PHÂN BIỆT KHI NÀO DÙNG IF, KHI NÀO DÙNG SWITCH:
Khi có sự so sánh các giá trị dùng If
Khi cho trước giá trị thì dùng switch (khi có 3 trường hợp trở lên, nếu dưới 3 TH thì dung If)
Ý là nếu condittion là true -> dòng code ở statement sẽ chạy

VI DU:
1. 
let temp = 120;
if (temp < 0) {
console.log("nuoc dong bang");
} 
else {
if (temp < 100) {
console.log("bang tan");
} 
else {
console.log("nuoc soi");}
}
2.
// VI DU DIEM SO
let score = 50;
if (score > 90) {
console.log("A");
} else if (score > 80) {
console.log("B");
} else if (score > 70) {
console.log("C");
} else if (score > 60) {
console.log("D");
} else {
console.log("E");
}

**Ngữ pháp mới:
***CONDITION ? STATEMENT1 : STATEMENT2

let age = 25;

// if (age>19){

// console.log('can drink Soju')

// }else{

// console.log('cant drink')

// }

***VIẾT TẮT

age > 19 ? console.log("you can drink") : console.log("you cant drink");

Ex2:
let score = 70;

if (score > 90) {

console.log("A");

} else if (score > 80) {

console.log("B");

} else if (score > 70) {

console.log("C");

} else if (score > 60) {

console.log("D");

} else {

console.log("E");

}