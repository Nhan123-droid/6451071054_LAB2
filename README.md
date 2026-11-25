# 6451071054 - Thực hành Buổi 2 (LAB 2): Khai thác dữ liệu

Repository lưu trữ các bài thực hành **Buổi 2 (LAB 2)** môn **Khai thác dữ liệu** sử dụng các thuật toán phân lớp (Decision Tree: ID3 / CART, Gaussian Naive Bayes) bằng Python.

## Thông tin sinh viên
- **Họ và tên:** Trần Công Nhân
- **MSSV:** `6451071054`
- **GitHub:** [Nhan123-droid](https://github.com/Nhan123-droid)

## Cấu trúc thư mục

| File | Nội dung chính | Bộ dữ liệu | Mô hình sử dụng |
| :--- | :--- | :--- | :--- |
| [6451071054_LAB2_Bai2.ipynb](./6451071054_LAB2_Bai2.ipynb) | Phân lớp thu nhập và đánh giá bằng Accuracy, Confusion Matrix | `adult.data.csv`, `adult.test.csv` | Decision Tree (ID3, CART), Gaussian Naive Bayes |
| [6451071054_LAB2_Bai2(32).ipynb](./6451071054_LAB2_Bai2(32).ipynb) | So sánh mô hình với các độ đo Precision, Recall, F1-score | `load_breast_cancer` (`sklearn`) | Decision Tree (ID3, CART), Gaussian Naive Bayes |
| [6451071054_LAB2_Bai4.ipynb](./6451071054_LAB2_Bai4.ipynb) | Tiền xử lý dữ liệu và phân lớp chất lượng rượu vang đỏ | `winequality-red.csv` | Decision Tree (ID3), Gaussian Naive Bayes |
| [6451071054_LAB2_Bai5.ipynb](./6451071054_LAB2_Bai5.ipynb) | Phân lớp khả năng sống sót trên tàu Titanic | `titanic` (`seaborn`) | Decision Tree, Gaussian Naive Bayes |
| [6451071054_LAB2_Bai6.ipynb](./6451071054_LAB2_Bai6.ipynb) | Phân lớp và trực quan hóa cây quyết định | `load_breast_cancer` (`sklearn`) | Decision Tree, Gaussian Naive Bayes |
| [6451071054_LAB2_Bai7.ipynb](./6451071054_LAB2_Bai7.ipynb) | Nhận diện chữ số viết tay và dự đoán ảnh thực tế | `load_digits` (`sklearn`) | Decision Tree (ID3) |

## Công nghệ & Thư viện sử dụng
- Python 3
- `numpy`, `pandas`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `Pillow` (`PIL`)

## Hướng dẫn chạy
1. Clone repository về máy:
   ```bash
   git clone https://github.com/Nhan123-droid/6451071054_LAB2.git
   cd 6451071054_LAB2
   ```
2. Cài đặt các thư viện cần thiết (nếu chạy local):
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn pillow jupyter
   ```
3. Mở các file `.ipynb` bằng **Jupyter Notebook**, **VS Code**, hoặc tải lên **Google Colab** để chạy.
   > Lưu ý: Với các bài sử dụng file `.csv` ngoài (`adult.data.csv`, `adult.test.csv`, `winequality-red.csv`), cần đặt đúng file dữ liệu cùng thư mục khi chạy.
