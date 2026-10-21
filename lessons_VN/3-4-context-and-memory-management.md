# Quản lý giới hạn ngữ cảnh và bộ nhớ: bắt đầu lại, tóm tắt, lưu giữ

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-4-context-and-memory-management

**Miền:** 3  
**Nhiệm vụ:** 3.4

**Học bài này theo hình thức tương tác**

## Những điều bạn cần biết

Một cuộc trò chuyện có không gian làm việc hữu hạn. Tất cả những gì đã nói, đính kèm và tạo ra cho đến lúc đó đều nằm trong phần Claude đang xử lý. Các cuộc trò chuyện rất dài sẽ tiến gần đến giới hạn độ dài và giới hạn sử dụng của nền tảng; cuộc trò chuyện càng dài càng tiêu tốn nhiều hạn mức sử dụng. Riêng claude.ai có bộ nhớ xuyên suốt nhiều cuộc chat. Tìm kiếm chat (chat search) là cách truy xuất theo yêu cầu, khi bạn hỏi Claude tìm thông tin trong các cuộc trò chuyện trước.

Một người bán rau quả đã lập kế hoạch cho các hộp rau Giáng sinh của cửa hàng trong một cuộc chat rất dài bắt đầu từ tháng Tám. Cuộc chat chứa lựa chọn nhà cung cấp, ba mẫu hộp đã bỏ, thành phần được thống nhất và bảng giá đã sửa đi sửa lại nhiều lần.

Khi cuộc trò chuyện chạm giới hạn độ dài, hướng dẫn chính thức khuyên bắt đầu cuộc trò chuyện mới hoặc dùng Project để làm việc với lượng thông tin lớn hơn. Hãy coi cuộc trò chuyện như một cuộc họp dài: biết rằng nó sẽ kết thúc và quyết định trước điều gì cần được giữ lại.

## Ba cách xử lý

### Bắt đầu lại (Restart)

Bắt đầu lại khi một phần việc đã hoàn thành, khi chat có các ngõ cụt và bản nháp đã bị thay thế, hoặc khi nó sắp chạm giới hạn. Một cuộc chat kéo dài từ đầu đến cuối mang theo mọi thứ từng gặp—bao gồm cả ba mẫu hộp đã bị người bán rau loại bỏ. Bắt đầu sạch với đúng bối cảnh cần thiết sẽ tốt hơn.

### Tóm tắt (Summarise)

Trước khi rời cuộc trò chuyện, hãy yêu cầu Claude tóm tắt các quyết định đã đưa ra, tình trạng hiện tại và những việc còn lại. Sau đó, tự đối chiếu bản tóm tắt với hồ sơ nguồn. Bản tóm tắt kế thừa mọi lỗi chưa được sửa trong cuộc chat mà nó tóm tắt. Người bán rau kiểm tra bản tóm tắt của mình bằng email và hóa đơn của nhà cung cấp. Bản tóm tắt đã xác minh trở thành bản mô tả công việc ban đầu cho chat mới.

### Lưu giữ (Persist)

Lưu lại mọi đầu ra công việc cụ thể mà cuộc trò chuyện tiếp theo sẽ cần. Dán nội dung vào chat mới, đính kèm lại tệp hoặc lưu trong kho kiến thức của Project để mọi chat trong Project đều có thể dùng. Tài liệu cố định được chỉnh sửa và chia sẻ liên tục có thêm một nơi lưu phù hợp: artifact, được cập nhật như một phiên bản duy nhất đang phát triển. Người bán rau dán nội dung đã thống nhất vào chat mới, biến bảng giá hằng tuần cho nhân viên thành artifact và lưu danh sách nhà cung cấp trong kho kiến thức của Project.

## Bộ nhớ lưu giữ điều gì, và không lưu giữ điều gì?

Bộ nhớ được xây dựng thành các chủ đề riêng lẻ: vai trò của bạn, dự án, sở thích giao tiếp và bối cảnh công việc đang diễn ra. Đó là thông tin về bạn, không phải bản ghi cuộc trò chuyện, bản nháp hay tài liệu đính kèm. Mỗi Project có bộ nhớ riêng. Bên trong một Project, Claude cũng sử dụng bộ nhớ của bạn từ các cuộc chat bên ngoài Project, nhưng không bao giờ dùng bộ nhớ của Project khác. Vì vậy, bộ nhớ giúp bạn không phải giới thiệu lại bản thân. Nó không thể chuyển một bản phác thảo đã duyệt hoặc tệp dữ liệu sang chat tiếp theo một cách đáng tin cậy. Chat mới của người bán rau có thể biết về cửa hàng, nhưng bảng giá chỉ có mặt vì chị đã lưu giữ nó một cách rõ ràng.

Có hai nhận định lỗi thời trái ngược nhau: Claude không thể nhớ bất cứ điều gì giữa các chat; và có thể tin bộ nhớ sẽ mang theo một tài liệu đang làm việc. Cách đáng tin cậy vẫn là lưu giữ rõ ràng những đầu ra công việc cụ thể.

