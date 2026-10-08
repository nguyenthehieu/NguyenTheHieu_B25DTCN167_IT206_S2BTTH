## **1\. Lý do chọn Agile**

Waterfall chốt yêu cầu từ đầu nên khi GreenMart thay đổi nhu cầu, đội phải sửa nhiều phần và phát hiện lỗi muộn.

Agile chia dự án thành các Sprint ngắn, thường xuyên nhận phản hồi và điều chỉnh Product Backlog.

**Kết luận:** GreenMart nên dùng Agile vì yêu cầu bán hàng đa kênh có thể thay đổi và cần khách hàng phản hồi thường xuyên.

## **2\. Làm việc theo 4 giá trị Agile**

| Thói quen hiện tại | Giá trị bị đi ngược | Cách làm mới |
| ----- | ----- | ----- |
| Chỉ trao đổi qua phần mềm | Cá nhân và tương tác hơn quy trình và công cụ | Trao đổi trực tiếp/Daily Scrum khi cần. |
| Viết tài liệu rất chi tiết, cuối dự án mới demo | Phần mềm chạy được hơn tài liệu đầy đủ | Làm và demo Increment sau mỗi Sprint. |
| Chờ 2 tuần để phê duyệt thay đổi | Hợp tác với khách hàng hơn đàm phán hợp đồng | Trao đổi với PO và cập nhật Backlog. |
| Luôn làm theo kế hoạch ban đầu | Đáp ứng thay đổi hơn bám theo kế hoạch | Điều chỉnh Product Backlog khi có thay đổi. |

## **3\. Khung Scrum**

### **Độ dài Sprint: 2 tuần**

* **Minh bạch:** Mọi người biết rõ mục tiêu và thời gian của Sprint.  
* **Thanh tra:** Cuối Sprint kiểm tra Increment và nhận phản hồi.  
* **Thích nghi:** Dựa vào phản hồi để điều chỉnh Product Backlog cho Sprint sau.

Chọn Scrum vì dự án có yêu cầu dễ thay đổi, cần phát triển từng phần và nhận phản hồi thường xuyên hơn Waterfall.

## **4\. Phân vai Scrum Team**

| Thành viên | Vai trò | Quyết định |
| ----- | ----- | ----- |
| **Long** | Product Owner | Quyết định ưu tiên Product Backlog, giá trị sản phẩm. |
| **Hoa** | Scrum Master | Hướng dẫn Scrum, hỗ trợ loại bỏ trở ngại. |
| **An, Bình, Chi, Dung** | Developers | Tự quyết cách làm kỹ thuật và công việc trong Sprint. |

**Không được quyết định:**

* PO không tự quyết cách lập trình.  
* Scrum Master không giao việc cho từng Developer.  
* Developers không tự thay đổi thứ tự ưu tiên Product Backlog.

## **5\. Artifacts & lịch sự kiện**

### **Product Backlog**

| Ưu tiên | Hạng mục |
| :---: | :---: |
| 1 | Đặt hàng online |
| 2 | Tìm kiếm sản phẩm |
| 3 | Thanh toán online |
| 4 | Quản lý giỏ hàng |
| 5 | Quản lý tồn kho |
| 6 | Theo dõi đơn hàng |
| 7 | Báo cáo bán hàng |

### **Sprint 1**

**Sprint Goal:** Xây dựng chức năng tìm kiếm sản phẩm và nền tảng đặt hàng online.

**Sprint Backlog:**

* Thiết kế giao diện tìm kiếm.  
* Xây dựng tìm kiếm sản phẩm.  
* Xây dựng giỏ hàng cơ bản.  
* Tạo chức năng đặt hàng.  
* Kiểm thử các chức năng trên.

### **Increment cuối Sprint 1**

Một phiên bản có thể chạy được gồm tìm kiếm sản phẩm \=\> thêm vào giỏ hàng \=\> đặt hàng, các chức năng đã kiểm thử và đạt Definition of Done.

### **5 sự kiện Scrum**

| Sự kiện | Thời gian | Mục đích |
| ----- | ----- | ----- |
| **Sprint Planning** | Đầu Sprint | Chọn mục tiêu và công việc. |
| **Daily Scrum** | Mỗi ngày | Đồng bộ tiến độ và phát hiện vướng mắc. |
| **Sprint Review** | Cuối Sprint | Demo Increment và nhận phản hồi. |
| **Sprint Retrospective** | Sau Review | Nhìn lại và cải thiện cách làm việc. |
| **Sprint** | 2 tuần | Thực hiện công việc để tạo Increment. |

## **6\. Xử lý tình huống thay đổi**

### **Tình huống 1: Khách muốn ưu tiên đặt hàng online giữa Sprint**

Không tự ý thay đổi Sprint đang thực hiện. PO ghi nhận yêu cầu và cập nhật Product Backlog, sau đó đưa chức năng đặt hàng online vào Sprint tiếp theo nếu phù hợp.

Nếu thay đổi khiến Sprint Goal không còn phù hợp, PO có thể trao đổi với Developers và Scrum Master để xem xét điều chỉnh hoặc hủy Sprint.

### **Tình huống 2: Tính năng chưa hoàn thành ở Sprint Review**

Không trình diễn tính năng chưa hoàn thành như một Increment. Đội ghi nhận phần chưa xong và đưa lại vào Product Backlog để PO sắp xếp ưu tiên cho Sprint sau.

