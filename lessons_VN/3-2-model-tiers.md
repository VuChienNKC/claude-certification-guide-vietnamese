# Phân biệt các loại mô hình Claude

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-2-model-tiers

**Miền:** 3  
**Nhiệm vụ:** 3.2

**Học bài này theo hình thức tương tác**

## Những điều bạn cần biết

Mục tiêu này nêu ba dòng mô hình: Haiku, Sonnet và Opus. Mỗi dòng là một cấp độ, và các cấp độ đánh đổi tốc độ, chi phí với độ sâu. Dòng Haiku có chi phí thấp nhất. Anthropic cho biết đây là dòng nhanh nhất, được xây dựng cho các tác vụ khối lượng lớn và nhạy cảm với độ trễ. Dòng Opus là cấp độ suy luận mạnh nhất, dành cho công việc phức tạp, có mức độ rủi ro cao. Dòng Sonnet đem lại sự kết hợp tốt nhất giữa tốc độ và trí tuệ: cấp độ cân bằng ở giữa và là lựa chọn mặc định hợp lý hằng ngày. Không có cấp độ nào là “loại tốt”. Mỗi cấp độ phù hợp với công việc phát huy được điểm mạnh của nó.

Một người bán hoa có hai việc: chuẩn hóa ba trăm danh mục sản phẩm theo cùng một mẫu trang web; và đối chiếu báo cáo của hai nhà bán sỉ có một phần thông tin mâu thuẫn để đưa ra một đề xuất đặt hàng.

## Sự đánh đổi

Ở cấp độ có năng lực cao, mỗi câu trả lời mất nhiều thời gian hơn; lựa chọn mô hình cũng là một trong những yếu tố quyết định mức sử dụng giới hạn sử dụng nhanh đến đâu. Cấp độ nhanh hơn đạt tốc độ bằng cách không nhắm đến những công việc đòi hỏi cao nhất. Nếu dùng Opus cho từng danh mục sản phẩm của người bán hoa, mỗi mục sẽ mất lâu hơn mà không đem lại lợi ích.

## Năng lực nghĩa là gì?

Năng lực ở đây là độ sâu khi xử lý công việc khó: tháo gỡ sự mơ hồ và mâu thuẫn, suy luận nhiều bước, tổng hợp các nguồn có điểm bất đồng, và soạn nội dung mà một sắc thái sai lệch có thể gây hậu quả thực sự. Điều đó không có nghĩa là mô hình làm mọi việc đều tốt hơn, vì vậy cấp cao nhất không phải lựa chọn áp dụng cho tất cả. Với công việc thường lệ, được mô tả rõ, các cấp nhẹ hơn tạo ra kết quả cần thiết nhanh hơn. Danh mục sản phẩm của người bán hoa là việc thường lệ; đề xuất đặt hàng từ báo cáo của hai nhà bán sỉ thì không.

Đừng bao giờ khẳng định cấp nhẹ hơn có chất lượng ngang cấp nặng hơn trong công việc đòi hỏi cao; tài liệu không nói vậy. Cấp nhẹ hơn phù hợp nhờ tương xứng với nhiệm vụ và có bước rà soát, chứ không phải vì nó tương đương về chất lượng.

## Nhận diện dấu hiệu trong nhiệm vụ

**Dấu hiệu phù hợp với cấp nhẹ hơn:** khối lượng lớn, dạng việc thường lệ và lặp đi lặp lại, chuyển đổi đơn giản như định dạng lại, trích xuất hoặc chuẩn hóa, cần tốc độ, và mỗi đầu ra có mức độ rủi ro thấp. Dù vậy, vẫn cần kiểm tra ngẫu nhiên vì nguyên tắc rà soát của Miền 2 không bao giờ ngừng áp dụng.

**Dấu hiệu phù hợp với cấp mạnh nhất:** sự mơ hồ, mâu thuẫn cần tháo gỡ, phán đoán kéo theo hậu quả, tổng hợp phức tạp, và công việc mà kết luận sai tinh vi gây tốn kém hơn thời gian chờ thêm. Khi không nhóm dấu hiệu nào chiếm ưu thế, cấp cân bằng ở giữa là lựa chọn hằng ngày.

Quy mô không quyết định; bản chất công việc mới quyết định. Chuẩn hóa một danh sách dài thành một mẫu duy nhất vẫn là việc phù hợp với cấp nhẹ hơn, bất kể có bao nhiêu dòng. Đối chiếu hai báo cáo có một phần mâu thuẫn để đưa ra một đề xuất duy nhất là việc phù hợp với cấp có năng lực cao, dù trang cuối cùng ngắn đến đâu. Các danh mục sản phẩm của người bán hoa nên chạy trên cấp nhẹ hơn và được kiểm tra mẫu; bản đề xuất một trang nên dùng Opus.

## Bộ chọn mô hình

