# Chọn đúng tính năng sản phẩm Claude

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-1-product-feature-selection

**Miền:** 3

**Nhiệm vụ:** 3.1

## Những điều bạn cần biết

Claude có bốn cách xử lý công việc. Chat thông thường là một cuộc trò chuyện đơn lẻ. Trung tâm Trợ giúp (Help Center) mô tả Projects là các không gian làm việc độc lập, có lịch sử chat và kho kiến thức riêng. Research phù hợp với câu hỏi cần tổng hợp câu trả lời từ nhiều nguồn bên ngoài và tạo báo cáo có trích dẫn. Artifact là nội dung độc lập được hiển thị trong cửa sổ riêng, bên cạnh cuộc trò chuyện. Nhiều người chọn tính năng theo thói quen. Trước khi viết bất kỳ prompt nào, hãy xem xét tính chất của nhiệm vụ.

Một chủ tiệm làm tóc có bốn việc. Chị cần soạn một lời hồi đáp cho khiếu nại của khách. Mỗi tuần, chị viết tin nhắc lịch đặt chỗ dựa trên cùng một bảng giá và phong cách của tiệm. Chị muốn tìm hiểu các tiệm khác xử lý tiền đặt cọc khi khách không đến như thế nào, với nguồn để cộng sự có thể kiểm tra. Mỗi quý, chị chỉnh sửa tờ hướng dẫn chăm sóc sau dịch vụ cho các thợ làm tóc. Có bốn câu hỏi giúp phân loại những việc này:

- Công việc chỉ làm một lần hay lặp lại?
- Công việc có thể đứng riêng, hay luôn cần cùng một bối cảnh nền?
- Kết quả chỉ được dùng một lần, hay sẽ được chỉnh sửa và tái sử dụng?
- Claude có thể trả lời từ tài liệu bạn cung cấp, hay phải thu thập câu trả lời từ các nguồn bên ngoài?

Mỗi tính năng được thiết kế cho một dạng công việc nhất định.

## Chat thông thường là lựa chọn mặc định

Một câu hỏi đơn lẻ, một bản nháp, hoặc phân tích tài liệu được đính kèm ngay lúc đó không cần tạo Project, dùng Research hay tạo artifact riêng. Chat thông thường xử lý ngay và thường là lựa chọn đúng hơn nhiều người đam mê công nghệ nghĩ. Trả lời khiếu nại của khách là dạng công việc này.

## Projects: bối cảnh chung cho công việc lặp lại

Một Project lưu hai thành phần dùng xuyên suốt:

- **Chỉ dẫn của Project** định hướng câu trả lời của Claude trong mọi cuộc chat thuộc không gian làm việc.
- **Kho kiến thức** chứa tài liệu đã tải lên để Claude dùng làm thông tin nền cho các cuộc chat đó.

Chỉ cần thiết lập một lần, cả hai sẽ áp dụng cho mọi cuộc chat trong Project. Dấu hiệu nhận biết là cùng một tài liệu nền, các yêu cầu và ưu tiên dùng lâu dài và tài liệu làm việc cần dùng trong nhiều cuộc trò chuyện. Việc dán đi dán lại cùng bối cảnh vào từng chat là đang tự làm thủ công công việc vốn phù hợp với Project. Tính năng này được tạo ra để loại bỏ cách làm vòng vèo đó. Project có thể lưu bảng giá và phong cách của tiệm mà chủ tiệm vẫn phải dán lại mỗi tuần.

## Research: tổng hợp nhiều nguồn có trích dẫn

Trong Research, Claude chủ động thực hiện nhiều lượt tìm kiếm, dùng kết quả trước để định hướng lượt sau. Báo cáo tổng hợp có trích dẫn để người đọc kiểm tra các phát hiện. Dấu hiệu phù hợp gồm: khảo sát toàn diện một lĩnh vực, bản tóm tắt cách người khác làm, tổng quan tình hình hiện tại, và đối tượng đọc muốn biết thông tin đến từ đâu. Câu hỏi về tiền đặt cọc phù hợp với Research.

Research không phải là cách nâng cấp chất lượng cho những câu hỏi thông thường. Nếu có thể trả lời từ tài liệu bạn đã có thì không được lợi gì từ Research, vì không cần thu thập thêm thông tin.

## Artifacts: nội dung có vòng đời riêng

Claude tạo artifact khi đầu ra tương đối hoàn chỉnh, có thể dùng độc lập và có khả năng được chỉnh sửa, phát triển qua nhiều lần hoặc tái sử dụng bên ngoài cuộc trò chuyện. Điều kiện cuối cùng là dấu hiệu quan trọng nhất: sản phẩm có vòng đời vượt ra ngoài cuộc chat đã tạo ra nó. Ví dụ gồm một tờ tài liệu tham khảo được chỉnh sửa mỗi quý hoặc một kế hoạch sẽ được chia sẻ và cập nhật. Mỗi nội dung nên tồn tại như một phiên bản duy nhất được phát triển liên tục, thay vì thành nhiều mảnh rải rác trong lịch sử trò chuyện.

