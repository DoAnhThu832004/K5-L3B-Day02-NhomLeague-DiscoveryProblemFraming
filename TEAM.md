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
- Phải có ranh giới rõ ràng: Việc nhập hàng dính tới tiền bạc của người ta nên tuyệt đối không để AI tự quyết hay tự gửi đơn cho xưởng, luôn phải để chủ shop kiểm tra và chốt lại cuối cùng.
