# BÁO CÁO PHÂN TÍCH TỔNG HỢP CHI TIẾT: TỪ DỮ LIỆU ĐẾN HÀNH ĐỘNG THỰC TIỄN
**(Executive & Operational Report: Key Insights & Prescriptive Strategy)**
*Nền tảng phân tích: 10.5 năm dữ liệu thương mại điện tử thời trang (07/2012 - 12/2022) | Công cụ: Python, Pandas, Matplotlib, Seaborn*

---

## PHẦN I: MÔ HÌNH HÀNH VI KHÁCH HÀNG & TỐI ƯU HÓA DANH MỤC SẢN PHẨM

### Insight 1.1: Trụ cột lợi nhuận "Everyday & Balanced" (Độ tuổi 25-44)
* **Dữ liệu phân tích (Descriptive):** Căn cứ theo *Chart 17 (Segment x Age Heatmap)* và *Chart 1 (Profit by Segment)*, phân khúc `Everyday` (Lợi nhuận gộp vượt mốc 109M VNĐ ở nhóm 25-34 tuổi và 93M VNĐ ở nhóm 35-44 tuổi) và `Balanced` (84M VNĐ ở nhóm 25-34 tuổi) đóng vai trò "con bò sữa" (Cash Cow) tạo ra hơn 60% tổng lợi nhuận toàn công ty. Ngược lại, các dòng `All-weather`, `Premium`, và `Trendy` tạo ra giá trị không đáng kể (dao động từ 1M đến 11M VNĐ trên mỗi nhóm tuổi).
* **Phân tích căn nguyên (Diagnostic):** Tệp khách hàng chủ đạo của nền tảng là giới văn phòng, độ tuổi lập gia đình và trưởng thành (25-44). Đặc điểm của tệp này là sự bận rộn, ưu tiên mua sắm các sản phẩm có tính ứng dụng cao (mặc đi làm kết hợp đi chơi), thiết kế cơ bản, bền bỉ và giá cả trung lưu. Họ không quá nhạy cảm với xu hướng nhanh (Trendy) và chưa sẵn sàng chi trả liên tục cho phân khúc cao cấp (Premium).
* **Chiến lược hành động (Prescriptive):** 
  * **Short-term (Quý tới):** Chuyển 75% ngân sách Digital Marketing sang các chiến dịch đẩy mạnh dòng `Everyday`. Tạm dừng nhập hàng mới cho dòng `All-weather` để thanh lý tồn kho.
  * **Long-term (1-2 năm):** Tái cấu trúc bộ phận R&D. Áp dụng chuẩn R&D Phase 1 (50% ngân sách) cho `Everyday x 25-54`, Phase 2 (25%) cho `Balanced x 25-44`. Biến công ty thành "Top of Mind" cho thời trang ứng dụng công sở.

### Insight 1.2: Phá vỡ định kiến về "Sức mua theo Giới tính"
* **Dữ liệu phân tích (Descriptive):** *Chart 16 (Gender x Age Total Profit)* và *Chart 6 (Category x Size x Gender)* chứng minh một sự thật bất ngờ: Biểu đồ phân phối lợi nhuận giữa Nam (Male) và Nữ (Female) gần như đối xứng 50-50 trên mọi độ tuổi. Tuy nhiên, ở tập khách hàng 35+ của dòng `Everyday`, tỷ lệ Retention (mua lặp lại) của Nữ giới cho thấy tín hiệu bền vững hơn.
* **Phân tích căn nguyên (Diagnostic):** Khác với lầm tưởng bán lẻ rằng "phụ nữ mua sắm nhiều hơn", nền tảng đang sở hữu một tệp khách hàng Nam giới vô cùng trung thành. Nam giới thường có hành vi "mua lặp lại cùng một kiểu dáng" nếu sản phẩm đáp ứng tốt nhu cầu cơ bản, giúp giảm chi phí Acquisition (thu hút).
* **Chiến lược hành động (Prescriptive):** Giữ vững thông điệp "Gender-inclusive" trên website. Ra mắt các gói Bundle (Combo) "Mua cho cả gia đình" hoặc "Mua cho cặp đôi" để tận dụng tệp khách nữ (người thường đưa ra quyết định mua sắm cho chồng/con).

