# BÀI THỰC HÀNH 5

---

## 1. SƠ ĐỒ CHUỖI PROMPT CHAINING (5 BƯỚC)

```text
[Thông tin cố định: Python cơ bản | SV năm 1 (18–20 tuổi) | 8 tuần | 100 đăng ký tư vấn | FB & TikTok]
        │
        ▼
[PROMPT 1 (CREATE)] Phân tích chân dung khách hàng mục tiêu (Buyer Persona)
        │ Output 1
        ▼
[PROMPT 2 (CREATE)] Xác định Thông điệp truyền thông chính (Key Message)
        │ Output 2
        ▼
[PROMPT 3 (CREATE)] Lập kế hoạch nội dung 7 ngày trên Facebook & TikTok
        │ Output 3
        ▼
[PROMPT 4 (CREATE)] Viết 2 bài Facebook & 2 kịch bản TikTok (30–45 giây)
        │ Output 4
        ▼
[PROMPT 5 (CREATE)] Kiểm tra tính nhất quán toàn chiến dịch (Audit)
```

---

## 2. 5 PROMPT LIÊN TIẾP

### PROMPT 1: Phân tích chân dung khách hàng mục tiêu
- **C – Character:** Bạn là Chuyên gia Nghiên cứu Khách hàng trong lĩnh vực EdTech.
- **R – Request:** Phân tích chân dung khách hàng mục tiêu cho khóa học **Python cơ bản dành cho người mới bắt đầu**, đối tượng **sinh viên năm nhất (18–20 tuổi)**, thời lượng **8 tuần**, mục tiêu **100 lượt đăng ký tư vấn** qua **Facebook và TikTok**.
- **E – Examples:** Ví dụ mục Nỗi đau: *"Tự học trên YouTube bị ngợp tài liệu, gặp lỗi code (bug) không biết hỏi ai nên dễ bỏ cuộc."*
- **A – Adjustments:** Giữ nguyên thông tin khóa học cố định; không tự thêm thông tin về học phí hay cam kết việc làm.
- **T – Type of output:** Danh sách gạch đầu dòng gồm 5 mục: Nhân khẩu học, Nỗi đau, Mong muốn, Rào cản ra quyết định, Hành vi trên Facebook/TikTok.
- **E – Extras:** Nội dung cô đọng, thực tế, sát tâm lý sinh viên năm nhất Việt Nam để làm đầu vào trực tiếp cho Bước 2.

### PROMPT 2: Xác định thông điệp truyền thông chính
- **C – Character:** Bạn là Giám đốc Sáng tạo (Creative Director) chuyên chiến dịch tuyển sinh EdTech.
- **R – Request:** Dựa trên `[Output 1 – Chân dung khách hàng]` và thông tin khóa học cố định (Python cơ bản, SV năm 1, 8 tuần, 100 đăng ký tư vấn), hãy đề xuất **DUY NHẤT 1 Thông điệp truyền thông chính (Key Message)** và giải thích lý do lựa chọn.
- **E – Examples:** Ví dụ cấu trúc Key Message: *"[Thời lượng] + [Giải quyết nỗi đau] – [Đối tượng] + [Kết quả đạt được]"*.
- **A – Adjustments:** Thông điệp dài dưới 15 từ, bám sát đúng thời lượng 8 tuần và đối tượng tân sinh viên; không phóng đại sai thực tế.
- **T – Type of output:** 1 câu Key Message nổi bật (in đậm/trích dẫn) kèm 1 đoạn ngắn giải thích lý do phù hợp.
- **E – Extras:** Thông điệp phải dễ lặp lại đồng bộ trên cả bài viết Facebook lẫn kịch bản video ngắn TikTok.

