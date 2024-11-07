# Machine-Learning
Tìm kiếm mô hình Machine Learning phù hợp, thiết lập bộ tham số tối ưu, lựa chọn các đặc trưng (features) có giá trị dự báo cao,
---------
## Giới thiệu Project
1. Giới thiệu Dataset và Vấn đề Cần Giải Quyết:

Dataset trên là dữ liệu về khách hàng của một công ty viễn thông, bao gồm các thông tin cá nhân và các dịch vụ mà khách hàng đang sử dụng, cũng như tình trạng Churn (khách hàng rời bỏ dịch vụ). Mục tiêu của dự án là xây dựng một mô hình Machine Learning dự báo khả năng một khách hàng sẽ Churn hay không, dựa trên các đặc điểm cá nhân và mức độ sử dụng dịch vụ của khách hàng. Việc này giúp công ty có thể dự đoán trước và áp dụng các chiến lược giảm thiểu tỷ lệ khách hàng rời bỏ, qua đó tăng doanh thu và hiệu quả dịch vụ.

2. Giải thích Dataset:
- CustomerID: Mã định danh của từng khách hàng.
- Gender: Giới tính của khách hàng (Male/Female).
- SeniorCitizen: Cho biết khách hàng có phải là người cao tuổi (SeniorCitizen = 1) hay không (SeniorCitizen = 0).
- Partner: Tình trạng hôn nhân của khách hàng (Yes/No).
- Dependents: Khách hàng có người phụ thuộc (Yes) hay không (No).
- Tenure: Số tháng khách hàng đã gắn bó với công ty.
- PhoneService: Khách hàng có sử dụng dịch vụ điện thoại hay không (Yes/No).
- MultipleLines: Khách hàng có nhiều đường dây điện thoại không (Yes/No/No phone service).
- InternetService: Loại dịch vụ Internet mà khách hàng sử dụng (DSL, Fiber optic, hoặc No).
- OnlineSecurity, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Các dịch vụ bổ sung mà khách hàng có sử dụng hay không (Yes/No).
- Contract: Loại hợp đồng của khách hàng, như hợp đồng tháng (Month-to-month), hợp đồng một năm (One year), hoặc hợp đồng hai năm (Two year).
- PaperlessBilling: Hóa đơn điện tử (Yes) hoặc hóa đơn giấy (No).
- PaymentMethod: Phương thức thanh toán, như chuyển khoản ngân hàng tự động, thanh toán qua séc, hoặc thanh toán qua thẻ tín dụng.
- MonthlyCharges: Phí dịch vụ hàng tháng.
- TotalCharges: Tổng chi phí từ trước tới nay mà khách hàng đã trả.
- Churn: Mục tiêu cần dự đoán, xác định khách hàng có rời bỏ dịch vụ (Yes) hay không (No).

3. Mục Tiêu Dự Án:

Mục tiêu của dự án là tìm kiếm mô hình Machine Learning phù hợp để dự báo liệu rằng khách hàng có rời bỏ dịch vụ hay không? Thiết lập bộ tham số tối ưu, lựa chọn các đặc trưng (features) có giá trị dự báo cao, và xây dựng pipeline tự động nhằm giúp công ty có thể dự báo hiệu quả khả năng khách hàng sẽ rời bỏ dịch vụ (churn) dựa trên dữ liệu hiện có. Pipeline này sẽ cho phép công ty dễ dàng áp dụng mô hình vào hệ thống Business Intelligence, hỗ trợ các chiến lược giữ chân khách hàng kịp thời và chính xác.

4. Các bước thực hiện:

- Khám Phá và Xử Lý Dữ Liệu
- Lựa Chọn Đặc Trưng (Feature Selection)
- Sử dụng K-Folk đánh giá độ ổn định mô hình
- Thiết Lập Pipeline Tự Động
- Tìm Kiếm Mô Hình và Bộ Tham Số Tối Ưu
