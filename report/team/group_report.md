# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm League
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra        | Candidate (Job Story ngắn)                                                                                                                                                                                                             | Actor | Bottleneck                                                                                                                                                                                                                                     | Câu hỏi phản biện nhận được (ai hỏi)                                                                                                                                                                                                                                                                                                                                                                                                      |
|---:|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Đỗ Anh Thư | Khi chuẩn bị nhập hàng mới, tôi muốn biết mặt hàng nào còn tồn kho nhiều, mặt hàng nào bán chạy và sắp hết, để quyết định nhập hàng hợp lý, tránh thiếu hàng hoặc tồn kho quá nhiều. |Chủ cửa hàng, nhân viên | phải kiểm tra nhiều mẫu quần áo, màu sắc, kích cỡ và đối chiếu số lượng bán với tồn kho. Giả thuyết: mất khoảng 30–60 phút mỗi lần kiểm tra và lên danh sách nhập hàng.| Các phần mềm quản lý kho (POS/ERP) hiện nay đều có thể tự động đặt ngưỡng Min/Max và hiển thị cảnh báo dashboard dựa trên số liệu bán hàng. Tại sao nhóm phải dùng Machine Learning dự đoán phức tạp trong khi giải pháp phần mềm thông thường (Rule-based) đã giải quyết được 80% bài toán này?(Hoàng Quang Đạt),Mở rộng vấn đề, sử dụng AI để phân loại đồ và tính tồn kho cho từng chi nhánh thay vì chỉ một chỗ.(Nguyễn Tài Minh Huy) |
| 2 | Nguyễn Tài Minh Huy | Khi chương trình Python xuất hiện lỗi trong lúc làm assignment, mình muốn xác định chính xác nguyên nhân để sửa lỗi và tiếp tục làm bài mà không phải thử nhiều cách không hiệu quả.|Học viên học các loại ngôn ngữ lập trình. | Việc xác định nguyên nhân lỗi tốn nhiều thời gian vì cần hiểu thông báo lỗi và tìm đúng vị trí trong code. Đã có trường hợp quá trình debug kéo dài trên 30 phút. | Không có. |
| 3 | Võ Thanh Huy | Khi một sản phẩm có nhiều đánh giá trái chiều từ người mua trước, tôi muốn xác định những ưu điểm và nhược điểm thường gặp, để hạn chế lựa chọn sản phẩm không đáp ứng nhu cầu.|Người cần tìm hiểu chất lượng sản phẩm trước khi mua | Bước 3 — đọc nhiều đánh giá, dự kiến mất 12 phút trong tổng số 25 phút. Đây là thời gian phân bổ tạm, cần đo lại. | Làm sao để nhận dạng được comment nào hoặc đánh giá nào là đúng và cái nào là bot/spam? (Nguyễn Tài Minh Huy) |
| 4 | Hoàng Quang Đạt| Tóm tắt mốc thời gian & việc cần làm từ file ghi âm bài giảng/buổi họp|Sinh viên, Học sinh, thành viên phụ trách ghi biên bản cuộc họp | Bước 3: Mất 35 phút tua đi tua lại vì không biết đoạn nào nói về bài tập/nhiệm vụ | Làm sao để đoán được hoặc nắm bắt được topic của người nói? (Nguyễn Tài Minh Huy) |
| 5 | Đỗ Anh Thư | Khi cần chuyển khoản hoặc thanh toán online, người thân, người lớn tuổi muốn tự thực hiện giao dịch một cách dễ hiểu và an toàn, để không phải thường xuyên nhờ con cháu hỗ trợ. |Người lớn tuổi, người thân |Bước 2–5: phải đọc nhiều nguồn, lọc thông tin quan trọng, xác định deadline và nhập lại thủ công. Giả thuyết: mất khoảng 15–30 phút/ngày để kiểm tra và tổng hợp công việc. | Khó khăn chính của người lớn tuổi nằm ở việc hiểu các bước thanh toán hay lo sợ chuyển nhầm tiền (Nguyễn Tài Minh Huy)? Nếu ngân hàng đã có giao diện đơn giản và xác nhận giao dịch, vấn đề nào vẫn chưa được giải quyết (Võ Thanh Huy)? |
| 6 | Đỗ Anh Thư | Khi tham gia khóa học hoặc dự án có nhiều bài tập và deadline được thông báo ở nhiều nơi, tôi muốn tổng hợp công việc vào một danh sách thống nhất để tránh bỏ sót nhiệm vụ và chủ động sắp xếp thời gian. | Sinh viên hoặc người tham gia chương trình đào tạo, khóa học, dự án | Bước 2–5: Phải đọc nhiều nguồn, lọc thông tin quan trọng, xác định deadline và nhập lại thủ công. Giả thuyết mất 15–30 phút mỗi ngày. | Google Calendar hoặc Notion đã có chức năng quản lý deadline. Tại sao các công cụ này chưa đáp ứng đủ nhu cầu? (Nguyễn Tài Minh Huy) |
| 7 | Nguyễn Tài Minh Huy | Khi chuẩn bị nộp assignment, mình muốn đối chiếu bài làm với rubric và hướng dẫn để phát hiện những phần còn thiếu hoặc chưa chính xác trước khi nộp. | Học viên chương trình AI Thực chiến tại VinUni | Việc đối chiếu từng tiêu chí với bài làm tốn thời gian vì rubric có nhiều yêu cầu và học viên phải tự tìm nội dung tương ứng trong bài. | Nếu dùng checklist dựa trên rubric, liệu có giải quyết được phần lớn vấn đề mà không cần AI không? (Đỗ Anh Thư) |
| 8 | Nguyễn Tài Minh Huy | Khi hoàn thành một buổi học có nhiều kiến thức mới, mình muốn xác định những nội dung bản thân đã hiểu và những phần còn yếu để ưu tiên cải thiện trước buổi học tiếp theo. | Học viên chương trình AI Thực chiến tại VinUni | Khó xác định chính xác kiến thức còn yếu vì đôi khi mình cảm thấy đã hiểu lý thuyết nhưng vẫn gặp khó khăn khi áp dụng. Mình mất ít nhất 30 phút để hiểu và thêm ít nhất 30 phút để áp dụng. | 1. Nếu học viên làm đúng câu hỏi lý thuyết nhưng không áp dụng được vào thực hành, làm thế nào để đánh giá mức độ hiểu bài? (Hoàng Quang Đạt) Làm thế nào để phân biệt kiến thức thực sự còn yếu với lỗi sai do bất cẩn? (Võ Thanh Huy) |
| 9 | Võ Thanh Huy | Khi tìm vị trí thực tập, tôi muốn xác định các công việc phù hợp với kỹ năng hiện tại để không mất thời gian đọc những tin tuyển dụng không đáp ứng điều kiện. | Sinh viên năm cuối, sinh viên mới tốt nghiệp hoặc người chưa có kinh nghiệm đang tìm thực tập | Bước 3 và 4: Đọc yêu cầu công việc và đối chiếu với kỹ năng bản thân. Tổng thời gian tìm và đối chiếu 20 tin khoảng 30 phút, cần đo riêng từng bước. | Không có |
| 10 | Võ Thanh Huy | Khi có nhiều bài tập và hạn nộp từ các môn học hoặc hoạt động khác nhau, tôi muốn nắm được thời hạn từng việc để sắp xếp thời gian và tránh nộp muộn. | Sinh viên tham gia nhiều môn học, khóa đào tạo hoặc hoạt động có deadline khác nhau | Bước 2 và 5: Phải kiểm tra nhiều nguồn thông báo và thường xuyên xem lại deadline. | Candidate này khác gì so với #6 về tổng hợp nhiệm vụ và deadline? Có thể gộp hai vấn đề không? (Hoàng Quang Đạt) |
| 11 | Hoàng Quang Đạt | Khi người nhà lớn tuổi gửi ảnh chụp đơn thuốc viết tay kèm chẩn đoán, tôi muốn hiểu rõ hướng dẫn sử dụng thuốc để hỗ trợ người thân dùng đúng theo chỉ định của bác sĩ. | Con cái hoặc người thân hỗ trợ người lớn tuổi | Bước 2 và 3: Mất khoảng 30 phút đọc chữ viết tắt, làm rõ tên thuốc và hướng dẫn, có nguy cơ hiểu nhầm liều lượng. | Nếu chữ viết tay của bác sĩ không rõ, làm thế nào để tránh nhận diện sai tên thuốc hoặc liều lượng? (Nguyễn Tài Minh Huy) Ai sẽ chịu trách nhiệm kiểm tra kết quả trước khi người nhà sử dụng thông tin? (Đỗ Anh Thư) Tại sao không xác nhận trực tiếp với bác sĩ hoặc dược sĩ thay vì cố gắng diễn giải đơn thuốc? (Võ Thanh Huy) |
| 12 | Hoàng Quang Đạt | Khi khách hàng gửi tin nhắn phản ánh chất lượng bằng ngôn ngữ bức xúc hoặc từ viết tắt, tôi muốn phân loại nhanh mức độ khẩn cấp và lý do phản ánh để chuyển đúng người xử lý trong vòng 15 phút. | Nhân viên trực page chăm sóc khách hàng, nhân viên hỗ trợ kỹ thuật | Bước 2 và 3: Mất khoảng 8 phút mỗi tin để hiểu nội dung và xác định mức độ ưu tiên. Khi quá tải có nguy cơ bỏ sót phản ánh quan trọng. | Làm thế nào phân biệt tin nhắn thực sự khẩn cấp với tin nhắn chỉ dùng ngôn ngữ bức xúc? (Nguyễn Tài Minh Huy) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A – Học tập và giải quyết bài tập | #2 Debug Python, #4 Tóm tắt bài giảng/cuộc họp, #7 Kiểm tra assignment, #8 Xác định kiến thức còn yếu | Người học gặp khó khăn khi xử lý, hiểu và áp dụng thông tin trong quá trình học tập. |
| B – Quản lý nhiệm vụ và thời gian | #6 Tổng hợp nhiệm vụ và deadline, #10 Theo dõi nhiều deadline | Thông tin về công việc và thời hạn nằm ở nhiều nguồn, khiến người dùng phải kiểm tra và tổng hợp thủ công. |
| C – Phân tích thông tin để đưa ra quyết định | #1 Quản lý tồn kho, #3 Phân tích đánh giá sản phẩm, #9 Tìm vị trí thực tập | Người dùng cần đọc, đối chiếu và phân tích nhiều nguồn thông tin để đưa ra lựa chọn phù hợp. |
| D – Hiểu thông tin quan trọng trong đời sống | #5 Thanh toán online cho người lớn tuổi, #11 Hiểu đơn thuốc viết tay | Người dùng gặp khó khăn khi hiểu thông tin quan trọng, có nguy cơ thực hiện sai thao tác hoặc hiểu sai hướng dẫn. |
| E – Phân loại thông tin khách hàng | #12 Phân loại tin nhắn phản ánh của khách hàng | Nhân viên cần xác định nội dung và mức độ ưu tiên của tin nhắn để chuyển đúng người xử lý. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian kiểm tra tồn kho và cải thiện quyết định nhập hàng.
|
|__ Opportunity A: Chủ cửa hàng mất thời gian đối chiếu tồn kho theo mẫu, màu sắc và kích cỡ.
|
|__ Opportunity B: Khó xác định mặt hàng bán chạy và có nguy cơ hết hàng.
|
|__ Opportunity C: Khó quyết định số lượng nhập thêm để tránh thiếu hàng hoặc tồn kho quá nhiều.
```

Những ý không đưa vào tầng Opportunity vì là giải pháp:

1. Xây chatbot tự động sửa lỗi Python.
2. Tạo công cụ AI tự động kiểm tra assignment.
3. Xây AI Tutor tự động đánh giá kiến thức của học viên.


### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 – Quản lý tồn kho | 5 | 5 | 3 | 5 | 5 | 5 | 4 | 32 |
| #6 – Tổng hợp nhiệm vụ và deadline | 5 | 4 | 2 | 4 | 5 | 4 | 4 | 28 |
| #12 – Phân loại phản ánh khách hàng | 5 | 5 | 3 | 4 | 4 | 5 | 3 | 28 |

**Candidate được chọn:** #1 – Quản lý tồn kho và hỗ trợ quyết định nhập hàng.

**Vì sao chọn:** Candidate #1 có actor rõ ràng là chủ cửa hàng và nhân viên quản lý kho. Vấn đề xuất hiện khi cần kiểm tra số lượng hàng tồn theo mẫu, màu sắc và kích cỡ, sau đó đối chiếu với tình hình bán hàng để quyết định nhập thêm. Quy trình có thể mô tả rõ, thời gian xử lý có thể đo được và kết quả cải thiện có thể đánh giá qua thời gian lập danh sách nhập hàng, số lần thiếu hàng và lượng tồn kho. Ngoài ra, nhóm có thể so sánh các phương án từ kiểm tra thủ công, cảnh báo Min/Max đến dự báo nhu cầu bằng Machine Learning để xác định mức can thiệp phù hợp.

**Vì sao loại các candidate còn lại:**

1. **Candidate #6 – Tổng hợp nhiệm vụ và deadline:** Vấn đề có tính thực tế và dễ triển khai, nhưng có thể được giải quyết phần lớn bằng các công cụ quản lý công việc hoặc lịch nhắc hạn hiện có. Nhóm cần thêm bằng chứng để xác định phần khó khăn mà các công cụ thông thường chưa giải quyết được.

2. **Candidate #12 – Phân loại phản ánh khách hàng:** Đây là vấn đề có tiềm năng ứng dụng AI, đặc biệt với những tin nhắn sử dụng ngôn ngữ không chuẩn hoặc viết tắt. Tuy nhiên, việc kiểm chứng cần có dữ liệu tin nhắn thực tế, tiêu chí phân loại rõ ràng và cách đánh giá mức độ khẩn cấp. Nhóm đánh giá phạm vi này khó kiểm chứng hơn trong thời gian lab.

**Xử lý bất đồng (nếu có):** Nhóm cần ghi lại các ý kiến khác nhau trong quá trình chấm điểm và lý do thống nhất chọn Candidate #1.


---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|:---:|
| 1 | Người bán thời trang/chủ shop mất nhiều thời gian (trên 45 phút/lần) đối chiếu thủ công tồn kho chi tiết (màu/size) với tốc độ bán để quyết định nhập hàng | Value | 5 | 2 | ✅ |
| 2 | Chủ shop sẵn sàng nhập hàng theo số lượng do máy tính/hệ thống tự động đề xuất thay vì dựa vào kinh nghiệm và linh cảm | Value | 5 | 1 | ✅ |
| 3 | Ngưỡng tồn kho tĩnh (Min/Max cố định) trên các phần mềm POS/Excel hiện nay không đủ linh hoạt để xử lý biến động tiêu thụ giữa các mã hàng | Value | 4 | 2 | ✅ |
| 4 | Dữ liệu lịch sử giao dịch và biến động tồn kho chi tiết theo từng SKU (màu/size) có thể xuất được từ Excel hoặc POS phổ biến (KiotViet, Sapo, Shopee) | Feasibility | 4 | 4 | — |
| 5 | Người dùng có thể dễ dàng hiểu lý do gợi ý (tốc độ bán, ngày tồn) và chỉnh sửa số lượng trên bản đề xuất nháp [DRAFT] trong dưới 15 phút | Usability | 4 | 2 | — |

Giả định nhóm kiểm chứng trong buổi này: **Giả định #1, #2 và #3** (đã được đưa vào kiểm chứng thực tế tại Mục 3.2 thông qua phỏng vấn The Mom Test và poll nhanh).

### 3.2. Kiểm chứng

**Cách đã dùng:** Phỏng vấn chéo bạn học nhóm khác theo The Mom Test (từng bán hàng online / làm thêm quản lý kho) + Poll nhanh trong lớp

### Interview snapshot

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Bạn học nhóm khác — từng tự bán áo quần unisex trên Shopee 1 năm |
| Câu nói đáng nhớ nhất (nguyên văn) | "Bán online sợ nhất là đọng vốn, nhìn tổng tưởng có lãi nhưng đến cuối vụ mới thấy tồn cả đống size XL màu kén khách, tiền nằm chết ở đó." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đợt hè vừa rồi nhập 100 áo polo, màu đen/trắng size chuẩn cháy hàng sau 1 tuần; màu tím/vàng size to tồn 40 cái, phải xả lỗ 50% để thu hồi vốn. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng Google Sheets trừ tồn thủ công mỗi ngày, cuối tuần tự ngồi cộng nhẩm số đã bán để tính xem có nên nhập tiếp không. |
| Mất bao lâu, bao lần? | 45–60 phút mỗi tuần một lần. |
| Insight / opportunity rút ra | Không thiếu chỗ ghi tồn kho, nhưng thiếu công cụ tính tốc độ bán (run-rate) theo từng phân loại màu/size để cảnh báo sớm. |

### Tổng hợp

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn bạn học nhóm khác | 3 | 3/3 bạn đều mất 45–60 phút/tuần soi Excel/kho và từng bị đọng vốn do nhập lệch size/màu. | 1 bạn cho biết: Nếu quy mô dưới 20 đơn/tuần thì nhìn file Excel là nhớ, không cần thêm tool; đồ hot trend TikTok thay đổi theo tuần, AI không có dữ liệu cũ để đoán. |
| Poll nhanh trong lớp | 6 | 4/6 bạn đồng ý việc tính số lượng cần nhập là bước đau đầu và dễ cảm tính nhất. | 2/6 bạn cho rằng đặt công thức Min/Max sẵn trong Excel là đủ giải quyết, không cần AI. |

### Nhóm đã sửa problem thế nào sau kiểm chứng

Thu hẹp từ bài toán "dự đoán nhập hàng chung chung" thành **"tổng hợp và đối chiếu số lượng tồn kho với tốc độ bán theo từng mẫu/size để đề xuất nhập hàng"**, với 3 điều chỉnh cụ thể:

1. **Thu hẹp phạm vi:** Tập trung vào nhóm **hàng cơ bản (basic items)** có chu kỳ bán ổn định; loại bỏ việc dự đoán hàng hot trend ngắn ngày vì không có dữ liệu quá khứ.
2. **Ranh giới an toàn (Boundary):** AI không tự động gửi đơn nhập hàng; chỉ tính toán và xuất danh sách đề xuất số lượng dạng **[DRAFT]** để người dùng tự duyệt (Human-in-the-loop).
3. **Phân định công nghệ:** Quản lý kho và tính toán tốc độ bán dùng **Rule/Script**, AI hỗ trợ dự báo xu hướng nhu cầu và cảnh báo nguy cơ đọng vốn.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Square for Retail — Quản lý tồn kho và thống kê bán hàng** | https://squareup.com/help/us/en/article/7809-sell-through-report-with-square-for-retail | **Bước 2–4:** Theo dõi số lượng tồn kho, tốc độ bán và đối chiếu hàng còn lại với số lượng đã bán. | Có báo cáo tốc độ bán, tỷ lệ hàng bán được và tồn kho; hỗ trợ theo dõi các biến thể sản phẩm, giúp nhận biết hàng bán nhanh hoặc bán chậm. | Một số báo cáo yêu cầu gói trả phí. Phụ thuộc vào dữ liệu bán hàng được cập nhật chính xác. Khả năng áp dụng cho cửa hàng tại Việt Nam cần kiểm tra thêm. | Cần xây dựng dữ liệu tồn kho và lịch sử bán hàng rõ ràng theo từng mẫu, màu sắc, kích cỡ trước khi nghĩ đến dự báo bằng AI. |
| **Zoho Inventory — Cảnh báo hàng tồn kho thấp (Rule-based)** | https://www.zoho.com/us/inventory/kb/items/item-reorder-notification.html | **Bước 2, 4 và 5:** Theo dõi tồn kho, phát hiện sản phẩm sắp hết và hỗ trợ xác định mặt hàng cần nhập thêm. | Cho phép thiết lập ngưỡng tồn kho tối thiểu và gửi thông báo khi số lượng hàng xuống thấp. Giúp giảm việc phải kiểm tra thủ công thường xuyên. | Ngưỡng cảnh báo cần được thiết lập phù hợp. Nếu nhu cầu bán thay đổi theo mùa hoặc xu hướng thời trang, ngưỡng cố định có thể dẫn đến nhập thiếu hoặc thừa hàng. | Nên ưu tiên các quy tắc đơn giản như cảnh báo tồn kho thấp trước. Không phải chức năng nào cũng cần sử dụng AI. |
| **Inventory Planner — Dự báo nhu cầu và đề xuất nhập hàng** | https://help.inventory-planner.com/en/articles/589017-replenishment | **Bước 3–6:** Phân tích lịch sử bán hàng, dự báo nhu cầu, đối chiếu tồn kho và đề xuất số lượng cần nhập. | Có thể dự báo theo xu hướng bán hàng, yếu tố mùa vụ và thông tin tồn kho. Đề xuất số lượng nhập cho từng biến thể sản phẩm, có tính đến thời gian giao hàng từ nhà cung cấp. | Cần dữ liệu bán hàng và tồn kho đủ chính xác. Dự báo có thể kém tin cậy đối với mẫu quần áo mới, ít dữ liệu hoặc xu hướng thay đổi đột ngột. Việc cấu hình có thể phức tạp với cửa hàng nhỏ. | Nếu muốn ứng dụng AI/ML, nhóm cần kiểm tra chất lượng dữ liệu lịch sử trước. Nên xây dựng hệ thống quản lý kho cơ bản rồi mới thử nghiệm chức năng dự báo nhu cầu. |

**Nhận xét sau khi nghiên cứu:**

Đối với cửa hàng quần áo, khó khăn đáng quan tâm là số lượng biến thể sản phẩm theo mẫu, màu sắc và kích cỡ. Vì vậy, nhóm nên ưu tiên xây dựng dữ liệu tồn kho chính xác, dễ tra cứu và có khả năng đối chiếu với lịch sử bán hàng.

Sau khi có đủ dữ liệu, nhóm có thể xem xét sử dụng Machine Learning để dự báo nhu cầu và đề xuất số lượng nhập hàng. Tuy nhiên, cần so sánh hiệu quả với phương pháp dựa trên quy tắc trước khi quyết định triển khai AI.


## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
       BẮT ĐẦU
           |
           v
  +-------------------------+
  | 1. Mở dữ liệu tồn kho   |
  |       (5 phút)          |
  +-------------------------+
           |
           v
  +-------------------------+
  | 2. Tổng hợp số bán      |
  |    trong 7 ngày (10')   |
  +-------------------------+
           |
           v
  +-------------------------+
  | 3. Đối chiếu tồn vs bán |
  |    Tính số lượng cần    |
  |    nhập (25 phút)       |
  +-------------------------+
           |
           v
  +-------------------------+
  | 4. Lập danh sách đặt    |
  |    hàng nháp (10 phút)  |
  +-------------------------+
           |
           v
  +-------------------------+
  | 5. Gửi xưởng qua Zalo   |
  |    và chốt đơn (5 phút) |
  +-------------------------+
           |
           v
        HOÀN TẤT

  TỔNG: 55 PHÚT/TUẦN
  THỦ CÔNG: 5/5 BƯỚC

  !!! BOTTLENECK !!!
  Bước 3: Đối chiếu tồn kho
  với số bán, tính toán thủ công.
  Dễ nhầm lẫn giữa size/màu.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Chủ shop / Nhân viên kho | Phần mềm POS (KiotViet/Sapo) hoặc file Google Sheets | Bảng số lượng tồn kho chi tiết theo từng mã SKU (mẫu, màu, size) | 5 phút / 1 lần mỗi tuần | Dữ liệu tồn kho tĩnh, chưa trừ hàng lỗi/đổi trả chưa kịp xử lý |
| 2 | Chủ shop | Báo cáo đơn hàng sàn TMĐT (Shopee/TikTok) hoặc POS | Số lượng đã bán ra trong 7 ngày gần nhất theo từng SKU | 10 phút / 1 lần mỗi tuần | Phải lọc tay từng mẫu để xem màu nào, size nào đang chạy |
| 3 | Chủ shop | Bảng tồn kho (Bước 1) + Báo cáo bán hàng (Bước 2) + Trí nhớ/kinh nghiệm | Số lượng dự kiến cần nhập thêm cho từng biến thể màu/size | **25 phút / 1 lần mỗi tuần** | **BOTTLENECK CHÍNH:** Tính toán nhẩm tỷ lệ bán/tồn, rất dễ phán đoán theo cảm tính |
| 4 | Chủ shop | Số lượng dự kiến nhập (Bước 3) + Báo giá sỉ từ nhà cung cấp | File Excel / bảng ghi chú đơn đặt hàng (PO) kèm tổng tiền vốn | 10 phút / 1 lần mỗi tuần | Cân đối lại số lượng nhập với hạn mức tiền mặt hiện có của shop |
| 5 | Chủ shop | Bảng đơn đặt hàng nháp (Bước 4) | Tin nhắn xác nhận đơn hàng và ngày giao từ nhà cung cấp | 5 phút / 1 lần mỗi tuần | Chuyển giao (Handoff) cho xưởng may / đại lý bỏ sỉ qua Zalo |

**Bottleneck chính:**
* **Vị trí nghẽn:** Bước 3 — Đối chiếu tồn kho với tốc độ bán và tính toán số lượng nhập thêm (**25/55 phút, chiếm 45% tổng thời gian**).
* **Bản chất nghẽn:** Quá tải nhận thức (Cognitive Overload). Một shop thời trang có nhiều mã hàng, mỗi mã chia nhỏ thành nhiều biến thể màu sắc và kích cỡ (S, M, L, XL). Chủ shop phải tự tính nhẩm tỷ lệ tiêu thụ (tồn kho / số bán mỗi ngày) cho từng SKU riêng biệt mà không có công cụ hỗ trợ tính toán động.
* **Hậu quả thực tế (từ phỏng vấn Mục 3.2):** Phán đoán dựa trên cảm tính hoặc trí nhớ dẫn đến lệch pha cung cầu: cháy hàng size chuẩn (M, L màu basic) chỉ sau 1 tuần, trong khi bị đọng vốn khoảng 40% ở các size to hoặc màu kén khách (XL màu tím/vàng), cuối vụ buộc phải xả lỗ 50% để thu hồi vốn lưu động.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — 5 bước, khoảng 16 phút/tuần, 2/5 bước thủ công

[1. Tự động xuất tồn kho & tính run-rate 7 ngày: 2']  ← RULE (Script / tích hợp POS)
→ [2. Đánh giá nguy cơ & tạo đề xuất nhập nháp: 1']     ← AI (Dự báo nhu cầu & giải thích)
→ [3. Chủ shop kiểm tra & duyệt bản nháp [DRAFT]: 10']  ← CON NGƯỜI (Kiểm soát chất lượng - HITL)
→ [4. Tự động sinh phiếu đặt hàng PO: 1']               ← RULE (Format & tính tổng tiền)
→ [5. Chủ shop gửi đơn qua Zalo và chốt với xưởng: 2']  ← CON NGƯỜI (Handoff)

BOUNDARY:
- AI KHÔNG tự ý gửi đơn đặt hàng hoặc thực hiện thanh toán cho nhà cung cấp.
- AI KHÔNG tự ý thay đổi số liệu tồn kho thật trong hệ thống POS.
- Toàn bộ kết quả AI sinh ra bắt buộc ở trạng thái [DRAFT - BẢN NHÁP] và cần con người duyệt trước khi chuyển bước tiếp theo.
- AI chỉ phân tích trên nhóm hàng cơ bản (basic items) có lịch sử tiêu thụ ổn định; không dự đoán hàng hot trend ngắn ngày.

PHƯƠNG ÁN QUAY VỀ (FALLBACK):
- Khi AI gặp sự cố (lỗi mạng, hallucinate ra số lượng bất thường): Hệ thống tự động chuyển về chế độ Rule-based thuần túy (áp dụng ngưỡng Min/Max tĩnh theo công thức: Tồn an toàn = Tốc độ bán 7 ngày x Thời gian xưởng giao 5 ngày).
- Nếu bản nháp do AI đề xuất không thỏa đáng: Chủ shop bấm "Bỏ nháp AI", giao diện giữ nguyên số liệu tồn và số bán của Bước 1 để chủ shop tự nhập tay số lượng mong muốn mà không làm gián đoạn việc đặt hàng.
```

