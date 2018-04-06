
# Elipse Tutorial
*Nguồn tham khảo : https://www.tutorialspoint.com/eclipse/index.htm*

## 1. Tổng quan về Elipse :
- Elipse là một môi trường phát triển tích hợp (IDE) cho ngôn ngữ Java, C, C++, PHP, Ruby,...(?Khi nào thử cài Trình biên dịch của C++ trên Elipse xem sao !!!)Vậy IDE khác Editor ở chỗ nào?
  - Editor (như notepadd++, Sublime,...): cho phép Lập trình viên sửa xóa code trong file, nhưng không có khả năng compile (biên dịch) và run (chạy) mã nguồn. Đồng thời nói không thể kiểm tra được lỗi về cú pháp (do không có trình biên dịch của ngôn ngữ được tích hợp) ==> Do không có trình biên dịch, nên thông thường nếu vẫn muốn chạy được mã nguồn trên các Editor này, chúng ta phải mượn trình biên dịch của Hệ điều hành. Ví dụ, khi sử dụng Sublime hay Notepad++ để chạy chương trình code-C thì cần gọi trình biên dịch của Linux hoặc Window,...==> Khá bất tiện !!!

  - IDE (Itegrated Development Environment) - Môi trường phát triển tích hợp : Bên trong IDE đã được gắn liền với một trình biên dịch cụ thể cho từng ngôn ngữ mà ta lựa chọn trước khi cài đặt như : Trình biên dịch của Java hay của PHP, hay của C (do cấu trúc và cú pháp của mỗi ngôn ngữ lập trình khác nhau nên cần phải sử dụng các trình biên dịch khác nhau) ==> Vì bên trong IDE đã được trang bị Trình biên dịch, do vậy trong quá trình Coding, mã nguồn của Lập trình viên sẽ được tự động kiểm tra lỗi cú pháp, được biên dịch và chạy ngay được nhờ chính Compiler (trình biên dịch) này. Ngoài ra, đối với một IDE sẽ được trang bị tính năng thuận tiện khác phục vụ đắc lực cho Lập trình viên trong Quá trình phát triển phần mềm.
  
- Với từng ngôn ngữ lập trình khác nhau, chúng ta có thể chọn lựa Công cụ phát triển tương ứng], ví dụ như : 
  - Với Java, sử dụng Java Development Tools (JDT) cho cung một plug-in mà cho phép Elipse có thể được sử dụng như một Java IDE
  - Tương tự, PyDev là plugin cho phép Elipse được sử dụng như Python IDE
  - C++ Development Tools (CDT) là plug-in cho C++ IDE, tượng tự với PHP Eclipse, ...
  
  
## 2. Cài đặt Eclipse 
- Lên trang chủ tải phiên bản về: http://www.eclipse.org/downloads/
- Tiến hành cài đặt file tải về ==> Eclipse hỏi bạn muốn cài Eclipse cho Java hay PHP, hay C++,... ==> Lựa chọn ngôn ngữ mong muốn ==> Kết thúc quá trình cài đặt
- Sau khi cài đặt xong, Eclipse hiện thông báo : Yêu cầu người dùng chỉ đường dẫn tới Work Space (Không gian làm việc - là thư mục gốc giúp ta có thể lưu các project vào trong đó) ==> Ta cần nên phải chỉ ra đường dẫn tới thư mục làm việc bởi vì nếu không chỉ ra thì Eclipse sẽ tự động chọn lựa thư mục ở trong ổ C
