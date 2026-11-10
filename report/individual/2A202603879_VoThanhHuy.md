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
| **Pitch Problem Card** | Tôi trình bày 3 vấn đề: đọc và tổng hợp đánh giá sản phẩm khi mua hàng, tìm cơ hội thực tập phù hợp với kỹ năng và theo dõi deadline từ nhiều nguồn khác nhau. Tôi giải thích actor, quy trình và bottleneck của từng vấn đề. | Nhóm có thêm các candidate thuộc lĩnh vực mua sắm, tìm việc và quản lý thời gian. Những vấn đề này được đưa vào phần hội tụ và phân nhóm ở CP3. |
| **Phản biện bài của bạn khác** |  cách phân biệt đánh giá thật với spam/bot | Những câu hỏi này giúp làm rõ vấn đề cốt lõi, xem xét giải pháp đã tồn tại và nhận diện rủi ro trước khi đề xuất sử dụng AI. |
| **Nhận phản biện** | Với vấn đề phân tích đánh giá sản phẩm, tôi nhận câu hỏi về cách phân biệt đánh giá thật với bot/spam. Với vấn đề quản lý deadline, tôi nhận câu hỏi liệu có thể gộp với candidate tổng hợp nhiệm vụ và deadline của thành viên khác không. | Những phản biện làm rõ hai điểm cần xử lý: tính đáng tin cậy của đánh giá sản phẩm và sự trùng lặp giữa các candidate. |
| **Gom cluster / cây OST** | Tôi xem xét các candidate mình trình bày trong bảng cluster: phân tích đánh giá sản phẩm và tìm thực tập thuộc nhóm C — Phân tích thông tin để đưa ra quyết định; quản lý deadline thuộc nhóm B — Quản lý nhiệm vụ và thời gian. | Nhóm xác định được các pattern chung. Cây OST của candidate được chọn tập trung vào ba khó khăn: đối chiếu tồn kho, nhận biết hàng bán chạy và quyết định số lượng nhập. |
| **Chọn candidate problem** | Tôi xem xét bảng shortlist của nhóm với ba candidate: quản lý tồn kho, tổng hợp deadline và phân loại phản ánh khách hàng.| Nhóm chọn candidate #1 — Quản lý tồn kho và hỗ trợ quyết định nhập hàng, đạt 32 điểm; hai candidate còn lại cùng đạt 28 điểm. |
| **Kiểm chứng / research** | Tôi sử dụng ChatGPT để tìm hiểu và tổng hợp các giải pháp đã có: Square for Retail, Zoho Inventory và Inventory Planner; đồng thời làm rõ vai trò của từng phần mềm trong quản lý tồn kho, cảnh báo thiếu hàng và dự báo nhu cầu. Tôi tham khảo kết quả phỏng vấn và poll được ghi trong báo cáo nhóm.| Kết quả research gợi ý rằng cập nhật tồn kho và cảnh báo có thể dùng Rule/Script; AI chỉ cần xem xét cho phần dự báo nhu cầu khi có đủ dữ liệu. |
| **Quy trình nhóm** | Tôi đối chiếu quy trình hiện tại và tương lai khi xây dựng phần Problem Statement: quy trình hiện tại 5 bước, khoảng 55 phút/tuần; quy trình tương lai dự kiến 5 bước, khoảng 16 phút/tuần. Tôi tìm hiểu vai trò của bước chủ cửa hàng duyệt bản nháp [DRAFT]. | Làm rõ bottleneck ở bước đối chiếu tồn kho với tốc độ bán (25 phút), điểm can thiệp của AI và ranh giới trách nhiệm của con người.|
| **Problem Statement** | Tôi sử dụng ChatGPT và bài mẫu VinUni để hỗ trợ xây dựng lại Problem Statement v1 từ Problem Statement v0, kết quả kiểm chứng, quy trình trước/sau và các phản biện đã ghi nhận. Tôi tập trung vào Success Metric, Boundary, AI intervention point và tiêu chí đánh giá. | Bản đề xuất v1 bổ sung cách xử lý dữ liệu khuyến mãi bất thường, làm rõ trách nhiệm phê duyệt của chủ cửa hàng và phân biệt các bước Rule, AI, con người. [Xác nhận với nhóm trước khi ghi rằng bản này đã được thông qua.] |
| **Mức can thiệp AI** | Tôi tìm hiểu sự khác nhau giữa Rule, Workflow và Agent; đồng thời làm rõ ý nghĩa của [DRAFT] và Human-in-the-loop. Tôi xem xét phương án Workflow kết hợp Rule/Script, AI dự báo và chủ cửa hàng phê duyệt. | Phương án đề xuất giúp AI hỗ trợ phân tích mà không tự đặt hàng hoặc thanh toán. Nhóm vẫn cần thống nhất chính thức mức can thiệp trong Mục 6. |
| **Quyết định** | Tôi xem xét các rủi ro liên quan đến giá trị sử dụng, có khả năng sử dụng, dữ liệu và chi phí triển khai. | Đây là cơ sở để nhóm tiếp tục đánh giá trong quá trình xây dựng. |
## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 Scan** | Tôi sử dụng ChatGPT để gợi ý thêm những khó khăn thường gặp khi mua hàng trực tuyến, bao gồm so sánh giá, thông số kỹ thuật và đánh giá sản phẩm. | Giúp tôi mở rộng các tình huống thực tế và chuyển vấn đề thành Job Story có actor, bối cảnh và dấu hiệu quan sát. | Một số ý tưởng trùng nhau về đối tượng hoặc bối cảnh. Số thứ tự của vấn đề được AI gợi ý cũng có lúc không thống nhất với bảng CP1 sau khi tôi thay đổi danh sách. | Tôi lựa chọn vấn đề phù hợp với trải nghiệm của mình và loại bỏ ý tưởng không muốn tiếp tục. Cần kiểm tra lại số thứ tự và bằng chứng thực tế trong bản cuối. |
| **CP2 Problem Card** | Tôi nhờ AI hỗ trợ xây dựng Problem Card, xác định quy trình hiện tại, bottleneck, impact, success metric và phương án không dùng AI. | Giúp tôi hiểu rõ các khái niệm Bottleneck, Success Metric và cách trình bày vấn đề theo mẫu báo cáo. | AI từng phân bổ thời gian cho từng bước khi chưa có số liệu đo thực tế. Một sơ đồ còn có tổng thời gian 28 phút, không khớp baseline 25 phút. | Tôi nhận diện được sự khác nhau giữa số liệu thực tế và số liệu AI ước lượng. |
| **CP4 Research** | Tôi sử dụng ChatGPT để tìm hiểu các giải pháp Square for Retail, Zoho Inventory và Inventory Planner, đồng thời so sánh các chức năng quản lý tồn kho, cảnh báo và dự báo nhu cầu. | Giúp tôi tổng hợp nhanh các giải pháp đã có và phân biệt tính năng có thể thực hiện bằng Rule với những phần có thể cân nhắc AI. | AI có thể mô tả chức năng công cụ ở mức khái quát mà chưa chứng minh hiệu quả trong cửa hàng cụ thể. AI cũng từng đưa ra câu nói phỏng vấn minh họa, không thể coi là trích dẫn nguyên văn thật. | Tôi yêu cầu giải thích nguồn link và phân biệt nghiên cứu tài liệu với bằng chứng phỏng vấn. |
| **CP5 Quy trình** | Tôi sử dụng ChatGPT để đối chiếu thông tin từ quy trình hiện tại và quy trình tương lai khi chuẩn bị Problem Statement. | Giúp tôi làm rõ bottleneck 25/55 phút, quy trình dự kiến 16 phút, bước nào là Rule, bước nào có AI và bước nào con người phải kiểm tra. | AI có thể trình bày thời gian kỳ vọng như thể đã đạt được, trong khi nhóm chưa thử nghiệm hệ thống thực tế. | Tôi phân biệt baseline với target trong bản nháp: 55 phút là mốc hiện tại của báo cáo, còn 16 phút là kỳ vọng cần kiểm chứng. |
| **CP5–6 Problem Statement** | Tôi cung cấp bài mẫu VinUni và báo cáo nhóm cho ChatGPT để hỗ trợ viết lại Mục 7 — Problem Statement v1 và tiêu chí đánh giá. | Giúp tôi liên kết Actor, Bottleneck, Impact, Success Metric, Boundary và AI intervention point; đồng thời làm rõ thay đổi từ v0 sang v1. | Một số đề xuất của AI chưa được nhóm xác nhận là quyết định cuối cùng. Việc đặt mục tiêu 80% hoặc chọn Workflow cũng không tự động có nghĩa nhóm đã kiểm chứng được hiệu quả. | Tôi yêu cầu bản v1 bám sát số liệu trong báo cáo nhóm, giữ mục tiêu thời gian dưới 20 phút và mục tiêu tồn đọng dưới 15%. |
| **CP6 Mức can thiệp / quyết định** | Tôi nhờ ChatGPT giải thích trạng thái [DRAFT], nguyên tắc Human-in-the-loop và vai trò của AI trong quy trình nhập hàng. | Giúp tôi hiểu rằng AI chỉ đưa ra đề xuất, còn chủ cửa hàng kiểm tra và quyết định có đặt hàng hay không. | AI có thể đề xuất Workflow trước khi nhóm hoàn thành việc so sánh bốn mức No AI, Rule, Workflow và Agent hoặc đánh giá đầy đủ rủi ro. | Tôi xem Workflow là phương án cần được nhóm đánh giá, không mặc định dùng AI cho mọi bước. |
## 6. Reflection (CP7)

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Qua phần trình bày và phản biện của các thành viên, tôi nhận thấy một vấn đề không nhất thiết phải phức tạp mới đáng giải quyết. Các bạn đưa ra nhiều vấn đề gần gũi như quản lý tồn kho, theo dõi deadline và phân loại phản ánh khách hàng. Điều tôi học được là cần xác định rõ người gặp khó khăn, quy trình hiện tại và tác động của vấn đề thay vì chỉ tập trung vào ý tưởng sử dụng AI. Khi lựa chọn một vấn đề trong tương lai, tôi sẽ ưu tiên những vấn đề có bằng chứng thực tế và có thể đo lường hiệu quả cải thiện.

