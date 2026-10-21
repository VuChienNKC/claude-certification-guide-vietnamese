# Khi nào cần người đánh giá hoặc xác minh bổ sung

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/2-output-evaluation/2-4-human-review-escalation

**Miền:** 2  
**Nhiệm vụ:** 2.4  
**Tên bài:** Khi nào cần người đánh giá hoặc xác minh bổ sung

*Học bài này theo hình thức tương tác |*

## Những điều bạn cần biết

Chuyển cấp để đánh giá (escalation) là chuyển câu trả lời của Claude cho một người có chuyên môn phù hợp xem xét trước khi sử dụng. Phân loại (triage) là quyết định ai sẽ đánh giá từng câu trả lời. Dấu hiệu kích hoạt (trigger) là đặc điểm của tình huống làm tăng cái giá phải trả nếu có sai sót. Mục tiêu này trình bày khi nào việc tự đánh giá của bạn là chưa đủ và ai cần xem xét câu trả lời.

Chủ một trường dạy lái xe có bốn bản nháp do Claude tạo: quảng cáo trang web, thư trả lời yêu cầu hoàn tiền theo điều khoản đặt chỗ, ghi chú đánh giá một giáo viên hướng dẫn, và lời nhắc vệ sinh xe. Cả bốn bản đều đọc trôi chảy.

## Các dấu hiệu kích hoạt

Mỗi dấu hiệu sau đây đều cần người có chuyên môn phù hợp đánh giá:

- Có đối tượng bên ngoài: khách hàng, công chúng, báo chí hoặc bên cấp tài trợ.
- Có hệ quả pháp lý, tài chính hoặc theo hợp đồng.
- Có quyết định liên quan đến con người: tuyển dụng, đánh giá hoặc phân công.
- Có ảnh hưởng đến an toàn hoặc sức khỏe.
- Không thể đảo ngược sau khi gửi đi.

Chỉ cần một dấu hiệu là đã đủ để cần thêm một người có chuyên môn xem xét. Có nhiều dấu hiệu cùng lúc thì việc chuyển cấp là không thể bỏ qua. Độ tự tin và sự trau chuốt không nằm trong danh sách, vì mọi bản nháp của Claude vốn đã có những đặc điểm đó. Không nên xem Claude là nguồn chân lý duy nhất, và câu trả lời có hệ quả quan trọng cần được xem xét cẩn thận.

Ở trường dạy lái xe, quảng cáo hướng đến đối tượng bên ngoài. Thư trả lời yêu cầu hoàn tiền có hệ quả theo hợp đồng. Ghi chú đánh giá góp phần đưa ra quyết định về một người. Lời nhắc vệ sinh xe không có dấu hiệu nào trong số đó, nên chủ trường tự xem xét. Các câu trả lời không có dấu hiệu kích hoạt vẫn cần bạn cẩn thận đánh giá bằng những thói quen trong mục tiêu 2.1 đến 2.3. Đó là tài liệu làm việc nội bộ, bản nháp đầu tiên sẽ còn được chỉnh sửa và thông điệp thường ngày ít hệ quả. Việc tự đánh giá vẫn là đánh giá thực sự, không phải miễn kiểm tra: phân loại quyết định ai sẽ xem xét, chứ không quyết định liệu có ai xem xét hay không.

## Có chuyên môn phù hợp, không nhất thiết là cấp cao

Chính sách sử dụng của Anthropic đặt ra tiêu chuẩn này. Chính sách nêu các lĩnh vực rủi ro cao (High-risk Areas), chẳng hạn pháp lý, y tế, tài chính và việc làm, nơi câu trả lời của Claude có thể trở thành lời khuyên dành cho một người hoặc quyết định về người đó. Chính sách gọi dạng nội dung này là Khuyến nghị AI rủi ro cao (High-risk AI Recommendation) và yêu cầu hai điều: phải thông báo cho người đó rằng đã sử dụng AI, và một người có chuyên môn phù hợp phải xem xét. Quy định đánh giá viết rằng: “Một người có chuyên môn phù hợp phải xem xét có ý nghĩa một Khuyến nghị AI rủi ro cao, và có quyền thay đổi hoặc sửa đổi nó, trước khi nội dung được đưa ra dưới dạng lời khuyên”. Quy định tương tự áp dụng trước khi nội dung được dùng để đưa ra quyết định. Tư vấn cho ai đó về quyền pháp lý của họ hoặc về việc cần làm trong một vấn đề pháp lý cụ thể là một trong những lĩnh vực này.

