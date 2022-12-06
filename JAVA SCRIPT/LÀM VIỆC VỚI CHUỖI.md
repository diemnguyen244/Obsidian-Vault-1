1. ===LENGTH: === **độ dài chuỗi
console.log(myString.length)
3. ===FIND INDEX: 
===console.log(myString.indexOf('JS'));
console.log(myString.indexOf('JS',6));
console.log(myString.lastIndexOf('JS',6));

3. ===CUT STRING:
===console.log(myString.slice(4,6)); -> từ vị trí số 4 đến số 6
console.log(myString.slice(4)) -> cằt từ số 4 tới hết
console.log(myString.slice(0)) -> cằt hết

4. ===REPLACE
===console.log(myString.replace('JS', 'JAVA'))-> THAY JÂVA VÀO CHỮ JS ĐẦU TIỀN

***ĐỂ THAY HẾT:
console.log(myString.replace(/JS/g, 'JAVA'))

5. ===CONVERT TO UPPER CASE/LOWER CASE
6. ===TRIM: loại bỏ khoảng trắng 2 đầu
7. ===SPLIT: dựa vào điểm chung cắt thành phần tử của mảng