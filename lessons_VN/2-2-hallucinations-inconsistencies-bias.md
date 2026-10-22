# Nhận diện hiện tượng bịa đặt, mâu thuẫn và thiên lệch

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-2-hallucinations-inconsistencies-bias

**Miền:** 2

**Nhiệm vụ:** 2.2

## Những điều bạn cần biết

Mục tiêu 2.1 đã giới thiệu cho bạn cách tiếp cận của người rà soát. Mục tiêu này gọi tên ba dạng lỗi mà một lượt đánh giá cần tìm: hiện tượng bịa đặt (hallucination) là nội dung nghe có vẻ thuyết phục nhưng không dựa trên sự thật; mâu thuẫn (inconsistency) là đầu ra tự mâu thuẫn; thiên lệch (bias) là cách nhìn nhận vấn đề, các giả định hoặc ngôn từ mang thiên lệch. Mỗi dạng có dấu hiệu nhận biết riêng và cần một cách xử lý khác nhau.

Trong một tuần, người quản lý trung tâm làm vườn giao cho Claude ba việc: hướng dẫn các bước tạo báo cáo tồn kho trong hệ thống tính tiền, tóm tắt doanh số mùa xuân kèm bảng, và soạn ghi chú đánh giá nhân viên thời vụ. Mỗi việc đều có thể mắc một trong ba dạng lỗi này.

## Bịa đặt: trôi chảy, cụ thể nhưng không có thật

Trung tâm Trợ giúp (Help Center) cho biết Claude “đôi khi có thể đưa ra câu trả lời không chính xác hoặc gây hiểu lầm”. Claude “có thể hiển thị những trích dẫn trông có vẻ đáng tin cậy hoặc nghe có vẻ thuyết phục nhưng không dựa trên sự thật”. Cụm cuối cùng là định nghĩa thực tế cần nhớ. Hiện tượng bịa đặt không mơ hồ hay rụt rè. Nó xuất hiện dưới dạng một con số trông có vẻ chính xác, một nguồn được nêu tên hoặc một danh sách bước được đánh số. Chi tiết bịa ra được trình bày với độ tự tin giống như chi tiết có thật, vì vậy mức độ cụ thể không phải là bằng chứng. Với mỗi chi tiết, hãy hỏi: “Thông tin này có thể xuất phát từ đâu?” Câu hỏi “Nghe có vẻ đúng không?” chỉ kiểm tra sự tự tin mà thôi.

Claude cũng có thể bịa về chính khả năng của mình. Một bài viết khác trong Help Center cảnh báo rằng Claude có thể tuyên bố sai rằng mình đã gửi email, tạo tài liệu bên ngoài hoặc cung cấp liên kết hoạt động được. Claude không thể truy cập email hay truyền tệp trừ khi các công cụ đó được tích hợp rõ ràng. Lời khẳng định Claude đã làm việc gì đó bên ngoài cuộc trò chuyện là điều cần kiểm tra, không phải xác nhận rằng việc ấy đã hoàn tất. Nếu Claude nói đã gửi số liệu tồn kho cho nhà cung cấp qua email, người quản lý cần xác minh với nhà cung cấp.

### Rủi ro tập trung ở đâu

Nguy cơ bịa đặt phụ thuộc vào mức độ có căn cứ. Rủi ro cao nhất khi Claude có ít thông tin để dựa vào:

- Hệ thống và tài liệu nội bộ riêng của tổ chức mà bạn chưa cung cấp cho Claude.
- Sự kiện rất mới, xảy ra sau thời điểm dữ liệu huấn luyện của Claude.
- Các số liệu rất cụ thể nhưng không có trong tài liệu nguồn.

Dạng rủi ro cao nhất là hướng dẫn theo từng bước, trình bày đầy tự tin cho một công cụ nội bộ mà Claude chưa từng thấy tài liệu hướng dẫn. Nội dung trôi chảy, cụ thể nhưng không có cơ sở. Các bước tạo báo cáo tồn kho thuộc dạng này: Claude nêu tên những menu trong hệ thống tính tiền mà nó chưa từng được giới thiệu, và một số menu có thể không tồn tại. Claude càng ít có căn cứ để dựa vào thì mức độ cụ thể của câu trả lời càng ít có giá trị chứng minh.

