# Chương 5: Các phương pháp dự báo động lực (Simplex và SMap Projections)

Trong các phần trước, chúng ta đã xem xét những phương pháp khác nhau để đặc trưng hóa chuỗi thời gian và các phép toán thống kê khác có thể thực hiện nhằm phục vụ cho việc dự báo. Nhiều phương pháp trong số này liên quan đến việc xây dựng các mô hình phù hợp nhất với chuỗi thời gian, trích xuất các tham số tối ưu để mô tả dữ liệu với sai số nhỏ nhất có thể. Tuy nhiên, nhiều quá trình trong thế giới thực lại thể hiện các đặc tính phi tuyến, phức tạp và mang tính động, do đó đòi hỏi những phương pháp khác có khả năng xử lý các đặc điểm này.


Trong phần này, chúng ta sẽ giới thiệu và thảo luận các phương pháp sử dụng mô hình thực nghiệm thay vì các phương trình phức tạp, được tham số hóa và mang tính giả thuyết. Dựa trên dữ liệu chuỗi thời gian thô, chúng ta sẽ cố gắng tái tạo các cơ chế nền tảng có thể quá phức tạp, quá nhiễu hoặc quá động để có thể được nắm bắt bằng các phương trình. Phương pháp này đề xuất một cách tiếp cận thay thế, linh hoạt hơn trong việc làm việc và dự báo các hệ động lực.

## Notebook này sẽ thảo luận các nội dung sau:
- Giới thiệu về Mô hình động lực thực nghiệm (Empirical Dynamic Modelling – EDM)
- Trực quan hóa dự báo EDM với chuỗi thời gian hỗn loạn
- Hấp dẫn tử Lorenz (Lorenz Attractor)
- Định lý Takens / Tái cấu trúc không gian trạng thái (State-Space Reconstruction – SSR)
- Phép chiếu Simplex
- Xác định các giá trị embedding tối ưu (tinh chỉnh siêu tham số)
- Phân biệt tín hiệu nhiễu và tín hiệu hỗn loạn
- Phép chiếu S-Map (Sequentially Locally Weighted Global Linear Map)

Biên soạn bởi: Francis James Olegario Corpuz