| Bước | Tên bước | Phân loại | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|---|---|
| 1 | Đồng bộ số liệu & tính run-rate | **RULE** | Script / Hệ thống | Dữ liệu tồn kho POS + Lịch sử đơn hàng 7 ngày | Bảng run-rate chuẩn hóa: Tồn kho, tốc độ bán/ngày, số ngày còn hàng | 2 phút / 1 lần mỗi tuần | Tự động hóa bằng công thức/script, không cần AI |
| 2 | Dự báo nguy cơ & tạo đề xuất nhập nháp | **AI** | Hệ thống AI | Bảng run-rate (Bước 1) + Lead time xưởng (3–5 ngày) | Bảng đề xuất số lượng nhập nháp **[DRAFT]** kèm lý do giải thích | 1 phút / 1 lần mỗi tuần | AI phân tích biến động, cảnh báo SKU sắp cháy hàng và gợi ý số lượng tối ưu |
| 3 | Kiểm tra, đối chiếu ngân sách & duyệt đơn | **CON NGƯỜI** | Chủ shop | Bản đề xuất [DRAFT] (Bước 2) + Ngân sách vốn thực tế | Danh sách số lượng chốt nhập cuối cùng | **10 phút / 1 lần mỗi tuần** | **Bước chốt chặn (HITL):** Chủ shop có toàn quyền sửa số lượng dựa trên tiền mặt hiện có |
| 4 | Sinh phiếu PO & chuẩn hóa tin nhắn | **RULE** | Script / Hệ thống | Danh sách chốt nhập (Bước 3) + Bảng giá sỉ xưởng | File PO (Excel/PDF) và nội dung tin nhắn đặt hàng chuẩn | 1 phút / 1 lần mỗi tuần | Tự động nhân đơn giá, tính tổng tiền vốn và format sẵn tin nhắn |
| 5 | Gửi đơn cho xưởng & xác nhận lịch giao | **CON NGƯỜI** | Chủ shop | Tin nhắn & File PO chuẩn (Bước 4) | Tin nhắn Zalo xác nhận đơn và hẹn ngày giao từ xưởng | 2 phút / 1 lần mỗi tuần | Con người trực tiếp giao dịch và giữ mối quan hệ với xưởng/nhà cung cấp |

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 bước | 5 bước | Giữ nguyên luồng 5 bước cốt lõi nhưng tự động hóa các khâu nặng tính toán |
| Tổng thời gian | 55 phút | **khoảng 16 phút** | Tiết kiệm ~70% thời gian (~39 phút/lần lập danh sách nhập hàng) |
| Số bước thủ công | 5/5 bước (100%) | **2/5 bước (40%)** | Chỉ còn bước Chủ shop duyệt bản nháp (Bước 3) và gửi chốt với xưởng (Bước 5) |
| Bottleneck chính | Tính nhẩm tỷ lệ tồn/bán và ước lượng số nhập (25') | Chủ shop kiểm tra bản nháp và cân đối ngân sách tiền mặt (10') | Bottleneck mới ngắn hơn và có kiểm soát vì đóng vai trò chốt chặn chất lượng |
| Rủi ro mới phát sinh | Đọng vốn do nhập lệch size/màu theo cảm tính | AI bịa số lượng bất thường (hallucination) hoặc mô hình dự báo sai lệch | Kiểm soát bằng: (1) Ranh giới [DRAFT] bắt buộc người duyệt, (2) Fallback về Rule Min/Max |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Chủ cửa hàng thời trang bán lẻ / người bán hàng thời trang online quy mô nhỏ và vừa (quản lý từ 30–50 mã sản phẩm trở lên, nhiều biến thể màu sắc và kích cỡ). |
| **Quy trình** | Mỗi tuần một lần: Mở dữ liệu tồn kho trên POS/Sheets → Tổng hợp số lượng đã bán 7 ngày gần nhất → Đối chiếu tồn kho với tốc độ bán để tính số lượng cần nhập thêm → Soạn danh sách đặt hàng nháp và cân đối ngân sách → Gửi đơn cho xưởng/nhà cung cấp qua Zalo. |
| **Bottleneck** | Bước đối chiếu tồn kho với tốc độ bán của từng biến thể màu/size và tính nhẩm số lượng cần nhập thêm (chiếm 25/55 phút) do phải tính toán thủ công tỷ lệ tiêu thụ cho hàng chục SKU và dễ bị chi phối bởi phán đoán cảm tính. |
| **Impact** | Tiêu tốn trung bình ~55 phút mỗi tuần/lần lập danh sách nhập hàng (khoảng 45–60 phút theo phỏng vấn 3 người bán, Mục 3.2); cơ cấu tồn kho bị lệch nghiêm trọng: cháy hàng size phổ thông (M, L màu cơ bản) chỉ sau 1 tuần làm mất cơ hội doanh thu, trong khi bị đọng vốn khoảng 40% ở các size to hoặc màu kén khách — dữ liệu từ 1 case cụ thể: nhập 100 áo polo, size XL màu tím/vàng tồn 40 cái, cuối vụ phải xả lỗ 50% để thu hồi vốn (Mục 3.2, Interview Snapshot). Con số 40% cần được kiểm chứng thêm trên nhiều shop trước khi khái quát hóa. |
| **Success Metric** (baseline → target, cách đo) | - **Baseline:** Trung bình ~55 phút/tuần — tính từ tổng 5 bước quy trình hiện tại (Mục 4.1), phù hợp với khoảng 45–60 phút/tuần ghi nhận qua phỏng vấn 3 người bán (Mục 3.2). Tỷ lệ đọng vốn do lệch size/màu ước tính ~40% (dữ liệu từ 1 case, cần kiểm chứng thêm).<br>- **Target:** Giảm tổng thời gian lập danh sách nhập hàng xuống **dưới 20 phút/tuần**; giảm tỷ lệ tồn đọng các mã hàng kén khách sau 30 ngày xuống **dưới 15%**. Lý do chọn ngưỡng 15%: nếu hệ thống loại bỏ được yếu tố phán đoán cảm tính ở Bước 3 (chiếm 45% tổng thời gian và là nguồn gốc chính gây lệch cung–cầu), nhóm ước tính tỷ lệ đọng vốn có thể giảm khoảng 60% so với baseline (~40% → ~15%). Ngưỡng này cũng tương đương mức tồn đọng chấp nhận được của shop nhỏ khi một số biến thể ít khách là không tránh khỏi.<br>- **Cách đo:** Chủ shop tự bấm giờ ghi nhận thời gian lập đơn hàng mỗi tuần trong 4 tuần thử nghiệm; kiểm kê định kỳ đối chiếu tỷ lệ hàng tồn khó bán sau 30 ngày. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - **AI KHÔNG được làm:** Không tự ý gửi đơn đặt hàng hoặc tự thực hiện thanh toán cho nhà cung cấp; không tự ý sửa đổi số liệu tồn kho thực tế trong POS; không tự động quyết định nhập các mặt hàng hot trend chưa có lịch sử dữ liệu.<br>- **Khi nào cần con người kiểm tra (HITL):** Bắt buộc con người kiểm tra ở Bước 3. Toàn bộ đề xuất số lượng của hệ thống chỉ ở trạng thái `[DRAFT]`; chủ shop trực tiếp rà soát số lượng, kiểm tra các cảnh báo cháy hàng, và cân đối với hạn mức ngân sách tiền mặt thực tế trước khi bấm duyệt. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

