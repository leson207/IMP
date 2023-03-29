# IMP
1,Sinh dữ liệu:

Ảnh gốc:

 ![image](https://user-images.githubusercontent.com/74070396/228534711-d7c72305-599c-4e7a-ab9b-4ee2f61f0cb1.png)

Bước 1: Tìm các mảng màu bằng color segmentation với k-means:

 ![image](https://user-images.githubusercontent.com/74070396/228534742-c550fca5-c3f2-43c3-898b-0ee8998b927b.png)

Bước 2: Tìm tọa độ chính xác của các mảng màu và lưu vào danh sách, sẽ chỉ lấy các mảng màu có số điểm ảnh lớn hơn 10000:

Bước 3: Viết các chỉnh sửa: các ảnh dưới đây dung chung mảng đám mây

Đổi màu:

 ![image](https://user-images.githubusercontent.com/74070396/228534765-5e3f7725-d09d-416e-8056-0e524e4cb85b.png)

Lật ngang:

 ![image](https://user-images.githubusercontent.com/74070396/228534780-f0859be0-dd67-4c46-af7f-b4ad4aacd9cc.png)

Lật dọc;

![image](https://user-images.githubusercontent.com/74070396/228534819-a822a912-4af6-49f7-be96-201e0502850c.png)

Nhân bản mảng màu đến các vị trí trái trên, trái dưới, phải trên, phải dưới ngẫu nhiên:

 ![image](https://user-images.githubusercontent.com/74070396/228534846-eae0a323-ff99-471d-b075-075e69c7f4d3.png)

Xóa mảng màu và thay thế bằng màu từ xung quanh:

 ![image](https://user-images.githubusercontent.com/74070396/228534860-83555f8f-29ac-460d-a6d3-c960b91d24da.png)

Thêm vào 1 mảng màu:

 ![image](https://user-images.githubusercontent.com/74070396/228534894-eed558c2-1624-4c39-998b-9a60bd3ac497.png)

1 ảnh được tạo random với 3 khác biệt:

 ![image](https://user-images.githubusercontent.com/74070396/228534923-5672dbb6-254d-48b0-8ee9-7758d5ab8751.png)

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

 ![image](https://user-images.githubusercontent.com/74070396/228534961-59581f54-210f-4358-9784-94048b214e5a.png)

Đặt ngưỡng lên ảnh:

 ![image](https://user-images.githubusercontent.com/74070396/228534990-d7134007-4383-41fe-a024-33f8a3494f82.png)

Mở rộng ảnh 2 lần để tăng kích thước vùng trắng

 ![image](https://user-images.githubusercontent.com/74070396/228535020-6a59998d-f309-4b45-bbe6-9fb8146f3d77.png)

Tính toán đường viền và vẽ hình chữ nhật bao quanh tạo ra kết quả sau cùng:
Link colab notebook của 2 file lần lượt là:
https://colab.research.google.com/drive/1svNhJkXDls3UyXvKnYmyXTF8pZ63vVYP?usp=sharing
https://colab.research.google.com/drive/12dZOu_TZ8mZd36tAB-zu0dPNeR3E7S3M?usp=sharing
cho sinh dữ liệu vào giải. Phải upload ảnh trước để có thể chạy.

