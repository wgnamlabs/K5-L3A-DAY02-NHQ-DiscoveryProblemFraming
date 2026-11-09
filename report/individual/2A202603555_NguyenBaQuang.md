# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Bá Quảng
- MSSV: 2A202603555
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NHQ
- Link repo nhóm:https://github.com/wgnamlabs/K5-L3A-DAY02-NHQ-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian |Khi bắt đầu code dự án tôi muốn biết được trong nhóm ai vừa push code lên và push lên nhánh nào để tôi không phải đi hỏi hoặc đi tìm tin nhắn thông báo của mọi người  |Team |5-10 phút / ngày |
| 2 |Tốn thời gian |Khi bắt đầu học một kiến thức mới, tôi muốn xác định những nội dung cần học và sắp xếp chúng theo thứ tự phù hợp, để tránh học lan man, trùng lặp và mất thời gian tìm kiếm tài liệu|Sinh viên, người tự học, người đi làm cần học kỹ năng mới|2-3 tiếng/lần |
| 3 |Lặp lại |Khi nhận được những câu hỏi giống nhau từ khách hàng, tôi muốn có sẵn câu trả lời chính xác, để không phải giải thích nhiều lần |Nhân viên bán hàng, CSKH |10-20 tin nhắn/ngày |
| 4 |Lặp lại |Khi bắt đầu ngày làm việc, tôi muốn biết các công việc cần ưu tiên và deadline sắp tới, để không phải kiểm tra từng ứng dụng |Nhân viên, quản lý |Phải đi tìm hoặc đọc 2,3 nguồn để check |
| 5 |Tốn thời gian |Khi chuẩn bị báo giá cho khách hàng, tôi muốn nhanh chóng có thông tin sản phẩm, giá và tồn kho, để phản hồi khách kịp thời |Sales, chủ cửa hàng |Phải tra cứu nhiều mã sản phẩm, kiểm tra tồn kho và tính giá bằng tay |
| 6 |Cần tổng hợp nhiều thông tin |Khi cần đưa ra quyết định, tôi muốn có bản tổng hợp từ nhiều báo cáo và nguồn dữ liệu, để hiểu tình hình mà không phải đọc từng nguồn riêng lẻ. |CEO, Manager, PM |Dữ liệu nằm ở nhiều dashboard, báo cáo Excel và tài liệu khác nhau. |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- ý 3, 4, 5, 6 là AI gợi ý

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Xác định nội dung và thứ tự học kiến thức mới | 2–3 tiếng/lần; dễ thu hẹp vào một chủ đề để đo và kiểm chứng. | Chưa rõ thời gian nằm ở tìm tài liệu hay sắp xếp nội dung. |
| 2 | Tổng hợp công việc ưu tiên và deadline | Lặp lại đầu ngày, phải kiểm tra 2–3 nguồn; có thể đo thời gian tổng hợp. | Cần xác nhận nguồn đang dùng, tần suất và số việc bỏ sót. |
| 3 | Tra thông tin sản phẩm, giá và tồn kho để báo giá | Đầu vào/đầu ra rõ, đo được thời gian và lỗi báo giá. | Chưa rõ số mã mỗi báo giá và mức độ cập nhật của dữ liệu. |

### Problem Card #1 — CP1 #2: Chuẩn bị lộ trình học

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu học một kiến thức mới, tôi muốn xác định nội dung cần học và thứ tự phù hợp, để tránh học lan man, trùng lặp và mất thời gian tìm kiếm tài liệu. |
| Actor | Sinh viên tự học một chủ đề mới phục vụ môn học hoặc dự án. |
| Thời điểm / bối cảnh | Trước buổi học đầu tiên, có mục tiêu nhưng chưa biết chọn tài liệu và kiến thức tiên quyết. Phạm vi là một chủ đề. |
| Quy trình hiện tại (3–7 bước) | Xác định mục tiêu → tìm tài liệu → đọc và đối chiếu → sắp xếp thứ tự → chốt kế hoạch. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: đọc lướt, so sánh độ phù hợp và nội dung trùng giữa nhiều tài liệu — tạm tính 60 phút/lần. |
| Impact (nếu không giải thì sao) | Mất 2–3 tiếng chuẩn bị mỗi lần theo CP1, làm chậm thời điểm bắt đầu học; có nguy cơ chọn tài liệu quá khó hoặc học trùng. |
| Success metric (baseline → target) | Tạm lấy 150 phút/lần, nằm trong khoảng CP1 → mục tiêu ≤60 phút/lần. Bấm giờ từ lúc xác định mục tiêu đến khi chốt kế hoạch ở 3 lần chuẩn bị trước và 3 lần thử cách mới; sau buổi học đầu ghi nội dung phải đổi do thiếu kiến thức nền để kiểm tra chất lượng. |
| Phương án không dùng AI | Dùng một syllabus làm khung, checklist mục tiêu và kiến thức đầu vào, bảng so sánh tài liệu; nhờ người đã học kiểm tra thứ tự. |
| Giả thuyết về AI (nếu có) | Hỗ trợ so sánh mục lục và đề xuất thứ tự từ tài liệu được cung cấp; người học kiểm tra nguồn và tự chốt. Chỉ thử khi cách không dùng AI chưa đủ. |
| Cảm nhận nhanh | Chưa biết; thử No AI trước. |

