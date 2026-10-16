# Bài 2 : Chuẩn hóa tài liệu cài đặt hệ thống
##  *1.Báo cáo phân tích (I/O)*
-   Input: Văn bản Markdown gồm tiêu đề, câu lệnh, code Python, bảng và danh sách công việc
    
-   Output: Tài liệu hướng dẫn dễ đọc, có màu code, bảng so sánh và ô đánh dấu công việc

## *2. Source code*
Giá trị **do_am** cho biết độ ẩm đất. Nếu **do_am** < 30, hệ thống sẽ bật máy bơm

- Khối code Python
```python
do_am = 25
nguong_do_am = 30

if do_am < nguong_do_am:
    print("Bật máy bơm")
else:
    print("Tắt máy bơm")
```
---
- Bảng so sánh

|Tiêu chí|Cảm biến mới|Cảm biến cũ|
|-|-|-|
|Độ chính xác|Cao hơn|Thấp hơn
|Khả năng sử dụng|Ổn định hơn|Dễ gặp sự cố
|Chi phí|Cao|Thấp

---
- Task List kiểm tra thiết bị
- [ ] Kiểm tra dây nối cảm biến
- [ ] Kiểm tra nguồn điện
- [ ] Chạy thử code Python
- [ ] Kiểm tra máy bơm có bật, tắt đúng 
- [ ] Kiểm tra cảm biến đã đo được độ ẩm 

