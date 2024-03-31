
GocMod
Nguyên2006
Nguyên2006
Mua VIP Member ủng hộ Forum cũng như tắt quảng cáo trên diễn đàn bạn nhé.
 Thủ thuật hay
Chia sẻ Viettel vào mạng miễn phí 2024
 Người tạo chủ đềThuan567  Ngày bắt đầu6/2/24

Đi đến bài mới
Theo dõi
Thuan567
Thuan567
Xem chùa 👀

6/2/24
Thêm dấu trang
#1
Như các bài viết trước của mình chia sẻ file để sử dụng internet viettel miễn phí tốc độ rất chậm nên nay mình mod lại để cải thiện tốc độ internet
Phiên bản này mình mod lại tại nguồn https://github.com/aztecrabbit/brainfuck-psiphon-pro-go
Các tính năng của phiên bản Psiphon đường hầm Brainfuck
Sử dụng trạng thái ngẫu nhiên làm trình kích hoạt kết nối (mặc định) nhưng có thể được đặt thành cấu hình
Kết nối lại sau khi đạt 4,2 MB (mặc định) để cải thiện tốc độ.

#####Cài đặt như sau:
B1" mở Termux (link tải https://www.mediafire.com/file/c5e5hzsnibhyx9p/Termux_0.119.1_thuanht567.apk yêu cầu phiên bản MỚI NHẤT Termux 119 các phiên bản khác sẽ bị thiếu các gói nên xuất hiện lỗi và không thể cài đặt thành công ) chạy lệnh sau:
Chú ý chọn 1 trong 2 lệnh cài đặt dưới:
--**Lệnh 1 tự động cài xong chỉ dùng được chương trình Brainfuck tunnel:


bash <(curl -fsSL https://raw.githubusercontent.com/thuanht567/v2/main/install567.sh)

bash <(curl -fsSL https://raw.githubusercontent.com/Kiyoshi2006/v2/main/install567.sh)


-**Lệnh 2 cài xong phải nhập " t " để chạy Brainfuck tunnel khi không dùng vẫn dùng được termux bình thường


bash <(curl -fsSL https://raw.githubusercontent.com/thuanht567/v2/main/567ta.sh)

+++ GỠ termux trước đó và cài đặt lại để tránh xung đột, lệnh cập nhật ngày 3/3/2024
-
***
B2 mở app nekobox (link tải
play.google.com
NekoBox for Android - Apps on Google Play
sing-box / universal proxy toolchain for Android
play.google.com play.google.com
Tải cấu hình socks
github.com
v2/psi-termux-Thuan567.json at main · thuanht567/v2
Contribute to thuanht567/v2 development by creating an account on GitHub.
github.com github.com
và
Cài đặt - app vpn mode - bybass - Termux

%##Bybass mới kết nối được app termux nhé


####SỬ DỤNG

BƯỚC 1 -mở app Termux:
với lệnh cài đặt 1 khi mở app Termux không cần gõ lệnh tự động chạy Brainfuck tunnel và chạy nekobox

+Với lệnh cài đặt 2:
Bash:
Mã:
 t

Với lệnh cài đặt 2
Gõ " t " enter để chạy Brainfuck tunnel



BƯỚC 2- mở app Nekobox chọn cấu hình Socks để kết nối.
***@ khuyên dùng Nekobox để k lỗi mạng ví dụ một số app k có mạng

∆// 2 app phải sử dụng song song và chương trình Brainfuck tunnel phải được bật
$% để thoát Brainfuck tunnel nhất Ctrl+c
-------------∆∆---------
*Fix lỗi termux tự thoát
*Fix lỗi listen tcp 0.0.0.0:8989: bind: address already in use
*Fix lỗi listen tcp 0.0.0.0:1080: bind: address already in use
**không cần gõ: tun
** không cần gõ: 4ghack
** đã fix:: fatal error: concurrent map writes
--*chưa fix lỗi cuộc gọi zalo

*****"%% vì là server miễn phí chỉ có 1 đến 2 + do số người dùng truy cập nhiều nên mạng có lúc sẽ load chậm( mình sẽ k build thêm server nữa trừ khi ai donate cho mình 🤣😎)
*** Bản mod build từ nguồn https://github.com/aztecrabbit/brainfuck-psiphon-pro-go ..

©®Duy nhất đăng trên diễn đàn Gocmod các trang hội nhóm khác đăng lại các lệnh cài đặt và sử dụng k phải bản mới nhất chưa dc fix các lỗi.

Vì là mã nguồn mở nhưng copy lại nhớ ghi nguồn Thuan567 nhé!🤩


Xin lưu ý: Phương pháp VPN này rất chậm ∆

một giao thức chống kiểm duyệt, mã hóa lưu lượng dưới dạng các yêu cầu và phản hồi HTTP đơn giản. Điều này cho phép lưu lượng truy cập thâm nhập vào các môi trường mà nếu không nó sẽ bị chặn.

Hiệu suất của nó là thấp. Nó không dành cho các tình huống mà bạn muốn ping nhanh hoặc truyền hàng gigabyte và gigabyte dữ liệu.
