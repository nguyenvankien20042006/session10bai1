# BÀI 1: Phân Tích & Lựa Chọn Chiến Lược Tài Liệu Hóa (Dạng Phân tích)

## Đáp án lựa chọn: **Phương án B**

---

## Lý do chọn Phương án B
- **Tổng quan ngữ cảnh đầy đủ:** Antigravity có khả năng index toàn bộ thư mục Guai-api, giúp AI đọc xuyên suốt nhiều lớp (Controller, Service, Repository, JWT Filter). Điều này giải quyết triệt để vấn đề logic nghiệp vụ trải dài nhiều file.  
- **Vai trò rõ ràng:** Prompt yêu cầu AI đóng vai System Analyst, tập trung vào phân tích nghiệp vụ thay vì chỉ giải thích code.  
- **Định dạng đầu ra chuẩn:** Yêu cầu AI xuất bản đặc tả Use Case theo format SRS (Pre-conditions, Main Flow, Exceptions), phù hợp với yêu cầu tài liệu hóa doanh nghiệp.  
- **Giảm thiểu thất thoát ngữ cảnh:** Vì toàn bộ codebase được index, AI không bị mất thông tin khi phải ghép nối thủ công.  
- **Phát huy sức mạnh công cụ:** Đây chính là điểm mạnh của Antigravity trong Session 10: khả năng đọc toàn bộ hệ thống, phân tích luồng end-to-end, thay vì chỉ từng đoạn nhỏ.

---

## Lý do loại trừ Phương án A
- **Ngữ cảnh rời rạc:** Chỉ giải thích từng đoạn code riêng lẻ, người dùng phải tự tổng hợp → dễ bỏ sót logic liên kết giữa các lớp.  
- **Nguy cơ thất thoát ngữ cảnh:** Khi luồng nghiệp vụ trải dài nhiều file, việc bôi đen từng đoạn không đảm bảo AI hiểu toàn bộ flow.  
- **Đầu ra không chuẩn:** AI chỉ giải thích code, không sinh ra đặc tả Use Case theo format SRS. Người dùng phải tự viết lại.

---

## Lý do loại trừ Phương án C
- **Thủ công, dễ lỗi:** Copy 5 file vào ChatGPT/Gemini không đảm bảo đầy đủ ngữ cảnh (có thể còn nhiều file liên quan khác).  
- **Nguy cơ context loss:** Khi dữ liệu dán vào quá dài, AI có thể bỏ sót hoặc rút gọn, dẫn đến mất chi tiết quan trọng.  
- **Không tối ưu công cụ:** Đây là cách làm tốn công sức, không tận dụng khả năng index toàn bộ codebase như Antigravity.  
- **Đầu ra thiếu chuẩn hóa:** AI có thể viết tài liệu nhưng không theo format Use Case chuẩn SRS nếu prompt không đủ chi tiết.

---

## Kết luận
- **Phương án B** là lựa chọn tối ưu vì:  
  - Đảm bảo AI có toàn bộ ngữ cảnh hệ thống.  
  - Đầu ra chuẩn SRS Use Case.  
  - Giảm thiểu rủi ro thất thoát ngữ cảnh.  
  - Phát huy đúng sức mạnh công cụ Antigravity trong Session 10.  
