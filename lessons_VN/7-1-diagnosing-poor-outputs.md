# Chẩn đoán và xử lý prompt hoạt động kém hiệu quả, đầu ra không tốt

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/7-troubleshooting-optimisation/7-1-diagnosing-poor-outputs

**Miền:** 7  
**Nhiệm vụ:** 7.1

## Điều cần biết

Đầu ra không tốt là phản hồi chưa đáp ứng được nhu cầu của yêu cầu. Chẩn đoán nghĩa là xác định lý do một yêu cầu có vẻ hợp lý lại tạo ra kết quả như vậy trước khi thay đổi bất cứ điều gì. Cấu hình của Project là các chỉ dẫn và kiến thức của Project.

Chủ một hiệu sách độc lập duy trì Project cho bản tin sách mới hằng tuần và dùng các cuộc trò chuyện thông thường để yêu cầu tạo thẻ kệ sách riêng lẻ.

## Câu hỏi định hướng

Công cụ chẩn đoán hữu ích nhất chỉ là một câu hỏi: việc này chỉ xảy ra một lần hay lần nào cũng xảy ra? Một bản tóm tắt nhạt nhẽo từ một yêu cầu thiếu thông tin là vấn đề prompt; hãy sửa bằng một bản mô tả yêu cầu tốt hơn. Nếu cùng một giọng điệu, định dạng hoặc giả định sai xuất hiện trong mọi đầu ra từ cùng một Project, thì đó là vấn đề cấu hình. Dấu hiệu nằm ở từ **mọi**. Chỉ dẫn hoặc kiến thức của Project tạo ra khiếm khuyết, vì vậy hãy sửa cấu hình một lần. Tự sửa từng đầu ra sẽ khiến bạn phải trả cùng một chi phí mãi mãi.

Một thẻ kệ sách nhạt nhẽo cần một bản mô tả yêu cầu tốt hơn. Giọng điệu cứng nhắc trong mọi bản tin cần được sửa một lần trong chỉ dẫn của Project.

## Danh sách nguyên nhân có thể rà soát trong một phút

Sáu nguyên nhân giải thích gần như mọi vấn đề:

- Thiếu ngữ cảnh.
- Quá tải chỉ dẫn.
- Lỗi cấu hình.
- Cuộc trò chuyện bị suy giảm.
- Tài liệu đã lỗi thời hoặc bị tài liệu mới thay thế.
- Tính năng hoặc cài đặt không phù hợp.

Thiếu ngữ cảnh là nguyên nhân phổ biến nhất. Một yêu cầu không nêu đối tượng độc giả, mục đích và tài liệu nguồn chỉ có thể tạo ra đầu ra chung chung, vì Claude không thể đoán phần thông tin bị bỏ sót. Help Center khuyên hãy cung cấp ngữ cảnh nhiều nhất có thể, như thể bạn đang hướng dẫn một người không có kiến thức nền về nhiệm vụ. Hãy bổ sung phần còn thiếu. Nhấn mạnh yêu cầu hơn không bổ sung được gì. Thẻ kệ sách cần có đối tượng đọc, mục đích và phần giới thiệu cuốn sách.

Tiếp theo là quá tải. Một yêu cầu có hàng tá tiêu chí có thể khiến một số tiêu chí bị bỏ quên. Biện pháp được tài liệu hóa là tổ chức cấu trúc: chia yêu cầu phức tạp thành các bước nhỏ, nhóm và sắp xếp ưu tiên để các yêu cầu quan trọng không bị chìm mất. Gửi lại cùng danh sách với những mục bị bỏ sót viết hoa không cung cấp gì mới. Nếu bản mô tả bản tin cứ làm mất giờ mở cửa, hãy chia nhỏ và xếp thứ tự ưu tiên.

## Khi chính cuộc trò chuyện là vấn đề

