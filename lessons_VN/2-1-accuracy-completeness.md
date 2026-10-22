# Đánh giá độ chính xác và tính đầy đủ của đầu ra

Nguồn: https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-1-accuracy-completeness

**Miền:** 2  
**Nhiệm vụ:** 2.1

## Những điều bạn cần biết

Rà soát đầu ra là kiểm tra những gì Claude viết trước khi có người dựa vào đó. Việc rà soát đặt ra hai câu hỏi. **Độ chính xác** hỏi xem các chi tiết cụ thể có đúng không: con số, tên, ngày tháng, chức danh, số liệu được trích dẫn và nội dung dẫn chiếu đến tài liệu hoặc quy định. **Tính đầy đủ** hỏi xem có nội dung nào bị thiếu không. Cả hai đều cần được kiểm tra dựa trên nguồn, tức tài liệu dùng để tạo ra đầu ra.

Một chủ tiệm bánh đính kèm hợp đồng mới của nhà cung cấp bột mì và yêu cầu Claude tóm tắt. Đối tác kinh doanh sẽ dựa vào bản tóm tắt để quyết định có ký hợp đồng hay không. Bản tóm tắt đọc trôi chảy nhưng có thể ghi sai giá mỗi bao hoặc bỏ sót một điều khoản.

## Quan điểm của người rà soát

Hãy xem mọi đầu ra của Claude là bản nháp đầu tiên chất lượng cao do một đồng nghiệp tài giỏi viết, nhưng đôi khi có thể tự tin mà vẫn sai. Trung tâm Trợ giúp giải thích lý do: Claude “đôi khi có thể đưa ra câu trả lời không chính xác hoặc gây hiểu lầm”, và người dùng “không nên dựa vào Claude như nguồn duy nhất để xác nhận thông tin là đúng”. Văn phong trôi chảy và sự tự tin là đặc tính của cách viết, không phải bằng chứng về sự thật. Claude viết trôi chảy dù đúng hay sai, nên một đầu ra đọc rất hay vẫn chưa qua bước kiểm tra nào. Bản tóm tắt của tiệm bánh đọc vẫn trôi chảy ngay cả khi ghi sai giá.

Trách nhiệm kiểm tra thuộc về người gửi nội dung do Claude soạn. Người đó phải chịu trách nhiệm về nội dung trước nhóm, các thành viên hoặc nhà tài trợ của mình. Rà soát là bước biến bản nháp thành công việc mà bạn có thể đứng tên. Đây không phải việc làm thêm tùy chọn chỉ dành cho người cẩn thận.

## Độ chính xác: Các chi tiết cụ thể có đúng không?

Trước tiên, hãy kiểm tra các chi tiết cụ thể, ưu tiên theo hậu quả nếu chi tiết đó sai: những chi tiết nếu sai sẽ gây tốn kém hoặc xấu hổ nhất. Điều đó thường có nghĩa là kiểm tra con số làm căn cứ cho quyết định, tên ở đầu thư và ngày đến hạn. Một bản nháp có hai mươi câu đúng nhưng một tổng số từng phần bị tính sai vẫn là bản nháp sai nếu cuộc họp đưa ra quyết định dựa trên tổng số từng phần đó. Với tiệm bánh, giá mỗi bao cần được kiểm tra đầu tiên vì đối tác sẽ quyết định dựa trên giá này.

## Tính đầy đủ: Có nội dung nào bị thiếu không?

Tính đầy đủ khó kiểm tra hơn vì bạn phải tìm nội dung đã bị bỏ mất, thay vì chỉ phát hiện thông tin hiện có nhưng sai. Một bản tóm tắt trôi chảy có thể bỏ mất một mục, một chủ đề hoặc một lưu ý quan trọng mà câu chữ không để lộ khoảng trống. Vì vậy, hãy đối chiếu với chính nguồn tài liệu, không phải trí nhớ của bạn về nguồn. Lần theo cấu trúc của nguồn: các mục, quỹ, chủ đề hoặc hạng mục chi tiết. Xác nhận mỗi yếu tố đều có trong đầu ra hoặc đã được chủ động loại trừ. Chỉ đọc đầu ra rồi gật đầu là cách khiến nội dung bị bỏ sót lọt qua. Chủ tiệm bánh đánh dấu từng điều khoản trong hợp đồng và đối chiếu với bản tóm tắt.

Luôn kiểm tra độ chính xác trước: chi tiết cụ thể sai là lỗi dễ gặp nhất và nhanh phát hiện nhất. Kiểm tra tính đầy đủ sau, vì bước này cũng cần mở nguồn tài liệu.

## Đối chiếu với đầu vào

