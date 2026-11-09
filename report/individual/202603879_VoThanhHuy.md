# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Võ Thanh Huy
- MSSV: 2A202603879
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:NhomLeague
- Link repo nhóm: https://github.com/DoAnhThu832004/K5-L3B-Day02-NhomLeague-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi muốn mua một sản phẩm được bán trên nhiều sàn thương mại điện tử, tôi muốn so sánh giá bán thực tế giữa các cửa hàng, để lựa chọn nơi mua phù hợp với ngân sách. | Người mua hàng trực tuyến, đặc biệt là sinh viên có ngân sách hạn chế. | Thời gian kiểm tra giá trên 3 cửa hàng: 15 phút. Bằng chứng: lịch sử tìm kiếm, ảnh chụp giá sản phẩm trên các sàn. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi lựa chọn điện thoại hoặc laptop có nhiều phiên bản khác nhau, tôi muốn hiểu sự khác biệt về thông số kỹ thuật, để lựa chọn sản phẩm phù hợp với nhu cầu sử dụng. | Sinh viên, người mua thiết bị công nghệ chưa có nhiều kiến thức chuyên môn. | Số sản phẩm cần so sánh: 3; thời gian đọc thông số: 35 phút. Bằng chứng: các trang thông số sản phẩm đã xem. |
| 3 | Tốn thời gian | Tốn thời gian tìm cơ hội thực tập phù hợp. Khi tìm vị trí thực tập, tôi muốn xác định các công việc phù hợp với kỹ năng hiện tại, để không mất thời gian đọc những tin tuyển dụng không đáp ứng điều kiện. | Sinh viên năm cuối, sinh viên mới tốt nghiệp và người chưa có kinh nghiệm làm việc đang tìm kiếm cơ hội thực tập. | Trong một lần tìm kiếm, tôi xem 20 tin tuyển dụng và mất khoảng 30 phút để đọc, đối chiếu yêu cầu với kỹ năng hiện tại. Bằng chứng: lịch sử tìm kiếm trên các trang tuyển dụng, đường dẫn và ảnh chụp các tin đã xem. |
| 4 | Lặp lại | Khi có nhiều bài tập và hạn nộp từ các môn hoặc hoạt động khác nhau, tôi muốn nắm được thời hạn của từng việc, để sắp xếp thời gian và tránh nộp muộn. | Sinh viên tham gia nhiều môn học hoặc khóa đào tạo. | Cần đo 15 thuật ngữ cần tra cứu trong một buổi, 20 phút dành cho việc tìm hiểu. Bằng chứng: ghi chú học tập và lịch sử tra cứu. |
| 5 | Pain từ người khác | Khi người thân hoặc bạn bè nhờ tôi tư vấn mua thiết bị công nghệ, tôi muốn xác định sản phẩm phù hợp với nhu cầu và ngân sách của họ, để đưa ra lời tư vấn có căn cứ mà không phải tìm kiếm quá nhiều lần. | Người được nhờ tư vấn và người cần mua thiết bị. | Số lần được nhờ tư vấn: 2 lần/tháng; thời gian tìm kiếm mỗi lần: 40 phút\lần. Bằng chứng: tin nhắn nhờ tư vấn đã ẩn thông tin cá nhân, danh sách sản phẩm từng so sánh. |

**Nếu có dùng AI để gợi ý thêm:**

Sử dụng ChatGPT để đề xuất các tình huống cụ thể liên quan đến việc mất thời gian so sánh sản phẩm khi mua hàng, bao gồm so sánh giá, thông số kỹ thuật, khuyến mãi và tư vấn mua hàng.

