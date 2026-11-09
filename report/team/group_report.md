# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NHQ
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Sinh viên làm bài nhóm cần xác định đúng phiên bản tài liệu chính thức khi nhiều bản sao được chia sẻ qua hội thoại để tránh sửa nhầm file cũ.
- Quyết định cuối: Go với pilot quy trình No AI trong 2 tuần; No-Go đối với việc xây dựng hệ thống AI riêng ở giai đoạn hiện tại.

---

## 2. Hội tụ nhóm (CP3)


### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Trần Quang Nam | Khi ôn thi, tôi muốn tổng hợp kiến thức từ slide, PDF và ghi chú để tránh học trùng hoặc bỏ sót nội dung. | Sinh viên đại học | Đối chiếu nội dung giữa nhiều tài liệu, mất khoảng 30 phút/lần. | Hiệp hỏi: Nếu sử dụng mục lục và checklist thì có thể giải quyết vấn đề mà không cần AI không? |
| 2 | Trần Quang Nam | Khi chỉnh sửa bài nhóm, tôi muốn tìm đúng phiên bản tài liệu mới nhất để tránh sửa nhầm file cũ. | Thành viên làm bài nhóm | Mở và so sánh nội dung giữa các phiên bản, mất khoảng 7 phút/lần. | Quảng hỏi: Nếu sử dụng chung một file Google Docs thì vấn đề này có còn xảy ra không? |
| 3 | Trần Quang Nam | Khi bắt đầu tuần học, tôi muốn tổng hợp deadline từ LMS và Google Calendar để không bỏ sót hạn nộp. | Sinh viên học nhiều môn | Tra cứu deadline trên LMS nhiều lần, mất 24–36 phút/tuần. | Hiệp hỏi: Có thể đồng bộ lịch học và deadline tự động mà không cần AI không? |
| 4 | Đoàn Văn Hiệp | Khi bắt đầu ngày làm việc, tôi muốn tổng hợp công việc từ các nhóm chat Zalo để không bỏ sót nhiệm vụ quan trọng. | Nhân viên hoặc sinh viên làm dự án nhóm | Đọc tin nhắn để tìm nhiệm vụ và deadline, mất khoảng 10 phút/sáng. | Nam hỏi: Làm sao phân biệt tin nhắn giao việc thật với tin nhắn trao đổi thông thường? |
| 5 | Đoàn Văn Hiệp | Khi đọc bài báo khoa học mới, tôi muốn nắm nhanh phương pháp và kết quả để đánh giá mức độ liên quan đến đề tài. | Sinh viên, nghiên cứu viên | Đọc phần phương pháp và thí nghiệm, mất khoảng 70 phút/bài. | Quảng hỏi: Nếu chỉ đọc Abstract và Conclusion trước thì có đủ để đánh giá bài báo không? |
| 6 | Đoàn Văn Hiệp | Khi bắt đầu nghiên cứu đề tài mới, tôi muốn đối chiếu các công trình đã công bố để tìm điểm mới và tránh trùng lặp. | Sinh viên, nghiên cứu viên | Đọc và trích xuất phương pháp, dataset từ nhiều bài báo, mất khoảng 180 phút. | Nam hỏi: Làm sao đảm bảo không bỏ sót các công trình quan trọng khi tìm kiếm tài liệu? |
| 7 | Nguyễn Bá Quảng | Khi bắt đầu học kiến thức mới, tôi muốn xác định nội dung và thứ tự học phù hợp để tránh học lan man, trùng lặp và mất thời gian tìm tài liệu. | Sinh viên tự học một chủ đề mới | Đọc lướt và đối chiếu độ phù hợp, trùng lặp giữa các tài liệu, ước tính 60 phút/lần. | Nam hỏi: Nếu dùng syllabus có sẵn và checklist thì có thể giảm thời gian chuẩn bị mà không cần AI không? |
| 8 | Nguyễn Bá Quảng | Khi bắt đầu ngày làm việc, tôi muốn biết công việc ưu tiên và deadline sắp tới để không phải kiểm tra từng ứng dụng nhiều lần. | Nhân viên quản lý công việc cá nhân từ 2–3 nguồn | Đối chiếu công việc trùng lặp, trạng thái và deadline giữa các nguồn, ước tính 8 phút/ngày. | Hiệp hỏi: Vấn đề này có trùng với việc tổng hợp công việc từ Zalo không? Có thể dùng một danh sách công việc chung không? |
| 9 | Nguyễn Bá Quảng | Khi chuẩn bị báo giá, tôi muốn tra cứu chính xác thông tin sản phẩm, giá và tồn kho để phản hồi khách hàng nhanh chóng. | Nhân viên sales lập báo giá | Tra cứu và đối chiếu giá, tồn kho từng mã sản phẩm, ước tính 12 phút/báo giá 5 mã. | Nam hỏi: Nếu sử dụng bảng giá và tồn kho được đồng bộ tự động thì có cần AI hỗ trợ không? |


### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
| :------ | :------------ | :------------ |
| A — Đọc và tổng hợp kiến thức | #1 Tổng hợp tài liệu ôn thi (Nam); #5 Đọc bài báo khoa học (Hiệp); #6 Đối chiếu công trình nghiên cứu (Hiệp); #7 Chuẩn bị lộ trình học kiến thức mới (Quảng) | Phải đọc, chọn lọc, so sánh và tổng hợp thông tin từ nhiều tài liệu. Tốn thời gian xử lý nội dung, dễ trùng lặp hoặc bỏ sót thông tin quan trọng. |
| B — Quản lý công việc và deadline | #3 Theo dõi deadline từ LMS và Calendar (Nam); #4 Tổng hợp công việc từ Zalo (Hiệp); #8 Tổng hợp công việc ưu tiên đầu ngày (Quảng) | Công việc và deadline nằm rải rác ở nhiều nguồn. Người dùng phải kiểm tra, đối chiếu và tổng hợp thủ công, gây mất thời gian và có nguy cơ bỏ sót nhiệm vụ. |
| C — Tra cứu và xác minh thông tin | #2 Tìm đúng phiên bản tài liệu nhóm (Nam); #9 Tra cứu sản phẩm, giá và tồn kho để báo giá (Quảng) | Phải tìm kiếm và đối chiếu dữ liệu từ nhiều phiên bản hoặc nguồn khác nhau để xác định thông tin chính xác, cập nhật trước khi thực hiện công việc. |



### 2.3. Opportunity Solution Tree rút gọn

**Outcome ban đầu của OST:** Giảm thời gian tìm kiếm, đối chiếu và tổng hợp thông tin. Sau khi chọn candidate, nhóm cụ thể hóa outcome đo được như sau:

```text
OUTCOME: Xác định đúng phiên bản tài liệu nhóm trong dưới 5 phút/lần, với 100% tình huống thử nghiệm không chọn nhầm bản được người phụ trách xác nhận.
│
├── Opportunity A: Người dùng mất nhiều thời gian đọc,
│   so sánh và tổng hợp kiến thức từ nhiều tài liệu.
│
├── Opportunity B: Công việc và deadline nằm phân tán
│   ở nhiều nguồn, khiến người dùng phải kiểm tra
│   thủ công và có nguy cơ bỏ sót nhiệm vụ.
│
└── Opportunity C: Người dùng khó xác định thông tin
    chính xác và cập nhật mới nhất khi có nhiều phiên bản
    hoặc nguồn dữ liệu khác nhau.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Xây chatbot AI để tổng hợp tài liệu học tập" → Đây là giải pháp, không phải vấn đề.
- "Tạo ứng dụng AI tự động quản lý deadline" → Đây là giải pháp, không phải nhu cầu thực tế.
- "Xây hệ thống AI tự động tìm kiếm và đối chiếu dữ liệu" → Đây là giải pháp, không phải pain của người dùng.


### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tìm đúng phiên bản tài liệu nhóm (Nam) | 5 | 5 | 5 | 5 | 5 | 4 | 4 | **33** |
| Đọc bài báo khoa học (Hiệp) | 5 | 5 | 4 | 5 | 4 | 5 | 4 | **32** |
| Tổng hợp công việc ưu tiên đầu ngày (Quảng) | 4 | 5 | 2 | 3 | 5 | 4 | 4 | **27** |

**Candidate được chọn:**
- Tìm đúng phiên bản tài liệu nhóm

**Vì sao chọn:**

- Nhóm chọn candidate **“Tìm đúng phiên bản tài liệu nhóm”** vì đạt tổng điểm cao nhất trong bảng chấm điểm (**33/35**) và có actor, quy trình, bottleneck tương đối rõ. Vấn đề xuất hiện trong bối cảnh quen thuộc của sinh viên khi làm bài nhóm: nhiều phiên bản tài liệu được gửi qua hội thoại khiến thành viên phải tìm, mở và đối chiếu thủ công trước khi chỉnh sửa hoặc nộp bài.

- Impact của vấn đề có thể đo được bằng thời gian xác định tài liệu chính thức, số lần chọn nhầm phiên bản và số lần phải làm lại nội dung. Nếu xác định đúng phiên bản ngay từ đầu, nhóm có thể giảm thời gian tìm kiếm, tránh chỉnh sửa nhầm file cũ và hạn chế công sức làm lại của các thành viên.

- Candidate này cũng vừa sức trong phạm vi lab vì nhóm có thể vẽ quy trình hiện tại, kiểm chứng trải nghiệm với người dùng thật, so sánh No AI / Rule / Workflow / Agent và thử một phương án đơn giản trước. Đặc biệt, nhóm có thể kiểm tra giả thuyết rằng một nguồn tài liệu chung, liên kết cố định và lịch sử phiên bản đã đủ giải quyết phần lớn vấn đề mà chưa cần xây AI.

**Vì sao loại các candidate còn lại:**

- **Tổng hợp công việc ưu tiên đầu ngày:** Candidate này có phạm vi quá rộng vì công việc và deadline có thể nằm ở nhiều ứng dụng, nhiều loại nhiệm vụ và nhiều bối cảnh khác nhau. Actor chưa đủ cụ thể; đồng thời nhóm chưa có bằng chứng mạnh về mức độ ảnh hưởng và khó vẽ một quy trình chung đủ rõ trong thời gian lab. Dù có thể dùng danh sách công việc chung hoặc công cụ có sẵn, nhóm chưa xác định được bottleneck nào là ưu tiên nhất để kiểm chứng.

- **Đọc bài báo khoa học:** Đây là vấn đề có impact tiềm năng lớn nhưng cần kiến thức chuyên môn để đánh giá liệu việc tóm tắt, chọn lọc hoặc so sánh bài báo có chính xác hay không. Nhóm chưa có ground truth hoặc tiêu chí đánh giá đủ rõ trong phạm vi lab để kiểm tra nguy cơ bỏ sót nghiên cứu quan trọng, hiểu sai phương pháp hoặc đánh giá sai mức độ liên quan. Candidate này cũng có rủi ro cao hơn nếu áp dụng AI và khó kiểm chứng hiệu quả trong thời gian ngắn.

**Xử lý bất đồng (nếu có):**

Nhóm dùng cùng một tiêu chí chấm điểm thay vì chọn theo ý kiến đa số: actor và quy trình phải rõ, pain phải có bằng chứng, impact phải đo được, phạm vi phải vừa sức và phải so sánh được các mức No AI/Rule/Workflow/Agent. Thành viên ủng hộ hoặc phản biện candidate nêu lý do và bằng chứng trong bảng chấm điểm; nếu còn khác biệt, nhóm đối chiếu lại Problem Card và chọn candidate có tổng điểm cao nhất. Với candidate được chọn, nhóm vẫn ghi rõ các điểm chưa chắc để đưa sang Assumption Map và kiểm chứng ở CP4. Không sử dụng AI để thay nhóm đưa ra quyết định CP3.


## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên làm việc nhóm thường mất nhiều thời gian tìm đúng phiên bản tài liệu mới nhất. | Value | 5 | 2 | **Có** |
| 2 | Việc sử dụng nhầm phiên bản cũ có thể gây mất nội dung, phải chỉnh sửa lại và ảnh hưởng tiến độ nhóm. | Value | 5 | 1 | **Có** |
| 3 | Bước mở và so sánh nội dung giữa các file là bước tốn nhiều thời gian nhất. | Usability | 4 | 4 | Theo dõi |
| 4 | Sử dụng một file chung có lịch sử chỉnh sửa có thể giải quyết phần lớn vấn đề mà không cần AI. | Feasibility | 5 | 4 | Theo dõi |
| 5 | Các thành viên sẵn sàng tuân thủ quy tắc lưu trữ và cập nhật tài liệu trên một nguồn chung. | Usability | 4 | 1 | **Có** |
| 6 | Các công cụ quản lý phiên bản hiện có đáp ứng được nhu cầu của nhóm với chi phí và quyền truy cập phù hợp. | Viability | 4 | 3 | Theo dõi |

**Giả định nhóm cần ưu tiên kiểm chứng:**

- Giả định #1: Vấn đề tìm nhầm hoặc mất thời gian tìm phiên bản tài liệu có xảy ra với nhiều sinh viên khác không, hay chỉ là trường hợp cá nhân?
- Giả định #2: Việc chọn nhầm phiên bản cũ đã từng khiến nhóm phải làm lại nội dung hoặc chậm tiến độ chưa?
- Giả định #5: Các thành viên sẵn sàng tuân thủ quy tắc lưu trữ và cập nhật tài liệu trên một nguồn chung chưa?

**Bằng chứng hiện có:**

- Theo báo cáo cá nhân của Trần Quang Nam, trong tháng trước việc tìm lại tài liệu nhóm xảy ra 4 lần.
- Lần gần nhất mất 18 phút để kiểm tra 5 file và xác định phiên bản mới nhất.
- Bước so sánh nội dung các phiên bản được ước tính mất 7 phút.
- Phỏng vấn 3 người ngoài nhóm cho tín hiệu ban đầu: 2/3 người gặp pain khi có nhiều file chỉnh sửa độc lập; 1/3 người không gặp pain nhờ dùng một nguồn chung từ đầu. Mẫu nhỏ và số liệu tự ước lượng nên chưa thể khái quát.

### 3.2. Kiểm chứng

#### Mục tiêu kiểm chứng

Nhóm ưu tiên kiểm tra các giả định có mức quan trọng cao nhưng bằng chứng còn thấp:

1. Sinh viên ngoài nhóm có thực sự mất thời gian khi xác định phiên bản tài liệu chính thức hay không.
2. Việc dùng nhầm phiên bản cũ có từng gây làm lại, mất nội dung hoặc chậm tiến độ hay không.
3. Quy trình dùng một nguồn tài liệu chung có phù hợp với cách làm việc thực tế của họ hay không.

#### Phương pháp

- **Phương pháp đã chọn:** Phỏng vấn nhanh theo The Mom Test, vì mẫu nhỏ và nhóm cần nghe những câu chuyện cụ thể đã xảy ra.
- **Số người hợp lệ:** 3 người.
- **Tiêu chí chọn người:** Không thuộc nhóm NHQ; từng làm bài nhóm; từng xử lý nhiều phiên bản tài liệu hoặc liên kết.
- **Thời gian thực hiện:** 09/11/2026.
- **Hình thức:** Phỏng vấn trực tiếp (tại lớp lab và căn tin trường), mỗi buổi khoảng 10–12 phút.
- **Cách hỏi:** Hỏi về hành vi đã xảy ra gần đây, không giới thiệu giải pháp AI và không hỏi người tham gia có muốn dùng một giải pháp giả định hay không.

#### Bộ câu hỏi phỏng vấn

1. Lần gần nhất bạn phải tìm phiên bản mới nhất của tài liệu nhóm là khi nào?
2. Bạn có thể kể lại từ đầu đến cuối chuyện đã xảy ra không?
3. Khi đó có bao nhiêu file hoặc liên kết cần kiểm tra, và chúng được gửi ở đâu?
4. Bạn đã làm những bước nào để xác định file cần dùng?
5. Bước nào mất thời gian nhất? Mất khoảng bao lâu?
6. Bạn hoặc thành viên nhóm từng chỉnh sửa hay nộp nhầm phiên bản cũ chưa? Khi đó điều gì xảy ra?
7. Nhóm bạn hiện xử lý việc này như thế nào? Đã thử cách nào khác chưa?
8. Có trường hợp nào nhiều phiên bản **không** gây khó khăn cho nhóm bạn không? Vì sao?

#### Interview Snapshot 1 — Sinh viên phụ trách tổng hợp đồ án nhóm

| Trường | Nội dung |
|---|---|
| Người được hỏi | Sinh viên năm cuối, phụ trách tổng hợp nội dung và slide đồ án nhóm 4 người. |
| Thời điểm và cách hỏi | 09/11/2026, phỏng vấn trực tiếp tại lớp lab, khoảng 12 phút. |
| Bối cảnh liên quan | Đồ án tổng hợp giữa kì gồm báo cáo Word, bảng số liệu Excel và bộ slide thuyết trình chia thành nhiều phần cho từng thành viên. |
| Lần gần nhất gặp vấn đề | 3 ngày trước, khi chuẩn bị nộp bản final. Có 6 file (3 Word, 2 Excel, 1 Slide) được gửi rải rác qua nhóm chat Messenger và Google Drive cá nhân của từng người. |
| Các bước đã làm | Tải các file mới nhất trong chat về máy → mở song song 3 file Word để tìm phần bị lệch → copy ghép thủ công vào file tổng → sửa lại font, căn lề, bảng bị vỡ. |
| Thời gian hoặc tần suất | Khoảng 3 tiếng cho mỗi đợt nộp báo cáo, khoảng 2 lần/tháng (người được hỏi tự ước lượng). |
| Workaround hiện tại | Nhắn tin giục từng thành viên gửi lại bản chuẩn cuối, kiểm tra lịch sử chỉnh sửa trên Google Drive thủ công, hoặc lục lại các link ghim đầu nhóm chat. |
| Câu nói đáng chú ý | Người được hỏi cho biết sợ nhất là khâu gom file, chỉnh font và xác định ai gửi bản chuẩn cuối, vì vừa mất thời gian vừa dễ cãi nhau trong nhóm (diễn đạt lại, không phải nguyên văn). |
| Tín hiệu xác nhận hoặc phản bác | Xác nhận pain: mất khoảng 3 tiếng/đợt, tần suất 2 lần/tháng, file phân tán qua nhiều kênh, dễ phát sinh tranh cãi về bản chuẩn. |
| Insight cho nhóm | Bottleneck người được hỏi nêu: gom file rải rác, chỉnh format và xác định bản chuẩn. Baseline khoảng 180 phút/đợt (tự ước lượng). Người này chưa được hỏi về giải pháp nên chưa đủ dữ liệu để kết luận No AI có đủ hay không. |

#### Interview Snapshot 2 — Trưởng nhóm đồ án tốt nghiệp

| Trường | Nội dung |
|---|---|
| Người được hỏi | Sinh viên năm 4 ngành CNTT, trưởng nhóm đồ án tốt nghiệp 4 người. |
| Thời điểm và cách hỏi | 09/11/2026, phỏng vấn trực tiếp tại căn tin trường, khoảng 10 phút. |
| Bối cảnh liên quan | Báo cáo đồ án tốt nghiệp gồm báo cáo Word, bảng tiến độ Google Sheets và code trên GitHub. |
| Lần gần nhất gặp vấn đề | Tuần trước, khi gom bài nộp bản draft cho giảng viên. Có 4–5 file Word chỉnh sửa độc lập, rải rác trên Messenger, Zalo và Drive cá nhân của các thành viên. |
| Các bước đã làm | Mở từng link Zalo/Messenger → tải file về máy → so sánh thủ công từng mục → copy-paste vào file tổng → sửa lỗi nhảy font, lỗi bảng. |
| Thời gian hoặc tần suất | Khoảng 2,5 tiếng mỗi lần tổng hợp, khoảng 1 lần/tuần vào mỗi đợt nộp báo cáo (tự ước lượng). |
| Workaround hiện tại | Tạo một file Google Docs chung, ghim link đầu box chat Zalo và nhắc thành viên chỉ sửa trực tiếp trên đó. |
| Câu nói đáng chú ý | Ý chính được ghi lại: người được hỏi rất lo khi đến hạn nộp vì không biết bản Word nào là bản mới nhất để chép vào file tổng. **Cần đối chiếu ghi chép trước khi coi đây là nguyên văn.** |
| Tín hiệu xác nhận hoặc phản bác | Xác nhận pain: mất nhiều thời gian xử lý thủ công, khó biết bản nào mới nhất, ảnh hưởng tiến độ nộp bài. |
| Insight cho nhóm | Baseline khoảng 150 phút/lần (tự ước lượng). Dù đã có Google Docs chung, vẫn còn 4–5 file Word rải rác, cho thấy vấn đề liên quan cả việc thành viên không tuân thủ quy tắc làm việc, không chỉ là thiếu công cụ lưu trữ (nhóm suy ra). |

#### Interview Snapshot 3 — Thành viên nhóm làm bài tập môn học

| Trường | Nội dung |
|---|---|
| Người được hỏi | Sinh viên năm 4 ngành MKT, thường xuyên làm bài tập nhóm 3–5 người. |
| Thời điểm và cách hỏi | 09/11/2026, phỏng vấn trực tiếp tại căn tin trường, khoảng 10 phút. |
| Bối cảnh liên quan | Làm slide thuyết trình và bài tiểu luận cho các môn chuyên ngành. |
| Lần gần nhất gặp vấn đề | Người được hỏi không nhớ rõ lần gần nhất gặp vấn đề, vì nhóm đã thiết lập quy trình lưu trữ ngay từ đầu buổi làm việc. |
| Các bước đã làm | Trưởng nhóm tạo một thư mục Google Drive chung → chia phần trực tiếp trên Notion → ai làm xong tự tải file lên đúng thư mục trên Drive. |
| Thời gian hoặc tần suất | Lấy file mất chưa tới 5 phút (người được hỏi tự ước lượng). |
| Workaround hiện tại | Chỉ dùng Google Workspace và Notion, ghim các liên kết quan trọng trong phần mô tả của nhóm làm việc. |
| Câu nói đáng chú ý | Người được hỏi cho biết nhóm quen dùng Google Drive nên cứ làm chung trên đó, hiếm khi bị lẫn file (diễn đạt lại, không phải nguyên văn). |
| Tín hiệu xác nhận hoặc phản bác | Đối chứng một phần: không gặp pain, mất ít thời gian vì đã có quy trình đủ tốt từ đầu; không đủ để kết luận mọi nhóm đều không gặp vấn đề. |
| Insight cho nhóm | Khi nhóm có một thư mục chung và quy tắc rõ ngay từ đầu, vấn đề gần như không xảy ra. Đây là bằng chứng cho phương án No AI ở nhóm có quy trình, và cho thấy người dùng mục tiêu nên giới hạn ở nhóm chưa có quy trình như vậy. |

#### Tổng hợp kết quả kiểm chứng

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Ý nghĩa với nhóm |
|---|---:|---|---|---|
| Báo cáo cá nhân CP1–CP2 của Trần Quang Nam | 1 trường hợp | Trong tháng trước xảy ra 4 lần tìm lại tài liệu; lần gần nhất mất 18 phút để kiểm tra 5 file. | Chưa chứng minh trải nghiệm này phổ biến với người ngoài nhóm. | Đây là baseline case ban đầu, chưa dùng để khái quát cho mọi sinh viên. |
| Phỏng vấn ngoài nhóm (09/11/2026) | 3 | 2/3 người gặp 4–6 file rải rác qua Messenger, Zalo, Drive cá nhân và đều gặp khó khi xác định bản mới nhất. Họ tự ước lượng mất khoảng 2,5–3 giờ mỗi lần gom và chỉnh format, tần suất từ 2 lần/tháng đến 1 lần/tuần. | 1/3 người (ngành MKT) không gặp pain: nhóm dùng thư mục Drive chung và Notion từ đầu, lấy file chưa tới 5 phút. Ngoài ra, người thứ 2 đã có Google Docs chung nhưng file vẫn rải rác do thành viên không tuân thủ. | Pain có thật ở nhóm có file chỉnh sửa độc lập và chưa có quy trình chung. Phần tốn thời gian nhất là gom nối và sửa format, không chỉ xác định phiên bản. Nhóm đã có quy trình một nguồn chung gần như không gặp vấn đề. |

#### Nhóm đã sửa problem thế nào sau kiểm chứng

- **Actor:** Thu hẹp từ "sinh viên làm bài nhóm" thành sinh viên làm bài nhóm có nhiều file chỉnh sửa độc lập (báo cáo, đồ án) và chưa có quy trình một nguồn chung. Nhóm đã dùng Drive/Notion ngay từ đầu nằm ngoài phạm vi.
- **Bottleneck:** Khâu tốn thời gian nhất là gom các file rải rác, so sánh thủ công, ghép nội dung và sửa lỗi format, không chỉ là xác định bản mới nhất. Nguyên nhân gồm file phân tán qua nhiều kênh và thành viên không tuân thủ quy tắc chung.
- **Impact / metric:** Giữ baseline của Nam (18 phút/5 file) cho bước tìm bản mới nhất. Thêm số liệu phỏng vấn (khoảng 150–180 phút/đợt gom và hoàn thiện, do người được hỏi tự ước lượng, n=2) làm tham chiếu riêng cho bước tổng hợp. Hai chỉ số này đo hai bước khác nhau.
- **Mức can thiệp:** Chọn **No AI cho pilot**, còn việc xây hệ thống AI riêng là **No-Go ở giai đoạn hiện tại**. Phạm vi pilot chỉ là xác định đúng phiên bản tài liệu chính thức; không bao gồm gom/ghép nội dung giữa các file, sửa font, sửa bảng hoặc định dạng báo cáo. Kết quả phỏng vấn cho thấy một nguồn chung có thể đủ khi nhóm tuân thủ quy tắc, nhưng việc tuân thủ cần được đo trong pilot.
- **Lý do thay đổi:** Phỏng vấn cho thấy pain rộng hơn ở khâu gom nối và định dạng (2/3 người), nhưng nhóm không đủ dữ liệu để thiết kế và đo một can thiệp cho toàn bộ khâu đó trong lab. Vì vậy, nhóm giữ scope hẹp, đo được là xác định phiên bản; các vấn đề ghép nội dung và định dạng được ghi nhận là ngoài phạm vi pilot và là hướng nghiên cứu tiếp theo.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Docs — Version History | https://support.google.com/docs/answer/190843?hl=en | Xem lịch sử chỉnh sửa, xác định ai sửa và khi nào, xem hoặc khôi phục phiên bản trước. | Cho phép nhiều người làm việc trên một tài liệu và theo dõi các thay đổi mà không cần tạo nhiều bản sao. | Không tự xác định được bản chính thức nếu nhóm đang sử dụng nhiều file riêng biệt. Cần quyền chỉnh sửa để xem lịch sử phiên bản. | Nên thống nhất một tài liệu chung và sử dụng lịch sử phiên bản trước khi cân nhắc AI. |
| Google Drive — Manage Versions | https://support.google.com/drive/answer/2409045 | Quản lý các phiên bản của cùng một file, tải lên phiên bản mới, xem hoặc tải lại phiên bản cũ. | Có thể quản lý các bản cập nhật của tài liệu tải lên, bao gồm các định dạng không phải Google Docs. | Lịch sử phiên bản chỉ giúp quản lý các bản của cùng một file, không tự xác định bản chính thức giữa nhiều file độc lập. | Chuẩn hóa nơi lưu trữ và quy trình cập nhật file có thể giảm đáng kể thời gian tìm kiếm. |
| Microsoft OneDrive — Version History | https://support.microsoft.com/en-us/onedrive/restore-a-previous-version-of-a-file-stored-in-onedrive | Xem và khôi phục những phiên bản trước của file lưu trong OneDrive. | Hỗ trợ lịch sử phiên bản của nhiều loại file, bao gồm tài liệu Office và PDF. | Phụ thuộc vào cách lưu trữ, quyền truy cập và cấu hình quản lý phiên bản. Không tự giải quyết được việc nhiều thành viên giữ các bản sao độc lập. | Có thể sử dụng công cụ quản lý phiên bản sẵn có thay vì xây dựng hệ thống AI mới. |

**Kết luận research:**

- Các công cụ hiện có đã hỗ trợ lưu trữ, theo dõi và khôi phục phiên bản tài liệu.
- Nguyên nhân có thể không nằm ở việc thiếu công nghệ, mà ở việc nhóm chưa thống nhất nơi lưu trữ và quy tắc xác định tài liệu chính thức.
- Nếu tất cả thành viên cùng chỉnh sửa một file chung có lịch sử phiên bản, nhu cầu tìm kiếm và đối chiếu nhiều bản sao có thể giảm đáng kể.
- Về mặt giả thuyết, AI có thể được cân nhắc cho bước so sánh hoặc tóm tắt khác biệt giữa các file độc lập; tuy nhiên, nhóm chưa kiểm chứng độ chính xác và chưa có bộ eval nên chưa chọn hướng này. AI cũng không thể tự xác định phiên bản chính thức nếu nhóm chưa thống nhất quy tắc.
- Vì vậy, nên thử phương án No AI trước: sử dụng một tài liệu chung, quy tắc đặt tên và lịch sử chỉnh sửa. Chỉ cân nhắc mức can thiệp AI cao hơn nếu kiểm chứng cho thấy các phương án đơn giản chưa đáp ứng nhu cầu.
- Chưa đủ bằng chứng để kết luận nhóm cần xây dựng một hệ thống AI riêng.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

**Bối cảnh:** Khi nhóm sinh viên chuẩn bị chỉnh sửa hoặc nộp bài, các thành viên gửi nhiều phiên bản tài liệu qua hội thoại. Người phụ trách phải tìm và xác định phiên bản mới nhất trước khi tiếp tục công việc.

**Sơ đồ quy trình hiện tại:**

```text
HIỆN TẠI — 18 phút/lần