### Insight 1.3: Sự thật ngầm hiểu về Kênh thu hút (Acquisition Channels)
* **Dữ liệu phân tích (Descriptive):** *Chart 7 (Acquisition Channel Bubble)* phơi bày thực trạng ROI của Marketing: `Organic Search` là kênh siêu lợi nhuận (295M VNĐ tổng lợi nhuận, bong bóng to nhất về số lượng khách). Trong khi đó, các kênh tốn chi phí rầm rộ như `Referral` lại chìm nghỉm ở góc dưới (chỉ mang về 96M VNĐ, số lượng khách cực thấp). `Paid Search` và `Social Media` giữ mức khá (203M và 211M).
* **Phân tích căn nguyên (Diagnostic):** Khách hàng đến từ tìm kiếm tự nhiên (Organic Search) là những người có "Purchase Intent" (Ý định mua) rất cao, tự họ tìm kiếm nhu cầu. Khách hàng từ Referral thường tạo tài khoản chỉ để lấy mã giảm giá 1 lần, thiếu sự gắn kết với thương hiệu (Low LTV).
* **Chiến lược hành động (Prescriptive):** Cắt giảm 40% ngân sách đổ vào chương trình Affiliate/Referral kém hiệu quả. Chuyển ngân sách này sang đầu tư xây dựng Blog thời trang, SEO On-page và Content chuẩn SEO để tối đa hóa "hữu cơ" (Organic).

---

## PHẦN II: TỐI ƯU HÓA VẬN HÀNH & KIỂM SOÁT RỦI RO TÀI CHÍNH

### Insight 2.1: Báo động đỏ từ Thanh toán Tiền mặt (COD)
* **Dữ liệu phân tích (Descriptive):** *Chart 10 (Cancellation Rate)* phát đi cảnh báo đỏ: Đơn hàng COD có tỷ lệ hủy/boom hàng lên tới **16%**, cao gấp 2 lần so với tỷ lệ hủy của E-wallet/Credit Card (~8%).
* **Phân tích căn nguyên (Diagnostic):** Người mua COD không chịu rủi ro hay tổn thất tài chính khi ấn nút "Đặt hàng". Hệ quả là các quyết định mua sắm bốc đồng (impulse buying) thường dẫn đến việc từ chối nhận hàng khi Shipper đến nơi. Điều này gây lãng phí x2 chi phí vận chuyển, chi phí đóng gói, và giam vốn hàng tồn kho.
* **Chiến lược hành động (Prescriptive):** 
  * Áp dụng "Rào cản nhẹ": Yêu cầu đặt cọc phí ship (20k - 30k) hoặc đặt cọc 20% đối với các giỏ hàng COD có giá trị trên 500.000 VNĐ.
  * Tích hợp sâu các cổng thanh toán ví điện tử (MoMo, ZaloPay, VNPay) với chính sách "Giảm thẳng 5% hoặc Freeship" để dịch chuyển hành vi người dùng khỏi COD.

### Insight 2.2: Lỗ hổng "Thảm họa" từ Trả góp 2 kỳ (Installment-2)
* **Dữ liệu phân tích (Descriptive):** *Chart 11 (Installment Analysis)* cho thấy một hiện tượng kỳ lạ: Gói trả góp `Installment-2` mang lại lợi nhuận tiệm cận mức 0, đi kèm Tỷ lệ hoàn trả (Return Rate) đứng đầu (chạm đỉnh). Ngược lại, `Installment-1` và `Installment-3` hoạt động rất tốt.
* **Phân tích căn nguyên (Diagnostic):** Gói trả góp 2 tháng tạo ra một ranh giới tài chính "nửa vời". Nó thường thu hút nhóm sinh viên, lao động phổ thông muốn mua đồ quá khả năng chi trả. Khi tới kỳ thanh toán thứ 2, áp lực tài chính khiến họ tìm cớ hoàn trả sản phẩm (chính sách đổi trả).
* **Chiến lược hành động (Prescriptive):** Xóa sổ hoàn toàn nút thanh toán `Installment-2` khỏi hệ thống. Chỉ giữ lại tùy chọn trả thẳng hoặc trả góp 3 kỳ.