- **Ý AI gợi ý tôi giữ lại:** Problem #3 — Cần đọc, tổng hợp nhiều thông tin: Khó xác định ưu điểm và nhược điểm của sản phẩm từ nhiều đánh giá của người mua.
- **Ý AI gợi ý tôi muốn bỏ:** Problem #5 — Pain từ người khác: Mất thời gian tư vấn mua thiết bị công nghệ cho người thân hoặc bạn bè.
- **Lý do lựa chọn:** Tôi chọn giữ lại Problem #3 vì khi mua hàng trực tuyến, việc đọc và tổng hợp nhiều đánh giá khác nhau có thể mất nhiều thời gian. Các đánh giá đôi khi trái chiều, khiến việc xác định ưu điểm, nhược điểm và chất lượng thực tế của sản phẩm trở nên khó khăn. Đây là vấn đề tôi muốn tìm hiểu và kiểm chứng sâu hơn. Tôi quyết định loại bỏ Problem #5 vì muốn tập trung vào những khó khăn mà bản thân trực tiếp gặp phải trong quá trình mua hàng, thay vì vấn đề phát sinh khi tư vấn sản phẩm cho người khác .

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Mất thời gian đọc và tổng hợp đánh giá sản phẩm | Tôi cần đọc khoảng 30 đánh giá trong 25 phút. Các đánh giá có thể trái chiều và chứa nhiều thông tin không liên quan, gây khó khăn khi xác định ưu điểm và nhược điểm thực tế của sản phẩm. | Chưa chắc có thể giảm thời gian đọc mà vẫn giữ được các thông tin quan trọng? Các đánh giá có đáng tin cậy không? |
| 2 | Khó so sánh thông số kỹ thuật giữa các sản phẩm | Tôi mất khoảng 35 phút để đọc thông số của 3 sản phẩm. Các thông số kỹ thuật khác nhau khiến việc xác định sản phẩm phù hợp với nhu cầu trở nên khó khăn. | Có phải tất cả thông số đều quan trọng? Người mua có thực sự cần đọc đầy đủ trước khi quyết định không? |
| 3 | Mất thời gian so sánh giá bán ở nhiều cửa hàng | Tôi mất khoảng 15 phút để kiểm tra giá sản phẩm từ 3 cửa hàng khác nhau. Việc tìm và đối chiếu giá làm tăng thời gian ra quyết định mua hàng. | Các công cụ so sánh giá hiện có đã giải quyết đủ tốt vấn đề này chưa? |

### Problem Card #1 — Đọc và tổng hợp đánh giá sản phẩm

| Trường | Nội dung |
|---|---|
| Job Story | Khi một sản phẩm có nhiều đánh giá trái chiều từ người mua trước, tôi muốn xác định những ưu điểm và nhược điểm thường gặp, để hạn chế lựa chọn sản phẩm không đáp ứng nhu cầu. |
| Actor | Người mua sắm trực tuyến, đặc biệt là người cần tìm hiểu chất lượng sản phẩm trước khi mua. |
| Thời điểm / bối cảnh | Khi đã tìm được sản phẩm quan tâm nhưng chưa quyết định mua vì cần xem đánh giá từ người dùng trước đó. |
| Quy trình hiện tại | 1. Mở trang sản phẩm. 2. Truy cập vào sản phẩm 3. Truy cập mục đánh giá. 4. Đọc các đánh giá của người mua. 5. Đối chiếu những ý kiến tích cực và tiêu cực. 6. Tổng hợp ưu điểm, nhược điểm để đưa ra quyết định. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — đọc nhiều đánh giá, dự kiến mất 12 phút trong tổng số 25 phút. Đây là thời gian phân bổ tạm, cần đo lại. |
| Impact | Người mua mất nhiều thời gian tìm hiểu, có thể bỏ sót nhược điểm quan trọng hoặc đưa ra quyết định dựa trên một vài đánh giá không đại diện. |
| Success metric (baseline → target) | Thời gian đọc và tổng hợp 30 đánh giá: 25 phút → mục tiêu đề xuất 15 phút, đồng thời không bỏ sót các ưu/nhược điểm quan trọng khi đối chiếu thủ công. |
| Phương án không dùng AI | Sử dụng bộ lọc đánh giá, ưu tiên đánh giá có hình ảnh, ghi lại các vấn đề xuất hiện nhiều lần. |
| Giả thuyết về AI | AI có thể hỗ trợ tổng hợp và phân loại các đánh giá thành ưu điểm, nhược điểm và vấn đề thường gặp. Tuy nhiên, kết quả cần được đối chiếu với đánh giá gốc để tránh tổng hợp sai. |
| Cảm nhận nhanh | Workflow — giả thuyết ban đầu, cần so sánh với cách lọc đánh giá thủ công. |

**Quy trình nháp hiện tại:**

```text
[B1. Mở trang sản phẩm — 1 phút]
                  |
                  v
B2. Mở trang sản phẩm — 1 phút
                  |
                  v
B3. Truy cập mục đánh giá — 5 phút
                  |
                  v
B4.(BOTTLENECK) Đọc 30 đánh giá — 15 phút
                  |
                  v
B5. Đối chiếu ý kiến — 4 phút
                  |
                  v
B6. Tổng hợp ưu, nhược điểm — 2 phút

Tổng: 28 phút/lần
```