Quy trình nháp hiện tại:

```text
[1. Xác định mục tiêu và kiến thức hiện có: 15 phút]
→ [2. Tìm và gom tài liệu: 40 phút]
→ [3. Đọc lướt, đối chiếu độ phù hợp/trùng lặp: 60 phút] ← BOTTLENECK
→ [4. Sắp xếp nội dung và kiến thức tiên quyết: 25 phút]
→ [5. Chốt tài liệu và kế hoạch học: 10 phút]

Tổng nháp: 150 phút/lần;
```

### Problem Card #2 — CP1 #4: Tổng hợp việc ưu tiên đầu ngày

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu ngày làm việc, tôi muốn biết công việc cần ưu tiên và deadline sắp tới, để bắt đầu đúng việc mà không phải kiểm tra từng ứng dụng nhiều lần. |
| Actor | Nhân viên tự quản lý công việc cá nhân nằm ở 2–3 nguồn. |
| Thời điểm / bối cảnh | Đầu ngày, cần đối chiếu danh sách việc, lịch và tin nhắn cập nhật; chưa bao gồm phân công cho cả nhóm. |
| Quy trình hiện tại (3–7 bước) | Mở các nguồn → ghi việc và hạn → đối chiếu cập nhật → xếp ưu tiên → ghi danh sách hôm nay. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: đối chiếu việc trùng, trạng thái và deadline mới nhất giữa các nguồn — tạm tính 8 phút/ngày. |
| Impact (nếu không giải thì sao) | Tạm tính mất 20 phút mỗi ngày tổng hợp; có nguy cơ ưu tiên theo thông tin cũ hoặc bỏ sót việc đến hạn. Chưa có bằng chứng đã trễ deadline. |
| Success metric (baseline → target) | Baseline nháp 20 phút/ngày → mục tiêu ≤10 phút/ngày. Ghi thời gian trong 5 ngày hiện tại và 5 ngày thử cách mới; cuối ngày đối chiếu nguồn để đếm việc đến hạn bị bỏ sót. Thời gian giảm nhưng số việc bỏ sót không được tăng. |
| Phương án không dùng AI | Một danh sách việc trung tâm có link nguồn; quy ước nơi cập nhật deadline; checklist rà soát đầu ngày và bộ lọc theo hạn/trạng thái. |
| Giả thuyết về AI (nếu có) | Nếu cập nhật chủ yếu là văn bản tự do, hỗ trợ trích việc/deadline kèm nguồn thành nháp. Người dùng xác nhận ngày mơ hồ và tự quyết ưu tiên; không tự đổi deadline. |
| Cảm nhận nhanh | No AI / Rule trước; chưa đủ bằng chứng cần Workflow. |

Quy trình nháp hiện tại:

```text
[1. Mở 2–3 nguồn công việc: 2 phút]
→ [2. Ghi việc và deadline: 5 phút]
→ [3. Đối chiếu trùng lặp, trạng thái và hạn mới nhất: 8 phút] ← BOTTLENECK
→ [4. Xếp thứ tự ưu tiên: 3 phút]
→ [5. Ghi danh sách việc hôm nay kèm nguồn: 2 phút]

Tổng nháp: 20 phút/ngày;
```