1. **Phản biện về Metric:** *"Success Metric ban đầu chỉ đo tốc độ (từ 55' xuống dưới 20'), nếu hệ thống làm rất nhanh nhưng đề xuất số lượng nhập sai khiến đọng vốn nhiều hơn thì sao?"*  
   → **Nhóm đồng ý:** Đã bổ sung thêm metric đo lường chất lượng: *"giảm tỷ lệ tồn đọng các mã hàng kén khách sau 30 ngày xuống dưới 15%"*.
2. **Phản biện về Rủi ro dữ liệu:** *"Nếu chỉ dựa vào số bán 7 ngày gần nhất thì vào các đợt chạy quảng cáo hoặc Flash Sale (doanh số tăng ảo ngắn hạn), hệ thống sẽ đề xuất nhập quá đà gây ngập kho."*  
   → **Nhóm đồng ý:** Ghi nhận rủi ro này để xử lý tại Problem Statement v1 (Mục 7) bằng cách bổ sung tiêu chí loại trừ ngày có biến động khuyến mãi bất thường hoặc gắn tag "chiến dịch sale" vào thuật toán tính toán.
3. **Phản biện về Giới hạn tự động:** *"Tại sao không để AI tự động gửi tin nhắn đặt hàng sang Zalo cho xưởng luôn để tiết kiệm thêm 2 phút?"*  
   → **Nhóm không đồng ý:** Giữ nguyên boundary vì việc gửi đơn đặt hàng đi kèm nghĩa vụ thanh toán tài chính thật và mối quan hệ với đối tác xưởng may. Đây là ranh giới bắt buộc phải do chủ shop trực tiếp kiểm soát.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô:** Độ mơ hồ cao × Độ phức tạp cao.