[1. Mở lại hội thoại nhóm: 2 phút]
                  |
                  v
[2. Tìm và tải các file đã chia sẻ: 4 phút]
                  |
                  v
[3. Kiểm tra tên file và thời gian cập nhật: 3 phút]
                  |
                  v
[4. Mở và so sánh nội dung các phiên bản: 7 phút]
                  |
                  | <-- BOTTLENECK
                  v
[5. Xác định phiên bản cuối cùng: 2 phút]
                  |
                  v
[Tiếp tục chỉnh sửa hoặc nộp bài]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Thành viên nhóm | Hội thoại nhóm trên Zalo hoặc ứng dụng nhắn tin | Danh sách tin nhắn có chứa tài liệu | 2 phút/lần | Phải tìm lại hội thoại cũ |
| 2 | Thành viên nhóm | Các file được chia sẻ | Các phiên bản tài liệu cần kiểm tra | 4 phút/lần | File phân tán trong nhiều tin nhắn |
| 3 | Thành viên nhóm | Tên file và thời gian cập nhật | Danh sách các phiên bản có khả năng là bản mới nhất | 3 phút/lần | Tên file và thời gian gửi chưa chắc phản ánh nội dung mới nhất |
| 4 | Thành viên nhóm | Nội dung của các phiên bản | Xác định điểm khác biệt giữa các file | 7 phút/lần | BOTTLENECK: Phải mở và đối chiếu thủ công từng file |
| 5 | Thành viên nhóm | Kết quả so sánh các file | Phiên bản được xác định để tiếp tục chỉnh sửa | 2 phút/lần | Có nguy cơ chọn nhầm bản cũ nếu chưa được nhóm xác nhận |

