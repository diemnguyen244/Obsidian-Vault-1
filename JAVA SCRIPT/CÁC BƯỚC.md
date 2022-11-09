1. Khai báo biến
2. Tạo event
3. tạo function

VD:
**let darkBtn** = document.getElementById("dark-btn");

**let lightBt**n = document.querySelector("#light-btn");

// let title = document.querySelector("h1");

**darkBtn.addEventListener**("click", darkMode);

**function** darkMode() {

document.body.style.color = "white";

document.body.style.backgroundColor = "black";

}

lightBtn.addEventListener("click", lightMode);

function lightMode() {

document.body.style.color = "black";

document.body.style.backgroundColor = "white";

}
*VÌ BODY CÓ SẴN TRONG HTML NÊN SET CHO BODY LÀ TRƯỜNG HỢP ĐẶC BIỆT, CÓ THỂ VIẾT TẮT NHƯ SAU:

function darkMode() {

document.body.style.color = "white";

document.body.style.backgroundColor = "black";

}