
# Kế hoạch thực hiện việc nghiên cứu 

## Giới thiệu:
 - Dự án này được thực hiện nghiên cứu ứng dụng AI vào trong cảnh báo và dự đoán giá chứng khoán
 - Dự án được chia làm ba phần chính
 
        - Phân tích kỹ thuật: Thông qua các biểu đồ trong chứng khoán
        - Phân tích cơ bản: Phân tích qua những bài báo có mức độ ảnh hưởng đến giá chứng khoán
        - Phân tích báo cáo tài chính: Thông qua báo cáo tài chính để đánh giá
        
 - Dưới đây là mô tả bằng tiếng Việt về phương pháp thực hiện từng phần trong dự án

## Phần 1 Phân tích kỹ thuật:

### 1. Phương pháp:

#### 1.1. XỬ LÝ THU THẬP DỮ LIỆU

- Tải toàn bộ dữ liệu của thị trường chứng khoán chưa được xử lý dưới dạng file csv về máy
- Trong file dữ liệu tải về bao gồm: Ngày/tháng/năm, giá mở cửa, giá cao nhất, giá đóng cửa và số lượng giao dịch
- File dữ liệu ở đây dưới dạng dữ liệu thô (Raw data) chưa được qua xử lý

#### 1.2. THỬ NGHIỆM VỚI MỘT MÃ CHỨNG KHOÁN

- Chuyển từ dạng dữ liệu thô của mã chứng khoán được chọn sang các sơ đồ
- Thực hiện với chuỗi sự thay đổi của 13 ngày liên tiếp
- Tạo Label cho các chuỗi sự thay đổi của 13 ngày liên tiếp
- Ghi kết quả của biểu đồ dưới dạng file dữ liệu đã được xử lý

#### 1.3. THỬ NGHIỆM VỚI CÁC MÔ HÌNH

- Thực hiện huấn luyện các sơ đồ với các mô hình sau
    - LSTM (Long Short-Term Memory)
    - RNN (Recurrent neural network)
    - GRU (Gated Recurrent Units)
    - Decision Tree
    - CNN (Convolutional neural network)
    - NN (Neural network)
- Sau khi thử nghiệm với từng mô hình với từng loại sơ đồ 

#### 1.4. TIẾN HÀNH PHÂN TÍCH VÀ ENSEMBLE

- Phân tích nên Ensemble các sơ đồ khối trong chứng khoán lại với nhau
- Phần tích nên sử dụng phương pháp Ensemble nào

## Phần 2: Phân tích cơ bản


```python

```


```python

```


```python

```


```python

```