### Insight 2.3: Ảo ảnh lợi nhuận từ các Siêu đô thị (City Volume vs Profit)
* **Dữ liệu phân tích (Descriptive):** *Chart 8 (Top 15 Cities Lollipop)* bóc tách sự chênh lệch giữa Khách hàng (Thanh ngang) và Lợi nhuận (Chấm tròn). Nhiều thành phố có volume khách rất đông nhưng chấm lợi nhuận lại nằm tuột lại phía sau (Logistics tốn kém hoặc khách chỉ săn sale).
* **Chiến lược hành động (Prescriptive):** Không thể đánh đồng chiến lược Marketing cho mọi thành phố. Phân loại thành phố thành "Tier 1: High Margin" (Tập trung bán hàng nguyên giá, Upsell) và "Tier 2: High Volume - Low Margin" (Làm nơi xả hàng tồn kho, bán Bundle giảm giá).

---

## PHẦN III: DẤU ẤN COVID-19 & CHIẾN LƯỢC BỨT PHÁ CHUYỂN ĐỔI

### Insight 3.1: Đứt gãy Phễu Chuyển Đổi (Conversion Rate Collapse)
* **Dữ liệu phân tích (Descriptive):** Kết hợp *Chart 13 (Monthly Revenue Area)*, *Chart 14 (Decoupling)* và *Chart 15 (Recovery Scorecard)*, một bức tranh hậu COVID đáng báo động hiện ra: 
  * Giai đoạn 2016-2018 là kỷ nguyên vàng (Peak).
  * Năm 2019-2021: Lợi nhuận bốc hơi 45%.
  * Năm 2022: Lượng truy cập Website (Sessions) phục hồi **>100%**, nhưng Lợi nhuận ròng chỉ đạt **~30%**. Tỷ lệ chuyển đổi (Conversion Rate) chìm đáy ở mức **~25-37%** so với trước dịch.
* **Phân tích căn nguyên (Diagnostic):** Khách hàng vẫn dạo web (Window-shopping) do thói quen online hình thành từ đợt dịch, nhưng họ trở nên khắt khe và cực kỳ nhạy cảm về giá (Price sensitive). Ngoài ra, khả năng cao giao diện Checkout của website chưa được nâng cấp từ 2018, dẫn đến trải nghiệm di động (Mobile UX) kém, khiến khách bỏ giỏ hàng.
* **Chiến lược hành động (Prescriptive):** 
  * **Tối ưu hóa Phễu (CRO - Conversion Rate Optimization):** Rút ngay ngân sách chạy Ads kéo Traffic. Dùng ngân sách đó thuê đội ngũ UX/UI thiết kế lại màn hình Thanh toán (One-click checkout). 
  * Áp dụng "Exit-intent Popups" (Cửa sổ bật lên khi khách định thoát trang) kèm mã giảm giá 10% có thời hạn 15 phút để tạo FOMO (Fear of Missing Out).

### Insight 3.2: Sự thất bại của chính sách "Thắt lưng buộc bụng"
* **Dữ liệu phân tích (Descriptive):** *Chart 18 (Discount & Return Timeline)* chỉ ra sau cú sốc "Khủng hoảng hoàn trả (Return Crisis)" vào tháng 11/2015, công ty đã cắt giảm mạnh tay các chương trình Giảm giá (Discount) từ năm 2018 trở đi.
* **Phân tích căn nguyên (Diagnostic):** Việc cắt giảm mã giảm giá quá đà trong thời kỳ hậu COVID (khi người tiêu dùng thắt chặt chi tiêu) chính là nguyên nhân trực tiếp khiến Conversion Rate không thể phục hồi.
* **Chiến lược hành động (Prescriptive):** Thiết kế lại hệ thống khuyến mãi thông minh hơn. Không giảm giá tràn lan trên giá bán, mà chuyển sang **Freeship cho đơn từ 400k** hoặc **Mua 3 tính tiền 2** để vừa kích cầu, vừa đẩy được lượng hàng tồn kho lớn.

---

## PHẦN IV: QUẢN TRỊ CHUỖI CUNG ỨNG & KẾ HOẠCH NHẬP HÀNG (S&OP)