Bạn có thể yêu cầu Claude chỉnh sửa artifact, hoặc sửa một tin nhắn trước đó để tạo nhánh chat với các artifact riêng. Bạn có thể quay lại artifact và chia sẻ bản hoàn chỉnh. Tờ hướng dẫn chăm sóc sau dịch vụ là một trường hợp phù hợp.

## Một dấu hiệu chủ đạo

Công việc thực tế có thể kết hợp nhiều tính năng. Một Project có thể chứa các cuộc chat tạo ra artifact. Một báo cáo Research có thể làm nền cho tài liệu dạng artifact được lưu và chỉnh sửa mỗi quý. Báo cáo về tiền đặt cọc của tiệm có thể là cơ sở để tạo chính sách tiền đặt cọc lưu dưới dạng artifact.

## Trong kỳ thi

Mục tiêu này kiểm tra bạn có chọn tính năng bằng cách đọc tính chất công việc hay không. Kỳ thi không kiểm tra các cách kết hợp tính năng. Mỗi câu hỏi đưa ra một công việc có một dấu hiệu chủ đạo: bối cảnh lặp lại, trích dẫn từ nhiều nguồn, sản phẩm cần được phát triển qua nhiều lần, hoặc việc đơn lẻ đơn giản. Các đáp án sai đều là tính năng có thật nhưng được dùng cho sai dạng công việc.

Chat thông thường cần được bảo vệ như một lựa chọn đúng, vì kỳ thi cũng làm vậy. Khi dấu hiệu chủ đạo của câu hỏi là một việc đơn lẻ đơn giản, chat thông thường là câu trả lời chuyên nghiệp, dù các tính năng khác có thể làm được nhiều hơn. Kỳ thi sẵn sàng chọn đáp án đơn giản nhất.

Viết chỉ dẫn cho Project và tuyển chọn nội dung trong kho kiến thức thuộc Miền 5; ở đây, kỹ năng được kiểm tra là nhận ra tính lặp lại. Kiểm tra trích dẫn trong báo cáo Research là nguyên tắc của Miền 2. Chọn giữa câu trả lời trực tiếp, bảng và tài liệu là câu hỏi về định dạng của Miền 2. Trong mục tiêu này, artifact là nơi lưu công việc cần được chỉnh sửa và tái sử dụng.

## Khái niệm chính

Trước tiên, hãy xác định dấu hiệu chủ đạo rồi ghép với tính năng phù hợp: bối cảnh chung lặp lại tương ứng với Project; câu trả lời có trích dẫn từ nhiều nguồn tương ứng với Research; đầu ra có vòng đời riêng tương ứng với artifact; và việc chỉ làm một lần và có thể xử lý độc lập tương ứng với chat thông thường.

## Bẫy trong kỳ thi

### Bẫy: Đề xuất Research cho câu hỏi có thể trả lời từ tài liệu người dùng đã có

Research dành cho những câu trả lời cần được thu thập từ nhiều nguồn bên ngoài. Khi câu hỏi đã cung cấp tài liệu, dùng Research để tìm kiếm nhiều lượt là một bước vòng không cần thiết vì chọn sai công cụ; câu trả lời chuyên nghiệp là chat thông thường kèm tài liệu.

### Bẫy: Đưa mọi việc vào Project hoặc Research để tối đa hóa chất lượng

Tính năng phức tạp nhất không đồng nghĩa với lựa chọn an toàn nhất. Một việc đơn lẻ đơn giản không được lợi gì từ không gian làm việc hay báo cáo nhiều nguồn. Chat thông thường là đáp án hoàn toàn hợp lệ trong mục tiêu này; quyết định dựa vào dấu hiệu chủ đạo, không phải vào vẻ “cao cấp” của tính năng.

### Bẫy: Coi việc dán lại cùng bối cảnh vào từng chat là cẩn thận

Cách làm thủ công khiến bạn phải trả chi phí thiết lập Project mỗi lần thay vì chỉ một lần. Nếu câu hỏi mô tả cùng tài liệu và sở thích được cung cấp lặp đi lặp lại trong nhiều chat, đáp án đúng là chuyển công việc đó vào Project.

## Tình huống thực hành

Một thư ký hội đồng địa phương (parish council) có bốn việc: chu kỳ lập chương trình nghị sự và biên bản hằng tháng, luôn cần quy chế thường trực của hội đồng, danh sách thành viên và quy ước định dạng; một bản tóm tắt chỉ làm một lần về cách năm hội đồng lân cận quản lý danh sách chờ thuê ô trồng rau, kèm nguồn để các ủy viên kiểm tra; một câu hỏi đơn lẻ của cư dân về hạn chót nộp hồ sơ xin trợ cấp; và một danh sách liên hệ khẩn cấp được cập nhật mỗi quý, chia sẻ với tất cả thành viên. Chị không muốn dùng tính năng phức tạp hơn mức cần thiết, tạo Project cho việc không lặp lại, hoặc phải cung cấp lại thông tin thủ công. Kế hoạch nào ghép đúng tính năng với công việc?

