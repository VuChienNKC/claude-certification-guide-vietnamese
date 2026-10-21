# Điều chỉnh chiến lược theo loại nhiệm vụ

Nguồn: https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-4-task-type-strategies

**Miền:** 1  
**Nhiệm vụ:** 1.4

## Những điều bạn cần biết

Loại nhiệm vụ là kiểu công việc bạn giao cho Claude. Mục tiêu này đề cập đến bốn loại: **phân tích** (tìm hiểu tài liệu cho thấy điều gì), **nghiên cứu** (thu thập thông tin từ các nguồn), **soạn thảo** (viết một nội dung) và **động não** (tạo ý tưởng). Tài liệu của Anthropic cho thấy Claude có thể làm cả bốn việc: phân tích dữ liệu biểu đồ, soạn từ tin nhắn văn bản đến kịch bản phim, và đưa ra góc nhìn cũng như đề xuất với vai trò cộng sự lên ý tưởng. Không có một cách viết prompt duy nhất phù hợp với cả bốn loại nhiệm vụ. Mỗi loại cần một cấu trúc giao việc khác nhau, tức nội dung mà prompt cần bao gồm.

Một quản lý công ty cho thuê nhà có bốn nhiệm vụ trong tháng này: tìm hiểu vì sao tỷ lệ gia hạn hợp đồng thuê giảm, so sánh quy trình sàng lọc người thuê của các công ty khác, viết thư cho chủ nhà về khoản phí mới và tìm cách thu hút thêm chủ nhà.

## Phân tích: tài liệu kèm câu hỏi

Phân tích bắt đầu từ tài liệu. Đính kèm bảng tính hoặc dán kết quả khảo sát, vì Claude làm việc dựa trên những gì được cung cấp. Tệp tải lên chứa tài liệu thực tế, kể cả tài liệu dài hàng trăm trang.

Sau đó, nêu rõ những câu hỏi mà phân tích cần trả lời và quyết định mà phân tích sẽ hỗ trợ. “Phân tích dữ liệu này” không cho Claude mục tiêu cụ thể, nên Claude sẽ mô tả thay vì phân tích. Quản lý đính kèm bảng tính gia hạn hợp đồng và hỏi vì sao tỷ lệ gia hạn giảm, bất động sản nào mất nhiều người thuê nhất và nên thay đổi điều gì trước năm sau. Yêu cầu nêu phát hiện chính, bằng chứng hỗ trợ và các điểm cần thận trọng; đồng thời giải thích Claude đã đi đến từng kết luận như thế nào để có thể kiểm tra lập luận. Việc kiểm tra lập luận thuộc Miền 2.

## Nghiên cứu: câu hỏi có phạm vi rõ ràng, không phải một chủ đề

Với các câu hỏi cần nhiều nguồn, Research hoạt động theo cơ chế tác nhân: Claude chủ động tìm kiếm nhiều lượt, dùng kết quả trước để định hướng lượt sau và trả về báo cáo có trích dẫn dễ kiểm tra. Với một thông tin hiện thời cần tra nhanh, tìm kiếm web thông thường là đủ. Ranh giới được tài liệu hướng dẫn nêu rõ: tìm kiếm web phù hợp với câu hỏi đơn giản về thông tin thực tế có thể trả lời bằng một hoặc hai lần tra cứu; Research phù hợp với việc thu thập kỹ lưỡng qua nhiều lần tìm kiếm.

Dù dùng cách nào, hãy đưa ra câu hỏi nghiên cứu chứ không chỉ nêu chủ đề. Nêu phạm vi, góc độ và điều mà các phát hiện sẽ giúp quyết định. Quản lý hỏi Research cách các công ty có quy mô tương tự ở địa phương sàng lọc người thuê để quyết định có nên thay đổi quy trình của mình hay không. Chỉ nêu tên chủ đề mà không đặt câu hỏi cụ thể sẽ khiến việc tìm kiếm thiếu định hướng và tạo ra báo cáo thiếu trọng tâm. Sau đó, hãy xác minh các trích dẫn quan trọng.

