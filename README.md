# 1. Thiết kế giải pháp

**Mục tiêu:** Sử dụng AI để giải thích kiến thức bằng Feynman và tự động chấm bài bằng Rubric.

**Input:** Chủ đề, bài làm và tiêu chí chấm điểm.

**Output:** Giải thích kiến thức, điểm số, nhận xét và cách cải thiện.

**Quy trình:** Kiểm tra dữ liệu → Giải thích Feynman → Chấm Rubric → Tổng hợp kết quả.

# 2. Prompt thực thi

**Prompt 1 – Kiểm tra dữ liệu:**

Kiểm tra dữ liệu đầu vào. Nếu thiếu hoặc sai định dạng, hãy yêu cầu bổ sung.

**Prompt 2 – Giải thích Feynman:**

Giải thích chủ đề bằng ngôn ngữ đơn giản, dễ hiểu và có ví dụ.

**Prompt 3 – Chấm Rubric:**

Chấm bài theo từng tiêu chí, không tự ý thêm tiêu chí hoặc vượt thang điểm.

**Prompt 4 – Tổng hợp:**

Tổng hợp điểm số, nhận xét và cách cải thiện thành báo cáo ngắn gọn.

# 3. Xử lý lỗi

- Thiếu dữ liệu: Yêu cầu bổ sung.
- Bài làm trống: Không chấm điểm.
- Sai định dạng: Thông báo lỗi.
- Điểm vượt giới hạn: Kiểm tra lại.

# 4. Kết quả chạy thử

**Input:**
- Chủ đề: Trí tuệ nhân tạo (AI).
- Bài làm: AI giúp máy tính thực hiện công việc giống con người.
- Rubric: Nội dung 4 điểm, dễ hiểu 3 điểm, ví dụ 2 điểm, trình bày 1 điểm.

**Output:**

Giải thích: AI giúp máy tính thực hiện các công việc như trả lời câu hỏi và nhận diện hình ảnh.

| Tiêu chí | Điểm |
|---|---:|
| Nội dung | 3/4 |
| Dễ hiểu | 3/3 |
| Ví dụ | 0/2 |
| Trình bày | 1/1 |
| **Tổng** | **7/10** |

Nhận xét: Bài làm dễ hiểu nhưng thiếu ví dụ minh họa.

Cải thiện: Bổ sung ví dụ về ChatGPT hỗ trợ học tập.
