# 🚢 Titanic Survival Prediction

Dự án **Titanic Survival Prediction** nhằm dự đoán khả năng sống sót của hành khách trên con tàu Titanic huyền thoại, dựa trên các đặc điểm như tuổi, giới tính, hạng vé, giá vé, cảng lên tàu, v.v.

---

## 🧩 Mục tiêu
- Thực hành quy trình **Machine Learning cơ bản** trên bộ dữ liệu thực tế.
- Thử nghiệm nhiều **mô hình học máy khác nhau** để đánh giá hiệu suất:
  - 🌳 **Decision Tree Classifier**
  - 🌲 **Random Forest Classifier**
  - (Sẽ bổ sung thêm Logistic Regression, KNN, SVM trong các phiên bản sau)

---

## 📈 Đánh giá mô hình

Các mô hình được đánh giá dựa trên các chỉ số sau:

- 🎯 **Accuracy (Độ chính xác):**  
  Tỷ lệ dự đoán đúng trên tổng số mẫu trong tập kiểm tra (test set).

- 🧮 **Confusion Matrix (Ma trận nhầm lẫn):**  
  Cho biết số lượng mẫu được dự đoán đúng/sai ở từng lớp:
  - **TP (True Positive):** Dự đoán đúng người sống sót.  
  - **TN (True Negative):** Dự đoán đúng người không sống sót.  
  - **FP (False Positive):** Dự đoán sai là sống sót.  
  - **FN (False Negative):** Dự đoán sai là không sống sót.

- 📊 **Classification Report:**  
  Gồm các chỉ số chi tiết:
  - **Precision:** Độ chính xác trong dự đoán một lớp cụ thể.  
  - **Recall:** Khả năng tìm đúng các mẫu thực sự thuộc lớp đó.  
  - **F1-score:** Trung bình điều hòa giữa Precision và Recall, cho biết độ cân bằng giữa hai chỉ số này.
