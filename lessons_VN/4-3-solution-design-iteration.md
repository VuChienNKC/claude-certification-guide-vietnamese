# Hỗ trợ thiết kế, phát triển và cải tiến giải pháp qua các vòng thử nghiệm

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-3-solution-design-iteration

**Miền:** 4

**Nhiệm vụ:** 4.3

## Những điều bạn cần biết

Cải tiến giải pháp qua nhiều vòng (solution iteration) là cải thiện một sản phẩm qua nhiều vòng, với Claude đóng vai trò cộng tác viên soạn thảo. Trong chứng chỉ này, giải pháp có thể là một quy trình, mẫu dùng lại, tài liệu hướng dẫn, chương trình, thiết kế dịch vụ, biểu mẫu hoặc kế hoạch. Giải pháp không bao giờ là phần mềm. Mỗi vòng được đánh giá theo một tiêu chí: phép thử rút ra từ yêu cầu đã xác lập ở mục 4.1.

Hãy hình dung một quán cà phê, nơi chủ quán muốn có danh sách kiểm tra mở cửa vào thứ Bảy cho một nhân viên pha chế làm việc một mình. Yêu cầu xác định đối tượng sử dụng và những tình huống danh sách cần đáp ứng, chẳng hạn sữa được giao trễ. Bản nháp đầu tiên của Claude có thể sử dụng được.

## Vì sao nên thực hiện vòng lặp

Trước đây, việc cải tiến qua nhiều vòng rất tốn kém nên mọi người thường bảo vệ bản nháp đầu tiên. Chi phí tạo phương án khác được dùng làm lý do để không xem xét thêm phương án. Claude thay đổi bài toán kinh tế đó. Tạo phiên bản thứ hai, thứ ba chỉ mất vài phút, vì vậy bạn có thể dành thời gian xem xét chúng. So sánh ba phương án cụ thể tốt hơn tranh luận về một phương án. Câu hỏi của chủ quán chuyển từ “Danh sách này có tốt không?” sang “Phiên bản nào đáp ứng được yêu cầu?”. Sự chuyển đổi đó là trọng tâm của mục tiêu này. Cách làm chỉ hiệu quả khi các phiên bản vẫn có thể bỏ đi. Có thể loại bỏ bản nháp ít tốn công tạo ra mà không cần ngần ngại; khi không ai quá gắn bó với một phiên bản, việc đánh giá nó sẽ khách quan hơn.

## Mỗi vòng cần một tiêu chí cụ thể

Mỗi vòng cần có một tiêu chí cụ thể rút ra từ yêu cầu. Điều đó phân biệt cải tiến có chủ đích với việc chỉnh sửa tùy tiện. “Làm cho tốt hơn” chỉ tạo ra thứ gì đó khác đi, chứ không phải tốt hơn. Nếu không có thông tin mới, không có định hướng cho bản sửa đổi. Help Center khuyên nên đưa phản hồi cụ thể thay vì chỉ thử lại khi câu trả lời chưa hữu ích, cũng vì lý do đó. “Hãy chỉnh để danh sách vẫn dùng được trong ngày mưa” là một thay đổi có thể kiểm tra.

Mỗi vòng hãy dựa trên một tiêu chí, chỉ kiểm tra kết quả theo tiêu chí đó và giữ lại phiên bản đạt yêu cầu. Chủ quán yêu cầu danh sách có thể xử lý việc sữa giao trễ, rồi chỉ kiểm tra điều đó. Có thể xếp hạng hai phiên bản được đánh giá theo cùng một phép thử. Nếu đánh giá hai phiên bản theo cảm nhận tổng thể thì mọi người chỉ tranh luận với nhau. Khóa học AI Fluency của Anthropic gọi nhịp này là **Vòng lặp Mô tả–Nhận định (Description-Discernment Loop)**: mô tả điều bạn cần, đánh giá kết quả nhận được, tinh chỉnh và lặp lại.

## Biết khi nào nên dừng

Hãy dừng khi những thay đổi còn lại chỉ là vấn đề sở thích thay vì mức độ đáp ứng yêu cầu. Trau chuốt một sản phẩm đã đạt yêu cầu sẽ lấy mất thời gian cần cho vấn đề tiếp theo. Việc đó cũng tạo ra một lỗi tinh vi hơn: một phiên bản trôi chảy, tự tin có thể thay thế phiên bản mà người dùng thực sự cần. Vì vậy, hãy kiểm tra theo yêu cầu và nhu cầu người dùng, không phải theo độ hay của câu chữ.

Nếu một vòng cho thấy chính yêu cầu ban đầu sai, bước tiếp theo là xem lại yêu cầu chứ không phải tạo thêm bản nháp. Dù sửa bao nhiêu lần cũng không thể khắc phục một sản phẩm được xây dựng theo mục tiêu sai. Giả sử chủ quán biết thêm rằng có hai nhân viên mở cửa vào thứ Bảy. Cần viết lại yêu cầu trước khi tạo thêm bản nháp. Dù vòng lặp kết thúc theo cách nào, hãy nêu lý do dừng trong một dòng. Nêu rõ lý do giúp những lần thực hiện sau vẫn bám sát mục đích.

