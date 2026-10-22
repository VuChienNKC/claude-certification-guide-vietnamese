# Điều chỉnh cách tiếp cận dựa trên phản hồi và kết quả

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/7-troubleshooting-optimisation/7-2-adjusting-from-feedback

**Miền:** 7

**Nhiệm vụ:** 7.2

## Những điều bạn cần biết

Một vòng điều chỉnh là thay đổi yêu cầu, chạy lại và đánh giá đầu ra. Mục tiêu 1.3 đã dạy cách đưa ra phản hồi tốt trong một cuộc trò chuyện. Mục tiêu này trình bày cách tổ chức quá trình điều chỉnh một cách có hệ thống. Một vòng điều chỉnh có hệ thống cho bạn nhiều hơn một kết quả khác: nó tạo ra kiến thức có thể áp dụng lại vào ngày mai và giải thích cho đồng nghiệp. Muốn vậy, cần ba nguyên tắc: mỗi lần chỉ thay đổi một yếu tố, giữ nguyên đầu vào thử nghiệm và đánh giá kết quả dựa trên tiêu chí đã nêu trước khi xem đầu ra.

Một cửa hàng bán thảm dùng Claude soạn thư báo giá gửi sau mỗi lần đến đo đạc. Khách hàng liên tục gọi điện để hỏi tổng giá.

## Mỗi lần chỉ thay đổi một yếu tố

Thay đổi từng yếu tố một cho biết điều gì đã cải thiện đầu ra. Giả sử chủ cửa hàng chỉ thay đổi dòng mô tả đối tượng đọc và lá thư được cải thiện. Như vậy, vấn đề nằm ở dòng mô tả đối tượng đọc; bài học này có thể áp dụng cho mọi nhiệm vụ tương tự. Nếu cô ấy thay đổi đồng thời cách diễn đạt, mô hình và tài liệu ví dụ đính kèm, lá thư được cải thiện nhưng không ai biết yếu tố nào trong ba yếu tố đã có tác dụng. Đến lần làm nhiệm vụ tương tự vào ngày mai, bạn vẫn không biết yếu tố nào đã giúp ích. Thay đổi nhiều thứ cùng lúc trông có vẻ hiệu quả cho đến khi bạn cần tạo ra kết quả tốt lần thứ hai.

Help Center của Anthropic nói rằng một prompt hiệu quả cần có nhiều ngữ cảnh nhất có thể. Khi nói về điều chỉnh, tài liệu chỉ dừng ở việc đưa phản hồi, làm rõ và yêu cầu Claude viết lại. Nguyên tắc mỗi lần chỉ thay đổi một biến là phương pháp làm việc chuyên nghiệp thông thường.

## Giữ nguyên đầu vào thử nghiệm

Thử prompt mới trên một tài liệu mới không cho bạn biết gì, vì có hai yếu tố đã thay đổi. Kết quả tốt hơn có thể chỉ vì đầu vào mới dễ hơn. Giữ nguyên đầu vào thử nghiệm (cùng một khóa học, báo cáo hoặc tệp nguồn) giúp việc so sánh giữa các vòng có ý nghĩa. Với chủ cửa hàng, đó là ghi chú đo đạc của cùng một khách hàng, được sử dụng ở mọi vòng. Chỉnh sửa một tin nhắn cũ sẽ tạo ra phiên bản khác của cuộc trò chuyện, với các Artifacts riêng. Mỗi vòng có thể bắt đầu từ cùng một đầu vào và được so sánh với vòng trước.

## Nêu tiêu chí trước khi xem kết quả

“Tốt hơn” không phải là một tiêu chí. “Khách hàng có thể tìm thấy tổng giá trong vòng năm giây” mới là tiêu chí. Nêu tiêu chí trước giúp bạn không thay đổi cách đánh giá theo những gì bản nháp mới tình cờ làm tốt. Việc thay đổi cách đánh giá như vậy khiến bạn chấp nhận một vòng điều chỉnh dù nó chẳng khắc phục được gì. Tiêu chí đã nêu cũng giúp bạn tận dụng phản hồi của người khác. Bản nháp bị trả lại cộng với một tiêu chí sẽ cho biết yêu cầu nào chưa đạt. “Người quản lý không thích nó” thì chẳng xác định được điều gì.

## Phản hồi đến từ độc giả, không chỉ từ văn bản

