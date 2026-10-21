# Lặp lại và cải thiện prompt

Nguồn: https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-3-prompt-iteration

**Miền:** 1  
**Nhiệm vụ:** 1.3

## Những điều bạn cần biết

Đầu ra đầu tiên là câu trả lời đầu tiên của Claude cho prompt; đó là bản nháp. Prompt giao nhiệm vụ là bản giao việc. Phản hồi là tin nhắn tiếp theo bạn gửi về đầu ra. Lặp lại là chu trình gồm đầu ra, phản hồi cụ thể và đầu ra tốt hơn. Đây là nhịp làm việc bình thường, không phải dấu hiệu thất bại. Hướng dẫn bắt đầu sử dụng của Trung tâm Trợ giúp nói rõ: đừng ngần ngại tinh chỉnh prompt hoặc đặt câu hỏi tiếp theo. Những người tận dụng Claude tốt nhất dành sẵn một hoặc hai lượt phản hồi cho mỗi nhiệm vụ. Những người tận dụng ít nhất thì chấp nhận ngay lần thử đầu tiên còn tầm thường, hoặc bỏ công cụ sau một lần thử.

Tại một phòng khám nha khoa, người quản lý yêu cầu Claude viết thư nhắc bệnh nhân đến hạn khám định kỳ. Bản nháp có đủ các phần cần thiết nhưng cứng nhắc, quá dài và đầy thuật ngữ lâm sàng.

## Phản hồi nêu rõ khoảng trống

Trung tâm Trợ giúp nêu phản hồi là một cách chính thức để khắc phục câu trả lời không hữu ích: đưa ra chỉ dẫn tiếp theo, làm rõ hoặc yêu cầu viết lại. “Làm hay hơn rồi thử lại” sẽ tái tạo vấn đề, vì cuộc trò chuyện không có thêm thông tin mới. Giả sử người quản lý viết: “Rút xuống còn 200 từ, giữ lại đoạn về phí và bỏ các tính từ quảng cáo.” Cách này hiệu quả vì mỗi vế đều nêu rõ một điểm cần sửa.

Phản hồi tốt thực hiện một trong ba việc:

- Bổ sung một giới hạn còn thiếu, chẳng hạn đối tượng đọc, định dạng hoặc điều cần tránh.
- Sửa một cách hiểu sai.
- Thu hẹp phạm vi.

Cả ba đều bắt đầu bằng việc chẩn đoán. Hãy xác định khoảng cách giữa đầu ra và nhu cầu, sau đó nói rõ ràng. Một cách nhanh là đối chiếu đầu ra với năm thành phần trong bản giao việc ban đầu. Khoảng trống thường nằm ở thành phần còn sơ sài hoặc bị thiếu. Prompt một dòng của người quản lý chưa nêu đối tượng đọc.

Yêu cầu các phương án khác nhau cũng là một hình thức lặp lại. Người quản lý có thể yêu cầu ba phiên bản đoạn mở đầu: trang trọng, thân mật và khẩn thiết. Claude trở thành công cụ tạo phương án còn người quản lý làm giám khảo. Đây thường là con đường nhanh nhất để tìm được cách diễn đạt phù hợp khi bạn biết có điều gì đó chưa ổn nhưng chưa thể gọi tên.

## Tinh chỉnh hay giao việc lại?

Khi đầu ra đã gần đạt yêu cầu, hãy tinh chỉnh. Tiếp tục trong cuộc trò chuyện hiện tại và gửi yêu cầu tiếp theo có trọng tâm. Đôi khi, đầu ra cho thấy prompt ban đầu sai: sai nhiệm vụ, sai cách định hướng hoặc thiếu bối cảnh. Khi đó, hãy viết lại bản giao việc và bắt đầu sạch từ đầu, thay vì cố vá một cách hiểu sai qua sáu lượt trao đổi. Chuỗi sửa đổi dài làm ngữ cảnh mà cuộc trò chuyện duy trì trở nên rối. Mỗi lần vá cũng phải chống lại cách định hướng ban đầu thay vì sửa tận gốc.

Việc phán đoán sai có thể theo cả hai hướng. Một là liên tục vá bản giao việc vốn yêu cầu sai thứ. Hai là bỏ cuộc trò chuyện dù chỉ cần sửa một điểm cụ thể là xong. Nếu thư của người quản lý chỉ cần dùng từ ngữ giản dị hơn, một yêu cầu tiếp theo là đủ.

## Ba cách xử lý bản nháp gây thất vọng

