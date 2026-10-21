# Cân bằng lựa chọn mô hình với chi phí, tốc độ và chất lượng

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-3-cost-speed-quality

**Miền:** 3  
**Nhiệm vụ:** 3.3

**Học bài này theo hình thức tương tác**

## Những điều bạn cần biết

Mục tiêu 3.2 giải thích các cấp độ mô hình. Mỗi lần chọn giữa chúng, bạn đang sử dụng ba loại nguồn lực: chi phí, thời gian và độ sâu. Chi phí là hạn mức sử dụng của gói dịch vụ, không phải hóa đơn tính cho từng lượt dùng. Tốc độ là thời gian chờ mỗi câu trả lời, thể hiện rõ nhất khi phải chạy nhiều lượt. Chất lượng là độ sâu cần thiết cho công việc khó, theo định nghĩa ở mục tiêu 3.2: xử lý sự mơ hồ, dung hòa mâu thuẫn và đưa ra phán đoán an toàn. Kỹ năng ở đây là xác định nhiệm vụ cần loại nguồn lực nào, rồi chỉ chi trả cho đúng thứ đó.

Một chủ tiệm cá và khoai tây chiên dùng Claude cho hai việc. Việc thứ nhất là viết năm trăm phản hồi đánh giá, chỉ khác nhau về tên khách và món ăn. Việc thứ hai là soạn một phản hồi gửi hội đồng địa phương sau đợt kiểm tra vệ sinh.

## Ba câu hỏi giúp xác định nguồn lực

Hãy lần lượt đặt ba câu hỏi:

1. Nếu sai thì hậu quả ở đây là gì?
2. Công việc này sẽ được chạy bao nhiêu lần?
3. Ai đang chờ câu trả lời?

Câu trả lời cho biết cần loại nguồn lực nào. Nếu không đặt các câu hỏi này, lựa chọn chỉ dựa trên cảm tính thay vì yêu cầu được xác định rõ. Với phản hồi đánh giá của tiệm: sai sót có hậu quả nhỏ, có năm trăm lượt chạy, không ai đang chờ. Với phản hồi về vệ sinh: sai sót có hậu quả lớn, chỉ chạy một lần, hội đồng địa phương đang chờ.

## Chi phí là hạn mức sử dụng của bạn

Help Center liệt kê lựa chọn mô hình, mức độ nỗ lực (effort level), độ dài cuộc trò chuyện hiện tại và kích thước tệp đính kèm trong số các yếu tố quyết định hạn mức sử dụng được tiêu thụ nhanh đến đâu. Hạn mức có giới hạn, vì thế nếu bạn chi quá nhiều cho một nhiệm vụ thì các nhiệm vụ sau sẽ còn ít hơn. Dùng mô hình nặng nhất cho các phản hồi đánh giá sẽ tiêu tốn hạn mức mà phản hồi gửi hội đồng cần đến.

## Khối lượng làm tăng tác động đến chi phí và tốc độ

Nếu chỉ chạy một lần, chênh lệch giữa các cấp độ chỉ là vài giây và một phần nhỏ hạn mức. Nếu chạy năm trăm lần, cùng mức chênh lệch đó có thể quyết định công việc hoàn thành trong hôm nay hay không, và hạn mức có đủ cho cả tuần hay không. Công việc thường lệ, khối lượng lớn như trả lời đánh giá nên dùng cấp nhẹ hơn.

Công việc số lượng lớn chạy trên cấp nhanh vẫn cần kiểm tra mẫu ngẫu nhiên, vì nghĩa vụ xác minh của Miền 2 không bao giờ mất đi. Cách này mở rộng hợp lý: chủ tiệm đọc kiểm tra một mẫu phản hồi. Sự kết hợp đó khiến lựa chọn trở nên chuyên nghiệp, chứ không chỉ là chọn phương án rẻ.

## Mức độ rủi ro làm tăng yêu cầu về chất lượng

Công việc có rủi ro cao nằm trên trục còn lại. Một số đầu ra đơn lẻ phục vụ quyết định quan trọng và cần độ sâu: hồ sơ đệ trình quy định, thư có nội dung nhạy cảm về pháp lý, hoặc khuyến nghị mà hội đồng quản trị sẽ hành động theo. Vài giây tiết kiệm được khi dùng cấp nhẹ hơn không đáng gì so với cái giá của một kết luận sai tinh vi. “Chỉ là một lá thư” đúng nhưng không liên quan, vì một lá thư có hậu quả đòi hỏi năng lực cao hơn năm trăm đầu ra thường lệ không có hậu quả lớn. Yêu cầu chất lượng phụ thuộc vào cái giá của việc sai, không phải vào danh tiếng hay mức độ quan trọng của nhiệm vụ. Sau đó, đầu ra có rủi ro cao cần được người có chuyên môn rà soát, bất kể mô hình nào đã soạn thảo. Phản hồi về vệ sinh nên dùng cấp có năng lực cao và có người kiểm tra đủ chuyên môn.

