💳 Enhancing Default Prediction in P2P Lending with Deep Model Fusion
Nghiên cứu này giải quyết bài toán dự báo vỡ nợ trong nền tảng cho vay ngang hàng (P2P Lending) bằng cách khai thác cấu trúc tuần tự trong dữ liệu giao dịch của người vay.

🎯 Mục tiêu
- Tích hợp dữ liệu giao dịch tuần tự (sequential) và thuộc tính tài chính tĩnh (static) để tăng độ chính xác dự báo.
- Đánh giá các chiến lược kết hợp mô hình (Deep Model Fusion) khác nhau.
- Tăng cường tính minh bạch của mô hình thông qua cơ chế Attention.

🏗 Kiến trúc mô hình
- Nghiên cứu đề xuất và so sánh nhiều kiến trúc Fusion:
- LSTM-Attention: Sử dụng mạng LSTM kết hợp lớp Attention để trọng số hóa các bước thời gian quan trọng.


Weighted Transformer-LSTM-MLP: Một mô hình phức hợp kết hợp khả năng học phụ thuộc xa của Transformer, đặc trưng tuần tự của LSTM và thuộc tính tĩnh từ MLP.


Adaptive/Concatenated/Weighted LSTM-MLP: Các phương thức kết hợp đầu ra từ hai nhánh học riêng biệt cho dữ liệu tuần tự và tĩnh.

📊 Kết quả chính

Độ chính xác: Các mô hình Fusion vượt trội đáng kể so với phương pháp truyền thống.


Mô hình tốt nhất: LSTM-Attention đạt Accuracy 0.8 và Precision 0.81. Weighted Transformer-LSTM-MLP đạt Recall cao nhất (0.90).


Tính giải thích: Bản đồ nhiệt Attention giúp xác định các biến như "Debt-to-Income" và "Interest" có ảnh hưởng lớn nhất tại các giai đoạn giao dịch sớm.
