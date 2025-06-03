 # Sentiment-Analysis-CNN-LSTM
 Dự án này áp dụng mô hình học sâu kết hợp giữa CNN (mạng nơ-ron tích chập) và LSTM (mạng bộ nhớ ngắn dài hạn) để phân tích cảm xúc trong văn bản bình luận. Mô hình được triển khai bằng Python trong môi trường Jupyter Notebook, sử dụng thư viện TensorFlow/Keras, nhằm phân loại cảm xúc thành tích cực, tiêu cực, hoặc trung tính.

## Tính năng chính
- Tiền xử lý văn bản: tokenization, padding, mã hóa nhãn
- Biểu diễn từ bằng lớp Embedding
- CNN để trích xuất đặc trưng cục bộ
- LSTM để ghi nhớ ngữ cảnh chuỗi
- Huấn luyện và đánh giá trên tập dữ liệu nhãn cảm xúc
- Biểu đồ trực quan hóa độ chính xác và sai số huấn luyện

# Sơ đồ mô phỏng quá trình
![image](https://github.com/user-attachments/assets/afc2feaf-ba16-4a6f-b7f9-84fc431f8c8c)

# Chạy dự án
- git clone https://github.com/TraNguyen1215/Sentiment-Analysis-CNN-LSTM.git
- cd Sentiment-Analysis-CNN-LSTM
- pip install -r requirements.txt
- jupyter notebook
- chạy từng bước trong file setiment_analyst.ipynb


# Sentiment-Analysis-CNN-LSTM - Eng

This project applies deep learning techniques—specifically a hybrid CNN + LSTM architecture—for sentiment analysis of textual user comments. Implemented in Python using Jupyter Notebook and TensorFlow/Keras, the model classifies comments into positive, negative, or neutral sentiments.

## Features
- Text preprocessing: tokenization, padding, label encoding

- Word embedding (using Embedding layer)

- CNN for extracting local features

- LSTM for capturing sequence dependencies

- Trained and evaluated on labeled comment data

- Visualizations of training accuracy and loss

# Run
- git clone https://github.com/TraNguyen1215/Sentiment-Analysis-CNN-LSTM.git
- cd Sentiment-Analysis-CNN-LSTM
- pip install -r requirements.txt
- jupyter notebook
- Run the notebook setiment_analyst.ipynb step by step
