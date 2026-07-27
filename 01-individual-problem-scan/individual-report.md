# Phase 1 — Individual Problem Scan

## 1. Bối cảnh quan sát

<!-- Mô tả ngắn vai trò, môi trường học tập/công việc và các workflow thường gặp. -->


## 2. Scan vấn đề theo bốn lăng kính

### 2.1. Lặp lại

<!-- Việc gì xuất hiện đều đặn mỗi ngày, tuần hoặc tháng? -->


### 2.2. Tốn thời gian

<!-- Việc gì mất nhiều thời gian ở bước tìm kiếm, đọc hiểu, tổng hợp, chờ đợi hoặc sửa lại? -->


### 2.3. AI có thể hỗ trợ tốt hơn

<!-- Bước nào cần đọc, viết, phân loại, so sánh hoặc tổng hợp ngữ cảnh? -->


### 2.4. Khó khăn đến từ người khác

<!-- Ai đang hỏi lại, phàn nàn, hiểu sai hoặc bỏ sót bước nào? -->


## 3. Bảng tổng hợp problem scan

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? (Actor) | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |
| 5 |  |  |  |  |
| 6 |  |  |  |  |
| 7 |  |  |  |  |
| 8 |  |  |  |  |
| 9 |  |  |  |  |
| 10 |  |  |  |  |

> Dấu hiệu thật có thể gồm: thời gian mỗi lần, tần suất, số người gặp, log/ticket/comment, hậu quả hoặc workaround hiện tại.

## 4. Problem tự quan sát trước khi hỏi AI

<!-- Ghi rõ những problem được tự quan sát trước khi sử dụng AI. -->

| # | Problem tự quan sát | Vì sao đây là pain thật? | Bằng chứng hiện có |
|---:|---|---|---|
| 1 |  |  |  |
| 2 |  |  |  |
| 3 |  |  |  |
| 4 |  |  |  |
| 5 |  |  |  |

## 5. Gợi ý bổ sung từ AI (nếu có)

<!-- Chỉ điền phần này sau khi đã có ít nhất 5 problem tự quan sát. -->

| # | Gợi ý của AI | Giữ hay loại? | Lý do |
|---:|---|---|---|
| 1 |  |  |  |
| 2 |  |  |  |
| 3 |  |  |  |

## 6. Kết quả sau khi loại bỏ ý không thực tế

<!-- Ghi lại danh sách problem cuối cùng sau khi loại các ý không xuất phát từ trải nghiệm thật. -->


## 7. Ghi chú về việc sử dụng AI

<!-- AI được hỏi ở thời điểm nào, hỗ trợ điều gì và gợi ý nào đã bị loại? -->


## 8. Self-check Phase 1

- [ ] Tôi đã tự quan sát trước khi hỏi AI.
- [ ] Tôi có ít nhất 5 problem cụ thể.
- [ ] Danh sách phủ nhiều lăng kính.
- [ ] Mỗi problem có actor rõ.
- [ ] Mỗi problem có dấu hiệu thật hoặc cách thu thập bằng chứng.
- [ ] Tôi đã loại các ý không xuất phát từ trải nghiệm thực tế.
- [ ] Tôi chưa nhảy sang chọn giải pháp hoặc Agent.

---

# Phase 2 — Top 3 Problem Cards và Draft Workflow

> Phase 1 tạm thời được bỏ qua theo tiến độ hiện tại. Phase 2 sử dụng trực tiếp ba problem đã quan sát. Các target chưa được kiểm chứng được ghi rõ là **mục tiêu pilot**, không được coi là dữ liệu thật.

## 1. Xếp hạng Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Điều chỉnh CV và Cover Letter theo từng JD | Actor và workflow rõ; xảy ra 10–20 lần trong một kỳ tìm việc; có baseline khoảng 20 phút cho mỗi công ty nên impact thời gian dễ đo. | Chưa có dữ liệu chứng minh việc cá nhân hóa làm tăng tỷ lệ được phản hồi; chưa biết phần nào của 20 phút tốn nhiều nhất. |
| 2 | Nhận feedback chi tiết cho IELTS Writing trong thời gian gấp | Pain có baseline rõ: phải chờ 3–5 ngày; output có thể kiểm theo bốn tiêu chí IELTS Writing; phù hợp với mô hình AI hỗ trợ trước, giáo viên kiểm tra sau. | Chưa biết độ nhất quán giữa feedback AI và giáo viên; “feedback chi tiết” cần được định nghĩa bằng checklist cụ thể. |
| 3 | Tìm trợ giúp chuyên môn nhưng bị phớt lờ hoặc phản hồi toxic | Có dấu hiệu thật từ ba bài đã đăng; impact không chỉ là thời gian mà còn ảnh hưởng động lực và tâm lý của người hỏi. | Mẫu quan sát mới có ba bài; loại câu hỏi và cộng đồng chưa được ghi rõ; advice sai có thể gây hại và AI không thể thay thế cộng đồng/mentor trong mọi trường hợp. |