## Trong kỳ thi

Mục tiêu này kiểm tra khả năng lập kế hoạch, không phải xử lý hậu quả sau khi sự cố xảy ra; đề thi yêu cầu hiểu chính xác bộ nhớ lưu giữ những gì. Hãy chú ý thì của câu hỏi. Một câu hỏi về lập kế hoạch mô tả công việc được sắp xếp cho giai đoạn tiếp theo: một công việc dài sắp chạm giới hạn, một dự án bước vào giai đoạn cuối, hoặc một kế hoạch bàn giao. Trường hợp của người bán rau là ví dụ như vậy. Một chat đã bắt đầu tạo đầu ra kém, được chẩn đoán sau sự việc, thuộc phạm vi của Miền 7. Cùng một cuộc chat kéo dài có thể xuất hiện trong cả hai dạng câu hỏi; đáp án đúng phụ thuộc vào điều câu hỏi đang hỏi. Ở đây, đó là nguyên tắc chủ động: bắt đầu lại có chủ đích, tóm tắt rồi xác minh (nguyên tắc Miền 2 vẫn áp dụng khi bàn giao), và lưu giữ những gì cuộc trò chuyện tiếp theo phụ thuộc vào.

Hướng dẫn chính thức không khẳng định sản phẩm suy giảm chất lượng trong các cuộc chat dài; không đáp án đúng nào dựa trên nhận định đó. Ngày triển khai và khả năng dùng theo gói dịch vụ là các dữ kiện thay đổi theo thời gian, được cập nhật trong phần tham khảo nhanh của miền này.

### Ảo tưởng về tính liên tục

“Cuộc trò chuyện mới sẽ làm mất toàn bộ bối cảnh của chúng ta” là lập luận mạnh nhất để giữ một cuộc chat kéo dài, nhưng điều đó không đúng. Bản tóm tắt đã xác minh cùng các tài liệu được lưu giữ sẽ chuyển tiếp phần bối cảnh đáng giữ, với độ dài và mức sử dụng chỉ bằng một phần nhỏ.

## Bẫy trong kỳ thi

### Bẫy: Dựa vào bộ nhớ hoặc tìm kiếm chat để chuyển một đầu ra công việc cụ thể sang chat mới

Bộ nhớ lưu các chủ đề về bạn, không phải bản ghi cuộc trò chuyện, bản nháp hoặc tệp đính kèm; tìm kiếm chat là cách truy xuất theo yêu cầu. Đầu ra mà cuộc trò chuyện tiếp theo phụ thuộc vào phải được chuyển bằng cách lưu giữ rõ ràng: dán nội dung, đính kèm lại hoặc lưu trong kho kiến thức của Project.

### Bẫy: Dán bản tóm tắt chưa xác minh vào cuộc trò chuyện mới để bàn giao nhanh

Bản tóm tắt kế thừa mọi lỗi chưa sửa và quyết định lỗi thời trong cuộc chat được tóm tắt. Đối chiếu với hồ sơ nguồn là bước giúp việc bàn giao an toàn, và đáp án đúng luôn bao gồm bước này; nguyên tắc Miền 2 không ngừng áp dụng khi bàn giao.

### Bẫy: Giữ mọi thứ trong một cuộc chat khổng lồ vì bắt đầu lại sẽ làm mất bối cảnh

Đây là cách duy trì cuộc chat marathon dưới danh nghĩa liên tục. Chat chứa lẫn bản nháp lỗi thời, ngõ cụt và quyết định quan trọng, tiến gần giới hạn độ dài và tiêu tốn thêm hạn mức; tóm tắt và lưu giữ sẽ chuyển tiếp mọi thứ đáng giữ lại.

## Tình huống thực hành

Một điều phối viên đám cưới đã dùng một cuộc trò chuyện khổng lồ suốt ba tháng lên kế hoạch: quyết định địa điểm, lịch trình, các bài đọc và nhiều lần sửa tên. Tháng cuối cùng bắt đầu ngay bây giờ; chat chứa đầy chi tiết đã bị thay thế và sắp chạm giới hạn độ dài của nền tảng. Một số tên và ngày tháng đã được sửa nhiều hơn một lần nên bản tóm tắt từ chat cũ có thể chứa phiên bản lỗi thời. Kế hoạch nào là tốt nhất?

### Lựa chọn

