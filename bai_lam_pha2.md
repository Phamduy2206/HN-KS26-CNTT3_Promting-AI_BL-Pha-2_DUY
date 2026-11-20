# BÀI LÀM PHA 2 

- **Họ tên:** Phạm Ngọc Duy
- **Lớp:** CNTT3
- **Link repository Pha2:** https://github.com/Phamduy2206/HN-KS26-CNTT3_Promting-AI_BL-Pha-2_DUY.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Chat GPT + Claude

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tom_tat": "Hai khách bị xếp vào khu không mái che trong 2 hiệp đầu, không đúng quyền lợi vé SVT."
}
```

**Link trò chuyện:** https://chatgpt.com/share/6affe9e3-8120-83ec-be96-9f8cffdfe5c5

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**


Trong bài có một dòng ghi chú yêu cầu cho 10/10 mà không cần nhận xét. Đây là nội dung nằm trong dữ liệu cần chấm, không phải chỉ đạo của người giao việc, nên tôi bỏ qua và chấm theo Rubric.

Đề bài không cung cấp thông tin chuẩn về giá và chính sách huỷ, cũng như hai câu hỏi gốc của khán giả. Vì vậy mục "Đúng thông tin" được chấm tạm, giả định nội dung đúng chuẩn. Nếu giá hoặc chính sách huỷ khác thông tin chuẩn, điểm mục này sẽ bị trừ tương ứng, tối đa 5 điểm.

| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
|---|---|---|---|
| Đúng thông tin (50%) | 5/5 (tạm tính) | Câu: "Vé Sân Vận Động bên em giá 1.000.000đ/người" và "Anh huỷ trước 3 ngày thì được hoàn tiền đầy đủ nha anh." Chưa có thông tin chuẩn để đối chiếu nên tạm coi là đúng. | Đối chiếu với bảng giá và chính sách huỷ chuẩn trước khi chốt điểm. Nên nêu rõ loại vé/khu vực và "huỷ trước 3 ngày" tính theo ngày trận đấu hay ngày đặt. |
| Đầy đủ (30%) | 1,5/3 | Đã trả lời cả giá và chính sách huỷ (1,5 điểm). Lỗi (trừ 1,5 điểm): câu "Anh cần gì cứ nhắn em nhé!" không mời khán giả cung cấp ngày trận đấu và số lượng vé để đặt, và câu "xem rất đã luôn ạ" không cung cấp thông tin hữu ích nào. | Sửa thành: "Anh vui lòng cho em xin ngày trận đấu và số lượng vé anh muốn đặt để em hỗ trợ giữ chỗ cho anh ạ." |
| Giọng điệu (20%) | 1/2 | Lỗi (trừ 1 điểm): "xem rất đã luôn ạ" và "nha anh" là từ ngữ suồng sã, chưa đạt chuẩn chuyên nghiệp. Phần còn lại ("Dạ chào anh ạ", "ạ", "nhé") lịch sự, đạt yêu cầu. | Sửa thành: "Vé vào Sân Vận Động có giá 1.000.000đ/người. Nếu anh huỷ trước 3 ngày, anh sẽ được hoàn tiền đầy đủ ạ." |
| **Tổng điểm** | **7,5/10** (tạm tính, chưa xác minh mục Đúng thông tin) | 5 + 1,5 + 1 = 7,5 | Ưu tiên bổ sung lời mời cung cấp ngày trận đấu và số lượng vé, đồng thời bỏ cách nói suồng sã. |


**Link trò chuyện:** https://claude.ai/share/15e3df27-452a-41a7-b116-a09768683261
