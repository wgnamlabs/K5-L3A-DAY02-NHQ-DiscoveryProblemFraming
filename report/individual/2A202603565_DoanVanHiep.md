# Báo cáo cá nhân — 2A202603565_DoanVanHiep

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:Đoàn Văn Hiệp
- MSSV:2A202603565
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:NHQ
- Link repo nhóm:https://github.com/wgnamlabs/K5-L3A-DAY02-NHQ-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | **Lặp lại** | Khi bắt đầu ngày làm việc lúc 8h sáng, tôi muốn lọc và tổng hợp các đầu việc từ các nhóm chat Zalo, để lên kế hoạch trong ngày và không bị bỏ sót việc quan trọng. | Bản thân, đồng nghiệp/nhóm làm việc | Mất 15–20 phút mỗi sáng (5 ngày/tuần). Tuần trước từng bị trễ 1 task do tin nhắn giao việc bị trôi trong group chat đông người. |
| 2 | **Tốn thời gian** | Khi tiếp cận một bài báo khoa học mới (10–15 trang), tôi muốn nắm nhanh phương pháp chính, đóng góp mới và kết quả thực nghiệm, để đánh giá bài này có liên quan đến đề tài hay không trước khi dành thời gian đọc sâu. | Bản thân, nhóm nghiên cứu | Mất 2–3 tiếng mỗi ngày để đọc 1–2 bài báo. Khoảng 40% số bài sau khi đọc xong mới thấy không áp dụng được vào bài toán của mình. |
| 3 | **Cần đọc, tổng hợp nhiều thông tin** | Khi chuẩn bị một hướng nghiên cứu mới, tôi muốn tìm và đối chiếu nhanh các công trình tương tự đã công bố, để xác định bài toán đã có ai làm chưa và tìm ra điểm mới (novelty) của mình. | Bản thân, người hướng dẫn | Mất từ 3–5 ngày tìm kiếm trên Google Scholar/arXiv cho mỗi đề tài mới. Từng tốn 1 tuần làm thử nghiệm mới phát hiện một nhóm khác đã công bố giải pháp tương tự. |
| 4 | **Pain từ người khác** | Khi chuẩn bị họp tiến độ định kỳ với người hướng dẫn / trưởng nhóm, tôi muốn tổng hợp các thử nghiệm đã chạy và chỉ số đạt được thành bản tóm tắt ngắn, để buổi họp đi thẳng vào vấn đề và nhận phản hồi nhanh. | Bản thân, người hướng dẫn (mentor) | Mất 45–60 phút chuẩn bị trước mỗi buổi họp tuần. Thầy/mentor từng nhắc nhở vì báo cáo dài dòng, thiếu bảng so sánh số liệu trực quan. |
| 5 | **Lặp lại** | Khi viết bài báo cáo môn học / bài báo khoa học, tôi muốn trích dẫn và định dạng danh mục tài liệu tham khảo (BibTeX/APA) chuẩn xác, để không bị giảng viên trừ điểm lỗi định dạng văn bản. | Bản thân, bạn cùng nhóm | Mất 30–45 phút mỗi lần nộp bài chỉ để chuẩn hóa citation và định dạng; từng bị trừ 0.5 điểm bài tập nhóm do trích dẫn sai quy chuẩn. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tự scan trước 4 bài toán từ trải nghiệm cá nhân (#1, #2, #3, #5).
- Dùng AI gợi ý thêm bài toán #4 (chuẩn bị báo cáo tiến độ tuần)
- Bỏ qua gợi ý của AI về *"Tự động viết code sinh mô hình AI"* và *"Tự động theo dõi log server"* vì phạm vi quá rộng hoặc quy trình chưa đủ ổn định.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lọc và tổng hợp đầu việc từ Zalo (#1) | Quy trình lặp lại mỗi ngày, có baseline đo được (15–20 phút), impact rõ (tránh sót việc) | Độ chính xác khi phân biệt giữa tin nhắn trò chuyện và tin nhắn giao việc thật |
| 2 |Tóm tắt nhanh bài báo khoa học (#2) | Nỗi đau tốn thời gian rất lớn (2–3 tiếng/ngày), quy trình đọc tài liệu rõ ràng | Tiêu chí tóm tắt thế nào là đủ tin cậy để không bỏ sót thông tin quan trọng |
| 3 | Đối chiếu công trình nghiên cứu trước đây (#3) | Tránh rủi ro làm trùng đề tài đã có người giải quyết, tiết kiệm nhiều ngày công | Khó bao quát hết mọi hội thảo/tạp chí nếu chỉ dựa vào từ khóa cơ bản |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu ngày làm việc lúc 8h sáng, tôi muốn lọc và tổng hợp các đầu việc từ các nhóm chat Zalo, để lên kế hoạch trong ngày và không bị bỏ sót việc quan trọng |
| Actor | Bản thân (nhân viên / sinh viên làm dự án nhóm) |
| Thời điểm / bối cảnh | 8h00–8h30 sáng mỗi ngày làm việc, khi mở máy tính bắt đầu ngày mới |
| Quy trình hiện tại (3–7 bước) | 1. Mở app Zalo (1') · 2. Lướt qua 5–7 nhóm chat công việc (5') · 3. Đọc từng đoạn chat để nhặt ra câu giao việc, hạn chót (10') · 4. Ghi chép đầu việc ra sổ tay hoặc app To-do (3') · 5. Sắp xếp thứ tự ưu tiên các việc trong ngày (2') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Đọc từng đoạn chat để tìm câu giao việc (mất ~10 phút), do tin giao việc nằm lẫn trong tin nhắn tán gẫu, thảo luận, icon |
| Impact (nếu không giải thì sao) | Dễ bỏ sót việc gấp; tuần trước từng bị trễ 1 đầu việc quan trọng gây ảnh hưởng tiến độ chung của nhóm |
| Success metric (baseline → target) | Baseline: mất 20–25 phút/sáng, sót 1 việc/tuần → Target: dưới 5 phút/sáng, 0 việc bị sót |
| Phương án không dùng AI | Thống nhất quy ước nhóm: khi giao việc bắt buộc tag @tên + dùng tính năng "Nhắc hẹn / Giao việc" có sẵn trong Zalo |
| Giả thuyết về AI (nếu có) | Dùng mô hình trích xuất (information extraction) nhận diện các câu mang tính hành động (action items) và deadline từ đoạn chat |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[1. Mở Zalo] (1')
       │
       ▼
[2. Lướt qua 5-7 nhóm chat công việc] (5')
       │
       ▼
[3. Đọc từng đoạn chat để tìm câu giao việc/deadline] (10')  <-- BOTTLENECK (tin trôi, lẫn chuyện phiếm)
       │
       ▼
[4. Ghi chép đầu việc ra sổ tay/app To-do] (3')
       │
       ▼
[5. Sắp xếp thứ tự ưu tiên các việc trong ngày] (2')

Tổng thời gian: ~21 phút
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp cận một bài báo khoa học mới (10–15 trang), tôi muốn nắm nhanh phương pháp chính, đóng góp mới và kết quả thực nghiệm, để đánh giá bài này có liên quan đến đề tài hay không trước khi dành thời gian đọc sâu |
| Actor | Sinh viên / Nghiên cứu viên |
| Thời điểm / bối cảnh | Giai đoạn đọc tài liệu để chuẩn bị làm đồ án tốt nghiệp hoặc viết bài báo khoa học |
| Quy trình hiện tại (3–7 bước) | 1. Tải file PDF bài báo (10–15 trang) (2') · 2. Đọc lướt Abstract và Conclusion (8') · 3. Đọc chi tiết phần Methodology và Thí nghiệm (70') · 4. Đánh giá xem phương pháp có áp dụng được vào bài toán của mình không (10') · 5. Lưu vào Zotero và ghi chú tóm tắt (10') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Đọc chi tiết Methodology và Thí nghiệm (mất ~70 phút), rất tốn công mà 40% số bài sau khi đọc xong mới thấy không dùng được |
| Impact (nếu không giải thì sao) | Mất 2–3 tiếng mỗi ngày chỉ để đọc 1–2 bài báo; làm chậm tiến độ nghiên cứu của cả kỳ |
| Success metric (baseline → target) | Baseline: mất 100 phút/bài, sàng lọc 1–2 bài/ngày → Target: giảm xuống 15–20 phút/bài, sàng lọc 4–5 bài/ngày |
| Phương án không dùng AI | Áp dụng kỹ thuật đọc 3 bước (Three-Pass Approach): Pass 1 chỉ đọc tiêu đề, abstract, đề mục và hình ảnh/bảng biểu trong 10 phút để quyết định đọc tiếp hay dừng |
| Giả thuyết về AI (nếu có) | Dùng LLM trích xuất bảng tóm tắt 3 câu hỏi then chốt: (1) Bài toán giải quyết là gì, (2) Giả định/phần cứng yêu cầu, (3) Điểm khác biệt so với baseline |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[1. Tải file PDF bài báo (10-15 trang)] (2')
       │
       ▼
[2. Đọc lướt Abstract và Conclusion] (8')
       │
       ▼
[3. Đọc chi tiết Methodology và Thí nghiệm] (70')  <-- BOTTLENECK (tốn nhiều thời gian đọc sâu)
       │
       ▼
[4. Đánh giá xem có áp dụng được vào đề tài không] (10')
       │
       ▼
[5. Lưu vào Zotero và ghi chú tóm tắt] (10')

Tổng thời gian: ~100 phút/bài
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị một hướng nghiên cứu mới, tôi muốn tìm và đối chiếu nhanh các công trình tương tự đã công bố, để xác định bài toán đã có ai làm chưa và tìm ra điểm mới (novelty) của mình |
| Actor | Sinh viên / Nghiên cứu viên bắt đầu đề tài mới |
| Thời điểm / bối cảnh | Tuần đầu tiên khi nhận hoặc hình thành ý tưởng nghiên cứu mới |
| Quy trình hiện tại (3–7 bước) | 1. Gõ từ khóa tìm kiếm trên Google Scholar/arXiv (30') · 2. Đọc lướt tiêu đề & chọn ra 20–30 bài liên quan (60') · 3. Mở từng bài để nhặt phương pháp và dataset so sánh (180') · 4. Lập bảng ma trận so sánh các công trình trước (90') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Mở từng bài nhặt thông tin phương pháp và dataset (mất ~180 phút), thông tin phân tán rải rác trong nhiều file PDF |
| Impact (nếu không giải thì sao) | Tốn 3–5 ngày chỉ để làm literature review; nguy cơ làm trùng ý tưởng đã có người làm |
| Success metric (baseline → target) | Baseline: mất 3–5 ngày để lập bảng so sánh → Target: có bảng so sánh sơ bộ trong 1 ngày, bao quát được ít nhất 15 bài then chốt |
| Phương án không dùng AI | Sử dụng các công cụ vẽ sơ đồ trích dẫn và liên kết học thuật chuyên dụng như Connected Papers, Litmaps, ResearchRabbit |
| Giả thuyết về AI (nếu có) | Dùng AI trích xuất các trường thông tin cố định (Tác giả, Năm, Phương pháp, Dataset, Kết quả chính) từ 10–20 file PDF và xuất thành bảng ma trận |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[1. Gõ từ khóa tìm kiếm trên Google Scholar/arXiv] (30')
       │
       ▼
[2. Đọc lướt tiêu đề & chọn ra 20-30 bài liên quan] (60')
       │
       ▼
[3. Mở từng bài nhặt phương pháp và dataset] (180')  <-- BOTTLENECK (đọc phân tán nhiều bài)
       │
       ▼
[4. Lập bảng ma trận so sánh các công trình] (90')

Tổng thời gian: ~6 tiếng (rải rác trong 3-5 ngày)
```

### Card muốn pitch nhất

- Card số: 1 (Lọc và tổng hợp đầu việc từ tin nhắn Zalo mỗi sáng)
- Vì sao: Vấn đề xảy ra lặp lại hàng ngày (tần suất cao), ai trong nhóm cũng gặp phải, quy trình đo lường baseline thời gian và rủi ro rất rõ ràng.
- Câu hỏi muốn nhóm phản biện: "Làm thế nào để hệ thống phân biệt được một tin nhắn trao đổi thông thường với một tin nhắn thực sự là nhiệm vụ (action item) cần làm mà không bị bắt nhầm hoặc bỏ sót?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Tin nhắn Zalo chứa dữ liệu nhạy cảm/nội bộ, đưa cả đoạn chat vào AI sẽ vi phạm quyền riêng tư và chính sách bảo mật | Đồng ý | Bổ sung Boundary: Không cấp quyền đọc toàn bộ app Zalo; chỉ xử lý các đoạn chat do người dùng chủ động chọn lọc và copy paste vào công cụ. |
| Nguy cơ báo nhầm (false positive): AI có thể nhầm các câu thảo luận đùa vui hoặc ý kiến cá nhân thành việc cần làm | Đồng ý | Bổ sung bước Human-in-the-loop: AI chỉ soạn bản nháp To-do list, người dùng bắt buộc phải tích chọn/xác nhận thì mới chính thức lưu. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1: Lọc và tổng hợp việc từ tin nhắn Zalo mỗi sáng (tốn 15–20 phút/ngày, hay sót việc) | Được nhóm quan tâm cao vì cả nhóm đều gặp tình trạng ngập tin nhắn trong các nhóm chat Zalo/Telegram; bài được đưa vào shortlist 3 bài tốt nhất |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt cho bạn Nam (bài Tự động tóm tắt cuộc họp nhóm): *"Nếu mic rè, nhiều tạp âm hoặc các thành viên nói chen ngang cướp lời nhau thì transcript đầu vào có đủ sạch để AI tóm tắt không, hay sẽ gây ra hiện tượng Garbage in - Garbage out?"* | Bạn Nam đồng ý là rủi ro kỹ thuật (Feasibility) của việc xử lý âm thanh tiếng Việt tự do quá cao; nhóm quyết định hạ độ ưu tiên bài này |
| Nhận phản biện | Câu hỏi tôi nhận được từ bạn Quảng: *"Tin nhắn Zalo hay có từ lóng, nói đùa, icon và thông tin cá nhân. Làm sao phân biệt được việc thật với chuyện phiếm mà không bị bắt nhầm (false positive)? Người dùng có dám cấp quyền đọc toàn bộ Zalo không?"* | Tôi đã sửa gì: Thêm ranh giới (Boundary) là không cấp quyền đọc toàn bộ app Zalo mà người dùng tự chọn copy đoạn chat cần xử lý; bổ sung cơ chế Human-in-the-loop (AI chỉ lên danh sách gợi ý, người dùng bấm duyệt mới lưu việc) |
| Gom cluster / cây OST | Cùng nhóm (hỗ trợ bạn Nam) gom 9 candidate của cả nhóm thành 3 cluster: (1) Quản lý task & tin nhắn trao đổi, (2) Đọc & tóm tắt tài liệu học thuật, (3) Tự động hóa báo cáo | Xây dựng cây OST với 1 Outcome chung: "Giảm thời gian xử lý thông tin lặp lại hàng ngày trong học tập và công việc" |
| Chọn candidate problem | Cùng chấm điểm bảng 7 tiêu chí cho shortlist 3 bài toán | Nhóm thống nhất chọn bài toán: "Lọc và trích xuất việc cần làm từ tin nhắn trao đổi nhóm" vì actor rõ, quy trình dễ vẽ, đo lường được ngay trong buổi lab |
| Kiểm chứng / research | **Người chính CP4 Kiểm chứng:** Chủ trì xây dựng Assumption Map (xác định 5 giả định cốt lõi) và trực tiếp phỏng vấn 2 bạn sinh viên theo The Mom Test để lấy Interview Snapshots. Đồng thời hỗ trợ bạn Quảng research giải pháp công cụ (Zalo To-do, extension trích xuất task). | Xác nhận 2/2 bạn đều từng bị trôi task trong group Zalo; phát hiện Zalo đã có tính năng To-do nhưng ít người dùng vì thao tác thủ công phức tạp |
| Quy trình nhóm | Tham gia cùng cả nhóm (hỗ trợ bạn Nam) phác thảo quy trình tương lai (Future State) và bảng so sánh Before/After | Làm rõ điểm can thiệp của AI: chỉ can thiệp ở bước phân tích văn bản và gợi ý checklist; con người giữ quyền duyệt cuối |
| Problem Statement | Tham gia cùng cả nhóm (hỗ trợ bạn Nam) viết Problem Statement v0 và v1, đặc biệt đóng góp phần Boundary và Success Metric | Đưa ra metric định lượng cụ thể: giảm thời gian lọc việc từ 20 phút xuống dưới 5 phút, tỷ lệ sót task về 0 |
| Mức can thiệp AI | Thảo luận và phân tích ma trận 4 mức can thiệp: No AI / Rule / Workflow / Agent (hỗ trợ bạn Nam) | Thuyết phục nhóm chọn mức **Workflow** thay vì Agent, vì quy trình trích xuất là tuần tự, không cần AI tự quyết định hành động |
| Quyết định | Tham gia cùng cả nhóm đánh giá 4 loại rủi ro (Value, Usability, Feasibility, Viability) và xây dựng pilot | Đưa ra quyết định: **Go, phạm vi nhỏ** với ngưỡng dừng thử nghiệm rõ ràng sau 2 tuần |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ gợi ý thêm các problem thường gặp trong môi trường công nghệ | Gợi ý góc nhìn về quản lý tài liệu trích dẫn (#5) khá thực tế | Gợi ý ý tưởng viển vông: "Tự động sinh toàn bộ code mô hình AI" – quá rộng, không có quy trình thật | Bỏ qua gợi ý viển vông, chỉ giữ lại các vấn đề có quy trình đo đạc được thời gian |
| CP2 Problem Card | Đóng vai "PM hoài nghi" để phản biện 3 Problem Card | Đặt ra các câu hỏi sắc bén về quyền riêng tư dữ liệu chat và rủi ro tin giả/nói đùa trong tin nhắn | Đề xuất giải pháp cực đoan: "Xây Agent tự động phân quyền và đọc API Zalo" (điều này Zalo không cho phép) | Bổ sung Boundary: người dùng tự copy-paste text vào công cụ thay vì đòi tích hợp API Zalo sâu |
| CP4 Research | Tìm kiếm các công cụ hiện có trên thị trường đã giải quyết việc lọc task từ chat | Gợi ý các công cụ như Slack AI, Todoist quick add, Zapier parser | Đưa ra 1 link extension Chrome đã bị gỡ và thông tin về API Zalo không còn chính xác ở thời điểm hiện tại | Tự mở link kiểm tra lại; chuyển hướng sang đánh giá tính năng "Nhắc hẹn / Giao việc" có sẵn trong chính Zalo |
| CP5 Quy trình | Chuyển đổi mô tả quy trình dạng lời thành sơ đồ trực quan (ASCII / Mermaid) | Format sơ đồ rất nhanh, căn chỉnh bố cục rõ ràng | Tự ý bỏ qua bước "Người dùng kiểm tra lại danh sách việc", cho AI tự động lưu luôn vào app To-do | Bắt buộc chèn lại bước Human-in-the-loop (Người dùng duyệt) trước khi task được lưu |
| CP5–6 Problem Statement | Gợi ý câu từ để chuẩn hóa Problem Statement | Giúp diễn đạt ngắn gọn các trường bối cảnh và bottleneck | Gợi ý success metric chung chung như: "giúp người dùng làm việc thông minh và hiệu quả hơn" (không đo được) | Sửa lại bằng số liệu đo lường cụ thể: giảm từ 20 phút xuống dưới 5 phút; giảm tỷ lệ sót việc từ 1 việc/tuần về 0 |
| CP6 Mức can thiệp / quyết định | Hỏi ý kiến xem bài toán này nên dùng Rule, Workflow hay Agent | Phân tích rõ ràng ranh giới giữa Workflow (tuần tự) và Agent (tự chủ) | Thúc đẩy chọn "Agent tự động hóa hoàn toàn" để nghe cho hiện đại và ấn tượng | Giữ vững quan điểm chọn **Workflow bán thủ công** để giảm thiểu rủi ro ảo giác (hallucination) và bảo mật |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**  
Khi nghe các bạn trong nhóm pitch, tôi nhận ra mọi người đều gặp một mẫu số chung: chúng tôi thường xuyên bị quá tải bởi thông tin rời rạc hàng ngày (từ tin nhắn chat, tài liệu học thuật, đến các ghi chú cuộc họp). Tuy nhiên, nhiều bạn ban đầu có thói quen mô tả giải pháp thay vì vấn đề (ví dụ nói "cần một con bot tóm tắt cuộc họp" thay vì nói "tốn 30 phút nghe lại audio để chép biên bản"). Điều này giúp tôi tỉnh táo hơn trong việc tự soi lại các card của chính mình để bóc tách triệt để giữa nỗi đau thực tế và công cụ giải quyết.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**  
Có, nhóm tôi bị "solution-first" ngay từ đầu buổi khi vừa họp nhóm ở CP3. Có bạn hào hứng đề xuất "xây một AI Agent tự động quản lý dự án cho sinh viên". Khi đó cả nhóm bị cuốn theo việc bàn xem nên dùng thư viện nào, model gì. Nhờ người điều phối nhắc lại quy định của lab và xem lại cây OST, nhóm mới phanh lại và tự hỏi: "Sinh viên thực sự đau ở bước nào trong việc quản lý dự án?". Khi bóc tách ra, nhóm thấy bước tốn thời gian và dễ hỏng việc nhất chỉ là việc các thành viên không nắm được deadline giao trong group chat. Nhờ vậy, nhóm quay về đúng bài toán trích xuất task cụ thể thay vì xây một hệ thống mơ hồ.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**  
Tôi đã đổi ý hoàn toàn ở bước thiết kế mức độ can thiệp của AI. Ban đầu, tôi khá tự tin với ý tưởng để hệ thống tự động quét tin nhắn và tự động đẩy việc vào Google Calendar / Trello mà không cần người dùng can thiệp. Nhưng sau khi bạn Quảng và bạn Nam phản biện rằng: "Nếu tin nhắn là sếp nói mỉa mai hoặc bạn bè đùa cợt, bot tự thêm vào lịch thì người dùng sẽ bị loạn to-do list và mất niềm tin vào công cụ ngay lập tức", tôi nhận thấy rủi ro báo nhầm (false positive) là chí mạng. Tôi đã lập tức đổi ý, chấp nhận quy trình bán tự động (Workflow có Human-in-the-loop): AI chỉ soạn nháp, quyền bấm lưu thuộc về con người.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**  
Điều làm tôi bất ngờ nhất khi đi phỏng vấn 2 bạn sinh viên khác là họ không hề thiếu công cụ quản lý công việc (họ đều biết Notion, Trello, Zalo To-do), nhưng họ vẫn dùng cách thủ công là chụp màn hình hoặc ghi sổ tay. Lý do là việc tạo task trên các app hiện tại đòi hỏi quá nhiều thao tác gõ lại thông tin. Một bất ngờ nữa từ phần research là Zalo thực ra đã có sẵn tính năng "Giao việc", nhưng 80% mọi người không dùng vì giao diện phức tạp và không tự trích xuất được từ ngữ cảnh chat. Điều này củng cố thêm niềm tin rằng vấn đề nằm ở khâu trích xuất thông tin thuận tiện chứ không phải người dùng thiếu nơi lưu việc.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**  
Điều khó nhất là viết phần **Boundary** (Ranh giới) và **Success Metric**. Với metric, rất dễ rơi vào bẫy dùng các tính từ cảm tính như "giúp làm việc nhanh hơn", "tiện lợi hơn"; tôi phải mất nhiều thời gian ngồi tính lại xem bình thường mình mất bao nhiêu phút (baseline) và kỳ vọng giảm còn bao nhiêu phút (target) để đo được bằng đồng hồ bấm giờ. Với Boundary, việc xác định rõ "AI KHÔNG được làm gì" đòi hỏi phải lường trước các trường hợp biên nguy hiểm (như lộ dữ liệu bí mật, tự gửi tin nhắn bậy bạ ra ngoài), điều mà trước đây khi nghĩ về AI tôi hiếm khi để tâm.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**  
Nếu được làm lại từ đầu buổi lab, tôi sẽ chủ động yêu cầu nhóm đi kiểm chứng (phỏng vấn người dùng thật) sớm hơn ngay từ cuối CP2, thay vì đợi đến CP4 mới đi hỏi. Việc có dữ liệu thực tế sớm sẽ giúp nhóm tiết kiệm ít nhất 20 phút tranh luận cảm tính ở CP3. Ngoài ra, tôi sẽ phản biện mạnh mẽ hơn những ý tưởng muốn ôm đồm nhiều tính năng, ép nhóm phải bám sát câu hỏi: "Nếu không dùng AI thì có cách nào giải quyết được 70% bài toán này với chi phí bằng 0 không?".

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.  
Bài toán của nhóm xuất phát từ **problem** có thật là người dùng mất 15–20 phút mỗi sáng để lướt các nhóm chat Zalo tìm việc cần làm và thường xuyên bị trễ hạn do trôi tin nhắn. **Quy trình** mới được thiết kế theo hướng người dùng chỉ cần copy đoạn hội thoại đưa vào hệ thống, mô hình ngôn ngữ sẽ trích xuất ra các đầu việc (action items) kèm deadline và người phụ trách, sau đó hiển thị dạng checklist để người dùng kiểm tra lại trước khi lưu vào to-do list. **Metric** thành công được đo lường rõ ràng: thời gian tổng hợp việc mỗi sáng giảm từ 20 phút xuống dưới 5 phút, và số lượng công việc bị bỏ sót giảm từ 1 việc/tuần về 0. **Boundary** của giải pháp quy định nghiêm ngặt: AI không được tự động đọc trộm dữ liệu ngoài vùng cho phép, không tự ý gán mức độ ưu tiên và không tự động lưu task khi chưa có sự xác nhận của người dùng (bắt buộc Human-in-the-loop). Nhóm lựa chọn **mức can thiệp là Workflow** thay vì Agent, bởi bài toán chỉ cần AI thực hiện một bước trích xuất thông tin có ngữ cảnh theo quy trình cố định, không cần AI tự quyết định hành động tiếp theo. Cuối cùng, nhóm đưa ra **quyết định: Go, phạm vi nhỏ** – triển khai thử nghiệm (pilot) trong 2 tuần bằng cách dùng prompt chuẩn trên ChatGPT/Gemini có sẵn để đo lường độ chính xác thực tế trước khi quyết định có nên xây dựng công cụ riêng hay không.

---

## 7. Tài liệu tham khảo

- Design Council (2004), *The "Double Diamond" Design Process Model*.
- Rob Fitzpatrick (2013), *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*.
- Teresa Torres (2021), *Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value* (Opportunity Solution Tree).
- Google PAIR (2019), *People + AI Guidebook: Designing human-centered AI products*.
- Gothelf, J. & Seiden, J. (2021), *Lean UX: Designing Great Products with Agile Teams* (Problem Statement Framework).
- Marty Cagan (2017), *Inspired: How to Create Tech Products Customers Love* (4 Product Risks: Value, Usability, Feasibility, Viability).