- **A.** Yêu cầu Claude tóm tắt quá trình lên kế hoạch rồi dán thẳng vào chat mới, vì Claude đã viết bản tóm tắt từ toàn bộ lịch sử và đó là hồ sơ đáng tin cậy nhất.
- **B.** Tiếp tục dùng cuộc trò chuyện duy nhất cho đến ngày cưới vì mọi quyết định đều nằm trong đó, còn chat mới sẽ làm mất ba tháng bối cảnh.
- **C.** Yêu cầu Claude tóm tắt các quyết định và câu hỏi còn mở, đối chiếu bản tóm tắt với xác nhận đặt chỗ, mở cuộc trò chuyện cho tháng cuối từ bản tóm tắt đã xác minh, rồi chuyển sơ đồ chỗ ngồi và lịch trình thành artifact, đồng thời đưa các tài liệu cố định vào kho kiến thức của Project.
- **D.** Bắt đầu một cuộc trò chuyện mới và dựa vào bộ nhớ cùng tìm kiếm chat để chuyển sơ đồ chỗ ngồi và lịch trình sang, yêu cầu Claude nhớ lại các chi tiết kế hoạch, bao gồm tên và bài đọc đã sửa, trước khi đóng cuộc chat kéo dài ba tháng.

## Bài tập thực hành

### Thực hành nguyên tắc bàn giao cho cuộc chat dài nhất của bạn

**Độ khó:** 30 phút

**Bạn sẽ học được**

- Cách rút ra bản tóm tắt gồm quyết định, tình trạng hiện tại và phần còn lại từ cuộc trò chuyện dài.
- Cách đối chiếu bản tóm tắt với hồ sơ nguồn trước khi tin dùng.
- Cách bắt đầu cuộc trò chuyện mới từ bản mô tả đã xác minh.
- Cách phân loại đầu ra công việc vào các dạng: dán sang chat mới, artifact và kho kiến thức của Project.
- Cách kiểm tra bộ nhớ có thể và không thể chuyển những gì sang chat mới.

**Tìm cuộc trò chuyện Claude kéo dài nhất của bạn và yêu cầu Claude tóm tắt các quyết định đã đưa ra, tình trạng hiện tại và câu hỏi còn mở.**

- **Tại sao:** Bản tóm tắt là tài liệu bàn giao; cuộc chat dài có thể chôn vùi các quyết định đáng giữ trong nhiều chi tiết không cần thiết.
- **Bạn cần thấy:** Bản tóm tắt có cấu trúc ba phần: quyết định, tình trạng hiện tại và câu hỏi còn mở.

**Đối chiếu bản tóm tắt với hồ sơ nguồn—email, lịch đặt chỗ hoặc tài liệu chứa thông tin đưa ra quyết định—rồi sửa những điểm sai.**

- **Tại sao:** Bản tóm tắt kế thừa mọi lỗi chưa sửa trong chat; xác minh giúp việc dựa vào bản tóm tắt an toàn.
- **Bạn cần thấy:** Bản tóm tắt đã chỉnh sửa, có ít nhất một điểm được sửa hoặc ghi chú rằng không cần sửa gì.

**Bắt đầu cuộc trò chuyện mới bằng bản tóm tắt đã xác minh và ghi lại những điều thay đổi trong vài câu trả lời đầu tiên.**

- **Tại sao:** Trải nghiệm khác biệt giữa bản mô tả công việc rõ ràng và chat kéo dài sẽ khiến quyết định bắt đầu lại trở nên cụ thể.
- **Bạn cần thấy:** Các câu trả lời dựa trên đúng bối cảnh bạn chọn mang theo, không bị chi tiết đã lỗi thời cản trở.

**Chuyển các đầu ra công việc trong chat cũ vào đúng nơi: nội dung cần dán sang một lần; nội dung trở thành artifact vì tiếp tục được chỉnh sửa và chia sẻ; và nội dung thuộc kho kiến thức của Project vì mọi chat sau này đều cần đến.**

- **Tại sao:** Lưu giữ là một quyết định định tuyến; mỗi nơi phù hợp với một vòng đời khác nhau của đầu ra.
- **Bạn cần thấy:** Mỗi đầu ra quan trọng được chỉ định một nơi lưu; artifact được tạo và kho kiến thức của Project được lưu.

**Kiểm tra bộ nhớ đóng góp gì khi bắt đầu lại: ghi lại điều hữu ích Claude biết về bạn và dự án, rồi xác nhận rằng các đầu ra công việc chỉ xuất hiện vì bạn đã lưu giữ chúng.**

- **Tại sao:** Tự thấy ranh giới này sẽ củng cố sự khác biệt mà kỳ thi kiểm tra: bộ nhớ giữ bối cảnh về bạn, còn lưu giữ rõ ràng giữ sản phẩm công việc.
- **Bạn cần thấy:** Ghi chú hai dòng: bộ nhớ cung cấp điều gì và thao tác lưu giữ rõ ràng cung cấp điều gì.

## Nguồn

- How do usage and length limits work? — Anthropic
- Use Claude's chat search and memory to build on previous context — Anthropic
- Bringing memory to Claude — Anthropic
- What are projects? — Anthropic
- What are artifacts and how do I use them? — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic

**Luyện tập Miền này · Bài tập thực hành · Tham khảo nhanh · Bảng thuật ngữ**  
**Bài trước:** Cân bằng lựa chọn mô hình với chi phí, tốc độ và chất lượng  
**Bài tiếp theo:** Phân tích yêu cầu và trường hợp sử dụng