### Lựa chọn

- **A.** Tạo một Project chứa cả bốn việc, vì giữ mọi nhiệm vụ của hội đồng trong một không gian làm việc sẽ đơn giản hơn việc quyết định tính năng riêng cho từng việc khi phát sinh.
- **B.** Dùng Research cho cả bản tóm tắt về các khu trồng rau và câu hỏi về hạn xin trợ cấp, rồi xuất bản mọi đầu ra thành artifact có thể chia sẻ để cả bốn việc đều đạt mức chặt chẽ tối đa.
- **C.** Dùng Project cho chu kỳ lập chương trình nghị sự và biên bản hằng tháng, Research cho bản tóm tắt về năm hội đồng, chat thông thường cho câu hỏi về hạn xin trợ cấp, và tạo rồi cập nhật danh sách liên hệ dưới dạng artifact.
- **D.** Thực hiện mọi việc trong chat thông thường, mỗi tháng dán lại quy chế và danh sách thành viên, rồi mỗi quý dựng lại danh sách liên hệ từ cuộc trò chuyện cũ.

## Bài tập thực hành

### Kiểm tra lựa chọn tính năng của bạn

**Độ khó:** Cơ bản (1/4)

**Thời lượng:** 20 phút

**Bạn sẽ học được**

- Cách xem xét tính chất của một nhiệm vụ trước khi chọn tính năng.
- Cách gọi tên dấu hiệu chủ đạo quyết định tính năng cho từng việc.
- Cách nhận ra cách làm thủ công trong thói quen làm việc của chính bạn.
- Cách quyết định khi nào một công việc lặp lại cần đến Project.

**Liệt kê năm cuộc trò chuyện Claude gần đây nhất trong công việc của bạn.**

- **Tại sao:** Các cuộc trò chuyện thật cho thấy thói quen thật; danh sách tự nghĩ ra dễ khiến bài tập có vẻ tốt hơn thực tế.
- **Bạn cần thấy:** Năm mô tả một dòng về những nhiệm vụ thực tế bạn mới làm.

**Gắn cho từng việc tính năng lẽ ra nên dùng: chat thông thường, chat trong Project, Research hoặc artifact cho đầu ra.**

- **Tại sao:** Việc gắn nhãn buộc bạn đưa ra quyết định chọn tính năng mà mục tiêu này kiểm tra, từng việc một.
- **Bạn cần thấy:** Mỗi nhiệm vụ có một nhãn tính năng.

**Nêu dấu hiệu chủ đạo quyết định từng nhãn: bối cảnh chung lặp lại, tổng hợp có trích dẫn từ nhiều nguồn, sản phẩm có thể chia sẻ và phát triển qua nhiều lần, hay việc đơn lẻ đơn giản.**

- **Tại sao:** Đề thi đưa ra các dấu hiệu, không phải tên tính năng; mục đích là luyện ghép dấu hiệu với tính năng.
- **Bạn cần thấy:** Một dấu hiệu được nêu bên cạnh mỗi nhãn tính năng.

**Tìm một cách làm thủ công trong thói quen của bạn, chẳng hạn dán lại bối cảnh giữa nhiều chat hoặc để tài liệu đang được cập nhật nằm sâu trong một cuộc trò chuyện cũ, rồi nêu tính năng có thể giải quyết việc đó.**

- **Tại sao:** Cách làm vòng vèo này là thói quen không hiệu quả mà đề thi thường trình bày như thể là sự cẩn thận; tự tìm ra giúp bạn nhận diện nó trong câu hỏi.
- **Bạn cần thấy:** Một cách làm vòng vèo được mô tả trong một câu, kèm tính năng thay thế.

**Nếu có công việc lặp lại xứng đáng được đưa vào Project, hãy ghi lại để thiết lập sau, rồi dừng ở đó; cấu hình Project cho tốt là kỹ năng ở phần sau.**

- **Tại sao:** Mục tiêu này chỉ dừng ở quyết định chọn tính năng; chỉ dẫn và tuyển chọn kiến thức thuộc Miền 5.
- **Bạn cần thấy:** Một ghi chú nêu Project bạn sẽ tạo và công việc lặp lại mà Project đó phục vụ.

## Nguồn

- [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects) — Anthropic
- [Use research on Claude](https://support.claude.com/en/articles/11088861-use-research-on-claude) — Anthropic
- [Analyze campaign performance](https://academy.claude.com/use-cases/analyze-campaign-performance) — Anthropic
- [What are artifacts and how do I use them?](https://support.claude.com/en/articles/17153992-what-are-artifacts-and-how-do-i-use-them) — Anthropic
- [When should I use web search, extended thinking, and research?](https://support.claude.com/en/articles/11095361-when-should-i-use-web-search-extended-thinking-and-research) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=3)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/3-product-model-selection)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-3)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-3)**

**Bài học trước:** [Tuyển chọn thông tin và lựa chọn định dạng đầu ra](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-6-output-formats-curation)

**Bài học tiếp theo:** [Phân biệt các loại mô hình Claude](https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-2-model-tiers)