## Mâu thuẫn: đầu ra tự mâu thuẫn

Để phát hiện mâu thuẫn, không cần nguồn bên ngoài. Các dạng thường gặp gồm: con số trong phần văn bản trái với con số trong bảng; khuyến nghị trái với kết quả phân tích; hoặc hai phần nêu những ngày khác nhau cho cùng một sự kiện. Mâu thuẫn nội bộ là cảnh báo về độ tin cậy của toàn bộ câu trả lời, chứ không chỉ là lỗi đánh máy cần sửa. Quy trình tạo ra một lỗi nhìn thấy được cũng có thể đã tạo ra những lỗi không dễ thấy khác. Vì vậy, hãy kiểm tra lại toàn bộ câu trả lời dựa trên nguồn, thay vì chỉ sửa điểm không khớp mà bạn nhận ra rồi gửi phần còn lại. Nếu phần văn bản và bảng trong bản tóm tắt doanh số mùa xuân đưa ra số liệu khác nhau về sản phẩm phân ủ hữu cơ, người quản lý cần đối chiếu toàn bộ bản tóm tắt với dữ liệu từ hệ thống tính tiền.

## Thiên lệch: nhìn vào khuôn mẫu, không chỉ từng câu

Thiên lệch có ảnh hưởng lớn nhất trong nội dung nói về con người: tài liệu tuyển dụng, đánh giá nhân viên, mô tả khách hàng và mọi nội dung xếp hạng hoặc mô tả các nhóm. Chính sách sử dụng (Usage Policy) của Anthropic cho thấy mức độ quan trọng của vấn đề khi xếp các quyết định liên quan đến từng cá nhân trong lĩnh vực việc làm, nhà ở, tài chính và chăm sóc sức khỏe vào nhóm mục đích sử dụng có rủi ro cao. Sự lệch lạc nằm trong khuôn mẫu, vì vậy hãy đọc xuyên suốt các phần mô tả thay vì chỉ đọc từng câu riêng lẻ. Ví dụ, ghi chú đánh giá mô tả nhân viên lớn tuổi là đáng tin cậy, còn nhân viên trẻ là sáng tạo. Không có câu nào riêng lẻ đáng phản đối, nhưng toàn bộ nội dung vẫn có vấn đề. Hãy tìm ngôn ngữ mang hàm ý và những giả định không được nói ra về tuổi tác, giới tính, xuất thân hoặc năng lực. Sau đó áp dụng phép thử đọc thành tiếng: cách diễn đạt ấy có đứng vững nếu được đọc trước chính nhóm người được mô tả không?

## Trong kỳ thi

Kỳ thi kiểm tra xem bạn có phân biệt được ba dạng lỗi và phản ứng đúng với từng dạng hay không, vì mỗi dạng cần cách xử lý khác nhau. Với mâu thuẫn, điểm cần nhớ là cách phản ứng: kiểm tra lại toàn bộ câu trả lời. Các phương án nhiễu thường đánh tráo cách xử lý: sửa một mâu thuẫn, xóa một từ mang hàm ý hoặc yêu cầu Claude xác nhận lại những bước nó tự bịa ra.

### Ghép cách xử lý với dạng lỗi

- **Bịa đặt:** xác minh thông tin bằng một nguồn có thẩm quyền.
- **Mâu thuẫn:** kiểm tra lại toàn bộ câu trả lời.
- **Thiên lệch:** xem xét và điều chỉnh khuôn mẫu trong toàn bộ tài liệu.

Chỉ hỏi “điều này có đúng không?” không phải là một bước kiểm tra. Anthropic nêu hai cách kiểm tra: chạy lại yêu cầu rồi so sánh kết quả với câu trả lời đầu tiên; hoặc hỏi tiếp Claude để xác minh các tuyên bố trước đó và chỉ ra điều gì không hợp lý. Cả hai cách đều tạo ra danh sách những điều cần đối chiếu với nguồn. Với các bước tạo báo cáo tồn kho, nguồn đó là tài liệu hướng dẫn của hệ thống tính tiền.

## Những bẫy trong kỳ thi

### Bẫy: Tin vào hướng dẫn tự tin, từng bước cho một hệ thống nội bộ riêng