## 2. Problem Card #1 — Điều chỉnh CV và Cover Letter theo JD

### Problem một câu

Sinh viên hoặc người mới tốt nghiệp đang tìm việc phải mất khoảng 20 phút để điều chỉnh CV và Cover Letter cho từng JD; với 10–20 công ty trong một kỳ tìm việc, workflow này lặp lại nhiều lần và làm giảm thời gian dành cho tìm hiểu doanh nghiệp, luyện phỏng vấn và nâng cao kỹ năng.

### Actor

- **Actor chính:** sinh viên năm cuối hoặc người mới tốt nghiệp đang chủ động ứng tuyển.
- **Stakeholder liên quan:** nhà tuyển dụng nhận và sàng lọc hồ sơ.

Nhà tuyển dụng là stakeholder chứ không phải actor chính của pain “mất thời gian điều chỉnh hồ sơ”.

### Thời điểm / bối cảnh

Mỗi lần ứng viên tìm được một JD phù hợp và chuẩn bị nộp hồ sơ cho doanh nghiệp.

### Current workflow

1. Đọc JD và đánh dấu trách nhiệm, kỹ năng, từ khóa quan trọng.
2. So sánh yêu cầu của JD với CV gốc và kinh nghiệm thật.
3. Chọn nội dung cần giữ, bỏ hoặc đổi thứ tự trong CV.
4. Viết lại bullet points để nhấn mạnh phần liên quan.
5. Viết hoặc chỉnh Cover Letter cho doanh nghiệp.
6. Kiểm tra lỗi, xuất file và nộp.

### Bottleneck

Cụm bước 2–5: phải hiểu JD, đối chiếu với nhiều trải nghiệm cá nhân và diễn đạt lại mà không làm sai sự thật. Tổng workflow hiện mất khoảng **20 phút cho mỗi công ty**.

### Impact

- Một kỳ tìm việc thường nộp 10–20 công ty.
- Tổng effort ước tính: `20 phút × 10–20 hồ sơ = 200–400 phút`, tương đương khoảng **3 giờ 20 phút đến 6 giờ 40 phút**.
- Việc lặp lại có thể khiến ứng viên dùng một CV chung cho mọi vị trí hoặc bỏ qua một số cơ hội.

### Success metric

Mục tiêu pilot:

- giảm thời gian điều chỉnh một bộ CV + Cover Letter từ khoảng 20 phút xuống **không quá 10 phút**;
- 100% bullet point cuối cùng phải dựa trên kinh nghiệm thật đã có trong CV gốc hoặc thông tin do ứng viên cung cấp;
- ứng viên phải kiểm tra và approve trước khi nộp;
- theo dõi tỷ lệ hồ sơ nhận phản hồi trước/sau pilot, nhưng chưa khẳng định AI sẽ làm tỷ lệ này tăng.

### Non-AI alternative

- Duy trì một master CV chứa toàn bộ kinh nghiệm.
- Chuẩn bị 2–3 CV template theo nhóm vị trí.
- Dùng checklist từ khóa và Cover Letter template có các vùng cần thay.
- Chỉ cá nhân hóa những phần có tác động cao thay vì viết lại toàn bộ hồ sơ.

### AI hypothesis

AI có thể trích xuất yêu cầu từ JD, đối chiếu với master CV, chỉ ra nội dung liên quan và đề xuất bản nháp. Ứng viên vẫn phải xác minh mọi claim, sửa giọng văn và quyết định bản cuối.

### Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

Workflow được chọn ở mức phỏng đoán ban đầu vì các bước có thứ tự cố định và cần human review; chưa có lý do để AI tự lập kế hoạch hoặc tự nộp hồ sơ như một Agent.

### Draft current workflow

```text
CURRENT STATE — khoảng 20 phút/hồ sơ

[Đọc và đánh dấu JD]
→ [So sánh JD với CV gốc]
→ [Chọn/đổi thứ tự nội dung]
→ [Viết lại bullet points]       <-- bottleneck
→ [Chỉnh Cover Letter]           <-- bottleneck
→ [Kiểm tra, xuất file và nộp]
```

### Draft future workflow

