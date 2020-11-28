###Lập trình trực quan là gì?

Thiết kế thường xuyên liên quan đến việc thiết lập các mối quan hệ trực quan, hệ thống, hoặc hình học giữa các bộ phận của một thiết kế. Nhiều lần hơn là không, những mối quan hệ này được phát triển bởi quy trình công việc giúp chúng ta từ khái niệm này sang kết quả bằng cách quy tắc. Có lẽ mà chúng ta không biết nó, chúng tôi đang làm việc theo thuật toán - xác định một bộ hành động từng bước tuân theo logic cơ bản của đầu vào, xử lý và đầu ra. Lập trình cho phép chúng tôi tiếp tục làm việc theo cách này nhưng bằng cách chính thức hóa các thuật toán của chúng tôi.
###Thuật toán trong tay
Trong khi cung cấp một số cơ hội mạnh mẽ, thuật ngữ **Algorithm** có thể mang theo một số quan niệm sai lầm với nó. Thuật toán có thể tạo ra những điều bất ngờ, tự nhiên hoặc thú vị, nhưng chúng không phải là phép thuật. Trong thực tế, nó khá công bằng. Hãy sử dụng một ví dụ hữu hình như cần xếp một origami. Chúng tôi bắt đầu với một mảnh giấy vuông (đầu vào), làm theo một loạt các bước gấp (hành động xử lý), và dẫn đến một kết quả là con hạc (đầu ra).
![Origami Crane](images/1-1/00-OrigamiCrane.png)

Vậy thuật toán ở đâu? Đó là tập hợp các bước trừu tượng, mà chúng ta có thể đại diện theo một vài cách - bằng văn bản hoặc đồ họa.

**Hướng dẫn bằng văn bản**
1. Bắt đầu với một mảnh giấy hình vuông,lật mặt màu lên trên. Gấp làm đôi mảnh giấy và mở ra. Sau đó gấp lại một nửa theo một hướng khác.
2. Lật mảnh giấy sang phía trắng. Gấp mảnh giấy làm đôi,đến khi có một nếp nhăn tốt và mở ra, sau đó gấp lại theo hướng khác.
4. Sử dụng các đường nếp gấp bạn đã thực hiện, Mang 3 góc trên cùng của mảnh giấy xuống góc dưới cùng. Duỗi thẳng mảnh giấy.
4. Gấp các cánh có hình tam giác trên cùng vào giữa và mở ra.
5. Gấp mặt trên của mảnh giấy xuống, để có một đường gấp tốt và mở ra.
6. Mở mảnh trên cùng của mảnh giấy đã gấp, đưa nó lên trên và nhấn hai bên của mảnh giấy vào trong cùng một lúc. Dẹt xuống để có một nếp gấp tốt.
7. Lật mô hình và lặp lại Bước 4-6 ở phía trên.
8. Gấp nếp trên vào giữa.
9. Lặp lại bước trên ở một mặt khác
10. Gấp cả hai 'chân' phía dưới của mảnh giấy lên, để có một nếp gấp tốt, sau đó mở ra.
11. Gấp các 'chân' bên trong ngược lại dọc theo các nếp gấp bạn vừa thực hiện.
12. Gấp các "Chân" hướng lên xuống bên dưới để tạo ra một cái đầu, sau đó gấp đôi cánh xuống.
13. Bây giờ bạn đã có một con hạc.

**Hướng dẫn minh họa:**

![Needs Update- Origami Crane](images/1-1/01-OrigamiCraneInstructions.png)

###Lập trình được định nghĩa
Sử dụng một trong hai bộ hướng dẫn này sẽ tạo ra một con hạc và nếu bạn tự theo dõi và làm điều đó, bạn đã áp dụng thuật toán. Sự khác biệt duy nhất là cách chúng ta đọc chính thức hóa bộ hướng dẫn đó và dẫn chúng ta đến **Programming**. Lập trình, thường được rút ngắn từ * Lập trình máy tính *, là hành động chính thức hóa của việc xử lý một loạt các hành động thành một chương trình thực thi. Nếu chúng ta biến các hướng dẫn ở trên cho một con hạc tạo thành một định dạng máy tính của chúng tôi có thể đọc và thực hiện được, như vậy là chúng tôi đang lập trình..


Chìa khóa và rào cản đầu tiên mà chúng tôi sẽ tìm thấy trong lập trình, là chúng ta phải dựa vào một số hình thức trừu tượng để giao tiếp hiệu quả với máy tính của chúng tôi. Điều đó có dạng bất kỳ số lượng ngôn ngữ lập trình nào, chẳng hạn như JavaScript, Python hoặc C. Nếu chúng ta có thể viết ra một bộ cộng cụ lặp lại các hướng dẫn, như xếp origami một con hạc, chúng ta chỉ cần dịch nó cho máy tính. Chúng tôi đang trên con đường của chúng tôi để có máy tính có thể làm cho một con hạc hoặc thậm chí vô số các con hạc khác nhau, nơi mà mỗi con hạc thay đổi một chút chi tiết. Đây là sức mạnh của lập trình - máy tính sẽ liên tục thực hiện bất cứ nhiệm vụ, hoặc tập hợp các nhiệm vụ, chúng tôi gán cho nó, không chậm trễ và không có lỗi của con người.
####Định Nghĩa Lập Trình Trực Quan
>Tải xuống tệp ví dụ đi kèm với bài tập này(nhấp chuột phải và "Save Link As..."): [Visual Programming - Circle Through Point.dyn](datasets/1-1/Visual Programming - Circle Through Point.dyn). Danh sách đầy đủ các tệp ví dụ có thể được tìm thấy trong Phụ lục.

Nếu bạn được giao nhiệm vụ viết hướng dẫn gấp một con hạc origami, bạn sẽ làm như thế nào? Bạn sẽ tạo chúng bằng đồ họa, giấy hay một vài kết hợp của cả hai?

Nếu câu trả lời của bạn chứa đồ họa, thì ** Lập trình trực quan ** chắc chắn là dành cho bạn. Quá trình này về cơ bản là giống nhau cho cả Lập trình và Lập trình trực quan. Họ sử dụng cùng một khuôn khổ chính thức hóa; tuy nhiên, chúng tôi xác định các hướng dẫn và mối quan hệ của chương trình của chúng tôi thông qua giao diện người dùng đồ họa (hoặc "Trực quan"). Thay vì nhập văn bản bị ràng buộc bởi cú pháp, chúng tôi kết nối các nút đóng gói sẵn với nhau. Dưới đây là so sánh của cùng một thuật toán - "vẽ một vòng tròn qua một điểm" - được lập trình với các nút so với viết mã:
**Chương trình trực quan**

![Basic Visual Program ](images/1-1/03-BasicVisualProgram.png)

**Chương trình văn bản:**
```
myPoint = Point.ByCoordinates(0.0,0.0,0.0);
x = 5.6;
y = 11.5;
attractorPoint = Point.ByCoordinates(x,y,0.0);
dist = myPoint.DistanceTo(attractorPoint);
myCircle = Circle.ByCenterPointRadius(myPoint,dist);
```
Kết quả thuật toán của chúng tôi:

![Circle Through Point ](images/1-1/04-CircleThroughPoint.png)

Đặc điểm trực quan để lập trình theo cách như vậy làm giảm rào cản tham gia sử dung ngôn ngữ lập trình không thường xuyên với các nhà thiết kế. Dynamo nằm trong mô hình Lập trình trực quan, cũng như chúng ta sẽ thấy ở phần sau, chúng ta vẫn có thể sử dụng lập trình văn bản trong ứng dụng.
