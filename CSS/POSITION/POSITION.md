1. Static (default): đi theo flow từ trên xuống dưới, không thể set top, right, bottom, left
2. Relative: chỉ phụ thuộc vào chính bản thân nó, có thể set trên dưới, trái phải.
3. Absolute: phụ thuộc vào thằng cha của nó
transform: translate (-50%, -50%);
4. Fixed: giữ vị trí cố định, Sau khi set fixed, width = auto, nên set width = 100%, top=0, left=0.
5. Stiky: *Rất ít được sử dụng*. Vì 1 số trình duyệt không hỗ trợ, dùng để fix 1 thanh navbar khi kéo xuống dưới vẫn giữ cố định và không kéo theo thanh phía trên của nó
		position: sticky;
	top: 0;		

*