```text
FUTURE STATE — mục tiêu không quá 10 phút/hồ sơ

[Ứng viên cung cấp JD + master CV]
→ [Rule/AI trích xuất tiêu chí]
→ [AI đề xuất nội dung liên quan và draft]
→ [Ứng viên kiểm chứng từng claim]  <-- human boundary
→ [Ứng viên sửa giọng văn]
→ [Ứng viên tự xuất và nộp]

Fallback:
AI thêm claim không có thật hoặc hiểu sai JD
→ bỏ đề xuất đó
→ quay về master CV + template thủ công.

Boundary:
Không bịa kỹ năng, kinh nghiệm hoặc thành tích;
không tự gửi hồ sơ; không thay ứng viên quyết định nội dung cuối.
```

## 3. Problem Card #2 — Trợ giúp chuyên môn thiếu an toàn và thiếu phản hồi

### Problem một câu

Sinh viên có thắc mắc chuyên môn phải hỏi cộng đồng, bạn bè hoặc mentor nhưng có thể bị phớt lờ hay nhận phản hồi mỉa mai; việc này kéo dài quá trình giải quyết vấn đề, làm giảm động lực đặt câu hỏi và có thể ảnh hưởng tiêu cực đến tâm lý.

### Actor

- **Actor chính:** sinh viên hoặc người mới học một lĩnh vực đang cần giải đáp thắc mắc.
- **Stakeholder liên quan:** bạn bè, mentor, moderator và thành viên cộng đồng trả lời câu hỏi.

### Thời điểm / bối cảnh

Khi người học gặp bug hoặc không hiểu một khái niệm, đã thử tự giải quyết nhưng vẫn cần ý kiến từ người có kinh nghiệm.

### Current workflow

1. Gặp bug hoặc thắc mắc.
2. Tự tìm kiếm từ khóa trên Google, tài liệu hoặc Stack Overflow.
3. Viết và đăng câu hỏi lên cộng đồng.
4. Chờ phản hồi.
5. Đọc, đánh giá thái độ và độ tin cậy của phản hồi.
6. Thử giải pháp hoặc tiếp tục tìm ở nguồn khác.

### Bottleneck

Bước 3–5: kết quả phụ thuộc vào việc có người nhìn thấy và sẵn lòng trả lời; phản hồi có thể chậm, không liên quan hoặc toxic. Khi không có câu trả lời hữu ích, người học phải quay lại tìm kiếm từ đầu.

### Impact

- Quan sát hiện có: đăng ba bài hỏi bug thì hai bài bị bỏ qua và một bài nhận phản hồi mỉa mai.
- Trong mẫu nhỏ này, số bài nhận được phản hồi hữu ích là **0/3**.
- Người học mất thêm thời gian tìm Stack Overflow; thời gian cụ thể chưa được đo.
- Hệ quả tiềm ẩn: giảm động lực, ngại đặt câu hỏi và có thể phản ứng tiêu cực với người khác. Tác động tâm lý cần được hỏi trực tiếp, không suy diễn từ ba bài đăng.

### Success metric

Mục tiêu pilot:

- ít nhất 80% câu hỏi thử nghiệm nhận được một hướng xử lý có thể hành động trong vòng 15 phút;
- câu trả lời phải nêu giả định, bước kiểm tra và nguồn tham khảo khi có thể;
- người học đánh giá mức hữu ích từ 4/5 trở lên;
- lời khuyên chỉ được coi là đúng sau khi người học chạy thử hoặc đối chiếu tài liệu.

Baseline thời gian tìm kiếm và điểm hữu ích hiện chưa có, cần đo trước pilot.

### Non-AI alternative

- Dùng template hỏi bug gồm context, expected result, actual result, code tối thiểu và các bước đã thử.
- Tạo kênh hỏi đáp có moderator và quy tắc ứng xử.
- Tổ chức office hour hoặc ghép buddy/mentor.
- Dùng checklist tìm kiếm tài liệu trước khi đăng câu hỏi.

### AI hypothesis

AI có thể giúp người học viết lại câu hỏi cho rõ, hỏi thêm context còn thiếu, giải thích khái niệm và đề xuất các bước debug ban đầu. Với câu trả lời không chắc hoặc rủi ro cao, AI phải chỉ rõ giới hạn và chuyển sang tài liệu chính thức/mentor.

### Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — thời gian chưa đo

[Gặp bug/thắc mắc]
→ [Tự tìm Google/Stack Overflow]
→ [Viết và đăng câu hỏi]
→ [Chờ cộng đồng]                   <-- bottleneck không dự đoán được
→ [Có thể bị bỏ qua/toxic]
→ [Tiếp tục tìm hoặc bỏ cuộc]
```

### Draft future workflow

```text
FUTURE STATE — mục tiêu có next step trong 15 phút

