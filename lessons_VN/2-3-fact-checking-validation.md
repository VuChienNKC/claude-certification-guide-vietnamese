# Kỹ thuật kiểm chứng thông tin và xác minh đầu ra

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-3-fact-checking-validation

**Miền:** 2

**Nhiệm vụ:** 2.3

## Những điều bạn cần biết

Xác minh là kiểm tra các tuyên bố trong câu trả lời bằng thông tin có thể xác nhận chúng. Mục tiêu này cung cấp cho hoạt động đánh giá ở mục tiêu 2.1 những công cụ cần thiết, được sắp xếp từ ít tốn công nhất đến nhiều nhất. Bước cân nhắc giúp quyết định mức độ kiểm tra cần thiết cho từng đầu ra. Tài liệu gốc (primary document) là hồ sơ ban đầu: ấn phẩm chính thức, văn bản của cơ quan quản lý, tiêu chí do bên cấp tài trợ công bố hoặc hồ sơ của tổ chức.

Hãy xét một công ty chuyển nhà. Văn phòng nhờ Claude soạn thư báo giá dựa trên ghi chú khảo sát và bảng giá đính kèm. Thư nêu tổng chi phí và quy định đỗ xe của hội đồng địa phương trên tuyến phố đó. Claude cũng soạn ý tưởng cho bản tin nội bộ.

Không nên xem Claude là nguồn duy nhất để xác nhận thông tin là đúng, và câu trả lời có hệ quả quan trọng cần được xem xét cẩn thận. Claude có thể tạo ra nội dung trôi chảy, cụ thể, trông có vẻ đúng nhưng lại sai nghiêm trọng. Chỉ riêng tính cụ thể không phải bằng chứng về độ chính xác.

## Bắt đầu từ cách kiểm tra ít tốn công nhất: nguồn bạn đã cung cấp

Với câu trả lời được tạo từ tài liệu đính kèm, bước kiểm tra đầu tiên là đối chiếu với tệp đính kèm. Tài liệu đã có sẵn trong cuộc trò chuyện. Hãy kiểm tra từng con số, mục và tuyên bố xem có khớp với tài liệu hay không. Đây là thói quen trong mục tiêu 2.1 được áp dụng như một kỹ thuật, chỉ tốn vài phút. Tổng chi phí được đối chiếu với ghi chú khảo sát và bảng giá. Chỉ dùng cách kiểm tra tốn công hơn khi nguồn đã cung cấp không thể giải quyết được câu hỏi.

## Nguồn độc lập, có thẩm quyền và là tài liệu gốc

Các tuyên bố về thông tin bên ngoài tài liệu đã cung cấp cần được kiểm tra bằng nguồn bên ngoài. Tài liệu đính kèm không thể xác nhận quy định đỗ xe vì thông tin đó không xuất phát từ các tài liệu ấy. Kết quả tìm kiếm trên web có kèm trích dẫn “để bạn có thể dễ dàng tự xác minh nguồn”. Người dùng được khuyến nghị đối chiếu các nguồn được trích dẫn và dùng nguồn có thẩm quyền khi đưa ra quyết định quan trọng. Bài viết về hiện tượng bịa đặt trong Help Center khuyên nên xem lại các nguồn Claude trích dẫn, vì kiểm tra bản gốc giúp phát hiện việc diễn giải sai. Trích dẫn là để được kiểm tra.

Tiêu chuẩn cần hướng đến là tài liệu gốc. Bản tóm tắt thứ hai do AI tạo, bài đăng trên diễn đàn hoặc câu trả lời trước đó của Claude không phải xác minh độc lập. Nếu cách kiểm tra thừa hưởng lỗi từ chính thứ đang được kiểm tra thì nó chẳng chứng minh được điều gì. Với quy định đỗ xe, tài liệu gốc là trang web đã công bố của hội đồng địa phương. Tìm kiếm trên web ngay trong claude.ai là một cách hợp lệ để truy cập trang đó. Chính nguồn thông tin mới là căn cứ xác minh, chứ không phải thao tác tìm kiếm.

