# Chương 7: Cross-Correlations, Fourier Transform, and Wavelet Transform

Để đạt được sự hiểu biết sâu hơn về nhân quả, chúng ta xem xét dự báo chuỗi thời gian dưới một góc nhìn khác.

Trong chương này, chúng ta sẽ tiếp cận theo một cách khác trong việc phân tích chuỗi thời gian, mang tính bổ trợ cho dự báo. Trước đó, các phương pháp giải thích như Nhân quả Granger, S-mapping và Cross-mapping tập trung vào miền thời gian – tức là giá trị của chuỗi thời gian khi được đo theo thời gian hoặc trong không gian pha của nó. Mặc dù cả hai đều hữu ích cho nhiều tác vụ, nhưng trong nhiều trường hợp, việc biến đổi các phép đo trong miền thời gian có thể giúp khai phá các khuôn mẫu khó nhận ra. Cụ thể, chúng ta muốn xem xét miền tần số để vừa phân tích động lực, vừa thực hiện các kỹ thuật tiền xử lý có thể được dùng để điều chỉnh các bộ dữ liệu trong thế giới thực.

Chúng ta sẽ phân tích động lực của các chuỗi thời gian không hẳn để tạo dự báo, mà để hiểu chúng theo khía cạnh tần số, nhằm bổ sung cho các phương pháp nhân quả và khả năng giải thích đã được trình bày trước đó.

Chúng ta giới thiệu ba kỹ thuật:

1. Cross-correlations (Tương quan chéo)

2. Fourier Transform (Biến đổi Fourier)

3. Wavelet Transform (Biến đổi Wavelet)

và kiểm thử việc sử dụng chúng trên bộ dữ liệu khí hậu Jena (2009–2016) cùng với một số bộ dữ liệu khác.


