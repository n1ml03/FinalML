# Tài liệu Hướng dẫn Thực nghiệm với Fashion-MNIST

## 1. Mô tả tổng quan
Tài liệu này cung cấp thông tin chi tiết về cách tổ chức thư mục dự án, cách thực hiện thực nghiệm trên bộ dữ liệu Fashion-MNIST, cũng như thông tin về các tài liệu liên quan như mã nguồn, slide thuyết trình, và báo cáo học thuật.

## 2. Tổ chức thư mục
Cấu trúc thư mục dự án như sau:
```
FinalML/
├── fashion-mnist/              # Thư mục chứa dữ liệu tải về
│   └── ...                     # Các file dữ liệu .gz của Fashion-MNIST
├── ML.ipynb                    # File Notebook chính thực hiện thực nghiệm
├── requirements.txt
```

## 3. Hướng dẫn thực hiện

### Bước 1: Tải dữ liệu
Tải tập dữ liệu Fashion-MNIST từ kho chính thức:  
📦 Link dataset: [Github](https://github.com/zalandoresearch/fashion-mnist)

### Bước 2: Cài đặt môi trường
Cài đặt các thư viện cần thiết bằng pip hoặc conda:
```
pip install -r requirements.txt
```

### Bước 3: Thực hiện thực nghiệm
Chạy trực tiếp file notebook:
```
jupyter notebook FinalCode_ML.ipynb
```

Trong notebook `FinalCode_ML.ipynb`, bao gồm các bước:
- Tiền xử lý dữ liệu
- Xây dựng mô hình phân loại (CNN, SVM, Naïve Bayes,...)
- Huấn luyện và đánh giá mô hình
- Vẽ biểu đồ và so sánh kết quả

## 4. Slide trình bày
📊 Link: [Canva](https://www.canva.com/design/DAGkn2MXADA/Oj1jhbngbYQw9U8VZY4aSg/view?utlId=he657e6a605)
