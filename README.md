# Performance_test_by_Jmeter
---
**BÁO CÁO ĐÁNH GIÁ HIỆU SUẤT TRANG WEB**

### 1. Giới thiệu
Báo cáo này đánh giá hiệu suất của trang web dựa trên kết quả kiểm thử tải bằng JMeter. Các thông số hiệu suất bao gồm thời gian phản hồi, thông lượng và tỷ lệ lỗi.

### 2. Kết quả hiệu suất
#### 2.1. Thời gian phản hồi
- **Thời gian phản hồi trung bình:** 1,113 ms
- **Thời gian phản hồi trung vị (Median):** 943 ms
- **90% requests có thời gian phản hồi dưới:** 1,857 ms
- **95% requests có thời gian phản hồi dưới:** 2,344 ms
- **99% requests có thời gian phản hồi dưới:** 3,675 ms
- **Thời gian phản hồi nhỏ nhất:** 350 ms
- **Thời gian phản hồi lớn nhất:** 11,837 ms

#### 2.2. Thông lượng và Tỷ lệ lỗi
- **Số lượng requests:** 6,903
- **Tỷ lệ lỗi:** 0.000% (không có lỗi)
- **Thông lượng (Throughput):** 22.41 requests/giây
- **Dữ liệu nhận vào (Received KB/sec):** 5,709.44 KB/s
- **Dữ liệu gửi (Sent KB/sec):** 2.54 KB/s

### 3. Phân tích và kết luận
- Hệ thống duy trì độ trả lời tốt đối với 90% requests có thời gian phản hồi dưới 1.8 giây.
- Các giá trị 95% và 99% cho thấy một số requests có thời gian phản hồi lâu hơn 2 giây, có thể gây trải nghiệm khách hàng không tốt.
- Throughput đạt 22.41 requests/giây, chứng tỏ hệ thống đang xử lý tốt.
- Tỷ lệ lỗi = 0% cho thấy không có requests bị thất bại.

**Đề xuất:**
- Cải thiện thời gian phản hồi cho 5% requests có thời gian chậm (trên 2 giây).
- Tăng cơ chế cache hoặc tối ưu truy vấn cơ sở dữ liệu.

Báo cáo kết thúc tại đây.

