# [Bài thực hành 3] Phân tích và giải quyết tình huống khách hàng khiếu nại
## 1. Prompt hoàn chỉnh (Chain-of-Thought)
"Đóng vai Chuyên viên CSKH ngành công nghệ. Hãy xử lý khiếu nại: "Mua laptop 10 ngày, máy nóng, quạt kêu to, pin 2 tiếng. Mang ra cửa hàng chỉ được vệ sinh, 2 ngày sau vẫn bị. Khách đòi đổi máy hoặc hoàn tiền."

Hãy suy luận lần lượt theo 5 bước (Chain-of-Thought):

Phân loại thông tin: Tách rõ Dữ kiện thực tế, Giả thuyết kỹ thuật và Thông tin chưa xác định.

Đánh giá vấn đề: Liệt kê lỗi và xếp hạng mức độ nghiêm trọng (Thấp/Trung bình/Cao).

Thông tin cần xác minh: Các dữ liệu bắt buộc kiểm tra trước khi chốt phương án.

Đề xuất 2 phương án xử lý: Kèm ưu điểm và hạn chế của từng phương án.

Soạn phản hồi khách hàng: Ngắn gọn, đồng cảm, chuyên nghiệp.

Ràng buộc: KHÔNG tự bịa chính sách đổi trả của cửa hàng; KHÔNG kết luận lỗi phần cứng khi chưa test máy."
## 2. Đầu ra mẫu (Báo cáo & Phản hồi)
**Bước 1 & 2: Phân tích tình huống**
- Dữ kiện: Mua 10 ngày; nóng, quạt ồn, pin 2h; đã vệ sinh ở lần 1 nhưng không hết; khách đòi đổi/trả.
- Giả thuyết: Lỗi phần cứng (pin/tản nhiệt) HOẶC do khách chạy tác vụ nặng/game không cắm sạc.
- Chưa xác định: Dòng máy (Gaming hay Văn phòng), biên bản kiểm tra lần 1, chính sách đổi trả 10 ngày của shop.
**Mức độ nghiêm trọng:**
- Dịch vụ lần 1 xử lý qua loa: Cao (gây bức xúc chính cho khách).
- Lỗi nóng/pin yếu: Trung bình - Cao (cần đo đạc thực tế để kết luận).
## Bước 3: Danh sách thông tin cần xác minh
- Quy định đổi trả/hoàn tiền của cửa hàng trong vòng 10 ngày.
- Mã máy cụ thể (Laptop Gaming pin 2h là bình thường, máy văn phòng là lỗi) & lịch sử test lần 1.
- Thói quen, phần mềm khách hay sử dụng.
## Bước 4: Hai phương án xử lý
**Phương án 1: Kỹ thuật trưởng kiểm tra sâu & Đổi mới nếu đúng lỗi.**
- Ưu điểm: Xử lý dứt điểm, xoa dịu sự bức xúc ở lần 1.
- Hạn chế: Khách phải mất công đi lại thêm một lần.
**Phương án 2: Hỗ trợ nhận máy tận nơi & Cho mượn máy dùng tạm.**
- Ưu điểm: Xóa bỏ hoàn toàn sự bất tiện đi lại, lấy lại uy tín tuyệt đối.
- Hạn chế: Tốn nhân sự và chi phí vận hành của cửa hàng.
## Bước 5: Phản hồi gửi khách hàng
"Chào anh/chị [Tên], cửa hàng chân thành xin lỗi vì trải nghiệm chưa tốt với chiếc laptop mới cũng như khâu kiểm tra chưa triệt để ở lần trước.
Để đảm bảo quyền lợi cho anh/chị, Kỹ thuật trưởng của chúng tôi xin trực tiếp kiểm tra chuyên sâu tình trạng pin và tản nhiệt của máy, từ đó áp dụng phương án xử lý thỏa đáng nhất theo đúng quy định của cửa hàng.
Anh/chị vui lòng cho biết khung giờ thuận tiện để ghé shop, hoặc cho phép nhân viên đến nhận máy tận nơi để anh/chị đỡ mất công đi lại nhé. Trân trọng!"    