Họ tên: Lê Thành Công

#Báo cáo CCNA
##A. Mạng máy tính
###1. Khái niệm
Mạng máy tính là tập hợp các thiết bị có khả năng truyền dữ liệu và các thiết bị, hệ thống đầu cuối (như user, server) được kết nối với nhau để có thể giao tiếp và truyền dược dữ liệu. Trong một hệ thống mạng có thể truyền tải rất nhiều kiểu dữ liệu, loại dữ liệu và các ứng dụng khác nhau.
###2. Các thành phần cơ bản của hệ thống mạng
####2.1. End devices
End devices là những thiết bị sinh ra và nhận bản tin. Dữ liệu được sinh ra từ end device, truyền qua mạng và gửi tới một end device.

Ví dụ: máy tính, laptop, điện thoại,...
####2.2. Các đường link kết nối
- Connector : cổng mạng RJ-45, RJ-11,….phục vụ giao tiếp dữ liệu giữa đường truyền và NIC trên thiết bị. 
- Devices tiếp nhận dữ liệu trên máy tính người dùng: NIC (card mạng có dây và không dây ). Thực hiện chuyển dữ liệu thành các dạng tín hiệu có thể truyền trên đường truyền như tín hiệu điện, ….
####2.3. Thiết bị tập trung
Switch, hub, brigde có chức năng tập dung dữ liệu từ các end users. Thực hiện chuyển mạch dữ liệu ở Layer 2 Ethernet LAN.
####2.4. Thiết bị định tuyến
Thiêt bị định tuyến thực hiện chức năng định tuyến (chọn đường đi tối ưu nhất) cho các dữ liệu đã được tập trung ở layer 2
###3. Các mô hình mạng máy tính
####3.1. LAN
Mô hình mạng LAN (Local area network) là mạng cục bộ, mạng tư nhân trong một tòa nhà hoặc một khu vực. Chúng nối các máy chủ và các máy chạm trong các văn phòng và nhà máy để chia sẻ tài nguyên và trao đổi thông tin.

LAN có 3 đặc điểm:

- Giới hạn về phạm vi hoạt động (<1km)
- Thường dung kỹ thuật đơn giản chỉ có một đường dây cáp nối tất cả máy
- 3 kiến trúc mạng LAN thông dụng: mạng bus, mạng vòng, mạng sao

####3.2. MAN
Mạng MAN (Metropolitan Area Network) hay còn gọi là mạng đô thị liên kết từ nhiều mạng LAN qua dây cáp, các phương tiện truyền dẫn khác,... Khả năng kết nối trong phạm vi lớn như trong một thị trấn, thành phố, tỉnh.

Mô hình mạng MAN thường được dùng chủ yếu cho đối tượng là tổ chức, doanh nghiệp nhiều chi nhánh, nhiều bộ phận kết nối với nhau.

Mạng MAN thường được sử dụng cho doanh nghiệp vì mô hình này này cung cấp nhiều loại dịch vụ như kết nối đường truyền qua voice (thoại), data (dữ liệu), video (hình ảnh), triển khai các ứng dụng dễ dàng.

Phạm vi kết nối lớn giúp tương tác giữa các bộ phận doanh nghiệp dễ dàng, hiệu quả,chi phí thấp, tốc độ truyền tải ổn định, bảo mật thông tin, quản lý đơn giản.

####3.3. WAN
Mạng WAN (Wide Area Network) hay còn gọi là mạng diện rộng được kết hợp giữa các mạng đô thị bao gồm cả mạng MAN và mạng LAN thông qua thiết bị vệ tinh, cáp quang, cáp dây điện.

Mạng diện rộng được tạo ra nhằm kết nối trên một diện lớn có quy mô trên quốc gia. Giao thức sử dụng trong mạng WAN là TCP/IP, đường truyền băng thông thay đổi tùy vào vị trí lắp đặt.

Khả năng kết nối rộng lớn, không bị giới hạn tín hiệu, dễ dàng chia sẻ thông tin, lưu trữ dữ liệu. Tốc độ truyền tải tương đối tùy vào mỗi khu vực hoặc thiết bị truyền dẫn khác nhau.

####3.4. PAN
Mạng PAN hay còn gọi là mạng cá nhân khả năng kết nối phạm vi nhỏ thường được dùng thông qua các thiết bị định tuyến. Khả năng định tuyến này giúp truyền dẫn dữ liệu trên thiết bị đến đích.
##B. Mô hình OSI

Mô hình OSI (Open system interconnection – Mô hình kết nối các hệ thống mở) là một thiết kế dựa vào nguyên lý tầng cấp, lý giải một cách trừu tượng kỹ thuật kết nối truyền thông giữa các máy vi tính và thiết kế giao thức mạng giữa chúng. Mô hình này được phát triển thành một phần trong kế hoạch OSI (Open Systems Interconnection) do ISO và IUT-T khởi xướng. Nó còn được gọi là Mô hình bảy tầng của OSI.

