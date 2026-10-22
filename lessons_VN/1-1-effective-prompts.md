# Tạo prompt hiệu quả cho các tác vụ kinh doanh và kỹ thuật

Nguồn: https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-1-effective-prompts

**Miền:** 1

**Nhiệm vụ:** 1.1

## Những điều bạn cần biết

Prompt là bản giao việc bạn đưa cho Claude: nhiệm vụ và mọi thông tin cần thiết để thực hiện nhiệm vụ đó. Giao việc rõ ràng không phải là kỹ năng kỹ thuật; đó là kỹ năng bạn dùng khi giao việc cho đồng nghiệp. Mọi mục tiêu khác trong chứng chỉ này đều dựa trên kỹ năng đó. Một bản giao việc tốt cung cấp nền tảng cho sáu miền còn lại; không tính năng, lựa chọn mô hình hay bước khắc phục sự cố nào có thể cứu được một bản giao việc tồi.

Người quản lý văn phòng của một công ty lợp mái muốn Claude soạn bản cập nhật một trang về các công trình trong tháng này cho hai giám đốc. Phiên bản một dòng của yêu cầu là: “viết gì đó về các công trình trong tháng này”.

## Tư duy giao việc

Hướng dẫn của Anthropic khuyên hãy xem Claude như một nhân viên mới rất tài giỏi: năng lực cao nhưng chưa biết gì về công ty, dự án hay tiêu chuẩn của bạn cho đến khi bạn cung cấp thông tin. Trung tâm Trợ giúp cũng đưa ra hình ảnh tương tự cho người dùng trò chuyện: một cộng tác viên vừa được thuê, cần chỉ dẫn thật cụ thể. Trung tâm khuyên bạn hãy giải thích prompt chưa hiệu quả như thể đang nói với người không có kiến thức nền về điều bạn yêu cầu.

Một prompt hiệu quả cung cấp càng nhiều ngữ cảnh càng tốt, vì Claude làm việc dựa trên những gì được cung cấp. Giống như khi giao việc tốt, prompt cần bao gồm nhiệm vụ, bối cảnh, đối tượng đọc, định dạng và tiêu chí cho một kết quả tốt. Cả nhân viên mới ở công ty lợp mái lẫn Claude đều không biết công trình nào bị chậm tiến độ.

## Năm thành phần

Một prompt kinh doanh đầy đủ có năm phần.

### Nhiệm vụ

Nêu chính xác việc bạn muốn hoàn thành, bằng một động từ và một sản phẩm bàn giao cụ thể. “Soạn bản cập nhật dự án một trang cho ban chỉ đạo” là một nhiệm vụ. “Giúp tôi làm dự án” thì không. Nhiệm vụ của người quản lý văn phòng là bản cập nhật một trang về các công trình trong tháng này cho các giám đốc.

### Bối cảnh

Cung cấp những thông tin nền mà Claude không thể tự biết: đối tượng đọc là ai, tài liệu dùng để làm gì, những gì đã được quyết định và mọi giới hạn áp dụng. Với một nhiệm vụ viết, prompt nêu yêu cầu, đối tượng mục tiêu và các ý chính.

### Tài liệu nguồn

Dán hoặc đính kèm tài liệu đầu vào gốc, chẳng hạn như báo cáo, ghi chú cuộc họp hoặc dữ liệu. Đừng mô tả chúng theo trí nhớ. Claude làm việc dựa trên những gì được cung cấp; bản tóm tắt theo trí nhớ có thể phát sinh sai sót hoặc bỏ mất thông tin vốn có trong tài liệu gốc. claude.ai hỗ trợ tài liệu, bảng tính và hình ảnh, giúp bạn cung cấp trực tiếp tài liệu gốc. Công ty lợp mái đính kèm phiếu công việc thay vì cố nhớ lại thông tin.

### Yêu cầu đầu ra

Quy định định dạng, độ dài, giọng điệu và cấu trúc: ba ý dạng gạch đầu dòng cho mỗi mảng công việc, giọng trung lập, dưới 400 từ.

### Ví dụ, khi tiêu chuẩn quan trọng

Một mẫu tài liệu trước đây theo văn phong nội bộ có giá trị hơn ba đoạn mô tả văn phong đó. Anthropic gọi ví dụ là một trong những cách đáng tin cậy nhất để định hướng định dạng, giọng điệu và cấu trúc. Bản cập nhật tháng trước là ví dụ mẫu của công ty lợp mái.

## Định hình vai trò và đối tượng

Mở đầu prompt bằng một vai trò, chẳng hạn như “Với vai trò chuyên gia truyền thông nhân sự”, sẽ định hình từ vựng, giọng điệu và ưu tiên. Anthropic lưu ý rằng chỉ một câu cũng tạo ra khác biệt.

Nêu rõ đối tượng đọc có ảnh hưởng đến đầu ra nhiều hơn hầu hết các chỉnh sửa chỉ dẫn khác. Cùng một phân tích nên được viết khác nhau cho hội đồng quản trị và cho nhóm dự án. Nếu được cho biết ai sẽ đọc, Claude sẽ điều chỉnh nội dung; vì vậy, bản giao việc của công ty lợp mái nêu rõ đối tượng là các giám đốc. Giải thích lý do của một yêu cầu cũng giúp câu trả lời phù hợp mục tiêu hơn.