Khi đầu ra được tạo từ tài liệu đính kèm, bước kiểm tra đầu tiên là xem tài liệu đính kèm. Tài liệu đã có ngay trong cuộc trò chuyện và việc so sánh chỉ mất vài phút. Hướng dẫn viết prompt của Anthropic cũng khuyên làm tương tự với tài liệu dài: yêu cầu Claude trích dẫn những phần liên quan trong nguồn trước khi thực hiện nhiệm vụ. Trong cuộc trò chuyện, hãy hỏi Claude mỗi con số hoặc nhận định trong đầu ra xuất phát từ đâu trong tài liệu đính kèm. Sau đó, kiểm tra chọn mẫu các nhận định quan trọng tại những vị trí đó. Đầu ra có nhận định truy được về nguồn sẽ chỉ mất vài phút để kiểm tra. Đầu ra không thể truy nguồn sẽ không được mặc nhiên tin tưởng. Chủ tiệm bánh hỏi giá được lấy từ đâu rồi đọc điều khoản tương ứng.

Chỉ hỏi Claude có chắc chắn hay không chưa phải là kiểm tra. Chính mô hình đã mắc lỗi sẽ lặp lại lỗi đó với cùng sự tự tin vì không có thông tin mới nào được đưa vào quá trình kiểm tra. Cách kiểm tra có giá trị là so sánh đầu ra với nguồn.

## Trong kỳ thi

Miền này chiếm tỷ trọng lớn hơn mọi miền khác trong kỳ thi, và mọi mục tiêu trong miền đều dựa trên quan điểm của người rà soát. Tuyên bố cốt lõi của chứng chỉ là người đạt chứng chỉ có thể được tin cậy khi xử lý những gì Claude tạo ra. Sự tin cậy đó được hình thành ở giai đoạn rà soát, không phải giai đoạn viết prompt. Khi đã có quan điểm đúng, các nội dung còn lại của miền sẽ theo đó mà rõ ràng: nhận diện dạng lỗi, xác thực nhận định và biết khi nào cần chuyển cấp xử lý. Trong đề thi, sự tự tin do chính Claude báo cáo luôn là phương án gây nhiễu, không phải bước kiểm tra.

### Ví dụ về cách tiếp cận

Câu hỏi mẫu của Miền 2 trong hướng dẫn kỳ thi kiểm tra mục tiêu này. Claude tóm tắt một quy định và trích dẫn một tiểu mục cụ thể. Hành động đúng là xác minh trích dẫn đó dựa trên văn bản chính thức trước khi gửi cho nhóm tuân thủ. Các đáp án sai được nêu rõ là tin vào sự tự tin Claude thể hiện và viết lại bản tóm tắt cho trang trọng hơn. Sự cẩn trọng quan trọng hơn sự tự tin; trau chuốt không bao giờ thay thế được tính chính xác.

## Bẫy trong kỳ thi

### Bẫy: Gửi đầu ra vì nội dung đọc trôi chảy hoặc Claude thể hiện sự tự tin cao

Văn phong trôi chảy là đặc tính của cách viết, còn sự tự tin không phải tín hiệu đáng tin cậy về độ chính xác; cả hai đều chưa kiểm chứng sự thật. Đáp án đúng luôn đối chiếu đầu ra với tài liệu nguồn trước khi lưu hành.

### Bẫy: Yêu cầu Claude tự xác nhận công việc của mình rồi xem câu trả lời “chắc chắn đúng” là một lần rà soát

Không có thông tin mới nào được đưa vào quá trình kiểm tra: chính mô hình đã tạo ra lỗi sẽ tự tin nhắc lại lỗi đó. Tự kiểm tra được ngụy trang thành rà soát là một trong những phương án gây nhiễu phổ biến của miền này, thường xuất hiện trong câu hỏi về những đầu ra cần được kiểm tra kỹ nhất.

### Bẫy: Xác minh một con số cụ thể được nêu trong khi đề bài gợi ý có cả một mục bị bỏ sót

Chỉ kiểm tra độ chính xác sẽ bỏ lỡ câu hỏi thứ hai trong quá trình rà soát. Khi đề bài cho thấy nguồn có nhiều nội dung hơn đầu ra, đáp án đúng sẽ lần theo cấu trúc nguồn để kiểm tra tính đầy đủ, chứ không chỉ xem các chi tiết đang thu hút sự chú ý.

## Tình huống thực hành

Một thủ quỹ của hội hướng đạo nhờ Claude soạn báo cáo tài chính thường niên cho đại hội thường niên (AGM) dựa trên bảng tính sổ sách của hội. Bản nháp đọc rất trôi chảy, nhưng thủ quỹ phải chắc rằng báo cáo đúng và không thiếu nội dung nào, chứ không thể chỉ tin lời Claude. Trước khi gửi báo cáo, thủ quỹ nên làm gì?