**Bottleneck chính:**

Bước 4 — Mở và so sánh nội dung giữa các phiên bản tài liệu, mất khoảng 7 phút trong lần kiểm tra được ghi nhận.

Nguyên nhân là các thành viên gửi nhiều bản sao tài liệu qua hội thoại mà không có quy ước thống nhất về phiên bản chính thức.

Theo báo cáo cá nhân của Trần Quang Nam, việc tìm lại tài liệu xảy ra 4 lần trong tháng trước. Lần gần nhất mất 18 phút để kiểm tra 5 file.

### 4.2. Quy trình tương lai

**Phương án đề xuất:** Sử dụng một tài liệu chung được lưu tại một vị trí thống nhất, kết hợp lịch sử phiên bản có sẵn trong Google Docs hoặc Google Drive.

**Phạm vi pilot:** Chỉ đo bước xác định phiên bản chính thức trước khi chỉnh sửa hoặc nộp. Pilot **không** đo và không cam kết giải quyết việc ghép nội dung từ nhiều file, sửa font/căn lề/bảng hoặc định dạng báo cáo; các việc đó cần được ghi nhận riêng nếu phát sinh.

**Sơ đồ quy trình tương lai:**

```text
TƯƠNG LAI — Dự kiến 4 phút/lần

[1. Mở tài liệu chung từ liên kết cố định: 1 phút]
                  |
                  v
[2. Xem lịch sử chỉnh sửa khi cần: 1 phút]
                  |
                  v
[3. Kiểm tra thay đổi và trạng thái tài liệu: 1 phút]
                  |
                  v
[4. Xác nhận phiên bản chính thức: 1 phút]
                  |
                  v
[Tiếp tục chỉnh sửa hoặc nộp bài]

No AI:
- Thống nhất một file chính thức.
- Quy định nơi lưu trữ và cách cập nhật.
- Không tạo nhiều bản sao không cần thiết.

Rule / chức năng có sẵn:
- Nền tảng lưu lịch sử chỉnh sửa.
- Hiển thị thời điểm và người cập nhật.
- Cho phép xem hoặc khôi phục phiên bản cũ.

AI:
- Không sử dụng ở phương án ban đầu.

CON NGƯỜI:
- Kiểm tra nội dung cập nhật.
- Xác nhận phiên bản chính thức.
- Quyết định chỉnh sửa hoặc nộp bài.
```