**Vì sao:**

Bài toán quản lý tồn kho và đề xuất nhập hàng cho cửa hàng thời trang có độ mơ hồ cao vì nhu cầu mua hàng không cố định. Cùng một mẫu quần áo có thể bán nhanh hoặc chậm tùy màu sắc, kích cỡ, mùa vụ và chương trình khuyến mãi. Không phải lúc nào cũng có một số lượng nhập hàng tối ưu duy nhất, vì quyết định cuối cùng còn phụ thuộc vào ngân sách và kinh nghiệm của chủ shop.

Độ phức tạp cao vì quy trình sử dụng nhiều nguồn dữ liệu như POS, Google Sheets, lịch sử bán hàng và thông tin nhà cung cấp. Hệ thống cần đối chiếu số lượng tồn kho theo từng SKU, tính tốc độ bán, xem xét thời gian giao hàng và đề xuất số lượng nhập phù hợp.

Tuy nhiên, quy trình xử lý gồm các bước tương đối cố định. Vì vậy, nhóm đề xuất sử dụng **Workflow** kết hợp Rule và AI, thay vì Agent tự quyết định toàn bộ quá trình.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Chuẩn hóa dữ liệu tồn kho trong Excel/Google Sheets, sử dụng bảng theo dõi và checklist nhập hàng. Chủ shop tự tính toán và quyết định số lượng nhập. | Phù hợp với shop nhỏ, số lượng SKU ít và nhu cầu bán hàng tương đối ổn định. | Vẫn mất thời gian đối chiếu thủ công, dễ sai khi có nhiều biến thể màu sắc và kích cỡ. | Không chọn làm phương án chính. |
| **Rule** | Sử dụng công thức tính tốc độ bán, số ngày còn hàng và ngưỡng Min/Max để cảnh báo tồn kho thấp, đồng thời gợi ý số lượng cần nhập. | Đủ khi dữ liệu chính xác, tốc độ bán ổn định và các quy tắc nhập hàng có thể xác định trước. | Ngưỡng cố định có thể không phản ánh tốt biến động theo mùa hoặc chương trình khuyến mãi. Tuy nhiên, Rule có thể giải quyết phần lớn nhu cầu của shop nhỏ. | Chọn làm nền tảng và phương án dự phòng. |
| **Workflow** | Rule đồng bộ tồn kho và tính run-rate, AI hỗ trợ dự báo nhu cầu và tạo đề xuất nhập hàng [DRAFT], chủ shop kiểm tra ngân sách và phê duyệt, Rule tạo phiếu PO, chủ shop gửi đơn cho nhà cung cấp. | Phù hợp khi có đủ dữ liệu lịch sử để đánh giá dự báo, quy trình cố định và cần con người kiểm soát quyết định nhập hàng. | AI có thể dự báo sai, đề xuất nhập quá nhiều hoặc bỏ sót SKU sắp hết hàng. Cần kiểm thử với dữ liệu thực tế và yêu cầu chủ shop duyệt. | **Đề xuất chọn để kiểm chứng.** |
| **Agent** | AI tự lựa chọn cách phân tích, truy vấn nhiều nguồn, quyết định các bước tiếp theo và có thể chuẩn bị quy trình đặt hàng theo tình huống. | Chỉ cần thiết khi quy trình có nhiều tình huống không thể định nghĩa trước và AI phải tự quyết định bước tiếp theo. | Khó kiểm soát, tăng chi phí, có nguy cơ đưa ra quyết định nhập hàng không phù hợp hoặc thao tác vượt quyền. | Không chọn. |

