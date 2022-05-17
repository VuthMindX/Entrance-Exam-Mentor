# Entrance exam for mentor

- Đối với câu hỏi lý thuyết, bạn viết ra một file .txt.
- Thời gian làm bài 2h
- Liên hệ TE đểấy link nộp bài nhé.
- Tạo 1 folder họ và tên, nộp toàn bộ source code và những file liên quan. 

### Kiến thức cơ bản về python

1. Tạo menu tương tác cho phép CRUD danh sách các sản phẩm


2. Có một file csv khoảng 400 dòng. Làm thế nào để insert một dòng mới ở dòng 200? (dữ liệu dòng 200 trở lên sẽ bị dòi xuống dòng 201 )

---

### OOP
1. Nêu sự khác biệt giữa 2 khái niệm Interface và Inheritance ở trong lập trình hướng đối tượng.

2. Lớp abstract là gì, nêu ví dụ.

---


### Thuật toán lý thuyết

Dãy số tự chọn
1. Giải thích sự khác nhau giữa merge sort/heap sort/quick sort (giải thích ngắn gọn)

2. Cài đặt thuật toán đếm bit 1 của các số từ 1 -> n. Độ phức tạp yêu cầu là O(n)

---

### Bài toán thực tế

Các câu sau sử dụng chung mô tả sau:  

Công ty ABC có các hai loại nhân viên: nhân viên gián tiếp và nhân viên trực tiếp, với các thông
tin sau: Mã , Tên , đơn vị, Mức lương. Công ty muốn thực hiện chấm công làm việc của mỗi nhân viên theo yêu cầu sau:

Nhân viên gián tiếp:
- Mỗi ngày công đi làm sẽ được tính hệ số là 1.
- Mỗi ngày nghỉ sẽ có 2 mức: nghỉ có lý do hệ số là 0.5, nghỉ không lý do hệ số là 0.

Nhân viên trực tiếp:

- Mỗi ngày công được tính theo ca làm việc: nếu làm Ca 1, hệ số là 1; Ca 2 hệ số là 1.5.
- Mỗi ngày nghỉ sẽ có 2 mức: nghỉ có lý do hệ số là 0.5, nghỉ không lý do hệ số là 0.
- Ngoài ra nhân viên trực tiếp còn có hệ số phụ cấp: 10%, 15% hoặc 20%.

Mỗi nhân viên sẽ có một danh sách chấm công ngày làm việc ( Ví dụ: ArrayList) tính từ ngày 1
của tháng cho đến hết tháng. (Lưu ý, danh sách chấm công chỉ lưu trữ số ngày chấm công trong
1 tháng, sang tháng mới sẽ trở lại từ đầu).  

Lương tháng của nhân viên sẽ được tính bằng tổng lương ngày (nếu là nhân viên trực tiếp thì
lương tháng sẽ có thêm hệ số phụ cấp); trong đó lương ngày được tính bằng Mức lương * hệ số
của ngày làm việc (hoặc nghỉ có lý do)

**Hãy**:
- Thiết kế cây kế thừa (mỗi node là một class gồm các method & attribute)
- Cài đặt các class đã thiết kế
- Giả sử có một list các nhân viên, tính lương cho từng người với một static method ở lớp nhân viên
