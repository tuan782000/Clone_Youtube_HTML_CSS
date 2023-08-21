# thuộc tính mặc định position

position: static;

position: fixed;

Thuộc tính fixed giúp phần tử đó được cố định tại 1 vị trí trên màn hình.
Ngoài ra chúng ta có thể điều chỉnh vị trí của nó thông qua

- Muốn nó cố định phía trên bên trái
    top + left (điều chỉnh hướng xuất hiện)
- Muốn nó cố định phía trên bên phải
    top +right (điều chỉnh hướng xuất hiện)
- Muốn nó cố định phía dưới bên trái
    bottom + left (điều chỉnh hướng xuất hiện)
- Muốn nó cố định phía dưới bên trái
    bottom + right (điều chỉnh hướng xuất hiện)

- Muốn cố định trên mà độ dài của thanh được giản ra (phủ chiều ngang)
    top + right + left
ví dụ: top: 10px; right: 50px; left: 50px;

- Muốn nó cố định trên mà có chiều cao và chiều ngang (phủ chiều ngang và chiều dọc) tự động stretch: kéo dài theo các con số chỉ định.
    top + right + left + bottom
ví dụ: top: 10px; right: 50px; left: 50px; bottom: 100px;


# Sẽ có 2 trường hợp chúng ta sử dụng
Trường hợp 1:
Nếu mà kích thước của thực thể cấu hình position: fixed; là có cụ thể và không thay đổi theo thời gian
Chúng ta nên set width height cho nó.

Trường hợp 2:
Nếu mà kích thước của thực thể cấu hình position: fixed; là không cụ thể và có thể bị thay đổi tùy theo kích thước màn hình
Chúng ta nên dùng top right bottom left để đặt kích thước của nó cho có thể co giãn linh động

# Học qua ví dụ:
1 trong các ứng dụng của postion fixed là dùng để làm nav

Bước 1:
Tạo chiều cao và chiều rộng cho thực thể. 
Tùy trường hợp mà dùng top right bottom left hoặc width height

Bước 2: 
set position: fixed để cho thực thể này nó rời khỏi bố cục luồng và lấy vị trí cung cấp được set màn hình làm cố đinh 
Bước này vẫn phải dùng top: 0 right: 0 bottom:0  để cố định vị trí trên top và bánh chướng hết màn ở trên.

Bước cuối cùng: xác định được chiều cao là bao nhiêu. thí dụ 60px;
Th1: thì mình phải set padding-top cho body đó là tối thiêu 60px;
Th2: Đố với các nội dung có cách ra khoảng thì nên hơn 60px



 z-index giúp xác định độ ưu tiên của thẻ đó

 z-index của ai lớn hơn ưu tiên hiển thị lớn hơn