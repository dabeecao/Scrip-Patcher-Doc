# Scrip-Patcher-Doc
#  BundleID
    ID của ứng dụng
#  Sytle
    Nếu Type == "D" thì sẽ chép vào $app/Documents"
    Nếu Type == "L" thì sẽ chép vào $app/Library"
    Nếu Type == "LP" thì sẽ chép vào $app/Library/Preferences"
    Nếu Type == "D/L" thì sẽ chép vào thư mục data gốc của ứng dụng
#  Name
    Tên ứng dụng
#  No_Backup
    Y == Không tạo bản sao lưu
    N == Tạo bản sao lưu
#  Work_Version
    Phiên bản mà Savegame hỗ trợ
    A == Tất cả phiên bản đều hỗ trợ
#  Trong Control
    kurd-patcher "tenhack" "i" == sử dụng trong postinst khi cài
    kurd-patcher "tenhack" "r" == sử dụng trong postrm khi gỡ
    Thêm >>dev/null sau 2 lệnh trên nếu muốn ẩn quá trình chạy lệnh. VD: kurd-patcher "tenhack" "i" >>dev/null