## Lợi ích của việc nêu cụ thể

Prompt mơ hồ tạo ra đầu ra chung chung, cần chỉnh sửa nhiều. Nêu cụ thể định dạng và giới hạn mong muốn sẽ cải thiện kết quả của Claude. Dành một phút cho bản giao việc sẽ tiết kiệm một vòng làm lại. Hướng dẫn sử dụng chính thức cũng đồng tình: hãy cụ thể và súc tích, đồng thời xem lại và chỉnh sửa prompt trước khi gửi. Giao việc rõ ràng ngay từ lần đầu giúp tiết kiệm thời gian và dùng ít hạn mức sử dụng hơn so với sửa đi sửa lại. Yêu cầu một dòng của công ty lợp mái không cung cấp phiếu công việc, người đọc hay định dạng.

## Tác vụ kỹ thuật ở cấp Associate

“Kỹ thuật” không có nghĩa là viết mã. Ở cấp độ này, đó là yêu cầu Claude tạo công thức bảng tính, thực hiện phân tích dữ liệu đơn giản ở bước đầu hoặc soạn bản nháp đầu tiên của tài liệu kỹ thuật. Kỹ năng vẫn như nhau: giao việc rõ ràng. Người quản lý văn phòng có thể viết: “Tôi cần một công thức đánh dấu mọi hóa đơn quá hạn hơn 30 ngày; đây là dữ liệu mẫu.”

## Trong kỳ thi

Đáp án sai thường gặp trong mục tiêu này là prompt một dòng “viết gì đó về kết quả quý 3 của chúng ta”, được xem là chấp nhận được vì Claude sẽ tự hiểu. Claude không thể làm vậy: không có thành phần nào trong năm thành phần để dựa vào. Yêu cầu về công thức ở trên đã thể hiện kỹ năng thuộc Miền 1; công thức được viết khéo đến đâu không phải điều câu hỏi này kiểm tra.

### Khái niệm chính

Khi đề thi so sánh các prompt, hãy đếm các thành phần. Đáp án đúng hầu như luôn bổ sung thành phần còn thiếu: nhiệm vụ, bối cảnh, tài liệu nguồn, yêu cầu đầu ra hoặc ví dụ. Các phương án gây nhiễu chỉ trau chuốt câu chữ nhưng vẫn để nguyên khoảng trống.

## Bẫy trong kỳ thi

### Bẫy: Chấp nhận prompt một dòng vì Claude sẽ tự hiểu

Claude không có ngữ cảnh mà một đồng nghiệp cần, vì vậy đầu ra sẽ chung chung và người dùng phải trả giá cho việc bỏ qua khâu giao việc bằng cách làm lại. Đáp án đúng giao việc đầy đủ; nêu cụ thể từ đầu là giải pháp đã được hướng dẫn.

### Bẫy: Chọn phương án chỉ trau chuốt câu chữ trong khi khoảng trống thực sự vẫn còn

Câu hỏi trong mục tiêu này thường chỉ ra một thành phần bị thiếu: không có đối tượng đọc, không có tài liệu nguồn hoặc không có định dạng. Chỉnh sửa chỉ dẫn mang tính hình thức không lấp được khoảng trống đó; vì vậy, phương án này trông có vẻ hợp lý nhưng vẫn kém hơn phương án giải quyết đúng vấn đề và không phải đáp án đúng.

### Bẫy: Tự viết sản phẩm bàn giao rồi chỉ dùng Claude để hiệu đính

Điều này có vẻ cẩn thận nhưng lại không tận dụng đủ công cụ. Soạn bản nháp từ một bản giao việc tốt chính là việc Claude làm hiệu quả; chỉ giao vai trò hiệu đính sẽ bỏ phí phần tiết kiệm thời gian. Kỳ thi xem đây là cách sử dụng hời hợt, chưa tận dụng hết công cụ.

## Tình huống thực hành

Một điều phối viên cơ sở vật chất cần Claude soạn bản ghi nhớ cho nhân viên để giới thiệu hệ thống đặt chỗ bàn làm việc mới, gửi cho toàn thể nhân viên làm việc tại văn phòng. Cô có hướng dẫn sử dụng của nhà cung cấp và muốn có bản nháp có thể gửi đi mà không phải tự sửa hoặc quay lại Claude thêm nhiều lượt. Prompt nào chuẩn bị công việc tốt nhất?