### 6.2. Nhóm có lúc nào bị "solution-first" không? Lúc đó nhóm nhận ra và xử lý thế nào?

Theo tôi, nhóm có lúc nghĩ đến giải pháp trước khi hiểu đầy đủ vấn đề, đặc biệt là ý tưởng sử dụng Machine Learning để dự báo số lượng hàng cần nhập. Tuy nhiên, khó khăn chính của chủ cửa hàng là phải kiểm tra và đối chiếu dữ liệu tồn kho với tốc độ bán của nhiều mẫu quần áo, màu sắc và kích cỡ.

Sau khi nhận phản biện về các công cụ POS, Excel và quy tắc Min/Max, nhóm đã xem xét lại mức độ cần thiết của AI. Hướng tiếp cận được điều chỉnh thành sử dụng Rule cho các phép tính đơn giản và chỉ cân nhắc AI cho phần dự báo nhu cầu. Qua đó, tôi hiểu rằng cần tìm giải pháp phù hợp với vấn đề thay vì cố gắng sử dụng AI cho mọi công việc.

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Khi trình bày vấn đề đọc và tổng hợp đánh giá sản phẩm, tôi nhận được câu hỏi từ Nguyễn Tài Minh Huy về cách phân biệt đánh giá thật với các bình luận do bot hoặc spam tạo ra.

