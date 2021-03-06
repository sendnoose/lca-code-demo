# lca-code-demo
Mã nguồn C++ cho phần thuyết trình của **nhóm 6 - 19CNTN ĐH KHTN, ĐHQG TP.HCM** trong môn **Nhập môn tư duy thuật toán** về chủ đề **Lowest Common Ancestor (LCA)** , bao gồm:

- 19120159 – Trần Huy Vũ
- 19120405 – Nguyễn Đình Trí
- 19120449 – Nguyễn Phan Đức Anh
- 19120726 – Nguyễn Vân Huy Vũ

Mã nguồn bao gồm cài đặt của 3 thuật toán giải bài toán tìm LCA -- Lowest Common Ancestor hay đỉnh tổ tiên gần nhất.

Mã nguồn sử dụng class `Tree` là đối tượng cơ sở biểu diễn cho một cây theo dạng danh sách liên kết (thật ra là nhiều mảng đơn chứa các chiều cao, đỉnh cha và danh sách các con).

Ba thuật toán có cách cài đặt riêng được chứa lần lượt trong ba file `LCAnaive.h`, `LCAsqrt.h`, `LCAbyRMQ.h`. Hiên tại mỗi hàm truy vấn LCA sẽ thực hiện cả bước tiền xử lý và bước truy vấn. Bạn có thể tuỳ biến các hàm này thành phương thức trong class Tree để vận dụng tối đa khả năng tiền xử lý cây một lần mà truy vấn được nhiều lần.

File `test.cpp` bao gồm mã chạy LCA bằng 3 thuật toán trên cây sau đây:
![Cây có 16 đỉnh dùng làm ví dụ](https://github.com/sendnoose/lca-code-demo/blob/main/tree_in_test_cpp.png?raw=true)

Nguồn tham khảo:
1. [cp-algorithms.com/graph/lca.html](https://cp-algorithms.com/graph/lca.html)
2. [github.com/e-maxx-eng](http://github.com/e-maxx-eng)
3. [vnoi.info/wiki/translate/topcoder/Range-Minimum-Query-and-Lowest-Common-Ancestor.md](https://vnoi.info/wiki/translate/topcoder/Range-Minimum-Query-and-Lowest-Common-Ancestor.md)
