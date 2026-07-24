# Hệ thống phát hiện xâm nhập cho mạng IoT

## Giới thiệu

Đây là repository lưu trữ toàn bộ tài liệu, cấu hình và kết quả của đề tài cuối kỳ môn **Bảo mật trong IoT**.

Đề tài tập trung xây dựng mô hình mạng IoT mô phỏng kết hợp với hệ thống phát hiện xâm nhập (Intrusion Detection System - IDS) nhằm giám sát lưu lượng mạng và phát hiện các hành vi bất thường trong môi trường thử nghiệm. Hệ thống được triển khai trên VMware Workstation với pfSense CE tích hợp Suricata IDS, Node-RED mô phỏng thiết bị IoT, Windows Client và Kali Linux phục vụ kiểm thử. 

---

## Mục tiêu

- Xây dựng mô hình IDS phù hợp với môi trường mạng IoT.
- Triển khai pfSense CE kết hợp Suricata IDS để giám sát lưu lượng mạng.
- Mô phỏng dịch vụ IoT bằng Node-RED.
- Thực hiện các kịch bản kiểm thử và đánh giá khả năng phát hiện của hệ thống thông qua cảnh báo và nhật ký sự kiện.

---

## Công nghệ sử dụng

- VMware Workstation
- pfSense CE
- Suricata IDS
- Node-RED
- Windows 10
- Kali Linux
- Nmap
- HTTP / JSON

---

## Cấu trúc repository

```
.
├── report/          # Báo cáo đề tài
├── slides/          # Slide thuyết trình
├── src/             # Thông tin về mã nguồn (README)
├── configs/         # File cấu hình hệ thống
├── data/            # Dữ liệu mẫu
├── results/         # Kết quả kiểm thử
└── references/      # Tài liệu tham khảo
```

---

## Mô hình triển khai

Hệ thống được triển khai trong môi trường VMware Workstation gồm các thành phần:

- pfSense CE (Firewall/Gateway)
- Suricata IDS
- Windows Client
- Node-RED
- Kali Linux

Suricata được cấu hình giám sát lưu lượng mạng nội bộ (LAN) nhằm phát hiện các hoạt động bất thường và sinh cảnh báo theo tập luật đã cấu hình.

---

## Nội dung repository

### report/

Báo cáo cuối kỳ định dạng DOCX và PDF.

### slides/

Slide sử dụng để bảo vệ đề tài.

### src/

Giải thích về mã nguồn của dự án.

### configs/

Các tệp cấu hình sử dụng trong quá trình triển khai như:

- flow.json
- pfSense configuration
- Suricata rules

### data/

Dữ liệu mẫu phục vụ mô phỏng và kiểm thử.

### results/

Bao gồm:

- Ảnh minh họa quá trình triển khai
- Nhật ký cảnh báo
- Kết quả kiểm thử

### references/

Danh sách tài liệu, tiêu chuẩn và nguồn GitHub được tham khảo trong đề tài.

---

## Kết quả đạt được

- Xây dựng thành công mô hình IDS cho mạng IoT.
- Triển khai Suricata trên pfSense.
- Mô phỏng thiết bị IoT bằng Node-RED.
- Tạo lưu lượng kiểm thử từ Kali Linux.
- Phát hiện thành công hoạt động quét cổng và sinh cảnh báo trên Suricata IDS.

---

## Tác giả

**Nguyễn Quốc Kiệt**

Trường Đại học Văn Hiến

Khoa Công nghệ Thông tin

Môn học: Bảo mật trong IoT

Giảng viên hướng dẫn: Hồ Nhựt Minh.

---

## Giấy phép

Repository được xây dựng phục vụ mục đích học tập, nghiên cứu và báo cáo học phần.