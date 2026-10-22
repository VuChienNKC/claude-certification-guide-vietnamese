# Tích hợp Claude vào quy trình làm việc hiện có

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-4-integrating-existing-workflows

**Miền:** 4

**Nhiệm vụ:** 4.4

## Những điều bạn cần biết

Trong chứng chỉ này, tích hợp là xác định vị trí trong quy trình hiện có mà một người đưa công việc cho Claude, và xem quy trình có giữ nguyên cấu trúc hay không. Từ này không bao giờ có nghĩa là kết nối kỹ thuật giữa các hệ thống. **Bổ trợ (augment)** là giao cho Claude một bước chậm. **Thiết kế lại (redesign)** là thay đổi chính quy trình. **Chuyển cấp (escalate)** là chuyển công việc vượt ngoài vai trò của Associate cho người khác.

Hãy hình dung một tiệm giặt khô. Mỗi thứ Hai, quản lý lập báo cáo về các khiếu nại hư hỏng của tuần trước. Khách hàng không đến lấy quần áo sẽ nhận được thư nhắc.

## Bổ trợ: Làm tốt hơn một bước

Khi Claude đảm nhận bước chậm, mọi phần khác vẫn giữ nguyên. Việc lập báo cáo chỉ mất mười phút thay vì một giờ. Quản lý vẫn chịu trách nhiệm và công việc của những người khác không thay đổi. Vì vậy, bổ trợ ít tốn kém, dễ đảo ngược và dễ giải thích cho đồng nghiệp. Nếu thất bại, quản lý quay lại tự viết báo cáo. Đây thường là lựa chọn đúng hơn nhiều so với phương án tham vọng hơn. Hầu hết các tích hợp thành công của một Associate đều là làm tốt hơn một bước.

## Thiết kế lại: Thử nghiệm trước

Khi thiết kế lại, quy trình thay đổi vì ràng buộc từng định hình nó đã không còn. Trước đây, cá nhân hóa thư nhắc mất hai mươi phút nên tiệm giặt khô chỉ gửi một thư chung. Khi việc đó chỉ mất hai phút, cách gửi các mẫu thư nhắc khác nhau theo từng nhóm khách hàng mà trước kia không ai nghĩ đến trở nên khả thi.

Thiết kế lại ít phổ biến hơn và có phạm vi lớn hơn, vì vậy cần thử nghiệm trước khi triển khai rộng. Hướng dẫn triển khai doanh nghiệp của Anthropic chia giai đoạn áp dụng theo cách này: một nhóm thử nghiệm được theo dõi phản hồi trong vài tuần trước khi mở rộng, đồng thời chỉ định người tiên phong ở mỗi nhóm. Tiệm giặt khô thử các mẫu thư nhắc theo nhóm với một đợt khách hàng trước. Triển khai tất cả cùng lúc không đo lường được gì, không còn phương án nào để so sánh và đặt mọi thứ vào rủi ro cùng một lúc.

## Điểm kiểm tra của con người

Hãy tìm bước đưa ra quyết định và giữ một người phụ trách bước đó. Tích hợp thất bại khi bỏ đi bước kiểm tra. Việc kiểm tra không tạo ra đầu ra hữu hình nên trông có vẻ lãng phí với người thiết kế lại quy trình chỉ dựa trên sơ đồ. Quản lý tiệm giặt khô ký duyệt từng lá thư trước khi gửi. Điểm kiểm tra này cũng giúp nhanh chóng áp dụng cách bổ trợ một cách an toàn. Người vẫn luôn ký thư tiếp tục ký thư, vì thế việc con người cân nhắc và quyết định vẫn được giữ nguyên trong quy trình.

## Ranh giới vai trò của Associate