**Boundary:**

- Không tự động xác định một file là phiên bản chính thức nếu chưa có sự xác nhận của nhóm.
- Không tự động xóa, ghi đè hoặc khôi phục phiên bản cũ khi chưa được người phụ trách đồng ý.
- Không cấp quyền truy cập tài liệu cho người ngoài nhóm.
- Người phụ trách vẫn phải kiểm tra nội dung trước khi nộp bài.

**Phương án quay về:**

- Nếu không truy cập được tài liệu chung, sử dụng bản sao lưu gần nhất đã được nhóm xác nhận.
- Nếu lịch sử phiên bản không đủ để xác định bản chính thức, liên hệ trưởng nhóm hoặc người phụ trách tài liệu.
- Nếu nhiều bản sao xuất hiện trở lại, tạm thời sử dụng quy trình đối chiếu thủ công trước khi thống nhất lại file chính thức.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---|---|---|
| Số bước | 5 | 4 | Giảm thao tác tìm và tải nhiều file |
| Tổng thời gian | 18 phút/lần | Khoảng 4 phút/lần | Số liệu sau là mục tiêu ước tính, cần kiểm chứng |
| Số bước thủ công | 5/5 | 4/4 | Người dùng vẫn thao tác, nhưng có lịch sử phiên bản hỗ trợ |
| Bottleneck chính | So sánh nội dung nhiều file, 7 phút | Kiểm tra và xác nhận thay đổi | Giảm nhu cầu mở nhiều bản sao |
| Rủi ro mới phát sinh | Chọn nhầm phiên bản cũ | Chỉnh sửa nhầm file, thiếu quyền truy cập hoặc khôi phục sai phiên bản | Cần phân quyền và xác nhận trước khi thay đổi |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên tham gia làm bài tập nhóm, đặc biệt là người phụ trách tổng hợp, chỉnh sửa và nộp báo cáo. |
| **Quy trình** | Khi cần chỉnh sửa bài nhóm, sinh viên phải mở lại hội thoại, tìm các file được chia sẻ, kiểm tra thời gian cập nhật, so sánh nội dung và xác định phiên bản cuối cùng. |
| **Bottleneck** | Bước mở và so sánh nội dung giữa các phiên bản tài liệu mất khoảng 7 phút do nhiều bản sao được chia sẻ ở các thời điểm khác nhau. |
| **Impact** | Trong tháng trước, Nam phải tìm lại tài liệu 4 lần. Lần gần nhất mất 18 phút kiểm tra 5 file. Việc chọn nhầm bản cũ có thể dẫn đến mất nội dung chỉnh sửa hoặc phải làm lại công việc. |
| **Success Metric** | Baseline: 18 phút/lần trong trường hợp đã ghi nhận → Target: dưới 5 phút/lần. Đo bằng cách bấm giờ khi xác định phiên bản chính thức ở ít nhất 5 tình huống thử nghiệm và đối chiếu với bản được nhóm xác nhận. Mục tiêu không chọn nhầm phiên bản. |
| **Boundary** | Không tự động thay đổi, xóa hoặc xác nhận tài liệu chính thức thay người dùng. Người phụ trách phải kiểm tra và xác nhận phiên bản trước khi chỉnh sửa hoặc nộp bài. |

