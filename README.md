READ ME </br>
Làm sao để chạy code </br>
Bước 1: pip install Django</br>
Bước 2: pip install xhtml2pdf</br>
Bước 3: pip install django-widget-tweaks</br>
Bước 4: python manage.py makemigrations </br>
Bước 5: python manage.py migrate</br>

Lưu ý : Phải tạo admin trước để đăng nhập import dữ liệu !!!!!!!!!</br>
ACCOUNT Admin </br>
Bước 6: python manage.py createsuperuser</br>
Điền thông tin mail (fake)
user name : (tên gì cũng được) - vd: hp</br>
email: Của thầy </br>
password : 123 - sau đó (Nhấn Y đồng ý)</br>

Bước 7: python manage.py runserver</br>
Sau khi vào admin import các file sau đây để có dữ liệu:</br>
- Vào Product (Nhấn vào dấu "+" màu XANH): import file tên "real_100_products.csv" (dữ liệu sản phẩm)</br>
- Vào Transaction: import file "generated_transactions_rich.csv" (dữ liệu mua hàng)</br>
- Chạy Basket Market để tìm tập phổ biến cực đại</br>
- Chạy Mafia Recommend để sinh luật kết hợp</br>

Bước 8: Qua một trình duyệt mới copy đường link để test "http://127.0.0.1:8000/"</br>
- Sign up user mới</br>
- Lựa chọn sản phẩm theo luật đã có</br>
LƯU Ý: PHẢI THANH TOÁN THÀNH CÔNG MỚI CÓ SẢN PHẨM GỢI Ý!!!!!!!!</br>
