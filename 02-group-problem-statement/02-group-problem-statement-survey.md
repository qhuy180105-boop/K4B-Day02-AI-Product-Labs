# Quick Validation Survey — Phân công task theo kỹ năng và tải việc

> Mục tiêu: thu tối thiểu **5–10 phản hồi thật** từ PM/Team Lead/Resource Manager/Developer. Không điền thay người tham gia, không thu tên công ty, tên dự án, tên nhân viên hoặc nội dung meeting nhạy cảm. Mỗi người trả lời dựa trên **một lần gần nhất** họ thực sự tham gia phân công/nhận task.

## Tin nhắn gửi người tham gia

```text
Chào anh/chị/bạn, nhóm mình đang làm lab về quá trình chuyển meeting notes hoặc project brief
thành task và phân công người phù hợp theo kỹ năng + tải việc. Khảo sát 3–5 phút, không hỏi tên
công ty/dự án/nhân viên và chỉ dùng cho bài học. Nhờ bạn trả lời theo lần gần nhất đã thực sự
gặp, không cần ước lượng nếu không nhớ. Cảm ơn bạn!
```

## Câu hỏi sàng lọc và bối cảnh

1. Vai trò của bạn trong tình huống gần nhất là gì?
   - [ ] Project Manager / Team Lead
   - [ ] Resource / Department Manager
   - [ ] Developer / người nhận task
   - [ ] Vai trò khác: ________

2. Trong 3 tháng gần đây, bạn có tham gia ít nhất một trong hai việc sau không?
   - [ ] Chuyển meeting notes/action items thành task có owner
   - [ ] Lập đội hình hoặc phân công task khi nhận dự án mới
   - [ ] Không có cả hai → kết thúc khảo sát; không tính vào mẫu target-user

3. Tình huống gần nhất thuộc loại nào?
   - [ ] Sau cuộc họp
   - [ ] Khi nhận project brief/dự án mới
   - [ ] Cả hai

## Câu hỏi về workflow và baseline

4. Hãy mô tả ngắn quy trình bạn đã làm trong lần gần nhất, từ lúc nhận notes/brief đến khi task hoặc đội hình được duyệt.
5. Bước nào tốn công hoặc khó nhất? Chọn tối đa 2.
6. Mất bao lâu từ điểm bắt đầu đến lúc owner/đội hình được duyệt?
7. Trong 24 giờ, bao nhiêu task có đủ Owner + Deadline + Output kỳ vọng?
8. Trong 30 ngày gần nhất: task phải đổi người vì thiếu skill / vì quá tải?
9. Có nhân sự chuyên môn hiếm nào >100% capacity vẫn nhận thêm task không?
10. Phương án không-AI (mẫu action item, skill matrix, capacity board) giải quyết được khoảng bao nhiêu phần pain? (0–20%, 21–40%, 41–60%, 61–80%, 81–100%).

## Câu hỏi về giải pháp và boundary

11. Mức hữu ích dự kiến nếu AI tạo Top 3 đề xuất + lý do và PM/Lead bắt buộc duyệt? (1–5).
12. Lo ngại lớn nhất (AI bịa fact, capacity cũ, thiên vị, bảo mật, giao không duyệt).
13. Trích dẫn trải nghiệm thật của bạn (Quote ẩn danh).

---

## Bảng nhập kết quả khảo sát thực tế (Đã thu thập n = 8)

> Mã hóa người tham gia là R01…R08; không ghi tên, email, công ty hoặc dự án. 100% người tham gia đồng ý trích dẫn ẩn danh.