## Artifacts và nhánh hội thoại

Các cơ chế sản phẩm phục vụ vòng lặp này nằm trong **artifacts**. Nội dung có dung lượng đáng kể và có thể đứng riêng nên được đưa vào cửa sổ riêng. Bạn sửa nội dung bằng cách yêu cầu Claude thay đổi artifact. Để so sánh hai phương án cụ thể, hãy chỉnh sửa tin nhắn đã tạo ra bản nháp. Thao tác đó tạo một phiên bản hội thoại khác, có artifacts riêng, trong khi nhánh gốc vẫn giữ nguyên bản nháp đầu tiên. Chủ quán có được danh sách kiểm tra thứ hai mà không làm mất bản đầu. So sánh hai nhánh tốt hơn là tin vào trí nhớ về vòng trước, vì trí nhớ thường thiên vị phiên bản xuất hiện gần nhất. Hãy để yêu cầu luôn hiển thị trong lúc so sánh. Các nhánh cho thấy các phiên bản, nhưng chỉ yêu cầu mới xác định phiên bản nào thắng.

## Trong kỳ thi

Thí sinh thường nhầm mục tiêu này với Miền 1. Tinh chỉnh prompt qua nhiều vòng để có câu trả lời tốt hơn là mục 1.3. Cải tiến giải pháp qua nhiều vòng, với Claude làm cộng tác viên soạn thảo, là mục 4.3: cùng một vòng lặp nhưng áp dụng cho một đối tượng khác.

### Khái niệm chính

Khi câu hỏi mục 4.3 cho biết bản nháp đầu tiên đã dùng được, đáp án đúng nêu một tiêu chí rút ra từ yêu cầu và kiểm tra bản sửa đổi theo tiêu chí đó. Các phương án gây nhiễu trau chuốt mà không có tiêu chí, tạo ra thật nhiều phiên bản rồi chọn theo cảm giác, hoặc đưa bản nháp chưa kiểm tra vào sử dụng thực tế. Khi câu hỏi cho thấy yêu cầu ban đầu mới là vấn đề, đáp án đúng xem lại yêu cầu.

## Bẫy trong kỳ thi

### Bẫy: Liên tục yêu cầu “làm tốt hơn” mà không nêu tiêu chí

Mỗi vòng tạo ra một phiên bản khác, nhưng không phiên bản nào có thể kiểm tra là tốt hơn vì không có định hướng cho việc sửa đổi. Đáp án đúng nêu một tiêu chí lấy từ yêu cầu và kiểm tra kết quả theo tiêu chí đó; tạo lại cho đến khi thấy ổn chỉ là hoạt động, không phải tiến bộ.

### Bẫy: Viết lại sản phẩm khi yêu cầu của nó vốn đã sai

Dù sửa bao nhiêu lần cũng không thể khắc phục sản phẩm được xây dựng theo mục tiêu sai. Khi câu hỏi cho thấy chính yêu cầu ban đầu không phù hợp, bước chuyên nghiệp là quay lại công việc ở mục 4.1; mọi vòng viết lại tiếp theo đều là phương án gây nhiễu.

### Bẫy: Chọn phiên bản viết hay nhất thay vì phiên bản phù hợp nhất

Câu chữ trôi chảy không đồng nghĩa với phù hợp. Các phiên bản được kiểm tra theo yêu cầu và người dùng, không phải theo văn phong của chúng. Bản nháp có giọng điệu thân thiện, tự tin nhưng bỏ qua một ràng buộc cứng chính là phiên bản mà kỳ thi muốn bạn loại bỏ.

## Tình huống thực hành

Điều phối viên tiệc ở một sân chơi bắn súng laser đang thiết kế lịch trình cho gói tiệc sinh nhật mới. Yêu cầu đã cố định: trẻ từ bảy đến mười một tuổi, phải phổ biến an toàn trước khi chơi, dùng bữa trong phòng tiệc và toàn bộ chương trình nằm trong khung 90 phút. Bản nháp đầu tiên của Claude dùng được. Cô muốn vòng thứ hai tạo ra một phiên bản có thể đánh giá rõ ràng là đạt hay không đạt, trước khi áp dụng cho bất kỳ bữa tiệc thật nào. Vòng thứ hai nên như thế nào?

**Phương án A**

Dùng nguyên bản nháp tại các bữa tiệc cuối tuần này, coi các buổi thực tế là vòng kiểm tra rồi điều chỉnh sau.

**Phương án B**

Yêu cầu Claude làm lịch trình vui hơn và trau chuốt hơn, rồi tiếp tục tạo lại cho đến khi có phiên bản khiến mình thấy ổn.

**Phương án C**

