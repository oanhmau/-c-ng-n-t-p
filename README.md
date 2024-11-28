# Đề cương ôn tập 
## Chương 1: Cấu trúc máy tính
### 1. Cấu trúc máy tính
- Cấu trúc máy tính bao gồm nhiều thành phần chính, mỗi thành phần có vai trò và chức năng riêng:
+ CPU (Central Processing Unit): Là bộ xử lý trung tâm, có nhiệm vụ thực hiện các lệnh và xử lý dữ liệu. CPU bao gồm ba thành phần chính:
Control Unit (CU): Điều khiển các hoạt động của các thành phần khác trong máy tính.
+ Arithmetic Logic Unit (ALU): Thực hiện các phép toán số học và logic.
+ Registers (RF): Bộ nhớ tạm thời để lưu trữ dữ liệu và lệnh trong quá trình xử lý.
+ GPU (Graphics Processing Unit): Được thiết kế để xử lý các tác vụ đồ họa và hình ảnh. GPU có khả năng xử lý song song nhiều tác vụ, rất hữu ích cho các ứng dụng đồ họa, trò chơi và học máy.
+ RAM (Random Access Memory): Là bộ nhớ tạm thời, nơi lưu trữ dữ liệu và chương trình đang được sử dụng. Dữ liệu trong RAM sẽ bị mất khi tắt máy.
+ ROM (Read-Only Memory): Là bộ nhớ chỉ đọc, chứa các chương trình và dữ liệu cố định mà không thể thay đổi. ROM thường chứa firmware và các thông tin khởi động máy.
+ SSD (Solid State Drive): Là thiết bị lưu trữ không có bộ phận chuyển động, sử dụng bộ nhớ flash để lưu trữ dữ liệu. SSD nhanh hơn HDD và tiêu thụ ít năng lượng hơn.
+ HDD (Hard Disk Drive): Là thiết bị lưu trữ truyền thống sử dụng đĩa từ để lưu trữ dữ liệu. HDD có dung lượng lớn nhưng tốc độ truy xuất chậm hơn SSD.
+ Bo mạch chủ (Motherboard): Là bảng mạch chính kết nối tất cả các thành phần của máy tính, cho phép chúng giao tiếp với nhau. Bo mạch chủ chứa các khe cắm cho CPU, RAM, GPU và các thiết bị khác.
### 2. Các thế hệ máy tính
- Máy tính đã trải qua 5 thế hệ chính, mỗi thế hệ có những đặc điểm và công nghệ riêng:
+Thế hệ thứ nhất (1940-1956): Sử dụng bóng đèn chân không (vacuum tubes) để xử lý dữ liệu. Máy tính lớn, tốn điện và không đáng tin cậy.
+ Thế hệ thứ hai (1956-1963): Sử dụng transistor thay cho bóng đèn chân không. Máy tính nhỏ hơn, nhanh hơn và tiêu thụ ít điện hơn.
+ Thế hệ thứ ba (1964-1971): Sử dụng mạch tích hợp (IC), giúp giảm kích thước và tăng tốc độ xử lý. Máy tính trở nên phổ biến hơn.
+ Thế hệ thứ tư (1971-1980): Sử dụng vi xử lý (microprocessor), tích hợp toàn bộ CPU vào một chip. Máy tính cá nhân ra đời và trở nên phổ biến.
+ Thế hệ thứ năm (1980-nay): Tập trung vào trí tuệ nhân tạo (AI) và công nghệ máy học. Sự phát triển của Internet và điện toán đám mây.
### 3. Phần cứng, phần mềm và hệ điều hành
- Phần cứng (Hardware): Là các thành phần vật lý của máy tính, bao gồm CPU, RAM, ổ cứng, bo mạch chủ, và các thiết bị ngoại vi như bàn phím, chuột, màn hình.
- Phần mềm (Software): Là tập hợp các chương trình và dữ liệu hướng dẫn phần cứng thực hiện các tác vụ. Phần mềm có thể được chia thành phần mềm hệ thống (như hệ điều hành) và phần mềm ứng dụng (như ứng dụng văn phòng, trò chơi).
-Hệ điều hành (Operating System): Là phần mềm quản lý phần cứng và phần mềm trên máy tính. Hệ điều hành cung cấp giao diện cho người dùng và điều phối các tác vụ, như Windows, macOS, Linux.
### 4. CPU: CU-ALU-RF
- CPU (Central Processing Unit): là thành phần chính của máy tính, thực hiện các phép toán và xử lý dữ liệu. CPU bao gồm ba thành phần chính:
+ Control Unit (CU - Đơn vị điều khiển):
. Chức năng: CU điều khiển và quản lý hoạt động của CPU cũng như các thành phần khác trong máy tính. Nó thực hiện việc giải mã lệnh và điều phối các tín hiệu đến các phần khác của CPU và hệ thống.
. Quá trình hoạt động: Khi CPU nhận lệnh từ bộ nhớ, CU giải mã lệnh đó và xác định các bước cần thực hiện. Nó gửi tín hiệu đến ALU để thực hiện các phép toán và điều phối dữ liệu giữa các thanh ghi và bộ nhớ.
+ Arithmetic Logic Unit (ALU - Đơn vị số học và logic):
. Chức năng: ALU thực hiện các phép toán số học (cộng, trừ, nhân, chia) và các phép toán logic (AND, OR, NOT).
. Quá trình hoạt động: ALU nhận tín hiệu từ CU và dữ liệu từ các thanh ghi để thực hiện các phép toán. Kết quả của các phép toán này sẽ được lưu trữ lại trong các thanh ghi hoặc gửi đến bộ nhớ.
+ Registers (RF - Thanh ghi):
. Chức năng: Registers là bộ nhớ tạm thời bên trong CPU, dùng để lưu trữ dữ liệu và lệnh trong quá trình xử lý. Chúng có tốc độ truy cập rất nhanh, giúp CPU thực hiện các phép toán một cách hiệu quả.
- Các loại thanh ghi:
+ Thanh ghi dữ liệu: Lưu trữ dữ liệu cần thiết cho phép toán.
+ Thanh ghi địa chỉ: Lưu trữ địa chỉ của dữ liệu trong bộ nhớ.
+ Thanh ghi lệnh: Lưu trữ lệnh hiện tại đang được thực hiện.
+ Thanh ghi trạng thái: Lưu trữ thông tin về trạng thái của CPU (ví dụ: kết quả của phép toán logic).
### 5. Main Memory vs. Cache Memory
- Bộ nhớ chính (Main Memory) và bộ nhớ cache (Cache Memory) là hai loại bộ nhớ quan trọng trong máy tính, nhưng chúng có những đặc điểm khác nhau:
+ Bộ nhớ chính (Main Memory)
. Định nghĩa: Bộ nhớ chính, thường được gọi là RAM (Random Access Memory), là nơi lưu trữ dữ liệu và chương trình đang được sử dụng. Nó có khả năng lưu trữ tạm thời và dữ liệu sẽ bị mất khi tắt máy.
. Tốc độ: RAM có tốc độ truy cập nhanh hơn so với HDD và SSD, nhưng chậm hơn so với cache memory.
. Dung lượng: Bộ nhớ chính thường có dung lượng lớn hơn so với cache memory, cho phép lưu trữ nhiều dữ liệu và chương trình hơn.
. Chức năng: Dùng để lưu trữ dữ liệu và lệnh mà CPU cần trong quá trình xử lý.
+ Bộ nhớ cache (Cache Memory)
. Định nghĩa: Cache memory là bộ nhớ tạm thời được sử dụng để lưu trữ các dữ liệu và lệnh mà CPU thường xuyên truy cập. Nó nằm gần CPU hơn so với RAM.
. Tốc độ: Cache memory có tốc độ truy cập rất nhanh, nhanh hơn nhiều so với RAM, giúp tăng tốc độ xử lý của CPU.
. Dung lượng: Dung lượng của cache memory thường nhỏ hơn so với bộ nhớ chính, thường chỉ từ vài KB đến vài MB.
. Chức năng: Cache memory lưu trữ các dữ liệu và lệnh mà CPU sử dụng thường xuyên, giúp giảm thời gian truy cập dữ liệu và tăng hiệu suất xử lý.
### Các câu hỏi trắc nghiệm
- #### Câu 1: Trong cấu trúc máy tính, thành phần nào sau đây có chức năng điều khiển các hoạt động của CPU và đảm bảo rằng các lệnh được thực hiện theo đúng thứ tự?
 A. ALU
 B. CU
 C. RAM
 D. GPU
