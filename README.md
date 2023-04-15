# Thay đổi chính:

- thay đổi 1 số tên hàm, thêm hàm feature_extract để trích đặc trưng
- code có chỉnh phần toggle skip processing. (chỉnh biến isProcessed, True: skip process, False: process)
- có upload các file .csv để đỡ phải process lại

# Task:

- Trích thêm đặc trưng: hiện tại đang để nguyên 17 điểm , shape (1, 17, 2)
- Dự kiến có thể sẽ làm lại tập gác chân (nếu cần)

# Kết quả hiện tại:

- Dù trên tập validate kết quả vẫn hơi thấp, kết quả trên tập test vẫn khá cao (validate: ~80%, test: ~90%)