Một cuộc trò chuyện kéo dài tích lũy các bản nháp đã bị thay thế, những chỉnh sửa sau đó lại bị mâu thuẫn và các chủ đề không liên quan. Claude phải xử lý tất cả. Cuối cùng, cuộc trò chuyện sẽ chạm giới hạn độ dài. Các cuộc trò chuyện dài hơn, kích hoạt cơ chế quản lý ngữ cảnh tự động, cũng tiêu tốn nhiều hơn hạn mức sử dụng. Lời khuyên được tài liệu hóa là chia nội dung thành phần nhỏ, tóm tắt các mục quan trọng hoặc bắt đầu cuộc trò chuyện mới. Projects xử lý lượng lớn tài liệu thường dùng thông qua cơ chế truy xuất. Cách khắc phục cuộc trò chuyện bị suy giảm là bắt đầu cuộc trò chuyện mới và mang theo bản tóm tắt đã xác minh về những điều vẫn còn quan trọng. Một cuộc trò chuyện chứa ba bản nháp bản tin nên được bắt đầu lại dựa trên bản tóm tắt.

## Các kiểu lỗi Anthropic nêu

Các bài viết xử lý sự cố của Help Center nêu những triệu chứng thuộc mục tiêu này. Câu trả lời sai hoặc gây hiểu lầm có thể bao gồm trích dẫn bịa đặt nhưng trông có vẻ đúng. Claude không phải nguồn chân lý duy nhất, vì vậy hãy xem xét kỹ các khẳng định có rủi ro cao và kiểm tra nguồn được trích dẫn, chẳng hạn trích dẫn của tác giả trong bản tin.

Ảo giác về khả năng xảy ra khi Claude tạo các liên kết trông như hoạt động nhưng lại hỏng, hoặc tuyên bố đã gửi email. Claude không có quyền truy cập email hay phần mềm nào khác trừ khi được tích hợp rõ ràng. Chẩn đoán đúng là khả năng bị bịa ra, không phải email cần truy tìm.

Nếu phản hồi quá ngắn, đó là vấn đề prompt: hãy điều chỉnh prompt. Cung cấp cho Claude prompt và phản hồi trước đó để Claude tiếp tục từ chỗ đã dừng. Thông báo lỗi không phải lỗi về chất lượng. Thông báo hết dung lượng nghĩa là hãy chờ rồi thử lại. Thông báo giới hạn độ dài nghĩa là chia nhỏ, tóm tắt hoặc bắt đầu cuộc trò chuyện mới. Một nửa việc chẩn đoán là nhận biết triệu chứng thuộc loại nào, vì mỗi loại cần một cách khắc phục khác nhau.

## Phản xạ leo thang

Bẫy quen thuộc nhất của miền này là chọn mô hình mạnh hơn hoặc cài đặt effort cao hơn vì đầu ra gây thất vọng. Một bản mô tả yêu cầu mơ hồ sẽ thất bại ở mọi cấp độ, vì ngữ cảnh còn thiếu vẫn thiếu đối với mọi mô hình. Leo thang sẽ mua về cùng một câu trả lời chung chung, được tạo kỹ hơn nhưng tốn kém hơn, còn thẻ kệ vẫn nhạt nhẽo. Thay đổi tính năng và cài đặt là hợp lý khi nhiệm vụ cần phân tích sâu hơn (cài đặt effort và extended thinking) hoặc thông tin bên ngoài cập nhật (web search hoặc Research). Chỉ cân nhắc các lựa chọn đó sau khi bản mô tả yêu cầu đã đầy đủ.

## Trong kỳ thi

Mọi câu hỏi trong miền này đều bắt đầu sau khi có sự cố. Viết một yêu cầu tốt là nhiệm vụ của Miền 1; chẩn đoán kết quả kém là nhiệm vụ của miền này. Thay đổi cấu hình là công việc của Miền 5; nhận ra cần thay đổi cấu hình là việc của bạn. Thí sinh mất điểm vì tìm cách khắc phục trước khi xác định nguyên nhân.

### Khái niệm then chốt

Phân loại triệu chứng trước khi đọc các phương án: xảy ra một lần hay lần nào cũng xảy ra, và thuộc kiểu lỗi nào đã nêu. Đáp án đúng khắc phục nguyên nhân. Ít nhất một phương án gây nhiễu xử lý triệu chứng, thường là viết lại prompt dù prompt không phải vấn đề.

