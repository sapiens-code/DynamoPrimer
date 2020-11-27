# The Dynamo Primer

## Đối với Dynamo v2.0
Tải về tại [Dynamo v1.3 Primer](http://primer.dynamobim.org/en/Appendix/DynamoPrimer-Print1_3.pdf)

![Dynamo Logo](images/dynamo_logo_dark-trim.jpg)

> Dynamo là một nền tảng lập trình trực quan giành cho các nhà thiết kế.

### Chào mừng
Chào mừng bạn đến với Dynamo Primer, một hướng dẫn toàn diện về lập trình trực quan trong Autodesk Dynamo Studio.Bản sơ lược này là một dự án chia sẻ các nguyên tắc cơ bản về lập trình. Chủ để bao gồm làm việc với hình học tính toán, các phương pháp hay nhất dựa trên thiết kế, các ứng dụng lập trình đa dạng, và nhiều hơn thế nữa với nền tảng Dynamo.

Sức mạnh của Dynamo có thể được tìm thấy trong rất nhiều hoạt động liên quan đến thiết kế. Dynamo cho phép mở rộng danh sách các cách dễ tiếp cận để bạn bắt đầu:
* **Khám phá** lập trình trực quan lần đầu tiên.
* **Kết nối** quy trình làm việc trong các phần mềm khác nhau
* **Hứa hẹn** một cộng đồng người dùng, cộng tác viên và nhà phát triển tích cực
* **Phát triển** một nền tảng mã nguồn mở để tiếp tục cải tiến.

In the midst of this activity and exciting opportunity for working with Dynamo, we need a document of the same caliber, the Dynamo Primer.

Primer này bao gồm các chương được phát triển bằng Mode Lab. Các chương này tập trung vào những điều cơ bản bạn cần để bắt đầu và vận hành phát triển các chương trình trực quan của riêng mình với Dynamo và những hiểu biết chính về cách đưa Dynamo tiến xa hơn. Dưới đây là những gì bạn có thể học được từ Primer:

* **Định Nghĩa** - Chính xác thì "Lập trình trực quan" là gì và những khái niệm tôi cần hiểu để đi sâu vào Dynamo là gì?
* **Bắt Đầu** - Làm cách nào để tải về Dynamo và tạo chương trình đầu tiên của tôi?
* **Có Gì Bên Trong Một Chương Trình** - Các chức năng của Dynamo là gì và làm cách nào để có thể sử dụng chúng?
* **Các Khu Của Tòa Nhà** - "Dữ liệu" là gì và một số kiểu dữ liệu cơ bản mà tôi có thể bắt đầu sử dụng trong các chương trình của mình là gì?
* **Hình học cho thiết kế** - Làm cách nào để làm việc với các yếu tố hình học trong Dynamo?
* **Danh sách, danh sách, danh sách** - Làm cách nào để quản lý và điều phối cấu trúc dữ liệu của tôi?
* **Mã Trong Nút** - Làm cách nào để bắt đầu mở rộng Dynamo bằng cách viết mã của riêng tôi?
* **BIM Tính Toán** - Làm cách nào để sử dụng Dynamo với mô hình Revit?
* **Custom Nodes** - Làm cách nào để tạo các nút (Nodes) của riêng tôi?
* **Packages** - Làm cách nào để chia sẻ các công cụ (Packages) của tôi với cộng đồng?

Đây là thời điểm thú vị để tìm hiểu, làm việc và phát triển cho Dynamo. Bắt đầu nào!

---

### Mã Nguồn Mở
Dự án Dynamo Primer là dự án mã nguồn mở! Chúng tôi tận tâm cung cấp nội dung chất lượng và đánh giá cao mọi phản hồi mà bạn có thể có. Nếu bạn muốn báo cáo sự cố về bất cứ điều gì, vui lòng đăng chúng trên trang sự cố GitHub của chúng tôi: https://github.com/DynamoDS/DynamoPrimer/issues

Nếu bạn muốn đóng góp một phần mới, chỉnh sửa hoặc bất kỳ điều gì khác cho dự án này, hãy xem repo GitHub để bắt đầu: https://github.com/DynamoDS/DynamoPrimer.

---
### Về Dự án Dynamo Primer
Dynamo Primer là một dự án mã nguồn mở, được khởi xướng bởi Matt Jezyk và nhóm phát triển Dynamo tại Autodesk.

**Mode Lab** đã được giao nhiệm vụ khởi xướng phiên bản đầu tiên của Primer. Chúng tôi cảm ơn họ vì tất cả những nỗ lực của họ trong việc thiết lập nguồn tài nguyên quý giá này.

[<img src="images/MODELAB_Logo.png">](http://modelab.is)

**John Pierson Của Parallax Team** đã được ủy nhiệm cập nhật lớn cho Primer để phản ánh các vấn đề với Dynamo 2.0, các bản sửa đổi.

[<img src="images/PRLX_Logo.jpg">](http://www.parallaxteam.com/)
### Sự biết ơn

Đặc biệt cảm ơn Ian Keough vì đã khởi xướng và hướng dẫn dự án Dynamo.

Cảm ơn Matt Jezyk, Ian Keough, Zach Kron, Racel Williams và Colin McCrone đã nhiệt tình cộng tác và có cơ hội tham gia vào nhiều dự án Dynamo.

### Phần mềm và Tài nguyên
**Dynamo** Phiên bản Dynamo * ổn định hiện tại là Phiên bản 2.1.0

http://dynamobim.com/download/ hoặc http://dynamobuilds.com

*Ghi chú: Bắt đầu với Revit 2020, Dynamo đi kèm với các bản phát hành Revit, do đó không cần cài đặt thủ công. Để biết thêm thông tin, có thể truy cập tại đây [Bài đăng trên blog](https://dynamobim.org/dynamo-core-2-1-release/).

**DynamoBIM** Là nguồn tốt nhất cho thông tin bổ sung, nội dung học tập và diễn đàn là trang web DynamoBIM.

http://dynamobim.org

**Dynamo GitHub** Dynamo là một dự án phát triển mã nguồn mở trên GitHub. Để đóng góp, hãy xem DynamoDS.

https://github.com/DynamoDS/Dynamo

**Contact** Hãy cho chúng tôi biết về bất kỳ vấn đề nào với tài liệu này.

Dynamo@autodesk.com

### Giấy phép
Bản quyền 2019 Autodesk

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép"); bạn không thể sử dụng tệp này trừ khi tuân theo Giấy phép. Bạn có thể nhận được một bản sao của Giấy phép tại

http://www.apache.org/licenses/LICENSE-2.0

Trừ khi được yêu cầu bởi luật hiện hành hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ ĐẢM BẢO HOẶC ĐIỀU KIỆN BẤT KỲ HÌNH THỨC NÀO, dù rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn điều chỉnh ngôn ngữ cụ thể theo Giấy phép.