## Chia tách khối lượng công việc hỗn hợp

Khối lượng công việc thực tế thường gồm nhiều dạng. Hãy tách chúng theo yêu cầu thay vì chạy mọi thứ ở cùng một cài đặt. Phần thường lệ số lượng lớn dùng cấp nhanh cùng bước rà soát mẫu. Phần khó nhất dùng cấp có năng lực cao cùng bước rà soát phù hợp. Bộ chọn mô hình giúp việc tách này dễ thực hiện: bạn có thể đổi mô hình bất cứ lúc nào trong cuộc trò chuyện và thay đổi có hiệu lực từ câu trả lời tiếp theo.

Ba đáp án sai thường lặp lại:

- **Tối đa hóa chất lượng cho mọi việc:** phải trả giá cho độ sâu ở những việc không cần đến nó; với khối lượng lớn, sự lãng phí cộng dồn.
- **Tối thiểu hóa chi phí cho mọi việc:** đưa ra đầu ra nông, thiếu chiều sâu cho công việc mà sai sót gây tốn kém.
- **Tăng cấp mô hình liên tục:** chạy lại đầu ra chưa đạt bằng các mô hình ngày càng nặng hơn. Cách này coi bản mô tả mơ hồ là vấn đề của mô hình, nhưng bản mô tả mơ hồ sẽ thất bại ở mọi cấp độ. Sửa bản mô tả là cách làm thuộc Miền 1; nâng cấp mô hình không thể thay thế việc đó. Nếu bản mô tả cho phản hồi về vệ sinh không nêu rõ người đọc là ai, mọi cấp độ đều sẽ bỏ sót.

## Trong kỳ thi

Câu hỏi yêu cầu bạn định giá một nhiệm vụ thực tế theo ba loại nguồn lực. Câu mẫu trong hướng dẫn chọn mô hình nhanh hơn, chi phí thấp hơn cho việc soạn thảo đơn giản, khối lượng lớn. Bẫy thường gặp là dùng dấu hiệu về khối lượng để đưa ra quyết định cho nhiệm vụ có rủi ro cao.

## Khái niệm chính

Khối lượng làm tăng tác động đến chi phí và tốc độ; mức độ rủi ro làm tăng yêu cầu về chất lượng. Khi câu hỏi có cả hai dạng công việc, đáp án đúng hầu như luôn chia tách khối lượng. Phần lớn được chạy trên cấp nhanh, kèm kiểm tra mẫu. Phần có hậu quả quan trọng được chạy trên cấp có năng lực cao, kèm bước rà soát phù hợp.

## Bẫy trong kỳ thi

### Bẫy: Biện minh cho cấp nhanh ở đầu ra rủi ro cao vì “chỉ là một lá thư”

Mức độ rủi ro, không phải khối lượng, quyết định yêu cầu chất lượng. Một đầu ra duy nhất phục vụ quyết định có hậu quả đòi hỏi năng lực cao hơn hàng trăm đầu ra thường lệ; vài giây tiết kiệm được khi dùng cấp nhẹ hơn không đáng gì so với cái giá của một kết luận sai tinh vi.

### Bẫy: Biện minh cho cấp cao nhất khi xử lý công việc thường lệ hàng loạt vì công việc quan trọng

Tầm quan trọng của dự án không chuyển sang mọi nhiệm vụ bên trong nó. Chuyển đổi thường lệ với khối lượng lớn cần tốc độ cao và chi phí thấp, kèm kiểm tra mẫu; trả giá cho độ sâu hàng trăm lần không đem lại điều gì mà nhiệm vụ cần.

### Bẫy: Tăng cấp mô hình khi vấn đề thực sự là bản mô tả mơ hồ

Bản mô tả mơ hồ sẽ thất bại ở mọi cấp độ, nên việc liên tục tăng cấp chỉ tốn thời gian và hạn mức để rồi nhận ra điều đó. Nếu câu hỏi cho thấy prompt thiếu đối tượng đọc, ràng buộc hoặc tài liệu nguồn, hành động đúng là sửa bản mô tả—việc thuộc Miền 1—chứ không phải nâng cấp mô hình.

## Tình huống thực hành

Một hiệp hội điền kinh cấp vùng đang chuẩn bị đêm trao giải hằng năm: năm trăm thư mời cá nhân hóa chỉ khác nhau về tên, câu lạc bộ và sự kiện, cùng một lá thư khó gửi đến một câu lạc bộ bị đình chỉ vì vi phạm quy định bảo vệ an toàn. Lá thư này cần chú ý đến giọng điệu, độ chính xác và sự thận trọng gần với vấn đề pháp lý. Chi phí cho thư mời phải thấp nhất có thể, và không được cắt giảm bất cứ điều gì giúp lá thư đình chỉ an toàn hơn. Người quản lý nên xử lý hai việc như thế nào?

### Lựa chọn

