# 03 — Individual Reflection

## Thông tin cá nhân

- **Họ và tên:** Đỗ Trung Kiên
- **Mã học viên:** 2A202601287
- **Vai trò:** Thành viên; đề xuất bài "Điều chỉnh CV và Cover Letter theo JD"

## 1. Những phần em đã tham gia

| Hoạt động | Em đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Scan 10 problems và chọn ba bài để phân tích sâu | Có đủ bốn lăng kính và ba Problem Card |
| Pitch Problem Card | Pitch bài CV/JD, trợ giúp kỹ thuật và IELTS Writing | Bài CV/JD vào shortlist và được chọn |
| Challenge | Khi nghe Hưng pitch bài phòng trọ và Liêm pitch bài paper, em đặt câu hỏi về độ mới của dữ liệu và cách kiểm tra relevance | Em hiểu rõ hơn vì sao impact lớn chưa đủ nếu data và cách đo còn mơ hồ |
| Cluster | Tham gia gom 14 candidates thành bốn cụm | Nhóm thấy pattern chung trước khi shortlist |
| Chọn candidate | Trình bày baseline 20 phút/hồ sơ, 10-20 hồ sơ/kỳ | Bài CV/JD đạt 34/35 |
| Validation / research | Phân biệt self-report với evidence đại diện; rà Europass, LinkedIn, Teal, Kickresume | Nhóm ghi rõ chưa có interview, survey hay pilot |
| Workflow | Góp phần vẽ current/future workflow | Có evidence mapping, human review và fallback |
| Problem Statement | Sửa actor và metric | Actor là người muốn tìm việc; metric tập trung vào thời gian và tính trung thực |
| Rule / Workflow / Agent | Lập luận chọn Workflow thay vì Agent | Không tự tìm việc hoặc auto-submit |
| Decision | Góp phần chốt pilot và rollback | `Go` cho pilot nhỏ, `Not Yet` cho production |

## 2. Bảng sử dụng AI

| Phase | Em dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Em đã sửa gì? |
|---|---|---|---|---|
| Scan | Chuẩn hóa actor-pain-evidence | Phân loại theo bốn lăng kính | Có thể tự làm đầy problem bằng số liệu chưa có | Chỉ giữ problem tự quan sát, chỗ chưa đo được ghi rõ |
| Problem Card | Tạo cấu trúc card | Làm rõ workflow và bottleneck | Scope/actor ban đầu quá hẹp hoặc quá chung | Mở rộng actor tìm việc; thu hẹp bài trợ giúp về cộng đồng công nghệ |
| Workflow | Chuyển mô tả thành before/after flow | Nhìn rõ Rule, AI và human boundary | Tập trung vào tạo text nhưng thiếu nguồn cho claim | Thêm evidence map, verify và fallback |
| Research | Tìm tool/pattern tương tự | Giúp thấy giải pháp đã có | Có claim marketing chưa kiểm chứng | Chỉ giữ nguồn có link; không dùng claim đó làm evidence |
| Problem Statement | Phản biện actor, metric, boundary | Chỉ ra "tăng accept" khó đo | Dễ coi ATS/target pilot là kết quả thật | Đổi sang timer, relevance và 0 unsupported claim |
| Rule / Workflow / Agent | So sánh bốn mức giải pháp | Làm rõ trade-off | Có xu hướng đề xuất Agent sớm | Chọn Workflow; giữ template/Rule làm baseline |
| Decision | Gợi ý pilot và rollback | Làm decision cụ thể | Có thể đưa threshold khi chưa chạy thử | Ghi rõ đây mới là thiết kế, chưa có kết quả |

## 3. Reflection cá nhân

### Bài học từ challenge nhóm

Khi nghe Hưng trình bày bài tìm phòng trọ, ban đầu em thấy bài này cấp thiết hơn bài CV vì liên quan cả tiền bạc và lừa đảo. Tuy nhiên, em tự hỏi nhóm sẽ lấy dữ liệu phòng còn trống ở đâu và kiểm tra tin giả thế nào. Với bài sàng lọc paper của Liêm, baseline 90 phút/10 bài khá thuyết phục, nhưng em chưa thấy cách chấm một paper là "đủ liên quan" nếu thiếu context đề tài. Hai bài này giúp em nhận ra impact lớn chưa đủ; data access và cách đo output cũng phải rõ.

Các bài của Yến về report/Discord, của Long về troubleshooting log và của– Quân về điểm danh cũng khiến em chú ý rằng không phải pain nào cũng cần AI. Có bài cần search hoặc lưu log tốt hơn; có bài chỉ cần Rule. Khi quay lại bài của mình, em cũng chấp nhận challenge rằng "tăng accept/ATS" chưa phải metric phù hợp. Nhóm chuyển sang đo thời gian, relevance/readability và 0 claim không có evidence; actor cũng được mở rộng từ sinh viên sang mọi người muốn tìm việc.

### Đóng góp và cách nhìn về AI

Đóng góp chính của em là đưa ra candidate CV/JD, pitch baseline và tham gia hoàn thiện workflow, metric, boundary cùng decision. Ranh giới quan trọng nhất là AI không được bịa kỹ năng hay thành tích; người dùng phải kiểm từng claim và tự nộp hồ sơ.

Nhóm từng có xu hướng solution-first, nhưng khi vẽ workflow thì thấy master CV, template và Rule đã giải được một phần. AI chỉ cần hỗ trợ semantic mapping và draft; chưa cần Agent vì luồng xử lý cố định và auto-submit khó rollback.

AI giúp em cấu trúc và phản biện nhanh, nhưng dễ mở rộng scope hoặc biến target thành evidence. Em đã phải sửa actor, thu hẹp bài trợ giúp về cộng đồng công nghệ, bỏ metric ATS chưa kiểm chứng và ghi rõ những phần chưa validation. Vì vậy, AI chỉ hỗ trợ; người làm bài vẫn chịu trách nhiệm về claim và quyết định cuối.

## 4. Nếu làm lại

Em sẽ:

1. Phỏng vấn 3-5 người tìm việc ở các mức kinh nghiệm khác nhau.
2. Bấm giờ từng bước trên hồ sơ thật.
3. So sánh template thủ công, Rule và Workflow có AI.
4. Nhờ reviewer chấm relevance, readability và tính trung thực trước khi chốt metric.

Em cũng sẽ challenge nhóm sớm hơn bằng câu hỏi: "Evidence nào chứng minh pain, và evidence nào chỉ chứng minh một tool đang tồn tại?".
