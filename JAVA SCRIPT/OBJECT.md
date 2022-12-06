property name = key
proerty value= value. Giá trị có thể là string, number, boolean, null, Object


===QUY TẮC VIẾT PROPERTY NAME:
1. phải bắt đầu bằng chữ cái, underscore, dolla sign
2. không khoảng cách, gạch ngang


===CÁCH LẤY KẾT QUẢ LÀ PHẦN TỬ BÊN TRONG OBJ:
===let profile = {
name: "diem",
age: 20,}
1. console.log(profile.name);
2. console.log(profile["name"]);

===THAY VALUE KHÁC CHO KEY CÓ SẴN
===profile.name = "nhi";
console.log(profile.name); -> kết quả cho tên được thay là nhi


===THÊM PROPERTY TRONG OBJ:
===profile.company = "like lion";
console.log(profile.company);
//cách 2 lấy kết quả
console.log(profile["company"]);


===XOÁ PROPERTY TRONG OBJ
===delete profile.age;
console.log(profile.age);

===LẤY KẾT QUẢ OBJ TRONG OBJ

console.log(profile.pet.name);
console.log(profile.pet.age);

===LẤY 1 GIÁ TRỊ TRONG ARRAY NHỎ NẰM TRONG OBJ LỚN

console.log(profile.friend[0]);

===LẤY 1 GIÁ TRỊ TRONG 1 OBJ NHỎ TRONG 1 ARRAY TRONG 1 OBJ LỚN
===console.log(profile.friend[2].age);
console.log(profile.friend[2].name);