## Soạn thảo: bản giao việc đầy đủ

Soạn thảo cần bản giao việc đủ năm thành phần từ mục tiêu 1.1: đối tượng đọc, mục đích, giọng điệu, độ dài và định dạng. Khi văn phong nội bộ quan trọng, hãy thêm một ví dụ mẫu vì ví dụ là một trong những cách đáng tin cậy nhất để định hướng định dạng, giọng điệu và cấu trúc. Với thư thông báo phí, quản lý nêu rõ đối tượng là chủ nhà và đính kèm một lá thư trước đây. Hãy dự kiến sẽ tinh chỉnh qua các vòng phản hồi (mục tiêu 1.3). Với nội dung dài, hãy chia công việc thành các giai đoạn (mục tiêu 1.2): lập dàn ý trước rồi viết từng phần.

## Động não: mở rộng trước, thu hẹp sau

Động não đảo ngược cách tiếp cận khi soạn thảo: trước tiên hãy mở rộng, yêu cầu số lượng và sự đa dạng, chẳng hạn hai mươi ý tưởng, bao gồm một số ý tưởng khác thường. Muốn vượt ra ngoài những ý tưởng hiển nhiên, hãy yêu cầu rõ điều đó thay vì chờ Claude tự suy ra. Tạm thời đừng phán xét, vì quá nhiều giới hạn sẽ làm giảm sự đa dạng vốn là mục tiêu của bước này. Sau đó, hội tụ ở bước thứ hai: áp dụng tiêu chí, chọn danh sách rút gọn rồi phát triển các ý tưởng còn lại. Quản lý yêu cầu hai mươi cách thu hút chủ nhà và chưa nêu ngân sách ở bước tạo ý tưởng mà để dành làm tiêu chí ở bước chọn danh sách rút gọn. Cách này biến Claude thành cộng sự lên ý tưởng thực sự thay vì một công cụ chỉ tạo ra ba đề xuất an toàn.

## Thói quen chẩn đoán

Xác định loại nhiệm vụ, rồi chọn cấu trúc phù hợp:

- **Phân tích:** tài liệu kèm câu hỏi.
- **Nghiên cứu:** câu hỏi có phạm vi rõ ràng, kèm yêu cầu dẫn nguồn cho kết quả.
- **Soạn thảo:** bản giao việc đầy đủ kèm các lượt tinh chỉnh.
- **Động não:** mở rộng trước, thu hẹp sau.

## Trong kỳ thi

Hướng dẫn kỳ thi nêu bốn loại nhiệm vụ này; kỹ năng được kiểm tra là khả năng chẩn đoán: đọc tình huống công việc, xác định loại nhiệm vụ và giao việc theo đúng cấu trúc. Các đáp án sai ghép nhầm: động não bị ràng buộc quá chặt, chủ đề nghiên cứu chỉ nêu một dòng, phân tích không đính kèm tài liệu hoặc bản nháp không nêu đối tượng đọc. Trường hợp cuối là đáp án sai thường gặp về soạn thảo. Lựa chọn tính năng sản phẩm hoặc mô hình nào thuộc Miền 3; mục tiêu này tập trung vào cách giao việc sau khi đã chọn.

### Nhận biết sự ghép nhầm

Phần lớn câu hỏi giấu lỗi trong một kế hoạch nghe có vẻ hợp lý nhưng lại áp dụng cách giao việc đúng cho sai loại nhiệm vụ. Hãy kiểm tra riêng từng phần của một phương án nhiều nhiệm vụ: chỉ cần ghép nhầm một chỗ, chẳng hạn đặt giới hạn trong bước mở rộng ý tưởng, cũng đủ khiến phương án không đạt.

Trình tự “mở rộng rồi hội tụ” của động não là thực hành điều phối tiêu chuẩn được áp dụng cho Claude, không phải quy tắc trong tài liệu hướng dẫn sản phẩm.