### PROMPT 3: Lập kế hoạch nội dung 7 ngày
- **C – Character:** Bạn là Content Strategist chuyên triển khai phễu tuyển sinh trên Facebook & TikTok.
- **R – Request:** Sử dụng `[Output 1]` và `[Output 2]`, lập lịch đăng nội dung chi tiết trong **7 ngày** trên Facebook và TikTok nhằm đạt mục tiêu **100 lượt đăng ký tư vấn**.
- **E – Examples:** Ngày 1 | Nhận biết | TikTok | Video 35s chạm nỗi đau lần đầu học code | Tăng tương tác & bình luận.
- **A – Adjustments:** Phân bổ đủ 4 giai đoạn phễu (Nhận biết → Quan tâm → Thuyết phục → Chuyển đổi); giữ đúng 2 kênh Facebook và TikTok.
- **T – Type of output:** Bảng (Markdown Table) gồm các cột: Ngày, Giai đoạn phễu, Kênh, Chủ đề/Định dạng, Mục tiêu & CTA.
- **E – Extras:** Đảm bảo sự phối hợp nhịp nhàng giữa nội dung ngắn gây chú ý trên TikTok và nội dung chuyên sâu chuyển đổi trên Facebook.

### PROMPT 4: Viết 2 bài đăng Facebook & 2 kịch bản TikTok (30–45 giây)
- **C – Character:** Bạn là Copywriter & Scriptwriter chuyên viết nội dung chuyển đổi cho đối tượng Gen Z / sinh viên.
- **R – Request:** Dựa trên `[Output 1, 2, 3]`, hãy sản xuất:
  1. Hai bài đăng Facebook (Bài 1: Chạm nỗi đau & Lộ trình 8 tuần; Bài 2: Giải đáp rào cản & Kêu gọi đăng ký tư vấn).
  2. Hai kịch bản video TikTok thời lượng **30–45 giây**.
- **E – Examples:** Kịch bản TikTok chia 3 cột: `0:00–0:05 | Hình ảnh sinh viên nhìn màn hình lỗi đỏ | Thoại + Text trên màn hình`.
- **A – Adjustments:** Phải lồng ghép nguyên văn Key Message từ Bước 2; giữ nguyên thông số khóa học (Python cơ bản, 8 tuần, SV năm nhất 18–20 tuổi); mọi CTA đều hướng về **Đăng ký tư vấn miễn phí**.
- **T – Type of output:** Văn bản bài đăng hoàn chỉnh (có Tiêu đề, Thân bài, CTA, Hashtag) cho Facebook; Bảng phân cảnh (Thời gian / Hình ảnh / Lời thoại & Text) cho TikTok.
- **E – Extras:** Giọng văn gần gũi, năng động, đúng ngôn ngữ sinh viên đại học, không khô khan.

### PROMPT 5: Kiểm tra tính nhất quán toàn chiến dịch (Audit)
- **C – Character:** Bạn là Quản lý Chiến dịch Marketing (Marketing QA/Auditor) kiểm duyệt độc lập trước khi chạy thực tế.
- **R – Request:** Đối chiếu toàn bộ `[Output 1, 2, 3, 4]` với Thông tin gốc khóa học để kiểm tra tính nhất quán theo 4 tiêu chí: Thông tin khóa học, Sự liên kết với chân dung khách hàng, Tính xuyên suốt của Key Message, và Sự đồng nhất của CTA.
- **E – Examples:** `Tiêu chí 1 | Đạt | Khớp 100% thời lượng 8 tuần và đối tượng 18–20 tuổi ở tất cả các bài.`
- **A – Adjustments:** Đánh giá khách quan, chỉ rõ bằng chứng đối chiếu; đề xuất tối ưu ngắn gọn nếu cần thiết.
- **T – Type of output:** Bảng báo cáo kiểm tra tính nhất quán (Tiêu chí / Trạng thái / Chi tiết đối chiếu) + 1 đề xuất tối ưu thực tế.
- **E – Extras:** Đảm bảo chiến dịch sẵn sàng bàn giao cho đội ngũ vận hành chạy ngay mà không gặp sai lệch thông tin.

---

## 3. KẾT QUẢ ĐẦU RA

