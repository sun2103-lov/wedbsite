Phân A
câu A1
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
        chú thích bên ảnh chụp màn hình : 
            blu:Status Code của request đầu tiên
            red:Tổng thời gian load trang
            yellow: Một request trả về file CSS
        
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
    hộp 3]

câu A4
    -phân biệt
        < thead>	Header	Tiêu đề cột
        < tbody>	Body	Dữ liệu chính
        < tfoot>	Footer	Tổng kết
    -vì 
         +< table> chỉ dùng cho dữ liệu dạng bảng (danh sách, so sánh, thống kê)
        +layout  khó thay đổi kích thước linh hoạt trên các thiết bị khác nhau
        +chỉnh sửa layout bằng bảng khó khăn

câu B3
    Lỗi 1: Dòng 1 — Sai DOCTYPE — Sửa thành <!DOCTYPE html>
    Lỗi 2: Dòng 4 — <title> không đóng — Thêm </title>
    Lỗi 3: Dòng 5 — Sai utf8 — Sửa thành utf-8
    Lỗi 4: Dòng 9 — <h1> không đóng — Sửa thành <h1>...</h1>
    Lỗi 5: Dòng 13 — <a> không đóng — Thêm </a>
    Lỗi 6: Dòng 13 — Link sai — Sửa href="home" → href="#home"
    Lỗi 7: Dòng 22 — Đóng thẻ sai — Sửa thành <p>Giá: <b>...</b></p>
    Lỗi 8: Dòng 36 — Footer chưa đóng — Thêm </p> và </footer>
    
