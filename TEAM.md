# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Nhóm League
- Candidate problem nhóm chọn (1 câu): Quản lý tồn kho và hỗ trợ quyết định nhập hàng cho cửa hàng thời trang vừa và nhỏ
- Quyết định cuối (Go / Not Yet / No-Go): Go (Pilot)

## Thành viên

| STT | Họ và tên | MSSV        | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|-------------|---|------------------|
| 1 | Đỗ Anh Thư | 2A202603815 | Nhóm trưởng, Điều phối thời gian, Viết Problem Statement | DoAnhThu832004   | 
| 2 | Hoàng Quang Đạt | 2A202603808 | Phản biện chính, Kiểm chứng The Mom Test, Thiết kế Boundary & Quy trình | QDat18           |
| 3 | Nguyễn Tài Minh Huy | 2A202603828 | Research giải pháp, Phân tích dữ liệu & Đánh giá rủi ro | ArthurTheMana    |
| 4 | Võ Thanh Huy | 2A202603879 | Khảo sát nhu cầu, Xây dựng quy trình hiện tại & After | VThanh-Huy       |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính         | Người hỗ trợ                      | Sản phẩm |
|---|---------------------|-----------------------------------|---|
| CP3 — Hội tụ nhóm | Nguyễn Tài Minh Huy          | Cả nhóm                           | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Hoàng Quang Đạt     | Võ Thanh Huy                      | Assumption map, snapshot hoặc survey |
| CP4 — Research | Nguyễn Tài Minh Huy | Hoàng Quang Đạt                   | Bảng research có link |
| CP5 — Quy trình trước/sau | Đỗ Anh Thư          | Hoàng Quang Đạt                   | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Đỗ Anh Thư          | Cả nhóm                           | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Hoàng Quang Đạt     | Nguyễn Tài Minh Huy, Võ Thanh Huy | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm             | Hoàng Quang Đạt                   | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### HoangQuangDat-2A202603808