- **Phương án A:** Hỏi Claude liệu Claude có tự tin rằng báo cáo chính xác và đầy đủ không, rồi gửi tài liệu khi Claude trả lời có.
- **Phương án B:** Chỉnh sửa báo cáo sang cách diễn đạt kế toán trang trọng hơn để báo cáo chịu được sự xem xét kỹ lưỡng của các thành viên tại cuộc họp.
- **Phương án C:** Đối chiếu từng con số được nêu với bảng tính, sau đó rà lại danh sách các quỹ được theo dõi trong sổ sách để xác nhận mọi quỹ đều xuất hiện trong bản tóm tắt.
- **Phương án D:** Gửi báo cáo nguyên trạng: các con số có vẻ hợp lý, định dạng chuyên nghiệp và hạn chót của bộ tài liệu AGM đang đến gần.

## Bài tập thực hành

### Thực hiện quy trình rà soát hai lượt

**Độ khó:** Cơ bản (1/4)

**Thời lượng:** 25 phút

**Bạn sẽ học được**

- Cách kiểm tra mọi chi tiết cụ thể trong đầu ra dựa trên tài liệu nguồn.
- Cách ưu tiên kiểm tra độ chính xác theo mức độ hậu quả.
- Cách lần theo cấu trúc nguồn để phát hiện nội dung bị bỏ sót.
- Cách giúp đầu ra có thể truy nguồn bằng cách hỏi từng nhận định xuất phát từ đâu.

Chọn một tài liệu Claude đã soạn dựa trên nguồn thực tế, chẳng hạn bản tóm tắt, báo cáo hoặc phần trình bày dữ liệu; hoặc tạo một tài liệu ngay lúc này từ bảng tính hay tài liệu bạn thực sự sử dụng.

**Vì sao:** Thói quen rà soát hai lượt chỉ chứng tỏ giá trị khi áp dụng vào công việc thật, khi bạn biết nguồn có nội dung gì và việc bỏ sót sẽ gây hậu quả ra sao.

**Bạn cần thấy:** Bản nháp của Claude và tài liệu nguồn đặt cạnh nhau trong cùng một cuộc trò chuyện.

**Lượt kiểm tra độ chính xác:** Liệt kê mọi chi tiết cụ thể trong đầu ra — con số, tên, ngày tháng và nội dung dẫn chiếu — rồi đối chiếu từng chi tiết với nguồn, bắt đầu từ những chi tiết mà người ra quyết định hoặc người đọc sẽ dựa vào.

**Vì sao:** Ưu tiên theo mức độ hậu quả giúp dành thời gian kiểm tra hạn chế cho những lỗi gây tốn kém nhất.

**Bạn cần thấy:** Danh sách chi tiết đã đánh dấu: được xác nhận, sai hoặc không thể xác minh.

**Lượt kiểm tra tính đầy đủ:** Lần theo cấu trúc nguồn — các mục, quỹ, chủ đề hoặc hạng mục chi tiết — và xác nhận từng yếu tố đều có trong đầu ra hoặc đã được chủ động loại trừ.

**Vì sao:** Nội dung bị bỏ sót không để lại dấu vết trong câu chữ; chỉ cấu trúc của nguồn mới cho thấy những gì cần có.

**Bạn cần thấy:** Dấu kiểm bên cạnh từng yếu tố của nguồn, hoặc ghi chú giải thích lý do yếu tố đó không có.

Yêu cầu Claude chỉ ra từng nhận định còn lại xuất phát từ đâu trong nguồn, rồi kiểm tra chọn mẫu các nhận định quan trọng.

**Vì sao:** Có thể xác minh đầu ra truy được nguồn chỉ trong vài phút; đầu ra không truy được nguồn sẽ không được mặc nhiên tin tưởng.

**Bạn cần thấy:** Từng nhận định gắn với một vị trí trong nguồn, trong đó các nhận định có ảnh hưởng lớn đã được xác nhận.

Ghi lại những gì hai lượt kiểm tra phát hiện và khoảng thời gian đã sử dụng.

**Vì sao:** Thói quen được duy trì khi bạn thấy được chi phí và lợi ích của nó trên công việc của chính mình.

**Bạn cần thấy:** Một ghi chú ngắn nêu lỗi phát hiện được, nội dung bị bỏ sót và số phút đã dùng.

## Nguồn

- [Claude is providing incorrect or misleading responses. What's going on?](https://support.claude.com/en/articles/8525154-claude-is-providing-incorrect-or-misleading-responses-what-s-going-on) — Anthropic
- [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

**[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=2)** · **[Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/2-output-evaluation)** · **[Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-2)** · **[Thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-2)**

**Bài học trước:** [Điều chỉnh chiến lược theo loại nhiệm vụ](https://claudecertificationguide.com/ccao-f/learn/1-prompting-task-execution/1-4-task-type-strategies)

**Bài học tiếp theo:** [Nhận diện hiện tượng bịa đặt, mâu thuẫn và thiên lệch](https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-2-hallucinations-inconsistencies-bias)
