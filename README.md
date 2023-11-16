# Quản lý thư viện Nhóm 1 Ca 2
# Mục lục
[I. Giới thiệu đề tài](#I)  
[1. Giới thiệu chung](#gt)  
[2. Các chức năng chính](#function)  
[II. Các thành viên](#member)  
[III. Công nghệ sử dụng](#cn)  
[IV. Những nội dung đã làm được](#dalam)  
[V. Hướng phát triển](#hpt)  

<a name = "I"></a>
# I. Giới thiệu đề tài   
![home](https://intedic.com/wp-content/uploads/2022/04/phan-mem-quan-ly-thu-vien.jpg)
<a name = "gt"></a>
## 1. Giới thiệu chung:  
  Thư viện là kho tàng tri thức vô giá, và chúng tôi hân hạnh giới thiệu đến bạn một website quản lý thư viện hiện đại và tiện ích. Với mục tiêu là tạo ra một không gian giúp cho người quản lý thư viện có thể quản lý, tổ chức và cung cấp dịch vụ thư viện hiệu quả. Đây không chỉ là một công cụ quản lý tài liệu mà còn là một hệ thống thông tin toàn diện hỗ trợ quy trình hoạt động của thư viện.
<a name = "function"></a>
## 2. Giới thiệu các thức năng chính:  
  Tại website này nhóm chúng tôi sẽ đưa tới cho người sử dụng các chức năng để quản lý thư viện một cách trực quan nhất. Bạn có thể quản lý sách ở trong thư viện, thêm những quyển sách mới, sửa lại thông tin hoặc xóa chúng nếu thư viện không còn nữa.  
Còn có chức năng quản lý bạn đọc giúp bạn có thể biết được thư viện của bạn có những bạn đọc nào cũng như họ đã mượn những cuốn sách nào, mỗi bạn đọc sẽ có một thẻ mượn và chúng tôi cũng có chức năng giúp bạn quản lý những thẻ mượn trả này như thế sẽ giúp cho việc bạn đọc mượn sách của thư viện được thư viện quản lý một cách chặt chẽ.  
Ngoài ra website còn có Thống kê số lượng được mượn của mỗi sách giúp cho chủ thư viện nắm được lượt mượn nhằm kiểm tra đảm bảo chất lượng của sách và nhập thêm sách nữa cần.
<a name = "member"></a>
# II. Các thành viên
|       Tên thành viên       |      Giới thiệu         | Vị trí     |  Email  |
| :------------:|:-------------:|:-----:|:-----------------|
|    Hoàng Thanh Huy          |        Nikname: Huyvipp123      |  Product Owner, Developer    |   hhuy68155@gmail.com   |
|     Đồng Phước Đạt         |        Nikname: Jackspiser      |   Scrum Master, Developer   |   datphuoc123000@gmail.com   |
|     Đinh Văn Lâm         | Nikname: Dinhlam123             |    Team Lead, Developer  |    dlam11032003@gmail.com    |
|     Ngô Xuân Hoàng    |     Nikname: hoanngo457           |      Developer   |    hoangngo457@gmail.com

<a name = "cn"></a>
# III. Công nghệ sử dụng
1. Môi trường thực hiện:
   MVC(Model-View-Controller)  
   <img src="https://www.pngkey.com/png/full/244-2444351_mvc-visual-studio-2010-icon.png" alt="..." width="250" />  
Mô hình MVC là một kiến trúc phần mềm được sử dụng để tổ chức và thiết kế các thành phần trong một ứng dụng. "MVC" là viết tắt của ba thành phần chính trong mô hình: Mô hình (Model), Quản lý Hiển thị (View), và Quản lý Điều khiển (Controller). Mô tả về các thành phần:  
   1.1. Model:
   <ul>
     <li>Đại diện cho dữ liệu và logic xử lý dữ liệu trong ứng dụng.  </li>
     <li>Thực hiện các thao tác như đọc và ghi dữ liệu, xử lý logic kinh doanh và duy trì trạng thái của ứng dụng. </li>
   </ul> 
   1.2. View:  
   <ul>
     <li>Chịu trách nhiệm hiển thị dữ liệu cho người dùng. </li>
     <li>Không chứa logic kinh doanh, chỉ hiển thị thông tin từ Mô hình và truyền các sự kiện người dùng đến Controller. </li>
   </ul>   
   1.3. Controller:  
   <ul>
     <li>Lắng nghe sự kiện từ người dùng, chẳng hạn như các cú nhấp chuột, phím nhấn, và thao tác người dùng khác. </li>
     <li>Xử lý sự kiện và cập nhật Mô hình hoặc View tương ứng.  </li>
     <li>Chịu trách nhiệm điều phối luồng điều khiển trong ứng dụng.  </li>
   </ul>
3. Ngôn ngữ thực hiện:
   C-Sharp  
   <img src="https://static-00.iconduck.com/assets.00/c-sharp-c-icon-1822x2048-wuf3ijab.png" alt="..." width="180" />  
C# (C Sharp) là một ngôn ngữ lập trình được phát triển bởi Microsoft, chủ yếu dành cho việc phát triển ứng dụng trên nền tảng Windows và .NET. Được thiết kế với hướng đối tượng, C# hỗ trợ quản lý bộ nhớ tự động, đa luồng, LINQ, và tích hợp chặt chẽ với các framework mạnh mẽ như .NET Framework và .NET Core. C# cũng có khả năng phát triển ứng dụng đa nền tảng và di động thông qua Xamarin. Với cộng đồng lớn và hỗ trợ đa dạng, C# đã trở thành một ngôn ngữ quan trọng trong cả lĩnh vực phát triển desktop và web.  
5. IDE:
   Visual Studio  
   <img src="https://logowik.com/content/uploads/images/6668-.webp" alt="..." width="250" />  
Visual Studio là một môi trường phát triển tích hợp (IDE) do Microsoft phát triển. Được thiết kế cho việc phát triển ứng dụng trên nền tảng Microsoft, Visual Studio cung cấp một loạt các công cụ mạnh mẽ cho việc viết mã, gỡ lỗi, và triển khai ứng dụng. Hỗ trợ đa ngôn ngữ, đa nền tảng, và tích hợp chặt chẽ với .NET, nó là một công cụ quan trọng trong cộng đồng phát triển phần mềm.  
7. Database: SQL Server  
   <img src="https://logowik.com/content/uploads/images/microsoft-sql-server4529.jpg" alt="..." width="250" />  
SQL Server là hệ quản trị cơ sở dữ liệu (DBMS) được phát triển bởi Microsoft. Được thiết kế để quản lý và lưu trữ dữ liệu, SQL Server cung cấp nền tảng cho việc phát triển, triển khai, và quản lý các ứng dụng cơ sở dữ liệu. Nó hỗ trợ ngôn ngữ truy vấn SQL (Structured Query Language) và cung cấp các tính năng như bảo mật dữ liệu, xử lý giao dịch, và khả năng mở rộng để đáp ứng các yêu cầu của các ứng dụng doanh nghiệp và web. SQL Server là một trong những hệ quản trị cơ sở dữ liệu phổ biến và được sử dụng rộng rãi trên toàn thế giới.  
<a name = "dalam"></a>
# IV. Những nội dung đã làm được:  
![Screenshot (55)](https://github.com/hoangngo457/QuanLyThuVien_Nhom1_T6_Ca2/assets/66813345/fdedd417-c054-4998-ac01-558b0ecd0e76)  
Đã thực hiện được các chức năng quản lý thư viện cơ bản:  
1. Đăng nhập: Chủ thư viện hoặc các nhân viên sẽ truy cập được vào trang web để thực hiện các nghiệp vụ của họ.    
2. Quản lý sách: Chủ thư viện hoặc nhân viên có thể xem các cuốn sách mà thư viện đang có, số lượng của chúng cũng như là tình trạng của chúng(còn hay đã được mượn hết), thêm lại các đầu sách mới hoặc cập nhật lại các thông tin của sách, cũng như số lượng nếu có nhập mới về.  
3. Quản lý loại sách: Điều này giúp chủ thư viện hoặc nhân viên biết được thư viện hiện tại đang cho mượn những thể loại sách nào nhằm mục đích bổ sung những loại sách mới phù hợp.
4. Quản lý tài khoản: Giúp cho chủ thư viện có thể tạo được tài khoản cho những nhân viên mới, cũng như chỉnh sửa lại khi cần thiết.  
5. Quản lý thẻ thư viện: Điều này giúp quản lý được hiện tại thư viện có bao nhiêu bạn đọc, cũng như thông tin về ngày đăng kí và ngày hết hạn thẻ cảu bạn đọc đó.  
6. Quản lý nhân viên: Giúp chủ thư viện quản lý được hiện tại đã có bao nhiêu nhân viên làm việc tại thư viện để có thể tuyển dụng thêm nhân viên mới khi cần thiết.  
7. Quản lý mượn trả: Mục đích của chức năng này là biết được ai đã mượn những cuốn sách nào cũng như ngày mượn và ngày trả dự kiến để có những biện pháp xử lí khi cần thiết.  

<a name = "hpt"><a/>
# V. Hướng phát triển:  
<img src="https://luanvanaz.com/wp-content/uploads/2015/08/7ffe5599705f8b26d21f774163e9dc52.jpg" alt="..." width="500" />  

Hiện tại website đã cung cấp được một số chức năng cơ bản để có thể quản lý được hệ thống thư viện ở mức đơn giản. Chính vì thế trong tương lai chúng tôi sẽ có dự định sẽ phát triểm website quản lý thư viện thêm nhiều chức năng tiên tiến, hỗ trợ người dùng giúp cho trải nghiệm người dùng được thuận tiện hơn nữa. Một số các chức năng chũng tôi dự định phát tiển như là:  
1. Nhập sách vào hệ thống với số lượng lớn.    
2. Lấy thông tin sách bằng mã QR trên sách: điều này giúp thuận tiện hơn cho nhân viên khi cho mượn sách.    
3. Tạo một môi trường với tính năng tương tác giữa các bạn đọc và kết nối cộng đồng: có các tính năng tương tác, như bình luận, đánh giá sách, chia sẻ suy nghĩ về tác phẩm, tạo cơ hội giao lưu văn hóa giữa người đọc.    
4. Bảo mật: Bảo mật thông tin người dùng và dữ liệu của thư viện.    
5. Hỗ trợ kĩ thuật: đảm bảo người dùng có trải nghiệm tốt nhất và để hệ thống hoạt động một cách trơn tru và hiệu quả.    
