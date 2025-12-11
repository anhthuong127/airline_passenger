**Airline Passenger Satisfaction**

**📌 Giới thiệu dự án**

**Airline Passenger Satisfaction** là dự án phân tích dữ liệu nhằm tìm hiểu các yếu tố ảnh hưởng đến mức độ hài lòng của hành khách đối với một hãng hàng không. Thông qua việc làm sạch, phân tích và trực quan hóa dữ liệu, dự án hướng tới việc rút ra các insight có giá trị và đề xuất giải pháp hỗ trợ doanh nghiệp nâng cao trải nghiệm khách hàng.

**📂 Nguồn dữ liệu**
- **Data gốc**: Dữ liệu do Trường Đại học Khoa học Tự nhiên cung cấp
- **Mô tả**: Dataset chứa thông tin chi tiết về các chuyến bay và trải nghiệm của hành khách (loại khách hàng, hạng vé, thời gian trễ, mức độ hài lòng, …)
  
  <img width="1000" height="300" alt="image" src="https://github.com/user-attachments/assets/046d2717-85a3-48aa-8ed1-de6a6027cd68" />


**🎯 Mục tiêu phân tích**

- Xác định những **yếu tố ảnh hưởng mạnh nhất đến sự hài lòng của hành khách**
- Tìm ra các **mối tương quan** giữa đặc điểm chuyến bay, loại vé và mức độ hài lòng
- Đưa ra **giải pháp và gợi ý thực tiễn** giúp hãng hàng không cải thiện chất lượng dịch vụ
-> Trả lời các câu hỏi chính:
- Tìm hiểu những yếu tố nào dẫn đến sự hài lòng của khách hàng đối với một hãng hàng không?
- Các giải pháp và gợi ý nào có thể sẽ hiệu quả cho doanh nghiệp?
- Liệu có những yếu tố nào có mối tương quan chặt chẽ với hành khách hài lòng (hoặc không hài lòng)?

**🔎 Quy trình thực hiện**

**Bước 1: Làm sạch dữ liệu (Data Cleaning): – Python**

- Đọc dữ liệu gốc
- Check missing value, duplicate 
- Chuẩn hóa kiểu dữ liệu (ngày, tháng, số)
- Tạo thêm cột (nếu cần)

**Bước 2: Phân tích dữ liệu (EDA)**

- Customer Type × Satisfaction
 → Khách hàng trung thành có hài lòng hơn khách không trung thành không?
- Class × Total Delay
 → Hạng vé nào có thời gian trễ nhiều nhất?
 → Liệu chất lượng dịch vụ theo từng hạng vé có ảnh hưởng?
- Total Delay × Satisfaction
 → Tỷ lệ hài lòng / không hài lòng thay đổi như thế nào theo từng mức độ trễ chuyến?

**Bước 3: Trực quan hoá dữ liệu – Matplotlib và Seaborn**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/1b0bf47a-2502-41aa-b8d4-50e4e2bc247a" />

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/cc468b3f-7eb0-4a94-8690-8f4dd8394da1" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/0e1cefb1-3070-4362-9dc4-5c04e76f1b08" />
<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/d57afc12-8fed-4378-9cce-2926d1dc0868" />

**🛠️ Công cụ & Công nghệ sử dụng**

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook / VS Code

**📊 Insight chính**

- Khách hàng trung thành thường có trải nghiệm tốt hơn, hoặc họ có kỳ vọng phù hợp hơn với dịch vụ. Khách không trung thành thì ngược lại -> việc giữ chân và chăm sóc khách hàng trung thành là rất quan trọng để duy trì mức độ hài lòng cao.
- Khách hàng hạng vé Eco có thời gian trễ trung bình cao nhất (~30 phút), tiếp theo là Eco Plus và thấp nhất là Business -> hạng vé càng cao thì thời gian bị trễ chuyến càng thấp, có thể do ưu tiên trong khâu phục vụ, boarding, hoặc quy trình xử lý sự cố tốt hơn cho khách hàng cao cấp → **Hãng hàng không nên cải thiện dịch vụ cho khách hàng hạng Eco nhằm đảm bảo công bằng và nâng cao sự hài lòng toàn diện.**
- Tỷ lệ khách hàng hài lòng và không hài lòng theo từng khoảng thời gian trễ chuyến bay (mỗi 30 phút) → Biểu đồ giúp xác định rõ ngưỡng độ trễ bắt đầu ảnh hưởng nghiêm trọng đến sự hài lòng. Do đó, cần ưu tiên cải thiện thời gian bay đúng giờ, đặc biệt giữ trễ ở mức <60 phút để duy trì mức hài lòng ổn định.


# Expected Outcomes
- A clear understanding of what drives customer satisfaction in the airline industry.
- Actionable insights for improving service quality and operational efficiency.
- Visual dashboards and data summaries to communicate findings effectively.
- Authour: Thuong Tran
LinkedIn: (https://www.linkedin.com/in/trananhthuong)
Link Data: Airline_Passenger_Satisfaction.csv https://drive.google.com/drive/folders/1rG5I9F45vhcSMwhKeR0TuRWMJ-myku9U?usp=sharing
