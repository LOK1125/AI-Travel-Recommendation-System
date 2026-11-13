# 🗺️ AI Travel Recommendation System
**Hệ thống gợi ý địa điểm du lịch thông minh dựa trên độ tương đồng ngữ nghĩa và phân tích đánh giá người dùng**

## 📌 Thông tin sinh viên thực hiện
* **Họ và tên:** Phạm Thành Lộc
* **MSSV:** 238023

## 🚀 Giới thiệu đề tài
Ứng dụng web hỗ trợ người dùng tìm kiếm địa điểm du lịch bằng ngôn ngữ tự nhiên (Semantic Search) thay vì chỉ khớp từ khóa truyền thống. Hệ thống tự động đề xuất các địa điểm tương đồng, phân tích mức độ uy tín dựa trên đánh giá của du khách và trực quan hóa vị trí trên bản đồ tương tác.

## 🛠️ Công nghệ & Thuật toán sử dụng
* **Ngôn ngữ lập trình:** Python
* **Xử lý ngôn ngữ tự nhiên (NLP):** `Sentence-Transformers` (`paraphrase-multilingual-MiniLM-L12-v2`) & `Cosine Similarity`
* **Phân tích cảm xúc (Sentiment Analysis):** Phân loại đánh giá tích cực/tiêu cực
* **Giao diện & Bản đồ:** `Streamlit`, `Folium`
