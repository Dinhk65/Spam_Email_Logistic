# 📩 Spam Email Classification with Logistic Regression  
*Phân loại email spam bằng hồi quy Logistic*

This project implements a **Logistic Regression** model to classify emails as **spam** or **not spam**. It is a simple ML project built from scratch in Python, focusing on core concepts like **logistic regression**, **feature engineering**, and **model evaluation**.

Dự án này sử dụng mô hình **Hồi quy Logistic** để phân loại email thành **spam** hoặc **không spam**. Mục tiêu là hiểu bản chất của thuật toán, cách xử lý dữ liệu đầu vào và đánh giá mô hình một cách đơn giản, dễ tiếp cận cho người mới học.

---

🎓 **Author's Note | Lưu ý từ tác giả:**

> This project was built when I was just getting started with Machine Learning, so the focus is on:
> - Understanding how Logistic Regression works  
> - Learning how to process data and train a model that actually runs 😄  
> - Building a simple Streamlit web app to demonstrate the result  

> Đây là project mình thực hiện khi mới bắt đầu học Machine Learning, nên mình tập trung vào:
> - Hiểu cách hoạt động của Logistic Regression  
> - Biết cách xử lý dữ liệu và huấn luyện mô hình chạy được ra kết quả 😄  
> - Cuối cùng là build giao diện web đơn giản bằng Streamlit để demo

💡 If you're new to ML, this is a great beginner-friendly project to follow.  
💡 Nếu bạn mới học ML, đây là project nhập môn rất phù hợp để bắt đầu.

🚫 If you're expecting a Gmail-level spam detection system... sorry, wrong place 😅  
🚫 Nếu bạn kỳ vọng hệ thống phát hiện spam như Gmail thì… xin hẹn bạn ở project khác 😅

---

## 🔍 Demo

- ▶️ [Live Demo on YouTube](https://youtube.com/live/Pom_brpUgKA?feature=share)  
- 💻 [Run on Google Colab](https://colab.research.google.com/drive/12z4Df1MRih5qhGYvjpHAEadxVvY3MOdh?usp=sharing)  
- 🎬 [Video Tutorial (YouTube)](https://docs.google.com/spreadsheets/d/1WTtAzmejGyav2i4zHPyaIcB9sgYwx60j/edit?gid=1123843552#gid=1123843552)  

---

## ⚙️ Requirements

### Libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `streamlit` *(for the web app)*

---

## 📄 Dataset (Datasheet)

**Dataset**: SMS Spam Collection  
- Original source: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)  
- Description: 5,574 labeled SMS messages (spam or ham)

📘 **Datasheet (bản dữ liệu mẫu)**:

> This is a simplified datasheet I prepared to support this tutorial, tailored for learning purposes.  
> Đây là bản dữ liệu mẫu mình đã chuẩn bị, để hỗ trợ cho bài giảng và phù hợp với người mới học.

📥 Download here | Tải tại đây:  
👉 [Google Drive - spam.csv](https://drive.google.com/file/d/1iKNyb9VC15Rh0IuHaH3tddZK-zOmTZUL/view?usp=sharing)

🗂️ After downloading, place it inside the `data/` folder  
📂 Sau khi tải về, đặt vào thư mục `data/`

---

## 🧪 Features
- Clean and preprocess raw SMS data  
- Convert text into numerical features  
- Train Logistic Regression model using `scikit-learn`  
- Evaluate accuracy, precision, recall  
- Make predictions on custom input  
- Streamlit web app for user interaction

---

## 🏷 Tags
`logistic-regression`, `machine-learning`, `spam-classifier`, `python`, `streamlit`, `beginner-friendly`, `ga-ai`

---

Made with ❤️ by [Gà AI](https://www.youtube.com/@GaAI-k2)
