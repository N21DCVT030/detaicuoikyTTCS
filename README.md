# 🚀 Dự Án Cuối Kỳ - Thực Tập Cơ Sở

## 📝 Giới Thiệu

Dự án này được phát triển như một phần của bài tập cuối kỳ cho môn **Thực Tập Cơ Sở**. 

Mục tiêu chính của dự án là xây dựng một hệ thống **Cân Điện Tử** sử dụng vi điều khiển STM32F401RE và cảm biến trọng lượng.

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
- Vi điều khiển STM32F401RE
- Cảm biến lực Load Cell + HX711
- Module LCD 16x2 với giao tiếp I2C
- Dây nối (Jumper)

### Phần Mềm
- STM32 Cubel (phiên bản mới nhất)
- Thư viện **LiquidCrystal_I2C**
- Thư viện **HX711**

---

## ✨ Tính Năng

- ✅ Đo trọng lượng bằng cảm biến Load Cell + HX711
- ✅ Hiển thị kết quả lên màn hình LCD
- ✅ Hiệu chỉnh giá trị cân để có độ chính xác cao

---

💡 *Hy vọng tài liệu này giúp bạn dễ dàng sử dụng và phát triển dự án hơn!* 🚀