### A. Chân dung khách hàng mục tiêu (Output 1)
- **Nhân khẩu học:** Sinh viên năm nhất (18–20 tuổi), vừa chuyển từ cấp 3 lên đại học (gồm cả sinh viên CNTT và sinh viên Kinh tế/Kỹ thuật muốn học thêm kỹ năng lập trình).
- **Nỗi đau (Pain points):** Chưa từng viết code, sợ lập trình khô khan khó hiểu; tự học trên mạng bị ngợp tài liệu, gặp lỗi (bug) không có người sửa nên dễ bỏ cuộc; lo bị tụt lại so với bạn bè ngay từ năm nhất.
- **Mong muốn (Goals):** Nắm vững nền tảng Python trong thời gian ngắn gọn (**8 tuần**), tự làm được bài tập/mini-project đầu tiên để tự tin học môn chuyên ngành và làm đẹp CV.
- **Rào cản ra quyết định:** Ngại lịch học trùng lịch trên trường, sợ học xong vẫn không tự code được, ngân sách sinh viên hạn chế nên cần được tư vấn rõ ràng trước khi quyết định.
- **Hành vi trên mạng xã hội:**
  - *TikTok:* Thích video ngắn 30–45 giây, bắt trend, thực tế, đánh trúng nỗi sợ tân sinh viên.
  - *Facebook:* Đọc và lưu bài chia sẻ lộ trình chi tiết, tương tác trong group sinh viên, sẵn sàng nhắn tin/điền form đăng ký tư vấn.

### B. Thông điệp truyền thông chính (Output 2)
> **Key Message:** *"8 tuần xóa mù code – Tân sinh viên làm chủ Python từ con số 0."*

- **Lý do phù hợp:** Gọi thẳng đúng đối tượng (*Tân sinh viên*), giữ chuẩn thời lượng (*8 tuần*), giải tỏa trực tiếp nỗi sợ lớn nhất (*xóa mù code, từ con số 0*) và khẳng định rõ môn học (*Python*).

### C. Lịch đăng nội dung 7 ngày (Output 3)

| Ngày | Giai đoạn phễu | Kênh | Chủ đề / Định dạng | Mục tiêu & CTA |
| :--- | :--- | :--- | :--- | :--- |
| **Ngày 1** | Nhận biết | TikTok | Video ngắn (35s): *"Nỗi ám ảnh mang tên dòng code đầu tiên của SV năm nhất"* | Chạm nỗi đau, tăng lượt xem & bình luận đồng cảm. |
| **Ngày 2** | Nhận biết | Facebook | Bài viết + Infographic: *"Tại sao SV năm nhất nên bắt đầu lập trình bằng Python?"* | Xây dựng nhận thức, kéo lượt lưu bài viết. |
| **Ngày 3** | Quan tâm | Facebook | Bài viết chi tiết: *"8 tuần xóa mù code – Lộ trình học Python từ con số 0 cho tân sinh viên"* | Giới thiệu rõ lộ trình 8 tuần; CTA: Điền form/Inbox nhận tư vấn. |
| **Ngày 4** | Quan tâm | TikTok | Video ngắn (40s): *"8 tuần học Python từ số 0 bạn sẽ làm được gì?"* | Trực quan hóa kết quả đầu ra; CTA: Link bio đăng ký tư vấn. |
| **Ngày 5** | Thuyết phục | Facebook | Bài viết FAQ: *"Chưa biết gì về IT, lịch học dày có theo nổi khóa Python 8 tuần không?"* | Gỡ bỏ rào cản tâm lý; CTA: Đăng ký tư vấn 1-1 miễn phí. |
| **Ngày 6** | Thuyết phục | TikTok | Video POV (35s): *"Tự học Python một mình ở nhà vs. Có lộ trình 8 tuần kèm sát"* | Tạo sự tương phản hiệu quả; CTA: Đăng ký tư vấn ngay. |
| **Ngày 7** | Chuyển đổi | Facebook & TikTok | Bài viết/Video chốt đợt: *"Cơ hội cuối nhận tư vấn lộ trình 1-1 khóa Python cơ bản 8 tuần"* | Thúc đẩy chuyển đổi mạnh để cán mốc **100 lượt đăng ký tư vấn**. |

### D. Hai bài đăng Facebook (Output 4A)

