# Phân rã các yêu cầu phức tạp

Nguồn: https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-2-task-decomposition

**Miền:** 1  
**Nhiệm vụ:** 1.2

## Những điều bạn cần biết

Claude tạo ra kết quả tốt nhất với công việc phức tạp khi công việc được chia thành từng phần mà Claude có thể xử lý đúng cách, lần lượt từng phần một. Việc chia nhỏ này gọi là phân rã nhiệm vụ. Các phần có liên quan sẽ cung cấp đầu vào cho nhau: phần sau cần đầu ra hoặc quyết định của phần trước. Các phần độc lập có thể tự đứng riêng.

Một prompt được soạn tốt có thể xử lý nhiều việc, nhưng vẫn có giới hạn. Nếu nhồi cả khối lượng công việc của một dự án vào một tin nhắn, kết quả sẽ nông và không đồng đều: một số phần được làm tốt, số khác chỉ được lướt qua. Hãy hình dung một quản lý siêu thị đang viết báo cáo phản hồi khách hàng theo quý cho trụ sở chính. Báo cáo cần có dàn ý, các phần với giọng văn thống nhất và danh sách hành động. Cô ấy còn cần bản tóm tắt cửa hàng đối thủ, thông cáo báo chí và bảng ngân sách. Danh sách cách khắc phục câu trả lời không hữu ích của Trung tâm Trợ giúp bao gồm việc chia yêu cầu phức tạp thành các bước nhỏ. Trung tâm cũng khuyên nên cung cấp càng nhiều ngữ cảnh càng tốt.

## Bốn kỹ thuật, từ nhẹ nhất đến nặng nhất

### Các bước được đánh số trong một prompt

Với các phần có liên quan, hãy liệt kê rõ từng bước. Quản lý siêu thị viết: trước tiên, tóm tắt các chủ đề phản hồi; tiếp theo, xếp hạng chúng theo tần suất; sau đó, soạn một hành động cải thiện cho mỗi chủ đề. Claude làm theo trình tự được nêu rõ đáng tin cậy hơn nhiều so với một đoạn văn dài liệt kê nhiều yêu cầu liên tiếp. Hướng dẫn của Anthropic khuyên dùng các bước tuần tự được đánh số khi thứ tự hoặc tính đầy đủ quan trọng, đồng thời nêu cụ thể định dạng đầu ra và các giới hạn.

### Prompt theo từng giai đoạn trong một cuộc trò chuyện

Với sản phẩm được xây dựng theo từng lớp, hãy yêu cầu tạo dàn ý, xem xét và điều chỉnh dàn ý, rồi soạn từng phần. Bạn kiểm tra đầu ra của mỗi giai đoạn trước khi chuyển sang giai đoạn tiếp theo. Đầu ra đã được duyệt trở thành nền tảng cho giai đoạn sau, nên có thể điều chỉnh khi chi phí sửa còn thấp. Quản lý siêu thị sửa dàn ý trước khi có bất kỳ phần nào được viết.

### Yêu cầu lập kế hoạch trước

Khi chưa rõ cấu trúc phù hợp, hãy yêu cầu Claude đề xuất cách tiếp cận trước. Ví dụ: trước khi viết bất cứ điều gì, hãy liệt kê các phần bạn sẽ đưa vào và nội dung của từng phần. Xem lại một kế hoạch chỉ mất vài giây; sửa lại một bản nháp sai dài 2.000 từ thì không.

### Cuộc trò chuyện riêng cho từng nhiệm vụ con

Các phần thực sự độc lập, chẳng hạn như bản tóm tắt đối thủ, thông cáo báo chí hoặc bảng ngân sách, nên được thực hiện trong các cuộc trò chuyện riêng. Cách này giữ cho từng ngữ cảnh rõ ràng và tập trung. Ba việc phụ của quản lý siêu thị sẽ có mỗi việc một cuộc trò chuyện.

## Chọn kỹ thuật

Các phần có liên quan nên được xử lý theo từng giai đoạn trong cùng một cuộc trò chuyện để các giai đoạn sau kế thừa những gì đã được duyệt ở các giai đoạn trước. Sản phẩm độc lập nên được xử lý trong các cuộc trò chuyện riêng. Khi chưa rõ cấu trúc, hãy yêu cầu lập kế hoạch trước.

Chọn sai sẽ dẫn đến một trong hai kiểu thất bại: prompt khổng lồ yêu cầu hoàn thành sản phẩm 20 trang trong một lượt, hoặc công việc liên quan bị chia nhỏ giữa nhiều cuộc trò chuyện. Khi đó, mỗi cuộc trò chuyện mới không có dàn ý và quyết định về giọng điệu đã hình thành ở cuộc trò chuyện trước. Nếu các phần của báo cáo bị chia sang nhiều cuộc trò chuyện, dàn ý và giọng điệu của quản lý sẽ bị mất.

## Duy trì ngữ cảnh