Người có chuyên môn phù hợp là “người có đào tạo hoặc kinh nghiệm để đánh giá câu trả lời trong lĩnh vực đó”. Cụm từ xác định người đánh giá là “trong lĩnh vực đó”. Nội dung hợp đồng cần người có năng lực pháp lý xem xét; số liệu thuế cần kế toán; tuyên bố lâm sàng cần nhân viên y tế; tiêu chí tuyển dụng cần góc nhìn chuyên môn của bộ phận nhân sự. Ngoài các lĩnh vực rủi ro cao, chính sách không quy định yêu cầu đánh giá, nhưng năng lực chuyên môn vẫn là tiêu chuẩn để chọn người đánh giá.

Thâm niên và mức độ sẵn sàng không phải điều kiện cần, cũng không đủ. Người đọc không đủ chuyên môn—dù giữ chức vụ cao đến đâu—cũng không thể phát hiện các lỗi khiến nội dung trở nên nguy hiểm. Một giám đốc bận rộn đọc lướt điều khoản hợp đồng thuê nhà chỉ tạo cảm giác yên tâm, chứ không phải đánh giá thực sự. Thư trả lời yêu cầu hoàn tiền cần được chuyển cho luật sư, không phải chủ trường.

## Cả hai hướng sai lầm

Chuyển cấp chưa đủ là lỗi dễ hình dung. Đó là khi gửi nội dung hướng đến bên ngoài có tuyên bố mang hệ quả chuyên môn chỉ vì bản nháp đọc có vẻ đáng tin. Hoặc bỏ qua việc đánh giá vì cho rằng nội dung “chỉ dùng nội bộ”, trong khi nó lại được dùng cho quyết định có hệ quả hoặc được gửi ra bên ngoài. Câu trả lời của Claude mặc định đọc có vẻ đáng tin, nhưng các dấu hiệu kích hoạt phụ thuộc vào tình huống và không biến mất chỉ vì câu chữ trau chuốt. Nơi nội dung được sử dụng tiếp theo có ý nghĩa hơn nơi nó được soạn ra. Ghi chú đánh giá được giữ trong văn phòng nhưng lại góp phần đưa ra quyết định về một giáo viên hướng dẫn.

Chuyển cấp quá mức có vẻ an toàn vì thận trọng thường tạo cảm giác an toàn. Nhưng không phải vậy. Lập hội đồng để xem xét ghi chú phân ca, hoặc chuyển mọi bản nháp thường ngày cho người đánh giá chuyên môn, là cách làm rườm rà không cần thiết. Việc này khiến người đánh giá bị quá tải, làm chậm công việc thường lệ và khiến tổ chức dần bỏ qua kênh chuyển cấp vốn cần dành cho nội dung rủi ro cao. Nếu luật sư đọc lời nhắc vệ sinh xe thì sẽ đến với thư hoàn tiền muộn hơn. Kỹ năng cần có là phân loại, không phải thận trọng tối đa.

## Hai lý do khác nhau để tạm dừng

Mục tiêu này yêu cầu chuyển cấp vì chất lượng và mức độ rủi ro: điều gì sẽ xảy ra nếu câu trả lời sai, và ai có đủ chuyên môn để phát hiện lỗi. Miền 6 đề cập những lý do khác để tạm dừng: dữ liệu mang tính cá nhân hoặc được quản lý theo quy định, hoặc mục đích sử dụng nằm ngoài chính sách AI của tổ chức. Cả hai có thể cùng xuất hiện trong một tình huống, chẳng hạn thư trả lời yêu cầu hoàn tiền có trích dẫn dữ liệu cá nhân của học viên, nhưng dấu hiệu kích hoạt là khác nhau. Chuyển cấp về kỹ thuật là dạng thứ ba trong chương trình. Dạng này giao nhiệm vụ cho Claude Developer hoặc Architect vì cần tự động hóa hoặc tích hợp. Đó là nhiệm vụ vượt quá khả năng của cuộc trò chuyện, chứ không phải câu trả lời cần một người có chuyên môn đánh giá.

## Trong kỳ thi

