# BÀI TẬP MÔN: An toàn và bảo mật thông tin
# bài tập 1
# TÌM HIỂU CÁC PHƯƠNG PHÁP MÃ HOÁ CỔ ĐIỂN
Caesar
Affine
Hoán vị
Vigenère
Playfair
# Với mỗi phương pháp, hãy tìm hiểu:
Tên gọi
Thuật toán mã hoá, thuật toán giải mã
Không gian khóa
Cách phá mã (mà không cần khoá)
Cài đặt thuật toán mã hoá và giải mã bằng code C++ và bằng html+css+javascript
# CAESAR CIPHER ( MÃ CAESAR)
# Tên gọi
Caesar cipher (mã của Julius Caesar) — dịch ký tự theo một dịch chuyển cố định.
# Thuật toán mã hoá / giải mã
Key: k (số nguyên, 0..25)
Mã hoá: C = (P + k) mod 26
Giải mã: P = (C − k mod 26) (P, C = chỉ số 0..25 của chữ A..Z)
# Không gian khóa
26 (thực tế 25 khác nhau nếu xem k=0 là khóa "không dịch").

# Cách phá (không cần khóa)
Brute force: thử tất cả 26 dịch chuyển. Nếu văn bản dài: tấn công tần suất (frequency analysis) — so sánh tần suất chữ trong bản mã với phân bố tiếng Anh.