## Bẫy trong kỳ thi

### Bẫy: Yêu cầu phân tích nhưng không nêu các câu hỏi cần trả lời

Tài liệu không kèm câu hỏi sẽ tạo ra phần mô tả dữ liệu chứ không phải phân tích. Bản giao việc chuyên nghiệp cung cấp tài liệu, câu hỏi và quyết định mà các phát hiện sẽ hỗ trợ; đồng thời yêu cầu nêu phát hiện, bằng chứng và các điểm cần thận trọng.

### Bẫy: Bắt đầu buổi động não bằng những giới hạn chặt chẽ và số hướng được chấp nhận cố định

Đặt giới hạn ngay ở bước mở rộng sẽ loại bỏ sự đa dạng mà bài tập cần tạo ra. Tiêu chí thuộc bước hội tụ, khi chúng được dùng để chọn từ nhiều ý tưởng thay vì bóp nghẹt ý tưởng trước khi chúng xuất hiện.

### Bẫy: Giao việc nghiên cứu bằng một chủ đề thay vì một câu hỏi có phạm vi rõ

Chủ đề không có phạm vi sẽ tạo ra báo cáo thiếu trọng tâm. Câu hỏi nghiên cứu cần nêu phạm vi, góc độ và điều mà các phát hiện sẽ hỗ trợ quyết định. Những điều này cho biết cần điều tra gì và xác định những nhận định mà các trích dẫn cần làm căn cứ hỗ trợ.

## Tình huống thực hành

Một nhân viên hành chính của khoa đại học có bốn nhiệm vụ trong tuần này: tìm hiểu vì sao tỷ lệ tham dự buổi hướng dẫn học tập (tutorial) giảm trong học kỳ này; tìm hiểu cách ba trường đại học khác tổ chức ngày hội tìm hiểu trường cho người dự tuyển; viết thư chào mừng sinh viên cho học kỳ mới; và tạo ý tưởng để tăng số người tham dự ngày hội tìm hiểu trường. Cô ấy dự định dùng Claude cho cả bốn nhiệm vụ. Kế hoạch làm việc nào ghép chiến lược với nhiệm vụ phù hợp?

- **Phương án A:** Đính kèm dữ liệu điểm danh và nêu câu hỏi cần trả lời trong phần phân tích; đưa cho Research một câu hỏi có phạm vi rõ về ngày hội tìm hiểu trường; giao việc đầy đủ cho bức thư và đính kèm thư năm trước làm ví dụ; yêu cầu nhiều ý tưởng trước rồi mới chọn danh sách rút gọn.
- **Phương án B:** Dùng Research cho tất cả nhiệm vụ vì nguồn có trích dẫn nâng cao chất lượng mọi đầu ra, đồng thời một phương pháp nhất quán sẽ dễ quản lý hơn trong tuần bận rộn.
- **Phương án C:** Chỉ dùng Claude cho bức thư và phần ý tưởng, còn tự xử lý phân tích điểm danh và nghiên cứu ngày hội tìm hiểu trường vì hai nhiệm vụ đó đòi hỏi khả năng phán đoán thực sự.
- **Phương án D:** Hỏi Claude về nguyên nhân thường khiến tỷ lệ tham dự ở các trường đại học giảm; trả lời phần so sánh ngày hội bằng một lượt tìm kiếm web nhanh; gửi yêu cầu một dòng cho thư chào mừng; và ngay từ đầu chỉ định chính xác ba ý tưởng an toàn, hợp lý.

## Bài tập thực hành

### Giao việc cho cả bốn loại nhiệm vụ

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách nhận diện loại nhiệm vụ trong công việc thực tế.
- Cách giao việc phân tích bằng tài liệu, câu hỏi và quyết định mà phân tích hỗ trợ.
- Cách xác định phạm vi câu hỏi nghiên cứu, gồm góc độ và mục đích.
- Cách mở rộng ý tưởng trước rồi hội tụ ở bước thứ hai.