Bắt đầu một cuộc trò chuyện mới cho mỗi bản nháp và thu thập năm lịch trình thay thế, rồi chọn bản đọc hay nhất về tổng thể.

**Phương án D**

Sửa đổi dựa trên một tiêu chí cụ thể, chẳng hạn xử lý được tình huống khách đến trễ mười lăm phút, rồi chỉ đánh giá kết quả theo tiêu chí đó.

## Bài tập thực hành

### Ba vòng, ba tiêu chí

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 35 phút

**Bạn sẽ học được**

- Cách viết yêu cầu trước khi tạo bản nháp đầu tiên.
- Cách thực hiện một vòng sửa đổi dựa chính xác vào một tiêu chí cụ thể.
- Cách so sánh các phiên bản bằng cách tạo nhánh hội thoại.
- Cách nhận ra thời điểm nên dừng và vấn đề nằm ở yêu cầu.

1. **Chọn một sản phẩm thực tế thuộc trách nhiệm của bạn:** mẫu biểu, danh sách kiểm tra, trang hướng dẫn hoặc kế hoạch.

   **Vì sao:** Chỉ có thể đưa ra quyết định dừng khi bạn hiểu rõ người dùng và các ràng buộc thực tế của công việc.

   **Bạn cần thấy:** Một sản phẩm cụ thể có đối tượng thực sự đang chờ sử dụng.

2. **Viết yêu cầu trước, trong ba đến năm dòng:** sản phẩm dành cho ai, cần đáp ứng tình huống nào và có ràng buộc cứng gì.

   **Vì sao:** Tiêu chí xuất phát từ yêu cầu; nếu không có yêu cầu, mọi vòng sau sẽ biến thành “làm cho tốt hơn”.

   **Bạn cần thấy:** Ghi chú yêu cầu ngắn mà đồng nghiệp có thể dùng để kiểm tra bản nháp.

3. **Yêu cầu Claude tạo bản nháp đầu tiên, rồi thực hiện vòng hai theo đúng một tiêu chí được nêu rõ trong yêu cầu; ghi lại đạt hay không đạt.**

   **Vì sao:** Mỗi vòng một tiêu chí giúp thay đổi có thể kiểm tra; nếu thay đổi ba thứ cùng lúc, bạn không thể biết điều gì đã khắc phục vấn đề.

   **Bạn cần thấy:** Một phiên bản sửa đổi và kết luận ngắn gọn “đạt” hoặc “không đạt” theo tiêu chí đã nêu.

4. **Thực hiện vòng ba theo tiêu chí thứ hai:** tạo nhánh hội thoại từ tin nhắn ở vòng hai (hoặc giữ các bản sao cạnh nhau) để so sánh phiên bản thay vì tin vào trí nhớ.

   **Vì sao:** So sánh phiên bản cụ thể là phương pháp thiết kế; trí nhớ thường thiên vị phiên bản gần nhất.

   **Bạn cần thấy:** Hai hoặc ba phiên bản được so sánh trực tiếp, trong đó xác định phiên bản được giữ lại.

5. **Dừng và viết một dòng giải thích lý do:** hoặc những thay đổi còn lại chỉ là sở thích, nghĩa là đã xong; hoặc phát hiện vấn đề trong yêu cầu, nghĩa là cần quay lại yêu cầu thay vì tạo thêm bản nháp.

   **Vì sao:** Nêu rõ lý do dừng giúp xây dựng khả năng phán đoán mà mục tiêu này thực sự kiểm tra.

   **Bạn cần thấy:** Một câu duy nhất: hoàn tất vì đã đáp ứng yêu cầu, hoặc tạm dừng vì cần sửa lại yêu cầu.

## Nguồn

- [What are artifacts and how do I use them?](https://support.claude.com/en/articles/17153992-what-are-artifacts-and-how-do-i-use-them) — Anthropic
- [My prompt isn't giving me a helpful answer](https://support.claude.com/en/articles/7996857-my-prompt-isn-t-giving-me-a-helpful-answer) — Anthropic
- [AI Fluency: Framework and Foundations](https://www.anthropic.com/learn/claude-for-you) — Anthropic (tên các thành tố là tên mô-đun trong khóa học; các diễn giải ngắn gọn một mệnh đề về từng thành tố là cách diễn đạt lại nội dung khóa học của chúng tôi)
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

Không tài liệu nào của Anthropic đề cập đến thiết kế và cải tiến qua nhiều vòng đối với sản phẩm công việc trong kinh doanh. Bài học này dựa trên mục tiêu trong hướng dẫn kỳ thi và thực hành thiết kế tiêu chuẩn; bài viết về artifacts đề cập đến cơ chế sản phẩm.

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=4) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/4-workflow-integration) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-4) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-4)

**Bài học trước:** [Sử dụng Claude để nghiên cứu, lập kế hoạch và tối ưu hóa quy trình](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-2-research-planning-optimisation)

**Bài học tiếp theo:** [Tích hợp Claude vào quy trình làm việc hiện có](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-4-integrating-existing-workflows)
