[Algo]
Thời gian: 90 minutes.
`Optimize thuật toán nhất có thể`
<br/>1. Tìm dãy con tăng liên tiếp dài nhất của 1 mảng cho trước. Ví dụ: [4, 3, 3, 5, 7, 8, 2] => [3, 5, 7, 8]
<br/>
<br/>2. Cho 2 dãy con tăng liên tiếp, gộp 2 dãy thành 1 dãy con tăng liên tiếp O(N)<br/>
[1, 3, 5, 6, 9],<br/>
[2, 4, 6, 8, 10]
<br/>
In ra: [1,2 ,3, 4, 5, 6, 7, 8, 9, 10]
<br/>
<br>
3. Có nhiều cách để mã hóa 1 chuỗi, trong đó có 1 cách như sau:
<br>Khi dãy con S xuất hiện K lần trong một chuỗi, chúng ta dùng K(S) để hiển thị giá trị.
<br>
<br>Ví dụ dãy hihihicohihihico = 2(3(hi)co)
Hoặc hihihico = 3(hi)co
<br></br>
<br>Input: 1 dãy S đã được mã hóa
<br>Output: trả về dãy ở trạng thái chưa được mã hóa.
<br>-Rằng buộc:
<br>•Độ dài của S nằm trong khoảng 1 -> 100
<br>•Dãy mã hóa chỉ bao gồm các số từ '0' -> '9', ngoặc '(', ')', và các kí tự thường (lower-case alphabet)
<br>•Độ dài của chuỗi trả về từ 1 -> 1000

 <br>Example:
 <br>Input: 2(3(hi)co)
 <br>Output: hihihicohihihico
 
