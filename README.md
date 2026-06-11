# Bài 1. Viết phần mềm trên công cụ Mit App inventor
   (tập trung vào quy trình tạo ra phần mềm)
   app có 3 screen:
   + about về bản thân+nút gọi sang 2 screen còn lại
   + giải 1 bài toán đơn giản
   + sử dụng webview: hiển thị 1 trang web có sẵn, hỗ trợ giao diện điện thoại
   mô tả: thanh công cụ có gì? kéo thả + thay đổi thuộc tính: làm ntn, để làm gì?
          block: mô tả bản chất việc kéo thả block ntn?
                 ưu điểm gì so với viết code? nhược điểm?
                 copy paste block ? (backpack)
  #                     Bài làm 
<img width="1919" height="1010" alt="image" src="https://github.com/user-attachments/assets/c3d55c58-fb2b-45d3-9ce3-595c41ee5338" />
Đây là trang web cần thiết cho bài làm 
<img width="1918" height="1013" alt="image" src="https://github.com/user-attachments/assets/657ef51f-8f6a-494b-8703-557d39ac914a" />
Giao diện khi vào trang 
<img width="930" height="668" alt="image" src="https://github.com/user-attachments/assets/8d718457-9312-4c66-ac31-2d26ac5ec2a1" />
<img width="922" height="674" alt="image" src="https://github.com/user-attachments/assets/0713949e-ac01-4e4b-807d-63cf34703664" />
<img width="919" height="717" alt="image" src="https://github.com/user-attachments/assets/f7202fac-984d-4493-8184-9e6625a08f5c" />
<img width="1860" height="855" alt="image" src="https://github.com/user-attachments/assets/dc4fab41-271d-42e4-91ea-88e58ba0b2ff" />
<img width="1860" height="839" alt="image" src="https://github.com/user-attachments/assets/9e7cc028-f583-42af-843f-cb9c2e73594c" />
# Mô tả công cụ MIT App Inventor

## 1. Thanh công cụ trong MIT App Inventor

MIT App Inventor cung cấp giao diện kéo thả trực quan để xây dựng ứng dụng di động. Các khu vực chính gồm:

### Palette

Là nơi chứa các thành phần để xây dựng ứng dụng như Label, Button, TextBox, Image, WebViewer,... Người dùng có thể kéo các thành phần này vào màn hình thiết kế.

### Viewer

Là khu vực mô phỏng giao diện điện thoại, nơi hiển thị các thành phần được kéo thả để thiết kế giao diện ứng dụng.

### Components

Hiển thị danh sách tất cả các thành phần đã được thêm vào màn hình hiện tại. Người dùng có thể đổi tên, sắp xếp hoặc lựa chọn thành phần để chỉnh sửa.

### Properties

Là khu vực dùng để thay đổi thuộc tính của thành phần như nội dung hiển thị (Text), màu sắc (Color), kích thước (Width, Height), kiểu chữ (FontSize),...

## 2. Kéo thả và thay đổi thuộc tính

Để xây dựng giao diện, người dùng kéo các thành phần từ Palette sang Viewer. Sau khi kéo thả, các thuộc tính của thành phần được chỉnh sửa trong mục Properties.

Ví dụ:

* Kéo một Button vào màn hình.
* Thay đổi thuộc tính Text thành "TÍNH".
* Thay đổi FontSize để chữ lớn hơn.
* Thay đổi Width để nút rộng bằng màn hình.

Việc thay đổi thuộc tính giúp giao diện trực quan, dễ sử dụng và phù hợp với yêu cầu của ứng dụng.

## 3. Bản chất của việc kéo thả Block

Trong MIT App Inventor, chương trình được xây dựng bằng cách ghép các Block với nhau thay vì viết mã nguồn bằng ngôn ngữ lập trình.

Mỗi Block đại diện cho một lệnh hoặc một hành động cụ thể. Người dùng kéo các Block và ghép chúng lại theo logic xử lý của chương trình.

Ví dụ:

* Khi người dùng nhấn Button.
* Đọc dữ liệu từ TextBox.
* Thực hiện phép tính.
* Hiển thị kết quả lên Label.

Việc ghép Block giúp mô tả trực quan luồng hoạt động của chương trình.

## 4. Ưu điểm của Block so với viết Code

* Dễ học và dễ sử dụng đối với người mới bắt đầu.
* Không cần ghi nhớ cú pháp lập trình.
* Hạn chế lỗi cú pháp.
* Thiết kế và phát triển ứng dụng nhanh.
* Trực quan, dễ quan sát luồng xử lý.

## 5. Nhược điểm của Block

* Khó phát triển các ứng dụng lớn và phức tạp.
* Khả năng tùy biến thấp hơn so với lập trình bằng Java hoặc Kotlin.
* Khi số lượng Block quá nhiều sẽ khó quản lý.
* Hiệu năng và khả năng mở rộng không cao bằng các công cụ lập trình chuyên nghiệp.

## 6. Chức năng Backpack

Backpack là công cụ hỗ trợ sao chép và tái sử dụng Block.

Người dùng có thể kéo các Block vào Backpack để lưu tạm thời, sau đó kéo các Block đó ra ở màn hình khác hoặc dự án khác.

Lợi ích của Backpack:

* Tiết kiệm thời gian xây dựng chương trình.
* Tránh phải tạo lại các Block giống nhau nhiều lần.
* Hỗ trợ tái sử dụng mã lệnh.
* Giúp quản lý và chia sẻ các Block dễ dàng hơn.