#### Bài đăng Facebook 1 (Ngày 3 – Chạm nỗi đau & Lộ trình 8 tuần)
> **TÂN SINH VIÊN SỢ CODE? 8 TUẦN XÓA MÙ CODE – LÀM CHỦ PYTHON TỪ CON SỐ 0!**
>
> Mới bước chân vào giảng đường đại học, bạn có đang rơi vào cảnh:
> - Mở tài liệu lập trình lên nhưng không biết bắt đầu từ đâu?
> - Tự học trên mạng, gặp lỗi (bug) không biết hỏi ai rồi bỏ dở?
> - Lo lắng bị tụt lại phía sau khi bạn bè xung quanh đã bắt đầu viết code?
>
> Đừng để nỗi sợ code cản bước năm nhất của bạn! Khóa học **Python cơ bản dành cho người mới bắt đầu** được thiết kế riêng cho sinh viên năm nhất (18–20 tuổi) với lộ trình tinh gọn chỉ trong **8 tuần**:
> - **Tuần 1–3:** Nắm chắc tư duy lập trình & cú pháp Python cơ bản từ con số 0.
> - **Tuần 4–6:** Thực hành xử lý dữ liệu, viết hàm và giải quyết bài toán thực tế.
> - **Tuần 7–8:** Hoàn thiện mini-project đầu tay để tự tin bước vào các môn chuyên ngành.
>
> Không yêu cầu nền tảng trước đó – chỉ cần bạn sẵn sàng bắt đầu!
> **Đăng ký tư vấn miễn phí lộ trình 8 tuần ngay tại đây:** [Link Form đăng ký] hoặc bình luận **"TƯ VẤN"** bên dưới để trung tâm hỗ trợ trực tiếp nhé!
>
> `#PythonCoBan #TanSinhVien #XoaMuCode8Tuan #HocLapTrinhTuSo0`

#### Bài đăng Facebook 2 (Ngày 5 – Giải đáp rào cản & Kêu gọi đăng ký tư vấn)
> **"CHƯA BIẾT GÌ VỀ IT CÓ HỌC ĐƯỢC PYTHON TRONG 8 TUẦN KHÔNG?"**
>
> Đây là câu hỏi mà trung tâm nhận được nhiều nhất từ các bạn sinh viên năm nhất (18–20 tuổi). Câu trả lời là: **HOÀN TOÀN ĐƯỢC!**
>
> Vì sao khóa **Python cơ bản** phù hợp với người mới bắt đầu?
> - **Ngôn ngữ dễ tiếp cận nhất:** Cú pháp Python ngắn gọn, gần giống tiếng Anh, giúp bạn tập trung vào tư duy thay vì vật lộn với ký tự phức tạp.
> - **Lộ trình 8 tuần vừa vặn lịch đại học:** Thiết kế để sinh viên năm nhất dễ dàng cân bằng giữa việc học trên trường và thực hành code mỗi tuần.
> - **Học đi đôi với sửa lỗi trực tiếp:** Không còn cảnh tự mày mò một mình khi code báo lỗi.
>
> **8 tuần xóa mù code – Tân sinh viên làm chủ Python từ con số 0.**
> Bạn vẫn còn băn khoăn về lịch học hay cách học phù hợp với bản thân?
> **Nhấn vào link bên dưới hoặc nhắn tin trực tiếp cho fanpage để đăng ký tư vấn 1-1 miễn phí ngay hôm nay!**
> Link đăng ký tư vấn: [Link Form đăng ký]
>
> `#PythonChoNguoiMoi #SinhVienNamNhat #LoTrinh8Tuan`

### E. Hai kịch bản video TikTok (30–45 giây) (Output 4B)

#### Kịch bản TikTok 1 (Ngày 1 – Chạm nỗi đau | 35 giây)
| Thời gian | Hình ảnh / Bối cảnh | Lời thoại (Voiceover) & Text trên màn hình |
| :--- | :--- | :--- |
| **0:00 – 0:05** | Sinh viên năm nhất ngồi nhìn màn hình laptop đầy lỗi đỏ, mặt hoang mang. | **Thoại:** "Tân sinh viên 18–20 tuổi lần đầu tự học code kiểu..." <br> **Text:** *Khi SV năm nhất lần đầu học code* |
| **0:05 – 0:18** | Chuyển cảnh nhanh: Mở 10 tab YouTube, gõ vài dòng, hiện `SyntaxError`, gập máy thở dài. | **Thoại:** "Mở 10 tab hướng dẫn, không biết bắt đầu từ đâu, dính lỗi đỏ là muốn bỏ cuộc luôn đúng không?" <br> **Text:** *Ngợp tài liệu – Gặp bug không biết hỏi ai* |
| **0:18 – 0:28** | Chuyển cảnh tươi sáng: Sinh viên gõ Python mượt mà, hiện lộ trình 8 tuần rõ ràng. | **Thoại:** "Đừng tự bơi nữa! Chỉ cần 8 tuần với khóa Python cơ bản cho người mới, bạn sẽ đi từ con số 0 đến tự tin viết code." <br> **Text:** *8 tuần xóa mù code – Làm chủ Python từ số 0* |
| **0:28 – 0:35** | Nhân vật chỉ tay về phía nút link bio. | **Thoại:** "Muốn xem lộ trình 8 tuần chi tiết? Bấm ngay link ở bio để đăng ký tư vấn miễn phí nhé!" <br> **Text:** *Link bio: Đăng ký tư vấn miễn phí!* |