Với bản nháp có cấu trúc ổn nhưng chưa đúng mục tiêu, có ba cách xử lý. Yêu cầu thử lại một cách mơ hồ như “chưa đúng lắm, thử lại đi” sẽ tạo ra thiếu sót tương tự vì cuộc trò chuyện không có thông tin mới. Yêu cầu tiếp theo có trọng tâm sẽ nêu rõ giọng điệu, các cụm từ cần tránh và đối tượng đọc. Cách này tạo ra bản sửa có thể dùng được vì mỗi khoảng trống được nêu ra cho Claude một mục tiêu cụ thể. Người quản lý nêu rõ cần giọng ấm áp, không dùng thuật ngữ lâm sàng và viết cho bệnh nhân.

Cách thứ ba là giao việc lại, dùng khi bản giao việc ban đầu là vấn đề thực sự. Một prompt hiệu quả cung cấp càng nhiều ngữ cảnh càng tốt, trong khi prompt một dòng cung cấp rất ít. Hãy giao việc lại cho đầy đủ, đính kèm hướng dẫn phong cách và nêu đối tượng đọc ngay từ đầu. Cách này sửa được đợt hiện tại và cải thiện mọi đợt tiếp theo.

## Giữ lại cách diễn đạt đã hiệu quả

Khi hai lượt phản hồi giúp đầu ra đạt yêu cầu, chính phản hồi đã sửa được bản nháp là chỉ dẫn còn thiếu trong prompt ban đầu. Hãy đưa nó trở lại prompt để prompt có thể tái sử dụng, giúp lần chạy tiếp theo bắt đầu từ nền tảng tốt hơn thay vì làm lại từ đầu. Đợt tiếp theo của người quản lý sẽ bắt đầu bằng prompt nêu rõ giọng điệu, cách dùng từ giản dị và đối tượng bệnh nhân.

## Trong kỳ thi

Kỳ thi kiểm tra chất lượng phản hồi và xếp hạng ba cách xử lý. Kỳ thi luôn đánh giá cao yêu cầu tiếp theo có trọng tâm hơn yêu cầu thử lại mơ hồ. Kỳ thi cũng yêu cầu nhận ra khi nào giao việc lại là lựa chọn chuyên nghiệp. Câu hỏi có thể kiểm tra cả hai hướng phán đoán sai. Khi nhiệm vụ lặp lại hằng tuần, đưa cách diễn đạt đó vào cấu hình dùng chung, chẳng hạn chỉ dẫn của Project, thuộc phạm vi Miền 5. Miền 1 chỉ tập trung vào việc tinh chỉnh yêu cầu hiện tại và giữ lại cách diễn đạt đã chứng minh được giá trị.

### Vì sao nên bắt đầu sạch?

Các cuộc trò chuyện dài hơn tiêu tốn nhiều hơn trong giới hạn sử dụng. Khi cuộc trò chuyện gần chạm giới hạn độ dài, hướng dẫn được công bố khuyên nên bắt đầu cuộc trò chuyện mới hoặc dùng Project. Bắt đầu lại khi bản giao việc sai là cách làm chuyên nghiệp được khuyến nghị, vì chuỗi sửa đổi dài khiến điểm xuất phát trở nên rối. Tài liệu chính thức không khẳng định rằng các cuộc trò chuyện dài làm giảm chất lượng đầu ra.

## Bẫy trong kỳ thi

### Bẫy: Yêu cầu thử lại mơ hồ nhưng ngụy trang như một sự cẩn thận

Tạo lại nội dung, đổi cách diễn đạt đôi chút hoặc yêu cầu Claude thử lại không bổ sung thông tin mới cho cuộc trò chuyện, nên đầu ra tiếp theo lặp lại thiếu sót cũ. Phản hồi chỉ hiệu quả khi nêu rõ khoảng trống: đối tượng đọc, giọng điệu, độ dài hoặc giới hạn còn thiếu.

### Bẫy: Vá một bản giao việc sai căn bản qua nhiều lượt tiếp theo

Khi đầu ra cho thấy prompt ban đầu yêu cầu sai việc, mỗi lần vá đều chống lại cách định hướng thay vì sửa nó. Viết lại bản giao việc và bắt đầu sạch sẽ nhanh hơn, đồng thời giúp mọi đợt sau của cùng công việc có điểm xuất phát tốt hơn.

### Bẫy: Mở cuộc trò chuyện mới khi đầu ra chỉ còn thiếu một chỉnh sửa cụ thể

Đây là phán đoán sai theo hướng ngược lại. Bắt đầu lại sẽ bỏ đi ngữ cảnh và tài liệu đã được duyệt mà cuộc trò chuyện hiện tại đang có. Khi đầu ra đã gần đạt yêu cầu, một phản hồi có trọng tâm trong cùng cuộc trò chuyện là cách chuyên nghiệp, nhanh và ít tốn kém hơn.

## Tình huống thực hành

