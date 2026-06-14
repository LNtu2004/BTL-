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

# Block screen 1 và 2 
<img width="1860" height="855" alt="image" src="https://github.com/user-attachments/assets/dc4fab41-271d-42e4-91ea-88e58ba0b2ff" />
<img width="1860" height="839" alt="image" src="https://github.com/user-attachments/assets/9e7cc028-f583-42af-843f-cb9c2e73594c" />

# Thử app 

các bạn tải app qua mã QR này nhé!

<img width="998" height="874" alt="image" src="https://github.com/user-attachments/assets/e415b898-6860-4924-990e-e9307d0ea618" />


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
# App 1
1. Các bạn nhấn vô new project nó hiện lên rất nhiều giao diện android nhưng ở đây mình sẽ chọn Empty Views Activity để làm bài cho mình
<img width="1118" height="794" alt="image" src="https://github.com/user-attachments/assets/7f6de9d5-ce03-4d08-95da-4148729cb1ba" />
2. Đây là project mình tạo
<img width="1114" height="804" alt="image" src="https://github.com/user-attachments/assets/06297c8a-4d18-4300-afc4-363a6d879b31" />

# Mình sẽ giải thích cho các bạn các thành phần của nó nhé ! 
a. Name : Là tên ứng dụng bạn muốn tạo.
b. Package name : Là định danh duy nhất cho ứng dụng
c. Save location : Nơi lưu dự án trên máy tính. 
d. Language : Ngôn ngữ lập trình bạn dùng cho app.
e. Minimum SDK : Là phiên bản Android thấp nhất mà app của bạn hỗ trợ.   
f. Build configuration language : Là ngôn ngữ cấu hình .

3. Sau khi nhấn Finish nó sẽ bắt bạn tải thêm phần bên trong ( Nhớ là phải có mạng đầy đủ nhé ! ) và đây là giao diện khi tải xong 
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/291d4c20-3b41-481c-97b1-6f379f33aa0a" />
4. Tạo thư mục Assets

Mình sẽ tạo thư mục Assets bằng cách click chuột phải vào app rồi chọn New → Folder → Assets Folder làm như trên hình là được
<img width="1916" height="1017" alt="image" src="https://github.com/user-attachments/assets/fdb880d7-70c6-4a91-bfca-8713f6626b18" />
Sau đó nó sẽ hiện ra 1 cửa sổ như này giữ nguyên nó r finish là được 
<img width="1122" height="807" alt="image" src="https://github.com/user-attachments/assets/691e307f-8bf0-4de4-b454-7501b65843c6" />
5. Tạo file guide.txt

Click chuột phải vào assets → New → File rồi đặt tên là guide.txt
<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/bda06ebe-1647-4c35-9bc9-8898f7144201" />
Cuối cùng là để nội dung như trên hình
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/471cd0f0-85c9-483a-a063-61c90b992a37" />
6. Thiết kế giao diện

Chọn thư mục res → layout → activity_main.xml rồi chuyển sang tab code 
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/4c636f6b-d7c7-4aa5-962a-4f8afce5dd80" />
Ở đây mình sẽ xóa hết code của nó r thay code mới nhé
Code :
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp">

        <TextView
            android:id="@+id/txtTitle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="ỨNG DỤNG HƯỚNG DẪN SEN ĐÁ"
            android:textSize="24sp"
            android:textStyle="bold"/>

        <TextView
            android:id="@+id/txtContent"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="20dp"
            android:textSize="18sp"/>

    </LinearLayout>

</ScrollView>

7. Viết code đọc Assets

Mở MainActivity.java xóa hết code cũ đi rồi thay code mới vô 

Code :
package com.example.apphuongdansenda;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.TextView;

import java.io.BufferedReader;
import java.io.InputStream;
import java.io.InputStreamReader;

public class MainActivity extends AppCompatActivity {

    TextView txtContent;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        txtContent = findViewById(R.id.txtContent);

        StringBuilder data = new StringBuilder();

        try {
            InputStream is = getAssets().open("guide.txt");

            BufferedReader reader =
                    new BufferedReader(
                            new InputStreamReader(is));

            String line;

            while ((line = reader.readLine()) != null) {
                data.append(line).append("\n");
            }

            reader.close();

            txtContent.setText(data.toString());

        } catch (Exception e) {
            txtContent.setText("Lỗi đọc file!");
        }
    }
}

8.chạy thử App

B1: Mở Device Manager ( nó năm bên phải màn hình nhé ! )

B2: Tạo máy ảo

B3: Chọn điện thoại ( mình chọn pixel 4 )

B4: Chọn Android ( ở đây mình chọn cái Android 10 )

<img width="1916" height="1020" alt="image" src="https://github.com/user-attachments/assets/6274abc0-1b10-46af-9ae5-f5a1f9fb44a3" />
<img width="1918" height="976" alt="image" src="https://github.com/user-attachments/assets/ea6c0d20-df19-4c57-bb96-df6388360353" />
<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/1ca84942-8c16-40d8-896b-63875adc078b" />

B5: Chạy thử app
 Các bạn nhấn vô mũi tên trên cùng màu xanh lá để chạy app nhé !
 Như này là chạy được r 
 <img width="1918" height="1019" alt="image" src="https://github.com/user-attachments/assets/7b4c35f2-3d98-4da2-95cc-b5fdff3a1322" />