**Mức chọn:** Workflow kết hợp Rule + AI + Human-in-the-loop (HITL).

**Vì sao không chọn mức đơn giản hơn:**

No AI vẫn yêu cầu chủ shop đối chiếu và tính toán thủ công, trong khi bước này đang chiếm 25/55 phút trong quy trình hiện tại.

Rule có thể giải quyết việc tổng hợp dữ liệu, tính tốc độ bán và cảnh báo tồn kho thấp. Đây là phương án cần triển khai và kiểm chứng trước vì chi phí thấp, dễ giải thích và có thể xử lý phần lớn công việc.

Tuy nhiên, Rule với ngưỡng cố định có thể gặp hạn chế khi nhu cầu bán thay đổi theo mùa, màu sắc, kích cỡ hoặc chương trình khuyến mãi. Workflow cho phép bổ sung một bước AI để thử dự báo nhu cầu trên nhóm hàng cơ bản có lịch sử bán ổn định.

Nhóm chỉ nên giữ bước AI nếu kết quả kiểm thử chứng minh nó cải thiện chất lượng đề xuất nhập hàng so với Rule. Nếu AI không tạo ra lợi ích rõ ràng hoặc dữ liệu chưa đủ tốt, nhóm sẽ sử dụng Rule-based.

**Vì sao không chọn Agent:**

