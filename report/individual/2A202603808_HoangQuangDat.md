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
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
