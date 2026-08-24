# Mạch phát triển MKE-K06 STM32F103C8T6 Blue Pill Dev Kit

## Giới thiệu

**Mạch phát triển MKE-K06 STM32F103C8T6 Blue Pill Dev Kit** sử dụng vi điều khiển **STM32F103C8T6 chính hãng STMicroelectronics**, dựa trên kiến trúc **ARM Cortex-M3 32-bit**, phù hợp cho học tập, nghiên cứu và phát triển các dự án điện tử nhúng.

Board hỗ trợ **Arduino IDE**, cho phép nạp **Arduino Bootloader** và lập trình tương tự các board Arduino thông dụng. Đồng thời, MKE-K06 vẫn hỗ trợ các môi trường phát triển chuyên nghiệp như **STM32CubeIDE, Keil và IAR**, phù hợp cho cả người mới bắt đầu với STM32 và các dự án phát triển hệ thống nhúng chuyên sâu.

MKE-K06 được tích hợp sẵn **mạch nguồn 3.3VDC, thạch anh hệ thống, thạch anh RTC, LED nguồn, LED người dùng và nút Reset**, đồng thời đưa ra đầy đủ các chân GPIO với nhiều giao tiếp phổ biến như **CAN, I2C, SPI, UART, USB, PWM và ADC**.

## Ứng dụng

MKE-K06 phù hợp cho:

* Học tập và thực hành lập trình STM32.
* Nghiên cứu vi điều khiển ARM Cortex-M3.
* Phát triển các thiết bị nhúng.
* Dự án IoT và tự động hóa.
* Điều khiển động cơ và thiết bị ngoại vi.
* Giao tiếp cảm biến thông qua I2C, SPI, UART.
* Các dự án sử dụng CAN Bus.
* Lập trình Arduino trên nền tảng STM32.
* Phát triển firmware chuyên nghiệp với STM32CubeIDE, Keil hoặc IAR.

## Thông số kỹ thuật

| Thông số               | Giá trị                         |
| ---------------------- | ------------------------------- |
| **Model**              | MKE-K06 STM32F103C8T6 Blue Pill Dev Kit |
| **Vi điều khiển**      | STM32F103C8T6 chính hãng STMicroelectronics |
| **Kiến trúc**          | ARM Cortex-M3 32-bit            |
| **Điện áp cấp nguồn**  | 5VDC qua cổng USB-C             |
| **Điện áp GPIO**       | TTL 3.3VDC                      |
| **Thạch anh hệ thống** | 8MHz                            |
| **Thạch anh RTC**      | 32KHz                           |
| **Giao tiếp**          | CAN, I2C, SPI, UART, USB        |
| **Chức năng ngoại vi** | PWM, ADC                        |
| **LED nguồn**          | Có                              |
| **LED người dùng**     | PC13                            |
| **Nút nhấn**           | Reset                           |
| **Arduino IDE**        | Hỗ trợ                          |
| **Arduino Bootloader** | Hỗ trợ nạp                      |
| **STM32CubeIDE**       | Hỗ trợ                          |
| **Keil**               | Hỗ trợ                          |
| **IAR**                | Hỗ trợ                          |
| **Kích thước**         | 53.34 × 22.86mm                 |

> **Lưu ý:** Các chân GPIO sử dụng mức logic **3.3VDC**. Không cấp trực tiếp tín hiệu 5V vào các chân GPIO nếu thiết bị ngoại vi không tương thích với mức logic 3.3V.

## Hướng dẫn sử dụng

Tham khảo [hướng dẫn sử dụng chi tiết tại đây.](https://deepbluembedded.com/stm32-blue-pill-pinout-programming-guide/)

## Kích thước sản phẩm
![MKE-K06 STM32F103C8T6 DK](/extras/MKE-K06_1.jpg)

## Lưu ý sử dụng an toàn
- Không đặt mạch trên bề mặt kim loại dẫn điện
- Tránh môi trường:
  - Ẩm ướt
  - Nhiệt độ cao
  - Nhiều bụi dẫn điện
- Nên sử dụng với nguồn điện chất lượng tốt
- Luôn đảm bảo mạch:
  - Không bị chập mạch
  - Không đấu sai cực nguồn
- Nên ngắt nguồn trước khi thay đổi đấu nối phần cứng.

## Hình ảnh sản phẩm
![MKE-K06 STM32F103C8T6 DK](/extras/MKE-K06_2.png)
![MKE-K06 STM32F103C8T6 DK](/extras/MKE-K06_3.png)

## Miễn trừ trách nhiệm
Sản phẩm này là bo mạch phát triển được thiết kế phục vụ cho mục đích nghiên cứu, thử nghiệm và học tập, không phải là một thiết bị hoàn chỉnh. Trong trường hợp người dùng kết hợp mạch này với các linh kiện, thiết bị hoặc phần mềm khác để tạo thành một hệ thống hoặc sản phẩm hoàn chỉnh, mọi chức năng và tính phù hợp của sản phẩm sau cùng đều thuộc trách nhiệm của người dùng.