Kỳ thi kiểm tra kỹ năng này dưới dạng phân loại: quyết định dựa trên điều mà câu trả lời liên quan đến, chứ không phải vẻ trau chuốt của nó. Kỳ thi đánh giá sai lầm theo cả hai hướng. Trong đề bài, hãy tìm đối tượng nhận nội dung và tiêu chuẩn cần có của người đánh giá được nêu tên. Thí sinh thường không ngờ việc chuyển cấp quá mức cũng được kiểm tra, nhưng “chuyển cấp mọi thứ” thực sự là một đáp án sai. Kỳ thi phân biệt rõ các dấu hiệu kích hoạt của Miền 6.

### Khái niệm then chốt

Phân loại đặt ra hai câu hỏi theo thứ tự:

1. Câu trả lời này có thể mang theo hệ quả gì?
2. Nếu có hệ quả, ai có chuyên môn trong chủ đề đó để phát hiện những lỗi quan trọng?

Các phương án trả lời bằng cấp bậc, mức độ sẵn sàng hoặc quy trình áp dụng tràn lan là phương án nhiễu.

## Những bẫy trong kỳ thi

### Bẫy trong kỳ thi

Chọn người đánh giá dựa trên thâm niên hoặc mức độ sẵn sàng thay vì chuyên môn  
Khi Chính sách sử dụng yêu cầu đánh giá lời khuyên hoặc quyết định trong một lĩnh vực rủi ro cao, người đánh giá phải có chuyên môn phù hợp: người có đào tạo hoặc kinh nghiệm để đánh giá câu trả lời trong lĩnh vực đó. Tiêu chuẩn chuyên môn cũng đúng ở ngoài các lĩnh vực ấy. Người quản lý cấp cao phê duyệt câu chữ pháp lý hoặc tuyên bố lâm sàng chỉ tạo cảm giác yên tâm, chứ không phải đánh giá thực sự. Vì vậy, đáp án đúng chọn người có chuyên môn thực sự phát hiện được lỗi nguy hiểm.

### Bẫy trong kỳ thi

Bỏ qua nội dung vì cho rằng nó chỉ dùng nội bộ  
Dấu hiệu kích hoạt phụ thuộc vào những gì câu trả lời đề cập, không phải nơi nó xuất hiện đầu tiên. Một phân tích nội bộ được dùng cho hồ sơ dự thầu bên ngoài hoặc quyết định về con người vẫn mang theo hệ quả đó. Vì vậy, đáp án đúng chuyển cấp dựa trên đích đến và mức độ rủi ro, chứ không phải nhãn “nội bộ”.

### Bẫy trong kỳ thi

Chuyển cấp mọi thứ để cho an toàn  
Chuyển cấp quá mức là đáp án sai được kiểm tra, không phải lựa chọn đúng vì thận trọng. Chuyển bản nháp nội bộ thường lệ qua các hội đồng hoặc chuyên gia sẽ khiến người đánh giá bị quá tải và làm suy yếu kênh dành cho nội dung rủi ro cao. Với tài liệu thực sự ít rủi ro, đáp án đúng cho phép tự đánh giá cẩn thận là đủ.

## Tình huống thực hành

Người quản lý một phòng khám mắt có ba bản nháp Claude: nội dung quảng cáo cho một dòng tròng kính mới, trong đó nêu các kết quả thị giác cụ thể; chính sách nội bộ được viết lại về đổi ca; và thư trả lời khiếu nại của bệnh nhân, có đề cập đến điều có thể đã xảy ra về mặt lâm sàng. Người quản lý không được đào tạo lâm sàng và không biết quảng cáo về chăm sóc mắt được phép hứa hẹn những gì theo pháp luật. Mỗi bản nháp phải được một người hiểu chuyên môn xem xét, nhưng không được gây chậm trễ không cần thiết. Cách phân loại nào phù hợp?

### Phương án

- **A.** Đăng quảng cáo vì nội dung đọc có vẻ chuyên nghiệp và được soạn từ tài liệu sản phẩm; yêu cầu bác sĩ đo mắt xem chính sách đổi ca và thư trả lời khiếu nại.
- **B.** Đưa cả ba bản nháp ra cuộc họp quản lý hằng tuần để tập thể phê duyệt trước khi sử dụng, nhằm chia sẻ trách nhiệm với cả nhóm.
- **C.** Yêu cầu người có chuyên môn phù hợp xem xét các tuyên bố quảng cáo và thư trả lời khiếu nại—người có chuyên môn về tuyên bố sức khỏe và bác sĩ đo mắt tương ứng—trước khi gửi; người quản lý tự đọc cẩn thận chính sách đổi ca.
- **D.** Với tư cách người quản lý chịu trách nhiệm, tự xem xét cẩn thận cả ba bản rồi gửi đi, để xử lý nhanh và giữ trách nhiệm ở một nơi.