Ban đầu, tôi tập trung nhiều vào việc giảm thời gian đọc và tổng hợp ưu điểm, nhược điểm của sản phẩm. Câu hỏi này khiến tôi nhận ra rằng nếu dữ liệu đánh giá không đáng tin cậy thì AI có thể tổng hợp nhanh nhưng vẫn đưa ra kết quả sai lệch.

Tôi chưa thay đổi hoàn toàn ý tưởng ban đầu, nhưng nhận thấy cần bổ sung việc kiểm chứng độ tin cậy của dữ liệu trước khi đánh giá hiệu quả của giải pháp. Đây cũng là điểm tôi cần tiếp tục nghiên cứu nếu phát triển Problem Card này.

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?

Kết quả kiểm chứng của nhóm có một số điểm khiến tôi chú ý. Báo cáo ghi nhận 3 cuộc phỏng vấn và một khảo sát nhanh với 6 người. Trong đó, có người cho rằng Excel hoặc công thức Min/Max đã đủ để quản lý tồn kho đối với cửa hàng nhỏ.

Điều này cho thấy không phải người dùng nào cũng cần một hệ thống AI mới. Ngoài ra, trường hợp nhập 100 áo polo nhưng còn tồn 40 chiếc thuộc các màu và kích cỡ khó bán cũng thể hiện hậu quả của việc nhập hàng không phù hợp với nhu cầu.