**Phản biện nhận được (từ AI) và đánh giá của nhóm:**

1. Baseline 18 phút chỉ dựa trên một trường hợp được ghi nhận, chưa đại diện cho tất cả sinh viên. Đồng ý — cần đo thêm ở các lần thực hiện khác.
2. Vấn đề có thể xuất phát từ quy trình quản lý file chưa thống nhất, không nhất thiết phải dùng AI. Đồng ý — ưu tiên thử phương án sử dụng một tài liệu chung.
3. Chỉ giảm thời gian là chưa đủ, vì người dùng vẫn có thể chọn nhầm phiên bản. Đồng ý — bổ sung tiêu chí xác định đúng phiên bản chính thức.
4. Chưa có bằng chứng đầy đủ từ người dùng ngoài nhóm. Đồng ý — tiếp tục kiểm chứng trước khi mở rộng phạm vi bài toán.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô: Độ mơ hồ thấp × Độ phức tạp thấp**, với điều kiện nhóm đã thống nhất một nguồn tài liệu chính thức.

**Vì sao:**

- Quy trình xác định phiên bản tài liệu có các bước tương đối rõ ràng.
- Khi có một tài liệu chính thức, người dùng có thể xem lịch sử chỉnh sửa để kiểm tra thay đổi.
- Không cần AI tạo nội dung mới hoặc tự đưa ra quyết định phức tạp.
- Bài toán chủ yếu liên quan đến quản lý file, đối chiếu phiên bản và tuân thủ quy trình.
- Nếu nhóm vẫn sử dụng nhiều file độc lập, mức độ mơ hồ có thể tăng vì không có cơ sở chắc chắn để xác định bản chính thức.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Sử dụng một file chung, thống nhất nơi lưu trữ, phân quyền và quy tắc cập nhật tài liệu. | Khi các thành viên có thể cùng chỉnh sửa một tài liệu và tuân thủ quy trình chung. | Thành viên không tuân thủ quy định hoặc tiếp tục tạo bản sao riêng. | **Chọn thử nghiệm trước** |
| **Rule** | Sử dụng script hoặc quy tắc tự động kiểm tra tên file, thời gian cập nhật và thông báo khi có bản mới. | Khi nhóm có dữ liệu có cấu trúc và cần tự động hóa thao tác lặp lại. | Thời gian cập nhật không luôn phản ánh phiên bản chính thức. | Chưa cần |
| **Workflow** | Sử dụng AI hỗ trợ so sánh nội dung nhiều file, tạo bảng khác biệt để người dùng xác nhận. | Khi vẫn cần xử lý nhiều phiên bản độc lập có nội dung phức tạp. | AI có thể bỏ sót thay đổi hoặc nhận diện sai nội dung quan trọng. | Chưa chọn |
| **Agent** | AI tự tìm kiếm các file, so sánh, quyết định phiên bản và đề xuất thao tác tiếp theo. | Chỉ cân nhắc nếu quy trình thực sự phức tạp và không thể xác định trước các bước. | Khó kiểm soát, cần nhiều quyền truy cập và có nguy cơ tác động sai lên tài liệu. | Không chọn |

**Mức chọn: No AI.**

