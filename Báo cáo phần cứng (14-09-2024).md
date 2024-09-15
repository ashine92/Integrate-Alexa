# Báo cáo phần cứng (14-09-2024)
## Sơ đồ mạch hoàn chỉnh
![image](https://github.com/user-attachments/assets/08b04842-6505-4316-bc65-f7aba14173cb)

## I. Điều khiển đèn từ xa
### 1. Linh kiện
#### a. LED
![image](https://github.com/user-attachments/assets/95f51576-77b6-4600-8da2-82605a9923e6)

Hình 1.1: LED (Light Emitting Diode)
- LED (Light Emitting Diode): LED là một thiết bị bán dẫn phát sáng khi có dòng điện chảy qua nó. Các electron trong bán dẫn kết hợp với các lỗ electron, phát ra năng lượng dưới dạng photon.

#### b. Breadboard
![image](https://github.com/user-attachments/assets/d5d3a0cd-16da-49b6-a4d6-d6223d338920)

Hình 1.2: Breadboard
- Breadboard là một bảng cơ sở để xây dựng mạch điện. Nó cho phép bạn đặt các thành phần và kết nối lên bảng để tạo mạch mà không cần hàn.
#### c. Switch
![image](https://github.com/user-attachments/assets/f5c75e1e-259c-46d0-8cbd-d9f690e6e065)

Hình 1.3: Công tắc (switch)
- Công tắc (switch) có hai trạng thái: ON (đóng) và OFF (mở). Trạng thái của công tắc sẽ thay đổi từ ON sang OFF, hoặc từ OFF sang ON mỗi khi nó được nhấn.
 
#### d. Vi điều khiển ESP32
![image](https://github.com/user-attachments/assets/d09a9eae-d260-4243-99d2-e5ac83bd4c40)

Hình 1.4: Vi điều khiển ESP32
- ESP32 là một mạch điều khiển mạnh mẽ được phát triển bởi Espressif Systems, sở hữu khả năng kết nối không dây WiFi lẫn Bluetooth. Ngoài ra, chúng cũng tích hợp nhiều linh kiện điện tử đa dạng cho dự án.

### 2. Sơ đồ kết nối linh kiện
![image](https://github.com/user-attachments/assets/6e3413b4-1294-43ab-8d1c-084695742f95)

## II. Đo độ ẩm và nhiệt độ trong không khí
### 1. Linh kiện
#### a. Vi điều khiển ESP 8266
![image](https://github.com/user-attachments/assets/0f6e07ed-5e30-494d-a155-85bddc3f6a4b)
Hình 2.1: Vi điều khiển ESP 8266

#### b. Cảm biến DTH11
![image](https://github.com/user-attachments/assets/788c93f6-6ab4-4477-a838-4d6a6f11b531)
Hình 2.2: Cảm biến độ ẩm, nhiệt độ DHT11 Temperature Humidity Sensor. 

#### c. Breadboard
![image](https://github.com/user-attachments/assets/458be7b8-4d48-432a-bff7-8e90fcaf7030)
Hình 2.3: Breadboard

#### d. Màn hình OLED

![image](https://github.com/user-attachments/assets/ae704032-062d-4c35-924e-b188d07cb641)
Hình 2.4: Màn OLED

### 2. Sơ đồ kết nối linh kiện
![image](https://github.com/user-attachments/assets/4c1bf53b-7ce7-4f74-84fa-40935e52ac67)

## III. Đo lượng nước sử dụng
### 1. Linh kiện
#### a. Vi điều khiển ESP 8266 (95K)
![image](https://github.com/user-attachments/assets/b1e40a44-5ef3-47c8-a945-8673fdf4e375)
Hình 3.1: Vi điều khiển ESP 8266
#### b. Breadboard (23K)
 ![image](https://github.com/user-attachments/assets/48de7a7c-5e8b-4a4a-a5b6-0ac841ca57d4)

Hình 3.2: Breadboard

#### c. Cảm biến lưu lượng nước YF-S201 (80k)
![image](https://github.com/user-attachments/assets/769cd07c-a850-4567-b405-f31abef04bfc)
Hình 3.3 Cảm biến lưu lượng nước YF-S201 

**Sơ đồ chân của YF-S201**

| Number| Color | Name| Description |
|--------------|-------|------|-------|
|1 | Yellow | Signal | Pulse Signal | 2 x 4 |
| 2 | Red | VCC |5 ~ 12 V | 3 x 4 |
| 3 | Black | GND | 4 x 3 | 4 x 4 |
   
#### d. Màn hình OLED I2C 60K
![image](https://github.com/user-attachments/assets/9b8871e1-fb68-4374-ba31-3d6a38781a07)

Hình 3.4: Màn hình OLED I2C
### 2. Sơ đồ kết nối linh kiện
![image](https://github.com/user-attachments/assets/558f2b15-2303-4229-abcc-81ba37a7b358)

Hình 3.5 Sơ đồ kết nối linh kiện
## IV. Tài liệu tham khảo
[1] ESP 8266 là gì? https://arduinokit.vn/esp8266-la-gi-huong-dan-lap-trinh-esp8266-bang-arduino-ide/

[2] [Thông tin] kỹ thuật NodeMCU ESP8266: https://mecsu.vn/ho-tro-ky-thuat/thong-tin-ky-thuat-nodemcu-esp8266.R1q

[3] Breadboard: https://dientutuonglai.com/tim-hieu-breadboard.html

[4] Module Cảm Biến Nhiệt Độ - Độ Ẩm: https://chotroihn.vn/module-cam-bien-nhiet-do-do-am-dht11-k1d2-3-5g

[5] Màn hình OLED 0.96: https://arduinokit.vn/huong-dan-su-dung-man-hinh-oled-0-96-voi-arduino-phan-1/

[6] Water Flow Sensor: https://wiki.dfrobot.com/Water_Flow_Sensor_-_1_2__SKU__SEN0217

[7] ESP32 Documentation: https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html, Introduction to ESP32 | Specifications, ESP32 DevKit Board, Layout, (electronicshub.org)

[8] IoT Documentation: Ứng dụng của iot đối với đời sống 2021 - TesterProVN, Documentation on Smart Home Monitoring Using Internet of Things | SpringerLink, Parks Assoc CEA Smart Home Ecosystem WP.pdf (parksassociates.com), Information | Free Full-Text | IoT Privacy and Security Challenges for Smart Home Environments (mdpi.com)
## V. Tài liệu hình ảnh
Hình 1.1: LED (Light Emitting Diode)

Hình 1.2: Breadboard

Hình 1.3: Công tắc (switch)

Hình 1.4: Vi điều khiển ESP32

Hình 2.1: Vi điều khiển ESP 8266

Hình 2.2: Cảm biến độ ẩm, nhiệt độ DHT11 Temperature Humidity Sensor. 

Hình 2.3: Breadboard

Hình 2.4: Màn OLED

Hình 3.1: Vi điều khiển ESP 8266

Hình 3.2: Breadboard

Hình 3.3 Cảm biến lưu lượng nước YF-S201 

Hình 3.4: Màn hình OLED I2C

Hình 3.5 Sơ đồ kết nối linh kiện