Một cuộc trò chuyện mới không tự động có được tài liệu làm việc của cuộc trò chuyện khác. Claude hiện có khả năng ghi nhớ giữa các cuộc trò chuyện, dưới dạng các chủ đề riêng lẻ về vai trò, dự án, sở thích và bối cảnh công việc đang diễn ra của bạn. Đó là ngữ cảnh về bạn, không phải bản ghi hội thoại. Tính năng này không chuyển dàn ý đã duyệt, hướng dẫn giọng điệu hay bản nháp đang viết dở sang cuộc trò chuyện mới. Trên các gói trả phí, bạn có thể yêu cầu Claude tìm kiếm các cuộc trò chuyện cũ và lấy thông tin liên quan. Đây là thao tác truy xuất mà bạn phải yêu cầu, không phải việc tự động chuyển tiếp ngữ cảnh.

Cách đáng tin cậy là chủ động lưu giữ thông tin để dùng tiếp. Dán đầu ra vào cuộc trò chuyện mới, đính kèm lại tệp hoặc lưu trong kho kiến thức của Project. Projects là các không gian làm việc độc lập với lịch sử trò chuyện và kiến thức riêng. Khi quay lại báo cáo trong một cuộc trò chuyện mới, quản lý dán dàn ý vào trước. Việc chuyển tiếp đầu ra là trách nhiệm của bạn, không phải của sản phẩm.

## Trong kỳ thi

Kỳ thi kiểm tra khả năng ghép kỹ thuật với tình huống, chứ không phải đọc thuộc lòng bốn kỹ thuật. Đáp án đúng tuân theo ba quy tắc lựa chọn ở trên. Cả hai kiểu thất bại đều xuất hiện dưới dạng phương án gây nhiễu. Câu hỏi về nơi nên lưu thông tin lâu dài thuộc Miền 3 và Miền 5.

## Tình hình hiện tại (tháng 9 năm 2026)

Tính năng Memory ra mắt trên claude.ai vào ngày 11 tháng 9 năm 2025 cho các gói Team và Enterprise, sau đó có mặt trên Pro và Max từ ngày 23 tháng 10 năm 2025. Tính đến ngày 30 tháng 9 năm 2026, tính năng này được bật mặc định cho Free, Pro và Max. Tính đến cùng ngày, với Team và Enterprise, chủ sở hữu quyết định có cung cấp Memory hay không. Tính năng này vẫn tắt đối với từng thành viên cho đến khi thành viên đó tự bật. Tìm kiếm cuộc trò chuyện, tức yêu cầu Claude tham chiếu các cuộc trò chuyện trước đây, có trên các gói trả phí. Cả hai tính năng đều không làm thay đổi nguyên tắc: Memory lưu ngữ cảnh về bạn dưới dạng các chủ đề riêng lẻ, còn việc tìm kiếm cuộc trò chuyện phải được yêu cầu.

## Bẫy trong kỳ thi

### Bẫy: Dùng prompt khổng lồ để làm mọi thứ, nhằm giữ toàn bộ sản phẩm ở một nơi

Mức độ chú ý phân bổ không đồng đều khi một tin nhắn chứa các yêu cầu của cả dự án, nên một số phần được làm tốt còn số khác chỉ được lướt qua; việc chỉnh sửa chỉ diễn ra sau khi toàn bộ sản phẩm đã sai. Biện pháp được hướng dẫn là chia yêu cầu phức tạp thành các bước nhỏ.

### Bẫy: Chia công việc liên quan sang nhiều cuộc trò chuyện

Mỗi cuộc trò chuyện mới không có dàn ý, quyết định về giọng điệu và tài liệu đã duyệt mà cuộc trò chuyện trước đã xây dựng. Vì vậy, các phần có giọng văn khác nhau và phải được chỉnh sửa cho thống nhất bằng tay. Cuộc trò chuyện riêng dành cho sản phẩm độc lập, không phải các phần liên quan.

### Bẫy: Đề nghị lập kế hoạch trước khi cấu trúc đã rõ và được thống nhất

Yêu cầu Claude đề xuất các phần mà bạn đã quyết định chỉ là bước vòng vo không cần thiết: nó thêm một lượt xem xét nhưng không thêm thông tin. Chỉ nên lập kế hoạch trước khi cấu trúc phù hợp thực sự chưa rõ.

## Tình huống thực hành

Một giám đốc chương trình tại tổ chức từ thiện phải làm báo cáo tác động hằng năm dài 20 trang: một phần tổng quan, năm phần được soạn từ ghi chú của năm nhóm chương trình và một giọng văn thống nhất. Giám đốc muốn duyệt từng phần khi chúng được tạo ra, đồng thời không muốn phải giải thích lại các quyết định đã thống nhất cho một cuộc trò chuyện mới. Giám đốc nên tổ chức công việc với Claude như thế nào?

