## 1. Use Case là gì?
Use case: là một hành động hoặc chức năng của hệ thống được thực hiện bởi một hoặc nhiều tác nhân. Ví dụ: Đăng nhập, Thêm sản phẩm vào giỏ hàng, Thanh toán, Quản lý đơn hàng, vv.

Sự tương tác giữa người dùng và hệ thống có 2 cách thức phổ biến:

- Cách thức mà người dùng tương tác với hệ thống.
- Cách thức mà hệ thống tương tác với các hệ thống khác.


## 2. Các thành phần đặc tả Use Case

Các thành phần đặc tả Use Case bao gồm: Actor (người sử dụng), Use Case (chức năng tương tác) & Relationship (các quan hệ trong Use Case).

![image](https://user-images.githubusercontent.com/122768076/225191264-5f569101-837c-47b9-906d-cb68855c6518.png)

a. Actor (Người sử dụng):
- Actor là thành phần chỉ người dùng hoặc một đối tượng nào đó bên ngoài tương tác với hệ thống.

b. Use Case (Chức năng tương tác):
- Use Case là các chức năng mà các Actor sẽ sử dụng hay thể hiện sự tương tác giữa người dùng và hệ thống. 

c. Relationship (Các quan hệ trong Use Case) 
- Các quan hệ trong Use Case gồm 3 loại: 
         * Include , Extend , Generalization.

Mối quan hệ Include trong Use Case:

- Include là mối quan hệ bao gồm hoặc bắt buộc phải có giữa các Use Case với nhau. Hiểu đơn giản hơn: Để Use Case A xảy ra thì phải đạt được Use Case B.

Mối quan hệ Extend:

Extend biểu diễn mối quan hệ mở rộng, không bắt buộc, có thể có hoặc không giữa các Use Case với nhau. 

![image](https://user-images.githubusercontent.com/122768076/225192102-2d3ab676-e740-4c2f-97d4-c1c96ac60a18.png)

Mối quan hệ Generalization:
- Generalization là mối quan hệ cha con giữa các Use Case với nhau. Generalization còn thể hiện khả năng thể hiện mối quan hệ giữa các Actor với nhau.

Ex:
- Đăng nhập (cha): Có thể thông qua số điện thoại (con) hoặc Email (con).
- Đặt hàng (cha): Có đặt hàng qua số điện thoại (con) hoặc website (con).








