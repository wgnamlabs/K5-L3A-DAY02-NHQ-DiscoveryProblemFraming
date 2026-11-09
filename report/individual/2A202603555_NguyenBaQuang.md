# Báo cáo cá nhân — Nguyễn Bá Quảng — 2A202603555

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Tôi phụ trách tìm hiểu công cụ và phản biện danh sách vấn đề. Ở CP5–CP6, tôi hỗ trợ phần chung theo [phân công nhóm](../../TEAM.md#phân-công-theo-checkpoint).

## 1. Thông tin học viên

- Họ tên: Nguyễn Bá Quảng
- MSSV: 2A202603555
- Tên nhóm: NHQ
- Link repo nhóm: https://github.com/wgnamlabs/K5-L3A-DAY02-NHQ-DiscoveryProblemFraming

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

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Ý 1 và 2 là phần tự scan ban đầu; ý 3, 4, 5, 6 là AI gợi ý thêm.
- Tôi chọn ý 4 và 5 vào top 3 vì dễ mô tả các bước đang làm và xác định phần cần cải thiện.
- Tôi chưa chọn ý 3 vì chưa biết thực tế mất bao lâu để trả lời khách. Ý 6 còn quá rộng, chưa rõ ai dùng và cần tổng hợp báo cáo gì.
- Các ý AI gợi ý vẫn cần hỏi người thực sự gặp vấn đề. Những con số này chưa được đo; riêng mốc 10–20 tin nhắn/ngày ở ý 3 chưa có nguồn xác nhận.

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
| Thời điểm / bối cảnh | Trước buổi học đầu tiên, có mục tiêu nhưng chưa biết chọn tài liệu và kiến thức cần biết trước. Phạm vi là một chủ đề. |
| Quy trình hiện tại (3–7 bước) | Xác định mục tiêu → tìm tài liệu → đọc và đối chiếu → sắp xếp thứ tự → chốt kế hoạch. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: đọc lướt, so sánh độ phù hợp và nội dung trùng giữa nhiều tài liệu — tạm tính 60 phút/lần. |
| Impact (nếu không giải thì sao) | Mất 2–3 tiếng, làm chậm thời điểm bắt đầu học; có nguy cơ chọn tài liệu quá khó hoặc học trùng. |
| Success metric (baseline → target) | Tạm lấy 150 phút/lần → mục tiêu ≤60 phút/lần. Bấm giờ từ lúc xác định mục tiêu đến khi chốt kế hoạch ở 3 lần chuẩn bị trước và 3 lần thử cách mới; sau buổi học đầu ghi nội dung phải đổi do thiếu kiến thức nền để kiểm tra chất lượng. |
| Phương án không dùng AI | Dùng đề cương có sẵn, ghi mục tiêu và kiến thức cần biết trước, rồi so sánh tài liệu. Có thể nhờ người đã học xem lại thứ tự học. |
| Giả thuyết về AI (nếu có) | Hỗ trợ so sánh mục lục và đề xuất thứ tự từ tài liệu được cung cấp; người học kiểm tra nguồn và tự chốt. Chỉ thử khi cách không dùng AI chưa đủ. |
| Cảm nhận nhanh | Chưa biết; thử No AI trước. |

Quy trình nháp hiện tại:

```text
[1. Xác định mục tiêu và kiến thức hiện có: 15 phút]
→ [2. Tìm và gom tài liệu: 40 phút]
→ [3. Đọc lướt, đối chiếu độ phù hợp/trùng lặp: 60 phút] ← BOTTLENECK
→ [4. Sắp xếp nội dung và kiến thức cần biết trước: 25 phút]
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
| Phương án không dùng AI | Gom việc vào một danh sách có link nguồn, thống nhất nơi cập nhật hạn và kiểm tra lại vào đầu ngày. |
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
- Vì sao: dễ thu hẹp vào một chủ đề và tự ghi thời gian để kiểm chứng.
- Câu hỏi muốn nhóm phản biện: **Nếu dùng đề cương có sẵn và danh sách cần kiểm tra đã giảm thời gian chuẩn bị, phần khó nào còn lại cần hỗ trợ thêm, và làm sao biết kế hoạch nhanh hơn vẫn phù hợp với người học?**

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Các nhóm “người tự học”, “nhân viên, quản lý” và “sales, chủ cửa hàng” bao gồm nhiều vai trò có cách làm khác nhau. | Đồng ý. Cần chọn một vai trò và một tình huống cho mỗi card. | Giới hạn ba card: sinh viên chuẩn bị học một chủ đề; nhân viên lập danh sách việc cá nhân đầu ngày từ 2–3 nguồn; sales lập một báo giá khoảng 5 mã sản phẩm có sẵn. |
| Các mốc 150 phút/lần chuẩn bị học, 20 phút/ngày tổng hợp việc và 30 phút/báo giá chưa được bấm giờ. | Đồng ý. Đây là số ước lượng để lập bản nháp. | Ghi rõ nhãn ước lượng ở từng quy trình; bổ sung cách bấm giờ từng bước trên 3 lần chuẩn bị học, 5 ngày làm việc và 5 báo giá trước khi thử cách mới. |
| Chỉ đo thời gian sẽ không phát hiện lộ trình thiếu kiến thức nền, danh sách bỏ sót việc đến hạn hoặc báo giá sai. | Đồng ý. Mỗi card cần kiểm tra cả thời gian và chất lượng. | Với lộ trình: ghi nội dung phải đổi do thiếu kiến thức nền sau buổi học đầu. Với danh sách việc: cuối ngày đối chiếu nguồn và đếm việc đến hạn bị bỏ sót. Với báo giá: kiểm tra từng mã, số lượng, giá và thời điểm cập nhật tồn kho trước khi gửi. |
| Chưa so sánh với đề cương, danh sách việc tập trung và bảng tra cứu có công thức trước khi đề xuất AI. | Đồng ý. Cần thử các phương án này trước để biết bước nào còn khó. | Thêm phương án dùng đề cương và danh sách cần kiểm tra cho việc học; danh sách việc trung tâm có link nguồn cho công việc đầu ngày; mẫu báo giá có công thức tra cứu và tính tiền cho sales. Chỉ cân nhắc AI nếu vẫn tốn thời gian so sánh tài liệu, đọc cập nhật dạng văn bản hoặc ghép mô tả sản phẩm với mã hàng. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đưa ra ba vấn đề: chuẩn bị lộ trình học, tổng hợp việc ưu tiên đầu ngày và tra cứu dữ liệu để báo giá. | Ba vấn đề được ghi ở mục 2.1 báo cáo nhóm; mỗi candidate có actor và bottleneck riêng. |
| Phản biện bài của bạn khác | Hỏi vấn đề tìm phiên bản tài liệu: “Nếu chỉ dùng một file Google Docs chung thì vấn đề này còn không?”; hỏi vấn đề đọc bài báo: “Nếu đọc Abstract và Conclusion trước thì có đủ để đánh giá bài báo không?” | Giúp nhóm xem cách làm đơn giản có đủ giải quyết vấn đề chưa. Các câu hỏi được ghi ở mục 2.1 báo cáo nhóm. |
| Nhận phản biện | Nam hỏi liệu đề cương và danh sách cần kiểm tra có đủ cho việc chuẩn bị học; Hiệp hỏi việc tổng hợp đầu ngày có trùng với tổng hợp từ Zalo; Nam hỏi liệu bảng giá/tồn kho đồng bộ có đủ cho báo giá. | Các card CP2 hiện ghi rõ phương án No AI, thu hẹp actor và phạm vi; các số thời gian vẫn là ước lượng cần đo. Shortlist chỉ ra vấn đề công việc đầu ngày còn thiếu bằng chứng về pain. |
| Gom cluster / cây OST | Cùng Nam gom các vấn đề có điểm giống nhau theo phân công CP3. | Các candidate của tôi thuộc cluster A (kiến thức), B (công việc/deadline), C (tra cứu/xác minh); cây OST là sản phẩm chung, Nam phụ trách chính (mục 2.2–2.3). |
| Chọn candidate problem | Cùng nhóm so sánh các vấn đề: ai gặp, đang làm thế nào, có bằng chứng gì, ảnh hưởng ra sao và có làm được trong buổi lab không. | Vấn đề công việc đầu ngày đạt 27/35; nhóm chọn tìm đúng phiên bản tài liệu, đạt 33/35. Đây là quyết định chung (mục 2.4). |
| Kiểm chứng / research | Phụ trách research Google Docs — Version History, Google Drive — Manage Versions và OneDrive — Version History, có Hiệp hỗ trợ; hỗ trợ phần kiểm chứng do Hiệp phụ trách. | Tổng hợp ba công cụ, link, bước được hỗ trợ, điểm mạnh, giới hạn và bài học tại mục 3.3. Hiệp phụ trách chính phần phỏng vấn ở mục 3.2. |
| Quy trình nhóm | Đóng góp kết quả tìm hiểu công cụ cho phần CP5 do Nam phụ trách: thống nhất nguồn chung, liên kết cố định và người xác nhận bản chính thức. | Hỗ trợ phương án quy trình tương lai ở mục 4; phần gom/ghép nội dung và định dạng nằm ngoài đợt thử tìm đúng phiên bản. |
| Problem Statement | Hỗ trợ Nam ở CP5–CP6, góp ý công cụ làm được gì và phần nào vẫn cần người kiểm tra. | Problem Statement v1 giữ mục tiêu xác định đúng phiên bản dưới 5 phút/lần, có người xác nhận khi mâu thuẫn; không tự xóa, ghi đè hay khôi phục file (mục 5 và 7). |
| Mức can thiệp AI | Dùng kết quả tìm hiểu công cụ hỗ trợ nhóm so sánh No AI / Rule / Workflow / Agent. | Nhóm chọn No AI để thử nghiệm: sửa quy trình và dùng tính năng sẵn có; chưa đủ bằng chứng cần xây AI riêng (mục 6). |
| Quyết định | Cùng nhóm thảo luận quyết định CP6 theo bốn rủi ro. | Go với đợt thử không dùng AI trong 2 tuần; No-Go với hệ thống AI riêng ở giai đoạn hiện tại. Pilot cần tối thiểu 5 case hợp lệ; chọn nhầm bản phải rà soát quy tắc trước khi tiếp tục (mục 8). |

Bằng chứng đối chiếu: [TEAM.md](../../TEAM.md), [báo cáo nhóm](../team/group_report.md). Baseline 18 phút/5 file và bước đối chiếu 7 phút thuộc trường hợp của Nam; đây không phải số liệu do tôi tự đo. Các mốc 150–180 phút trong phỏng vấn đo cả gom và hoàn thiện tài liệu, không dùng thay baseline xác định phiên bản.

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm ví dụ về các khó khăn lặp lại sau phần tự scan; các ý giữ lại là 3, 4, 5, 6. | Mở rộng các bối cảnh CSKH, công việc, báo giá và tổng hợp báo cáo. | Chưa có bằng chứng xác nhận pain; actor ở một số ý quá rộng. | Chọn ý 4 và 5 để đào sâu; phân biệt gợi ý với trải nghiệm/số liệu đã xác nhận. |
| CP2 Problem Card | Phản biện actor, baseline, metric và phương án không dùng AI theo bảng phản biện ở mục 3. | Chỉ ra actor rộng, số liệu chưa đo và metric chỉ xét tốc độ. | Các mốc thời gian nháp không thể được xem là dữ liệu thực nghiệm. | Thu hẹp mỗi card vào một tình huống; ghi nhãn ước lượng, bổ sung cách đo và kiểm tra chất lượng; so sánh No AI trước. |
| CP4 Research | Chưa ghi rõ có dùng AI ở bước này hay không. | Cần bổ sung nếu có dùng. | Chưa có ghi chép. | Cần ghi lại đúng cách mình đã làm. |
| CP5 Quy trình | Chưa ghi rõ có dùng AI ở bước này hay không. | Cần bổ sung nếu có dùng. | Chưa có ghi chép. | Tôi hỗ trợ phần chung, Nam phụ trách chính. |
| CP5–6 Problem Statement | Chưa ghi rõ có dùng AI ở bước này hay không. | Cần bổ sung nếu có dùng. | Chưa có ghi chép. | Nếu có dùng, ghi câu hỏi phản biện và thay đổi do nhóm tự chốt. |
| CP6 Mức can thiệp / quyết định | Chưa ghi rõ có dùng AI ở bước này hay không. | Cần bổ sung nếu có dùng. | Chưa có ghi chép. | Nhóm chọn cách làm không dùng AI để thử nghiệm. Việc dùng AI hỗ trợ làm báo cáo cần ghi riêng. |
| Rà soát báo cáo cá nhân | Nhờ Codex so lại phần việc với TEAM.md và báo cáo nhóm, sửa câu chữ cho dễ đọc. | Làm rõ phần phụ trách, phần hỗ trợ và nguồn số liệu. | Không xác nhận được trải nghiệm cá nhân hoặc lịch sử dùng AI chưa được ghi lại. | Các nội dung cần xác nhận được đánh dấu; AI có đưa gợi ý Reflection theo yêu cầu, cá nhân cần tự viết lại trước khi nộp. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua các vấn đề của nhóm, tôi thấy cần nói rõ ai đang gặp khó khăn và khó ở bước nào. Ví dụ, Nam có trường hợp mất 18 phút để kiểm tra 5 file. Còn vấn đề tổng hợp việc đầu ngày của tôi mới chỉ nói là phải xem nhiều nguồn, chưa có số liệu rõ. Một việc nghe có vẻ phiền vẫn cần được kiểm tra xem nó xảy ra thường xuyên không và mất bao nhiêu thời gian.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong báo cáo nhóm có các ý như làm chatbot tổng hợp tài liệu hay ứng dụng AI quản lý deadline. Đây là những cách giải quyết, nên chưa phù hợp để đưa vào cây vấn đề. Điều cần làm trước là hỏi người dùng đang vướng ở đâu. Với bài của nhóm, câu hỏi dùng chung một file Google Docs có đủ không giúp xem lại việc có cần AI hay chưa.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Với việc chuẩn bị học kiến thức mới, Nam hỏi dùng đề cương có sẵn và danh sách việc cần kiểm tra đã đủ chưa. Từ câu hỏi này, hướng tôi muốn thử trước là dựa vào một đề cương, xem mình còn thiếu kiến thức gì rồi chọn tài liệu. Nếu làm vậy vẫn mất nhiều thời gian so sánh tài liệu thì mới tính đến AI. Tôi cần tự xác nhận lại đây là lần mình đổi ý hay chỉ làm rõ cách làm.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Một trường hợp đáng chú ý là người được hỏi gần như không gặp khó khăn vì nhóm đã có thư mục chung và quy tắc từ đầu. Điều này cho thấy có thêm công cụ chưa chắc đã giải quyết được vấn đề; cách mọi người dùng công cụ cũng quan trọng. Dù có file chung, nếu thành viên vẫn sửa bản riêng thì vẫn dễ nhầm. Nhóm cần thử thực tế để biết mọi người có làm theo quy tắc hay không.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điểm tôi muốn làm rõ là đang đo phần việc nào. Thời gian 150–180 phút trong phỏng vấn gồm cả gom nội dung và sửa định dạng. Còn 18 phút trong trường hợp của Nam là thời gian tìm đúng phiên bản. Không thể lấy hai số này để so trực tiếp với nhau. Nam phụ trách chính phần Problem Statement; tôi hỗ trợ từ kết quả tìm hiểu công cụ và góp ý phần nào nằm trong phạm vi thử nghiệm.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi muốn đo thời gian cho vấn đề của mình sớm hơn. Chẳng hạn, với việc tổng hợp công việc đầu ngày, tôi sẽ ghi lại trong 5 ngày xem mất bao lâu và có bỏ sót việc nào không. Khi góp ý cho nhóm, tôi muốn hỏi rõ hơn số liệu lấy từ đâu và đang đo bước nào. Khi tìm hiểu công cụ, tôi cũng muốn ghi cụ thể công cụ giúp được việc gì và việc gì vẫn cần người xác nhận.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

*Gợi ý ôn tập; cần tự viết lại khi đóng tài liệu:*

Nhóm chọn vấn đề tìm đúng bản tài liệu khi có nhiều file được gửi riêng. Cách thử là dùng một nguồn chung, ghim link và kiểm tra với người phụ trách khi chưa rõ bản nào đúng. Mục tiêu là từ trường hợp ban đầu mất 18 phút xuống dưới 5 phút mỗi lần và không chọn nhầm file. Nhóm chỉ thử phần tìm đúng phiên bản, chưa làm phần ghép nội dung hay sửa định dạng, cũng không tự động xóa hoặc ghi đè file. Nhóm chọn No AI vì muốn thử cách làm đơn giản với công cụ đang có trước. Nhóm sẽ thử trong 2 tuần với ít nhất 5 trường hợp, chưa xây hệ thống AI riêng. Nếu chọn nhầm file thì phải xem lại quy tắc trước khi tiếp tục; sau đợt thử, nếu ít nhất 3/5 trường hợp vẫn mất từ 5 phút trở lên thì dừng để đánh giá lại cách làm.

---

## 7. Tài liệu tham khảo

- [Phân công và mô tả đóng góp của nhóm](../../TEAM.md).
- [Báo cáo nhóm NHQ](../team/group_report.md), mục 2–8: pitch, shortlist, kiểm chứng, research, quy trình và quyết định chung.
- [Worksheet Day 02](../../docs/01-worksheet.md): cấu trúc Problem Card, quy trình và tiêu chí đánh giá.
- [Quy định sử dụng AI và liêm chính](../../RULES.md), mục 2–4.
- Các nguồn công cụ được dẫn trong bảng research tại [mục 3.3 báo cáo nhóm](../team/group_report.md#33-research-giải-pháp-đã-có); cần tự mở và kiểm tra trước khi xác nhận đã kiểm chứng nguồn.