### Điều nguồn tài liệu không nói

Không có nguồn chính thức nào nói rằng các cuộc trò chuyện dài trở nên chậm hơn hoặc Claude nhầm lẫn giữa các chủ đề. Lý do để bắt đầu lại chỉ dựa trên những gì đã được tài liệu hóa.

## Bẫy trong kỳ thi

### Bẫy: Viết lại prompt hôm nay dù đề bài nói mọi đầu ra đều có cùng khiếm khuyết

Khiếm khuyết xuất hiện trong mọi đầu ra cùng loại là do phần thiết lập; vì vậy, hãy sửa một lần trong chỉ dẫn hoặc kiến thức của Project. Viết lại từng prompt hoặc tự sửa từng đầu ra sẽ khiến bạn phải trả cùng một chi phí mãi mãi, đồng thời để nguyên nguyên nhân.

### Bẫy: Chọn mô hình mạnh hơn hoặc tăng effort ngay khi đầu ra gây thất vọng

Nếu yêu cầu chưa nêu đối tượng đọc hoặc chưa đính kèm tài liệu, leo thang chỉ tạo ra cùng câu trả lời chung chung chậm hơn và tốn kém hơn. Hãy chẩn đoán trước: bản mô tả thiếu ngữ cảnh cần được bổ sung ngữ cảnh; không cấp độ mô hình nào có thể đoán phần đã bị bỏ qua.

### Bẫy: Coi thông báo lỗi là khiếm khuyết chất lượng rồi viết lại prompt

Thông báo dung lượng và giới hạn độ dài có cách xử lý được tài liệu hóa: chờ một lúc rồi thử lại, hoặc chia nhỏ, tóm tắt và bắt đầu cuộc trò chuyện mới. Viết lại yêu cầu là trả lời một câu hỏi mà hệ thống chưa hề đặt ra.

### Bẫy: Truy tìm email mà Claude nói đã gửi

Claude không có quyền truy cập email hoặc phần mềm chưa được tích hợp rõ ràng. Vì vậy, lời tuyên bố đã gửi email là ảo giác về khả năng chứ không phải lỗi gửi thư. Kiểm tra thư mục đã gửi hoặc yêu cầu Claude gửi lại là truy tìm một việc chưa từng xảy ra.

## Tình huống thực hành

Quản trị viên của một phòng trưng bày nghệ thuật nhỏ soạn thư đề nghị cho mượn tác phẩm gửi các bên cho mượn trong một Project trao đổi thư từ. Suốt hai tháng, mọi lá thư đều dùng chính tả kiểu Mỹ; cô ấy đã sửa tay từng lá thư trước khi gửi. Một mô hình mạnh hơn cũng tạo ra cách viết chính tả tương tự. Cô ấy muốn chấm dứt việc sửa tay và tiếp tục soạn thư trong Project. Bước tiếp theo phù hợp nhất là gì?

- **Phương án A:** Tiếp tục sửa tay từng lá thư trước khi gửi, vì mỗi lần chỉ mất vài phút và ngoài ra các lá thư đều đúng như mong muốn.
- **Phương án B:** Kiểm tra chỉ dẫn và kiến thức của Project để tìm nguyên nhân, rồi nêu rõ quy chuẩn chính tả ở đó một lần.
- **Phương án C:** Chuyển Project sang mô hình mạnh hơn để thư dùng đúng chính tả ngay từ đầu, không cần sửa tay.
- **Phương án D:** Soạn các thư sau trong những cuộc trò chuyện mới bên ngoài Project để cài đặt của Project không ảnh hưởng đến văn bản hoàn chỉnh.

## Bài tập thực hành

### Chẩn đoán lần thất vọng gần nhất

**Độ khó:** 25 phút

**Bạn sẽ học được**

- Cách định hướng triệu chứng bằng câu hỏi “một lần hay lần nào cũng vậy”.
- Cách rà soát danh sách nguyên nhân ngắn trước khi động đến prompt.
- Cách nhận biết các kiểu lỗi Anthropic đã tài liệu hóa.
- Cách áp dụng một biện pháp khắc phục và kiểm tra xem triệu chứng có thay đổi không.

