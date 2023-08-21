# Cùng nhau học Position Absolute và Relative


fixed = placed in the browser window (cố định = được đặt trong cửa sổ trình duyệt)
absolute = placed on the page (tuyệt đối = được đặt trên trang)



Position absolute và relative là hai trong số các thuộc tính position quan trọng nhất trong CSS. Chúng cho phép bạn điều khiển vị trí của các phần tử trên trang web của mình theo nhiều cách khác nhau.

- Position absolute: Khi bạn đặt một phần tử ở vị trí absolute, nó sẽ bị tách khỏi dòng chảy bình thường của trang web và được đặt ở vị trí bạn chỉ định trong CSS. Phần tử absolute sẽ được định vị theo offsetParent của nó, là phần tử cha gần nhất có thuộc tính position khác với static. Nếu không có offsetParent, phần tử absolute sẽ được định vị theo viewport (cửa sổ trình duyệt).

- Position relative: Khi bạn đặt một phần tử ở vị trí relative, nó sẽ không bị tách khỏi dòng chảy bình thường của trang web, nhưng nó sẽ được định vị theo offsetParent của nó. Điều này cho phép bạn di chuyển phần tử relative xung quanh dòng chảy bình thường của trang web.

Dưới đây là một số ví dụ về cách sử dụng các thuộc tính position absolute và relative:

- Đặt các phần tử chồng lên nhau: Bạn có thể sử dụng các thuộc tính position absolute và relative để đặt các phần tử chồng lên nhau. Ví dụ, bạn có thể sử dụng một phần tử absolute để đặt một thanh điều hướng ở trên cùng của trang web, ngay cả khi có nội dung khác được hiển thị trên trang.
- Tạo các hiệu ứng pop-up: Bạn có thể sử dụng các thuộc tính position absolute và relative để tạo các hiệu ứng pop-up. Ví dụ, bạn có thể sử dụng một phần tử absolute để đặt một hộp thoại pop-up ở giữa màn hình, ngay cả khi người dùng đang cuộn trang.
- Điều chỉnh kích thước và vị trí của các phần tử: Bạn có thể sử dụng các thuộc tính position absolute và relative để điều chỉnh kích thước và vị trí của các phần tử. Ví dụ, bạn có thể sử dụng một phần tử absolute để đặt một hình ảnh ở một vị trí cụ thể trên trang web, ngay cả khi kích thước của trang web thay đổi.

Các thuộc tính position absolute và relative là một công cụ mạnh mẽ mà bạn có thể sử dụng để tạo các bố cục trang web phức tạp. Tuy nhiên, điều quan trọng cần nhớ là chúng có thể gây khó khăn cho việc duy trì trang web của bạn. Nếu bạn không chắc chắn về cách sử dụng các thuộc tính này, bạn nên tham khảo ý kiến của một nhà thiết kế web có kinh nghiệm.