**Vì sao không chọn mức đơn giản hơn:**

No AI đã là mức can thiệp đơn giản nhất. Vì vậy không có mức thấp hơn để so sánh.

**Vì sao không chọn mức cao hơn:**

- Các công cụ hiện có đã hỗ trợ lịch sử phiên bản và chỉnh sửa cộng tác.
- Bài toán có thể được cải thiện bằng cách thống nhất quy trình lưu trữ.
- Chưa có bằng chứng Rule hoặc AI sẽ mang lại lợi ích đủ lớn so với chi phí và rủi ro bổ sung.
- Cần kiểm chứng hiệu quả của phương án No AI trước khi cân nhắc Workflow hoặc Agent.

### 6.3. AI Canvas rút gọn

**Mức chọn là No AI nên AI Canvas không bắt buộc.**

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Không áp dụng. Không sử dụng AI để dự đoán phiên bản tài liệu chính thức. |
| **Judgment** — con người cân nhắc, quyết định gì? | Người phụ trách kiểm tra thay đổi và xác nhận tài liệu được phép chỉnh sửa hoặc nộp. |
| **Action** — hành động cuối cùng là gì, ai làm? | Thành viên nhóm mở tài liệu chung, kiểm tra và tiếp tục chỉnh sửa. Trưởng nhóm hoặc người được phân công xác nhận phiên bản cuối. |
| **Outcome** — đo kết quả bằng gì? | Thời gian xác định đúng phiên bản; số lần chọn nhầm file; tỷ lệ các thành viên tuân thủ quy trình. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Không cần đầu vào cho AI. Quy trình sử dụng tài liệu chung, lịch sử chỉnh sửa và quy định quản lý file. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Nhật ký thời gian, các trường hợp chọn nhầm file và phản hồi trực tiếp của thành viên nhóm. |

### 6.4. Hai câu hỏi của Google PAIR

Vì nhóm lựa chọn No AI, phần Google PAIR không bắt buộc. Tuy nhiên, nhóm vẫn có thể sử dụng hai câu hỏi để đánh giá hướng can thiệp trong tương lai.

**1. Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)?**

Giả thuyết ban đầu là người dùng cần được hỗ trợ tìm và kiểm tra phiên bản nhanh hơn, nhưng vẫn muốn tự xác nhận tài liệu chính thức.

Chưa có đủ bằng chứng phỏng vấn để khẳng định người dùng muốn tự động hóa hoàn toàn.

**2. AI sai kiểu nào tệ hơn — báo nhầm hay bỏ sót?**

Nếu sau này triển khai AI, báo nhầm một phiên bản cũ thành bản mới nhất có thể nghiêm trọng vì khiến nhóm chỉnh sửa hoặc nộp sai tài liệu.

Bỏ sót một phiên bản có cập nhật quan trọng cũng có thể khiến nhóm mất nội dung.

Vì vậy, mọi đề xuất từ AI (nếu triển khai trong tương lai) cần có nguồn đối chiếu và người kiểm tra trước khi sử dụng.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Thành viên sinh viên chịu trách nhiệm xác định phiên bản tài liệu chính thức trước khi chỉnh sửa hoặc nộp bài nhóm, trong bối cảnh có nhiều file độc lập. |
| **Quy trình** | Khi có nhiều file hoặc liên kết, thành viên tìm nguồn đã được nhóm quy định, kiểm tra lịch sử/thời điểm thay đổi, đối chiếu với người phụ trách và xác định bản chính thức trước khi chỉnh sửa hoặc nộp. |
| **Bottleneck** | Việc xác định file nào là bản chính thức mất thời gian vì tài liệu phân tán và chưa có quy ước chung; trong baseline, bước mở/đối chiếu mất khoảng 7 phút/lần. |
| **Impact** | Lần kiểm tra gần nhất mất 18 phút với 5 file. Việc quản lý nhiều bản sao gây lãng phí thời gian và có nguy cơ chỉnh sửa nhầm phiên bản. |
| **Success Metric** | Giảm thời gian xác định phiên bản từ 18 phút/lần (trường hợp đã ghi nhận) xuống dưới 5 phút/lần trong các tình huống thử nghiệm. Không chọn nhầm phiên bản được nhóm xác nhận. Đo bằng bấm giờ và kiểm tra kết quả với người phụ trách tài liệu. |
| **Boundary** | Pilot không bao gồm ghép nội dung, sửa font/căn lề/bảng hoặc định dạng báo cáo. Không tự động xóa, ghi đè hay khôi phục phiên bản; người phụ trách phải xác nhận khi có mâu thuẫn trước khi chỉnh sửa hoặc nộp bài. |
| **AI intervention point** | Không có. Nhóm ưu tiên cải thiện quy trình và sử dụng tính năng lịch sử phiên bản có sẵn. |
| **Mức chọn** | No AI |
| **Rủi ro & người kiểm tra** | Rủi ro gồm thành viên sử dụng nhầm liên kết, tạo bản sao riêng hoặc khôi phục sai phiên bản. Trưởng nhóm và người phụ trách tài liệu có trách nhiệm kiểm tra, xác nhận bản chính thức. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Sinh viên tham gia làm bài tập nhóm nói chung. | Tập trung vào thành viên cần tổng hợp, chỉnh sửa hoặc nộp tài liệu có nhiều phiên bản. | Thu hẹp phạm vi để dễ đo lường và kiểm chứng. |
| Quy trình | Tìm file trong hội thoại, tải nhiều phiên bản rồi đối chiếu. | Sử dụng một nguồn tài liệu chính thức và kiểm tra lịch sử chỉnh sửa. | Đề xuất từ việc phân tích bottleneck và nghiên cứu các chức năng có sẵn. |
| Success Metric | Giảm thời gian từ 18 phút xuống dưới 5 phút. | Giữ mục tiêu thời gian, bổ sung điều kiện không chọn nhầm phiên bản. | Giảm thời gian nhưng chọn sai file thì vẫn không giải quyết được vấn đề. |
| Boundary | Người dùng kiểm tra trước khi chỉnh sửa hoặc nộp. | Bổ sung quy định không tự xóa, ghi đè hoặc khôi phục phiên bản. | Giảm nguy cơ mất dữ liệu hoặc sử dụng nhầm tài liệu. |
| Mức can thiệp | Chưa xác định. | No AI. | Các công cụ hiện có có thể đáp ứng nhu cầu cơ bản mà chưa cần AI. |

