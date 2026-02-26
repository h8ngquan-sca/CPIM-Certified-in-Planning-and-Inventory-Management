# Tác động của các môi trường sản xuất khác nhau lên quy trình S&OP

Trước khi xem xét tác động của từng môi trường, S&OP **Xác định, thu thập và tổng hợp thông tin từ tất cả các nguồn nhu cầu tổng hợp (Aggregate sources of demand)**  có thể hoặc sẽ tác động đến vận hành hệ thống, bao gồm:
- Doanh số bán hàng cho khách (bao gồm cả phụ tùng thay thế).
- Nhu cầu luân chuyển nội bộ/giữa các nhà máy (Interplant/intracompany transfers).
- Hàng cho các đợt khuyến mãi, dự án thử nghiệm.
- Kiểm định chất lượng (QA) và các khoản quyên góp từ thiện.

Tiếp theo, việc thiết kế sản phẩm/dịch và đặc điểm của sản phẩm dựa trên vị tối ưu 5 yếu tố ***Tốc độ (speed), độ tin cậy (dependability), tính linh hoạt (flexibility), chất lượng (quality) và chi phí (cost)*** để xác định cấu trúc quy trình sản xuất. Từ cấu trúc quy trình sản xuất đã chốt, hệ thống sẽ được thiết lập để vận hành theo 1 trong 4 môi trường sản xuất chính: Làm để lưu kho (MTS), Làm theo đơn hàng (MTO), Lắp ráp theo đơn hàng (ATO), hoặc Thiết kế theo đơn hàng (ETO)

Mỗi môi trường sản xuất sử dụng loại dữ liệu và đơn vị đo lường khác nhau để lập kế hoạch và vận hành:

| Môi trường sản xuất         | Thông tin cốt lõi cần cung cấp cho S&OP                                                                            | Đơn vị đo lường kế hoạch                                |
| :-------------------------- | :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------ |
| **Engineer-to-order (ETO)** | Thông số kỹ thuật từ khách hàng, số lượng năng lực kỹ thuật (engineering capacity) cần thiết, và lịch trình dự án. | Giờ công kỹ thuật (Engineering labor hours).            |
| **Make-to-order (MTO)**     | Dự báo nhu cầu theo nhóm sản phẩm (product family), các thông số thiết kế/vật liệu chi tiết từ bộ phận kỹ thuật.   | Khối lượng nợ đơn hàng (Order backlog).                 |
| **Assemble-to-order (ATO)** | Dự báo nhu cầu theo nhóm sản phẩm (product family) và các tùy chọn cấu hình lắp ráp.                               | Giờ công máy móc và lao động (Machine and labor hours). |
| **Make-to-stock (MTS)**     | Dự báo nhu cầu theo nhóm sản phẩm (Product family).                                                                | Năng lực cung ứng vật liệu (Material supply capacity).  |

Dù ở môi trường nào, chức năng quan trọng của S&OP là ***phản ứng linh hoạt với các thay đổi trung và dài hạn*** (ví dụ: khách hàng lớn thay đổi lượng đặt hay thay đổi chính sách tồn kho an toàn, thời gian giao hàng). Khả năng đáp ứng thời gian giao hàng (lead time) sẽ bị chi phối bởi yêu cầu thiết kế, mức độ sẵn có của linh kiện và nguồn lực.
