# Các liên kết chính

| Các thành phần của quy trình MPC                                    | Liên kết với S&OP                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Demand Planning (Hoạch định nhu cầu)**                            | Là nguồn cung cấp dữ liệu đầu vào cốt lõi. S&OP phụ thuộc vào bộ phận này để **thu thập _tất cả_ các nguồn cầu tác động lên năng lực sản xuất**, bao gồm dự báo bán hàng, đơn đặt hàng từ mọi cấp độ phân phối, nhu cầu luân chuyển nội bộ (interplant) và các yêu cầu dịch vụ bảo hành                                                                                                                         |
| **Resource Planning (Hoạch định nguồn lực)**                        | Đóng vai trò **đánh giá tính khả thi**. Nó cung cấp cho S&OP các **ước tính về năng lực cần thiết** cho các phương án kế hoạch thay thế, đồng thời đảm bảo doanh nghiệp có sẵn các nguồn lực then chốt để hỗ trợ cho giai đoạn lập lịch trình sản xuất (master production scheduling)                                                                                                                           |
| **Master Production Scheduling - MPS (Lịch trình sản xuất chính):** | Là một trong kết quả đầu ra từ S&OP. **MPS thực hiện việc "phân rã" (disaggregation)** kế hoạch sản xuất từ cấp độ Nhóm sản phẩm (Product family) xuống thành số lượng chi tiết cho từng mã hàng cụ thể (end-item mix). Nguyên tắc quan trọng là tổng số lượng hoạch định cho từng mã hàng (end-item quantities) trong MPS bắt buộc phải khớp với khối lượng tổng Nhóm mã hàng (product family) mà S&OP đã chốt |
| **Distribution Planning (Hoạch định phân phối):**                   | **Quản lý tồn kho** tại các địa điểm phân phối. Nhu cầu từ các trung tâm phân phối được gộp lại (rolled up) để xác định tổng cầu tồn kho phân phối. Ngoài ra, bộ phận này báo cáo cho S&OP biết hệ thống logistics có đủ năng lực lưu trữ và vận chuyển để đưa hàng hóa đến tay khách hàng đúng hạn hay không                                                                                                   |

# Planning Factors

Để các bộ phận này có thể giao tiếp hiệu quả, S&OP cần thống nhất về 3 Yếu tố Hoạch định cốt lõi (Planning Factors):

| Yếu tố Hoạch định (Planning Factor)           | Bản chất / Định nghĩa                                                                                  | Nguyên tắc quản lý cốt lõi trong S&OP                                                                                                                                                                                                                       |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Đơn vị đo lường (Units of Measure)**     | Đơn vị dùng để quản lý số lượng sản phẩm (ví dụ: cái, cân, tấn, giờ lao động, giá trị tiền tệ)         | Các phòng ban thường dùng đơn vị khác nhau (Tài chính dùng USD, Sản xuất dùng giờ công/tấn). <br>S&OP đóng vai trò như một bộ chuyển đổi, dịch các đơn vị này qua lại để tất cả các bên đều hiểu và cam kết thực hiện chung một kế hoạch                    |
| **2. Gia đình sản phẩm (Product Family)**     | Nhóm các sản phẩm có cùng đặc điểm, đi qua các bước xử lý tương tự và chia sẻ chung thiết bị/nguồn lực | Con số tối ưu là từ **6 đến 12 nhóm**; nếu nhiều hơn sẽ gây sa lầy vào chi tiết. Việc phân nhóm nên dựa trên cách thị trường nhìn nhận sản phẩm, đồng thời phải có ý nghĩa đối với cả bán hàng và năng lực sản xuất                                         |
| **3. Tầm nhìn hoạch định (Planning Horizon)** | Khoảng thời gian mà kế hoạch mở rộng về phía tương lai                                                 | Thường kéo dài từ **15 đến 18 tháng** (hoặc hơn) và chia theo từng tháng. Nguyên tắc sống còn là tầm nhìn phải dài hơn tổng thời gian hoàn thành (cumulative lead time) để doanh nghiệp kịp thời điều chỉnh và bổ sung năng lực (mua máy móc, tuyển người). |

**1/ Đơn vị đo lường (Units of measure)**
**Khái niệm Đơn vị đo lường (Unit of measure):** Là đơn vị chuẩn dùng để quản lý số lượng của một mặt hàng (ví dụ: cân, cái, hộp 12 chiếc, kiện 144 chiếc). 

**Thách thức:** các quy trình khác nhau thường diễn giải đơn vị đo lường theo cách khác nhau. Ví dụ: Kế hoạch vận hành thường sử dụng đơn vị đo lường "tổng sản lượng mỗi tháng", trong khi MPC lại đo lường bằng "số lượng sản phẩm tồn mỗi tuần". Phương pháp tốt nhất là sử dụng một đơn vị chung nhất quán với cách tổ chức tiếp cận thị trường và có bảng quy đổi chuẩn giữa các phòng ban.