- **A.** Dùng mô hình có năng lực cao nhất cho cả hai việc, vì đêm trao giải là sự kiện trọng điểm của hiệp hội và không nội dung nào được phép trông kém chất lượng.
- **B.** Dùng mô hình nhanh hơn cho cả hai việc, vì thư mời rõ ràng là công việc số lượng lớn còn thư đình chỉ chỉ là một lá thư, mô hình nào cũng xử lý được.
- **C.** Soạn thư đình chỉ bằng mô hình nhanh hơn để tiết kiệm hạn mức; nếu giọng điệu chưa phù hợp thì chạy lại cùng prompt bằng mô hình có năng lực cao nhất, lặp lại cho đến khi có bản chấp nhận được.
- **D.** Chạy năm trăm thư mời bằng mô hình nhanh, chi phí thấp hơn và kiểm tra mẫu; sau đó soạn thư đình chỉ bằng mô hình có năng lực cao nhất và yêu cầu người có chuyên môn rà soát trước khi gửi.

## Bài tập thực hành

### Định giá khối lượng công việc hỗn hợp theo ba nguồn lực

**Độ khó:** 25 phút

**Bạn sẽ học được**

- Cách xác định một nhiệm vụ cần nhiều nhất loại nguồn lực nào: chi phí, thời gian hay độ sâu.
- Cách chạy công việc hàng loạt trên cấp nhẹ hơn và rà soát theo mẫu.
- Cách chuyển đầu ra có rủi ro cao sang cấp độ sâu hơn, kèm người có chuyên môn rà soát.
- Cách phát hiện những quyết định dựa trên danh tiếng hoặc thói quen đồng loạt trong tuần làm việc của bạn.

**Chọn một tuần làm việc thực tế có cả nhiệm vụ hàng loạt với nhiều đầu ra tương tự và một nhiệm vụ đơn lẻ có rủi ro cao.**

- **Tại sao:** Khối lượng công việc hỗn hợp là dạng mà mục tiêu này kiểm tra; một tuần chỉ có một dạng sẽ che khuất quyết định cần tách việc.
- **Bạn cần thấy:** Hai nhiệm vụ được nêu rõ: một việc hàng loạt và một việc có hệ quả quan trọng.

**Với mỗi nhiệm vụ, viết một dòng nêu loại nguồn lực cần nhất—chi phí, thời gian hay độ sâu—và lý do.**

- **Tại sao:** Xác định loại nguồn lực cần thiết là toàn bộ nguyên tắc; mọi đáp án sai trong mục tiêu này đều bỏ qua bước đó.
- **Bạn cần thấy:** Hai lời giải thích một dòng, mỗi dòng nêu một loại nguồn lực chủ đạo.

**Gán cấp độ cho từng nhiệm vụ và chạy công việc hàng loạt trên cấp nhẹ hơn, kiểm tra một mẫu theo tiêu chuẩn chất lượng của bạn.**

- **Tại sao:** Kiểm tra mẫu giúp phân biệt kiểm soát chi phí chuyên nghiệp với việc đưa ra kết quả chưa được rà soát.
- **Bạn cần thấy:** Đầu ra hàng loạt vượt qua kiểm tra mẫu và được tạo nhanh hơn rõ rệt.

**Với nhiệm vụ có rủi ro cao, ghi rõ ai sẽ rà soát đủ chuyên môn sau khi cấp có năng lực cao soạn thảo.**

- **Tại sao:** Bản nháp có độ sâu không thay thế nghĩa vụ rà soát; đầu ra có hậu quả quan trọng cần người có chuyên môn kiểm tra, bất kể mô hình nào tạo ra nó.
- **Bạn cần thấy:** Tên người rà soát có đủ năng lực và thẩm quyền để phát hiện kết luận sai tinh vi.

**Xem lại tuần làm việc: đánh dấu quyết định nào dựa trên danh tiếng hoặc thói quen dùng một cài đặt cho mọi việc thay vì yêu cầu thực tế, rồi ghi lại cách phân công đã sửa.**

- **Tại sao:** Hai cài đặt đồng loạt—tối đa hóa chất lượng cho mọi việc và tối thiểu hóa chi phí cho mọi việc—là các đáp án đánh lạc hướng thường gặp; rà soát tuần của chính bạn giúp nhận ra chúng trong câu hỏi thi.
- **Bạn cần thấy:** Mỗi nhiệm vụ được đánh dấu là dựa trên yêu cầu, danh tiếng hay thói quen; các trường hợp dựa trên hai yếu tố sau có cách phân công đã chỉnh sửa.

## Nguồn

- Models overview — Anthropic
- Usage limit best practices — Anthropic
- Change the model, effort, and thinking settings — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic

**Luyện tập Miền này · Bài tập thực hành · Tham khảo nhanh · Bảng thuật ngữ**  
**Bài trước:** Phân biệt các loại mô hình Claude  
**Bài tiếp theo:** Quản lý giới hạn ngữ cảnh và bộ nhớ: bắt đầu lại, tóm tắt, lưu giữ