**Tiêu chí đánh giá giải pháp No AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Thời gian tìm phiên bản | Xác định được phiên bản chính thức trong dưới 5 phút/lần. | Mất từ 5 phút trở lên. |
| 2 | Độ chính xác | 100% tình huống thử nghiệm chọn đúng bản được người phụ trách xác nhận. | Có ít nhất một lần chọn nhầm phiên bản. |
| 3 | Tính thống nhất | Mọi thành viên sử dụng đúng liên kết tài liệu chính thức trong các lần thử nghiệm. | Có thành viên tiếp tục chỉnh sửa bản sao ngoài quy trình. |
| 4 | Khả năng truy vết | Người phụ trách xem được các thay đổi và xác định được bản cần sử dụng. | Không xác định được nguồn gốc hoặc lịch sử của thay đổi quan trọng. |
| 5 | Khả năng phục hồi | Có thể truy cập hoặc khôi phục phiên bản phù hợp khi phát hiện chỉnh sửa sai. | Không có cách phục hồi hoặc làm mất nội dung quan trọng. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Trung bình | Nam đã ghi nhận 4 lần tìm lại tài liệu trong một tháng, lần gần nhất mất 18 phút. Phỏng vấn 3 người ngoài nhóm cho tín hiệu ban đầu 2/3 xác nhận pain, 1/3 là đối chứng; mẫu nhỏ và số liệu tự ước lượng. |
| **Usability** | Người dùng có dùng được và tuân thủ quy trình mới không? | Trung bình | 2/3 người được hỏi mô tả pain khi các thành viên làm trên file độc lập; 1/3 không gặp pain vì đã dùng Drive/Notion và quy tắc chung từ đầu. Pilot vẫn cần đo việc tuân thủ ở các case thực tế. |
| **Feasibility** | Có đủ dữ liệu, công cụ và kỹ năng để làm không? | Thấp | Google Docs, Google Drive và OneDrive đã có các chức năng quản lý lịch sử phiên bản. Không cần xây hệ thống AI riêng. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Có thể thử trên công cụ nhóm đang sử dụng mà không cần phát triển sản phẩm mới. Người phụ trách tài liệu quản lý quyền truy cập và quy trình cập nhật. Cần kiểm tra hạn mức, chính sách tài khoản thực tế. |

### 8.2. Kết luận

**Quyết định: Go với pilot quy trình No AI trong 2 tuần; No-Go đối với việc xây dựng hệ thống AI riêng ở giai đoạn hiện tại.**

**Lý do:**

- Vấn đề đã có bằng chứng ban đầu từ trải nghiệm thực tế.
- Bottleneck chủ yếu xuất phát từ việc quản lý nhiều phiên bản tài liệu chưa thống nhất.
- Các chức năng quản lý phiên bản đã tồn tại trong những công cụ phổ biến.
- Chưa có bằng chứng cho thấy AI mang lại lợi ích đủ lớn so với phương án sửa quy trình.
- Việc xây dựng AI có thể làm tăng chi phí, độ phức tạp và rủi ro liên quan đến dữ liệu.

**Nếu Go — pilot nhỏ nhất:**

Go với quy trình No AI trong 2 tuần. Mỗi case chỉ đo thời gian xác định đúng phiên bản tài liệu chính thức và kết quả xác nhận; không tính việc ghép nội dung, sửa định dạng hoặc hoàn thiện báo cáo vào success metric của pilot.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Thu thập thêm dữ liệu từ sinh viên ngoài nhóm.
- Kiểm tra liệu một file chung có giảm được thời gian tìm kiếm hay không.
- Đánh giá mức độ tuân thủ quy trình của các thành viên.

**Nếu No-Go — nên làm gì thay AI:**

1. Tạo một thư mục tài liệu chung cho nhóm.
2. Quy định một file chính thức cho mỗi báo cáo.
3. Sử dụng lịch sử phiên bản thay vì tạo nhiều bản sao.
4. Phân quyền chỉnh sửa và xác định người phụ trách xác nhận phiên bản cuối.
5. Ghim liên kết tài liệu chính thức trong nhóm chat.
6. Thử nghiệm quy trình trong 2 tuần, ghi nhận thời gian và các trường hợp chọn nhầm file.

**Ngưỡng dừng:**

- Sau 2 tuần và tối thiểu 5 case hợp lệ, nếu có từ 3/5 case trở lên mất **từ 5 phút/lần trở lên**, nhóm dừng pilot và đánh giá lại quy trình.
- Nếu xuất hiện ít nhất một lần chọn nhầm phiên bản chính thức, cần kiểm tra và sửa quy tắc xác nhận trước khi tiếp tục.
- Nếu phương án No AI không đạt ngưỡng trên, nhóm chưa chuyển ngay sang Agent; trước hết phải xem lại quy tắc lưu trữ, tuân thủ và dữ liệu ghi nhận rồi mới cân nhắc Rule/Workflow.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- Baseline 18 phút mới được ghi nhận từ một trường hợp cụ thể.
- Thời gian của từng bước trong quy trình hiện tại là số liệu ước tính từ báo cáo cá nhân.
- Mới phỏng vấn 3 người ngoài nhóm; kết quả 2/3 xác nhận và 1/3 đối chứng chỉ là tín hiệu ban đầu, không đại diện cho mọi sinh viên.
- Thời gian tương lai 4 phút/lần mới là kỳ vọng, chưa được thử nghiệm.
- Hiệu quả của phương án No AI phụ thuộc vào việc các thành viên tuân thủ quy trình chung.
- Pilot chỉ xử lý bước xác định phiên bản; việc ghép nội dung, sửa font/bảng và định dạng báo cáo được loại khỏi phạm vi nên chưa có số liệu đánh giá cho các việc đó.

**Hướng tiếp theo:**

1. Phỏng vấn bổ sung sinh viên thường xuyên làm bài tập nhóm.
2. Ghi nhận thời gian tìm phiên bản tài liệu trong ít nhất 5 tình huống có quy mô tương đương.
3. Thử nghiệm phương án một file chung trong 2 tuần.
4. Đo thời gian tìm kiếm, số lần chọn nhầm phiên bản và mức độ tuân thủ quy trình.
5. So sánh kết quả thực tế với mục tiêu dưới 5 phút/lần.
6. Nếu chưa đạt, xác định nguyên nhân và đánh giá có cần Rule hoặc Workflow để hỗ trợ thêm hay không.

---

## 10. Tài liệu tham khảo

1. Google Docs Editors Help — Find what's changed in a file (Version History).
   https://support.google.com/docs/answer/190843

2. Google Drive Help — Check activity & file versions.
   https://support.google.com/drive/answer/2409045

3. Microsoft Support — Restore a previous version of a file stored in OneDrive.
   https://support.microsoft.com/en-us/onedrive/restore-a-previous-version-of-a-file-stored-in-onedrive

4. Báo cáo cá nhân của Trần Quang Nam — 2A202603516_TranQuangNam.md, mục CP1 và CP2.

5. Báo cáo cá nhân của Đoàn Văn Hiệp — 2A202603565_DoanVanHiep.md, mục CP1 và CP2.

6. Báo cáo cá nhân của Nguyễn Bá Quảng — 2A202603555_NguyenBaQuang.md, mục CP1 và CP2.