## Giúp người đọc truy nguyên câu trả lời

Câu trả lời có thể truy nguyên cho biết từng tuyên bố xuất phát từ đâu, nhờ đó có thể kiểm tra được. Câu trả lời không thể truy nguyên thì không được mặc nhiên cho là đáng tin. Với tài liệu dài, hướng dẫn viết prompt của Anthropic khuyên yêu cầu Claude trích dẫn các phần liên quan của nguồn trước khi thực hiện nhiệm vụ. Với công việc nghiên cứu, hướng dẫn khuyên yêu cầu Claude xác minh thông tin qua nhiều nguồn. Đối với thư báo giá, hãy yêu cầu Claude nêu nguồn của từng tuyên bố và cách nó đưa ra từng kết luận. Sau đó, kiểm tra chọn mẫu các tuyên bố quan trọng. Khi một con số duy nhất quyết định lựa chọn, hãy xác nhận con số đó tại hai nguồn kiểm chứng độc lập trước khi gửi đi.

## Tính tương xứng: cân nhắc mức độ kiểm chứng

Nỗ lực xác minh cần tương xứng với hệ quả. Khách hàng sẽ dựa vào tổng chi phí để quyết định, vì vậy con số này cần được xác nhận bằng hai nguồn kiểm chứng độc lập. Ý tưởng cho bản tin chỉ cần được đọc lại. Bỏ qua việc kiểm tra tuyên bố có hệ quả quan trọng là lỗi rõ ràng. Nhưng kiểm tra quá mức công việc ít rủi ro cũng không phải cách làm đúng hay an toàn. Thời gian dành để kiểm tra ba lần câu chữ của bản tin mà không ai hành động dựa vào sẽ làm mất thời gian kiểm tra tổng chi phí.

Yêu cầu Claude tự kiểm tra câu trả lời có phạm vi sử dụng hạn chế. Hướng dẫn viết prompt của Anthropic cho biết việc tự kiểm tra có thể phát hiện lỗi, đặc biệt trong lập trình và toán học. Hướng dẫn nêu một ngoại lệ: Claude Opus 5 có thể xác minh tốt công việc của chính mình mà không cần yêu cầu. Chỉ dẫn tự kiểm tra được viết cho các mô hình trước đó có thể khiến mô hình này kiểm tra quá mức. Tự kiểm tra là bước đầu ít tốn công để tìm lỗi tính toán và mâu thuẫn. Đó không phải xác minh độc lập: vẫn là cùng mô hình với cùng điểm mù.

## Trong kỳ thi

Câu hỏi kiểm tra các kỹ thuật này và khi nào mức kiểm tra là tương xứng, cả về tránh kiểm tra quá ít lẫn quá nhiều. Bẫy thường gặp nhất là xem tự kiểm tra như thể đó là xác minh. Một phương án yêu cầu Claude xác nhận, kiểm tra lại hoặc tự đánh giá câu trả lời, rồi gọi câu trả lời tự tin ấy là xác minh. Phần giải thích mẫu trong hướng dẫn cho biết vì sao cách đó không đúng: mức độ tự tin do chính hệ thống báo cáo không phải tín hiệu đáng tin cậy về độ chính xác.

### Khái niệm then chốt

Khi một câu hỏi về xác minh đưa ra nhiều kế hoạch kiểm tra, hãy đánh giá từng kế hoạch bằng hai câu hỏi:

1. Có thông tin độc lập nào được đưa vào quá trình kiểm tra không?
2. Mức độ kiểm tra có tương xứng với tầm quan trọng của từng tuyên bố không?

Đáp án đúng đáp ứng cả hai câu hỏi. Các phương án nhiễu thường không đáp ứng một trong hai: tự kiểm tra và dùng nguồn dẫn lại cùng nội dung chưa được kiểm chứng không bảo đảm tính độc lập; kiểm tra tối đa mọi nội dung như nhau thì không tương xứng.

