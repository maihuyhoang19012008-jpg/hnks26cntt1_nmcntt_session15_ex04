

# VẤN ĐỀ 
Nhóm của bạn quản lý 500GB dữ liệu video giám sát campus. Ổ cứng Laptop của các bạn chỉ có 256GB. Nếu đồng bộ toàn bộ về máy, SSD sẽ bị tràn ngay lập tức và gây treo phần mềm đồng bộ.

# Yêu cầu
• Giải pháp kỹ thuật: Mô tả cách thiết lập tính năng Files On-Demand để chỉ tải file xuống khi cần mở thực tế.
• Báo cáo dung lượng: Tính toán và chứng minh tính hiệu quả của giải pháp khi dung lượng Cloud lớn hơn dung lượng Local SSD nhiều lần.
# BÀI LÀM 
## PHẦN 1 
Không đồng bộ toàn bộ về máy. Mọi file trên Cloud hiển thị trên máy dưới dạng biểu tượng đám mây  chỉ tải xuống thực sự khi bạn double-click mở file.
**các bước**
1.  Cài Google Drive cho Máy tính 
2. Vào Cài đặt  Files On-Demand   Bật "Save space and download files as you use them"
3. chọnthư mục Video_Giam_Sat  đặt chế độ (chỉ trực tuyến)
4. Khi cần xem một đoạn video nhấn  double-click  file tự tải về xem xong có thể "Free up space" (Giải phóng dung lượng) để xóa bản local, giữ bản Cloud


|Bẫy|Cách xử lý|
|-|-|
|Treo mạng nhà trọ|Giới hạn băng thông upload vài Mbps, lên lịch upload ban đêm|
|Đứt đoạn khi gập máy|Dùng công cụ hỗ trợ |

## Phần 2 


|Chiếm SSD|Đồng bộ toàn bộ
|-|-|
|500 GB|Files On-Demand, mở 10%|
|50 GB|Files On-Demand, mở 40%|
|200 GB|Chỉ metadata |
|0.5 GB|chưa mở file nào)|
>Files On-Demand cho phép Cloud lớn gấp nhiều lần SSD mà vẫn hoạt động mượt, vì chỉ tải file nào thực sự cần mở.