Từ những kết quả này, tôi nhận thấy nhóm cần xác định rõ đối tượng sử dụng và kiểm chứng liệu AI có thực sự mang lại giá trị tốt hơn những công cụ đang có hay không.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Đối với tôi, phần khó nhất là xác định Bottleneck và xây dựng Success Metric phù hợp. Nếu chỉ mô tả rằng chủ cửa hàng gặp khó khăn khi quản lý tồn kho thì vấn đề vẫn còn quá rộng.

Trong báo cáo nhóm, quy trình hiện tại gồm 5 bước, mất khoảng 55 phút mỗi tuần. Trong đó, bước đối chiếu tồn kho với tốc độ bán và tính số lượng cần nhập mất khoảng 25 phút. Việc xác định được bước nghẽn này giúp nhóm tập trung vào đúng phần cần cải thiện.

Tôi cũng nhận thấy rằng giảm thời gian xử lý chưa đủ để đánh giá thành công. Hệ thống còn phải hạn chế nhập thừa, thiếu hàng và bảo đảm chủ cửa hàng có thể kiểm tra các đề xuất trước khi quyết định.

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Nếu được thực hiện lại, tôi sẽ ưu tiên thu thập thêm dữ liệu thực tế từ nhiều cửa hàng trước khi quyết định sử dụng AI. Tôi muốn kiểm tra thời gian quản lý tồn kho, số lượng mặt hàng thường bị nhập thừa và mức độ hiệu quả của những công cụ cửa hàng đang sử dụng.

Câu hỏi tôi muốn phản biện nhóm mạnh hơn là: **"Nếu Excel hoặc Rule-based đã có thể tính tốc độ bán và cảnh báo tồn kho, AI có cải thiện đủ nhiều để xứng đáng với chi phí và rủi ro bổ sung hay không?"**

Tôi cho rằng nhóm cần thử nghiệm và so sánh hai phương pháp trên cùng một bộ dữ liệu. Nếu AI không mang lại kết quả tốt hơn, việc sử dụng Rule-based sẽ đơn giản, dễ kiểm soát và phù hợp hơn với cửa hàng nhỏ.

### 6.7. Hiểu bài

Các nội dung cần giải thích:

- Vấn đề quản lý tồn kho và quyết định nhập hàng của cửa hàng quần áo.
- Quy trình hiện tại gồm 5 bước và Bottleneck nằm ở bước đối chiếu tồn kho với tốc độ bán.
- Cách đo hiệu quả dựa trên thời gian xử lý, tỷ lệ hàng tồn khó bán và tình trạng thiếu hàng.
- Ranh giới AI chỉ đề xuất, không tự đặt hàng hoặc thanh toán.
- Lý do lựa chọn Workflow kết hợp Rule, AI và sự phê duyệt của con người.
- Phương án quay về Rule-based khi AI đưa ra kết quả không đáng tin cậy.
- Quan điểm cá nhân về việc nên thử nghiệm tiếp, cần kiểm chứng thêm hay không nên triển khai AI.

## 7. Tài liệu tham khảo

-