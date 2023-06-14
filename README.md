# timelist
CTDL ontap linkedlist
Viết chương trình quản lý THỜI GIAN bằng danh sách liên kết đơn. Biết rằng mỗi một thời gian sẽ chứa thông tin giờ - phút - giây

Trong đó, thời gian sẽ được tối giản theo qui ước 1 giờ = 60 phút, 1 phút = 60 giây, và giờ sẽ không vượt quá 24h

VD: 24h 70p 70s --> 1h 11p 10s

INPUT
Dãy các số nguyên trong đó: (Giả sử luôn thỏa điều kiện nhập)

Số nguyên đầu tiên n là: số lượng thời gian trong danh sách
n dòng tiếp theo, mỗi dòng chứ 03 số nguyên lần lượt là giờ - phút - giây của một thời gian trong danh sách
OUTPUT
Xuất ra tất cả thời gian trong danh sách đã được tối giản theo qui ước trên.

EXAMPLE
Input    

0	     
Output  
1

2 20 60	

	Output  
 
 2h21p0s

4

2 60 30

2 30 60

2 60 70

24 70 70 

Output  

1h11p10s

3h1p10s

2h31p0s

3h0p30s
