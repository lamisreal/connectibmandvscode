# connectibmandvscode
How to connect IBM i in VS Code

Để có thể connect giữa IBM i và VS Code ta làm như sau:

B1. Tải xuống VS Code
B2. Cài đặt extension sau: [Code for IBM i Link](https://marketplace.visualstudio.com/items?itemName=HalcyonTechLtd.code-for-ibmi)
B3. Cài đặt thêm extension: [IBM i Development Pack](https://marketplace.visualstudio.com/items?itemName=HalcyonTechLtd.ibm-i-development-pack)
B4. Tại màn hình bên cạnh trái, nhấn vào "IBM i"
B5. Tạo connect mới: Nhập Các thông số như:
- Connecttion Name: Tên của connection
- Host or IP Address: có thể dùng cmd => nhập ping + Connecttion Name để lấy IP Address
- Port: 22 (Mặc định)
- Username: Tài khoản được cấp
- Password:
B6. Nhấn vào connect
-----
Sau khi connect được, nên đổi lại thư viện cần trỏ bằng cách:
B1. Nhấn chuột phải vào tên vừa connect và chọn: "Connection Settings"
B2. Bấm vào "Temporary Data", dòng Temporary library đầu tiên sửa từ "ILEDITOR" trở thành "HCMCTL" (Tên thư viện cá nhân)
B3. Nhấn save.

-----
#Hướng dẫn connect
B1. Tại USER LIBRARY LIST, mở connect tới LIBRARY chứa code.
B2. Tại OBJECT BROWSER chọn new Filter và đặt tên Lib mới của bản thân
