# Selenium Test Project

## Giới thiệu
Dự án này là một ứng dụng kiểm thử tự động sử dụng Selenium để kiểm tra chức năng của trang web. Mẫu kiểm thử được thực hiện cho trang Google.

## Yêu cầu
- Java 8 trở lên
- Maven
- ChromeDriver

## Cài đặt

### Bước 1: Tải xuống ChromeDriver
1. Truy cập [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/downloads).
2. Tải về phiên bản ChromeDriver tương thích với phiên bản Chrome của bạn.
3. Giải nén tệp và lưu nó vào một thư mục (ví dụ: `C:\Users\Noir\chromedriver-win64\`).

### Bước 2: Cấu hình Đường dẫn
Mở file `AppTest.java` và đảm bảo rằng đường dẫn đến `chromedriver.exe` là chính xác:
```java
System.setProperty("webdriver.chrome.driver", "C:\\Users\\Noir\\chromedriver-win64\\chromedriver.exe");