Liệt kê bốn nhiệm vụ thực tế trong tuần của bạn, mỗi loại một nhiệm vụ: một phân tích, một câu hỏi nghiên cứu, một tài liệu cần soạn và một vấn đề cần lên ý tưởng.

**Vì sao:** Thói quen chẩn đoán chỉ hình thành khi áp dụng vào công việc thật; bốn loại nhiệm vụ trông có vẻ dễ phân biệt trên giấy nhưng dễ bị nhầm lẫn trong thực tế.

**Bạn cần thấy:** Bốn mô tả nhiệm vụ một dòng, mỗi mô tả có nhãn loại nhiệm vụ.

Viết bản giao việc phân tích: đính kèm tài liệu thật, sau đó nêu câu hỏi cần trả lời và quyết định mà phân tích sẽ hỗ trợ.

**Vì sao:** Tài liệu kèm câu hỏi là yếu tố phân biệt phân tích với việc mô tả dữ liệu.

**Bạn cần thấy:** Bản giao việc có đính kèm tệp thật và nêu hai hoặc ba câu hỏi.

Viết bản giao việc nghiên cứu dưới dạng câu hỏi có phạm vi, góc độ và mục đích; ghi chú liệu nhiệm vụ phù hợp với Research hay chỉ cần tìm kiếm web nhanh.

**Vì sao:** Câu hỏi có phạm vi rõ sẽ định hướng việc tìm kiếm; chỉ nêu tên chủ đề sẽ tạo ra báo cáo thiếu trọng tâm.

**Bạn cần thấy:** Một câu hỏi nghiên cứu nêu phạm vi, góc độ và điều mà các phát hiện sẽ hỗ trợ, kèm một dòng về công cụ sẽ dùng.

Viết bản giao việc soạn thảo với đủ năm thành phần và một ví dụ mẫu; viết bản giao việc động não yêu cầu số lượng và sự đa dạng, để dành tiêu chí cho bước sau.

**Vì sao:** Hai cấu trúc này đối lập nhau: bản nháp cần quy định đầy đủ, còn động não cần chủ động mở rộng không gian ý tưởng.

**Bạn cần thấy:** Một bản giao việc soạn thảo hoàn chỉnh có đính kèm ví dụ mẫu và một yêu cầu động não gồm hai mươi ý tưởng, trong đó có ý tưởng khác thường.

Chạy cả bốn nhiệm vụ, sau đó ghi lại trường hợp nào nếu giao việc sai cấu trúc thì bạn đã phải làm lại.

**Vì sao:** Tự thấy cái giá của việc ghép nhầm trong công việc của mình sẽ giúp thói quen chẩn đoán được duy trì lâu dài.

**Bạn cần thấy:** Bốn đầu ra cùng một ghi chú ngắn cho mỗi nhiệm vụ, nêu cách ghép nhầm mà bạn đã tránh được.

## Nguồn

- [Use research on Claude](https://support.claude.com/en/articles/11088861-use-research-on-claude) — Anthropic
- [When should I use web search, extended thinking, and research?](https://support.claude.com/en/articles/11095361-when-should-i-use-web-search-extended-thinking-and-research) — Anthropic
- [What are some things I can use Claude for?](https://support.claude.com/en/articles/7996845-what-are-some-things-i-can-use-claude-for) — Anthropic
- [Upload files to Claude](https://support.claude.com/en/articles/8241126-upload-files-to-claude) — Anthropic
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=1)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/1-prompting-task-execution)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-1)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-1)**

**Bài học trước:** [Tinh chỉnh prompt qua các vòng phản hồi để cải thiện đầu ra](https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-3-prompt-iteration)

**Bài học tiếp theo:** [Đánh giá độ chính xác và tính đầy đủ của đầu ra](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-1-accuracy-completeness)
