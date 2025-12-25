# Chương 3: Các phương pháp tự hồi quy vectơ (Vector Autoregressive Methods)

Trước đó, chúng ta đã giới thiệu các phương pháp cổ điển trong dự báo chuỗi thời gian đơn biến như mô hình Tự hồi quy – Trung bình trượt (Autoregressive-Moving-Average (ARIMA)) và mô hình hồi quy tuyến tính đơn giản. Chúng ta đã học rằng tính dừng là điều kiện cần thiết khi sử dụng ARIMA, trong khi điều kiện này không bắt buộc khi sử dụng mô hình hồi quy tuyến tính.

Trong notebook này, chúng ta mở rộng bài toán dự báo sang một khuôn khổ tổng quát hơn, nơi chúng ta làm việc với
**chuỗi thời gian đa biến (multivariate time series)**--tức là các chuỗi thời gian có nhiều hơn một biến phụ thuộc theo thời gian. Cụ thể hơn, chúng ta giới thiệu các mô hình **tự hồi quy vectơ (vector autoregressive (VAR))** và trình bày cách sử dụng chúng để dự báo chuỗi thời gian đa biến.


[Notebook](03_VectorAutoregressiveMethods.ipynb) được phác thảo như sau:
* Mô hình chuỗi thời gian đa biến
    * Động cơ (Motivation)
    * Chuỗi thời gian đơn biến so với đa biến (Univariate VS Multivariate Time Series)
    * Ví dụ
    * Cơ sở lý thuyết
* Các mô hình Tự hồi quy vectơ (VAR)
    * Mô hình VAR(1)
    * Mô hình VAR(*p*)
    * Lựa chọn bậc *p*
* Xây dựng mô hình VAR  
* Xây dựng mô hình
    * Hàm phản ứng xung (Impulse Response Function)
    * Phân rã phương sai sai số dự báo (Forecast Error Variance Decomposition)
* Kết luận chính
* Tài liệu tham khảo