Bạn chọn mô hình trong giao diện chat, không phải trong phần cấu hình kỹ thuật. Nhấp vào tên mô hình rồi chọn một mô hình khác đang có. Bạn có thể đổi mô hình bất cứ lúc nào trong cuộc trò chuyện; thay đổi có hiệu lực từ câu trả lời tiếp theo của Claude. Bộ chọn hiển thị các mô hình mà tài khoản của bạn được phép dùng. Danh sách này tùy theo gói dịch vụ và, trong môi trường làm việc, tùy vào những gì tổ chức bật.

Vì vậy, quyết định cấp độ không phải cam kết chỉ chọn một lần. Công việc thường lệ để chuẩn bị nền có thể dùng cấp nhẹ hơn, còn phần tổng hợp khó có thể dùng cấp mạnh nhất, ngay trong cùng một quy trình. Người bán hoa có thể trích xuất điều khoản của từng nhà bán sỉ bằng Haiku, rồi chuyển sang Opus để đưa ra đề xuất. Không bao giờ mở bộ chọn mô hình là phục vụ công việc trung bình nhưng lại không đáp ứng tốt cho cả hai đầu. Cài đặt mặc định cố định phản ánh tài khoản của bạn, không phải quyết định dựa trên công việc.

## Trong kỳ thi

Hướng dẫn nêu tên ba dòng mô hình. Mục tiêu này tồn tại vì không có cấp nào phù hợp với mọi nhiệm vụ. Kỳ thi kiểm tra việc đọc đúng yêu cầu thực tế của nhiệm vụ, không phải chọn theo danh tiếng; kỹ năng này vẫn hữu ích dù danh sách mô hình thay đổi. Trong câu mẫu của hướng dẫn, khối lượng lớn các bản nháp ngắn, thường lệ, trong đó tốc độ và chi phí quan trọng hơn suy luận sâu, được ghép với mô hình nhanh hơn, chi phí thấp hơn. “Luôn dùng mô hình hàng đầu” là một đáp án sai được nêu rõ.

### Bẫy danh tiếng

“Dự án này quan trọng” không khiến một nhiệm vụ thường lệ phải chuyển lên cấp cao nhất. Tầm quan trọng thuộc về dự án; yêu cầu về năng lực thuộc về từng nhiệm vụ. Kỳ thi chọn cấp độ phù hợp với nhiệm vụ trước mắt. Một thao tác định dạng thường lệ trong dự án trọng điểm vẫn chỉ là thao tác định dạng thường lệ.

Tên mô hình cụ thể và danh sách hiện tại thay đổi theo thời gian; những thông tin đó nằm trong phần tham khảo nhanh.

## Bẫy trong kỳ thi

### Bẫy: Chọn mô hình có năng lực cao nhất cho mọi việc chỉ vì công việc quan trọng

Đây là lựa chọn theo danh tiếng. Lý do trong câu mẫu của hướng dẫn gọi việc luôn dùng mô hình hàng đầu là lãng phí ngân sách chi phí và độ trễ; công việc thường lệ, khối lượng lớn không cần độ sâu, và tầm quan trọng của dự án không khiến mọi nhiệm vụ bên trong đều trở nên đòi hỏi cao.

### Bẫy: Giao công việc rõ ràng cần độ sâu cho cấp nhanh nhất vì “chỉ là viết”

Đây là tiết kiệm sai chỗ. Yêu cầu chất lượng phụ thuộc vào cái giá của việc sai: một đầu ra ngắn nhưng chứa phán đoán, mâu thuẫn hoặc hệ quả chính là nơi cấp có năng lực cao xứng đáng với thời gian bỏ ra, dù việc gõ nội dung có thể nhanh đến đâu.

### Bẫy: Chấp nhận đáp án đánh lạc hướng rằng cấp nhẹ hơn cho chất lượng ngang bằng trong công việc khó

Tài liệu không bao giờ khẳng định các cấp có chất lượng tương đương và không có đáp án đúng nào dựa vào điều đó. Cấp nhẹ hơn phù hợp khi đúng với nhiệm vụ và có bước rà soát; nếu câu hỏi đòi hỏi độ sâu thì lựa chọn cấp nhẹ hơn là sai, dù được diễn đạt tự tin đến đâu.

## Tình huống thực hành

Một hợp tác xã năng lượng cộng đồng có một nhân viên hành chính với hai việc song song: chuẩn hóa sáu trăm hồ sơ thành viên theo một định dạng địa chỉ; và soạn phản hồi của hợp tác xã cho một cuộc tham vấn quy định phức tạp, trong đó ba thành viên hội đồng quản trị đưa ra chỉ đạo có một phần mâu thuẫn. Nhân viên cần giữ chi phí cho việc thường lệ ở mức thấp nhất có thể, nhưng không được làm giảm chất lượng lập trường của hợp tác xã. Nên phân công mô hình như thế nào?

### Lựa chọn

