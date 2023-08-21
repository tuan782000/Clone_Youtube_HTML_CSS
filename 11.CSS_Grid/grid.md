# Grid
Grid là gì? Lưới là một bố cục có hàng và cột

rows: trục ngang
columns: trục dọc

3 columns và 2 rows

##|##|##
--------
##|##|##

2 columns và 1 rows

##|##

Bố cục (đối với Grid) chặt chẽ hơn thằng Flex

có nghĩa

grid-template-columns: 1fr 100px 2fr

vị trí bố cục ở html cũng phải đứng đúng như vậy thì css mới sắp xếp đúng được

Còn Flexbox nó sẽ không có điểm này.

Grid = rigid layout
Flexbox = flexible layout

"Grid = bố cục cứng nhắc 
Flexbox = bố cục linh hoạt"

Câu hỏi muôn thưởu là khi nào dùng GRID và khi nào Dùng Flex

Tùy thuộc vào nội dung đó đang hiển thị.

Nếu nội dung đó hiển thị 1 cách linh hoạt thì nên dùng flex

Nội dung cố định không thay đổi thì nên dùng grid.