Một nhân viên phụ trách trưng bày hàng bán lẻ yêu cầu Claude viết mô tả sản phẩm cho danh mục đồ gia dụng theo mùa. Đợt đầu có cấu trúc ổn nhưng chung chung, không đúng giọng thương hiệu. Cô ấy đã thử cùng prompt trong một cuộc trò chuyện mới nhưng kết quả vẫn chung chung, và muốn sửa nội dung chỉ trong một lượt nữa. Prompt tiếp theo nào hiệu quả nhất?

- **Phương án A:** Trả lời rằng nội dung chưa đúng lắm, yêu cầu Claude thử lại và tiếp tục tạo lại trong cùng cuộc trò chuyện cho đến khi có một đợt nội dung đúng giọng.
- **Phương án B:** Bắt đầu cuộc trò chuyện hoàn toàn mới, dán lại cùng prompt một dòng và trông đợi cuộc trò chuyện mới tạo ra giọng văn mới mẻ, đặc sắc hơn cho đợt nội dung.
- **Phương án C:** Trả lời bằng phản hồi cụ thể, nêu giọng điệu cần có, các cụm từ dùng quá nhiều cần tránh và nhóm người mua mà danh mục hướng tới, sau đó tạo lại nội dung.
- **Phương án D:** Chấp nhận nội dung như một điểm khởi đầu hợp lý, rồi tự viết lại giọng văn cho cả bốn mươi mô tả trước khi in danh mục.

## Bài tập thực hành

### Thực hiện hai chu kỳ phản hồi

**Độ khó:** 20 phút

**Bạn sẽ học được**

- Cách chẩn đoán khoảng cách giữa đầu ra và nhu cầu.
- Cách viết phản hồi nêu rõ khoảng trống.
- Cách dùng các phương án theo giọng điệu được gọi tên để chọn hướng.
- Cách đưa phản hồi hiệu quả trở lại prompt có thể tái sử dụng.

Chọn một đầu ra gần đây của Claude khiến bạn thất vọng, hoặc chạy bản giao việc đủ năm thành phần ở mục tiêu 1.1 rồi dùng bản nháp đầu tiên.

**Vì sao:** Muốn luyện phản hồi thì cần có một khoảng trống thực tế để chẩn đoán; ví dụ tự nghĩ ra khiến bài tập có vẻ dễ hơn thực tế.

**Bạn cần thấy:** Bản nháp đầu tiên cùng prompt đã tạo ra nó.

Chẩn đoán khoảng trống: nêu cụ thể điều gì khác với nhu cầu, chẳng hạn đối tượng đọc, giọng điệu, độ dài, phạm vi hoặc một giới hạn còn thiếu.

**Vì sao:** Chẩn đoán là kỹ năng được kiểm tra; chỉ có thể nêu khoảng trống trong phản hồi sau khi đã xác định được nó.

**Bạn cần thấy:** Một hoặc hai câu nêu khoảng trống cụ thể, không chỉ nói chung chung rằng kết quả có vẻ sai.

Viết phản hồi nêu rõ từng khoảng trống, rồi chạy bản chỉnh sửa đầu tiên.

**Vì sao:** Phản hồi cụ thể cho bản sửa một mục tiêu rõ ràng; phản hồi mơ hồ lặp lại vấn đề.

**Bạn cần thấy:** Bản sửa cải thiện rõ rệt ở những điểm bạn đã nêu.

Chẩn đoán lại và thực hiện chu kỳ thứ hai; nếu đang chọn giữa các hướng, hãy yêu cầu các phương án theo những giọng điệu đã nêu.

**Vì sao:** Chu kỳ thứ hai giúp hình thành nhịp làm việc: đầu ra, phản hồi cụ thể, đầu ra tốt hơn; các phương án khác nhau giúp bạn làm giám khảo thay vì người phải sửa mọi thứ.

**Bạn cần thấy:** Bản sửa thứ hai hoặc một nhóm phương án có nhãn, đủ gần với kết quả cuối để chỉ cần chỉnh tay.

Ghi lại từng phản hồi đã gửi, đánh dấu nội dung nào lẽ ra nên có trong prompt ban đầu rồi đưa nội dung đó vào phiên bản có thể tái sử dụng.

**Vì sao:** Phản hồi đã sửa được bản nháp chính là chỉ dẫn còn thiếu trong prompt ban đầu; đưa nó vào prompt biến một lần sửa thành tài sản dùng lại.

**Bạn cần thấy:** Một prompt đã chỉnh sửa, có tích hợp phản hồi, được lưu ở nơi bạn lưu ghi chú công việc.

## Nguồn

- Get started with Claude — Anthropic
- My prompt isn't giving me a helpful answer — Anthropic
- How do usage and length limits work? — Anthropic

**Luyện tập miền này** · **Bài tập thực hành** · **Tham khảo nhanh** · **Thuật ngữ**

**Bài học trước:** Phân rã các yêu cầu phức tạp  
**Bài học tiếp theo:** Điều chỉnh chiến lược theo loại nhiệm vụ