Claude không thể truy cập phần mềm nội bộ của tổ chức, trừ khi thông tin về phần mềm đó đã được cung cấp trong cuộc trò chuyện. Vì vậy, chi tiết cụ thể nhưng không có căn cứ là dạng bịa đặt rủi ro cao nhất. Đáp án đúng xem các bước đó là chưa được xác minh và tra cứu tài liệu chính thức của hệ thống.

### Bẫy: Tin lời Claude rằng nó đã gửi email hoặc tạo tệp bên ngoài

Claude có thể bịa về khả năng của mình và không thể truy cập các công cụ chưa được tích hợp. Vì vậy, lời khẳng định đã hoàn thành là một tuyên bố cần kiểm tra như mọi tuyên bố khác. Đáp án đúng xác minh xem hành động có thực sự xảy ra hay không, thay vì xem lời khẳng định là sự xác nhận.

### Bẫy: Sửa mâu thuẫn duy nhất bạn phát hiện rồi gửi phần còn lại

Mâu thuẫn nội bộ là bằng chứng cho thấy quy trình tạo câu trả lời đã có chỗ trục trặc, vì vậy cần kiểm tra lại toàn bộ câu trả lời dựa trên nguồn. Việc sửa cho đẹp bề ngoài vẫn giữ lại một tài liệu mà chính nó đã cho thấy không thể tin cậy từng dòng.

### Bẫy: Xem thiên lệch như một từ không phù hợp duy nhất cần xóa

Thiên lệch nằm trong khuôn mẫu mô tả xuyên suốt: ai bị thêm lời dè dặt, thành tích của ai bị kèm điều kiện, nhóm nào được mô tả bằng những cách khác nhau. Xóa một cụm từ mang hàm ý sẽ không loại bỏ được sự lệch lạc; đáp án đúng điều chỉnh khuôn mẫu, không chỉ sửa một từ.

## Tình huống thực hành

Người quản lý một phòng khám da liễu nhờ Claude hướng dẫn cách tạo báo cáo gọi nhắc bệnh nhân hằng tháng trong phần mềm quản lý phòng khám. Claude chưa từng được truy cập phần mềm này hay bất kỳ tài liệu nào về nó, nhưng vẫn trả lời bằng các bước được đánh số đầy tự tin, có nêu tên menu và nút cụ thể. Người quản lý vẫn muốn dùng Claude cho những công việc khác có liên quan đến phần mềm. Cô ấy nên xử lý các bước này thế nào?

### Phương án

- **A.** Làm theo các bước như đã viết: mức độ chi tiết đến tên menu và nút cho thấy Claude có kiến thức đáng tin cậy về phần mềm này.
- **B.** Ngừng sử dụng Claude cho mọi việc liên quan đến phần mềm của phòng khám, vì Claude vừa cho thấy nó sẽ bịa ra hướng dẫn nghe có vẻ hợp lý thay vì thừa nhận không biết câu trả lời.
- **C.** Yêu cầu Claude kiểm tra lại từng bước dựa trên phần mềm của phòng khám và xác nhận tất cả đều đúng trước khi thử, để không có bước bịa đặt nào lọt qua.
- **D.** Xem các bước đó là chưa được xác minh và kiểm tra tài liệu của nhà cung cấp phần mềm hoặc phần trợ giúp tích hợp sẵn.

## Bài tập thực hành

### Thực hiện lượt rà soát ba dạng lỗi

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách phân biệt các tuyên bố có thể truy nguyên với các tuyên bố chưa được xác minh.
- Cách phản ứng khi câu trả lời tự mâu thuẫn.
- Cách đọc xuyên suốt các phần mô tả con người để phát hiện khuôn mẫu thiên lệch.
- Cách ghép đúng cách xử lý với từng dạng lỗi.

1. Thu thập ba câu trả lời thực tế của Claude từ công việc: một đầu ra có các nhận định về thông tin thực tế, một đầu ra lặp lại cùng số liệu ở nhiều chỗ, và một đầu ra mô tả hoặc so sánh con người.

   **Vì sao:** Mỗi loại câu trả lời là môi trường thường gặp của một dạng lỗi, nên lượt rà soát giúp bạn học nhận diện cả ba dạng trên tài liệu thực tế.

   **Bạn cần thấy:** Ba câu trả lời sẵn sàng để kiểm tra: tài liệu có tuyên bố, tài liệu có số liệu và tài liệu nói về con người.