## Những bẫy trong kỳ thi

### Bẫy: Yêu cầu Claude xác nhận hoặc kiểm tra lại các tuyên bố của mình rồi gọi đó là xác minh

Không có thông tin độc lập nào được đưa vào quá trình kiểm tra, và cùng điểm mù đã tạo ra lỗi có thể sẽ xác nhận lại lỗi ấy. Tự kiểm tra là bước đầu hợp lệ để tìm lỗi nhỏ và mâu thuẫn, nhưng đáp án đúng luôn tìm đến nguồn độc lập để kiểm tra các tuyên bố quan trọng.

### Bẫy: Đối chiếu một tuyên bố với bản tóm tắt AI khác hoặc câu trả lời trước đây của Claude

Xác minh vòng tròn sẽ thừa hưởng lỗi của nội dung đang được kiểm tra. Tính độc lập là điều khiến việc xác minh có ý nghĩa, vì vậy đáp án đúng tìm đến tài liệu gốc: ấn phẩm chính thức, tiêu chí đã công bố hoặc hồ sơ của tổ chức.

### Bẫy: Xác minh mọi câu với cùng mức độ kiểm tra tối đa, bất kể hệ quả

Kỹ năng được kiểm tra là tính tương xứng: việc kiểm tra chuyên sâu như nhau sẽ tiêu tốn thời gian hạn chế vào phần văn bản không ảnh hưởng đến quyết định. Đó là cách làm quá mức, không phải lựa chọn an toàn. Đáp án đúng tập trung kiểm tra vào những tuyên bố làm cơ sở cho quyết định.

## Tình huống thực hành

Điều phối viên tình nguyện của một tuyến đường sắt di sản nhờ Claude soạn đơn xin tài trợ. Bản nháp nêu số lượt khách hằng năm, tỷ lệ phần trăm tăng lượt học sinh tham quan và tuyên bố rằng tuyến đường sắt đáp ứng tiêu chí đủ điều kiện đã công bố của bên cấp tài trợ. Cô ấy chỉ có một buổi tối, không đủ thời gian xác minh chuyên sâu mọi dòng, và không được phép chỉ dựa vào lời Claude. Kế hoạch xác minh nào phù hợp trước khi nộp?

### Phương án

- **A.** Yêu cầu Claude kiểm tra lại toàn bộ bản nháp cẩn thận và xác nhận từng tuyên bố, sau đó nộp khi Claude vẫn khẳng định các số liệu là đúng.
- **B.** Đối chiếu số lượt khách với hồ sơ của chính tuyến đường sắt, tính lại tỷ lệ phần trăm từ các hồ sơ đó, và đối chiếu tuyên bố về điều kiện được nhận tài trợ với tài liệu tiêu chí đã công bố của bên cấp tài trợ.
- **C.** Đối chiếu các tuyên bố về điều kiện được nhận tài trợ với bản tóm tắt tiêu chí mà Claude đã tạo trước đó trong cuộc trò chuyện, đồng thời xác nhận số liệu lượt khách nhất quán ở mọi chỗ trong bản nháp.
- **D.** Xác minh độc lập từng câu trong đơn với cùng mức độ chuyên sâu, kể cả phần lịch sử mô tả, trước khi bất kỳ ai xem tài liệu.

## Bài tập thực hành

### Lập kế hoạch xác minh cho một tài liệu thực tế

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 35 phút

**Bạn sẽ học được**

- Cách gọi tên nguồn có thẩm quyền để xác nhận từng tuyên bố.
- Cách xếp hạng tuyên bố theo hệ quả và chọn mức độ kiểm tra.
- Cách làm cho câu trả lời có thể truy nguyên trước khi kiểm tra chọn mẫu.
- Cách nhận biết những gì chỉ tự kiểm tra có thể bỏ sót.