### Problem Card #2— Tìm cơ hội thực tập phù hợp

| Trường | Nội dung |
|---|---|
| Job Story | Khi tìm vị trí thực tập, tôi muốn xác định các công việc phù hợp với kỹ năng hiện tại, để không mất thời gian đọc những tin tuyển dụng không đáp ứng điều kiện. |
| Actor | Sinh viên năm cuối, sinh viên mới tốt nghiệp và người chưa có kinh nghiệm làm việc đang tìm kiếm cơ hội thực tập. |
| Thời điểm / bối cảnh | Khi sinh viên bắt đầu tìm kiếm cơ hội thực tập trên các trang tuyển dụng nhưng chưa biết vị trí nào phù hợp với kỹ năng và kiến thức hiện tại. |
| Quy trình hiện tại (3–7 bước) | 1. Truy cập các trang tuyển dụng. 2. Tìm kiếm vị trí thực tập theo ngành nghề. 3. Mở và đọc yêu cầu của từng tin tuyển dụng. 4. Đối chiếu yêu cầu với kỹ năng hiện tại. 5. Lưu lại những vị trí phù hợp để cân nhắc ứng tuyển. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 4 — đọc yêu cầu công việc và đối chiếu với kỹ năng bản thân. Tổng thời gian tìm kiếm và đối chiếu 20 tin là 30 phút; cần đo riêng thời gian của từng bước để xác định bottleneck chính. |
| Impact (nếu không giải thì sao) | Sinh viên mất nhiều thời gian đọc những tin tuyển dụng không phù hợp, dễ bỏ lỡ các cơ hội thực tập phù hợp và khó tập trung chuẩn bị hồ sơ ứng tuyển. |
| Success metric (baseline → target) | Giảm thời gian sàng lọc 20 tin tuyển dụng từ 30 phút xuống còn 15 phút, đồng thời đảm bảo không bỏ sót những vị trí phù hợp với kỹ năng hiện tại. |
| Phương án không dùng AI | Sử dụng bộ lọc theo ngành nghề, vị trí, kinh nghiệm trên các trang tuyển dụng. Tạo danh sách kỹ năng hiện có và checklist điều kiện để kiểm tra từng tin. |
| Giả thuyết về AI (nếu có) | AI có thể đọc nội dung tuyển dụng, trích xuất yêu cầu về kỹ năng, so sánh với hồ sơ kỹ năng người tìm việc và gợi ý các vị trí phù hợp. Người dùng cần kiểm tra lại trước khi ứng tuyển. |
| Cảm nhận nhanh | Workflow — có thể kết hợp bộ lọc và AI để hỗ trợ sàng lọc, nhưng cần thử phương án thủ công trước. |

**Quy trình nháp hiện tại:**

```text
B1. Truy cập trang tuyển dụng
                 |
                 v
B2. Tìm vị trí thực tập
                 |
                 v
B3. Đọc 20 tin tuyển dụng
                 |
                 v
B4(BOTTLENEC). Đối chiếu yêu cầu với kỹ năng
                 |
                 v
B5. Lưu các vị trí phù hợp

Tổng thời gian: 30 phút
Thời gian từng bước: cần đo thêm
```

---

### Problem Card #3— Quản lý bài tập và thời hạn nộp 

