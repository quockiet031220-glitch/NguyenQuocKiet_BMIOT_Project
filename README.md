# Hệ thống phát hiện xâm nhập cho mạng IoT

## Giới thiệu

Đây là repository phục vụ cho đề tài tiểu luận:

**Hệ thống phát hiện xâm nhập cho mạng IoT**

Đề tài tập trung nghiên cứu việc thiết kế mô hình hệ thống phát hiện xâm nhập (Intrusion Detection System - IDS) cho môi trường Internet of Things (IoT). Hệ thống có nhiệm vụ giám sát lưu lượng mạng, phát hiện các hành vi bất thường và hỗ trợ cảnh báo sớm nhằm nâng cao khả năng bảo vệ hệ thống trước các nguy cơ mất an toàn thông tin.

Mô hình được triển khai trong môi trường mô phỏng sử dụng VMware và các công cụ mã nguồn mở phục vụ mục đích học tập, nghiên cứu và thực hành an toàn thông tin.

---

# Người thực hiện

- **Họ và tên:** Nguyễn Quốc Kiệt
- **MSSV:** 231A010689
- **Lớp:** 253INT441001
- **Giảng viên hướng dẫn:** Hồ Nhật Minh

---

# Mục tiêu

- Thiết kế mô hình IDS phù hợp với mạng IoT.
- Nghiên cứu và so sánh IDS dựa trên chữ ký (Signature-based IDS) và IDS dựa trên hành vi (Anomaly-based IDS).
- Xây dựng mô hình giám sát lưu lượng mạng IoT bằng Suricata IDS.
- Mô phỏng lưu lượng IoT bằng Node-RED phục vụ kiểm thử hệ thống.
- Đánh giá khả năng phát hiện thông qua log cảnh báo và kết quả thực nghiệm.

---

# Tài liệu tham khảo chính

### 1. OWASP IoT Security Testing Guide (ISTG)

https://github.com/OWASP/owasp-istg

### 2. OWASP IoT Security Verification Standard (ISVS)

https://github.com/OWASP/IoT-Security-Verification-Standard-ISVS

### 3. Node-RED

https://github.com/node-red/node-red

### 4. Netgate pfSense Documentation

https://docs.netgate.com/pfsense/

### 5. Suricata Documentation

https://docs.suricata.io/

### 6. VMware Documentation

https://docs.vmware.com/

---

# Cấu trúc Repository

```text
configs/
data/
images/
references/
report/
results/
slides/
src/
README.md
```

### Mô tả các thư mục

- **configs/**: Lưu các file cấu hình của pfSense, Suricata và các thành phần liên quan.
- **data/**: Lưu dữ liệu hoặc lưu lượng mô phỏng phục vụ kiểm thử.
- **images/**: Lưu sơ đồ kiến trúc, sơ đồ luồng dữ liệu và hình ảnh minh chứng.
- **references/**: Lưu tài liệu tham khảo sử dụng trong đề tài.
- **report/**: Lưu báo cáo Word hoặc PDF.
- **results/**: Lưu log cảnh báo, kết quả kiểm thử và hình ảnh thực nghiệm.
- **slides/**: Lưu slide thuyết trình.
- **src/**: Lưu mã nguồn hoặc script hỗ trợ (nếu có).

---

# Công nghệ sử dụng

- VMware Workstation
- pfSense CE
- Suricata IDS
- Node-RED
- Kali Linux
- Windows Client
- MQTT
- GitHub

---

# Cách triển khai

Quy trình thực hiện dự kiến:

1. Xây dựng môi trường mô phỏng trên VMware.
2. Cấu hình mạng IoT và Gateway.
3. Triển khai Suricata IDS trên pfSense.
4. Mô phỏng lưu lượng IoT bằng Node-RED.
5. Thực hiện các kịch bản kiểm thử.
6. Thu thập log và đánh giá kết quả phát hiện.

---

# Tiến độ thực hiện

## Đã hoàn thành

- Tạo repository GitHub.
- Xây dựng cấu trúc thư mục.
- Thu thập tài liệu tham khảo.
- Hoàn thành Chương 1.
- Hoàn thành bản nháp Chương 2 (đến mục 2.4).
- Thiết kế sơ đồ kiến trúc hệ thống.
- Thiết kế sơ đồ luồng dữ liệu.

## Đang thực hiện

- Hoàn thiện Chương 2.
- Xây dựng mô hình thực nghiệm.
- Triển khai và đánh giá hệ thống IDS.
- Hoàn thiện báo cáo và slide thuyết trình.

---

# Hình ảnh minh chứng

Thư mục **images/** sẽ được cập nhật trong quá trình thực hiện, bao gồm:

- Sơ đồ kiến trúc hệ thống.
- Sơ đồ luồng dữ liệu.
- Ảnh cấu hình pfSense.
- Ảnh cấu hình Suricata IDS.
- Ảnh mô phỏng Node-RED.
- Ảnh Alert Log và kết quả thực nghiệm.

---

# Kết quả dự kiến

- Mô hình mạng IoT mô phỏng hoàn chỉnh.
- Hệ thống IDS giám sát lưu lượng mạng.
- Bộ luật (Rule) phát hiện các hành vi bất thường.
- Alert Log và kết quả phát hiện.
- Bảng đánh giá khả năng phát hiện của hệ thống.
- Hướng dẫn triển khai và tái hiện mô hình.

---

# Giới hạn an toàn

Repository chỉ phục vụ mục đích học tập và nghiên cứu.

Toàn bộ mô hình được triển khai trong môi trường mô phỏng VMware với dữ liệu thử nghiệm. Không triển khai trên hệ thống thực tế và không sử dụng cho các hoạt động tấn công trái phép hoặc gây ảnh hưởng đến hệ thống của bên thứ ba.

---

# Giấy phép

Tài liệu trong repository được sử dụng cho mục đích học tập và nghiên cứu tại Trường Đại học Văn Hiến.