2. Rà soát hiện tượng bịa đặt: gạch dưới mọi chi tiết cụ thể không xuất phát từ tài liệu bạn cung cấp—số liệu, tên, tài liệu tham chiếu, hướng dẫn—và đánh dấu từng chi tiết là có thể truy nguyên hoặc chưa được xác minh.

   **Vì sao:** Tính cụ thể là đặc trưng của hiện tượng bịa đặt, vì thế mọi chi tiết cụ thể chưa có căn cứ đều cần được truy nguyên.

   **Bạn cần thấy:** Một câu trả lời đã được đánh dấu, trong đó mọi chi tiết cụ thể đều có một trong hai nhãn.

3. Rà soát mâu thuẫn: so sánh mọi con số, ngày tháng và kết luận xuất hiện nhiều hơn một lần; nếu hai chỗ không khớp, đánh dấu toàn bộ câu trả lời để kiểm tra lại.

   **Vì sao:** Nhận định mà kỳ thi kiểm tra là: mâu thuẫn làm mất độ tin cậy của quy trình, chứ không chỉ của câu có mâu thuẫn.

   **Bạn cần thấy:** Hoặc là đã đối chiếu nhất quán, hoặc là đánh dấu toàn bộ câu trả lời; tuyệt đối không chỉ sửa một con số riêng lẻ.

4. Rà soát thiên lệch: đọc xuyên suốt các phần mô tả con người và ghi lại xem những người hoặc nhóm khác nhau có được mô tả bằng những cách khác nhau một cách có hệ thống hay không.

   **Vì sao:** Toàn bộ đầu ra vẫn có thể chứa thiên lệch dù từng câu riêng lẻ không có gì đáng phản đối; điều cần tìm là khuôn mẫu xuyên suốt.

   **Bạn cần thấy:** Ghi chú xem khuôn mẫu diễn đạt có vượt qua phép thử đọc thành tiếng hay không.

5. Với mỗi điểm cần lưu ý, ghi lại cách xử lý đúng: xác minh bằng nguồn, kiểm tra lại toàn bộ câu trả lời, hay điều chỉnh khuôn mẫu.

   **Vì sao:** Gọi tên cách xử lý giúp củng cố mối liên hệ mà kỳ thi kiểm tra: mỗi dạng lỗi có cách khắc phục riêng.

   **Bạn cần thấy:** Kế hoạch xử lý gồm ba dòng, mỗi dòng dành cho một dạng lỗi.

## Nguồn

- [Claude đang đưa ra câu trả lời không chính xác hoặc gây hiểu lầm. Chuyện gì đang xảy ra?](https://support.claude.com/en/articles/8525154-claude-is-providing-incorrect-or-misleading-responses-what-s-going-on) — Anthropic
- [Claude đang tạo liên kết không hoạt động và tuyên bố sai rằng đã gửi email hoặc tạo tài liệu bên ngoài. Chuyện gì đang xảy ra?](https://support.claude.com/en/articles/8241188-claude-is-producing-links-that-don-t-work-and-falsely-claiming-that-it-has-sent-emails-or-produced-external-documents-what-s-going-on) — Anthropic
- [Dữ liệu huấn luyện của Claude cập nhật đến thời điểm nào?](https://support.claude.com/en/articles/8114494-how-up-to-date-is-claude-s-training-data) — Anthropic
- [Giảm hiện tượng bịa đặt](https://platform.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/reduce-hallucinations) — Anthropic
- [Chính sách sử dụng (Usage Policy)](https://www.anthropic.com/legal/aup) — Anthropic
- [Hướng dẫn kỳ thi Claude Certified Associate – Foundations](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=2)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/2-output-evaluation)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-2)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-2)**

**Bài học trước:** [Đánh giá độ chính xác và tính đầy đủ của đầu ra](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-1-accuracy-completeness)

**Bài học tiếp theo:** [Kỹ thuật kiểm chứng thông tin và xác minh đầu ra](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-3-fact-checking-validation)