| Trường | Nội dung |
|---|---|
| Job Story | Khi có nhiều bài tập và hạn nộp từ các môn hoặc hoạt động khác nhau, tôi muốn nắm được thời hạn của từng việc, để sắp xếp thời gian và tránh nộp muộn. |
| Actor | Sinh viên tham gia nhiều môn học, khóa đào tạo hoặc hoạt động có thời hạn nộp bài khác nhau. |
| Thời điểm / bối cảnh | Khi sinh viên nhận nhiều bài tập, thông báo và deadline từ LMS, email, nhóm lớp hoặc các nền tảng học tập khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận thông báo bài tập từ các nguồn. 2. Kiểm tra nội dung và thời hạn từng bài. 3. Ghi lại deadline vào lịch hoặc ghi chú. 4. Sắp xếp thứ tự ưu tiên. 5. Kiểm tra lại các deadline trong quá trình làm bài. 6. Hoàn thành và nộp bài trước thời hạn. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 và 5 — phải kiểm tra nhiều nguồn thông báo và thường xuyên xem lại deadline. Cần đo thời gian thực tế |
| Impact (nếu không giải thì sao) | Sinh viên có thể quên deadline, phân bổ thời gian không hợp lý, phải hoàn thành bài gấp hoặc nộp muộn, ảnh hưởng đến kết quả học tập. |
| Success metric (baseline → target) | Số bài nộp muộn mỗi tháng: [cần đo] → mục tiêu 0 bài. Thời gian kiểm tra và tổng hợp deadline mỗi tuần: [cần đo] → mục tiêu giảm ít nhất 50% so với hiện tại. |
| Phương án không dùng AI | Sử dụng Google Calendar, ứng dụng ghi chú hoặc bảng checklist để tổng hợp deadline. Đặt thông báo nhắc trước 1–2 ngày và đánh dấu những bài đã hoàn thành. |
| Giả thuyết về AI  | AI có thể hỗ trợ trích xuất tên bài tập và thời hạn từ thông báo, sau đó đề xuất lịch học. Người dùng phải kiểm tra thông tin trước khi lưu; chức năng nhắc deadline có thể thực hiện bằng quy tắc thông thường. |
| Cảm nhận nhanh | Rule / Workflow — chưa cần AI nếu việc ghi deadline và nhắc lịch thông thường đã đáp ứng nhu cầu. |

**Quy trình nháp hiện tại:**

```text
B1. Nhận thông báo bài tập
                 |
                 v
B2. Kiểm tra deadline từng nguồn
                 |
                 v
B3. Ghi deadline vào lịch
                 |
                 v
B4. Sắp xếp thứ tự ưu tiên
                 |
                 v
B5.(BOTTLENECK) Kiểm tra lại deadline
                 |
                 v
B6. Hoàn thành và nộp bài

Thời gian mỗi bước: cần đo
Tổng thời gian kiểm tra: cần đo
```

### Card muốn pitch nhất

- **Card số:** 1 — Đọc và tổng hợp đánh giá sản phẩm.
- **Vì sao:** Tôi ưu tiên vấn đề này vì việc đọc nhiều đánh giá trái chiều không chỉ tốn thời gian mà còn đòi hỏi khả năng tổng hợp và đánh giá thông tin. Vấn đề có đối tượng sử dụng rõ ràng, quy trình quan sát được và có chỉ số thời gian để đánh giá cải thiện. Đây cũng là bài toán phù hợp để tìm hiểu khả năng xử lý ngôn ngữ của AI, nhưng cần kiểm chứng xem các bộ lọc đánh giá hiện tại đã đủ hiệu quả hay chưa.
- **Câu hỏi muốn nhóm phản biện:** Việc đọc 30 đánh giá trong 25 phút có thực sự là một vấn đề đáng giải quyết bằng công cụ mới không, hay người mua chỉ cần sử dụng tốt hơn các bộ lọc đánh giá có sẵn?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ba vấn đề đều thuộc hoạt động so sánh sản phẩm, có thể trùng lặp về đối tượng và bối cảnh. | Cần tự đánh giá | Trong bản nháp đã phân biệt rõ ba bước: tìm hiểu đánh giá, so sánh thông số và so sánh giá bán. |
| Chưa có bằng chứng người mua khác cũng gặp khó khăn tương tự. | Cần kiểm chứng | Giữ phạm vi actor là người mua trực tuyến; chưa khẳng định đây là vấn đề phổ biến và đề xuất phỏng vấn ở CP4. |
| Tổng thời gian đã có, nhưng chưa đo chính xác thời gian của từng bước nghẽn. | Đồng ý | Đã tách quy trình thành từng bước và đánh dấu thời gian phân bổ tạm để đo lại. |
| Việc giảm thời gian đọc đánh giá có thể làm mất thông tin quan trọng. | Đồng ý | Bổ sung điều kiện không bỏ sót những ưu điểm và nhược điểm quan trọng vào Success metric. |
| Có thể đang nghĩ đến AI trước khi đánh giá công cụ hiện có. | Đồng ý | Bổ sung phương án không dùng AI cho cả ba card và chỉ xem AI là giả thuyết cần thử nghiệm. |

**Kết luận sơ bộ:** Tôi ưu tiên Card #1 để trình bày và tiếp tục kiểm chứng, nhưng chưa quyết định xây dựng công cụ AI khi chưa có thêm bằng chứng.

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