### Problem Card #3 — CP1 #5: Tra cứu dữ liệu để báo giá

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị báo giá cho khách hàng, tôi muốn nhanh chóng xác định đúng thông tin sản phẩm, giá áp dụng và tồn kho, để phản hồi khách kịp thời và chính xác. |
| Actor | Nhân viên sales trực tiếp lập báo giá từ danh mục sản phẩm, bảng giá và dữ liệu tồn kho. |
| Thời điểm / bối cảnh | Nhận yêu cầu khoảng 5 mã sản phẩm có sẵn cùng số lượng; chưa xét hàng đặt riêng hoặc chiết khấu ngoại lệ. |
| Quy trình hiện tại (3–7 bước) | Đọc yêu cầu → xác định mã → tra giá/tồn kho → tính tiền, điền mẫu → kiểm tra và gửi. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: tra và đối chiếu giá áp dụng, tồn kho từng mã giữa các nguồn — tạm tính 12 phút/báo giá 5 mã. |
| Impact (nếu không giải thì sao) | Tạm tính 30 phút/báo giá; thao tác thủ công có nguy cơ nhầm mã, giá hoặc dùng tồn kho cũ, làm chậm phản hồi. Chưa có số lỗi hay doanh thu mất được xác nhận. |
| Success metric (baseline → target) | Baseline nháp 30 phút/báo giá 5 mã → mục tiêu ≤15 phút. Đo 5 báo giá quy mô tương đương trước và sau thử nghiệm; tách thời gian thao tác và chờ xác nhận. Kiểm tra toàn bộ mã, số lượng, giá và thời điểm dữ liệu tồn kho trước khi gửi. |
| Phương án không dùng AI | Chuẩn hóa mã; thống nhất nguồn giá/tồn kho có thời điểm cập nhật; dùng mẫu báo giá, công thức tra cứu và tính tiền; sales xử lý dữ liệu thiếu hoặc mâu thuẫn. |
| Giả thuyết về AI (nếu có) | Có thể hỗ trợ ghép mô tả tự do với mã sản phẩm, sales xác nhận lại. Giá/tồn kho phải lấy từ nguồn được duyệt; không tự suy đoán hoặc tự gửi báo giá. |
| Cảm nhận nhanh | No AI / Rule trước; chưa có cơ sở cần Agent. |

Quy trình nháp hiện tại:

```text
[1. Đọc yêu cầu và số lượng: 3 phút]
→ [2. Xác định mã sản phẩm và thông số: 5 phút]
→ [3. Tra giá áp dụng và tồn kho từng mã: 12 phút] ← BOTTLENECK
→ [4. Tính thành tiền và điền mẫu báo giá: 6 phút]
→ [5. Kiểm tra và gửi khách: 4 phút]

Tổng nháp: 30 phút/báo giá khoảng 5 mã;
```

### Card muốn pitch nhất

- Card số: **#1 — CP1 #2: Chuẩn bị lộ trình học.**
- Vì sao: Đã có dấu hiệu thời gian ở CP1, dễ thu hẹp vào một chủ đề và tự ghi thời gian để kiểm chứng.
- Câu hỏi muốn nhóm phản biện: **Nếu dùng syllabus có sẵn và checklist đã giảm thời gian chuẩn bị, phần khó nào còn lại cần hỗ trợ thêm, và làm sao biết kế hoạch nhanh hơn vẫn phù hợp với người học?**

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor còn quá rộng, dễ gộp nhiều quy trình khác nhau. | Chờ học viên xác nhận. | Bản nháp thu hẹp thành sinh viên học một chủ đề, nhân viên tổng hợp việc cá nhân và sales báo giá khoảng 5 mã. |
| Số phút chưa đo dễ bị hiểu thành bằng chứng thật, nhất là #4 và #5 vốn là gợi ý AI. | Chờ học viên xác nhận. | Gắn nhãn số tạm, phân biệt dữ liệu CP1 với ước lượng và thêm cách đo. |
| Chỉ giảm thời gian có thể làm kế hoạch kém phù hợp, bỏ sót việc hoặc báo giá sai. | Chờ học viên xác nhận. | Thêm kiểm tra chất lượng đi cùng metric thời gian ở cả ba card. |
| Chưa chứng minh cần AI. | Chờ học viên xác nhận. | Bổ sung phương án No AI/Rule và giữ vai trò AI ở mức giả thuyết cần kiểm chứng. |

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
