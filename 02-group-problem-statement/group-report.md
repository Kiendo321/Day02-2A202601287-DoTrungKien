# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   |           |             |                    |
| 2   |           |             |                    |
| 3   |           |             |                    |
| 4   |           |             |                    |
| 5   |           |             |                    |

## Candidate problem nhóm đã chọn

### Problem Card tóm tắt

**Problem một câu:** Sinh viên năm cuối hoặc người mới tốt nghiệp đang tìm việc mất khoảng 20 phút để điều chỉnh CV và Cover Letter theo từng JD. Với 10-20 công ty trong một kỳ tìm việc, workflow lặp lại này tiêu tốn khoảng 200-400 phút.

**Actor chính:** Sinh viên năm cuối hoặc người mới tốt nghiệp đang chủ động ứng tuyển.

**Stakeholder:** Nhà tuyển dụng tiếp nhận và sàng lọc hồ sơ.

**Current workflow:** Đọc JD → so sánh với CV gốc → chọn/đổi thứ tự nội dung → viết lại bullet points → chỉnh Cover Letter → kiểm tra và nộp.

**Bottleneck:** Cụm bước đối chiếu JD với kinh nghiệm thật và diễn đạt lại nội dung phù hợp mà không bịa kỹ năng, kinh nghiệm hoặc thành tích.

**Giả thuyết ban đầu:** Một workflow kết hợp rule và AI có thể tạo bản nháp phù hợp hơn với JD, trong khi ứng viên vẫn kiểm chứng từng claim và tự quyết định bản cuối.

---

# Phase 4 — Quick Validation và Research giải pháp

## 4.1. Quick validation

### Evidence hiện có

Nhóm hiện có một quan sát trực tiếp từ problem owner:

- mỗi hồ sơ mất khoảng 20 phút để điều chỉnh CV và Cover Letter;
- một kỳ tìm việc thường nộp 10-20 hồ sơ;
- tổng effort suy ra là `20 phút × 10-20 hồ sơ = 200-400 phút`, tương đương khoảng 3 giờ 20 phút đến 6 giờ 40 phút.

Phép tính 200-400 phút là impact suy ra từ cùng một baseline, **không phải một mẫu validation độc lập**.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác / giới hạn | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quan sát trực tiếp của problem owner | 1 người; 10-20 hồ sơ/kỳ | Workflow xảy ra lặp lại; baseline khoảng 20 phút/hồ sơ; tổng effort đủ lớn để đáng kiểm tra | Chưa bấm giờ từng bước; chỉ có một người; chưa biết 20 phút có giống với người khác không | Giữ time-saving là giả thuyết cần pilot, không khẳng định đây là baseline của mọi sinh viên |
| Quick interview | 0 | Chưa thực hiện | Chưa biết người khác có cùng pain, workaround hay mức thời gian hay không | Bắt buộc phỏng vấn thêm trước khi mở rộng sản phẩm |
| Survey / poll | 0 | Chưa thực hiện | Chưa có phân bố tần suất, thời gian hoặc mức độ đáng giải quyết | Không dùng tỷ lệ phần trăm đại diện cho cộng đồng |
| Research công cụ hiện có | 4 pattern/tool | Nhiều sản phẩm đã hỗ trợ CV template, JD matching hoặc AI drafting, cho thấy workflow này đã được thị trường sản phẩm chú ý | Sự tồn tại của tool không chứng minh pain của nhóm người dùng mục tiêu; cũng có thể là tín hiệu rằng giải pháp hiện có đã đủ | Chuyển câu hỏi từ “có nên build tool mới?” sang “workflow tối thiểu nào tạo thêm giá trị và kiểm soát claim tốt hơn?” |

### Tín hiệu xác nhận

- Pain có thật ở mức **một problem owner**.
- Workflow lặp lại đủ nhiều để time-saving có thể đo được trong pilot.
- Bước khó không chỉ là format mà là nối yêu cầu trong JD với evidence có thật trong master CV.

