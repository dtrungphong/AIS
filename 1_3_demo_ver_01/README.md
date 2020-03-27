
# VER_01

## Mô tả

- Thực hiện trên ba loại sơ đồ khối
    - Momentum
    - Money Flow Index
    - RSI
- Sử dụng mô hình LSTM để thực hiện
- Thực hiện trên 1 mã chứng khoán: REE

## QUÁ TRÌNH

### Xử lý dữ liệu thô

- Chuyển từ dạng dữ liệu thô của mã chứng khoán được chọn sang các sơ đồ được chọn
- Thực hiện với chuỗi sự thay đổi của 13 ngày liên tiếp
- Tạo Label cho các chuỗi sự thay đổi của 13 ngày liên tiếp

### Huấn luyện mô hình

- Xử dụng dữ liệu đã qua xử lý và gán nhãn qua các biểu đồ được chọn
- Thực hiện việc huấn luyện các biểu đồ với mô hình LSTM
- Đánh giá kết quả

### Đánh giá kết quả


```python

```
