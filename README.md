# Selenium Test Project

## Giới thiệu
Dự án này là một ứng dụng kiểm thử tự động sử dụng Selenium để kiểm tra chức năng của trang web. Các bài kiểm thử được thực hiện cho trang Google và được triển khai trên Jenkins để tự động hóa quy trình kiểm thử.

## Yêu cầu
- Java 8 trở lên
- Maven
- ChromeDriver
- Jenkins

## Cài đặt

### Bước 1: Tải xuống ChromeDriver về Máy
1. Truy cập [ChromeDriver Downloads](https://storage.googleapis.com/chrome-for-testing-public/130.0.6723.69/win64/chrome-win64.zip).
2. Tải về phiên bản ChromeDriver tương thích với phiên bản Chrome của bạn.
3. Giải nén tệp và lưu vào một thư mục, ví dụ: `C:\Users\Noir\chromedriver-win64\`.

### Bước 2: Cấu hình Đường dẫn
Mở file `AppTest.java` trong thư mục `src/test/java` và đảm bảo rằng đường dẫn đến `chromedriver.exe` là chính xác:
```java
System.setProperty("webdriver.chrome.driver", "C:\\Users\\Noir\\chromedriver-win64\\chromedriver.exe");
