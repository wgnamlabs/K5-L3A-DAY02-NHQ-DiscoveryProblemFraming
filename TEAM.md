# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: NHQ
- Candidate problem nhóm chọn (1 câu): Sinh viên làm bài nhóm cần xác định đúng phiên bản tài liệu chính thức khi có nhiều file hoặc bản sao được chia sẻ, để tránh sửa nhầm bản cũ.
- Quyết định cuối: Go với pilot quy trình No AI trong 2 tuần; No-Go đối với việc xây dựng hệ thống AI riêng ở giai đoạn hiện tại.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Trần Quang Nam | 2A202603516 | Điều phối, phụ trách candidate và Problem Statement | wgnamlabs |
| 2 | Nguyễn Bá Quảng | 2A202603555 | Phản biện shortlist và research công cụ | nbquang04 |
| 3 | Đoàn Văn Hiệp | 2A202603565 | Phụ trách kiểm chứng/phỏng vấn và research | (điền GitHub) |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Trần Quang Nam | Nguyễn Bá Quảng, Đoàn Văn Hiệp | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đoàn Văn Hiệp | Trần Quang Nam, Nguyễn Bá Quảng | Assumption map, interview snapshots |
| CP4 — Research | Nguyễn Bá Quảng | Đoàn Văn Hiệp | Bảng research có link |
| CP5 — Quy trình trước/sau | Trần Quang Nam | Cả nhóm | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Trần Quang Nam | Cả nhóm | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Trần Quang Nam | Nguyễn Bá Quảng, Đoàn Văn Hiệp | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm | Cả nhóm | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### Trần Quang Nam-2A202603516

**Phần việc phụ trách:**

- Điều phối phần hội tụ nhóm ở CP3; phụ trách candidate “Tìm đúng phiên bản tài liệu nhóm”.
- Cung cấp baseline từ trải nghiệm thực tế và phối hợp xây dựng quy trình trước/sau ở CP5.
- Tham gia viết Problem Statement v0, Problem Statement v1, tiêu chí đánh giá và quyết định CP6.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đề xuất và trình bày candidate về việc xác định đúng phiên bản tài liệu nhóm khi có nhiều bản sao được chia sẻ qua hội thoại.
- Cung cấp số liệu baseline: trong một tháng phải tìm lại tài liệu nhóm 4 lần; lần gần nhất mất 18 phút để kiểm tra 5 file, trong đó bước mở và so sánh mất khoảng 7 phút.
- Tham gia lập bảng pitch, cluster, OST và bảng chấm điểm shortlist; candidate này đạt 33/35 điểm và được nhóm lựa chọn.
- Phối hợp mô tả quy trình hiện tại/tương lai, xác định bottleneck, success metric, boundary và phương án fallback.
- Tham gia thu hẹp phạm vi pilot vào việc xác định đúng phiên bản tài liệu; loại việc ghép nội dung, sửa font, sửa bảng và định dạng khỏi success metric của pilot.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Báo cáo cá nhân: `report/individual/2A202603516_TranQuangNam.md`.
- Báo cáo nhóm: mục **2.1 Pitch**, **2.2 Cluster**, **2.3 Opportunity Solution Tree**, **2.4 Chấm điểm shortlist** và phần lựa chọn candidate.
- Báo cáo nhóm: mục **4.1 Quy trình hiện tại**, **4.2 Quy trình tương lai**, **4.3 Before / after**, **5. Problem Statement v0**, **7. Problem Statement v1** và **8. Quyết định**.

**Điều mình học được từ phần nhóm:**

- Cần bắt đầu từ problem và bằng chứng hành vi thay vì bắt đầu từ ý tưởng AI.
- Một bottleneck rộng như “gom file và sửa định dạng” cần được tách khỏi bài toán hẹp hơn là “xác định đúng phiên bản”, để có metric và phạm vi pilot đo được.
- Một quy trình No AI với nguồn tài liệu chính thức, lịch sử phiên bản và người xác nhận có thể là lựa chọn phù hợp trước khi cân nhắc Rule, Workflow hoặc Agent.
- Khi dữ liệu còn ít, cần ghi rõ baseline, giả định, tín hiệu phản bác và ngưỡng dừng thay vì khái quát quá mức.

