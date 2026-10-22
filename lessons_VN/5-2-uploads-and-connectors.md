# Quản lý kiến thức đã tải lên và trình kết nối

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-2-uploads-and-connectors

**Miền:** 5

**Nhiệm vụ:** 5.2

## Những điều bạn cần biết

Kiến thức của một Project là tài liệu mà Claude sử dụng bên trong Project đó. Kiến thức được đưa vào theo một trong hai cách. Tải tệp lên sẽ đưa một bản sao vào cơ sở kiến thức của Project: tài liệu, văn bản, mã và các tệp khác. Trình kết nối liên kết Claude với nguồn đang được cập nhật, chẳng hạn như Google Drive. Mỗi cách có những đặc tính mà cách kia không có. Việc lựa chọn phụ thuộc vào mức độ thay đổi của tài liệu.

Hãy hình dung một thợ sơn và trang trí nội thất thiết lập Project để báo giá và lập kế hoạch công việc. Điều khoản và điều kiện cùng bản mô tả phương pháp thi công hầu như không thay đổi. Lịch công việc, được lưu trong Google Docs trên Drive, lại thay đổi mỗi tuần.

### Bản sao tại thời điểm tải lên hay nguồn đang được cập nhật

Tệp tải lên là bản sao được tạo tại thời điểm tải lên. Mọi người dùng Project đều thấy cùng một bản sao, vì vậy nội dung ổn định và dễ dự đoán. Khi nguồn được thay thế bằng phiên bản mới, bản sao vẫn giữ nguyên và không có thông báo nào cho biết điều đó. Sau sáu tháng, nó vẫn trông có vẻ mới như ngày đầu. Cách này phù hợp với điều khoản và điều kiện, nhưng không phù hợp với lịch công việc vì lịch sẽ sai chỉ sau một tuần.

Trình kết nối phù hợp với tài liệu thường xuyên thay đổi vì nó truy cập nguồn đang được cập nhật khi được yêu cầu. Tài liệu Google Workspace nêu rằng Google Docs được thêm vào cuộc trò chuyện và Project sẽ đồng bộ trực tiếp từ Google Drive, nhờ đó bạn luôn làm việc với phiên bản mới nhất. Tài liệu cũng nêu rằng Claude chỉ truy cập dữ liệu khi bạn chủ động đặt câu hỏi hoặc yêu cầu một hành động cần đến dữ liệu đó, và chỉ truy xuất lượng thông tin tối thiểu cần thiết.

Phiên bản mới nhất có thể bao gồm bản chỉnh sửa còn dang dở của đồng nghiệp ngay lúc bạn đặt câu hỏi. Nếu quản lý văn phòng đang chuyển các công việc hôm thứ Ba giữa chừng, Claude sẽ đọc lịch khi các công việc vẫn đang trong quá trình chuyển. Tài liệu được cập nhật liên tục cũng mang theo những xáo trộn đang diễn ra, vì vậy tài liệu tham khảo ổn định thường phù hợp hơn khi tải lên.

### Quyền và quản trị

Trình kết nối không phải lúc nào cũng là tùy chọn cá nhân có thể bật ở mọi nơi làm việc. Với các gói Team và Enterprise, Owner hoặc Primary Owner cần bật trình kết nối cho tổ chức trước khi thành viên có thể sử dụng. Nếu chúng bị tắt trong workspace của bạn, cách làm đúng là yêu cầu người quản trị bật, không tự tìm cách bật ngoài quy trình.

Quyền truy cập phản ánh quyền mà mỗi người đã có trong dịch vụ được kết nối. Nếu ai đó không thể truy cập một tệp trong hệ thống nguồn, họ cũng không thể truy cập tệp đó qua trình kết nối từ Claude. Hai đồng nghiệp dùng cùng một Project có thể nhận được câu trả lời khác nhau từ cùng một trình kết nối. Đó là đặc tính của hệ thống phân quyền, không phải lỗi của Project.