### Tín hiệu chưa xác nhận

- Chưa chứng minh đa số sinh viên mất khoảng 20 phút/hồ sơ.
- Chưa tách được thời gian cho đọc JD, chỉnh CV, viết Cover Letter và review.
- Chưa có dữ liệu cho thấy cá nhân hóa bằng AI làm tăng tỷ lệ được phỏng vấn hoặc “được accept”.
- Chưa biết người dùng hiện đã dùng template hoặc công cụ tương tự hay chưa.

### Problem được sửa sau validation

Problem ban đầu có mục tiêu “tăng cơ hội được accept”. Nhóm thu hẹp lại:

```text
Sinh viên năm cuối hoặc người mới tốt nghiệp đang chủ động ứng tuyển
phải lặp lại việc đối chiếu từng JD với kinh nghiệm thật rồi chỉnh CV
và Cover Letter. Với quan sát ban đầu khoảng 20 phút/hồ sơ và
10-20 hồ sơ/kỳ, workflow này tiêu tốn khoảng 200-400 phút.

Nhóm cần kiểm tra liệu có thể giảm thời gian tạo một bản nháp phù hợp
với JD mà không tạo claim không có bằng chứng hay không.
```

Tỷ lệ nhận phản hồi/phỏng vấn được giữ làm **secondary metric để quan sát dài hạn**, không phải success metric chính của pilot. Nhóm chưa có cơ sở để kết luận quan hệ nhân quả giữa AI tailoring và tỷ lệ được tuyển.

### Kế hoạch validation tiếp theo

Phỏng vấn nhanh 3-5 sinh viên/người mới tốt nghiệp đã nộp ít nhất năm hồ sơ trong ba tháng gần nhất:

1. Lần gần nhất bạn điều chỉnh CV cho một JD là khi nào?
2. Bạn đã thay những phần nào và mất bao lâu cho từng phần?
3. Bạn có viết Cover Letter cho mọi công ty không?
4. Bạn đang dùng master CV, template hoặc AI tool nào?
5. Lỗi nào khiến bạn không tin một bản nháp do AI tạo?

Mỗi người sẽ bấm giờ một lần làm thủ công để có baseline thay vì chỉ nhớ lại.

## 4.2. Research giải pháp đã có

Nhóm ưu tiên trang chính thức của sản phẩm/tổ chức và không sử dụng claim tiết kiệm thời gian nếu chưa có phương pháp kiểm chứng độc lập.

