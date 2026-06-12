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
# Bài 2. Viết app sử dụng Android Studio
   + Android manifest.xml  => mô tả gì? app cần quyền để do-st: khai báo ntn? để làm gì?
   + vòng đời của 1 ứng dụng android.
     code tự sinh sau khi tạo 1 project: có sẵn hàm onCreate: tại sao???
   + Code: java language. 
     app cần check xem có quyền để do-st? : code ntn? ý nghĩa?
     giao diện: (res/layout) mô tả bằng file XML + UI Design review
        + thuộc tính text, hoặc các thuộc tính khác: giá trị hardcode => lưu vào nới khác, tham chiếu tới nó:
          cú pháp của việc tham chiếu là gì?
          ưu điểm của việc tham chiếu này?
          OS hỗ trợ auto việc lấy giá trị tham chiếu theo LOCATION, LANGUAGE, THEME
          việc hỗ trợ auto này giúp app làm được điều gì?	
        + đối tượng chứa: gộp các đối tượng con lại: cùng 1 quy luật sắp xếp để hiển thị 
          các đối tượng con nằm kề nhau theo chiều dọc | hoặc ngang, gravity
     code tương tác với layout: vd hiển thị text
          mong muốn text hiển thị phù hợp với thiết lập LOCATION, LANGUAGE, THEME của người dùng
          thì làm ntn? (tránh hardcode)
     event (sự kiện) người dùng tác động vào app: CLICK vào button, click vào text,...
          với 1 sự kiện nào đó, muốn chạy 1 đoạn code để do-st
          thì LAYTOUT cần làm gì?
              CODE viết như nào (2 cách)
---------------------------
     trong app có các thư mục đặc biệt: Assets
     khi sử dụng Window Explorer để copy các files + folder vào trong Assets
     thì khi compiler: mọi file này đều đi theo app, nằm trong app
     trong app có thể truy cập được đến các file này
     cú pháp truy cập vào là gì?
     lợi ích của việc app có sẵn các files (offline cũng có)?
     ứng dụng: app hướng dẫn việc X

==> tạo app1 sử dụng cơ chế Dữ liệu chuẩn bị trước trong Assets
         format dữ liệu: tuỳ ý, nội dung tuỳ ý
         công cụ để hiển thị dữ liệu: tuỳ ý
         có cần phải tiền xử lý trước khi hiển thị ko: tuỳ ý.
         SV TỰ ĐẶT RA VẤN ĐỀ => TỰ GIẢI QUYẾT VẤN ĐỀ
         MÔ TẢ ĐƯỢC DỮ LIỆU CÓ ĐẶC THÙ GÌ
                    DÙNG THUẬT TOÁN NÀO ĐỂ XỬ LÝ DỮ LIỆU (NẾU CẦN)
                    DÙNG ĐỐI TƯỢNG NÀO ĐỂ HIỂN THỊ DỮ LIỆU.
                    (ĐỘ SÁNG TẠO LÀ KO GIỚI HẠN)
------------------------
APP2 (android studio):  tạo app tương đương với Mit App inventor
  app có 3 activity
  + activity1: about: about+nút gọi sang 2 activity còn lại
  + activity2: giải toán đơn giản (tuỳ ý). mỗi khi giải xong bài toán: gọi api tại https://k58kmt.tdh.io.vn/api
    để gửi bài toán lên đó
    {app_by:mã số sv, input: {a:1,b:2,c:3,name:"hello tắc kè"},output:{ketluan:"vô nghiệm", abc:"xyz", nghiem:3.14}}
    nhận lại json: {ok:1, stt:1234}
  + activity3: 
    dùng web-view để truy cập từ 
    1 trang web https://k58kmt.tdh.io.vn?masv=mã sv của bạn
#                       Bài làm 
I cài Android Studio 
1. Vô web " https://developer.android.com/studio?hl=vi " để tải ứng dụng về máy
2. Sau khi tải xong thì các bạn cứ nhấn next là dc
3. Đây là màn hình sau khi các bạn cài xong
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/bfab8b85-6677-494f-a3e6-80a28deb70be" />
II Thực hiện bài làm

1. Các bạn nhấn vô new project nó hiện hiện lên rất nhiều giao diện android nhưng ở đây mình sẽ chọn Empty Views Activity để làm bài cho mình
<img width="1118" height="794" alt="image" src="https://github.com/user-attachments/assets/7f6de9d5-ce03-4d08-95da-4148729cb1ba" />
2. 



