
Cho ma trận $N \times N$ biểu thị kết quả thắng/thua của các trận đấu với $A_{ij}$ là kết quả của trận đội $i$ gặp đội $j$ và $A_{ji}$ sẽ ngược lại.

Nhưng có một đội tuyển $K$ đã "vô tình" được một công ty tài trợ của mình thay đổi kết quả thành toàn thua để có được tiền cá độ tốt nhất.

![](https://i.imgur.com/jg2BDUM.jpg)

Bạn là người của công ty đó và được giao việc là phải xác định sẽ thay đổi kết quả của trận nào để được số tiền nhiều nhất.

Số tiền thu được từ cá độ sẽ được quyết định nhờ vào tỷ lệ trận thắng thua của 2 đội. Đội thua càng nhiều thì khi thắng sẽ được tiền độ càng cao.

Bạn phải xác định thay đổi kết quả của trận nào để có kết quả tốt nhất và in ra đội sẽ phải thay đổi kết quả.

## Input

- Dòng đầu tiên gồm 2 số nguyên $N$ ($2 \le N \le 1000$) và $K$ ($1 \le K \le N$)
- $N$ dòng tiếp, mỗi dòng gồm $N$ số $A_{ij}$ hoặc là $1$ và $0$ với ý nghĩa đội $i$ đã thắng hay thua đội $j$

## Output

- Dòng đầu tiên in ra 1 số nguyên $B$ là số trận phải thay đổi kết quả.
- $B$ dòng tiếp theo, mỗi dòng in ra $2$ số nguyên $i$, $j$ biểu thị trận $A_{ij}$ phải thay đổi kết qủa