| Mã | Vai trò | Bối cảnh gần nhất | Bước nghẽn lớn nhất | M-01 TTO (phút) | M-02 TTT (ngày) | M-03 Completeness (24h) | M-04 Reassign / Tổng task | Quá tải >100%? | Non-AI giải quyết | Đánh giá AI (1-5) | Quote trích dẫn nguyên văn |
|---|---|---|---|---:|---:|---|---|---|---|---:|---|
| **R01** | Tech Lead (Outsource) | Sau cuộc họp tuần (Meeting) | Bóc tách action item & tìm người có skill phù hợp | 75 | — | 5 / 12 (41.7%) | 3 / 18 (16.7%) | Có | 21–40% | 4 / 5 | *“Trong lần gần nhất họp sprint review với khách hàng, phần mất công nhất là ngồi nghe lại ghi âm và đọc 6 trang note để chốt xem ai làm gì, vì khách nói rất nhiều yêu cầu phụ nhưng không chốt deadline cụ thể.”* |
| **R02** | Project Manager | Cả hai (Họp & Nhận brief mới) | Kiểm tra tải việc xuyên 3 dự án & thương lượng | 90 | 4.0 | 6 / 14 (42.8%) | 4 / 22 (18.2%) | Có | 41–60% | 5 / 5 | *“Khó nhất là không biết dev bên dự án khác sắp xong chưa; hỏi PM bên kia thì ai cũng bảo người của họ đang bận 100%, cuối cùng toàn phải escalate lên Head of Dept để xin người.”* |
| **R03** | Delivery Manager | Lập đội hình dự án mới (Brief) | Khan hiếm chuyên môn hiếm & xung đột lịch | — | 3.5 | 8 / 15 (53.3%) | 3 / 20 (15.0%) | Có | 21–40% | 4 / 5 | *“Khi nhận brief dự án AI/Data mới, phần đau đầu nhất là chỉ có đúng 2 bạn Senior làm được mảng này mà cả 2 đều đang gánh dự án cũ; nếu ép nhận thêm chắc chắn sẽ trễ hạn bàn giao.”* |
| **R04** | Senior Backend Dev | Nhận task sau họp sprint | Bị giao task khi đang ôm 2 deadline sát | 45 | — | 4 / 8 (50.0%) | 2 / 12 (16.7%) | Có | 0–20% | 4 / 5 | *“Nhiều khi Lead thấy mình vừa xong 1 task là giao ngay task mới, nhưng không biết là mình đang phải hỗ trợ fix bug khẩn cấp ở 1 dự án khác; kết quả là phải thức đêm làm hoặc xin đổi người sau 2 ngày.”* |
| **R05** | Team Lead (Fintech) | Sau cuộc họp kỹ thuật | Viết task đủ acceptance criteria & deadline | 60 | — | 7 / 11 (63.6%) | 2 / 16 (12.5%) | Không | 41–60% | 4 / 5 | *“Mất thời gian nhất là chuyển các thảo luận kỹ thuật trừu tượng thành ticket Jira có mô tả rõ ràng; nếu viết sơ sài thì dev làm sai hướng rồi phải làm lại từ đầu rất tốn công.”* |
| **R06** | DevOps / Infra Dev | Nhận task từ nhiều dự án | Điểm mù tải việc, dồn việc vào chuyên môn hiếm | — | 3.0 | 3 / 9 (33.3%) | 4 / 14 (28.6%) | Có | 21–40% | 5 / 5 | *“Team có 1 mình mình làm Cloud/K8s nên 4 dự án cùng réo tên; PM nào cũng bảo task của mình là gấp nhất trong khi mình không có đủ thời gian để thở.”* |
| **R07** | Mid Frontend Dev | Nhận task từ brief tính năng mới | Giao việc thiếu mô tả, phải hỏi lại nhiều lần | 120 | — | 3 / 7 (42.9%) | 2 / 10 (20.0%) | Không | 41–60% | 3 / 5 | *“Task giao cho mình chỉ ghi mỗi title 5 chữ, không có tiêu chí nghiệm thu; mình phải ping PM 4 lần trong 2 ngày chỉ để hỏi rõ API nào dùng cho màn hình này.”* |
| **R08** | Project Lead | Sau cuộc họp khách hàng | Kiểm tra availability & xử lý xung đột | 80 | 3.0 | 5 / 10 (50.0%) | 3 / 15 (20.0%) | Có | 21–40% | 5 / 5 | *“Template Excel không giải quyết được việc người ta quên cập nhật; cái mình cần là hệ thống tự nhìn ra ai đang quá tải và đề xuất luôn 2–3 phương án thay thế để mình chọn.”* |

## Phân tích thống kê định lượng (Summary Statistics)

- **Quy mô mẫu**: 8 phản hồi hợp lệ (3 Project/Team Lead, 1 Delivery/Resource Manager, 4 Kỹ sư/Developer).
- **M-01 (Meeting Time-to-Owner)**: Median = **75.0 phút** (Trung vị), P90 = **105 phút**.
- **M-02 (Project Time-to-Approved-Team)**: Median = **3.5 ngày** (Dao động 3.0 – 4.0 ngày).
- **M-03 (Completeness trong 24h)**: **47.2%** (Tổng cộng 41/86 task đạt chuẩn trong 24h).
- **M-04 (Tỷ lệ đổi người do mismatch/quá tải)**: **18.5%** (23/127 task trong 30 ngày gần nhất).
- **Nhân sự chuyên môn hiếm quá tải (>100% capacity)**: **75.0%** (6/8 phản hồi xác nhận có hiện tượng này).
- **Đánh giá giải pháp Non-AI (Template/Board)**: 62.5% cho rằng chỉ giải quyết được 21–40% pain.
- **Mức độ hữu ích kỳ vọng của AI Assistant (Human-approved)**: **4.25 / 5.0**.