### Insight 4.1: Đập tan lầm tưởng "Cuối tuần mua sắm"
* **Dữ liệu phân tích (Descriptive):** *Chart 9 (Day of Week Analysis)* chứng minh doanh thu tạo ra một đường cong hình chuông, lập đỉnh vào **Thứ 3, Thứ 4 và Thứ 5**. Thứ 7 và Chủ nhật lại là vùng trũng của doanh thu.
* **Chiến lược hành động (Prescriptive):** Lịch trình gửi SMS Marketing, Email và ra mắt BST mới phải chuyển sang **10h sáng Thứ 3 hoặc Thứ 4**. Tránh việc "đốt tiền" chạy quảng cáo khung giờ vàng cuối tuần khi khách hàng đang đi chơi offline và không chú ý điện thoại.

### Insight 4.2: Cuộc cách mạng trong Kế hoạch Đặt hàng (S&OP Planning)
* **Dữ liệu phân tích (Descriptive):** Qua bộ *Dashboard Kế hoạch Nhập hàng (Chart A đến Chart G)*:
  * **Chart C:** Tỷ trọng mua Size biến động cực mạnh. Quý 4 (mùa đông) tiêu thụ size L, XL nhiều hơn hẳn mùa hè. Việc cắt size theo tỷ lệ cố định (VD: 1:2:2:1) sẽ dẫn đến tồn kho rác trầm trọng.
  * **Chart D:** Tỷ trọng chi tiêu giữa Nam và Nữ có độ lệch pha theo từng tháng.
* **Chiến lược hành động (Prescriptive):** Loại bỏ hoàn toàn phương pháp nhập hàng "Cảm tính" hoặc "Dựa theo năm ngoái". Ban Giám đốc yêu cầu bộ phận Cung ứng (Procurement) bắt buộc áp dụng **Bộ 2 Bảng Template (CSV)** được sinh ra từ hệ thống:
  1. **Template Số Lượng (Dựa trên Chart F - `Order_Plan_Quantity_Template.csv`):** Dùng để chốt số lượng gia công tối thiểu với xưởng. Cho biết chính xác cần may bao nhiêu chiếc áo `Everyday-Nữ-Size M` vào Tháng 11.
  2. **Template Ngân Sách (Dựa trên Chart G - `Order_Plan_Profit_Allocation_Template.csv`):** Dùng cho Giám đốc Tài chính (CFO) để phân bổ phần trăm vốn lưu động. Nhấn mạnh việc dồn tiền cho các SKU có tỷ suất lợi nhuận cao thay vì chỉ nhìn vào sản lượng bán.

---
---

## APPENDIX: HỆ THỐNG DANH MỤC 18+ DASHBOARD PHÂN TÍCH
*(Phụ lục dành cho Ban Giám đốc và Data Team dùng để tra cứu chéo số liệu)*