Mô hình OSI được tạo ra với mục đích là cho phép sự tương giao (interoperability) giữa các hệ máy (platform) đa dạng được cung cấp bởi các nhà sản xuất khác nhau. Mô hình cho phép tất cả các thành phần của mạng hoạt động hòa đồng, bất kể thành phần ấy do ai tạo dựng. Vào những năm cuối thập niên 1980, ISO đã tiến cử việc thực thi mô hình OSI như một tiêu chuẩn mạng.

###Mô hình OSI gồm 7 lớp:
###1. Lớp Application
Lớp trên cùng trong mô hình OSI là lớp Application (lớp ứng dụng), lớp 7, hỗ trợ ứng dụng và các tiến trình liên quan đến người dùng cuối. Đối tác truyền thông, chất lượng dịch vụ, xác thực người dùng, quyền riêng tư và bất cứ ràng buộc nào về cú pháp dữ liệu sẽ được xem xét và xác định tại lớp này. Tất cả mọi thứ ở lớp 7 được cụ thể thành ứng dụng. Lớp này cung cấp các dịch vụ ứng dụng cho truyền file, email và các dịch vụ phần mềm mạng khác. Telnet, FTP là các ứng dụng nằm hoàn toàn trong trong cấp Application, còn kiến trúc ứng dụng phân tầng là một phần của lớp này.

Tuy nhiên, bạn cần nắm được rằng, lớp này không ám chỉ đến các ứng dụng mà người dùng đang chạy, thay vào đó nó chỉ cung cấp nền tảng làm việc (framework) mà ứng dụng đó chạy bên trên.

Để hiểu lớp ứng dụng này thực hiện những gì, chúng ta hãy giả dụ rằng một người dùng nào đó muốn sử dụng Internet Explorer để mở một FTP session và truyền tải một file. Trong trường hợp cụ thể này, lớp ứng dụng sẽ định nghĩa một giao thức truyền tải. Giao thức này không thể truy cập trực tiếp đến người dùng cuối mà người dùng cuối này vẫn phải sử dụng ứng dụng được thiết kế để tương tác với giao thức truyền tải file. Trong trường hợp này, Internet Explorer sẽ làm ứng dụng đó.
###2. Lớp Presentation
Lớp Presentation lấy dữ liệu đã được cung cấp bởi lớp ứng dụng, biến đổi chúng thành một định dạng chuẩn để lớp khác có thể hiểu được định dạng này. Tương tự như vậy lớp này cũng biến đổi dữ liệu mà nó nhận được từ lớp session (lớp dưới) thành dữ liệu mà lớp Application có thể hiểu được. Lý do lớp này cần thiết đến vậy là vì các ứng dụng khác nhau có dữ liệu khác nhau. Để việc truyền thông mạng được thực hiện đúng cách thì dữ liệu cần phải được cấu trúc theo một chuẩn nào đó.
###3. Lớp Session
Khi dữ liệu đã được biến đổi thành định dạng chuẩn, máy gửi đi sẽ thiết lập một phiên – session với máy nhận. Đây chính là lớp sẽ đồng bộ hoá quá trình liên lạc của hai máy và quản lý việc trao đổi dữ liệu. Lớp phiên này chịu trách nhiệm cho việc thiết lập, quản lý và chấm dứt session với máy từ xa.

Một điểm thú vị về lớp session là nó có liên quan gần với lớp Application hơn với lớp Physical. Có thể một số người nghĩ rằng việc kết nối session mạng như một chức năng phần cứng, nhưng trong thực tế session lại được thiết lập giữa các ứng dụng. Nếu người dùng đang chạy nhiều ứng dụng thì một số ứng dụng này có thể đã thiết lập session với các tài nguyên ở xa tại bất kỳ thời điểm nào.

###4. Lớp Transport
Lớp Transport hay lớp giao vận chịu trách nhiệm chuyển dữ liệu giữa các hệ thống đầu cuối hoặc máy chủ (host). Hệ điều hành Windows cho phép người dùng có thể chạy nhiều ứng dụng một cách đồng thời, chính vì vậy mà nhiều ứng dụng, và bản thân hệ điều hành cần phải truyền thông trên mạng đồng thời. Lớp Transport lấy dữ liệu từ mỗi ứng dụng và tích hợp tất cả dữ liệu đó vào trong một luồng. Lớp này cũng chịu trách nhiệm cho việc cung cấp vấn đề kiểm tra lỗi và thực hiện khôi phục dữ liệu khi cần thiết. Bản chất mà nói, lớp Transport chịu trách nhiệm cho việc bảo đảm tất cả dữ liệu được truyền từ máy gửi đến máy nhận.
###5. Lớp Network
Lớp mạng Network là lớp có trách nhiệm quyết định xem dữ liệu sẽ đến máy nhận như thế nào. Lớp này nắm những thành phần như việc định địa chỉ, định tuyến, và các giao thức logic. Lớp mạng này tạo các đường logic được biết đến như các mạch ảo giữa máy nguồn và máy đích. Mạch ảo này cung cấp các gói dữ liệu riêng lẻ để chúng có thể đến được đích của chúng. Bên cạnh đó lớp mạng cũng chịu trách nhiệm cho việc quản lý lỗi của chính nó, cho việc điều khiển xếp chuỗi và điều khiển tắc nghẽn.

