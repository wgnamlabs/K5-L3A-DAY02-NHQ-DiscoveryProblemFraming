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
