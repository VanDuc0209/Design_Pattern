# Design Pattern là gì?

**Design Patterns** là những giải pháp điển hình cho các vấn đề thường gặp trong thiết kế phần mềm. Chúng giống như những bản thiết kế có sẵn mà bạn có thể tùy chỉnh để giải quyết một vấn đề lặp đi lặp lại trong mã nguồn của mình.

Bạn không thể chỉ tìm một Design Pattern và sao chép nó vào chương trình của mình như cách bạn làm với các hàm hoặc thư viện có sẵn. Design Pattern không phải là một đoạn mã cụ thể, mà là một khái niệm chung để giải quyết một vấn đề nhất định. Bạn có thể làm theo các chi tiết của Design Pattern và triển khai một giải pháp phù hợp với thực tế của chương trình của mình.

Mọi người thường nhầm lẫn giữa Design Patterns và thuật toán vì cả hai đều mô tả các giải pháp điển hình cho những vấn đề đã biết. Tuy nhiên, thuật toán luôn xác định một tập hợp hành động rõ ràng để đạt được một mục tiêu, trong khi Design Pattern là một mô tả ở cấp độ cao hơn về một giải pháp. Mã nguồn áp dụng cùng một Design Pattern trong hai chương trình khác nhau có thể hoàn toàn khác nhau.

Một phép so sánh đơn giản là: thuật toán giống như một công thức nấu ăn – cả hai đều có các bước cụ thể để đạt được một mục tiêu. Trong khi đó, Design Pattern giống như một bản thiết kế – bạn có thể hình dung được kết quả và các đặc điểm của nó, nhưng cách thực hiện cụ thể là tùy thuộc vào bạn.

## Design Pattern bao gồm những gì?

Hầu hết các Design Patterns được mô tả một cách chính thức để mọi người có thể tái sử dụng chúng trong nhiều ngữ cảnh khác nhau. Dưới đây là các phần thường có trong mô tả của một Design Pattern:

- **Intent**: Mô tả ngắn gọn về vấn đề mà Design Pattern giải quyết và cách thức giải quyết.
- **Motivation**: Giải thích chi tiết hơn về vấn đề và cách mà Design Pattern giúp giải quyết vấn đề đó.
- **Structure**: Mô tả các lớp (class) trong Design Pattern và mối quan hệ giữa chúng.
- **Code example**: Đoạn mã minh họa bằng một trong các ngôn ngữ lập trình phổ biến để giúp dễ hiểu hơn về cách hoạt động của Design Pattern.

# Lịch sử của Design Pattern

### Ai đã phát minh ra Design Patterns?

Design Patterns không phải là những khái niệm phức tạp hay bí ẩn—thực tế hoàn toàn ngược lại. Chúng là những giải pháp điển hình cho các vấn đề phổ biến trong thiết kế hướng đối tượng. Khi một giải pháp được lặp đi lặp lại trong nhiều dự án, cuối cùng ai đó sẽ đặt tên cho nó và mô tả chi tiết. Đó chính là cách một Design Pattern được khám phá.

Khái niệm về "pattern" lần đầu tiên được mô tả bởi Christopher Alexander trong cuốn sách **A Pattern Language: Towns, Buildings, Construction**. Ý tưởng này sau đó được bốn tác giả Erich Gamma, John Vlissides, Ralph Johnson, và Richard Helm áp dụng vào lập trình. Năm 1994, họ xuất bản cuốn sách **Design Patterns: Elements of Reusable Object-Oriented Software**, trong đó mô tả 23 Design Patterns giúp giải quyết các vấn đề khác nhau trong thiết kế hướng đối tượng. Cuốn sách này nhanh chóng trở thành một best-seller và được gọi tắt là "GoF book" (cuốn sách của Gang of Four).

Kể từ đó, hàng chục Design Patterns khác đã được khám phá, và phương pháp tiếp cận dựa trên Design Patterns trở nên phổ biến trong nhiều lĩnh vực lập trình.

# Tại sao chúng ta nên học về Design Pattern?

Bạn có thể làm lập trình viên trong nhiều năm mà không cần biết đến một Design Pattern nào. Nhưng ngay cả trong trường hợp đó, bạn có thể đã vô tình áp dụng một số Design Patterns mà không hề nhận ra. Vậy tại sao bạn nên dành thời gian để học chúng?

- **Giải pháp tối ưu**: Design Patterns là một bộ công cụ gồm những giải pháp đã được kiểm chứng để giải quyết các vấn đề phổ biến trong thiết kế phần mềm.
- **Cải thiện kỹ năng lập trình**: Biết về Design Patterns giúp bạn học cách giải quyết nhiều loại vấn đề bằng các nguyên tắc của lập trình hướng đối tượng.
- **Giao tiếp hiệu quả hơn**: Design Patterns tạo ra một ngôn ngữ chung giúp bạn và đồng đội giao tiếp dễ dàng. Bạn có thể nói: “Cứ dùng Singleton cho cái này đi”, và mọi người sẽ hiểu ngay ý tưởng mà không cần giải thích Singleton là gì.

# Phân loại các Design Pattern

Design Patterns khác nhau về mức độ phức tạp, mức độ chi tiết và phạm vi áp dụng trong toàn bộ hệ thống được thiết kế. Một cách để phân loại chúng là theo **mức độ ứng dụng**:

- **Idioms**: Những Design Patterns cơ bản, có phạm vi hẹp, thường chỉ áp dụng cho một ngôn ngữ lập trình cụ thể.
- **Architectural patterns**: Những Design Patterns có tính phổ quát cao, có thể triển khai trong hầu hết các ngôn ngữ lập trình và thường được sử dụng để thiết kế kiến trúc của toàn bộ ứng dụng.

Ngoài ra, Design Patterns còn được phân loại theo **mục đích sử dụng** thành ba nhóm chính:

1. **Creational patterns**: Cung cấp các cơ chế tạo đối tượng giúp tăng tính linh hoạt và khả năng tái sử dụng mã nguồn.
2. **Structural patterns**: Giải thích cách tổ chức và liên kết các đối tượng, lớp thành những cấu trúc lớn hơn mà vẫn đảm bảo tính linh hoạt và hiệu quả.
3. **Behavioral patterns**: Quản lý cách các đối tượng giao tiếp với nhau và phân công trách nhiệm giữa chúng một cách hiệu quả.

---

Design Patterns là một công cụ mạnh mẽ giúp lập trình viên viết mã tốt hơn, hiệu quả hơn và dễ bảo trì hơn. Việc hiểu và áp dụng đúng Design Patterns sẽ giúp bạn nâng cao kỹ năng lập trình và làm việc chuyên nghiệp hơn trong các dự án phần mềm.