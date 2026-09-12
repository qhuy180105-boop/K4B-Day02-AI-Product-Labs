# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Quang Huy
- Mã học viên: 2A202602462
- Nhóm: SLOPPER
- Candidate problem nhóm chọn: Phân công task theo kỹ năng và tải việc (Capacity) trong doanh nghiệp từ Meeting Notes & Project Briefs

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 8 problem thực tế từ trải nghiệm cá nhân; chọn ra top 3 Problem Cards có số liệu minh chứng cụ thể. | Đưa ra được 3 đề xuất problem chất lượng cao, có workflow rõ ràng để nhóm cân nhắc. |
| Pitch Problem Card | Pitch chi tiết Problem Card (Phân công task theo kỹ năng & capacity trong doanh nghiệp) trong 2 phút với baseline 110 phút/lần. | Thuyết phục nhóm thấy được pain point thực tế vô cùng phổ biến của PM/Lead trong doanh nghiệp. |
| Gom trùng / cluster | Đề xuất gom 9 candidate problems của nhóm thành 3 cụm chính: Quản lý công việc & Vận hành nhóm, Tự động hóa tài liệu, Quản lý cá nhân. | Giúp nhóm hệ thống hóa danh sách đề xuất nhanh chóng và trực quan trước khi shortlist. |
| Chọn candidate problem | Đưa ra lập luận bảo vệ candidate phân công task theo kỹ năng & capacity dựa trên tần suất lặp lại và tính sẵn sàng của workflow. | Đồng thuận cùng nhóm chọn đề tài phân công task & capacity làm candidate problem chính thức để deep-dive. |
| Validation / research | Đóng góp bộ câu hỏi phỏng vấn nhanh 3 PM/Lead và tìm kiếm 3 công cụ hiện có (Jira, Asana, Kingwork). | Tìm ra khoảng trống của thị trường: các tool hiện tại thiếu bước tự động bóc tách task từ meeting transcript kết hợp check capacity cross-project. |
| Workflow nhóm | Vẽ draft Current Workflow (9 bước) và cùng nhóm hoàn thiện Future Workflow với các mốc thời gian và điểm bàn giao (handoff). | Định hình rõ ràng 6 bước workflow mới, đặc biệt là bước kiểm tra (human boundary) của Manager. |
| Problem Statement | Đề xuất chỉ số Success Metric cụ thể (giảm từ 110' xuống <10'/lần) và khoanh vùng Boundary khắt khe cho AI. | Hoàn thiện Problem Statement v0/v1 chặt chẽ, không bị sa đàm vào mô tả chung chung. |
| Rule / Workflow / Agent | Phân tích rủi ro ảo giác (hallucination) và bảo mật RBAC nếu dùng Agent, lập luận ủng hộ giải pháp mức AI Workflow. | Giúp nhóm giữ thực tế, không bị cuốn vào việc dựng Agent phức tạp ngoài tầm kiểm soát. |
| Decision | Đóng góp ý kiến cho exit/rollback plan và xây dựng phương án Pilot thử nghiệm ngầm (Shadow mode) trên 1-2 team dự án nhỏ. | Chốt quyết định Not Yet cho sản xuất đại trà / GO cho Pilot có điều kiện kèm theo kế hoạch thử nghiệm thực tế rõ ràng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người đề xuất candidate problem ban đầu từ bài toán phân công công việc và cùng nhóm phát triển thành đề tài "Phân công task theo kỹ năng & capacity trong doanh nghiệp", đóng góp số liệu baseline 110 phút/lần và trực tiếp thiết lập ranh giới kiểm soát (Human Boundary) bắt buộc cho Manager/Lead trong Future Workflow.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các vấn đề thực tiễn của sinh viên theo 4 lăng kính. | Mở rộng góc nhìn về các tác vụ tốn thời gian rải rác trong tuần. | Gợi ý ý tưởng "dùng AI tự động viết hộ bài tiểu luận" vi phạm quy chế. | Lọc bỏ hoàn toàn các ý vi phạm, chỉ giữ lại các pain point workflow hợp lệ. |
| Problem Card | Đóng vai Skeptical PM để phản biện 3 Problem Cards cá nhân. | Chỉ ra rủi ro AI tạo task quá chung chung nếu meeting notes bị mờ hồ. | Đánh giá quá thấp độ phức tạp của việc phân công task và cân bằng tải (capacity) trong thực tế. | Bổ sung bắt buộc template meeting notes chuẩn và dữ liệu capacity làm đầu vào (input) cho AI. |
| Workflow | Dùng Mermaid/ASCII prompt để minh họa Before/After workflow. | Tạo sơ đồ workflow trực quan, rõ ràng các bước nối tiếp nhau. | Tự động bỏ qua bước Leader review chốt task, để AI tự gửi task thẳng. | Thêm bước Human Boundary 5 phút bắt buộc cho Leader/Manager duyệt trước khi broadcast. |
| Research | Tìm kiếm các giải pháp/tool hiện có đang giải bài toán quản lý task. | Liệt kê nhanh danh sách tính năng của Jira, Asana, Kingwork. | Bịa ra số liệu phần trăm người dùng hài lòng không có link kiểm chứng. | Xóa bỏ các số liệu vô căn cứ, tự truy cập trang chủ công cụ để kiểm chứng thật. |
| Problem Statement | Phản biện Problem Statement v0 để tìm chỗ mơ hồ. | Nhắc nhở làm rõ đơn vị đo lường và thời điểm đo của Success Metric. | Đề xuất Boundary quá rộng, ôm đùm cả phần đánh giá hiệu suất (KPI) nhân sự. | Thắt chặt Boundary: AI chỉ bóc tách task và gợi ý phân công theo capacity, không tự giao việc hay đánh giá KPI. |
| Rule / Workflow / Agent | Phân tích so sánh ưu rủi ro giữa AI Workflow và AI Agent. | Cung cấp danh sách rủi ro tiềm ẩn khi Agent tự ý gọi tool bên ngoài. | Khuyên nên dùng Agent để "hiện đại và tối ưu nhất" theo trào lưu. | Từ chối tư vấn của AI, quyết định chọn mức AI Workflow vừa đủ và an toàn. |
| Decision | Kiểm tra checklist các điều kiện Go / Not Yet / No-Go. | Gợi ý các kịch bản rollback khi AI gặp sự cố hoặc ngưng hoạt động. | Đề xuất Go ngay lập tức trên diện rộng mà không cần pilot. | Sửa lại quyết định Go kèm điều kiện bắt buộc: chỉ pilot thử nghiệm ngầm (shadow mode) trên 1-2 team dự án nhỏ. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe phần trình bày top 3 problems từ các thành viên trong nhóm Slopper, tôi nhận ra bài toán nào cũng có vẻ cấp thiết, nhưng nếu không mổ xẻ workflow hiện tại thì rất dễ rơi vào bẫy tưởng tượng ra pain point không có thật. Có những lúc thảo luận ở Phase 6, cả nhóm đã suýt bị cuốn vào tư duy "solution-first" khi một số bạn đề xuất dựng hẳn một AI Agent tự động truy cập Slack/Jira và tự ý phân công task cho nhân viên "cho ngầu". Tuy nhiên, sau khi tôi đưa ra câu hỏi phản biện về rủi ro ảo giác (hallucination), vi phạm bảo mật dữ liệu RBAC và nguy cơ AI giao sai người gây quá tải (burnout), nhóm đã nhanh chóng tỉnh táo quay lại đánh giá thực tế. Chúng tôi nhận ra rằng một AI Workflow có con người kiểm duyệt (Manager Human Boundary) kết hợp Rule Engine kiểm tra Capacity là vừa đủ để giải quyết 80% điểm nghẽn mà lại an toàn tuyệt đối. Điều khó khăn nhất với tôi khi tham gia hoàn thiện Problem Statement chính là việc thắt chặt Boundary và định lượng Success Metric; nếu không khéo, metric sẽ bị viết chung chung kiểu "giúp phân công nhanh hơn" thay vì chỉ số cứng như "giảm thời gian từ 110 phút xuống dưới 10 phút/lần" và "tỷ lệ reassign <5%". Đóng góp thực sự mà tôi tự hào nhất chính là việc bảo vệ thành công đề tài phân công task theo kỹ năng & capacity trong doanh nghiệp, đồng thời thiết lập ranh giới không cho AI tự ý giao việc hay đánh giá KPI. Nếu có cơ hội làm lại lab này, tôi sẽ challenge nhóm mạnh mẽ hơn ngay từ khâu Quick Validation ở Phase 4 bằng cách thực hiện một bài test thử nghiệm đọc meeting transcript thật, giúp nhóm thấy ngay ranh giới chính xác của AI trước khi chốt Problem Statement v1.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
