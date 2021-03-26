[Algo]
Thời gian: 60 -> 90 minutes.
`Optimize thuật toán nhất có thể`
<br/>1. Tìm dãy con tăng liên tiếp dài nhất của 1 mảng cho trước. Ví dụ: [4, 3, 3, 5, 7, 8, 2] => [3, 5, 7, 8]
<br/>2. Cho mảng chứa lịch họp trong công ty bao gồm startTime/endTime.<br/> Output: hợp nhất lại lịch họp của công ty
  ```
  [
    Meeting(startTime: 0,  endTime: 1),
    Meeting(startTime: 3,  endTime: 5),
    Meeting(startTime: 4,  endTime: 8),
    Meeting(startTime: 10, endTime: 12),
    Meeting(startTime: 9,  endTime: 10)
]
```
=>
```
   [
    Meeting(startTime: 0, endTime: 1),
    Meeting(startTime: 3, endTime: 8),
    Meeting(startTime: 9, endTime: 12)
]
```
<br/>
Giải thích<br/>
- [Meeting(startTime: 3,  endTime: 5), Meeting(startTime: 4,  endTime: 8)]
hợp lại thành Meeting(startTime: 3, endTime: 8)
<br/>
- Meeting(startTime: 10, endTime: 12), Meeting(startTime: 9,  endTime: 10) hợp lại thành Meeting(startTime: 9, endTime: 12)
<br/>3. Cho 1 mảng gồm n phần tử hiển thị giá của stock theo trục thời gian 1 -> n. Tìm max profit nếu 1 user mua và bán trong cùng ngày (chú ý thời điểm mua phải diễn ra trước và không trùng với thời điểm bán). (Ví dụ: [1, 4, 5, 6, 2, 3]) => max profit: 5 (mua 1 bán 6)
 