Một số yêu cầu vượt ngoài vai trò này vì cần triển khai kỹ thuật: các hệ thống trao đổi với nhau, dữ liệu tự động di chuyển, hoặc quy trình được xây dựng để chạy khi không có ai hiện diện. Giả sử chủ tiệm muốn thư nhắc được gửi qua đêm, trực tiếp từ hệ thống tính tiền. Việc đó đòi hỏi kết nối hệ thống tính tiền với hệ thống gửi thư, tức là công việc kỹ thuật. Cách làm chuyên nghiệp là chuyển yêu cầu cho Claude Developer hoặc Architect cùng mô tả rõ ràng bằng văn bản về nhu cầu của quy trình. Mô tả tốt nhu cầu đó chính là phần đóng góp của Associate. Chuyển cấp không phải thất bại; đó là hiểu rõ phạm vi công việc của mình.

**Connectors** cho phép Claude lấy dữ liệu và thực hiện hành động trong các dịch vụ đã kết nối. Chúng hoạt động trong cuộc trò chuyện, khi yêu cầu của một người cần đến chúng. Tài liệu Google Workspace nêu rằng Claude chỉ truy cập dữ liệu của bạn khi bạn chủ động đặt câu hỏi hoặc yêu cầu một hành động cần dùng đến dữ liệu đó. Trong phạm vi các tính năng mà kỳ thi đề cập, chẳng hạn chat, Projects, nghiên cứu, artifacts và connectors, công việc chỉ được thực hiện khi có người yêu cầu.

**Trạng thái hiện tại (đã kiểm tra ngày 14 tháng 10 năm 2026):** Claude Cowork, không được nêu trong hướng dẫn kỳ thi, có tác vụ theo lịch. Khóa học Cowork của Anthropic cho biết một tác vụ chỉ dùng connectors của bạn có thể chạy từ xa vào thời điểm đã đặt. Trong kỳ thi, yêu cầu công việc tự chạy vẫn được chuyển cấp, vì kỳ thi xem đó là triển khai kỹ thuật vượt ngoài vai trò này.

## Công việc định kỳ nên đặt ở đâu

Công việc định kỳ nên nằm trong **Project**, không phải một cuộc trò chuyện kéo dài mãi. Project là không gian làm việc độc lập, có lịch sử trò chuyện và kiến thức riêng. Khi cuộc trò chuyện gần đạt giới hạn độ dài, Help Center khuyên bắt đầu cuộc trò chuyện mới hoặc dùng Project. Báo cáo ngày thứ Hai được lưu ở đó. Khi gói dịch vụ hỗ trợ chia sẻ, Project cung cấp cho nhóm một môi trường chung chứa tài liệu và chỉ dẫn. Các cuộc trò chuyện trong Project không được chia sẻ theo mặc định. Thành viên có thể xem nội dung, kiến thức và chỉ dẫn của Project. Cuộc trò chuyện riêng của từng người vẫn riêng tư trừ khi họ chọn chia sẻ. Quyết định công việc có nên nằm trong Project thuộc mục tiêu này. Cấu hình Project cũng như duy trì chỉ dẫn và kiến thức thuộc Miền 5.

## Trong kỳ thi

Hiểu đúng ý nghĩa của “tích hợp” sẽ giúp trả lời nhiều câu hỏi. Các phương án gây nhiễu thường nói về tích hợp theo nghĩa kỹ thuật. Đáp án đúng là tích hợp theo nghĩa của bài học này. Hãy nhận biết các dấu hiệu trong câu hỏi cho thấy cần triển khai kỹ thuật và do đó phải chuyển cấp: tự động, không cần ai thực hiện, trực tiếp từ hệ thống, qua đêm.

### Bước nhảy sang tự động hóa

Kết nối Claude vào một hệ thống hoặc cài đặt để Claude chạy không người giám sát là phương án gây nhiễu tiêu biểu trong miền này và không bao giờ là đáp án đúng. Hãy chuyển cấp vì yêu cầu là triển khai kỹ thuật, vượt ngoài vai trò này và ngoài phạm vi tính năng kỳ thi đề cập. Đừng dựa vào khẳng định rằng không sản phẩm Claude nào có thể chạy công việc đó. Cowork có tác vụ theo lịch, dù không được nêu trong hướng dẫn kỳ thi, có thể chạy một số tác vụ vào thời điểm đặt trước.