**Phần việc phụ trách:**
- Người phản biện chính (Devil's Advocate) trong toàn bộ các buổi pitch và chốt giải pháp.
- Phụ trách chính phần Kiểm chứng The Mom Test (Mục 3.2) và xây dựng Assumption Map (Mục 3.1).
- Thiết kế ranh giới an toàn (Boundary - Human-in-the-loop) và phương án Fallback cho quy trình tương lai (Mục 4.2).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Trực tiếp phỏng vấn The Mom Test một bạn học từng kinh doanh thời trang online trên Shopee; mang về insight thực tế về việc đọng vốn size to/màu kén khách và tín hiệu phản bác quan trọng về hàng hot trend.
- Xây dựng 5 giả định trong Assumption Map, chọn ra 3 giả định quan trọng nhất để kiểm chứng ngay trong buổi lab.
- Đề xuất phân tầng công nghệ rõ ràng trong quy trình tương lai: Rule/Script xử lý đồng bộ và tính toán tốc độ bán, AI chỉ nhận diện quy luật tiêu thụ và tạo bảng nháp `[DRAFT]`.
- Thiết lập ranh giới Boundary chặt chẽ (AI không tự gửi đơn đặt hàng) và kịch bản Fallback an toàn (lùi về Rule Min/Max khi mất mạng/thiếu data).
- Đóng góp vào đánh giá 4 rủi ro của Marty Cagan để đưa ra quyết định Go (Pilot) kèm ngưỡng dừng (Kill metric).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
- Mục 3.1 (Assumption Map) và Mục 3.2 (Kiểm chứng The Mom Test) trong `report/team/group_report.md`.
- Sơ đồ quy trình tương lai Mục 4.2 trong `report/team/group_report.md`.
- Các commit trên branch `HoangQuangDat`: `dc46e92 hoan thien 3.1`, `0349001 feat: cap nhat muc 3.2 kiem chung The Mom Test`, `91a7711 Merge remote-tracking branch 'origin/DoAnhThu'`.

**Điều mình học được từ phần nhóm:**
- Bài học sâu sắc nhất là: không bao giờ được "yêu giải pháp trước khi hiểu nỗi đau". AI không phải cây đũa thần có thể giải quyết mọi thứ; một bài toán tốt phải bắt đầu từ nỗi đau kinh tế thật sự có thể đo đếm được.
- Tầm quan trọng của "tín hiệu phản bác" (Disconfirming signals): lắng nghe người dùng phản bác giúp nhóm tỉnh ngộ, dũng cảm thu hẹp ranh giới vào hàng basic thay vì ảo tưởng làm AI dự báo cho toàn bộ các mẫu mốt ngắn hạn.
- Sự kết hợp giữa Rule-based và AI: giải pháp thông minh không phải là dùng AI cho 100% quy trình, mà là dùng Rule giải quyết dứt điểm 80% phần tính toán cơ bản và chỉ dùng AI ở điểm chạm nhận thức thực sự cần thiết.

### DoAnhThu-2A202603815

**Phần việc phụ trách:**
- Làm nhóm trưởng, phân chia công việc và nhắc nhở các bạn chạy tiến độ theo từng checkpoint.
- Đưa ra ý tưởng Problem Card #1 (Quản lý tồn kho và hỗ trợ nhập hàng cho shop thời trang), trình bày buổi pitch và được cả nhóm chọn làm bài chung.
- Phụ trách chính phần Quy trình trước/sau (CP5: Mục 4.1, 4.2, 4.3) và viết Problem Statement v0 (CP5: Mục 5).
- Tự vẽ sơ đồ ASCII mô tả quy trình hiện tại và quy trình mới trong báo cáo nhóm.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Đề xuất bài toán từ thực tế người nhà mình bán quần áo hay bị đau đầu vì tồn kho; chuẩn bị bài pitch và giải thích các thắc mắc của nhóm để chọn làm đề tài chính.
- Làm Mục 4.1 (Quy trình hiện tại): Vẽ sơ đồ ASCII 5 bước thủ công (mất 55 phút/tuần); lập bảng chi tiết từng bước và chỉ ra bước nghẽn nhất là Bước 3 (ngồi tính nhẩm tỷ lệ bán/tồn mất 25 phút), dẫn đến việc phán đoán theo cảm tính làm cháy hàng size M/L basic mà lại đọng vốn 40% ở các size to/màu kén khách.
- Làm Mục 4.2 & 4.3 (Quy trình tương lai & Before/After): Vẽ sơ đồ ASCII quy trình mới rút xuống còn 16 phút/tuần; chia rõ bước nào dùng Script/Rule tính tốc độ bán, bước nào AI gợi ý số lượng nháp `[DRAFT]`, và bước nào chủ shop bắt buộc phải tự duyệt; đưa ra ranh giới AI không được tự đặt hàng và có phương án dự phòng quay về công thức Min/Max khi AI bị lỗi.
- Viết Problem Statement v0 (Mục 5): Điền đủ các mục Actor, Quy trình, Bottleneck, Impact, Metric (giảm từ 55 phút xuống dưới 20 phút, giảm tồn đọng mã khó bán xuống dưới 15%); đưa số liệu thực tế từ phỏng vấn 3 shop (ca tồn 40 áo polo XL vàng/tím phải xả lỗ 50%); trả lời các câu hỏi phản biện về việc không để AI tự gửi đơn qua Zalo.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
- Mục 2.1 (Pitch candidate 1), Mục 4.1, 4.2, 4.3 (Quy trình trước/sau) và Mục 5 (Problem Statement v0) trong `report/team/group_report.md`.
- Báo cáo cá nhân `report/individual/2A202603815_DoAnhThu.md`.
- Các commit trên repo:
  - `9ec137d DoAnhThu check point 1,2`: Tạo báo cáo cá nhân và viết Problem Card #1.
  - `fc4c6e4 check point group_report 2.1`: Cập nhật bảng pitch chung của nhóm.
  - `d4a52a1 check point group_report 4.1`: Vẽ sơ đồ ASCII quy trình cũ và phân tích bottleneck Bước 3.
  - `e401219 check point group_report 4.2, 4.3 5`: Vẽ sơ đồ quy trình mới, bảng Before/After và viết Problem Statement v0.
  - `70d64bb fix check point 5`: Cập nhật số liệu thực tế vào Impact và Metric.

**Điều mình học được từ phần nhóm:**
- Bài toán hay phải từ thực tế: Thấy người nhà làm vất vả mới hiểu được nỗi đau thật, chứ không phải cứ nghĩ ra một ý tưởng nghe công nghệ rồi cố tìm cách nhét AI vào.
- Khi vẽ quy trình mới thấy rõ vấn đề: Lúc chưa chia bước thì tưởng việc nào cũng cần AI, nhưng vẽ chi tiết ra mới thấy khâu đồng bộ số liệu hay xuất phiếu đặt hàng chỉ cần viết script thường là xong, AI chỉ cần hỗ trợ ở bước gợi ý số lượng.

### NguyenTaiMinhHuy-2A202603828

**Phần việc phụ trách:**

- Tham gia CP3 (Mục 2): Đề xuất 3 Problem Cards, tham gia Pitch, phản biện các candidate của thành viên khác, hỗ trợ Cluster, Opportunity Solution Tree (OST) và đánh giá shortlist.
- Phụ trách CP6 (Mục 6): Phân tích mức can thiệp AI, so sánh No AI / Rule / Workflow / Agent, xây dựng AI Canvas và trả lời hai câu hỏi Google PAIR.
- Đề xuất phân chia rõ vai trò của Rule-based, AI và con người trong quy trình quản lý tồn kho, đồng thời xem xét những rủi ro khi AI dự báo sai.

**Đóng góp cụ thể (mình đã làm gì, ra sản phẩm gì):**

- **CP3 - Pitch:** Chuẩn bị 3 Problem Cards về Debug Python, kiểm tra assignment theo rubric và xác định kiến thức còn yếu sau buổi học. Đặt câu hỏi phản biện về đánh giá sản phẩm, tóm tắt file ghi âm và góp ý mở rộng quản lý tồn kho theo từng chi nhánh.
- **CP3 - Cluster và OST:** Hỗ trợ phân nhóm 12 candidates theo các vấn đề tương tự, xây dựng các opportunity liên quan đến việc đối chiếu tồn kho, xác định mặt hàng bán chạy và quyết định số lượng cần nhập.
- **CP3 - Shortlist:** Hỗ trợ so sánh Candidate #1 (Quản lý tồn kho), #6 (Tổng hợp deadline) và #12 (Phân loại phản ánh khách hàng). Nhóm lựa chọn Candidate #1 làm bài toán chính.
- **CP6 – Mục 6.1:** Phân tích bài toán quản lý tồn kho có độ mơ hồ cao và độ phức tạp cao do nhu cầu mua hàng thay đổi theo màu sắc, kích cỡ, mùa vụ và chương trình khuyến mãi.
- **CP6 - Mục 6.2:** So sánh bốn mức No AI, Rule, Workflow và Agent. Đề xuất Workflow kết hợp Rule + AI + Human-in-the-loop (HITL), nhưng chỉ giữ AI nếu kiểm thử chứng minh hiệu quả tốt hơn Rule-based.
- **CP6 - Mục 6.3:** Xây dựng AI Canvas gồm Prediction, Judgment, Action, Outcome, Input và Feedback; làm rõ dữ liệu đầu vào, đề xuất nhập hàng [DRAFT] và trách nhiệm phê duyệt của chủ shop.
- **CP6 - Mục 6.4:** Phân tích Augment so với Automate theo Google PAIR; đánh giá hai loại lỗi False Positive và False Negative. Đề xuất các biện pháp kiểm soát như chủ shop phê duyệt, cảnh báo số lượng bất thường và fallback về Rule-based.

**Bằng chứng (phần nào trong group_report.md, commit nào):**

- **Mục 2.1-2.4 (CP3):** Pitch, Cluster, Opportunity Solution Tree và Chấm điểm shortlist trong `report/team/group_report.md`.
- **Mục 6.1:** Ma trận độ mơ hồ × độ phức tạp.
- **Mục 6.2:** Bảng so sánh bốn mức No AI / Rule / Workflow / Agent và lý do lựa chọn Workflow.
- **Mục 6.3:** AI Canvas rút gọn với 6 thành phần.
- **Mục 6.4:** Hai câu hỏi Google PAIR về Augment/Automate và False Positive/False Negative.
- Các ảnh lịch sử thay đổi GitHub cho thấy nội dung Mục 6 đã được cập nhật, bao gồm bảng so sánh bốn mức, AI Canvas và Google PAIR. Cần lấy mã commit đầy đủ từ GitHub để bổ sung bằng chứng chính xác.
- Báo cáo cá nhân: `report/individual/2A202603828_NguyenTaiMinhHuy.md`.

**Điều mình học được từ phần nhóm:**

- Không nên bắt đầu bằng việc lựa chọn công nghệ AI khi chưa hiểu rõ vấn đề của người dùng. Nhiều bước như đồng bộ tồn kho, tính tốc độ bán và cảnh báo Min/Max có thể được giải quyết hiệu quả bằng Rule hoặc Script.
- Workflow phù hợp hơn Agent đối với bài toán quản lý tồn kho vì quy trình đã có các bước xác định trước, còn quyết định nhập hàng liên quan trực tiếp đến ngân sách của chủ shop.
- AI chỉ nên hỗ trợ dự báo và đề xuất số lượng nhập hàng khi dữ liệu đủ tin cậy. Mọi đề xuất cần được con người kiểm tra, và hệ thống phải có phương án quay về Rule-based nếu AI không mang lại hiệu quả tốt hơn.

- Phải có ranh giới rõ ràng: Việc nhập hàng dính tới tiền bạc của người ta nên tuyệt đối không để AI tự quyết hay tự gửi đơn cho xưởng, luôn phải để chủ shop kiểm tra và chốt lại cuối cùng.
