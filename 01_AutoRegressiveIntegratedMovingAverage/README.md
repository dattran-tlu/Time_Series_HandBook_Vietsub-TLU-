# Chapter 1: Trung bình trượt tích hợp tự hồi quy - AutoRegressive Integrated Moving Average (ARIMA)

Trong notebook này, chúng ta sẽ giới thiệu phương pháp tiếp cận đầu tiên đối với dự báo chuỗi thời gian, đó là **ARIMA** or **Tự hồi quy Trung bình trượt tích hợp - AutoRegressive Integrated Moving Average**.  

ARIMA, hay AutoRegressive Integrated Moving Average, là một tập hợp các mô hình dùng để giải thích một chuỗi thời gian bằng cách sử dụng chính các giá trị trong quá khứ của nó thông qua các độ trễ (**A**uto**R**egressive – Tự hồi quy) và các sai số trễ (**M**oving **A**verage – Trung bình trượt), đồng thời xét đến tính dừng được hiệu chỉnh bằng phép sai phân (đối lập với Integration – Tích phân).

Notebook này sẽ thảo luận:

1. Định nghĩa và Công thức của các mô hình ARIMA

2. Các tham số của mô hình (p, d, và q) và các trường hợp đặc biệt của mô hình ARIMA

3. Các thống kê mô hình và cách giải thích

4. Triển khai và dự báo bằng ARIMA

#### Các bộ dữ liệu được sử dụng:
- *Synthetic Data* (Filename: [`../data/wwwusage.csv`](https://raw.githubusercontent.com/selva86/datasets/master/wwwusage.csv)) 

- *Climate Data* (Filename: `../data/jena_climate_2009_2016.csv"`)