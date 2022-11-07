Dùng cho layout 2D
còn Flex dùng cho layout 1D

**Cách đơn vị dùng:

1. px
2. %: .grid-container {

display: grid;

grid-template-columns: 25% 25% 25%;

}
3. fretion:

.grid-container {

display: grid;

/* grid-template-columns: 1fr 1fr 1fr 1fr ; */

grid-template-columns: repeat(4. 1fr);

}
*KHOẢNG TRỐNG GIỮA CÁC ITÉMS:
Gap tương tự flex:
**Row gap
Colunm gap