- **Phương án A:** Trước tiên, yêu cầu Claude mô tả cách các hệ thống đặt chỗ bàn làm việc thường hoạt động, rồi để Claude tự chọn định dạng phù hợp để soạn bản ghi nhớ. Nếu bản nháp đầu tiên chưa đạt thì mới cung cấp hướng dẫn, đối tượng đọc và yêu cầu về giọng điệu trong các lượt hỏi tiếp theo.
- **Phương án B:** Gửi một câu duy nhất yêu cầu viết bản ghi nhớ về hệ thống đặt chỗ bàn làm việc, giữ yêu cầu ngắn để Claude có không gian sáng tạo, rồi dự định chọn những phần tốt nhất trong câu trả lời.
- **Phương án C:** Đính kèm hướng dẫn sử dụng một trang, nêu đối tượng đọc là toàn thể nhân viên làm việc tại văn phòng, nói rõ mục tiêu là giảm nhầm lẫn trong tuần đầu tiên, rồi yêu cầu giọng thân thiện nhưng dứt khoát, độ dài 300 từ và phần tóm tắt ba gạch đầu dòng ở đầu.
- **Phương án D:** Tự viết bản ghi nhớ dựa trên hướng dẫn sử dụng, rồi chỉ yêu cầu Claude kiểm tra chính tả, ngữ pháp và giọng điệu của văn bản hoàn chỉnh trước khi gửi cho nhân viên.

## Bài tập thực hành

### Viết bản giao việc đủ năm thành phần

**Độ khó:** Cơ bản (1/4)

**Thời lượng:** 20 phút

**Bạn sẽ học được**

- Cách nêu nhiệm vụ bằng động từ và sản phẩm bàn giao cụ thể.
- Cách cung cấp bối cảnh mà Claude không thể tự biết.
- Cách đính kèm tài liệu nguồn thật thay vì mô tả tài liệu.
- Cách quy định định dạng, độ dài, giọng điệu và cấu trúc.
- Cách dùng một tài liệu mẫu để thiết lập tiêu chuẩn.

**Chọn một nhiệm vụ lặp lại thực tế trong công việc của bạn:** báo cáo, bản tóm lược hoặc email bạn tạo hàng tuần.

**Vì sao:** Một nhiệm vụ bạn hiểu rõ sẽ giúp các khoảng trống trong bản giao việc lộ ra; bạn có thể nhận ra ngay khi đầu ra không đạt tiêu chuẩn.

**Bạn cần thấy:** Một dòng nêu nhiệm vụ, sản phẩm bàn giao và tần suất lặp lại.

Viết dòng mô tả nhiệm vụ bằng một động từ và một sản phẩm bàn giao, sau đó bổ sung bối cảnh Claude không thể biết: đối tượng đọc, mục đích, những gì đã được quyết định và mọi giới hạn.

**Vì sao:** Nhiệm vụ và bối cảnh là hai thành phần thường thiếu nhất trong prompt yếu, đồng thời cũng là hai thành phần bổ sung ít tốn công nhất.

**Bạn cần thấy:** Một câu nêu nhiệm vụ, cùng ba hoặc bốn dòng bối cảnh mà một đồng nghiệp mới cần biết ngay ngày đầu tiên.

Đính kèm hoặc dán tài liệu nguồn thật: báo cáo, ghi chú, dữ liệu; không dùng bản tóm tắt dựa trên trí nhớ.

**Vì sao:** Claude làm việc dựa trên những gì được cung cấp; mô tả theo trí nhớ có thể phát sinh sai sót hoặc bỏ mất thông tin vốn có trong tài liệu gốc.

**Bạn cần thấy:** Các tệp gốc hoặc văn bản đã dán có mặt trong cuộc trò chuyện bên cạnh bản giao việc.

Quy định đầu ra: định dạng, độ dài, giọng điệu và cấu trúc; đồng thời đính kèm một ví dụ về tài liệu trước đây theo văn phong nội bộ.

**Vì sao:** Ví dụ là một trong những cách đáng tin cậy nhất để định hướng định dạng, giọng điệu và cấu trúc; một mẫu có giá trị hơn nhiều đoạn mô tả.

**Bạn cần thấy:** Một hoặc hai dòng quy định đầu ra cùng một ví dụ được đính kèm.

Chạy prompt và so sánh bản nháp này với bản nháp đầu tiên bạn thường có khi làm công việc đó, ghi lại thành phần nào đã tạo ra giá trị.

**Vì sao:** So sánh giúp bạn nhận ra từng phần của bản giao việc đã đem lại điều gì; đó là cách hình thành thói quen giao việc tốt.

**Bạn cần thấy:** Bản nháp đầu tiên gần đạt mức có thể phát hành hơn rõ rệt so với kết quả của prompt một dòng.

## Nguồn

- [Get started with Claude](https://support.claude.com/en/articles/8114491-get-started-with-claude) — Anthropic
- [Introduction to prompt design](https://support.claude.com/en/articles/7996853-introduction-to-prompt-design) — Anthropic
- [My prompt isn't giving me a helpful answer](https://support.claude.com/en/articles/7996857-my-prompt-isn-t-giving-me-a-helpful-answer) — Anthropic
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Anthropic
- [Upload files to Claude](https://support.claude.com/en/articles/8241126-upload-files-to-claude) — Anthropic
- [Usage limit best practices](https://support.claude.com/en/articles/9797557-usage-limit-best-practices) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=1)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/1-prompting-task-execution)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-1)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-1)**

**Bài học tiếp theo:** [Phân rã các yêu cầu phức tạp](https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-2-task-decomposition)