| Nguồn / tool / pattern | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Europass CV + Cover Letter | [Europass CV](https://europass.europa.eu/en/create-europass-cv) và [Cover Letter](https://europass.europa.eu/en/create-europass-cover-letter) | Lưu profile chứa kỹ năng/kinh nghiệm; chọn nội dung để tạo nhiều CV; cung cấp cấu trúc và template Cover Letter | Non-AI baseline rõ; tái sử dụng master profile; người dùng chủ động chọn thông tin | Không tự giải toàn bộ việc semantic matching giữa JD và evidence; format/chuẩn Europass không phù hợp mọi thị trường | Master profile + template có thể giải phần quản lý nội dung mà không cần AI |
| LinkedIn Job Match / Skills Match | [Job Match](https://www.linkedin.com/help/linkedin/answer/a8078207) và [Skills Match](https://www.linkedin.com/help/linkedin/answer/a793433/) | So sánh required/preferred qualifications trong JD với profile/resume; tóm tắt độ phù hợp và kỹ năng khớp | Cho thấy pattern “extract JD → compare profile → explain match” đã tồn tại | Một số insight phụ thuộc rollout/Premium và dữ liệu trong LinkedIn; không phải lúc nào cũng tạo được CV/CL chỉnh sửa ngoài nền tảng | Evidence mapping và giải thích vì sao match quan trọng hơn một score không minh bạch |
| Teal Resume Builder / Job Matching | [Teal Resume Builder](https://www.tealhq.com/tools/resume-builder) | Gắn JD vào resume, tìm skills/keywords, đề xuất điều chỉnh, tạo nhiều version và Cover Letter | Bao phủ gần như toàn bộ workflow nhóm đang nghĩ tới | Match score có thể khiến người dùng keyword-stuffing; claim marketing của vendor không được coi là bằng chứng hiệu quả; người dùng vẫn phải kiểm tra nội dung | Không nên clone feature; pilot phải tập trung vào provenance của từng claim và effort review |
| Kickresume AI Cover Letter Writer | [Kickresume AI Cover Letter](https://www.kickresume.com/en/ai-cover-letter-writer/) | Dùng job ad và resume để tạo bản nháp Cover Letter theo vị trí | Tạo draft nhanh; chính trang sản phẩm cũng khuyến nghị người dùng chỉnh lại vì AI không biết đầy đủ câu chuyện cá nhân | Có thể tạo văn phong generic hoặc diễn giải quá mức kinh nghiệm; “ready-to-send” không loại bỏ nhu cầu review | AI draft chỉ nên là điểm bắt đầu; human edit và claim verification phải là boundary bắt buộc |

### Research takeaway

```text
Không nên bắt đầu bằng một Agent tự tìm việc, sửa hồ sơ và nộp đơn.

Các giải pháp hiện có cho thấy ba pattern hữu ích:
1. Master profile/template để tái sử dụng dữ liệu thật.
2. Rule để trích required/preferred criteria từ JD.
3. AI để map evidence và draft, sau đó ứng viên review.

Khoảng trống đáng kiểm tra trong pilot không phải “AI có viết được không”,
mà là “AI có giảm effort trong khi mọi claim vẫn truy ngược được về
evidence do ứng viên cung cấp hay không”.
```

---

# Phase 5 — Workflow và Problem Statement

## 5.1. Current workflow bản nhóm

```text
CURRENT STATE — 6 bước, khoảng 20 phút/hồ sơ

[1 Ứng viên đọc và đánh dấu JD]
→ [2 So sánh JD với master CV]
→ [3 Chọn/bỏ/đổi thứ tự nội dung]      <-- bottleneck
→ [4 Viết lại bullet points]           <-- bottleneck
→ [5 Chỉnh Cover Letter]               <-- bottleneck
→ [6 Kiểm tra, xuất file và tự nộp]

Handoff cuối:
Ứng viên → nhà tuyển dụng.
```

Nhóm mới có baseline tổng khoảng 20 phút; chưa có log thời gian đáng tin cậy cho từng bước nên không chia nhỏ bằng số ước lượng.

| Bước | Actor | Input | Output | Thời gian / tần suất | Handoff / ghi chú |
|---:|---|---|---|---|---|
| 1 | Ứng viên | JD của doanh nghiệp | JD đã đánh dấu responsibility, skill và keyword | Chưa tách thời gian; 10-20 lần/kỳ tìm việc | Sang bước 2, vẫn do ứng viên xử lý |
| 2 | Ứng viên | JD đã đánh dấu + master CV | Danh sách match, gap và evidence có thể dùng | Chưa tách thời gian | Sang bước 3 |
| 3 | Ứng viên | Danh sách match/gap + CV gốc | Bộ nội dung được chọn và sắp xếp lại | Chưa tách thời gian | Một phần bottleneck |
| 4 | Ứng viên | Bullet points và evidence gốc | Bullet points đã điều chỉnh | Chưa tách thời gian | Không được thêm claim không có thật |
| 5 | Ứng viên | JD, thông tin doanh nghiệp, CV đã chỉnh | Cover Letter riêng cho vị trí | Chưa tách thời gian | Một phần bottleneck |
| 6 | Ứng viên | CV + Cover Letter bản cuối | File được kiểm tra và hồ sơ được nộp | Chưa tách thời gian | Handoff sang nhà tuyển dụng |

**Tổng thời gian quan sát ban đầu:** khoảng 20 phút/hồ sơ.

### Bottleneck chính

```text
Cụm bước 2-5: biến JD thành lựa chọn nội dung và cách diễn đạt phù hợp,
trong khi phải bảo đảm mọi kỹ năng, kinh nghiệm và thành tích đều có thật.
```

## 5.2. Future workflow bản nhóm

```text
FUTURE STATE — 6 bước, mục tiêu không quá 10 phút/hồ sơ

[1 Ứng viên chọn JD + master CV: ~1']
→ [2 Rule kiểm tra input và trích tiêu chí: <1']
→ [3 AI map mỗi tiêu chí với evidence: ~1']
→ [4 AI draft thay đổi CV + Cover Letter: ~2']
→ [5 Ứng viên kiểm chứng và sửa: ≤5']     <-- human boundary
→ [6 Ứng viên tự xuất file và nộp: ~1']   <-- human boundary

Fallback:
- Claim không có evidence → xóa claim, không cho qua bước review.
- AI hiểu sai JD hoặc draft kém → bỏ draft và dùng master CV + template.
- JD thiếu rõ ràng → ứng viên tự quyết hoặc loại khỏi pilot.

Bottleneck mới:
Ứng viên kiểm chứng evidence và chỉnh giọng văn.
Đây là bottleneck chấp nhận được vì nó là điểm kiểm soát tính trung thực.
```

Các con số theo bước ở future state là **time budget của pilot**, không phải kết quả đã đo.

| Bước | Loại xử lý | Input | Output | Boundary |
|---:|---|---|---|---|
| 1 | Human | JD + master CV do ứng viên chọn | Bộ input được consent | Không tự lấy dữ liệu từ tài khoản khác |
| 2 | Rule | JD và file hợp lệ | Must-have, preferred, responsibility, tone | Nếu parse lỗi, yêu cầu người dùng sửa input |
| 3 | AI trong workflow | Tiêu chí + master CV | Evidence map: tiêu chí ↔ câu/bullet nguồn | Không được tự tạo evidence |
| 4 | AI trong workflow | Evidence map | Bản nháp thay đổi CV và Cover Letter | Mỗi claim phải có source hoặc gắn “không đủ evidence” |
| 5 | Human | Draft + evidence map | Nội dung được approve/edit/reject | Ứng viên chịu trách nhiệm nội dung cuối |
| 6 | Human | CV + Cover Letter đã approve | Hồ sơ hoàn chỉnh | Không tự động nộp |

### Before/after impact

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 6 | Không giảm số bước; giảm effort ở bước đọc-map-draft |
| Tổng thời gian | Khoảng 20 phút/hồ sơ | Không quá 10 phút/hồ sơ | Target chính; phải đo bằng timer |
| Bước hoàn toàn thủ công | 6/6 | 3/6 | Human vẫn chọn input, review và nộp |
| Bottleneck chính | Đối chiếu + viết lại CV/CL | Verify evidence + edit | Human boundary |
| Claim không có evidence | Chưa đo | 0 claim ở bản cuối | Guardrail bắt buộc |
| Tỷ lệ nhận phản hồi | Chưa đo | Chỉ theo dõi | Không dùng làm tiêu chí pass/fail của pilot ngắn |
| Risk mới | Lỗi thủ công, bỏ sót keyword | Hallucination, keyword stuffing, lộ dữ liệu cá nhân, văn phong đồng dạng | Cần provenance, consent và review |

## 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối hoặc người mới tốt nghiệp đang chủ động ứng tuyển 10-20 công ty trong một kỳ tìm việc. |
| **Workflow** | Đọc JD → so sánh với master CV → chọn/đổi thứ tự nội dung → viết lại bullet points → chỉnh Cover Letter → kiểm tra và nộp. |
| **Bottleneck** | Cụm bước đối chiếu JD với kinh nghiệm thật và viết lại CV/Cover Letter; tổng workflow hiện mất khoảng 20 phút/hồ sơ theo quan sát của một problem owner. |
| **Impact** | Khoảng 200-400 phút mỗi kỳ tìm việc, tương đương 3 giờ 20 phút đến 6 giờ 40 phút; ứng viên có thể dùng hồ sơ chung hoặc bỏ qua cơ hội vì effort lặp lại. |
| **Success Metric** | Giảm thời gian xuống không quá 10 phút/hồ sơ; 0 claim không có evidence trong bản cuối; ứng viên approve trước khi nộp. |
| **Boundary** | Chỉ dùng JD và dữ liệu do ứng viên cung cấp; không bịa kỹ năng/kinh nghiệm/thành tích; không tự chọn việc; không tự nộp hồ sơ; không thay ứng viên quyết định nội dung cuối. |

### Phản biện Problem Statement v0

1. Baseline 20 phút mới đến từ một người và chưa được bấm giờ theo bước.
2. “Phù hợp với JD” có thể bị hiểu thành nhồi keyword; cần thêm thước đo relevance và readability.
3. Chỉ số “được accept” quá xa intervention và chịu nhiều yếu tố khác, nên không dùng làm metric chính.
4. “0 claim không có evidence” cần evidence map để reviewer kiểm tra được.
5. Boundary cần bổ sung quyền riêng tư: không suy diễn dữ liệu nhạy cảm và không dùng dữ liệu ngoài phạm vi người dùng đồng ý.

---

# Phase 6 — Rule / Workflow / Agent và Decision

## 6.0. Ma trận độ phù hợp với AI

**Ô của bài toán:** Độ phức tạp cao, độ mơ hồ cao.

**Vì sao:**

- Workflow có sáu bước, hai artifact đầu ra và kết quả bước sau phụ thuộc kết quả bước trước.
- Có nhiều cách viết CV/Cover Letter vẫn có thể chấp nhận được.
- Việc chọn evidence và diễn đạt cần hiểu ngữ nghĩa, không chỉ exact keyword.
- Tuy nhiên, đường đi giữa các bước là cố định; AI không cần tự quyết định dùng công cụ nào hoặc tự chọn bước tiếp theo.

| Câu hỏi | Kết quả cho bài toán |
|---|---|
| Output có thể khác nhau mỗi lần mà vẫn chấp nhận được không? | Có → độ mơ hồ cao |
| Cần phối hợp từ ba bước trở lên không? | Có → độ phức tạp cao |
| AI có cần tự quyết định bước tiếp theo không? | Không → workflow cố định có thể đủ |

Kết luận từ ma trận: độ phức tạp và mơ hồ cao làm AI hữu ích ở khâu semantic mapping/drafting, nhưng **không tự động suy ra rằng cần Agent**.

## 6.1. So sánh No AI / Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro / giới hạn | Chọn? |
|---|---|---|---|---|
| **No AI / process fix** | Master CV, 2-3 template theo job family, Cover Letter skeleton và checklist review | Đủ khi các JD tương tự nhau và ứng viên có ít hồ sơ | Vẫn phải đọc, map và viết thủ công; có thể bỏ sót semantic match | Dùng làm baseline và fallback |
| **Rule** | Trích keyword, chia must-have/preferred, chọn section theo bảng mapping cố định | Đủ khi JD có cấu trúc ổn định và chỉ cần thay section/keyword rõ ràng | Không hiểu tốt synonym, context hoặc mức độ liên quan; dễ khuyến khích keyword stuffing | Dùng cho input validation và cấu trúc |
| **Workflow** | Rule trích tiêu chí → AI map evidence → AI draft → ứng viên verify/edit → ứng viên tự nộp | Phù hợp khi đường đi cố định nhưng mapping/drafting có độ mơ hồ cao | Hallucination, overclaim, privacy, văn phong generic; cần human review | **Chọn** |
| **Agent** | Tự tìm JD, chọn việc, đọc dữ liệu cá nhân, chỉnh hồ sơ, điền form và nộp | Chỉ đáng cân nhắc nếu cần tự lập kế hoạch động qua nhiều nền tảng và đã có permission/boundary rất chặt | Quyền truy cập rộng; có thể nộp sai việc hoặc sai claim; khó rollback sau khi gửi; rủi ro riêng tư cao | Không chọn |

### Mức chọn

```text
Workflow.
```

### Vì sao chọn

- Các bước đã biết trước và có thể kiểm soát.
- Rule phù hợp với kiểm tra input và phân loại field rõ ràng.
- AI có lợi thế ở semantic matching và drafting, là hai bước có nhiều output hợp lệ.
- Human review nằm trước hành động không thể thu hồi là nộp hồ sơ.
- Workflow có thể log evidence map, thời gian và edit để đánh giá pilot.

### Vì sao không chỉ chọn mức đơn giản hơn

No-AI/template và Rule có thể giải một phần đáng kể, nên được dùng làm baseline. Tuy nhiên, chúng chưa chắc giảm được effort ở phần khó nhất: nối một yêu cầu được diễn đạt tự do trong JD với bằng chứng liên quan trong kinh nghiệm thật và viết lại tự nhiên.

Nhóm chưa biết Rule giải được 70-80% case hay không. Pilot phải đo điều này; nếu Rule đạt mục tiêu với ít rủi ro hơn, nhóm sẽ hạ mức từ Workflow về Rule.

### Vì sao không chọn Agent

- Không cần lập kế hoạch động.
- Không cần tự tìm hoặc chọn công việc.
- Không được phép tự nộp hồ sơ.
- Lợi ích tăng thêm chưa đủ bù permission, privacy và rollback risk.

## 6.2. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên năm cuối hoặc người mới tốt nghiệp đang chủ động ứng tuyển nhiều vị trí trong cùng một kỳ tìm việc. |
| **Workflow** | Chọn JD → đọc và trích tiêu chí → đối chiếu với master CV → chọn evidence → chỉnh CV → viết Cover Letter → review và tự nộp. |
| **Bottleneck** | Đối chiếu các yêu cầu được viết tự do trong JD với kinh nghiệm thật rồi diễn đạt lại CV/Cover Letter. Quan sát ban đầu cho thấy toàn workflow mất khoảng 20 phút/hồ sơ, nhưng baseline mới có một người. |
| **Impact** | Với 10-20 hồ sơ/kỳ, effort ước tính 200-400 phút; workflow lặp lại có thể khiến ứng viên dùng một hồ sơ chung hoặc giảm số cơ hội họ sẵn sàng theo đuổi. |
| **Success Metric** | Trong pilot, median time không quá 10 phút/hồ sơ và giảm ít nhất 40% so với baseline thủ công của chính participant; 0 claim không có evidence ở bản cuối; relevance/readability đạt tối thiểu 4/5 theo rubric review. Tỷ lệ nhận phản hồi chỉ là metric theo dõi dài hạn. |
| **Boundary** | Chỉ xử lý JD và master CV do ứng viên chủ động cung cấp; không suy diễn thuộc tính nhạy cảm; không bịa hoặc nâng khống claim; không tự chọn việc; không tự gửi/nộp hồ sơ; ứng viên approve mọi thay đổi. |
| **AI intervention point** | Sau khi Rule trích tiêu chí từ JD và trước bước ứng viên chỉnh CV/Cover Letter: AI map tiêu chí với evidence có sẵn và tạo draft kèm provenance. |
| **Mức chọn** | Workflow: Rule validate/extract → AI evidence mapping/draft → human verify/edit → human submit. |
| **Rủi ro & người thật kiểm tra** | Rủi ro: hallucination, overclaim, keyword stuffing, lộ dữ liệu cá nhân, giọng văn generic. Ứng viên kiểm từng claim qua evidence map, sửa giọng văn và quyết định bản cuối; reviewer dùng rubric relevance/readability trong pilot. |

## 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor chính, stakeholder, sáu bước và handoff đã xác định |
| Baseline và success metric đã đo được chưa? | Not Yet | Có baseline recall khoảng 20 phút từ một người; chưa có timer log hoặc mẫu nhiều người |
| Có data/input đủ dùng chưa? | Yes cho pilot | Chỉ cần master CV và JD do participant tự chọn; chưa cần tích hợp nền tảng |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes trong pilot kín | Draft chưa được gửi; ứng viên review và có thể rollback. Không chấp nhận auto-submit |
| Có người review/owner vận hành không? | Yes | Ứng viên là owner nội dung; nhóm theo dõi metric; reviewer chấm rubric |
| Có cách non-AI đơn giản hơn không? | Yes | Master CV + template + checklist; được dùng làm baseline/fallback |

### Decision

```text
Go với pilot giới hạn.
Not Yet cho production integration hoặc auto-submit.
```

### Lý do

- Pain và workflow đủ cụ thể để chạy một thí nghiệm nhỏ.
- Input có thể được participant cung cấp trực tiếp, không cần permission rộng.
- Output là draft có thể thu hồi; human approval xảy ra trước khi nộp.
- Pilot đồng thời kiểm tra baseline, giá trị tăng thêm so với template/rule và rủi ro unsupported claim.
- Chưa có validation đủ mạnh để build sản phẩm hoặc tuyên bố tăng tỷ lệ được tuyển.

### Pilot nhỏ nhất

**Mẫu:** 3 sinh viên/người mới tốt nghiệp, mỗi người chọn 4 JD trong một job family; tổng 12 bộ hồ sơ thử nghiệm.

**Thiết kế:**

1. Mỗi participant chuẩn bị master CV đã xác nhận là đúng.
2. Với hai JD, participant dùng master CV + template thủ công.
3. Với hai JD tương đương, participant dùng workflow hỗ trợ; thứ tự manual/assisted được đảo giữa người tham gia để giảm learning effect.
4. Không cần nộp hồ sơ thật trong pilot.
5. Timer ghi thời gian từng bước.
6. Evidence checker đánh dấu mỗi claim trong output là supported/unsupported.
7. Participant và một reviewer dùng rubric 1-5 cho relevance, readability và giữ đúng giọng cá nhân.

**Điều kiện pilot pass:**

- median time không quá 10 phút và giảm ít nhất 40% so với manual baseline;
- 0 unsupported claim trong bản được participant approve;
- relevance và readability trung bình tối thiểu 4/5;
- 100% participant hiểu rằng họ, không phải AI, chịu trách nhiệm bản cuối.

### Exit / rollback

- Nếu xuất hiện unsupported claim ở bản cuối sau bước review, dừng generation tự do và hạ xuống Rule + template + evidence suggestions.
- Nếu time reduction dưới 30% hoặc người dùng phải viết lại hơn 50% draft, không mở rộng Workflow; thử cải thiện template/Rule trước.
- Nếu relevance/readability dưới 4/5, không dùng output để nộp thật.
- Nếu participant không đồng ý cung cấp CV hoặc lo ngại privacy, không lưu dữ liệu và dùng quy trình thủ công.
- Trong mọi trường hợp, rollback là master CV + template; không có hồ sơ nào được tự động gửi.

### Việc cần validate sau pilot

- Phỏng vấn thêm ít nhất 5 người để kiểm tra pain có lặp lại ngoài nhóm ban đầu không.
- Tách baseline theo job family, mức kinh nghiệm và việc có/không cần Cover Letter.
- So sánh Workflow với Rule/template, không chỉ so với “làm hoàn toàn thủ công”.
- Chỉ nghiên cứu tỷ lệ nhận phản hồi sau khi có đủ hồ sơ và kiểm soát các yếu tố gây nhiễu; không dùng metric này để quảng bá sớm.