#### Kịch bản TikTok 2 (Ngày 4 – Kết quả sau 8 tuần | 40 giây)
| Thời gian | Hình ảnh / Bối cảnh | Lời thoại (Voiceover) & Text trên màn hình |
| :--- | :--- | :--- |
| **0:00 – 0:05** | Quay cận mặt sinh viên hỏi thẳng vào camera. | **Thoại:** "Chưa từng viết một dòng code nào, liệu 8 tuần có học được Python không?" <br> **Text:** *Số 0 → Python trong 8 tuần?* |
| **0:05 – 0:18** | Chia màn hình: Bên trái "Tuần 1" (chưa biết gì), bên phải hiện mốc Tuần 1–3, Tuần 4–6. | **Thoại:** "Đây là lộ trình dành riêng cho sinh viên năm nhất: 3 tuần đầu nắm chắc nền tảng, 3 tuần tiếp theo thực hành giải bài toán thực tế." <br> **Text:** *Tuần 1–3: Nền tảng \| Tuần 4–6: Thực hành* |
| **0:18 – 0:30** | Quay màn hình chạy thành công mini-project Python đơn giản, sinh viên mỉm cười. | **Thoại:** "Và 2 tuần cuối, bạn tự tay hoàn thiện sản phẩm nhỏ đầu tiên của mình. Đúng chuẩn 8 tuần xóa mù code!" <br> **Text:** *Tuần 7–8: Hoàn thiện Mini-project đầu tay* |
| **0:30 – 0:40** | Hiện khung CTA rõ ràng giữa màn hình. | **Thoại:** "Đăng ký tư vấn miễn phí ngay tại link bio để giữ suất nhận lộ trình chi tiết cho tân sinh viên nhé!" <br> **Text:** *Đăng ký tư vấn miễn phí tại Link Bio!* |

### F. Báo cáo kiểm tra tính nhất quán (Output 5)

| Tiêu chí kiểm tra | Trạng thái | Chi tiết đối chiếu |
| :--- | :---: | :--- |
| **1. Thông tin khóa học** | **Đạt** | Giữ nguyên 100% thông tin gốc xuyên suốt 5 bước: Python cơ bản cho người mới, SV năm nhất (18–20 tuổi), 8 tuần, 100 lượt đăng ký tư vấn, Facebook & TikTok. Không tự thêm học phí hay cam kết sai lệch. |
| **2. Liên kết Chân dung khách hàng** | **Đạt** | Các nỗi đau (sợ code, ngợp tài liệu, gặp bug) và rào cản (chưa biết IT, ngại lịch học) từ Output 1 được giải quyết trực tiếp trong lịch 7 ngày, 2 bài Facebook và 2 kịch bản TikTok. |
| **3. Xuyên suốt Thông điệp chính** | **Đạt** | Key Message *"8 tuần xóa mù code – Tân sinh viên làm chủ Python từ con số 0"* xuất hiện đồng nhất từ kế hoạch đến toàn bộ nội dung quảng cáo. |
| **4. Đồng nhất Mục tiêu & CTA** | **Đạt** | Toàn bộ CTA trên Facebook và TikTok đều dẫn về duy nhất hành động **Đăng ký tư vấn miễn phí**, phục vụ trực tiếp mục tiêu 100 lượt đăng ký. |

- **Đề xuất tối ưu trước khi chạy:** Gắn mã theo dõi UTM riêng cho Facebook và TikTok để đo lường kênh chuyển đổi tốt hơn, từ đó dồn ngân sách/tần suất đăng vào Ngày 6–7 nhằm đảm bảo đạt mốc 100 lượt đăng ký tư vấn.
