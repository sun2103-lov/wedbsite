Phân A
câu A1
    a) Khi bạn gõ https://shopee.vn vào trình duyệt và nhấn Enter, hãy liệt kê đúng thứ tự ít nhất 5 bước xảy ra (từ DNS lookup đến render).
    b) Trong DevTools của Chrome, tab Network cho thấy thông tin gì? Hãy mở một trang web bất kỳ, chụp screenshot tab Network và đánh dấu (vẽ mũi tên/khoanh tròn) vào:
    -Status Code của request đầu tiên
    -Tổng thời gian load trang
    -Một request trả về file CSS


    a)các bước xẩy ra:
        1.DNS Lookup (Phân giải tên miền):Trình duyệt cần tìm địa chỉ IP tương ứng với tên miền
        2.TCP Handshake (Thiết lập kết nối):Sau khi có IP, trình duyệt và máy chủ Shopee thiết lập kết nối tin cậy.
            Thực hiện quy trình bắt tay 3 bước (SYN, SYN-ACK, ACK)
            Đảm bảo kênh truyền dữ liệu ổn định    
        3.TLS/SSL Handshake (Bảo mật):Do sử dụng HTTPS, cần thiết lập lớp bảo mật giữa trình duyệt và máy chủ.
        4.HTTP Request & Response: Trình duyệt gửi yêu cầu để lấy nội dung trang web.
        5.Parsing & Rendering (Phân tích & hiển thị): Trình duyệt xử lý dữ liệu nhận được và hiển thị giao diện.   
    b)tab Network cho thấy
        -Tên file (Name): Danh sách các file HTML, CSS, JS, ảnh, API.
        -Trạng thái (Status): Kết quả của yêu cầu (Thành công, Lỗi, hoặc từ Cache).
        -Loại file (Type): Định dạng của tài nguyên được tải về.
        -Thời gian (Time/Waterfall): Quá trình tải mất bao lâu và diễn ra vào thời điểm nào.
        
câu A2
    Dùng < div class="header"> thay vì thẻ ngữ nghĩa < header>  
→ Google không nhận diện đây là phần đầu trang.
    Logo chỉ là < div>  
→ Nên dùng thẻ < h1> hoặc < a> để thể hiện tên thương hiệu, giúp SEO nhận diện rõ.
    Menu điều hướng dùng < div>  
→ Nên dùng < nav> và danh sách < ul>< li> để thể hiện cấu trúc menu.
   Tiêu đề sản phẩm dùng < div class="title">  
→ Nên dùng thẻ heading như < h2> để Google hiểu đây là tiêu đề nội dung quan trọng.

câu A3
[hộp 1]->div
[text A][text B]->span
[hộp 2]
[text C][text D]->text D đc in đậm 
[hộp 3]
câu A4
    -phân biệt
    < thead>	Header	Tiêu đề cột
    < tbody>	Body	Dữ liệu chính
    < tfoot>	Footer	Tổng kết
    -vì 
    +< table> chỉ dùng cho dữ liệu dạng bảng (danh sách, so sánh, thống kê)
    +layout  khó thay đổi kích thước linh hoạt trên các thiết bị khác nhau
    +chỉnh sửa layout bằng bảng khó khăn