### Nguyễn Bá Quảng-2A202603555

**Phần việc phụ trách:**

- CP3: phản biện shortlist; hỗ trợ Trần Quang Nam gom cluster, xây cây OST và lựa chọn candidate problem.
- CP4: phụ trách research công cụ, có Đoàn Văn Hiệp hỗ trợ; hỗ trợ phần kiểm chứng do Hiệp phụ trách.
- Phần chung của nhóm: hỗ trợ Trần Quang Nam ở CP5 (quy trình trước/sau, Problem Statement v0) và CP6 (so sánh mức can thiệp, Problem Statement v1); cùng nhóm thảo luận và chốt quyết định CP6.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đưa ra ba candidate: chuẩn bị lộ trình học kiến thức mới, tổng hợp công việc ưu tiên đầu ngày và tra cứu sản phẩm, giá, tồn kho để báo giá; xác định actor, bottleneck và phương án không dùng AI cho từng vấn đề.
- Phản biện candidate tìm phiên bản tài liệu bằng câu hỏi: “Nếu sử dụng chung một file Google Docs thì vấn đề này có còn xảy ra không?”; phản biện candidate đọc bài báo bằng câu hỏi liệu đọc Abstract và Conclusion trước có đủ để đánh giá mức độ liên quan.
- Tham gia đối chiếu shortlist theo bằng chứng và phạm vi lab; candidate tổng hợp công việc ưu tiên đầu ngày của mình đạt 27/35 điểm nhưng còn thiếu bằng chứng về pain và actor chưa đủ cụ thể.
- Research Google Docs — Version History, Google Drive — Manage Versions và Microsoft OneDrive — Version History; tổng hợp link, bước được hỗ trợ, điểm mạnh, khoảng trống và bài học trong bảng research.
- Đóng góp kết quả research cho phần chung CP5–CP6: một nguồn tài liệu chung, liên kết cố định và quy tắc xác nhận phiên bản chính thức; hỗ trợ so sánh No AI / Rule / Workflow / Agent. Quyết định chung của nhóm là Go với pilot No AI trong 2 tuần, No-Go với việc xây hệ thống AI riêng ở giai đoạn hiện tại.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Báo cáo cá nhân: `report/individual/2A202603555_NguyenBaQuang.md`
- Phần pitch và phản biện: mục **2.1 Pitch** (ba candidate của Quảng và câu hỏi phản biện); hỗ trợ hội tụ tại mục **2.2 Cluster**, **2.3 Opportunity Solution Tree** và **2.4 Chấm điểm shortlist**.
- Phần research phụ trách: mục **3.3 Research giải pháp đã có** (bảng ba công cụ, link và kết luận research).
- Phần chung CP5–CP6 có tham gia hỗ trợ: mục **4. Quy trình trước/sau**, **5. Problem Statement v0**, **6. Mức can thiệp AI**, **7. Problem Statement v1**; quyết định của cả nhóm tại mục **8. Quyết định**.

**Điều mình học được từ phần nhóm:**

- Cần phản biện bằng phương án đơn giản sẵn có trước khi kết luận một vấn đề cần AI; lịch sử phiên bản chỉ hữu ích khi nhóm thống nhất nguồn tài liệu và quy tắc làm việc.
- Candidate có vẻ hữu ích vẫn cần actor cụ thể, bằng chứng về pain và metric đo được; các con số ước lượng ban đầu cần được kiểm chứng trước khi dùng làm kết luận.
- Phải phân biệt thời gian xác định đúng phiên bản với thời gian gom, ghép và sửa định dạng tài liệu để tránh dùng số liệu của hai công việc khác nhau cho cùng một metric.
- Research công cụ cần chỉ ra cả giới hạn: công cụ quản lý phiên bản không tự quyết định bản nào là chính thức giữa nhiều file độc lập, và pilot vẫn cần đo việc thành viên tuân thủ quy trình chung.