Trình kết nối không chỉ có quyền đọc. Chúng có thể truy xuất dữ liệu và thực hiện hành động trong các dịch vụ được kết nối. Trình kết nối Gmail có thể gửi, trả lời và chuyển tiếp email từ chính tài khoản của bạn. Theo mặc định, Claude yêu cầu bạn phê duyệt từng hành động này trước khi thực hiện. Người thợ trang trí vẫn phê duyệt từng email báo giá trước khi gửi.

### Truy xuất, không phải đọc từ đầu đến cuối

Project có cơ sở kiến thức lớn không đọc toàn bộ nội dung mỗi khi có câu hỏi. Tài liệu mô tả rằng Claude tìm kiếm trong kiến thức của Project và chỉ tải nội dung phù hợp nhất. Tính năng truy xuất được kích hoạt khi Project gần chạm hoặc vượt quá giới hạn cửa sổ ngữ cảnh (context window). Việc truy xuất cần tìm đúng tài liệu giữa tất cả nội dung đã cung cấp.

Có hai bước được tài liệu hướng dẫn:

- Đặt tên tệp rõ ràng, mô tả đúng nội dung để giúp tìm ra tài liệu phù hợp. Tên `terms-and-conditions` hữu ích hơn `final-v2-new`.
- Bạn cũng có thể nêu tên một tài liệu cụ thể trong câu lệnh để tập trung việc tìm kiếm vào tài liệu đó.

### Chọn lọc quan trọng hơn đầy đủ

Kiến thức của Project không phải kho lưu trữ. Mỗi tài liệu không bao giờ cần dùng sẽ làm loãng không gian tìm kiếm và tạo thêm khả năng bị trích dẫn sai thời điểm. Một nhóm nhỏ tài liệu liên quan tốt hơn việc tải lên hàng loạt. Hãy dọn bỏ các tệp không còn được sử dụng trong công việc hiện tại thay vì giữ chúng lại.

Khi được giao một ổ đĩa dùng chung, hãy chọn một vài tài liệu mà công việc cần và quyết định cách đưa từng tài liệu vào dựa trên mức độ thay đổi. Tài liệu thường xuyên thay đổi như lịch công việc của người thợ trang trí nên được truy cập qua trình kết nối đến nguồn đang được cập nhật. Tài liệu tham khảo ổn định như bản mô tả phương pháp thi công nên được tải lên. Đồng nghiệp muốn đưa tất cả vào có ý tốt, nhưng cái giá sẽ xuất hiện về sau: câu trả lời lấy thông tin từ nhầm tài liệu.

### Trong kỳ thi

Các câu hỏi kiểm tra xem bạn có chọn đúng cách đưa tài liệu vào hay không; dấu hiệu trong gần như mọi tình huống là mức độ thay đổi của tài liệu. Việc một tài liệu có được phép đưa vào Project hay không vì lý do quyền riêng tư, hợp đồng hoặc chính sách thuộc câu hỏi của Miền 6. Mục tiêu này xử lý tài liệu đã được phép đưa vào.

### Hiện trạng: phạm vi hỗ trợ thêm tài liệu từ Drive

