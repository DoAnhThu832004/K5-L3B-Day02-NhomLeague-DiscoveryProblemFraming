# Báo cáo cá nhân — 2A202603808_HoangQuangDat

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Hoàng Quang Đạt
- MSSV: 2A202603808
- Email trường (không bắt buộc, repo có thể để public): 26ai.dathq@vinuni.edu.vn
- Tên nhóm: TeamLeague
- Link repo nhóm: https://github.com/DoAnhThu832004/K5-L3B-Day02-NhomLeague-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại | Khi tới hạn nộp báo cáo tuần của đồ án, tôi muốn tổng hợp nhanh danh sách task đã hoàn thành từ Trello, để cập nhật tiến độ cho GVHD trước 22h Chủ Nhật |Nhóm trưởng, thành viên nhóm |Tốn 45–60 phút mỗi tối Chủ nhật; 3/5 tuần gần nhất gửi muộn do phải chờ hỏi từng bạn trong nhóm Zalo |
| 2 |Lặp lại |Khi đến cuối tháng, tôi muốn tổng hợp các hóa đơn tiền điện, nước, internet và đồ dùng chung từ ảnh chụp hóa đơn, để chia tiền sòng phẳng và minh bạch với các bạn cùng phòng |Bản thân và bạn cùng phòng |Mất 45–60 phút mỗi tối ngày 30 hàng tháng; tháng trước bị cãi nhau vì tính nhầm 1 hóa đơn tiền rác 60.000đ |
| 3 |Lặp lại |Khi kết thúc một ngày, tôi muốn ghi nhận lại các khoản chi tiêu tiền mặt và chuyển khoản lẻ (ăn sáng, gửi xe, cafe), để kiểm soát ngân sách sinh hoạt không bị thâm hụt trước cuối tháng|Bản thân |Tốn 10–15 phút mỗi tối; tuần trước bỏ quên 3 ngày không ghi dẫn đến tài khoản hụt mất 350.000đ không rõ lý do |
| 4 |Tốn thời gian |Khi cần tìm phòng trọ mới gần trường/chỗ làm, tôi muốn lọc nhanh các bài đăng chính chủ và loại bỏ tin đăng trùng lặp hoặc tin từ môi giới ảo, để tìm được phòng đúng giá trong thời gian ngắn |Sinh viên, Người thuê trọ |Mất 2–3 tiếng mỗi tối lướt hơn 10 nhóm Facebook; gọi thử 6 số điện thoại thì 5 số là môi giới dẫn đi xem phòng khác |
| 5 |Tốn thời gian |Khi nghe lại file ghi âm buổi họp/bài giảng kéo dài 60–90 phút, tôi muốn xác định nhanh các mốc thời gian thảo luận ý chính và danh sách việc cần làm, để không phải tua nghe lại từ đầu |Sinh viên, người ghi biên bản |Mất 45–60 phút tua đi tua lại mỗi file ghi âm; tuần trước bỏ sót 1 bài tập giảng viên dặn miệng ở phút thứ 75  |
| 6 |Pain từ người khác |Khi khách hàng gửi tin nhắn phản ánh chất lượng bằng câu chữ bức xúc và teencode viết tắt, tôi muốn phân loại nhanh mức độ khẩn cấp và lý do phàn nàn chính, để chuyển đúng người xử lý trong vòng 15 phút |Nhân viên trực page CSKH, khách hàng |30–50 tin nhắn mỗi ngày; hôm qua bị khách hàng VIP dọa hủy hợp đồng vì tin nhắn khiếu nại bị trôi mất 4 tiếng |
| 7 | Pain từ người khác |Khi người nhà lớn tuổi gửi ảnh chụp đơn thuốc viết tay kèm chẩn đoán, tôi muốn chuyển đổi thành bảng hướng dẫn uống thuốc rõ ràng theo từng buổi sáng/trưa/tối, để bố mẹ uống thuốc đúng giờ và không uống nhầm loại | Bố mẹ lớn tuổi, con cái |Mất 30–45 phút dịch chữ bác sĩ và gọi hỏi lại hiệu thuốc|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Ý giữ lại: Ý 6 (Phân loại tin nhắn khiếu nại CSKH) và Ý #7 (Trích xuất toa thuốc viết tay): Giữ lại vì đây là các bài toán xử lý dữ liệu phi cấu trúc (tin nhắn teencode cảm xúc, ảnh chụp chữ viết tay) mà code truyền thống bó tay, có điểm nghẽn thực sự về mặt thời gian và ảnh hưởng trực tiếp đến con người.
- Ý bỏ: Bỏ ý "Tối ưu hóa thời gian ngủ và sinh hoạt cá nhân": Quá mơ hồ, không có quy trình cụ thể (không chỉ ra được 3–5 bước làm việc), không có điểm nghẽn rõ ràng để đo lường.
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Tóm tắt mốc thời gian file ghi âm bài giảng/họp |Tần suất lặp lại hàng tuần, dễ đo lường thời gian baseline |Chất lượng âm thanh rè hoặc nhiều người nói chèn nhau |
| 2 |Chuyển đổi đơn thuốc viết tay|Tác động sức khỏe lớn, quy trình rõ, chữ bác sĩ viết tay là nỗi đau thật của nhiều gia đình |Trách nhiệm pháp lý và ranh giới an toàn khi AI nhận diện nhầm liều lượng |
| 3 |Phân loại tin nhắn CSKH khẩn cấp |Dễ đo lường thời gian và SLA phản hồi, bài toán doanh nghiệp thực tế |Làm sao đo được độ nhạy cảm xúc khi khách dùng teencode mỉa mai |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi muốn nghe lại file ghi âm buổi họp/bài giảng kéo dài 60–90 phút, tôi muốn xác định nhanh các mốc thời gian thảo luận ý chính và danh sách việc cần làm, để không phải tua nghe lại từ đầu |
| Actor | Sinh viên, Học sinh, thành viên phụ trách ghi biên bản cuộc họp |
| Thời điểm / bối cảnh | Sau buổi học kéo dài hoặc sau buổi họp sprint dự án vào cuối ngày |
| Quy trình hiện tại (3–7 bước) | 1. Tải file ghi âm từ điện thoại/Drive về máy tính (3')<br>2. Mở trình phát âm thanh và file Word ghi chú (2')<br>3. Tua tới lui các đoạn giảng viên/nhóm nhấn mạnh hoặc giao bài tập (35')<br>4. Gõ lại danh sách đầu việc và mốc thời gian vào biên bản (10')<br>5. Đọc lại và gửi vào nhóm Zalo (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Mất 35 phút tua đi tua lại vì không biết đoạn nào nói về bài tập/nhiệm vụ |
| Impact (nếu không giải thì sao) | Tốn 55 phút mỗi buổi họp; tuần trước bỏ sót 1 bài tập giảng viên dặn miệng ở phút thứ 75 |
| Success metric (baseline → target) | Thời gian tổng hợp giảm từ 55 phút xuống dưới 15 phút; tỷ lệ bỏ sót đầu việc = 0% |
| Phương án không dùng AI | Người nói tự viết biên bản hoặc tự ghi chú timestamp trong lúc họp (khó thực hiện vì ngắt quãng mạch nói) |
| Giả thuyết về AI (nếu có) | Chuyển âm thanh thành văn bản có mốc giờ (Timestamped Transcript) ➔ Trích xuất các câu có hàm ý giao việc/deadline ➔ Người nghe bấm vào đúng mốc giờ để kiểm chứng lại |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng: 55 phút

[1. Tải file ghi âm: 3'] 
  ──> [2. Mở file Word: 2'] 
  ──> [3. Tua tới lui tìm đoạn giao bài/nhiệm vụ: 35']  ← BOTTLENECK (Tốn thời gian nhất)
  ──> [4. Soạn danh sách việc cần làm: 10'] 
  ──> [5. Review & gửi nhóm: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi người nhà lớn tuổi gửi ảnh chụp đơn thuốc viết tay kèm chẩn đoán, tôi muốn chuyển đổi thành bảng hướng dẫn uống thuốc rõ ràng theo từng buổi sáng/trưa/tối, để bố mẹ uống thuốc đúng giờ và không uống nhầm loại |
| Actor | Con cái (người hỗ trợ từ xa), bố mẹ lớn tuổi (người trực tiếp uống thuốc) |
| Thời điểm / bối cảnh | Sau khi bố mẹ đi khám định kỳ tại bệnh viện tuyến dưới/phòng khám về, nhận đơn thuốc viết tay nhiều loại |
| Quy trình hiện tại (3–7 bước) | 1. Nhận ảnh chụp đơn thuốc mờ qua Zalo (2')<br>2. Căng mắt dịch tên từng hoạt chất/biệt dược và liều lượng (15')<br>3. Tra cứu Google hoặc gọi điện hỏi lại dược sĩ hiệu thuốc để xác nhận lại tên thuốc (15')<br>4. Gõ lại ra tin nhắn Zalo hoặc ghi ra giấy dán tủ lạnh chia theo Sáng/Trưa/Tối (8') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3: Mất 30 phút vì chữ bác sĩ viết tắt, nguy cơ nhìn nhầm liều lượng gây nguy hiểm tính mạng |
| Impact (nếu không giải thì sao) | Bố mẹ lớn tuổi uống nhầm thuốc hoặc bỏ uống vì nhìn đơn quá rối; từng có tiền sử uống nhầm thuốc huyết áp vào buổi tối |
| Success metric (baseline → target) | Thời gian lập bảng hướng dẫn giảm từ 40 phút xuống dưới 10 phút; tỷ lệ sai lệch tên/liều thuốc khi đối chiếu với dược sĩ = 0% |
| Phương án không dùng AI | Mua hộp chia thuốc sẵn có dán nhãn theo thứ trong tuần; yêu cầu bệnh viện in đơn điện tử (nhưng nhiều cơ sở y tế vẫn viết tay) |
| Giả thuyết về AI (nếu có) | Vision Model nhận diện chữ viết tay ➔ Trích xuất bảng tên thuốc, liều dùng theo bữa ➔ Bắt buộc con cái/dược sĩ review  trước khi gửi cho bố mẹ |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng: 40 phút

[1. Nhận ảnh Zalo: 2'] 
  ──> [2. Căng mắt dịch chữ bác sĩ: 15'] 
  ──> [3. Tra cứu Google / Gọi dược sĩ kiểm tra: 15']  ← BOTTLENECK (Nguy hiểm, dễ nhầm)
  ──> [4. Soạn bảng chia liều gửi bố mẹ: 8']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách hàng gửi tin nhắn phản ánh chất lượng bằng câu chữ bức xúc và teencode viết tắt, tôi muốn phân loại nhanh mức độ khẩn cấp và lý do phàn nàn chính, để chuyển đúng người xử lý trong vòng 15 phút |
| Actor | Nhân viên trực page chăm sóc khách hàng, nhân viên hỗ trợ kỹ thuật |
| Thời điểm / bối cảnh | Giờ cao điểm bán hàng (11h–13h hoặc 20h–22h) khi có 30–50 tin nhắn đổ về đồng loạt |
| Quy trình hiện tại (3–7 bước) | 1. Đọc tin nhắn mới trong hộp thư đến (3')<br>2. Dịch các từ viết tắt/teencode và tìm hiểu khách đang giận vì điều gì (5')<br>3. Đánh giá mức độ nghiêm trọng (khách thường hay khách VIP dọa hủy dịch vụ) (3')<br>4. Soạn tin nhắn xin lỗi tạm thời và chuyển tiếp cho quản lý/kỹ thuật (4') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3: Mất 8 phút/tin; dễ quá tải làm trôi tin nhắn bức xúc của khách hàng lớn |
| Impact (nếu không giải thì sao) | Khách hàng VIP dọa hủy hợp đồng vì tin nhắn khiếu nại bị trôi mất 4 tiếng; nguy cơ bị bóc phốt trên mạng xã hội làm giảm uy tín thương hiệu |
| Success metric (baseline → target) | Thời gian phân loại và chuyển tiếp giảm từ 15 phút xuống dưới 2 phút; 0% tin nhắn khẩn cấp bị tồn đọng quá 30 phút |
| Phương án không dùng AI | Cài đặt chatbot rule-based theo từ khóa cố định ("hủy", "tệ") ➔ Nhược điểm: teencode biến thể liên tục ("huỷ", "hũy", "bực vcl", "lđ") khiến rule bỏ sót |
| Giả thuyết về AI (nếu có) | Mô hình ngôn ngữ đọc hiểu ngữ cảnh tự nhiên ➔ Gán nhãn tag [KHẨN CẤP] và trích xuất 1 câu tóm tắt lý do ➔ Đẩy lên đầu danh sách để nhân viên ưu tiên xử lý trước |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng: 15 phút/tin

[1. Đọc tin nhắn mới: 3'] 
  ──> [2. Đọc hiểu teencode & nguyên nhân giận: 5'] 
  ──> [3. Đánh giá mức độ khẩn cấp: 3']  ← BOTTLENECK (Dễ trôi tin, đọc sót)
  ──> [4. Soạn phản hồi & chuyển tiếp bộ phận: 4']
```

### Card muốn pitch nhất

- Card số: 1 (Tóm tắt mốc thời gian & việc cần làm từ file ghi âm bài giảng/buổi họp)
- Vì sao: 
  - Đây là nỗi đau thật mà bản thân tôi và hầu hết sinh viên/thành viên nhóm gặp phải hàng tuần (tần suất cao, 2–3 lần/tuần).
  - Có số liệu đo lường thời gian baseline rất rõ ràng và kiểm chứng được ngay (mất 55 phút để tua nghe và ghi chép; tuần trước vừa bị bỏ sót 1 bài tập giảng viên dặn miệng ở phút thứ 75).
  - Phạm vi bài toán (scoping) vừa vặn trong khuôn khổ một buổi lab, có thể so sánh rõ ràng giữa Rule (bấm giờ/chia mục thủ công) vs Workflow (Speech-to-text + LLM trích xuất task kèm timestamp có người duyệt) vs Agent.
- Lý do không chọn 2 card còn lại:
  - **Không chọn Card #2 (Chuyển đổi đơn thuốc viết tay):** Rủi ro y tế và pháp lý (Feasibility & Viability risk) quá cao. Nếu mô hình nhận diện sai tên thuốc hoặc liều lượng do ảnh mờ, hậu quả sẽ đe dọa trực tiếp đến tính mạng người dùng. Hơn nữa, nhóm sinh viên không đủ chuyên môn y khoa để thẩm định ground truth và khó xin được dữ liệu đơn thuốc thật để test trong thời gian lab mà không vi phạm quyền riêng tư bệnh nhân.
  - **Không chọn Card #3 (Phân loại tin nhắn CSKH teencode):** Bài toán đòi hỏi dữ liệu nội bộ của doanh nghiệp (log chat fanpage thật), sinh viên khó tiếp cận để kiểm chứng hành vi thật ở CP4. Ngoài ra, ranh giới giữa tin nhắn "bức xúc thực sự" và "than phiền vu vơ" phụ thuộc nhiều vào quy định riêng của từng công ty, khó thống nhất bộ tiêu chí đánh giá (eval metrics) trong phạm vi môn học.
- Câu hỏi muốn nhóm phản biện: "Làm thế nào để hệ thống phân biệt chính xác đâu là một nhiệm vụ/bài tập thật sự được giao, và đâu chỉ là một câu nói bâng quơ hoặc ví dụ minh họa của giảng viên/người nói, tránh làm người nghe bị 'bội thực' việc cần làm giả?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 55 phút nghe lại có thể giải quyết bằng cách nghe tốc độ 1.5x hoặc 2x mà không cần dùng AI | **Đồng ý một phần** | Đã thử nghe 1.5x/2x nhưng khi giảng viên nói nhanh thì càng dễ bỏ sót chi tiết và vẫn phải tua đi tua lại. Đã bổ sung rõ trong quy trình: điểm nghẽn không phải ở tốc độ phát mà ở việc **không biết đoạn nào chứa bài tập/nhiệm vụ** để nhảy đến đúng lúc. |
| AI gợi ý làm Agent tự động gửi email/tin nhắn giao việc cho các thành viên sau khi nghe xong | **Không đồng ý** | Giữ nguyên ranh giới an toàn (Boundary) ở mức Workflow: AI chỉ đóng vai trò soạn nháp danh sách việc kèm timestamp để con người bấm vào nghe lại và kiểm tra (Human-in-the-loop), tuyệt đối không để AI tự ý gửi việc đi. |
| Card #2 rủi ro y tế quá lớn, Card #3 khó lấy dữ liệu doanh nghiệp để test trong buổi lab | **Đồng ý hoàn toàn** | Đã dùng nhận định này để quyết định chọn Card #1 làm bài pitch chính cho nhóm, đồng thời đưa lý do loại trừ Card #2 và #3 vào phần lập luận hội tụ. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| **Pitch Problem Card** | Trình bày Card #1: *Tóm tắt mốc thời gian & việc cần làm từ file ghi âm bài giảng/buổi họp* (mất 55 phút nghe lại, tuần trước bỏ sót bài tập ở phút 75). | Bài toán được đưa vào danh sách pitch chung của nhóm để cùng so sánh, chấm điểm. |
| **Phản biện bài của bạn khác** | **Câu hỏi tôi đã đặt (cho bài Quản lý tồn kho & nhập hàng - Đề tài chốt):** "Các phần mềm quản lý kho (POS/ERP) hiện nay đều có thể tự động đặt ngưỡng Min/Max và hiển thị cảnh báo dashboard dựa trên số liệu bán hàng. Tại sao nhóm phải dùng Machine Learning dự đoán phức tạp trong khi giải pháp phần mềm thông thường (Rule-based) đã giải quyết được phần lớn bài toán này?" | Bạn phụ trách bài toán giải thích: Rule-based chỉ giải quyết được việc cảnh báo tồn kho tĩnh, còn với ngành thời trang có tính mùa vụ và xu hướng thay đổi nhanh thì việc dự đoán số lượng nhập theo từng mẫu/size/màu cần phân tích dữ liệu lịch sử bán hàng ➔ Nhóm thống nhất đây là bài toán kết hợp Rule + AI (Rule quản lý kho, ML dự đoán xu hướng nhu cầu). |
| **Nhận phản biện** | **Câu hỏi tôi nhận được (về bài ghi âm):** "Làm sao để hệ thống đoán được hoặc nắm bắt chính xác chủ đề (topic) của người nói khi bài giảng/buổi họp diễn ra liên tục, người nói chuyển mạch ý bất ngờ hoặc nói lan man mà không bị cắt vụn ngữ cảnh?" | **Tôi đã sửa gì:** Tôi điều chỉnh lại giả thuyết kỹ thuật và ranh giới an toàn: Thay vì để AI tự suy diễn chủ đề tùy tiện (rất dễ hallucination), hệ thống chỉ thực hiện phân đoạn ngữ nghĩa (Semantic Chunking) theo các mốc thời gian và từ khóa chuyển tiếp, rồi tạo nhãn mốc giờ (Timestamp). Bắt buộc người nghe bấm vào mốc giờ để nghe lại 15–30 giây ngữ cảnh gốc trước khi xác nhận chủ đề (Human-in-the-loop). |
| **Gom cluster / cây OST** | Đề xuất gom 12 candidate thành 5 nhóm dựa trên bản chất dữ liệu đầu vào. Tại cây OST, tôi kiên quyết yêu cầu nhóm gạch bỏ các nhánh "Xây chatbot", "App tự động đặt hàng" ở tầng Opportunity vì đó là giải pháp đội lốt. | Nhóm có 5 cluster trực quan; cây OST giữ đúng chuẩn Teresa Torres với 1 Outcome cốt lõi (Giảm thời gian kiểm tra tồn kho & cải thiện quyết định nhập hàng) và 3 Opportunity thực sự tập trung vào nỗi đau của chủ shop. |
| **Chọn candidate problem** | Tham gia chấm điểm shortlist cho 3 bài (#1 Tồn kho, #6 Deadline, #12 CSKH teencode). Tôi bỏ phiếu cao nhất cho bài #1 (Quản lý tồn kho) và phản biện bài #6 vì bài deadline sinh viên có thể giải quyết tốt bằng Google Calendar/Notion mà chưa cần AI. | Bài #1 đạt điểm cao nhất (32/35 điểm), cả nhóm đồng thuận chọn bài này vì có actor rõ, quy trình nghiệp vụ rõ ràng và đo lường được tác động tài chính/thời gian. |
| **Kiểm chứng / research** | Trực tiếp phỏng vấn 1 bạn học ở nhóm khác từng tự bán quần áo unisex trên Shopee 1 năm theo The Mom Test; cùng nhóm lập Assumption Map (ưu tiên kiểm chứng giả định #1, #2, #3); hỗ trợ tìm kiếm tài liệu về các giải pháp Rule-based (Zoho/POS) vs ML forecasting. | Thu được insight thực tế đắt giá: "đọng vốn 40% ở size to/màu kén khách, cháy hàng size basic". Ghi nhận tín hiệu phản bác then chốt: chủ shop không tin AI tự quyết và hàng hot trend không có dữ liệu cũ ➔ Giúp nhóm thu hẹp bài toán vào hàng basic và ranh giới [DRAFT]. |
| **Quy trình nhóm** | Cùng nhóm phân tích quy trình hiện tại (5 bước thủ công, 55 phút, nghẽn ở bước 3) và thiết kế quy trình tương lai; đề xuất sơ đồ quy trình phân tầng rõ rệt giữa Rule / Script (đồng bộ, tính toán thô) và AI (phân tích xu hướng nhu cầu). | Quy trình tương lai rút ngắn từ 55 phút xuống dưới 20 phút (giảm >60%), chỉ rõ điểm nghẽn nhận thức tại Bước 3 và bổ sung nhánh Fallback an toàn lùi về Rule Min/Max khi AI mất mạng hoặc thiếu dữ liệu. |
| **Problem Statement** | Cùng nhóm hoàn thiện Problem Statement v0 và v1; kiên quyết loại bỏ các từ định tính chung chung ("tối ưu kho") để thay bằng các chỉ số đo lường cụ thể (baseline 55' ➔ target <20', tỷ lệ duyệt ≥80%); siết chặt ranh giới Boundary. | Problem Statement của nhóm rất sắc bén, đạt chuẩn rubric: có baseline, target, cách đo lường cụ thể và ranh giới an toàn tuyệt đối (AI chỉ xuất draft, không được tự động gửi đơn cho xưởng). |
| **Mức can thiệp AI** | Đấu tranh giữ mức can thiệp ở **Workflow (kết hợp Rule + AI hỗ trợ)** thay vì nhảy vọt lên Autonomous Agent; tham gia điền AI Canvas rút gọn và trả lời 2 câu hỏi của Google PAIR (người dùng muốn Augment chứ không muốn Automate; báo nhầm đỡ tệ hơn báo sai số lượng lớn). | Nhóm định vị đúng bài toán ở vùng "Độ phức tạp thấp - Độ mơ hồ trung bình" (Workflow), tránh được bẫy over-engineering và tiết kiệm tài nguyên phát triển. |
| **Quyết định** | Phân tích 4 rủi ro của Marty Cagan (Value, Usability, Feasibility, Viability); đề xuất quyết định **Go có điều kiện (Pilot)** trên tập nhỏ hàng basic (30-50 SKU) và thiết lập ngưỡng dừng (Kill metric). | Nhóm thống nhất quyết định Go với pilot nhỏ nhất (chạy thử nghiệm dự báo cho 1 shop bán hàng trong 4 tuần); có ngưỡng dừng rõ ràng: nếu sau 4 tuần tỷ lệ chủ shop phải sửa bản nháp >30% thì quay về dùng Rule tính toán đơn giản trên Excel. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 Scan** | Gợi ý thêm các góc nhìn về các vấn đề trong đời sống và quản lý cá nhân. | Gợi ý các tình huống thực tế về dữ liệu phi cấu trúc (như trích xuất toa thuốc viết tay, tin nhắn khiếu nại). | Đưa ra các ý tưởng giải pháp trá hình ("Trợ lý AI tự học bài", "Tối ưu hóa giấc ngủ") không có quy trình nghiệp vụ rõ ràng. | Loại bỏ hoàn toàn các ý mơ hồ; viết lại các ý được chọn theo đúng cấu trúc Job Story (*Khi... tôi muốn... để...*) và tự bổ sung số liệu thời gian/tần suất thật của bản thân. |
| **CP2 Problem Card** | Đóng vai "PM hoài nghi" để phản biện Card #1 (Ghi âm bài giảng). | Bắt bẻ sắc bén: chỉ ra rằng nghe ở tốc độ 1.5x/2x có thể giải quyết được bài toán mà không cần AI. | Đề xuất xây dựng Agent tự động gửi danh sách task vào nhóm Zalo (quá phức tạp và dễ gây phiền toái nếu trích xuất nhầm). | Làm rõ trong quy trình: nút thắt không phải tốc độ nghe mà là **không biết đoạn nào có bài tập** để nhảy tới; kiên quyết giữ mức can thiệp ở Workflow (AI chỉ tạo timestamp nháp để người nghe tự duyệt). |
| **CP4 Research** | Tìm kiếm các phần mềm quản lý kho/bán hàng (POS) và công cụ dự đoán tồn kho hiện có trên thị trường (KiotViet, Sapo, Odoo). | Tổng hợp nhanh danh sách các phần mềm phổ biến và các tính năng quản lý kho cơ bản (cảnh báo tồn kho Min/Max). | Tuyên bố rằng "hầu hết các phần mềm POS hiện nay đều đã tích hợp sẵn AI tự động dự báo lượng hàng cần nhập cho từng size/màu" (thực tế các gói cơ bản cho shop nhỏ chỉ dùng rule cảnh báo số lượng). | Tự tra cứu trực tiếp bảng giá và tài liệu tính năng của KiotViet/Sapo; xác nhận tính năng dự báo AI chuyên sâu chưa phổ biến ở phân khúc cửa hàng nhỏ lẻ. |
| **CP5 Quy trình** | Hỗ trợ chuyển đổi các bước quy trình nhập hàng hiện tại và tương lai thành cú pháp sơ đồ Mermaid/ASCII. | Giúp format sơ đồ nhanh, trực quan, dễ nhìn. | Tự động bỏ qua bước chủ shop kiểm tra và chốt số lượng với nhà cung cấp, gộp thẳng từ bước "AI gợi ý" sang "Tự động gửi đơn đặt hàng". | Bổ sung bước Human-in-the-loop bắt buộc: chủ shop phải duyệt và điều chỉnh số lượng đề xuất trước khi liên hệ nhà cung cấp; thêm nhánh Fallback nếu dữ liệu bán hàng quá ít thì quay về dùng Rule tồn kho tối thiểu. |
| **CP5–6 Problem Statement** | Rà soát các trường trong Problem Statement (đặc biệt là Success Metric và Boundary) xem có bị mơ hồ không. | Cảnh báo không được dùng các từ định tính như "giảm tồn kho hiệu quả", "tối ưu hóa lợi nhuận". | Gợi ý đặt mục tiêu quá viển vông: "Dự đoán chính xác 100% nhu cầu nhập hàng" (phi thực tế trong ngành thời trang phụ thuộc nhiều vào thời tiết/xu hướng). | Đặt lại Success Metric có tính khả thi: thời gian lập danh sách nhập hàng giảm ≥ 50%, tỷ lệ đề xuất đúng nhu cầu đạt ≥ 80% sau khi đối chiếu với quyết định thực tế của chủ shop. |
| **CP6 Mức can thiệp / quyết định** | Phản biện lựa chọn giữa Rule-based và Machine Learning cho bài toán quản lý tồn kho. | Chỉ ra ranh giới rõ ràng: Rule đủ cho việc cảnh báo tồn kho tối thiểu, nhưng cần ML khi muốn phân tích tương quan giữa tốc độ bán, kích cỡ/màu sắc và tính mùa vụ. | Khuyên nhóm xây dựng hệ sinh thái Multi-Agent tự động liên hệ đàm phán giá với nhà cung cấp. | Nhóm kiên quyết từ chối giải pháp Agent; chốt mức can thiệp là **Rule + Workflow/AI hỗ trợ** và đề xuất quyết định **Go ở phạm vi nhỏ (Pilot)** kèm ngưỡng dừng nếu sai số vượt mức cho phép. |

---

## 6. Reflection (CP7)

Trắc nghiệm nhận thức và đúc rút bài học cá nhân qua toàn bộ quá trình Discovery & Problem Framing:

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi lắng nghe các candidate của các bạn trong nhóm (Debug code Python, Tổng hợp deadline từ nhiều kênh, và Quản lý tồn kho thời trang), bài học lớn nhất tôi rút ra là: sinh viên chúng tôi rất dễ bị thiên kiến lựa chọn những vấn đề liên quan trực tiếp đến việc học tập hàng ngày vì nó quen thuộc. Tuy nhiên, các bài toán học tập thường rất khó định lượng giá trị kinh tế (thế nào là "học hiểu sâu hơn"?) hoặc đã có sẵn nhiều giải pháp thay thế đơn giản (Google Calendar, Notion, ChatGPT). Ngược lại, bài toán Quản lý tồn kho của bạn Thư cho thấy một "nỗi đau kinh tế" cực kỳ rõ ràng: có dòng tiền bị chôn vốn cụ thể, có rủi ro mất khách hiện hữu, và quy trình có các bước nghiệp vụ đo đếm được bằng phút và con số tài chính. Tôi học được rằng một bài toán đáng giải không chỉ cần gây khó chịu (annoying), mà phải gây ra tổn thất thực sự (painful & costly) và có thể lượng hóa được thành công.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Nhóm tôi đã bị rơi vào bẫy "solution-first" ngay ở đầu buổi thảo luận CP3. Vừa khi chốt chọn chủ đề tồn kho, một thành viên đã lập tức hào hứng đề xuất: *"Nhóm mình làm một con AI Agent tự kết nối API KiotViet và tự nhắn tin qua Zalo đặt hàng xưởng may luôn cho ngầu"*. Lúc đó, tôi và cả nhóm giật mình nhận ra nhóm đang cầm một cây búa công nghệ (Agentic AI) đi tìm chiếc đinh, giả định rằng chủ cửa hàng muốn tự động hóa 100%. Nhóm đã kịp thời xử lý bằng cách áp dụng nghiêm ngặt quy tắc của Teresa Torres trong cây OST: lập tức gạch bỏ các từ ngữ mang tính giải pháp như "Chatbot", "AI Agent", "App tự động" ra khỏi tầng Opportunity. Chúng tôi ép nhau chỉ được nói về nhu cầu và nỗi đau nguyên bản: *"Mất thời gian đối chiếu thủ công từng SKU màu/size"* và *"Sợ đọng vốn hàng bán chậm"*. Nhờ đó, giải pháp sau này mới đi đúng hướng hỗ trợ nhận thức thay vì tự động hóa liều lĩnh.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý hoàn toàn sau khi nhận câu hỏi phản biện cho bài pitch cá nhân của mình (Card #1 - Tóm tắt việc cần làm từ ghi âm cuộc họp/bài giảng): *"Làm sao hệ thống nắm bắt chính xác chủ đề (topic) khi người nói chuyển ý đột ngột hoặc nói lan man mà không làm vụn ngữ cảnh?"*. Ban đầu, tôi khá chủ quan cho rằng các mô hình LLM hiện nay đủ thông minh để tự động phân đoạn và suy luận mọi ý chính. Nhưng câu hỏi phản biện đã chỉ ra lỗ hổng lớn: dữ liệu giọng nói đời thực có vô số từ đệm, nói đùa, lạc đề; nếu để AI tự do suy diễn, hiện tượng ảo giác (hallucination) sẽ sinh ra các nhiệm vụ giả mạo, làm người dùng mất lòng tin. Nhận ra điều đó, tôi đã lập tức từ bỏ ý định để AI "tự biên tự diễn" và chuyển sang thiết kế cơ chế Semantic Chunking có kiểm soát: AI chỉ đánh dấu mốc giờ (timestamp) và trích xuất câu nói gốc, bắt buộc con người phải bấm nghe lại 15 giây ngữ cảnh trước khi xác nhận tạo task (Human-in-the-loop).

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Điều làm tôi bất ngờ nhất chính là **tín hiệu phản bác** từ bạn học từng bán hàng Shopee trong buổi phỏng vấn The Mom Test ở CP4. Trước khi phỏng vấn, nhóm tôi đinh ninh rằng người bán hàng sẽ rất hào hứng nếu có một AI dự đoán số lượng nhập cho mọi loại quần áo. Nhưng khi phỏng vấn thực tế, bạn ấy thẳng thắn dội một "gáo nước lạnh": *"Quần áo bắt trend TikTok thay đổi theo tuần, máy móc làm sao đoán được khi không có dữ liệu cũ? Nếu AI tự đoán mấy mẫu đó thì mình chắc chắn không dám nghe theo vì sợ ôm đống hàng ế"*. Phát hiện này khiến tôi bất ngờ vì nó phá vỡ hoàn toàn giả định màu hồng của nhóm. Tuy nhiên, nó là thông tin vô giá giúp nhóm điều chỉnh kịp thời: loại bỏ hoàn toàn nhóm hàng thời trang theo trend ngắn hạn ra khỏi phạm vi bài toán, chỉ tập trung vào nhóm hàng cơ bản (basic items) có chu kỳ tiêu thụ ổn định, và bắt buộc đầu ra phải là bản nháp `[DRAFT]` để người bán duyệt lại dựa trên ngân sách thực tế.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với tôi và nhóm là việc thiết lập **Boundary (ranh giới an toàn)** và **Success Metric có thể đo lường độc lập**. Rất dễ để viết ra những câu tuyên bố bóng bẩy nhưng sáo rỗng như: *"Giúp chủ shop tối ưu hóa tồn kho và tăng trưởng doanh thu"*. Nhưng khi phải cụ thể hóa theo cấu trúc của môn học (Baseline ➔ Target và cách đo), nhóm gặp khó khăn lớn: doanh thu hay lợi nhuận phụ thuộc vào quá nhiều biến số ngoại cảnh (quảng cáo, thời tiết, đối thủ), không thể quy hết công trạng cho AI. Chúng tôi phải mất nhiều thời gian tranh luận để quy về những chỉ số đo đếm được ngay: thời gian lập danh sách nhập hàng (giảm từ 55' xuống <20' đo bằng bấm giờ) và tỷ lệ đề xuất được chủ shop chấp nhận duyệt (≥80%). Ngoài ra, việc xác định Boundary — dũng cảm gạch bỏ những việc AI **không được phép làm** (không tự đặt hàng, không dự đoán hàng trend) — đòi hỏi sự kỷ luật và hiểu biết sâu sắc về rủi ro của mô hình.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu có cơ hội làm lại buổi lab từ đầu, tôi sẽ thay đổi hai điểm:
1. **Tìm kiếm dữ liệu mẫu sớm hơn:** Thay vì chỉ phỏng vấn định tính bằng lời nói, tôi sẽ chủ động mượn một file Excel xuất tồn kho thật (khoảng 30–50 dòng SKU) từ bạn bè đang bán hàng ngay từ bước CP4. Có dữ liệu thực tế với các cột cụ thể sẽ giúp nhóm hình dung quy trình xử lý dữ liệu và thiết kế input/output cho AI ở CP5 sát sườn hơn nhiều.
2. **Phản biện nhóm quyết liệt hơn về chi phí và tính khả thi của dữ liệu:** Trong quá trình làm, nhóm từng có lúc thảo luận về việc huấn luyện các mô hình Machine Learning dự báo chuỗi thời gian chuyên sâu. Nếu làm lại, tôi sẽ phản biện mạnh mẽ hơn ngay từ đầu rằng với các shop nhỏ dưới 100 đơn/ngày, dữ liệu lịch sử rất mỏng và phân mảnh, việc áp dụng các công thức Rule thống kê (Moving Average / Reorder Point) kết hợp khả năng suy luận ngữ cảnh của LLM là đã quá đủ và thực tế hơn rất nhiều so với việc xây dựng một hệ thống ML đồ sộ tốn kém.

**6.7. Hiểu bài:** Giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình:

1. **Problem:** Chủ shop thời trang vừa và nhỏ gặp nút thắt nhận thức nghiêm trọng khi phải đối chiếu thủ công giữa tồn kho chi tiết và tốc độ bán của hàng chục mã màu/size, làm mất 55 phút mỗi tuần và thường xuyên phán đoán theo cảm tính dẫn đến đọng vốn hoặc cháy hàng.
2. **Quy trình:** Nhóm tái cấu trúc quy trình bằng cách dùng Rule/Script để tự động đồng bộ dữ liệu và tính tốc độ bán, sau đó dùng AI phân tích xu hướng tiêu thụ để soạn nháp bảng gợi ý số lượng cần nhập, trước khi chủ shop rà soát dòng tiền và bấm duyệt gửi cho xưởng.
3. **Metric:** Thành công được đo lường cụ thể bằng việc giảm thời gian lập danh sách từ 55 phút xuống dưới 20 phút/lần (bấm giờ trong 3 lần pilot) và đạt tỷ lệ đề xuất được chấp nhận duyệt mà không cần chỉnh sửa quá 20% đạt ≥ 80%.
4. **Boundary:** Ranh giới an toàn tối thượng là AI tuyệt đối không tự ý gửi đơn đặt hàng tới nhà cung cấp, không can thiệp vào các mẫu thời trang theo trend ngắn hạn thiếu dữ liệu, và luôn trả kết quả ở dạng danh sách nháp `[DRAFT]` kèm lý do số ngày tồn dự kiến.
5. **Mức can thiệp:** Nhóm chọn mức **Workflow (kết hợp Rule + AI hỗ trợ)** vì bài toán có các bước cố định, độ phức tạp thấp và độ mơ hồ ở mức trung bình (Rule chịu trách nhiệm tính toán chính xác, AI chỉ hỗ trợ nhận diện quy luật tiêu thụ).
6. **Phương án quay về:** Nếu hệ thống mất kết nối mạng hoặc dữ liệu bán hàng dưới 30 ngày, giải pháp tự động kích hoạt chế độ Fallback lùi về áp dụng công thức Rule Min/Max tồn kho truyền thống mà không làm gián đoạn công việc của shop.
7. **Quyết định:** Nhóm đưa ra quyết định **Go có điều kiện (Pilot)** thử nghiệm trên nhóm hàng basic của 1 cửa hàng trong 4 tuần; kèm ngưỡng dừng (Kill metric) nếu sau 4 tuần mà chủ shop vẫn phải chỉnh sửa lại quá 30% danh sách đề xuất thì lập tức dừng dự án AI và quay về hoàn thiện bảng tính Excel thông thường.

---

## 7. Tài liệu tham khảo

- Fitzpatrick, R. (2013). *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you.* Robfitz Ltd.
- Torres, T. (2021). *Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value.* Product Talk LLC.
- Bland, D. J., & Osterwalder, A. (2019). *Testing Business Ideas: A Field Guide for Rapid Experimentation.* John Wiley & Sons.
- Cagan, M. (2017). *Inspired: How to Create Tech Products Customers Love (2nd ed.).* Wiley.
- Agrawal, A., Gans, J., & Goldfarb, A. (2018). *Prediction Machines: The Simple Economics of Artificial Intelligence.* Harvard Business Press.
- Google People + AI Research (PAIR). *People + AI Guidebook: Designing human-centered AI products.* https://pair.withgoogle.com/guidebook/
- Anthropic. (2024). *Building Effective Agents.* https://www.anthropic.com/research/building-effective-agents
- Square for Retail. *Sell-Through Report & Inventory Management.* https://squareup.com/help/us/en/article/7809-sell-through-report-with-square-for-retail
- Zoho Inventory. *Item Reorder Notification & Low Stock Rules.* https://www.zoho.com/us/inventory/kb/items/item-reorder-notification.html
- Inventory Planner by Sage. *Replenishment & Demand Forecasting.* https://help.inventory-planner.com/en/articles/589017-replenishment
