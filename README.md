# Bài 1: Bóc tách 6 thành phần cốt lõi trong công thức CREATE

## 1. Bối cảnh & Vấn đề

Tuấn là thực tập sinh phòng Marketing tại TechShop. Để chuẩn bị bài viết fanpage quảng bá dòng điện thoại mới, Tuấn nhập câu lệnh vào ChatGPT:

> "Viết bài đăng Facebook về iPhone mới"

Kết quả nhận về là một bài viết dài dòng, từ ngữ chung chung sáo rỗng (*"Sản phẩm tuyệt vời với công nghệ đỉnh cao..."*), không nêu được giá bán khuyến mãi, không có icon, không đúng phong cách trẻ trung của khách hàng TechShop. Tuấn than phiền với Trưởng phòng: *"AI viết văn chán quá, không dùng vào thực tế được!"*.

## 2. Ràng buộc & Bẫy dữ liệu

**Bẫy:** Tuấn mắc lỗi **"Ảo tưởng ngữ cảnh" (Context Illusion)** - nghĩ rằng AI tự biết mình là ai, viết cho ai và viết theo phong cách nào. Khi thiếu 5/6 thành phần của Khung CREATE, AI buộc phải dùng xác suất thống kê chung chung nhất để trả lời.

## 3. Yêu cầu đầu ra

### Phần 1 (Phân tích lỗi)

Chỉ ra chính xác 5 thành phần trong Khung CREATE mà câu lệnh của Tuấn đã bỏ sót. Giải thích ngắn gọn tác hại của việc thiếu từng thành phần đó dựa trên Mục 2.1 Lesson 01.

| STT | Thành phần | Tác hại |
|:---:|------------|---------|
| 1 | **Context** (Bối cảnh) | AI không biết mục đích nên viết lan man, không có mục tiêu rõ |
| 2 | **Role** (Vai trò) | Giọng văn trung tính, không có "chất" của người viết |
| 3 | **Example** (Ví dụ mẫu) | AI không biết phong cách bạn muốn, viết theo mẫu chung chung |
| 4 | **Audience** (Đối tượng) | Ngôn ngữ và nội dung không đánh trúng người đọc |
| 5 | **Extras** (Ràng buộc bổ sung) | Độ dài, format ngẫu nhiên, thiếu kêu gọi hành động |

### Phần 2 (Sửa lỗi)

Viết lại câu lệnh trên thành một Prompt hoàn chỉnh theo đúng cấu trúc 6 thành phần **C - R - E - A - T - E** để tạo bài đăng Facebook hấp dẫn cho TechShop.

---

**[C - CONTEXT / Bối cảnh]**
TechShop là cửa hàng điện thoại chính hãng tại [TP.HCM], bảo hành [12 tháng]. Cửa hàng vừa nhận lô [iPhone 17 Pro] và đang có ưu đãi [giảm 1 triệu, tặng ốp lưng + cường lực, trả góp 0%] đến hết [30/11]. Mục tiêu: thu hút người đang có nhu cầu đổi máy inbox hoặc đến cửa hàng đặt cọc trong tuần đầu mở bán.

**[R - ROLE / Vai trò]**
Bạn là chuyên viên PR cho TechShop, 5 năm kinh nghiệm truyền thông sản phẩm công nghệ trên Facebook. Giọng văn chuyên nghiệp, đáng tin cậy nhưng vẫn gần gũi, không khoa trương.

**[E - EXAMPLE / Ví dụ mẫu]**
Học theo giọng điệu và cách mở bài của đoạn mẫu sau (không copy nội dung):
"Máy cũ lag, pin tụt nhanh, chụp tối thì nhòe? Có thể đã đến lúc cho chiếc điện thoại của bạn một lần nghỉ hưu xứng đáng. TechShop giữ máy sẵn cho bạn đây"

**[A - AUDIENCE / Đối tượng]**
Sinh viên và dân văn phòng 20-30 tuổi, thích chụp ảnh, quay video, quan tâm giá và trả góp, đang dùng iPhone đời cũ hoặc Android muốn đổi máy.

**[T - TASK / Nhiệm vụ]**
Viết 1 bài PR đăng Facebook giới thiệu [iPhone 17 Pro], nêu bật 3 điểm đáng tiền nhất với đối tượng trên (camera, pin, hiệu năng) và ưu đãi hiện có tại TechShop.

**[E - EXTRA / Ràng buộc bổ sung]**
- Độ dài: 120-150 từ, xuống dòng ngắn dễ đọc trên điện thoại
- Câu mở đầu đánh vào nỗi đau hoặc gây tò mò
- Dùng 4-6 emoji, giọng PR chuyên nghiệp, không sáo rỗng (tránh "đỉnh cao", "mạnh mẽ vượt trội")
- Chỉ nêu thông số có thật, không nói quá sự thật
- Kết bài bằng CTA: "Inbox ngay / Comment SĐT để được tư vấn"
- Kèm 3 hashtag: #TechShop #iPhone #[ThànhPhố]
- Viết 2 phiên bản (bản đầy đủ + bản ngắn để chạy quảng cáo)
