<div align="center">

# THỰC HÀNH THIẾT KẾ VI MẠCH SỐ VỚI HDL

<img src="https://img.shields.io/badge/Language-Verilog-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Software-Quartus%20II-lightgrey?style=for-the-badge">
<img src="https://img.shields.io/badge/Board-DE2-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/FPGA-Altera-success?style=for-the-badge">

Repository tổng hợp các bài thực hành môn  
**Thiết kế vi mạch số với HDL** sử dụng **Verilog HDL**, Quartus II và kit FPGA DE2.

</div>

---

# Giới thiệu

Project bao gồm:

- Code Verilog HDL
- File bài tập thực hành
- Hướng dẫn cài đặt Quartus II
- Hướng dẫn USB Blaster
- Hướng dẫn nạp code FPGA
- File pin assignment cho board DE2
- Các project mô phỏng và kiểm thử mạch số

Nội dung phù hợp cho:

- Sinh viên Điện tử - Viễn thông
- Sinh viên Kỹ thuật máy tính
- Người mới học FPGA / Verilog HDL
- Thực hành thiết kế mạch số cơ bản

---

# Nội dung repository

## Tài liệu lý thuyết & bài tập

| File | Nội dung |
|---|---|
| `Bai 1_LT cong tac,nut nhan,led_sv.pdf` | Công tắc, nút nhấn, LED |
| `Bai 2_Mach to hop_sv.pdf` | Mạch tổ hợp |
| `Bai 3_Mach giai ma led 7SEG_sv1.pdf` | Giải mã LED 7 đoạn |
| `Bai 4 - Mach Dem_sv.pdf` | Mạch đếm |
| `Bai 5 - Clock va bo dinh thoi_sv.pdf` | Clock & Timer |
| `bai 6_mach cong_nhan nhi phan_sv.pdf` | Bộ cộng nhị phân |
| `Bai 7-may trang thai (FSM)_sv.pdf` | Máy trạng thái FSM |

---

## Source code & project

| File ZIP | Nội dung |
|---|---|
| `baitapled.zip` | Bài tập LED |
| `baitapmachdem.zip` | Bài tập mạch đếm |
| `baitapclock.zip` | Bài tập clock |
| `baitapmachnhan.zip` | Bộ cộng / nhân nhị phân |
| `baitapmachsosanh.zip` | Mạch so sánh |
| `baitapfsm.zip` | FSM |
| `baitappcd.zip` | Project thực hành |
| `baitaptuan11.zip` | Bài tập tuần 11 |
| `cuoiky.zip` | Bài tập cuối kỳ |

---

## Công cụ hỗ trợ

| File | Mô tả |
|---|---|
| `DE2_pin_assignments.csv` | Pin assignment cho board DE2 |
| `HUONG DAN QUATUS 13.wmv` | Hướng dẫn Quartus II |
| `Huong dan cai dat USB Blaster_win11.wmv` | Cài driver USB Blaster |
| `duong dan cai usb blaster cho win 10.wmv` | USB Blaster Win10 |
| `huong dan nap code verilog.wmv` | Nạp code FPGA |
| `link quatus13.docx` | Link tải Quartus |

---

# Công nghệ sử dụng

```text
- Verilog HDL
- Intel Quartus II 13.0
- FPGA DE2 Board
- ModelSim
```

---

# Cấu trúc thư mục

```bash
📦 HDL-Digital-Design
 ┣ 📂 Source_Code
 ┣ 📂 PDF_Documents
 ┣ 📂 Video_Tutorials
 ┣ 📂 FPGA_Projects
 ┣ 📜 README.md
 ┣ 📜 DE2_pin_assignments.csv
 ┗ 📜 test_board.v
```

---

# Hướng dẫn sử dụng

## 1. Clone repository

```bash
git clone https://github.com/your-username/HDL-Digital-Design.git
```

---

## 2. Mở project Quartus

- Giải nén file `.zip`
- Mở file `.qpf`
- Compile project
- Gán pin theo `DE2_pin_assignments.csv`
- Nạp xuống board FPGA DE2

---

## 3. Mô phỏng

Có thể sử dụng:

- ModelSim
- Quartus Waveform
- RTL Viewer

---

# Kiến thức đạt được

- Thiết kế mạch số bằng Verilog HDL
- Thiết kế mạch tổ hợp & tuần tự
- FSM (Finite State Machine)
- Bộ đếm & chia tần
- Hiển thị LED 7 đoạn
- Clock & Timer
- Kiểm thử và mô phỏng FPGA

---


# Thông tin sinh viên

```text
Họ và tên : Nguyễn Ngọc Hùng
Ngành      : Điện tử - Viễn thông
Môn học    : Thực hành thiết kế vi mạch số với HDL
```

---

# License

Repository phục vụ cho mục đích học tập và nghiên cứu.

---

<div align="center">

### Nếu repository hữu ích hãy cho repo một ⭐

</div>
