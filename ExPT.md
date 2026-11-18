# [Phân tích] So sánh Trade-off các giải pháp ra lệnh cho Kỹ thuật Prompting Nâng cao (Logic & Chuỗi)

## Bước 1: Đề xuất 2 prompt mẫu

**Giải pháp 1 – Prompt đơn giản:**

```text
Hãy phân tích bài toán theo từng bước (Chain-of-Thought), chia nhiệm vụ thành các phần nhỏ (Prompt Chaining). Nếu bị gián đoạn, hãy tiếp tục từ nội dung trước đó.
```

**Giải pháp 2 – Prompt chi tiết:**

```text
Hãy thực hiện nhiệm vụ theo yêu cầu:
1. Phân tích vấn đề theo từng bước logic.
2. Chia nhiệm vụ thành các giai đoạn nhỏ.
3. Kiểm tra kết quả sau mỗi giai đoạn.
4. Nếu bị gián đoạn, tiếp tục từ phần đã hoàn thành, không lặp lại.
5. Đảm bảo nội dung chính xác, nhất quán và đầy đủ.
```

## Bước 2: Bảng so sánh Trade-off

| Tiêu chí | Giải pháp 1 | Giải pháp 2 |
|---|---|---|
| Độ dễ hiểu | Cao | Trung bình |
| Tốn Token | Ít | Nhiều hơn |
| Chặn lỗi biên | Trung bình | Tốt |
| Tính nhất quán | Khá | Cao |
| Khả năng kiểm soát | Thấp | Cao |
| Tốc độ xử lý | Nhanh | Chậm hơn |

## Bước 3: Lựa chọn và chạy thử

**Lựa chọn: Giải pháp 2.**

**Lý do:** Prompt chi tiết giúp AI làm việc theo từng bước, hạn chế sai sót, kiểm tra kết quả và duy trì ngữ cảnh khi bị gián đoạn.

**Chạy thử:** Yêu cầu AI lập kế hoạch học tập trong 3 ngày.

| Giai đoạn | Kết quả |
|---|---|
| Ngày 1 | Xác định nội dung cần học |
| Ngày 2 | Thực hành và hoàn thành bài tập |
| Ngày 3 | Ôn tập và kiểm tra kiến thức |

