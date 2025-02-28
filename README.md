# 🚀 Dự Án Cuối Kỳ - Thực Tập Cơ Sở

## 📝 Giới Thiệu

Dự án này được phát triển như một phần của bài tập cuối kỳ cho môn **Thực Tập Cơ Sở**. 

Mục tiêu chính của dự án là xây dựng một hệ thống **Cân Điện Tử** sử dụng vi điều khiển Arduino và cảm biến trọng lượng.

---

## 📂 Cấu Trúc Dự Án

```
📦 detaicuoikyTTCS
┣ 📜 code.txt                 # Mã nguồn ban đầu
┣ 📜 code(da chinh sua).txt   # Mã nguồn đã chỉnh sửa và hoàn thiện
┣ 📜 liquidcrystal_i2c.c      # Thư viện LCD I2C (C source)
┣ 📜 liquidcrystal_i2c.h      # Header file cho thư viện LCD I2C
┣ 📜 README.md                # Tài liệu hướng dẫn
```

---

## 🛠 Yêu Cầu Hệ Thống

### Phần Cứng
- Arduino Uno hoặc tương đương
- Cảm biến lực Load Cell + HX711
- Module LCD 16x2 với giao tiếp I2C
- Dây nối (Jumper)

### Phần Mềm
- Arduino IDE (phiên bản mới nhất)
- Thư viện **LiquidCrystal_I2C**
- Thư viện **HX711**

---

## 🔧 Cài Đặt

1. **Clone repository**:

   ```bash
   git clone https://github.com/N21DCVT030/detaicuoikyTTCS.git
   cd detaicuoikyTTCS
   ```

2. **Cài đặt thư viện trong Arduino IDE**:
   - Mở Arduino IDE
   - Vào **Sketch** > **Include Library** > **Manage Libraries...**
   - Tìm kiếm **LiquidCrystal_I2C** và **HX711**, sau đó cài đặt

3. **Nạp code lên Arduino**:
   - Mở file `code(da chinh sua).txt` trong Arduino IDE
   - Kết nối Arduino với máy tính
   - Chọn đúng board và cổng COM
   - Nhấn **Upload** để nạp chương trình

---

## 💡 Hướng Dẫn Sử Dụng

- Kết nối phần cứng theo sơ đồ sau:  
  _(Cập nhật sơ đồ kết nối tại đây)_
- Sau khi nạp code, hệ thống sẽ hiển thị trọng lượng đo được lên LCD.

---

## ✨ Tính Năng

- ✅ Đo trọng lượng bằng cảm biến Load Cell + HX711
- ✅ Hiển thị kết quả lên màn hình LCD
- ✅ Hiệu chỉnh giá trị cân để có độ chính xác cao

---

💡 *Hy vọng tài liệu này giúp bạn dễ dàng sử dụng và phát triển dự án hơn!* 🚀