Những kết quả quan trọng thường đến từ bên ngoài cuộc trò chuyện. Đồng nghiệp nói giọng điệu chưa phù hợp. Quản lý trả lại bản nháp. Độc giả hỏi cùng một câu làm rõ đến ba lần. Những thông tin này thường chỉ ra khoảng trống chính xác hơn việc bạn tự đọc lại văn bản. Khách hàng gọi hỏi tổng giá là một ví dụ về kết quả như vậy. Coi những phản hồi này là đầu vào cho vòng tiếp theo, thay vì coi chúng là thông tin gây nhiễu, sẽ giúp bạn cải tiến tính hữu dụng của đầu ra. Nếu bỏ qua chúng, bạn chỉ tiếp tục điều chỉnh vẻ ngoài của đầu ra.

## Biết khi nào nên dừng điều chỉnh

Điều chỉnh giả định rằng cách tiếp cận là đúng, chỉ có cách thực hiện chưa ổn. Khi vài vòng điều chỉnh có mục tiêu rõ ràng vẫn không làm đầu ra thay đổi, giả định đó không còn đúng. Nhiệm vụ có thể cần tài liệu nguồn khác, một tính năng như web search hoặc Research, hay một cài đặt khác. Cũng có thể đây là công việc không nên giao cho AI. Vòng điều chỉnh thất bại thứ ba là tín hiệu quay lại danh sách nguyên nhân ở mục 7.1 và chẩn đoán lại. Vòng thứ tư với cách diễn đạt hơi khác chỉ tiếp tục kiểm tra một giả định đã thất bại. Nếu đến vòng thứ ba khách hàng của chủ cửa hàng vẫn gọi hỏi, cô ấy nên ngừng viết lại câu chữ.

## Trong kỳ thi

Mỗi thành phần trong ba phần trên đều có thể xuất hiện trong câu hỏi thi. Đề bài thường mô tả thay đổi nhiều thứ cùng lúc như một hành động quyết đoán.

## Nguồn gốc của phương pháp này

Không bài viết nào của Anthropic dạy phương pháp điều chỉnh từng biến một. Lời khuyên trong Help Center chỉ dừng ở việc phản hồi Claude và yêu cầu viết lại. Tạo nhánh cho cuộc trò chuyện chỉ cung cấp các phiên bản để so sánh. Phương pháp trong bài học này dựa trên cách diễn đạt mục tiêu trong đề cương kỳ thi và phương pháp thực hành nghề nghiệp thông thường.

## Bẫy trong kỳ thi

### Bẫy: Sửa hàng loạt nhưng gọi đó là quyết đoán

Thay đổi cách diễn đạt, mô hình và ví dụ trong cùng một vòng tạo ra bản nháp mà bạn không thể rút kinh nghiệm: không thể xác định yếu tố tạo ra sự cải thiện, chủ động lặp lại hay giải thích sự cải thiện đó. Đáp án đúng chỉ thay đổi một biến và giữ nguyên mọi yếu tố khác.

### Bẫy: Tiếp tục thêm vòng viết lại thứ tư sau ba vòng có mục tiêu nhưng không hiệu quả

Việc điều chỉnh liên tục thất bại là bằng chứng về cách tiếp cận, không phải lời mời gọi cố gắng điều chỉnh nhiều hơn. Cách khắc phục không còn nằm ở câu chữ; phản ứng chuyên nghiệp là chẩn đoán lại theo danh sách nguyên nhân: tài liệu khác, tính năng hoặc cài đặt khác, hay nhiệm vụ không nên giao cho AI.

### Bẫy: Thử prompt đã điều chỉnh trên tài liệu khác rồi ghi công cho prompt

Khi đầu vào cũng thay đổi, việc so sánh không có ý nghĩa; kết quả cải thiện có thể chỉ vì tài liệu mới dễ hơn. Muốn học hỏi qua các vòng, phải dùng cùng một đầu vào thử nghiệm mỗi lần.

## Tình huống thực hành

Chủ một xưởng gốm soạn email hướng dẫn người tham dự trước mỗi buổi hội thảo cuối tuần. Người tham dự liên tục nói email quá dài và quá trang trọng. Tuần này cô ấy chỉ có thời gian cho một vòng điều chỉnh. Vòng nào được thiết kế để giúp cô ấy rút ra bài học?

- **Phương án A:** Thêm một dòng nêu rõ đối tượng đọc, chạy lại email của cùng buổi hội thảo và đánh giá theo tiêu chí đặt ra trước: người tham dự có thể tìm thấy giờ bắt đầu trong vòng năm giây.
- **Phương án B:** Yêu cầu Claude làm email thân thiện và ngắn gọn hơn, rồi dùng phiên bản mới nếu đọc thấy hay hơn.
- **Phương án C:** Chạy prompt không đổi trên email của một buổi hội thảo khác để xem vấn đề nằm ở prompt hay ở riêng buổi hội thảo đó.
- **Phương án D:** Viết lại prompt, chuyển sang mô hình khác và đính kèm một email mẫu thân thiện hơn trong cùng vòng, rồi giữ lại tổ hợp hoạt động tốt nhất.