- **A.** Dùng mô hình có năng lực cao nhất cho hồ sơ thành viên vì độ chính xác dữ liệu quan trọng ở quy mô đó, và dùng mô hình nhanh nhất cho phản hồi tham vấn vì một lá thư có thể viết nhanh.
- **B.** Xử lý sáu trăm hồ sơ bằng mô hình nhanh, chi phí thấp hơn và kiểm tra ngẫu nhiên một mẫu; soạn phản hồi tham vấn quy định bằng mô hình có năng lực cao nhất.
- **C.** Dùng mô hình nhanh nhất cho cả hai việc vì hồ sơ là công việc thường lệ, còn phản hồi tham vấn chỉ là soạn thảo thông thường sau khi đã dán quan điểm của cả ba thành viên hội đồng.
- **D.** Dùng mô hình có năng lực cao nhất cho cả hai việc vì uy tín của hợp tác xã với tất cả thành viên phụ thuộc vào công việc này, và mô hình tốt nhất sẽ tối đa hóa chất lượng ở mọi nơi.

## Bài tập thực hành

### Ghép nhiệm vụ trong một tuần với cấp độ mô hình

**Độ khó:** 25 phút

**Bạn sẽ học được**

- Cách phân loại nhiệm vụ thành: thường lệ, khối lượng lớn; cấp trung bình dùng hằng ngày; hoặc tổng hợp có rủi ro cao.
- Cách kiểm tra các mô hình tài khoản của bạn cung cấp trong bộ chọn.
- Cách chạy một nhiệm vụ thường lệ trên cấp nhẹ hơn và kiểm tra mẫu chất lượng.
- Cách nêu điều mà độ sâu đem lại cho một nhiệm vụ thực sự đòi hỏi cao.

**Liệt kê các nhiệm vụ Claude trong tuần làm việc gần nhất và gắn nhãn từng việc: thường lệ-khối lượng lớn, cấp trung bình hằng ngày, hoặc tổng hợp-rủi ro cao.**

- **Tại sao:** Ba nhãn này là các nhóm dấu hiệu dùng trong câu hỏi thi; luyện trên công việc của chính bạn giúp nhận ra chúng nhanh hơn.
- **Bạn cần thấy:** Danh sách ngắn các nhiệm vụ thật, mỗi nhiệm vụ có một trong ba nhãn.

**Với từng nhiệm vụ, ghi lại cấp độ mà yêu cầu công việc đòi hỏi và cấp độ bạn thực tế đã dùng; sau đó mở bộ chọn mô hình để xác nhận tài khoản đang có những mô hình nào.**

- **Tại sao:** Khoảng cách giữa cấp độ cần dùng và cấp độ thực tế là nơi thói quen chỉ dùng một cài đặt cố định lộ ra.
- **Bạn cần thấy:** Hai cột cấp độ cho mỗi nhiệm vụ, cùng danh sách mô hình hiện hiển thị trong bộ chọn của bạn.

**Chọn một nhiệm vụ thường lệ, chạy lại bằng cấp nhẹ hơn và kiểm tra ngẫu nhiên một mẫu đầu ra theo tiêu chuẩn chất lượng của bạn.**

- **Tại sao:** Tương xứng với nhiệm vụ cộng với rà soát là lý do để dùng cấp nhẹ hơn; kiểm tra mẫu giúp lựa chọn trở nên chuyên nghiệp thay vì chỉ đơn thuần rẻ hơn.
- **Bạn cần thấy:** Đầu ra vượt qua kiểm tra mẫu và được tạo nhanh hơn cài đặt bạn thường dùng.

**Chọn nhiệm vụ khó nhất gần đây của bạn và viết một câu về điều mà cấp có năng lực cao đã đem lại, hoặc lẽ ra có thể đem lại, mà tốc độ không thể thay thế.**

- **Tại sao:** Việc nêu lợi ích bằng một câu giúp xác định nhiệm vụ thực sự cần độ sâu hay chỉ có vẻ quan trọng.
- **Bạn cần thấy:** Một câu nêu lợi ích cụ thể: tháo gỡ mâu thuẫn, giữ được sắc thái hoặc tránh được hệ quả.

**Đánh dấu nhiệm vụ nào bạn chọn theo danh tiếng thay vì yêu cầu thực tế, rồi phân loại lại theo cấp độ mà nhiệm vụ thật sự cần.**

- **Tại sao:** Chọn theo danh tiếng là đáp án sai thường gặp trong mục tiêu này; tự phát hiện trong tuần làm việc giúp bạn tránh mắc bẫy trong đề thi.
- **Bạn cần thấy:** Ít nhất một lần phân loại lại thành thật, hoặc một tuần thực sự không có trường hợp nào.

## Nguồn

- Models overview — Anthropic
- Change the model, effort, and thinking settings — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic

**Luyện tập Miền này · Bài tập thực hành · Tham khảo nhanh · Bảng thuật ngữ**  
**Bài trước:** Chọn đúng tính năng sản phẩm Claude  
**Bài tiếp theo:** Cân bằng lựa chọn mô hình với chi phí, tốc độ và chất lượng