## Bẫy trong kỳ thi

### Bẫy: Tự chế cách tự động hóa thay vì chuyển cấp

Kết nối các hệ thống, tự động xuất bản và quy trình chạy mà không có người giám sát đều là triển khai kỹ thuật, vượt ngoài vai trò Associate và phạm vi tính năng kỳ thi đề cập. Các giải pháp tự chế có thể âm thầm thất bại mà không có ai phát hiện. Cách làm chuyên nghiệp là gửi yêu cầu chuyển cấp rõ ràng cho Claude Developer hoặc Architect.

### Bẫy: Thiết kế lại toàn bộ quy trình cùng lúc

Triển khai “làm tất cả một lần” có nghĩa là nếu thất bại thì mọi thứ cùng thất bại và chẳng rút ra được bài học nào. Thiết kế lại cần được thử nghiệm trên một phần trước, có phép đo, đúng như cách hướng dẫn triển khai của Anthropic chia giai đoạn áp dụng.

### Bẫy: Loại bỏ bước kiểm tra

Điểm kiểm tra của con người không tạo đầu ra hữu hình, nên có vẻ lãng phí trên sơ đồ quy trình. Đó chính là nơi con người cân nhắc và đưa ra quyết định trong quy trình. Bỏ nó đi, và lỗi đầu tiên không được phát hiện sẽ trở thành tai tiếng của toàn bộ giải pháp tích hợp.

## Tình huống thực hành

Trang sự kiện của một tờ báo địa phương được trợ lý biên tập tổng hợp hàng tuần từ thông tin sự kiện do các địa điểm gửi qua email. Một đồng nghiệp đề xuất Claude tự thu thập danh sách từ trang web của các địa điểm qua đêm rồi đăng trang hoàn chỉnh mà không cần ai động đến. Trợ lý vẫn muốn tiết kiệm thời gian cho trang tuần này và cần có người đọc từng mục trước khi đăng. Trợ lý nên phản hồi thế nào?

**Phương án A**

Đồng ý và dành cả tuần thử nghiệm connectors cho đến khi Claude có thể tự thu thập danh sách sự kiện, tạo trang mỗi đêm mà không cần ai tham gia.

**Phương án B**

Không dùng Claude cho trang này, vì chỉ cần sai một ngày hoặc giờ cũng có thể làm tổn hại uy tín của báo với độc giả và các địa điểm.

**Phương án C**

Chuyển phiên bản chạy qua đêm cho nhóm kỹ thuật, kèm ghi chú về nhu cầu của quy trình; trong lúc đó, dùng Claude định dạng lại các thông tin gửi qua email để người phụ trách kiểm tra.

**Phương án D**

Thiết kế lại toàn bộ hoạt động đăng danh sách sự kiện trong một lần: các ấn bản in, web và mạng xã hội cùng được xây dựng từ thông tin gửi đến rồi phát hành đồng loạt.

## Bài tập thực hành

### Lập sơ đồ một quy trình thuộc trách nhiệm của bạn

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 45 phút

**Bạn sẽ học được**

- Cách phân loại từng bước trong quy trình: bổ trợ, thiết kế lại, chuyển cấp hoặc chỉ dành cho con người.
- Cách viết bản mô tả chuyển cấp hữu ích cho Developer hoặc Architect.
- Cách chọn bước bổ trợ có tỷ lệ thời gian tiết kiệm so với rủi ro tốt nhất.
- Cách đo lường tích hợp một cách trung thực trong hai tuần.

1. **Chọn một quy trình định kỳ mà bạn có thể giải thích cho đồng nghiệp mới trong năm phút, rồi liệt kê đầy đủ từng bước từ đầu đến cuối.**

   **Vì sao:** Quyết định tích hợp được đưa ra theo từng bước; nếu không liệt kê được quy trình thì không thể tích hợp một cách có chủ đích.

   **Bạn cần thấy:** Danh sách có thứ tự các bước từ tác nhân khởi động quy trình đến khi có đầu ra hoàn chỉnh, bao gồm cả các bước không chính thức.

