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
| 1 | Đỗ Anh Thư          | Khi chuẩn bị nhập hàng mới, tôi muốn biết mặt hàng nào còn tồn kho nhiều, mặt hàng nào bán chạy và sắp hết, để quyết định nhập hàng hợp lý, tránh thiếu hàng hoặc tồn kho quá nhiều.                                                   |Chủ cửa hàng, nhân viên | phải kiểm tra nhiều mẫu quần áo, màu sắc, kích cỡ và đối chiếu số lượng bán với tồn kho. Giả thuyết: mất khoảng 30–60 phút mỗi lần kiểm tra và lên danh sách nhập hàng.                                                                        | Các phần mềm quản lý kho (POS/ERP) hiện nay đều có thể tự động đặt ngưỡng Min/Max và hiển thị cảnh báo dashboard dựa trên số liệu bán hàng. Tại sao nhóm phải dùng Machine Learning dự đoán phức tạp trong khi giải pháp phần mềm thông thường (Rule-based) đã giải quyết được 80% bài toán này?(Hoàng Quang Đạt),Mở rộng vấn đề, sử dụng AI để phân loại đồ và tính tồn kho cho từng chi nhánh thay vì chỉ một chỗ.(Nguyễn Tài Minh Huy) |
| 2 | Nguyễn Tài Minh Huy | Khi chương trình Python xuất hiện lỗi trong lúc làm assignment, mình muốn xác định chính xác nguyên nhân để sửa lỗi và tiếp tục làm bài mà không phải thử nhiều cách không hiệu quả.                                                   |Học viên học các loại ngôn ngữ lập trình. | Việc xác định nguyên nhân lỗi tốn nhiều thời gian vì cần hiểu thông báo lỗi và tìm đúng vị trí trong code. Đã có trường hợp quá trình debug kéo dài trên 30 phút.                                                                              | Không có.                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| 3 | Võ Thanh Huy        | Khi một sản phẩm có nhiều đánh giá trái chiều từ người mua trước, tôi muốn xác định những ưu điểm và nhược điểm thường gặp, để hạn chế lựa chọn sản phẩm không đáp ứng nhu cầu.                                                        |Người cần tìm hiểu chất lượng sản phẩm trước khi mua | Bước 3 — đọc nhiều đánh giá, dự kiến mất 12 phút trong tổng số 25 phút. Đây là thời gian phân bổ tạm, cần đo lại.                                                                                                                              | Làm sao để nhận dạng được comment nào hoặc đánh giá nào là đúng và cái nào là bot/spam? (Nguyễn Tài Minh Huy)                                                                                                                                                                                                                                                                                                                             |
| 4 | Hoàng Quang Đạt     | Tóm tắt mốc thời gian & việc cần làm từ file ghi âm bài giảng/buổi họp                                                                                                                                                                 |Sinh viên, Học sinh, thành viên phụ trách ghi biên bản cuộc họp | Bước 3: Mất 35 phút tua đi tua lại vì không biết đoạn nào nói về bài tập/nhiệm vụ                                                                                                                                                              | Làm sao để đoán được hoặc nắm bắt được topic của người nói? (Nguyễn Tài Minh Huy)                                                                                                                                                                                                                                                                                                                                                         |
| 5 | Đỗ Anh Thư          | Khi cần chuyển khoản hoặc thanh toán online, người thân, người lớn tuổi muốn tự thực hiện giao dịch một cách dễ hiểu và an toàn, để không phải thường xuyên nhờ con cháu hỗ trợ.                                                       |Người lớn tuổi, người thân |Bước 2–5: phải đọc nhiều nguồn, lọc thông tin quan trọng, xác định deadline và nhập lại thủ công. Giả thuyết: mất khoảng 15–30 phút/ngày để kiểm tra và tổng hợp công việc.                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 6 | Đỗ Anh Thư          | Khi tham gia các khóa học hoặc dự án có nhiều bài tập và deadline được thông báo ở nhiều nơi, tôi muốn tự động tổng hợp tất cả công việc cần làm vào một danh sách thống nhất, để không bỏ sót nhiệm vụ và chủ động sắp xếp thời gian. |Sinh viên hoặc người tham gia các chương trình đào tạo, khóa học và dự án có nhiều nhiệm vụ. | Bước 2–5: phải đọc nhiều nguồn, lọc thông tin quan trọng, xác định deadline và nhập lại thủ công. Giả thuyết: mất khoảng 15–30 phút/ngày để kiểm tra và tổng hợp công việc.                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 7 | Nguyễn Tài Minh Huy | Khi chuẩn bị nộp assignment, mình muốn đối chiếu bài làm với rubric và hướng dẫn để phát hiện những phần còn thiếu hoặc chưa chính xác trước khi nộp.                                                                                  |Học viên chương trình AI Thực chiến tại VinUni. | Việc đối chiếu từng tiêu chí với bài làm tốn thời gian vì rubric có nhiều yêu cầu và học viên phải tự tìm nội dung tương ứng trong bài. Thường mình phải hỏi đồng đội hoặc giáo viên, hoặc lab coach để kiểm tra. Việc có thể diễn ra khá lâu. |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 8 | Nguyễn Tài Minh Huy | Khi hoàn thành một buổi học có nhiều kiến thức mới, mình muốn xác định những nội dung bản thân đã hiểu và những phần còn yếu để ưu tiên cải thiện trước buổi học tiếp theo.                                                            |Học viên chương trình AI Thực chiến tại VinUni. | Khó xác định chính xác kiến thức còn yếu vì đôi khi mình cảm thấy đã hiểu lý thuyết nhưng vẫn gặp khó khăn khi áp dụng vào bài tập thực tế. Mình mất ít nhất 30 phút để hiểu được và thêm ít nhất 30 phút để áp dụng.                          |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 9 | Võ Thanh Huy        | Khi tìm vị trí thực tập, tôi muốn xác định các công việc phù hợp với kỹ năng hiện tại, để không mất thời gian đọc những tin tuyển dụng không đáp ứng điều kiện.                                                                        |Sinh viên năm cuối, sinh viên mới tốt nghiệp và người chưa có kinh nghiệm làm việc đang tìm kiếm cơ hội thực tập.  | Bước 3 và 4 — đọc yêu cầu công việc và đối chiếu với kỹ năng bản thân. Tổng thời gian tìm kiếm và đối chiếu 20 tin là 30 phút; cần đo riêng thời gian của từng bước để xác định bottleneck chính.                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 10 | Võ Thanh Huy        | Khi có nhiều bài tập và hạn nộp từ các môn hoặc hoạt động khác nhau, tôi muốn nắm được thời hạn của từng việc, để sắp xếp thời gian và tránh nộp muộn.                                                                                                                                                                                                                                       |Sinh viên tham gia nhiều môn học, khóa đào tạo hoặc hoạt động có thời hạn nộp bài khác nhau. | Bước 2 và 5 -phải kiểm tra nhiều nguồn thông báo và thường xuyên xem lại deadline.                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 11 | Hoàng Quang Đạt                    | Khi người nhà lớn tuổi gửi ảnh chụp đơn thuốc viết tay kèm chẩn đoán, tôi muốn chuyển đổi thành bảng hướng dẫn uống thuốc rõ ràng theo từng buổi sáng/trưa/tối, để bố mẹ uống thuốc đúng giờ và không uống nhầm loại                   |Con cái | Bước 2 & 3: Mất 30 phút vì chữ bác sĩ viết tắt, nguy cơ nhìn nhầm liều lượng gây nguy hiểm tính mạng                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 12 | Hoàng Quang Đạt                    | Khi khách hàng gửi tin nhắn phản ánh chất lượng bằng câu chữ bức xúc và teencode viết tắt, tôi muốn phân loại nhanh mức độ khẩn cấp và lý do phàn nàn chính, để chuyển đúng người xử lý trong vòng 15 phút                             |Nhân viên trực page chăm sóc khách hàng, nhân viên hỗ trợ kỹ thuật | Bước 2 & 3: Mất 8 phút/tin; dễ quá tải làm trôi tin nhắn bức xúc của khách hàng lớn Câu hỏi phản biện                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                           |

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
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

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
