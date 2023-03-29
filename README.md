# IMP
1,Sinh dữ liệu:
Ảnh gốc:
 
Bước 1:Tìm các mảng màu:
 
Bước 2: Tìm tọa độ chính xác của các mảng màu và lưu vào danh sách, sẽ chỉ lấy các mảng màu có số điểm ảnh lớn hơn 10000:
Bước 3: Viết các chỉnh sửa: các ảnh dưới đây dung chung mảng đám mây
Đổi màu:
 
Lật ngang:
 
Lật dọc;
 ![image](https://user-images.githubusercontent.com/74070396/228534575-28bcb75f-a95b-4acc-9f06-dffc8036e257.png)

Nhân bản mảng màu đến các vị trí trái trên, trái dưới, phải trên, phải dưới ngẫu nhiên:
 
Xóa mảng màu và thay thế bằng màu từ xung quanh:
 
Thêm vào 1 mảng màu:
 
1 ảnh được tạo random với 3 khác biệt:
 
Bước 4: Viết chương trình chính
Đọc ảnh, tìm các mảng màu và tọa độ của chúng.
Nhập vào level=1,2,3:
Ta sẽ random số mảng màu được chỉnh sửa theo từng level:
Level 1=1
Level 2=2
Level 3=3
….
Với mỗi mảng màu, ta sẽ chọn ngẫu nhiên một chỉnh sửa.
Để đảm bảo tính toàn vẹn của ảnh, mảng màu cuối cùng sẽ có thể áp dụng tùy ý các chỉnh sửa trên, nhưng các mảng màu trước đó sẽ chỉ được xóa hoặc đổi màu.
2,Giải:
Tính toán khác biệt tuyệt đối giữa 2 ảnh
 
Đặt ngưỡng lên ảnh:
 
Mở rộng ảnh 2 lần để tăng kích thước vùng trắng
 
Tính toán đường viền và vẽ hình chữ nhật bao quanh tạo ra kết quả sau cùng:
 
