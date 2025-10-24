#  Dự án: Đọc cảm biến ánh sáng (LDR) với ESP32 & Teleplot

## Giới thiệu
Trong dự án này, ESP32 được sử dụng để đọc giá trị ánh sáng tương đối từ cảm biến quang trở (LDR) thông qua chân ADC.
Giá trị thu được sẽ được gửi qua UART và hiển thị dưới dạng đồ thị thời gian thực trên Teleplot trong VS Code, giúp dễ dàng quan sát sự thay đổi cường độ ánh sáng theo thời gian.
![Biểu đồ Teleplot](image.png)
## Thành phần phần cứng
- **ESP32 DevKit V1**
- **LDR (CdS)**
- **Điện trở 10kΩ** (tạo mạch chia áp)
- **Nguồn 3.3V**
## Thành phần phần mềm
- **Arduino IDE (hoặc VS Code với extension PlatformIO) – để lập trình và nạp code cho ESP32**
- **Thư viện Teleplot (hoặc Serial Plotter trong VS Code) – để hiển thị dữ liệu ánh sáng dạng biểu đồ**
- **Trình điều khiển (driver) cho ESP32 – giúp máy tính nhận cổng COM của bo mạch**
- **Git & GitHub – dùng để lưu trữ và quản lý mã nguồn**
## Kết quả
- **Teleplot sẽ hiển thị đồ thị thay đổi cường độ ánh sáng theo thời gian.**
- **Khi bạn che LDR → giá trị giảm**
- **Khi chiếu sáng mạnh → giá trị tăng** 