**Các thước đo cần đồng bộ (Measurements):** Để hệ thống S&OP thống nhất, cần chuẩn hóa các thước đo chính sau đây giữa các phòng ban:
- Tổng số đơn vị cho mỗi dòng sản phẩm (product line).
	- **Định nghĩa Dòng sản phẩm (Product Line):** Dòng sản phẩm là một nhóm các sản phẩm có liên quan với nhau qua chức năng, nhóm người tiêu dùng, kênh phân phối, đặc điểm sản xuất hoặc mức giá. Phản ánh góc nhìn tiếp thị và bán hàng (Marketing and Sales), được sử dụng rất nhiều trong việc lập kế hoạch tổng hợp, định giá và kế hoạch bán hàng
- Giá trị tiền tệ (Dollar value) của tổng sản lượng hàng tháng.
- Tổng sản lượng theo từng nhà máy.
- Số giờ lao động.
- Khối lượng sản phẩm (ví dụ: Số tấn sản phẩm).

**2/ Nhóm sản phẩm (Product family)** 
**Gia đình sản phẩm (Product family):** Là một nhóm các sản phẩm hoặc dịch vụ ***trải qua các bước xử lý tương tự nhau, có chung đặc điểm và sử dụng chung thiết bị/nguồn lực trước khi được giao cho khách hàng***. Khái niệm này được sử dụng chủ yếu trong hoạch định sản xuất và S&OP để tính toán năng lực.

Phương pháp thường được sử dụng để xác định Product family là xác định ***sự tương đồng về đặt điểm sản xuất***. Lý do là vì những sản phẩm có đặc điểm giống nhau sẽ đi qua các quy trình tương tự, dùng chung máy móc, thiết bị hoặc nhân công (tức là sử dụng cùng một loại năng lực sản xuất - capacity). Việc gom chung chúng lại giúp ban quản lý dễ dàng tính toán tổng nguồn lực cần thiết và lên kế hoạch sản xuất hàng loạt một cách hiệu quả

**Danh sách các cách gộp nhóm khả thi (List of possible product family grouping):** khoảng tối ưu cho việc tạo Gia đình sản phaarm là từ **6 đến 12 nhóm**. Danh sách các cách gộp nhóm sản phẩm từ mức độ tổng quát nhất đến chi tiết: 
1. **Total company** (Toàn công ty)
2. **Business unit** (Đơn vị kinh doanh)
3. **Product family** (Gia đình sản phẩm)
4. **Product subfamily** (Phân nhóm sản phẩm/Nhóm phụ)
5. **Model/brand** (Mẫu mã/Thương hiệu)
6. **Package size** (Kích thước đóng gói)
7. **SKU** (Đơn vị lưu kho chi tiết)
8. **SKU by customer** (SKU theo khách hàng)
9. **SKU by customer by location** (SKU theo khách hàng và theo địa điểm phân phối)

Việc gộp nhóm Gia đình sản phẩm nên thể hiện sự ***logic và mang tính đại diện*** (Logical and representative) , phản ánh đúng cách mà các sản phẩm được đưa ra thị trường. Một cách phân nhóm hiệu quả nên đáp ứng 4 tiêu chí:
1. Thuận tiện cho các phòng ban khác nhau trong việc dự báo và cung cấp dữ liệu.
2. Có ý nghĩa trong việc đo lường khối lượng doanh số.
3. Có ý nghĩa đối với việc hoạch định sản xuất và năng lực.
4. Giúp tổ chức chọn được "Đơn vị đo lường" chuẩn xác cho từng nhóm.

**3/ Tầm nhìn hoạch định (Planning horizon)**
**Tầm nhìn hoạch định (Planning horizon):** Là khoảng thời gian mà một kế hoạch mở rộng trong tương lai, đối với:
- **Kế hoạch ngắn hạn (như Lịch trình sản xuất chính - MPS):** Tầm nhìn phải bao trùm ít nhất là tổng thời gian chờ (cumulative lead time), cộng thêm thời gian để gom lô (lot sizing) và thời gian thay đổi công suất của máy móc hoặc nhà cung cấp chính.
- **kế hoạch dài hạn (như S&OP):** Tầm nhìn phải đủ dài để tổ chức kịp thời bổ sung các năng lực sản xuất khi cần thiết (ví dụ: mua máy móc mới, mở rộng nhà máy).
Đối với S&OP, độ dài thường kéo dài từ **15 đến 18 tháng**. Con số này được tính bằng một chu kỳ kế hoạch kinh doanh hàng năm cộng thêm một khoảng đệm (thường từ 3 đến 6 tháng) để kết nối với năm tài chính tiếp theo. Tầm nhìn có thể dài hơn 18 tháng nếu tổ chức cần mua sắm các tài sản hoặc vật liệu có thời gian chờ (lead time) đặc biệt dài.