[Người học mô tả vấn đề]
→ [Rule kiểm tra context tối thiểu]
→ [AI hỏi lại thông tin còn thiếu]
→ [AI gợi ý bước debug + nguồn]
→ [Người học chạy thử]              <-- human verification
→ [Chưa giải quyết được: chuyển mentor/cộng đồng]

Fallback:
AI không chắc hoặc giải pháp không chạy
→ giữ nguyên log/context
→ tạo câu hỏi chuẩn hóa để nhờ mentor/cộng đồng.

Boundary:
Không giả vờ chắc chắn; không đưa chẩn đoán sức khỏe tâm thần;
không thay moderator hoặc mentor trong tình huống phức tạp.
```

## 4. Problem Card #3 — Feedback IELTS Writing đến chậm và thiếu chi tiết

### Problem một câu

Sinh viên ôn IELTS trong thời gian gấp phải chờ khoảng 3–5 ngày để nhận feedback Writing từ giáo viên hoặc trung tâm; feedback đôi khi chỉ có band tổng mà không chỉ rõ lỗi và cách sửa, làm chậm vòng lặp viết–nhận xét–viết lại.

### Actor

- **Actor chính:** học viên đang ôn IELTS Writing với thời gian chuẩn bị hạn chế.
- **Stakeholder liên quan:** giáo viên hoặc người chấm Writing đang xử lý nhiều bài.

### Thời điểm / bối cảnh

Sau khi học viên hoàn thành một bài IELTS Writing Task 1 hoặc Task 2 và cần biết điểm yếu để viết lại trước buổi học hoặc kỳ thi tiếp theo.

### Current workflow

1. Học viên viết bài.
2. Nộp bài cho giáo viên/trung tâm.
3. Chờ giáo viên sắp xếp thời gian chấm.
4. Giáo viên đọc, ước lượng band và ghi nhận xét.
5. Học viên nhận feedback sau 3–5 ngày.
6. Học viên tự hiểu nhận xét và sửa bài.

### Bottleneck

- Thời gian chờ ở bước 3 kéo dài 3–5 ngày.
- Feedback ở bước 4 đôi khi chỉ có band tổng, thiếu lỗi cụ thể và hướng sửa theo từng tiêu chí.

### Impact

- Vòng lặp luyện tập bị kéo dài, đặc biệt khi ngày thi gần.
- Học viên có thể lặp lại cùng một lỗi trong các bài viết tiếp theo khi chưa nhận được feedback.
- Giáo viên phải dành nhiều thời gian cho việc phát hiện các lỗi ngôn ngữ lặp lại thay vì tập trung vào lỗi lập luận và chiến lược nâng band.

### Success metric

Mục tiêu pilot:

- cung cấp feedback sơ bộ trong vòng **10 phút** sau khi nộp;
- feedback phải tách theo bốn tiêu chí: Task Achievement/Task Response, Coherence and Cohesion, Lexical Resource, Grammatical Range and Accuracy;
- mỗi bài có ít nhất ba lỗi được trích đúng từ bài viết, kèm giải thích và gợi ý sửa;
- band do AI đưa ra chỉ là ước lượng, không phải điểm chính thức;
- giáo viên/học viên chấm mức hữu ích của feedback từ 4/5 trở lên trên tập bài pilot.

### Non-AI alternative

- Dùng checklist tự chấm theo bốn tiêu chí IELTS.
- Peer review theo rubric và mẫu feedback chuẩn.
- Giáo viên dùng comment bank cho các lỗi thường gặp.
- Chia bài thành các lượt feedback nhỏ thay vì yêu cầu chấm toàn bộ mỗi lần.

### AI hypothesis

AI có thể tạo feedback vòng đầu theo rubric, trích dẫn trực tiếp lỗi trong bài và gợi ý câu hỏi để học viên tự sửa. Giáo viên vẫn chịu trách nhiệm hiệu chỉnh band, xử lý lỗi lập luận tinh tế và quyết định feedback cuối.

### Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — chờ khoảng 3–5 ngày

[Học viên viết bài]
→ [Nộp cho giáo viên/trung tâm]
→ [Chờ được chấm 3–5 ngày]          <-- bottleneck
→ [Nhận band/feedback]
→ [Tự hiểu lỗi]
→ [Sửa và viết lại]
```

### Draft future workflow