Việc sắp xếp các gói là rất cần thiết bởi mỗi một giao thức giới hạn kích thước tối đa của một gói. Số lượng dữ liệu phải được truyền đi thường vượt quá kích thước gói lớn nhất. Chính vì vậy mà dữ liệu được chia nhỏ thành nhiều gói nhỏ. Khi điều này xảy ra, lớp mạng sẽ gán vào mỗi gói nhỏ này một số thứ tự nhận dạng.

Khi dữ liệu này đến được máy tính người nhận thì lớp mạng lại kiểm tra số thứ nhận dạng của các gói và sử dụng chúng để sắp xếp dữ liệu đúng như những gì mà chúng được chia lúc trước từ phía người gửi, bên cạnh đó còn có nhiệm vụ chỉ ra gói nào bị thiếu trong quá trình gửi.


###6. Lớp Data Link
Tại lớp Data Link, các gói dữ liệu được mã hóa và giải mã thành các bit. Nó cho biết giao thức truyền tải, quản lý và xử lý lỗi trong lớp vật lý Physical, điều khiển luồng và đồng bộ khung.

Lớp liên kết dữ liệu Data Link có thể được chia nhỏ thành hai lớp khác; Media Access Control (MAC) và Logical Link Control (LLC). MAC về cơ bản thiết lập sự nhận dạng của môi trường trên mạng thông qua địa chỉ MAC của nó. Địa chỉ MAC là địa chỉ được gán cho adapter mạng ở mức phần cứng. Đây là địa chỉ được sử dụng cuối cùng khi gửi và nhận các gói. Lớp LLC điều khiển sự đồng bộ khung, điều khiển luồng và cung cấp một mức kiểm tra lỗi.
###7. Lớp Physical
Lớp vật lý Physical của mô hình OSI truyền tải luồng bit, xung điện, tín hiệu radio hoặc ánh sáng thông qua mạng ở mức điện hoặc máy móc. Nó ám chỉ đến các chi tiết kỹ thuật của phần cứng. Lớp vật lý định nghĩa các đặc điểm như định thời và điện áp. Lớp này cũng định nghĩa các chi tiết kỹ thuật phần cứng được sử dụng bởi các adapter mạng và bởi cáp mạng (thừa nhận rằng kết nối là kết nối dây). Để đơn giản hóa, lớp vật lý định nghĩa những gì để nó có thể truyền phát và nhận dữ liệu.
###Cách thức hoạt động trong mô hình OSI
Tầng dưới cung cấp dịch vụ cho các tầng trên nó. Các tầng trên sẻ gửi yêu cầu dữ liệu xuống tầng dưới và nhận được kết quả. Các tầng trên không quan tâm cách thức hoạt động của các tầng dưới.

Phân lớp giao tiếp ngang hàng giữa 2 host với nhau, nhưng các lớp ngang hàng nay muốn giao tiếp được với nhau phải thông qua hoạt động của các lớp dưới. Các loại dữ liệu sẻ đi lần lượt từ lớp trên xuống lớp dưới, cuối cùng đến tầng vật lý sẻ biến đổi thành các tín hiệu để đến được host 2 và tiếp tục đi lên lớp ngang hàng của host 1.

####Encapsulation và De-encapsulation
Khi các gói tin đi từ lớp Application xuống lớp Physical. Các giao thức đặc trưng của mỗi lớp sẻ quy định cách thức đóng gói dữ liệu. Các gói tin này được gọi là PDU (Protocol Data Unit) các gói tin PDU gồm 2 phần là Header (Phần thông tin quản lý gói tin của các tầng)  và Data (dữ liệu thực của gói tin được truyền)

Gói tin PDU đi từ trên xuống dưới chúng sẻ được đóng gói thành data lớp bên dưới và được đóng thêm header của tầng dưới. Cứ xuống thêm một tầng thì sẻ có một header được thêm vào. Đặc biệt ở tầng Data Link , gói tin sẻ được đóng thêm một trường kiểm soát lỗi FCS

