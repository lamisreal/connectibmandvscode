# connectibmandvscode
How to connect IBM i in VS Code<br>
<br>
Để có thể connect giữa IBM i và VS Code ta làm như sau:<br>
<br>
B1. Tải xuống VS Code<br>
B2. Cài đặt extension sau: [Code for IBM i Link](https://marketplace.visualstudio.com/items?itemName=HalcyonTechLtd.code-for-ibmi)<br>
B3. Cài đặt thêm extension: [IBM i Development Pack](https://marketplace.visualstudio.com/items?itemName=HalcyonTechLtd.ibm-i-development-pack)<br>
B4. Tại màn hình bên cạnh trái, nhấn vào "IBM i"<br>
B5. Tạo connect mới: Nhập Các thông số như:<br>
- Connecttion Name: Tên của connection <br>
- Host or IP Address: có thể dùng cmd => nhập ping + Connecttion Name để lấy IP Address<br>
- Port: 22 (Mặc định)<br>
- Username: Tài khoản được cấp<br>
- Password:<br>
B6. Nhấn vào connect<br>
-----
Sau khi connect được, nên đổi lại thư viện cần trỏ bằng cách:<br>
B1. Nhấn chuột phải vào tên vừa connect và chọn: "Connection Settings"<br>
B2. Bấm vào "Temporary Data", dòng Temporary library đầu tiên sửa từ "ILEDITOR" trở thành "HCMCTL" (Tên thư viện cá nhân)<br>
B3. Nhấn save.<br>

-----
#Hướng dẫn connect<br>
B1. Tại USER LIBRARY LIST, mở connect tới LIBRARY chứa code.<br>
B2. Tại OBJECT BROWSER chọn new Filter và đặt tên Lib mới của bản thân<br>