| Mã Chart | Tên Biểu Đồ | Phương pháp & Tiêu chí Thống kê (Metrics) | Ý nghĩa Vận hành (Business Purpose) |
| :--- | :--- | :--- | :--- |
| **Chart 01** | Profit by Segment (Bar Chart) | `adjusted_profit` (Sum) | Đo lường "Sức khỏe tài chính" của từng dòng sản phẩm. Khẳng định Everyday là Cash Cow. |
| **Chart 02** | Category x Segment Heatmap | `adjusted_profit` (Sum) x 2 Dimensions | Tìm ra giao điểm hái ra tiền (Ví dụ: Streetwear x Everyday). |
| **Chart 03** | Category x Age Group Heatmap | `adjusted_profit` (Sum) x 2 Dimensions | Lập bản đồ thị hiếu theo thế hệ (Gen Z vs Millennials). |
| **Chart 04** | Segment x Size Heatmap | `adjusted_profit` (Sum) x 2 Dimensions | Nhận diện form dáng chủ lực của từng phân khúc. |
| **Chart 05** | Size Order Ratio (Pie/Donut) | `% Profit` by Size | Cấu trúc rập/cắt size tổng quan của toàn thương hiệu. |
| **Chart 06** | Category x Size x Gender | `adjusted_profit` (Sum) x 3 Dimensions | Hỗ trợ phân bổ hàng hóa cho các cửa hàng (Store Allocation). |
| **Chart 07** | Acquisition Channel (Bubble) | `Orders per Cust` x `Total Profit` x `Cust Count` | Đánh giá ROI và giá trị trọn đời (CLV) của từng kênh Marketing. |
| **Chart 08** | Top 15 Cities (Lollipop/Dual) | `Cust Count` (Bar) vs `Total Profit` (Dot) | Tách bạch giữa số lượng khách và lợi nhuận thực mang lại trên từng địa lý. |
| **Chart 09** | Day of Week (Bar & Line) | `Total Profit/Rev` (Bar) + `Return Rate` (Line) | Xác định "Khung giờ vàng" để chạy Flash Sale và Marketing. |
| **Chart 10** | Cancellation by Payment (Bar) | `% Cancel` vs `Payment Method` | Đo lường rủi ro thanh toán và lỗ hổng từ hình thức COD. |
| **Chart 11** | Installment Analysis (Combo) | `Total Profit` (Bar) vs `Return Rate` (Line) | Loại bỏ các chính sách tài chính độc hại (Installment-2). |
| **Chart 12** | Price Tier Analysis (4-Panel) | `Revenue`, `Profit`, `Rating`, `Avg Discount` | Định vị phân khúc giá và biên lợi nhuận thực tế của hàng Premium/Medium/Low. |
| **Chart 13** | Monthly Revenue (Area Chart) | `Net Rev`, `COGS`, `Gross Profit` over Time | Bức tranh toàn cảnh về sức khỏe doanh nghiệp trong 11 năm. |
| **Chart 14** | Decoupling (Line/Dual Axis) | `Sessions` vs `Net Revenue` over Time | Phát hiện đứt gãy giữa Traffic và Khả năng tạo ra tiền mặt (Conversion gap). |
| **Chart 15** | COVID Recovery (Gauge) | `% Recovery` vs Pre-COVID Baseline | Chấm điểm tốc độ phục hồi của các chỉ số sống còn. |
| **Chart 16** | Gender x Age Heatmap | `adjusted_profit` (Sum) | Cơ sở để hoạch định chiến lược nhắm mục tiêu (Targeting) trên Facebook/Google Ads. |
| **Chart 17** | Segment x Age Target Heatmap | Bản đồ R&D Target Zone (Red/Orange box) | Quy hoạch rõ ràng ngân sách thiết kế và ra rập (R&D Phase 1-4). |
| **Chart 18** | Discount & Return Timeline | `Return Rate` vs `Avg Discount` (Time Series) | Cảnh báo lịch sử về khủng hoảng hoàn trả và tác dụng ngược của việc siết khuyến mãi. |
| **Chart A** | Seasonality by Category | `Monthly % Profit` x Category | Xác định mùa cao điểm của Streetwear, Outerwear... |
| **Chart B** | Seasonality by Segment | `Monthly % Profit` x Segment | Quyết định tháng nào nên tung bộ sưu tập Everyday hay Balanced. |
| **Chart C** | Monthly Size Ratio (Stacked) | `Size %` x Month | Điều chỉnh tỷ lệ cắt rập (S/M/L/XL) theo từng tháng thực tế. |
| **Chart D** | Gender Split by Month | `Male vs Female Profit` x Month | Quyết định tỷ lệ nhập hàng Nam/Nữ cho từng tháng. |
| **Chart F** | Detailed Qty Matrix (Heatmap)| `Avg Quantity` x Segment x Gender x Size | **Template Đặt Hàng:** Bảng chốt số lượng sản xuất thực tế với nhà máy mỗi tháng. |
| **Chart G** | Detailed Profit Matrix (Heatmap)| `Profit %` x Segment x Gender x Size | **Template Ngân Sách:** Bảng phân bổ % vốn lưu động hàng tháng cho CFO. |

---
**Báo cáo được xuất tự động từ hệ thống Jupyter Notebook (02_business_analysis.ipynb)**. 
*Tất cả hình ảnh biểu đồ độ phân giải cao và file CSV Template được lưu trữ tại thư mục `./output/` để phục vụ công tác thuyết trình.*