# App 2 làm tương tự 
1.Lần này mình chọn Empty Activity tên là AppBTLAndroid
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/b39c0ec0-4571-4f0f-af2f-a46d6366f891" />
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/c4d07986-589e-49ce-80af-55dff964eecc" />
2.Thêm quyền internet 
vào  manifests chọn AndroidManifest.xml thêm dòng code : " <uses-permission android:name="android.permission.INTERNET"/> " như trên hình là được
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/d12fec20-2f6d-4172-b491-6d8fea479958" />
3.Tạo 2 Activity mới
tên là : SolverActivity và WebActivity
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/8b56559f-ba1a-4311-ba94-d2978d23b269" />
<img width="1125" height="803" alt="image" src="https://github.com/user-attachments/assets/de9c93ee-0521-4c5d-a136-ffaa5850b445" />
<img width="1120" height="655" alt="image" src="https://github.com/user-attachments/assets/357d78b1-56be-4339-8322-cc1d7ca14044" />
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/dd5038d7-c8bb-41bf-b7ea-1b0cf593f9e0" />
4.Thiết kế MainActivity
Code activity_main.xml : 
<?xml version="1.0" encoding="utf-8"?>

<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center"
    android:orientation="vertical">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="LÊ NGỌC TÚ"
        android:textSize="24sp"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="MSSV: K225480106069"/>

    <Button
        android:id="@+id/btnSolver"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Giải toán"/>

    <Button
        android:id="@+id/btnWeb"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Mở Website"/>

</LinearLayout>

Code MainActivity.java: 
package com.example.appbtlandroid;

import android.content.Intent;
import android.os.Bundle;
import android.widget.Button;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    Button btnSolver, btnWeb;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        btnSolver = findViewById(R.id.btnSolver);
        btnWeb = findViewById(R.id.btnWeb);

        btnSolver.setOnClickListener(v -> {
            startActivity(
                    new Intent(
                            MainActivity.this,
                            SolverActivity.class
                    )
            );
        });

        btnWeb.setOnClickListener(v -> {
            startActivity(
                    new Intent(
                            MainActivity.this,
                            WebActivity.class
                    )
            );
        });
    }
}

5.SolverActivity (Giải toán + API)

Code activity_solver.xml :

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <EditText
        android:id="@+id/inputA"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="@string/input_a"
        android:inputType="number" />

    <EditText
        android:id="@+id/inputB"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="@string/input_b"
        android:inputType="number" />

    <Button
        android:id="@+id/btnSolve"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/btn_solve"
        android:layout_gravity="center_horizontal"
        android:layout_marginTop="12dp" />

    <TextView
        android:id="@+id/resultText"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="@string/result_text"
        android:textSize="18sp"
        android:textColor="#000000"
        android:layout_marginTop="16dp" />

</LinearLayout>

Code SolverActivity.java :

package com.example.appbtlandroid;

import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.widget.*;
import org.json.JSONObject;
import java.io.*;
import java.net.*;

public class SolverActivity extends AppCompatActivity {
    EditText inputA, inputB;
    Button btnSolve;
    TextView resultText;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_solver);

        inputA = findViewById(R.id.inputA);
        inputB = findViewById(R.id.inputB);
        btnSolve = findViewById(R.id.btnSolve);
        resultText = findViewById(R.id.resultText);

        btnSolve.setOnClickListener(v -> {
            double a = Double.parseDouble(inputA.getText().toString());
            double b = Double.parseDouble(inputB.getText().toString());
            double sum = a + b;
            resultText.setText("Kết quả: " + sum);

            // Gửi API
            new Thread(() -> {
                try {
                    JSONObject data = new JSONObject();
                    data.put("app_by", "K225480106069");

                    JSONObject input = new JSONObject();
                    input.put("a", a);
                    input.put("b", b);
                    input.put("name", "hello tắc kè");
                    data.put("input", input);

                    JSONObject output = new JSONObject();
                    output.put("ketluan", "Đã tính tổng");
                    output.put("nghiem", sum);
                    data.put("output", output);

                    URL url = new URL("https://k58kmt.tdh.io.vn/api");
                    HttpURLConnection conn = (HttpURLConnection) url.openConnection();
                    conn.setRequestMethod("POST");
                    conn.setRequestProperty("Content-Type", "application/json");
                    conn.setDoOutput(true);

                    OutputStream os = conn.getOutputStream();
                    os.write(data.toString().getBytes());
                    os.close();

                    BufferedReader reader = new BufferedReader(new InputStreamReader(conn.getInputStream()));
                    StringBuilder response = new StringBuilder();
                    String line;
                    while ((line = reader.readLine()) != null) response.append(line);
                    reader.close();

                    runOnUiThread(() -> resultText.append("\nAPI: " + response));
                } catch (Exception e) {
                    runOnUiThread(() -> resultText.append("\nLỗi: " + e.getMessage()));
                }
            }).start();
        });
    }
}

6.WebActivity (WebView)
<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/1beeeb2b-daae-4c65-8a66-e8b6b4a758f1" />
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/8996d3f6-6c62-4900-a95a-06ca0bdd02f4" />