1. Tìm lần gần nhất công việc Claude khiến bạn thất vọng và không viết lại bất cứ điều gì cho đến khi đã chẩn đoán.
   - **Vì sao:** Kỷ luật cốt lõi của miền này là xác định nguyên nhân trước khi khắc phục; nhảy ngay vào viết lại là phản xạ bài tập này giúp rèn lại.
   - **Bạn cần có:** Đầu ra gây thất vọng và yêu cầu đã tạo ra nó, đặt cạnh nhau và chưa chỉnh sửa.
2. Trước tiên, hãy hỏi: việc đó chỉ xảy ra một lần hay lần nào làm loại công việc này cũng xảy ra?
   - **Vì sao:** Lỗi đơn lẻ thường liên quan đến yêu cầu hoặc cuộc trò chuyện; lỗi lặp lại thường liên quan đến phần thiết lập. Hai chẩn đoán dẫn đến hai cách xử lý hoàn toàn khác nhau.
   - **Bạn cần có:** Một quyết định bằng một từ: “một lần” hoặc “mọi lần”.
3. Nếu chỉ xảy ra một lần, rà soát danh sách nguyên nhân: thiếu ngữ cảnh, có quá nhiều yêu cầu cùng lúc, cuộc trò chuyện kéo dài quá lâu, tài liệu đã bị thay thế, hoặc nhiệm vụ cần một tính năng/cài đặt mà cách diễn đạt không thể thay thế.
   - **Vì sao:** Một danh sách ngắn có thể thực sự áp dụng hữu ích hơn việc tìm kiếm vô định; phần lớn lỗi đơn lẻ là do thiếu ngữ cảnh, và danh sách giúp bạn không bỏ qua các nguyên nhân ít gặp hơn.
   - **Bạn cần có:** Một nguyên nhân cụ thể kèm câu giải thích bằng chứng khiến bạn chọn nguyên nhân đó.
4. Nếu xảy ra mọi lần, mở chỉ dẫn và kiến thức của Project, tìm dòng gây lỗi hoặc dòng còn thiếu.
   - **Vì sao:** Lỗi lặp lại do cấu hình tạo ra; bằng chứng nằm trong chỉ dẫn và kiến thức, không phải trong một cuộc trò chuyện riêng lẻ.
   - **Bạn cần có:** Dòng gây lỗi được xác định, hoặc ghi chú rằng tiêu chuẩn dẫn đến lỗi chưa từng được nêu.
5. Áp dụng đúng một biện pháp mà chẩn đoán chỉ ra, chạy lại cùng yêu cầu và ghi nhận triệu chứng có thay đổi hay không trước khi sửa bất cứ điều gì khác.
   - **Vì sao:** Chỉ thay đổi một yếu tố rồi kiểm tra lại mới biến phỏng đoán thành chẩn đoán; nếu triệu chứng thay đổi, bạn đã tìm được nguyên nhân; nếu không, danh sách nguyên nhân vẫn cần được xem xét.
   - **Bạn cần có:** Cặp đầu ra trước và sau cùng kết luận một dòng về việc biện pháp có hiệu quả hay không.

## Nguồn

- **My prompt isn't giving me a helpful answer** — Anthropic
- **Claude is providing incorrect or misleading responses. What's going on?** — Anthropic
- **Claude is producing links that don't work and falsely claiming that it has sent emails or produced external documents** — Anthropic
- **Claude's response to my prompt is too brief** — Anthropic
- **Troubleshoot Claude error messages** — Anthropic
- **How do usage and length limits work?** — Anthropic
- **Change the model, effort, and thinking settings** — Anthropic
- **When should I use web search, extended thinking, and research?** — Anthropic

**Luyện tập miền này · Bài tập thực hành · Tham khảo nhanh · Bảng thuật ngữ**  
**Bài học trước:** Tìm hiểu những tác động đạo đức của việc sử dụng AI  
**Bài học tiếp theo:** Điều chỉnh cách tiếp cận dựa trên phản hồi và kết quả
