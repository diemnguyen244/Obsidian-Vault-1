 1 phần rất quan trọng. Sau khi event xảy ra tiếp theo sẽ có 1 chuỗi sự kiện.

-   Click là event-> sau đó sẽ có 1 sự kiện xảy ra.

CÁC LOẠI EVENT ĐƠN GIẢN:

  

A. **Keydown**(sử dụng nhiều, khi mình nhấn phím) /**keypress** (chưa cần quan tâm) /**keyup (**xảy ra khi mình thả phím mình mới nhấn**):** lúc mình nhấn phím có sự kiện xảy ra

B. **Mouseenter** (khi mình rê chuột vào)/**Mouseover** (

C. **Click/Dblclick** (sử dụng nhiều nhất)

Vd:

_html: <button>clink</>_

_document.querySelector("button").addEventListener("click", sayhello);_

_function sayhello() {_

  _alert("hello");_

_}_

  

  

***

**TRƯỜNG HỢP MUỐN NGHE NHIỀU SỰ KIỆN:**

  

**Code 2 dòng:**

document.querySelector("button").addEventListener("click", sayhello);

document.querySelector("button").addEventListener(“dblclick”, sayhello);