2. **Đánh dấu từng bước:** bổ trợ (một người đưa bước này cho Claude ngay bây giờ), thiết kế lại (bước này chỉ tồn tại vì trước kia một việc nào đó quá tốn kém), chuyển cấp (cần triển khai kỹ thuật như kết nối hệ thống hoặc để quy trình chạy khi không có người), hoặc chỉ dành cho con người (đây là nơi đưa ra quyết định).

   **Vì sao:** Bốn nhãn này là toàn bộ khung ra quyết định của mục tiêu, áp dụng vào công việc thực tế.

   **Bạn cần thấy:** Mỗi bước mang đúng một nhãn.

3. **Với từng bước cần chuyển cấp, viết bản mô tả hai câu để gửi Claude Developer:** quy trình cần gì và điều gì phải tiếp tục do con người thực hiện.

   **Vì sao:** Mô tả rõ nhu cầu là đóng góp của Associate cho công việc ngoài bộ công cụ; viết mô tả giúp kiểm tra xem bạn có hiểu quy trình hay không.

   **Bạn cần thấy:** Bản mô tả cho từng bước chuyển cấp mà Developer có thể thực hiện mà không cần họp.

4. **Chọn một bước bổ trợ có tỷ lệ thời gian tiết kiệm so với rủi ro tốt nhất và thực hiện trong hai tuần, giữ nguyên vị trí của điểm kiểm tra con người.**

   **Vì sao:** Làm tốt hơn một bước, đo lường được, là cách tích hợp thành công; nguyên tắc thử nghiệm cũng áp dụng ở quy mô này.

   **Bạn cần thấy:** Quy trình vận hành trong hai tuần với một bước được bổ trợ và không có thay đổi nào khác.

5. **Đo lường trung thực (trước, sau và cách bạn biết), đồng thời ghi lại những gì cần xem xét lại khi thiết kế quy trình, nay bước đó đã ít tốn kém hơn.**

   **Vì sao:** Đo lường trung thực cung cấp thông tin cho mục tiêu 4.5; bước ít tốn kém hơn có thể đã loại bỏ một ràng buộc từng định hình quy trình.

   **Bạn cần thấy:** Bản ghi ba dòng: trước, sau, bằng chứng; cùng mọi phương án thiết kế lại đáng đem ra thử nghiệm.

## Nguồn

- [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects) — Anthropic
- [Manage project visibility and sharing](https://support.claude.com/en/articles/9519189-manage-project-visibility-and-sharing) — Anthropic
- [Use connectors to extend Claude's capabilities](https://support.claude.com/en/articles/11176164-use-connectors-to-extend-claude-s-capabilities) — Anthropic
- [Use Google Workspace connectors](https://support.claude.com/en/articles/10166901-use-google-workspace-connectors) — Anthropic
- [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work) — Anthropic
- [Claude Enterprise Administrator Guide](https://claude.com/resources/tutorials/claude-enterprise-administrator-guide) — Anthropic
- [Introduction to Claude Cowork: What Claude Cowork can do for you](https://academy.claude.com/courses/introduction-to-claude-cowork/scheduled-tasks) — Anthropic (chỉ dùng cho ghi chú về trạng thái hiện tại; hướng dẫn kỳ thi không đề cập Cowork)
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic (hướng dẫn kỳ thi; các khẳng định về thực hành chuyên nghiệp là nhận định của chúng tôi, không phải hướng dẫn của Anthropic)

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=4) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/4-workflow-integration) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-4) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-4)

**Bài học trước:** [Hỗ trợ thiết kế, phát triển và cải tiến giải pháp qua các vòng thử nghiệm](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-3-solution-design-iteration)

**Bài học tiếp theo:** [Truyền đạt giá trị và giới hạn cho các bên liên quan](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-5-communicating-value-limitations)