Hướng dẫn thi nêu Google Drive là một trình kết nối cần quản lý cùng với việc tải lên, và đánh giá đúng là đưa tài liệu thường xuyên thay đổi qua trình kết nối đó. Tính đến ngày 28 tháng 9 năm 2026, [bài viết về trình kết nối Google Workspace](https://support.claude.com/en/articles/10166901-use-google-workspace-connectors) mô tả cách thêm tài liệu từ Drive là thêm từng tài liệu một, và chỉ vào **Files** của một Project riêng tư. Bạn thêm từng tài liệu bằng cách tìm trong các tài liệu gần đây hoặc dán liên kết của tài liệu. Bài viết nêu tùy chọn này bị tắt đối với Project dùng chung, nơi mục **Files** tiếp nhận tệp tải lên. Trình kết nối vẫn hoạt động trong các cuộc trò chuyện: Google Docs được thêm vào cuộc trò chuyện sẽ đồng bộ trực tiếp từ Drive. Trong kỳ thi, hãy chọn cách đưa tài liệu vào dựa trên mức độ thay đổi của tài liệu.

### Dấu hiệu trong đề thi

Câu hỏi về tải lên hay dùng trình kết nối được chấm dựa trên mức độ thay đổi của tài liệu, không phải tầm quan trọng của nó. Lịch công việc hàng tuần được đưa qua trình kết nối, dù có vẻ tầm thường đến đâu. Điều khoản và điều kiện hầu như không thay đổi thì được tải lên, dù có vai trò nền tảng đến đâu.

## Những bẫy trong kỳ thi

### Bẫy trong kỳ thi: Đưa toàn bộ ổ đĩa dùng chung vào để không bỏ sót thứ gì

Việc tải hàng loạt trông có vẻ cẩn thận và tận tâm; chính thái độ đó là điều việc chọn lọc cần điều chỉnh. Tính năng truy xuất phải tìm đúng tài liệu trong tất cả nội dung đã cung cấp. Vì vậy, mỗi tệp không liên quan đều khiến tài liệu cần thiết khó xuất hiện hơn và tăng khả năng một tài liệu sai bị trích dẫn vào thời điểm không phù hợp.

### Bẫy trong kỳ thi: Chọn tải lên hay trình kết nối dựa trên độ quan trọng của tài liệu

Độ quan trọng không phải tiêu chí đúng. Đáp án chuẩn chọn cách đưa vào dựa trên mức độ thay đổi: tài liệu được sửa thường xuyên nên dùng trình kết nối đến nguồn đang được cập nhật; tài liệu tham khảo ổn định được tải lên một lần. Lịch làm việc tải lên sẽ âm thầm trở nên lỗi thời, bất kể công việc phụ thuộc vào nó đến mức nào.

### Bẫy trong kỳ thi: Để người dùng gói Team tự bật trình kết nối của tổ chức

Owner hoặc Primary Owner phải bật trình kết nối cho tổ chức trước khi thành viên sử dụng được. Vì vậy, bước đúng là hỏi quản trị viên workspace. Các lựa chọn để thí sinh tự tìm cách bật trình kết nối đang kiểm tra chính bước quản trị này.

## Tình huống thực hành

Một hội bảo tồn hang động mở cửa cho khách tham quan đang thiết lập kiến thức cho Project liên quan đến lịch hướng dẫn viên, sắp xếp giờ mở cửa và thông tin liên lạc với tình nguyện viên. Lịch hướng dẫn viên và giờ mở cửa — thay đổi theo mực nước sau mưa — nằm trong một thư mục Drive dùng chung; điều lệ, đánh giá rủi ro tại địa điểm và sổ tay hướng dẫn viên hầu như không thay đổi. Một ủy viên ban quản trị đề xuất đưa toàn bộ ổ đĩa dùng chung vào để mọi thứ đều sẵn có. Tài liệu không liên quan đến ba lĩnh vực đó không nên có trong Project. Cách thiết lập nào tốt nhất?

**Lựa chọn A**

Thêm lịch và giờ mở cửa từ Drive để các cuộc trò chuyện sử dụng phiên bản hiện tại; tải điều lệ, đánh giá rủi ro và sổ tay lên dưới dạng tệp; không đưa phần còn lại của ổ đĩa vào.

**Lựa chọn B**

Tải mọi thứ lên dưới dạng tệp, kể cả lịch và giờ mở cửa hiện tại, để mọi người dùng Project đều thấy đúng cùng một bộ tài liệu ổn định mỗi khi hỏi.

**Lựa chọn C**

Không đưa kiến thức vào Project; thay vào đó, mỗi người đặt câu hỏi phải dán lịch và giờ mở cửa hiện tại vào cuộc trò chuyện của mình mỗi lần.

**Lựa chọn D**

Làm theo đề xuất của ủy viên và đưa toàn bộ ổ đĩa dùng chung vào, để mọi tài liệu của hội — từ biên bản họp ban quản trị đến thư từ cũ — đều có trong Project ngay từ ngày đầu mà không cần ai lựa chọn.

## Bài tập thực hành

### Đưa tài liệu của một Project thực tế vào đúng nơi theo mức độ thay đổi

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách phân loại từng tài liệu theo tần suất thay đổi.
- Cách đưa tài liệu thường xuyên thay đổi qua trình kết nối và tải tài liệu ổn định lên.
- Cách kiểm tra việc quản trị trình kết nối trước khi dựa vào nó.
- Cách kiểm tra Project thực sự trích dẫn phiên bản nào của tài liệu đã thay đổi.

1. Liệt kê mọi tài liệu cần cho một phần công việc bạn thường làm, rồi đánh dấu từng tài liệu: thay đổi hàng tuần hoặc hàng tháng, hay hầu như không thay đổi.

   **Lý do:** Quyết định cách đưa vào được thực hiện cho từng tài liệu, và tần suất thay đổi là tiêu chí cốt lõi của toàn bộ mục tiêu này.

   **Bạn sẽ thấy:** Một danh sách hai cột: tài liệu thường xuyên thay đổi ở một bên, tài liệu ổn định ở bên kia.

2. Tải các phiên bản hiện tại của nhóm tài liệu ổn định lên kiến thức của Project và ghi lại ngày tải lên.

   **Lý do:** Tài liệu ổn định tận dụng được ưu điểm của việc tải lên: dễ dự đoán, giống nhau với mọi người và không phụ thuộc vào nguồn đang được cập nhật khi được tham khảo.

   **Bạn sẽ thấy:** Các tài liệu ổn định trong cơ sở kiến thức, cùng ghi chú ngày tải lên.

3. Với nhóm tài liệu thường xuyên thay đổi, xác định phiên bản hiện tại ở nguồn nằm ở đâu. Nếu tài liệu nằm trong Google Drive và nơi làm việc cho phép dùng trình kết nối, hãy thêm tài liệu từ Drive thay vì tải bản sao lên.

   **Lý do:** Trình kết nối giữ tài liệu thường xuyên thay đổi ở trạng thái hiện hành mà không cần ai nhớ tải lại — tránh được nguy cơ bản sao tải lên bị cũ vì người dùng quên tải lại.

   **Bạn sẽ thấy:** Các tài liệu thường xuyên thay đổi có thể truy cập qua trình kết nối Drive, hoặc một yêu cầu bằng văn bản gửi quản trị viên workspace nếu trình kết nối chưa được bật.

4. Mạnh tay loại bỏ tài liệu thừa: xóa mọi thứ bạn chỉ liệt kê vì “biết đâu sau này có ích”, đồng thời đặt tên rõ ràng, mô tả đúng nội dung cho những tệp còn lại.

   **Lý do:** Mỗi tài liệu không bao giờ cần dùng đều làm loãng việc truy xuất; tên tệp rõ ràng giúp tìm đúng tài liệu.

   **Bạn sẽ thấy:** Danh sách kiến thức ngắn hơn, trong đó mọi tệp đều xứng đáng có mặt và tên tệp nói rõ nội dung.

5. Đặt một câu hỏi có câu trả lời đã thay đổi gần đây và kiểm tra Project trích dẫn phiên bản nào.

   **Lý do:** Bài kiểm tra xác nhận cách đưa tài liệu vào: tài liệu được kết nối phải trả lời theo phiên bản hiện tại; nếu câu trả lời đã lỗi thời, nghĩa là có tài liệu thường xuyên thay đổi đã bị tải lên.

   **Bạn sẽ thấy:** Câu trả lời trích dẫn phiên bản hiện tại, hoặc xác định được một tệp cụ thể cần chuyển sang cách đưa vào khác.

## Nguồn

- [Retrieval augmented generation (RAG) for projects](https://support.claude.com/en/articles/11473015-retrieval-augmented-generation-rag-for-projects) — Anthropic
- [Use connectors to extend Claude's capabilities](https://support.claude.com/en/articles/11176164-use-connectors-to-extend-claude-s-capabilities) — Anthropic
- [Use Google Workspace connectors](https://support.claude.com/en/articles/10166901-use-google-workspace-connectors) — Anthropic
- [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work) — Anthropic
- [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=5) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/5-configuration-knowledge) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-5) · [Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-5)

**Bài học trước:** [Cấu hình Project với chỉ dẫn và nguồn kiến thức](https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-1-project-instructions-knowledge)

**Bài học tiếp theo:** [Tạo chỉ dẫn hiệu quả ở cấp hệ thống](https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-3-system-level-instructions)