## Bài tập thực hành

### Phân loại năm câu trả lời gần đây nhất của bạn

**Độ khó:** 25 phút

**Bạn sẽ học được**

- Cách phát hiện dấu hiệu cần người có chuyên môn đánh giá.
- Cách chọn người đánh giá dựa trên chuyên môn chủ đề thay vì chức vụ.
- Cách kiểm tra quyết định phân loại để tránh sai lầm theo cả hai hướng.
- Cách biến một lượt phân loại thành danh sách chuyển cấp dùng lâu dài.

1. Liệt kê năm nội dung gần đây nhất Claude đã soạn cho bạn, hoặc tạo năm nội dung điển hình trong vai trò của bạn.  
   **Vì sao:** Chỉ khi thực hành với nhiều mức độ rủi ro thực tế trong công việc thì việc phân loại mới trở thành thói quen.  
   **Bạn cần thấy:** Năm mô tả ngắn, từ nội dung thường lệ đến nội dung có hệ quả.

2. Với từng nội dung, đánh dấu các dấu hiệu hiện diện: đối tượng bên ngoài; hệ quả pháp lý hoặc tài chính; quyết định về con người; ảnh hưởng đến an toàn hoặc sức khỏe; không thể đảo ngược sau khi gửi.  
   **Vì sao:** Dấu hiệu kích hoạt là đặc điểm của tình huống; liệt kê chúng giúp vẻ trau chuốt của câu chữ không chi phối quyết định phân loại.  
   **Bạn cần thấy:** Mỗi nội dung có các dấu hiệu được đánh dấu hoặc được ghi nhận là không có dấu hiệu nào.

3. Với mỗi nội dung có dấu hiệu kích hoạt, nêu người đánh giá có chuyên môn phù hợp trong tổ chức: một người hoặc vai trò có năng lực ở chủ đề đó, không chỉ đơn thuần là người cấp cao.  
   **Vì sao:** Gọi tên một người thật giúp kiểm tra xem kênh chuyển cấp có tồn tại trước khi bạn cần dùng đến hay không.  
   **Bạn cần thấy:** Mỗi nội dung có dấu hiệu đều được chỉ định một người đánh giá cụ thể cùng chuyên môn làm căn cứ.

4. Với mỗi nội dung không có dấu hiệu kích hoạt, ghi lại những gì bạn sẽ kiểm tra cẩn thận, dùng thói quen đọc hai lượt ở mục tiêu 2.1 làm danh sách kiểm tra.  
   **Vì sao:** Tự đánh giá là cách xử lý phù hợp với công việc ít rủi ro; ghi lại giúp đây thực sự là một lượt đánh giá, không phải bỏ qua kiểm tra.  
   **Bạn cần thấy:** Ghi chú ngắn về cách tự đánh giá cho từng nội dung không có dấu hiệu.

5. Kiểm tra quyết định phân loại đã hoàn tất theo cả hai hướng sai lầm, sau đó lưu kết quả làm danh sách chuyển cấp dùng lâu dài.  
   **Vì sao:** Cả chuyển cấp thiếu lẫn chuyển cấp quá mức đều được kiểm tra và đều dễ nhận thấy khi quyết định được ghi lại.  
   **Bạn cần thấy:** Không bỏ qua nội dung hướng ra bên ngoài, không chuyển nội dung thường lệ vào hàng đợi của hội đồng, và có một danh sách có thể dùng lại.

## Nguồn

- Chính sách sử dụng (Usage Policy) — Anthropic
- Claude đang đưa ra câu trả lời không chính xác hoặc gây hiểu lầm. Chuyện gì đang xảy ra? — Anthropic
- Hướng dẫn kỳ thi Claude Certified Associate – Foundations — Anthropic

## Luyện tập miền này

- Bài tập thực hành
- Tham khảo nhanh
- Thuật ngữ
- Bài học trước: Kỹ thuật kiểm tra sự thật và xác thực
- Bài học tiếp theo: Chỉnh sửa, điều chỉnh và so sánh câu trả lời cho phù hợp với người đọc