Quy trình nhập hàng đã có các bước xác định trước và không yêu cầu AI tự lựa chọn toàn bộ hành động. Ngoài ra, quyết định nhập hàng liên quan trực tiếp đến ngân sách và vốn kinh doanh. Vì vậy, Agent làm tăng rủi ro và độ phức tạp không cần thiết.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | AI hỗ trợ dự báo nhu cầu bán hàng theo từng SKU (mẫu, màu, size), xác định SKU có nguy cơ hết hàng hoặc tồn kho lâu và tạo bảng đề xuất số lượng nhập thêm ở trạng thái [DRAFT], kèm lý do. |
| **Judgment** — con người cân nhắc, quyết định gì? | Chủ shop xem xét số lượng tồn thực tế, tốc độ bán, ngân sách, xu hướng thị trường, chương trình khuyến mãi và khả năng giao hàng của nhà cung cấp. Chủ shop quyết định giữ, sửa hoặc từ chối đề xuất của AI. |
| **Action** — hành động cuối cùng là gì, ai làm? | Sau khi chủ shop phê duyệt số lượng, hệ thống Rule tạo phiếu đặt hàng PO và tính tổng chi phí. Chủ shop kiểm tra lần cuối, gửi đơn qua Zalo và xác nhận với nhà cung cấp. AI không tự gửi đơn hoặc thanh toán. |
| **Outcome** — đo kết quả bằng gì? | Thời gian lập danh sách nhập hàng giảm từ baseline 55 phút xuống dưới 20 phút/tuần. Theo dõi thêm tỷ lệ SKU tồn đọng sau 30 ngày, tỷ lệ thiếu hàng và mức sai lệch giữa số lượng đề xuất với nhu cầu thực tế. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Dữ liệu tồn kho theo SKU, lịch sử bán hàng, số lượng đổi trả, giá nhập, thời gian giao hàng, thông tin khuyến mãi và ngân sách nhập hàng. Báo cáo nhóm đã xác định POS/Sheets và lịch sử bán hàng là các nguồn dự kiến. Cần kiểm tra khả năng xuất dữ liệu và độ đầy đủ của lịch sử trước khi dùng ML. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Lưu bản đề xuất [DRAFT], số lượng chủ shop chỉnh sửa, số lượng thực tế đã nhập, doanh số sau nhập, số SKU hết hàng và hàng tồn sau 30 ngày. Dùng dữ liệu này để đánh giá sai lệch và cải thiện quy tắc hoặc mô hình dự báo. |

