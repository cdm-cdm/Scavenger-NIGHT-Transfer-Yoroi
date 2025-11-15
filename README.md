Truy cập https://cdm-cdm.github.io/Scavenger-NIGHT-Transfer-Yoroi/

Bước 1: Nhập địa chỉ Donor và Recipient.

Bước 2: Nhấn nút “Ký và tạo chữ ký số Signature” để Yoroi mở ví và ký message.

Bước 3: Hệ thống tạo lệnh curl (hoặc JSON output), copy vào CMD và chạy, sẽ hiện kết quả dạng:

{
"status": "success",
"message": "Successfully assigned accumulated Scavenged NIGHT from addr1q... to addr1q...",
"solutions_consolidated": 2
}

Ý nghĩa: toàn bộ Night từ Donor (quá khứ và tương lai) được chuyển sang Recipient.

Các lỗi phổ biến:

409 Xung đột: đã gửi Night từ địa chỉ này rồi → không còn gì để làm.

400 Yêu cầu xấu: chữ ký không hợp lệ → kiểm tra ký đúng hay chưa.

404 Không tìm thấy: địa chỉ chưa đăng ký → dùng địa chỉ từng là thành phần của Scavenger.