1. Chọn một tài liệu do Claude soạn trong công việc, có ít nhất ba tuyên bố có thể kiểm tra: một con số, một thông tin thực tế từ bên ngoài tài liệu đã cung cấp và một tuyên bố về việc đáp ứng yêu cầu đã công bố.

   **Vì sao:** Ba loại tuyên bố cần ba cách xác minh khác nhau; đây là bộ công cụ thu nhỏ.

   **Bạn cần thấy:** Một tài liệu có ít nhất ba tuyên bố được gạch dưới và phân loại.

2. Với mỗi tuyên bố, nêu tên nguồn có thẩm quyền có thể xác nhận nó: hồ sơ của tổ chức bạn, ấn phẩm chính thức hoặc tiêu chí đã công bố.

   **Vì sao:** Một tuyên bố không có nguồn cụ thể thì không thể truy nguyên, và không nên mặc nhiên cho là đáng tin.

   **Bạn cần thấy:** Mỗi tuyên bố được ghép với một nguồn cụ thể hoặc được đánh dấu là không thể truy nguyên.

3. Xếp các tuyên bố theo hệ quả: xác nhận bằng hai nguồn hoặc cách kiểm tra độc lập đối với con số then chốt; đọc lại phần câu chữ ít ảnh hưởng đến quyết định; viết một câu giải thích vì sao mỗi nội dung cần mức kiểm tra đó.

   **Vì sao:** Cân nhắc mức kiểm tra tương xứng là kỹ năng phán đoán mà kỳ thi kiểm tra; câu giải thích buộc bạn trình bày rõ lập luận.

   **Bạn cần thấy:** Kế hoạch kiểm tra có mức độ khác nhau rõ ràng tùy theo mức độ quan trọng.

4. Yêu cầu Claude nêu nguồn của từng tuyên bố còn lại và cách nó đưa ra từng kết luận, sau đó kiểm tra chọn mẫu những tuyên bố quan trọng.

   **Vì sao:** Khả năng truy nguyên biến việc đọc lại chung chung thành đánh giá có thể kiểm tra, đồng thời tập trung nỗ lực vào nơi cần thiết.

   **Bạn cần thấy:** Các tuyên bố được gắn với nguồn và lập luận; những tuyên bố quan trọng được xác nhận.

5. Thực hiện kế hoạch và ghi lại tuyên bố nào sai, nguồn nào phát hiện ra sai sót, và kế hoạch chỉ tự kiểm tra sẽ bỏ sót điều gì.

   **Vì sao:** So sánh với cách chỉ tự kiểm tra giúp nguyên tắc độc lập trở nên cụ thể trong chính công việc của bạn.

   **Bạn cần thấy:** Bản ghi ngắn về các lỗi phát hiện được, nguồn giúp phát hiện và điểm mù của việc chỉ tự kiểm tra.

## Nguồn

- [Bật và sử dụng tính năng tìm kiếm trên web](https://support.claude.com/en/articles/10684626-enable-and-use-web-search) — Anthropic
- [Claude đang đưa ra câu trả lời không chính xác hoặc gây hiểu lầm. Chuyện gì đang xảy ra?](https://support.claude.com/en/articles/8525154-claude-is-providing-incorrect-or-misleading-responses-what-s-going-on) — Anthropic
- [Sử dụng tính năng nghiên cứu trên Claude](https://support.claude.com/en/articles/11088861-use-research-on-claude) — Anthropic
- [Các phương pháp viết prompt tốt nhất](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Anthropic
- [Hướng dẫn kỳ thi Claude Certified Associate – Foundations](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=2)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/2-output-evaluation)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-2)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-2)**

**Bài học trước:** [Nhận diện hiện tượng bịa đặt, mâu thuẫn và thiên lệch](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-2-hallucinations-inconsistencies-bias)

**Bài học tiếp theo:** [Khi nào cần người đánh giá hoặc xác minh bổ sung](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-4-human-review-escalation)