Tại đầu nhận quá trình mở gói sẻ bắt đầu một chiều ngược lại từ tầng 1 đến tầng 7, cứ mỗi khi lên 1 tầng thì header của tầng dưới lại được gở bỏ để trả lại gói tin dữ liệu PDU. Đến tầng 7 dữ liệu sẻ được mở gói hoàn toàn. Thực hiện các ứng dụng của tầng này sẻ gửi data trực tiếp đến người dùng.

PDU của từng các lớp trong mô hình OSI:

- Physical: **bit**
- Data link: **Frame**
- Network: **Packet**
- Transport: **Segment**
- Session, Presentation, Application: **Data**
##C. Mô hình TCP/IP
TCP/ IP (Transmission Control Protocol/ Internet Protocol - Giao thức điều khiển truyền nhận/ Giao thức liên mạng), là một bộ giao thức trao đổi thông tin được sử dụng để truyền tải và kết nối các thiết bị trong mạng Internet. TCP/IP được phát triển để mạng được tin cậy hơn cùng với khả năng phục hồi tự động.

Phân tích từ tên gọi, TCP/IP là sự kết hợp giữa 2 giao thức. Trong đó IP (Giao thức liên mạng) cho phép các gói tin được gửi đến đích đã định sẵn, bằng cách thêm các thông tin dẫn đường vào các gói tin để các gói tin được đến đúng đích đã định sẵn ban đầu. Và giao thức TCP (Giao thức truyền vận) đóng vai trò kiểm tra và đảm bảo sự an toàn cho mỗi gói tin khi đi qua mỗi trạm. Trong quá trình này, nếu giao thức TCP nhận thấy gói tin bị lỗi, một tín hiệu sẽ được truyền đi và yêu cầu hệ thống gửi lại một gói tin khác. Quá trình hoạt động này sẽ được làm rõ hơn ở chức năng của mỗi tầng trong mô hình TCP/IP.

###Mô hình TCP/IP gồm 4 lớp
####1. Lớp Application
Đây là lớp giao tiếp trên cùng của mô hình. Đúng với tên gọi, tầng Ứng dụng đảm nhận vai trò giao tiếp dữ liệu giữa 2 máy khác nhau thông qua các dịch vụ mạng khác nhau (duyệt web, chat, gửi email, một số giao thức trao đổi dữ liệu: SMTP, SSH, FTP,...). Dữ liệu khi đến đây sẽ được định dạng theo kiểu Byte nối Byte, cùng với đó là các thông tin định tuyến giúp xác định đường đi đúng của một gói tin.

Lớp Application trong mô hình TCP/IP tương ứng với 3 lớp Application, Presentation và Session trong mô hình OSI.

####2. Lớp Transport
Chức năng chính của tầng 3 là xử lý vấn đề giao tiếp giữa các máy chủ trong cùng một mạng hoặc khác mạng được kết nối với nhau thông qua bộ định tuyến. Tại đây dữ liệu sẽ được phân đoạn, mỗi đoạn sẽ không bằng nhau nhưng kích thước phải nhỏ hơn 64KB. Cấu trúc đầy đủ của một Segment lúc này là Header chứa thông tin điều khiển và sau đó là dữ liệu.

Trong tầng này còn bao gồm 2 giao thức cốt lõi là TCP và UDP. Trong đó, TCP đảm bảo chất lượng gói tin nhưng tiêu tốn thời gian khá lâu để kiểm tra đầy đủ thông tin từ thứ tự dữ liệu cho đến việc kiểm soát vấn đề tắc nghẽn lưu lượng dữ liệu. Trái với điều đó, UDP cho thấy tốc độ truyền tải nhanh hơn nhưng lại không đảm bảo được chất lượng dữ liệu được gửi đi.

####3. Lớp Internet
Gần giống như tầng mạng của mô hình OSI. Tại đây, nó cũng được định nghĩa là một giao thức chịu trách nhiệm truyền tải dữ liệu một cách logic trong mạng. Các phân đoạn dữ liệu sẽ được đóng gói (Packets) với kích thước mỗi gói phù hợp với mạng chuyển mạch mà nó dùng để truyền dữ liệu. Lúc này, các gói tin được chèn thêm phần Header chứa thông tin của tầng mạng và tiếp tục được chuyển đến tầng tiếp theo. Các giao thức chính trong tầng là IP, ICMP và ARP.
####4. Lớp Physical
Là sự kết hợp giữa lớp Physical và lớp Data Link của mô hình OSI. Chịu trách nhiệm truyền dữ liệu giữa hai thiết bị trong cùng một mạng. Tại đây, các gói dữ liệu được đóng vào khung (gọi là Frame) và được định tuyến đi đến đích đã được chỉ định ban đầu.