- **Phương án A:** Gửi một prompt kèm ghi chú của cả năm nhóm và yêu cầu hoàn thành toàn bộ báo cáo 20 trang, bao gồm phần tổng quan, trong một lượt để không mất thông tin giữa các cuộc trò chuyện và giữ giọng văn thống nhất.
- **Phương án B:** Dùng một cuộc trò chuyện: thống nhất dàn ý và hướng dẫn giọng điệu trước, rồi soạn từng phần; mỗi prompt mang theo ghi chú cho phần đó, còn phần tổng quan được viết sau cùng dựa trên các phần đã hoàn tất.
- **Phương án C:** Yêu cầu từng nhóm trong năm nhóm chương trình tự dùng một cuộc trò chuyện Claude theo phong cách tùy ý, rồi ghép sáu bản nháp thành một tài liệu sau đó.
- **Phương án D:** Mở sáu cuộc trò chuyện riêng, mỗi cuộc trò chuyện cho một phần và một cuộc trò chuyện cho phần tổng quan, để từng cuộc trò chuyện luôn ngắn gọn và không cuộc trò chuyện nào chạm giới hạn độ dài.

## Bài tập thực hành

### Chia một sản phẩm nhiều phần thành các giai đoạn

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách phân loại các phần của sản phẩm thành phần liên quan và phần độc lập.
- Cách chọn kỹ thuật nhẹ nhất phù hợp cho từng phần.
- Cách sửa dàn ý trước khi bắt đầu soạn thảo.
- Cách chuyển đầu ra đã duyệt sang các giai đoạn tiếp theo.

Chọn một sản phẩm thực sự gồm nhiều phần trong công việc của bạn: báo cáo thường niên, kế hoạch dự án hoặc bộ tài liệu khóa học.

**Vì sao:** Phân rã chỉ phát huy tác dụng với công việc quá lớn để xử lý bằng một prompt; một nhiệm vụ nhỏ sẽ không giúp thực hành các kỹ thuật này.

**Bạn cần thấy:** Một sản phẩm được nêu tên, với các phần được liệt kê bằng gạch đầu dòng.

Phân loại các phần thành **liên quan**, nghĩa là chúng cung cấp đầu vào cho nhau, và **độc lập**, nghĩa là chúng tự đứng riêng.

**Vì sao:** Đây là phán đoán mà kỳ thi kiểm tra: phần liên quan phù hợp với một cuộc trò chuyện theo từng giai đoạn; phần độc lập phù hợp với các cuộc trò chuyện riêng.

**Bạn cần thấy:** Mỗi phần được gắn nhãn liên quan hoặc độc lập, kèm một cụm từ giải thích lý do.

Chỉ định một kỹ thuật cho từng phần: các bước được đánh số, cuộc trò chuyện theo từng giai đoạn, lập kế hoạch trước hoặc cuộc trò chuyện riêng; kèm một câu giải thích cho mỗi lựa chọn.

**Vì sao:** Ghép kỹ thuật với nhiệm vụ chính là mục tiêu; phần giải thích giúp lựa chọn có cơ sở.

**Bạn cần thấy:** Danh sách ngắn ghép từng phần với một kỹ thuật và lý do.

Chạy giai đoạn đầu tiên, tức dàn ý hoặc kế hoạch, rồi sửa nó trước khi bắt đầu soạn thảo.

**Vì sao:** Điều chỉnh ở giai đoạn dàn ý chỉ mất vài giây; sửa cùng lỗi đó sau khi đã viết 2.000 từ có thể mất cả buổi chiều.

**Bạn cần thấy:** Một dàn ý đã được bạn chủ động chỉnh sửa và phê duyệt, không phải chỉ được chấp nhận nguyên trạng.

Mỗi khi một giai đoạn sau cần đầu ra của giai đoạn trước, hãy ghi lại cách bạn chuyển đầu ra đó: dán vào, đính kèm lại hoặc lưu trong Project.

**Vì sao:** Cuộc trò chuyện mới không tự động có tài liệu làm việc từ cuộc trò chuyện cũ; chủ động chuyển tiếp là cách đáng tin cậy.

**Bạn cần thấy:** Một ghi chú cho từng giai đoạn, nêu cách bạn chuyển tiếp thông tin.

## Nguồn

- [My prompt isn't giving me a helpful answer](https://support.claude.com/en/articles/7996857-my-prompt-isn-t-giving-me-a-helpful-answer) — Anthropic
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Anthropic
- [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work) — Anthropic
- [Use Claude's chat search and memory to build on previous context](https://support.claude.com/en/articles/11817273-use-claude-s-chat-search-and-memory-to-build-on-previous-context) — Anthropic
- [Bringing memory to Claude](https://claude.com/blog/memory) — Anthropic
- [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects) — Anthropic

**[Luyện tập miền này](/ccao-f/drill?domain=1)** · **[Bài tập thực hành](/ccao-f/exercises/1-prompting-task-execution)** · **[Tham khảo nhanh](/ccao-f/quick-reference/domain-1)** · **[Thuật ngữ](/ccao-f/glossary/domain-1)**

**Bài học trước:** [Tạo prompt hiệu quả cho các tác vụ kinh doanh và kỹ thuật](/ccao-f/learn/1-prompting-task-execution/1-1-effective-prompts)

**Bài học tiếp theo:** [Lặp lại và cải thiện prompt](/ccao-f/learn/1-prompting-task-execution/1-3-prompt-iteration)