## Bài tập thực hành

### Thực hiện một vòng điều chỉnh trung thực

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 25 phút

**Bạn sẽ học được**

- Cách chọn và giữ cố định một lần thực hiện nhiệm vụ để dùng làm trường hợp thử nghiệm.
- Cách viết tiêu chí đạt/không đạt trước khi điều chỉnh.
- Cách chỉ thay đổi chính xác một biến trong mỗi vòng.
- Cách nhận ra vòng thất bại thứ ba là tín hiệu cần chẩn đoán lại.

1. Chọn một nhiệm vụ thực tế lặp lại mà đầu ra gần nhất khiến bạn thất vọng, rồi chọn một lần thực hiện cụ thể và giữ cố định để dùng làm trường hợp thử nghiệm.
   - **Vì sao:** Đầu vào thử nghiệm cố định giúp việc so sánh giữa các vòng có ý nghĩa; nếu không, kết quả tốt hơn có thể chỉ vì đầu vào dễ hơn.
   - **Bạn cần thấy:** Một trường hợp thử nghiệm cụ thể: cùng tài liệu, yêu cầu và tài liệu đi kèm sẽ được dùng trong mọi vòng.
2. Viết tiêu chí trước khi bắt đầu: một câu mô tả đầu ra được cải thiện cần giúp người đọc thực hiện việc gì.
   - **Vì sao:** Nêu trước tiêu chí giúp bạn không thay đổi cách đánh giá theo những gì bản nháp mới tình cờ làm tốt.
   - **Bạn cần thấy:** Một câu có thể đánh giá đạt/không đạt, chứ không phải mong muốn chung chung rằng kết quả phải tốt hơn.
3. Thay đổi chính xác một yếu tố trong yêu cầu: dòng mô tả đối tượng đọc, tài liệu đính kèm hoặc thứ tự các yêu cầu; ghi lại yếu tố bạn chọn.
   - **Vì sao:** Chỉ thay đổi một biến mới giúp bạn xác định yếu tố tạo ra sự cải thiện, lặp lại và giải thích sự cải thiện đó; thay đổi nhiều thứ cùng lúc không đem lại bài học.
   - **Bạn cần thấy:** Một dòng ghi lại thay đổi duy nhất trong vòng này.
4. Chạy lại yêu cầu trên cùng trường hợp thử nghiệm và chỉ đánh giá kết quả theo tiêu chí đã ghi.
   - **Vì sao:** Tiêu chí là căn cứ đánh giá; ấn tượng chung chung sẽ khiến một vòng không khắc phục được gì vẫn được chấp nhận.
   - **Bạn cần thấy:** Kết luận đạt hoặc không đạt theo tiêu chí, ghi cạnh thay đổi tạo ra kết quả.
5. Nếu vòng này không đạt, thực hiện thêm tối đa hai vòng có mục tiêu. Nếu vòng thứ ba cũng thất bại, dừng điều chỉnh và chẩn đoán lại theo danh sách nguyên nhân ở mục 7.1.
   - **Vì sao:** Việc điều chỉnh liên tục thất bại cho thấy cách tiếp cận sai; kỹ năng chuyên nghiệp là nhận ra tín hiệu thay vì cố đổi câu chữ thêm nữa.
   - **Bạn cần thấy:** Hoặc một vòng đạt, hoặc ghi chú rằng đã dừng điều chỉnh và bắt đầu chẩn đoán lại.

## Nguồn

- [My prompt isn't giving me a helpful answer](https://support.claude.com/en/articles/7996857-my-prompt-isn-t-giving-me-a-helpful-answer) — Anthropic
- [What are artifacts and how do I use them?](https://support.claude.com/en/articles/17153992-what-are-artifacts-and-how-do-i-use-them) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic. Không bài viết nào của Anthropic dạy phương pháp thay đổi từng biến, giữ nguyên đầu vào và nêu tiêu chí trước. Bài học này dựa trên mục tiêu trong đề cương kỳ thi và thực tiễn thông thường; Help Center có tài liệu về cách đưa phản hồi.

[Luyện tập miền này](https://claudecertificationguide.com/ccao-f/drill?domain=7) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/7-troubleshooting-optimisation) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-7) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-7)

**Bài học trước:** [Chẩn đoán và xử lý prompt hoạt động kém hiệu quả, đầu ra không tốt](https://claudecertificationguide.com/ccao-f/learn/7-troubleshooting-optimisation/7-1-diagnosing-poor-outputs)

**Bài học tiếp theo:** [Tối ưu hóa quy trình làm việc để tăng hiệu suất và hiệu quả](https://claudecertificationguide.com/ccao-f/learn/7-troubleshooting-optimisation/7-3-optimising-workflows)