##### Đáp án: B. CU
- #### Câu 2: Những đặc điểm nào sau đây đúng về bộ nhớ cache? (Chọn tất cả các đáp án đúng)
 A. Có tốc độ truy cập nhanh hơn bộ nhớ chính (RAM)
 B. Lưu trữ dữ liệu tạm thời và có dung lượng nhỏ hơn
 C. Giúp tăng tốc độ xử lý của CPU bằng cách giảm thời gian truy cập dữ liệu
 D. Dữ liệu trong cache sẽ bị mất khi tắt máy
 E. Là bộ nhớ vĩnh viễn, không bị mất dữ liệu khi tắt máy
##### Đáp án: A. Có tốc độ truy cập nhanh hơn bộ nhớ chính (RAM), B. Lưu trữ dữ liệu tạm thời và có dung lượng nhỏ hơn, C. Giúp tăng tốc độ xử lý của CPU bằng cách giảm thời gian truy cập dữ liệu, D. Dữ liệu trong cache sẽ bị mất khi tắt máy
- #### Câu 3: Trong cấu trúc máy tính, các thành phần chính bao gồm __________, __________, __________, __________, __________, __________, và __________. Trong đó, CPU được chia thành ba phần chính là __________, __________, và __________.

 ##### Đáp án: CPU, GPU, RAM, ROM, SSD, HDD, Bo mạch chủ; CU (Control Unit), ALU (Arithmetic Logic Unit), RF (Registers)