### 6.4. Hai câu hỏi của Google PAIR

**1. Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**

Nhóm đề xuất hướng **Augment (hỗ trợ con người)**, không tự động hóa hoàn toàn quyết định nhập hàng.

Theo nội dung kiểm chứng ở Mục 3.2, người bán gặp khó khăn khi phải đối chiếu số lượng tồn kho và tốc độ bán theo từng màu, size. Đồng thời, một số người được hỏi cho rằng công thức Min/Max trong Excel đã đủ và không cần AI.

Vì vậy, hệ thống nên tự động hóa các bước tính toán có quy tắc rõ ràng, đồng thời hỗ trợ tạo bản đề xuất nhập hàng để chủ shop xem xét.

Chủ shop vẫn phải có quyền điều chỉnh số lượng, cân đối ngân sách và quyết định gửi đơn. Mức độ sẵn sàng sử dụng đề xuất AI cần được kiểm chứng thêm bằng hành vi thực tế.

**2. AI sai kiểu nào tệ hơn: báo nhầm hay bỏ sót? Vì sao, và thiết kế xử lý thế nào?**

Cả hai loại lỗi đều ảnh hưởng đến kinh doanh:

**Báo nhầm (False Positive):** AI dự báo nhu cầu cao hơn thực tế và đề xuất nhập quá nhiều. Hậu quả là tăng tồn kho, đọng vốn và có thể phải giảm giá để thanh lý hàng.

**Bỏ sót (False Negative):** AI không nhận diện SKU có nguy cơ hết hàng. Hậu quả là shop thiếu hàng, mất doanh thu và có thể mất khách hàng.

Trong phạm vi bài toán của nhóm, cần đặc biệt kiểm soát lỗi báo nhầm dẫn đến nhập dư hàng, vì kết quả phỏng vấn ở Mục 3.2 đã ghi nhận trường hợp tồn nhiều sản phẩm khó bán và phải giảm giá để thu hồi vốn.

Tuy nhiên, nhóm vẫn phải theo dõi cả tỷ lệ thiếu hàng để tránh tình trạng giảm tồn kho nhưng làm mất doanh thu.

**Thiết kế kiểm soát:**

1. Mọi đề xuất AI đều ở trạng thái [DRAFT] và bắt buộc chủ shop phê duyệt.
2. Hệ thống hiển thị số lượng tồn, tốc độ bán, thời gian giao hàng và lý do đề xuất để người dùng đối chiếu.
3. Các đề xuất số lượng bất thường hoặc vượt ngân sách phải được cảnh báo để kiểm tra lại.
4. Không sử dụng dự báo AI cho các mặt hàng hot trend có lịch sử bán không đủ hoặc biến động quá mạnh.
5. Khi AI không đáng tin cậy hoặc gặp sự cố, hệ thống chuyển về phương án Rule-based; chủ shop có thể chỉnh sửa số lượng thủ công.
6. Theo dõi tỷ lệ nhập dư, thiếu hàng và sai lệch dự báo trong thời gian thử nghiệm để quyết định có tiếp tục sử dụng AI hay không.
7. 
---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Chủ cửa hàng thời trang bán lẻ hoặc kinh doanh quần áo online quy mô nhỏ và vừa, quản lý từ 30–50 mã sản phẩm trở lên với nhiều màu sắc và kích cỡ. Tập trung vào các mặt hàng cơ bản có lịch sử bán tương đối ổn định. |
| **Quy trình** | Mỗi tuần, chủ shop kiểm tra tồn kho theo từng SKU (mẫu, màu, size), tổng hợp số bán trong 7 ngày, đối chiếu tốc độ tiêu thụ, xác định số lượng cần nhập và gửi đơn cho nhà cung cấp. Quy trình hiện tại gồm 5 bước thủ công, mất khoảng 55 phút. Quy trình tương lai: Rule tổng hợp dữ liệu → AI đề xuất nhập hàng → chủ shop kiểm tra, phê duyệt → Rule tạo phiếu đặt hàng → chủ shop gửi đơn. |
| **Bottleneck** | Bước 3 — đối chiếu tồn kho với tốc độ bán và tính số lượng cần nhập theo từng SKU, mất **25/55 phút (khoảng 45%)**. Chủ shop phải xử lý nhiều biến thể màu sắc, kích cỡ bằng phương pháp thủ công và kinh nghiệm nên dễ tính toán sai. |
| **Impact** | Việc kiểm tra thủ công gây mất thời gian, dễ dẫn đến nhập thiếu hàng bán chạy hoặc nhập thừa hàng bán chậm, làm mất doanh thu và đọng vốn. Một trường hợp được phỏng vấn ghi nhận nhập 100 áo polo nhưng còn tồn 40 chiếc thuộc các màu và size khó bán, phải giảm giá 50% để thu hồi vốn. Đây là trường hợp cụ thể, chưa đại diện cho mọi cửa hàng. |
| **Success Metric (baseline → target, cách đo)** | **1. Thời gian:** 55 phút/tuần → mục tiêu dưới 20 phút/tuần; quy trình mới kỳ vọng khoảng 16 phút. Đo bằng cách bấm giờ trong 4 tuần thử nghiệm. **2. Tồn kho:** Mục tiêu tỷ lệ hàng khó bán dưới 15% sau 30 ngày, đo bằng kiểm kê và đối chiếu số lượng tồn theo cùng nhóm sản phẩm. Baseline chung cần đo thêm vì số liệu 40/100 áo chỉ thuộc một trường hợp. **3. Thiếu hàng:** Theo dõi số SKU hết hàng khi vẫn có nhu cầu. **4. An toàn:** 100% đơn nhập phải được chủ shop phê duyệt trước khi gửi. |
| **Boundary** | AI chỉ phân tích dữ liệu và đưa ra bản đề xuất nhập hàng, không được tự gửi đơn qua Zalo, thanh toán hoặc chỉnh sửa dữ liệu tồn kho thực tế. Chủ shop có quyền kiểm tra, sửa hoặc từ chối đề xuất. Không dùng AI dự báo hàng hot trend thiếu dữ liệu. Khi AI gặp lỗi hoặc dự báo bất thường, hệ thống cảnh báo và chuyển về Rule-based (Min/Max) hoặc thao tác thủ công. |
| **AI intervention point** | AI tham gia ở **Bước 2 của quy trình tương lai**, sau khi Rule/Script đã tổng hợp tồn kho, doanh số và tốc độ bán. AI đánh giá nguy cơ thiếu hàng, tồn kho lâu và đề xuất số lượng nhập. Dữ liệu từ Flash Sale hoặc khuyến mãi bất thường cần được nhận diện, xử lý riêng để tránh dự báo nhu cầu quá cao. Các đề xuất phải có lý do để chủ shop đối chiếu. |
| **Mức chọn** | **Workflow (Rule + AI + Human-in-the-loop).** Rule/Script tổng hợp dữ liệu, tính tốc độ bán và tạo phiếu đặt hàng; AI hỗ trợ dự báo nhu cầu; chủ shop kiểm tra và phê duyệt. Không chọn Agent vì quy trình có các bước cố định và liên quan đến quyết định tài chính. Chỉ duy trì AI nếu kiểm thử chứng minh hiệu quả tốt hơn Rule-based. |
| **Rủi ro & người kiểm tra** | **Rủi ro:** Dữ liệu tồn kho sai, thiếu lịch sử bán, doanh số tăng bất thường do khuyến mãi, AI đề xuất nhập dư hoặc bỏ sót hàng sắp hết. **Người kiểm tra:** Nhân viên kho kiểm tra dữ liệu; chủ shop đối chiếu đề xuất với ngân sách và quyết định số lượng nhập. Nếu AI không đáng tin cậy, chuyển về Rule-based hoặc quyết định thủ công. |

