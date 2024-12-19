# **ESP32 DEMONIC**

## **Giới Thiệu**
Dự án này là một thiết bị phá sóng có khả năng can thiệp và làm gián đoạn các tín hiệu không dây trong băng tần 2.4GHz, bao gồm WiFi, BlueTooth. Thiết bị này được phát triển với mục đích nghiên cứu và giáo dục, giúp hiểu rõ hơn về cách hoạt động của các mạng không dây và bảo mật.

## **Cảnh Báo**
Việc sử dụng các thiết bị chứa phần mềm hay phần mềm DEMONIC để phá sóng các tín hiệu không dây là bất hợp pháp trong hầu hết các quốc gia. Mục đích của dự án này là để giáo dục và nghiên cứu. Người dùng phải đảm bảo tuân thủ các quy định pháp luật hiện hành và chỉ sử dụng thiết bị trong các môi trường thí nghiệm, được cấp phép.

## **Nguyên Lý Hoạt Động**
Thiết bị phá sóng hoạt động bằng cách phát ra tín hiệu gây nhiễu tại cùng tần số với tín hiệu mà nó muốn phá. Khi tín hiệu gây nhiễu đủ mạnh, nó sẽ lấn át tín hiệu gốc, gây khó khăn cho các thiết bị nhận diện và xử lý tín hiệu đó.

### **Các Bước Cơ Bản Của Phá Sóng:**
1. **Tạo Sóng Mang**: Bộ vi xử lý tạo ra sóng mang ở tần số mục tiêu (2.4GHz).
2. **Phát Sóng Gây Nhiễu**: Sóng mang này được khuếch đại và phát ra qua anten.
3. **Can Thiệp Tín Hiệu**: Sóng gây nhiễu làm suy yếu hoặc lấn át tín hiệu gốc, làm gián đoạn kết nối không dây.

### **Ứng Dụng Thực Tiễn:**
- **Nghiên Cứu Bảo Mật**: Kiểm tra và đánh giá mức độ bảo mật của các hệ thống không dây.
- **Giáo Dục**: Giúp sinh viên và nhà nghiên cứu hiểu rõ nguyên lý hoạt động của các thiết bị không dây và các mối đe dọa tiềm ẩn.

### **Phòng Tránh và Bảo Vệ:**
- **Sử Dụng Mã Hóa**: Áp dụng các phương pháp mã hóa mạnh để bảo vệ dữ liệu.
- **Chuyển Sang Dải Tần Khác**: Sử dụng các dải tần ít bị can thiệp hơn.
- **Giám Sát Tín Hiệu**: Sử dụng các thiết bị giám sát để phát hiện và phản ứng nhanh chóng với các tín hiệu gây nhiễu.

## **Tính Năng**
- **Phá Sóng WiFi:** Ngăn chặn các thiết bị kết nối mạng WiFi trong phạm vi hoạt động.
- **Phá Sóng Bluetooth:** Can thiệp vào các thiết bị sử dụng Bluetooth, gây gián đoạn kết nối.
- **Tạo WiFi Rác:** Tạo ra hàng loạt WiFi đồng thời với địa chỉ khác nhau, gây gián đoạn kết nối.
- **Tạo BlueTooth Rác:** Tạo ra hàng loạt BlueTooth đồng thời với địa chỉ khác nhau, gây gián đoạn kết nối.
- **Tạo Thư Rác Số Điện Thoại:** Tạo ra hàng loạt tin nhắn và cuộc gọi rác, gây khó chịu.
- **Điều Khiển:** Thông qua WebServer và nút bấm có sẵn.
- **Phạm Vi Hoạt Động:** Hoạt động trong băng tần 2.4GHz, với phạm vi tùy thuộc vào công suất và môi trường sử dụng.

## **Yêu Cầu Hệ Thống**
- **Phần Cứng:**
  - ESP32
  - nRF24L01
  - Tụ 10 - 100 uF
  - Nút bấm
  - Angten

- **Phần Mềm:**
  - Demonic

## **Sử Dụng**
- Cấp nguồn cho thiết bị thông qua chân Type-C
- Kết nối với **WiFi: Demonic** và **Mật Khẩu: propropro**
- Truy cập **192.168.4.1** để điều khiển hoặc qua nút nhấn

## **Góp Ý và Phát Triển**
Chúng tôi luôn chào đón các góp ý và sự tham gia phát triển từ cộng đồng. Hãy tạo các pull request hoặc issues nếu bạn có ý tưởng hoặc gặp vấn đề.

## **Pháp Lý**
Dự án này chỉ dành cho mục đích nghiên cứu và giáo dục. Người dùng phải tự chịu trách nhiệm về việc tuân thủ các quy định pháp luật liên quan đến việc sử dụng các thiết bị chứa phần mềm và phần mềm DEMONIC.

## **Giấy Phép**
Dự án này được cấp phép theo giấy phép GNU General Public License v3.0. Bạn có thể xem toàn bộ nội dung giấy phép tại [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

<h1 align="center"> NGUYEN QUANG HIEU </h1>