```text
FUTURE STATE — feedback sơ bộ trong 10 phút

[Học viên nộp bài + đề bài]
→ [Rule kiểm tra đủ input]
→ [AI draft feedback theo 4 tiêu chí]
→ [AI trích lỗi và đặt câu hỏi gợi sửa]
→ [Học viên tự sửa]                 <-- learning boundary
→ [Giáo viên spot-check/calibrate]  <-- quality boundary
→ [Học viên viết lại]

Fallback:
AI hiểu sai đề hoặc feedback không thuyết phục
→ bỏ feedback đó
→ dùng rubric tự chấm hoặc chờ giáo viên review.

Boundary:
Không coi band AI là điểm chính thức;
không viết lại toàn bộ bài để học viên nộp như bài của mình;
không thay thế giáo viên ở quyết định đánh giá cuối.
```

## 5. So sánh nhanh ba Problem Card

| Tiêu chí | CV/Cover Letter | Trợ giúp chuyên môn | IELTS Writing |
|---|---|---|---|
| Actor rõ | Cao | Trung bình–cao | Cao |
| Workflow vẽ được | Cao | Cao | Cao |
| Baseline hiện có | 20 phút × 10–20 hồ sơ | 0/3 bài có phản hồi hữu ích; chưa có baseline thời gian | Chờ 3–5 ngày |
| Impact đo được | Thời gian/hồ sơ, thời gian/kỳ, tỷ lệ phản hồi | Thời gian tới next step, useful-response rate, điểm hữu ích | Thời gian chờ, độ phủ feedback, điểm hữu ích |
| Rủi ro chính | Bịa kỹ năng/thành tích, văn phong mất tự nhiên | Advice sai, phụ thuộc AI, scope tâm lý quá rộng | Band thiếu ổn định, học viên phụ thuộc hoặc dùng AI viết thay |
| Non-AI alternative | Master CV + template + checklist | Moderated community + question template + office hour | Rubric tự chấm + peer review + comment bank |
| Quick gut | Workflow | Workflow | Workflow |

## 6. Card muốn pitch nhất

**Card được chọn để pitch:** Problem Card #1 — Điều chỉnh CV và Cover Letter theo từng JD.

### Vì sao

- Có workflow lặp lại rõ nhất.
- Có baseline định lượng trực tiếp: khoảng 20 phút/hồ sơ và 10–20 hồ sơ/kỳ.
- Có thể chạy pilot nhỏ mà không cần quyền truy cập hệ thống phức tạp.
- Có human boundary rõ: ứng viên xác minh claim và tự nộp.
- Có thể so sánh nghiêm túc giữa template/rule, workflow có AI và agent.

### Pitch ngắn

Sinh viên và người mới tốt nghiệp thường phải điều chỉnh CV cùng Cover Letter cho từng JD. Mỗi hồ sơ mất khoảng 20 phút; với 10–20 công ty, tổng effort khoảng 3 giờ 20 phút đến 6 giờ 40 phút trong một kỳ tìm việc. Bước khó nhất là đối chiếu JD với kinh nghiệm thật rồi diễn đạt lại mà không bịa thông tin. Tôi muốn kiểm tra liệu một workflow trích yêu cầu, gợi ý nội dung và bắt buộc ứng viên review có thể giảm thời gian xuống không quá 10 phút/hồ sơ hay không.

### Câu hỏi muốn nhóm challenge

1. Baseline 20 phút nằm nhiều nhất ở đọc JD, sửa CV hay viết Cover Letter?
2. Có cần cá nhân hóa cả CV và Cover Letter cho mọi công ty không, hay template/rule đã giải được phần lớn trường hợp?
3. Success metric có nên ưu tiên thời gian, tỷ lệ được phản hồi hay chất lượng hồ sơ do recruiter đánh giá?
4. Làm sao phát hiện và chặn AI bịa kỹ năng hoặc thành tích?
5. Có bằng chứng nào cho thấy cá nhân hóa hồ sơ thực sự tăng cơ hội được phản hồi trong nhóm đối tượng này?

## 7. Self-check Phase 2

- [x] Có ba Problem Card.
- [x] Mỗi card có actor và stakeholder rõ.
- [x] Mỗi card có current workflow từ 3–7 bước.
- [x] Bottleneck được chỉ ra.
- [x] Evidence thật được tách khỏi target pilot.
- [x] Có success metric dự thảo.
- [x] Có non-AI alternative.
- [x] Có AI hypothesis và quick gut.
- [x] Có draft current/future workflow và fallback.
- [x] Đã chọn một card để pitch và chuẩn bị câu hỏi challenge.