### Thay đổi so với v0 và lý do

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| **Actor / Phạm vi** | Chủ cửa hàng thời trang nhỏ và vừa có nhiều mã sản phẩm. | Tập trung vào các mặt hàng cơ bản có lịch sử bán ổn định, không dự báo hàng hot trend thiếu dữ liệu. | Nhu cầu hàng thời trang biến động nhanh, sản phẩm mới có thể không đủ dữ liệu lịch sử để dự báo chính xác. |
| **Quy trình / AI intervention** | Chủ shop đối chiếu tồn kho, tính số lượng nhập bằng phương pháp thủ công. | Rule tổng hợp dữ liệu → AI đề xuất → chủ shop phê duyệt → Rule tạo phiếu đặt hàng → chủ shop gửi đơn. | Research cho thấy phần quản lý tồn kho có thể dùng Rule; AI chỉ nên hỗ trợ dự báo khi cần. |
| **Success Metric** | Thời gian dưới 20 phút/tuần; tỷ lệ hàng khó bán dưới 15% sau 30 ngày. | Giữ mục tiêu cũ, bổ sung kỳ vọng 16 phút/tuần, theo dõi thiếu hàng và yêu cầu 100% đơn được phê duyệt. | Cần đánh giá cả tốc độ, chất lượng và an toàn thay vì chỉ đo thời gian xử lý. |
| **Dữ liệu đầu vào** | Chủ yếu dựa vào tồn kho và lịch sử bán trong 7 ngày. | Bổ sung nhận diện và xử lý riêng dữ liệu Flash Sale, khuyến mãi hoặc quảng cáo bất thường. | Doanh số tăng đột biến có thể khiến AI dự báo quá cao, gây nhập thừa hàng. |
| **Rủi ro & kiểm soát** | Nhận diện rủi ro nhập thiếu, nhập thừa và tính toán theo cảm tính. | Bổ sung rủi ro dữ liệu thiếu/sai, khuyến mãi bất thường; phân rõ trách nhiệm kiểm tra của nhân viên kho và chủ shop. | Cần xác định người chịu trách nhiệm và cách xử lý khi dự báo không chính xác. |

### Tiêu chí đánh giá đầu ra của AI

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | **Tính chính xác của dữ liệu** | Mã SKU, màu sắc, kích cỡ, số lượng tồn, số bán và tốc độ bán khớp dữ liệu nguồn đã xác minh. | Nhầm sản phẩm, màu/size, tính sai hoặc tạo số liệu không có trong nguồn. |
| 2 | **Chất lượng đề xuất nhập hàng** | Đề xuất dựa trên tồn kho, tốc độ bán và thời gian giao hàng; nhận diện được hàng sắp hết hoặc tồn lâu. Kết quả thử nghiệm được so sánh với Rule-based và nhu cầu thực tế. | Thường xuyên đề xuất nhập dư hàng bán chậm, bỏ sót hàng sắp hết hoặc cho kết quả kém Rule-based mà không có lý do. |
| 3 | **Xử lý dữ liệu bất thường** | Phát hiện hoặc sử dụng được nhãn khuyến mãi, cảnh báo khi doanh số biến động mạnh hoặc thiếu lịch sử bán. | Coi doanh số Flash Sale là nhu cầu thường xuyên hoặc dự báo chắc chắn dù dữ liệu không đủ. |
| 4 | **Khả năng giải thích và kiểm tra** | Đề xuất thể hiện SKU, số lượng tồn, tốc độ bán, số lượng nhập và lý do; chủ shop có thể chỉnh sửa hoặc từ chối. | Đưa ra số lượng nhập thiếu căn cứ, không giải thích được hoặc không cho phép điều chỉnh. |

**Cách đánh giá khi thử nghiệm:**

Nhóm sử dụng dữ liệu tồn kho và bán hàng có thể đối chiếu, gồm các trường hợp hàng bán ổn định, hàng tồn lâu, hàng sắp hết, sản phẩm mới và ngày khuyến mãi bất thường.

Mỗi lần chạy, nhóm so sánh đề xuất AI với phương án Rule-based, nhận xét của chủ shop và kết quả bán thực tế. Đồng thời ghi nhận thời gian xử lý, số đề xuất phải chỉnh sửa, tình trạng thiếu hàng và tỷ lệ tồn khó bán.

Nếu AI không cải thiện kết quả so với Rule-based hoặc không đáp ứng tiêu chí an toàn, nhóm sẽ ưu tiên sử dụng Rule-based.

**Kết luận:** Nhóm lựa chọn Workflow để kiểm chứng khả năng hỗ trợ quyết định nhập hàng. AI chỉ đóng vai trò phân tích và đề xuất, còn chủ shop quyết định cuối cùng. Mục tiêu là giảm thời gian xử lý, hạn chế nhập thiếu hoặc thừa hàng và bảo đảm an toàn tài chính.

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
