# Sử dụng Claude để nghiên cứu, lập kế hoạch và tối ưu hóa quy trình

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-2-research-planning-optimisation

**Miền:** 4

**Nhiệm vụ:** 4.2

## Những điều bạn cần biết

Nghiên cứu thu thập và tổng hợp tài liệu bên ngoài, vì vậy bạn bắt đầu từ những gì đã có thay vì một trang giấy trắng. Lập kế hoạch biến mục tiêu thành các bước theo thứ tự. Tối ưu hóa quy trình tìm và khắc phục bước làm chậm quy trình. Cả ba đều có chung một cấu trúc: Claude tạo bản nháp đầu tiên, còn bạn chịu trách nhiệm đưa ra nhận định sau đó.

Hãy hình dung một công ty môi giới bất động sản, nơi người quản lý dùng Claude cho cả ba việc: tìm hiểu cách định giá của các công ty khác, lên kế hoạch cho cuối tuần mở cửa đón khách xem nhà và xử lý quy trình cho thuê nhà đang chậm.

## Nghiên cứu ở hai quy mô

Sản phẩm hỗ trợ nghiên cứu ở hai quy mô, và Help Center phân biệt rõ chúng. **Tìm kiếm web (Web search)** phù hợp với những câu hỏi đơn giản về dữ kiện mà một hoặc hai lượt tra cứu có thể trả lời. **Chế độ Nghiên cứu (Research mode)** thực hiện nhiều lượt tìm kiếm, dùng kết quả của lượt trước làm cơ sở cho lượt sau. Chế độ này khảo sát các góc độ khác nhau của câu hỏi và giải quyết có hệ thống những điểm còn bỏ ngỏ. Kết quả gồm các phát hiện có trích dẫn, phù hợp với những công việc lớn cần nhiều nguồn. Ở công ty môi giới, tra cứu một quy định về cho thuê là tìm kiếm web; khảo sát cách định giá là dùng Research.

Giá trị của tính năng là độ bao quát và tốc độ. Giới hạn là mọi thông tin quan trọng đều cần được kiểm tra trước khi truyền đạt lại, dù có trích dẫn hay không: trích dẫn cho biết phát hiện đến từ đâu, chứ không chứng minh phát hiện đó đúng.

## Kế hoạch được xây dựng từ những ràng buộc đã nêu

Một kế hoạch nháp đầu tiên tốt hơn một trang giấy trắng. Claude đặc biệt giỏi bảo đảm tính đầy đủ. Hãy hỏi kế hoạch còn thiếu gì, bạn sẽ nhận được các điểm phụ thuộc lẫn nhau, vấn đề về thứ tự và bước mà mọi người thường quên.

Claude cũng sẽ tự tin lập kế hoạch mà không tính đến những ràng buộc bạn chưa hề đề cập, bởi nó không biết chúng: lối vào duy nhất dành cho người khuyết tật, tình nguyện viên không thể làm vào Chủ nhật, hay căn phòng đã bị đặt trùng lịch. Kết quả không cảnh báo rằng kế hoạch được lập khi thiếu những thông tin đó. Một kế hoạch mở cửa đón khách xem nhà không có ràng buộc có thể xếp nhân viên tư vấn vào các buổi xem nhà Chủ nhật dù người đó không bao giờ làm Chủ nhật. Kế hoạch ấy xa rời thực tế nhưng được trình bày như thể người lập rất am hiểu, nguy hiểm hơn một kế hoạch rõ ràng tệ vì nó khiến người khác tin tưởng.

Biện pháp khắc phục rất đơn giản. Hướng dẫn prompt engineering cho doanh nghiệp của Anthropic khuyên hãy xem Claude như một thực tập sinh trong ngày đầu tiên: đưa chỉ dẫn rõ ràng, tường minh và đầy đủ mọi chi tiết cần thiết. Để có kế hoạch hữu ích, hãy nêu các ràng buộc thực tế trong bản giao việc, rồi hỏi Claude những giả định nào làm cơ sở cho kế hoạch. Khi giả định được nêu rõ, bạn có thể sửa nó.

## Vòng lặp tối ưu hóa

Claude đưa ra các giả thuyết về điểm nghẽn, khâu dễ xảy ra sai sót hoặc công việc bị làm trùng của quy trình. Nó không thể biết giả thuyết nào đúng vì chưa từng quan sát quy trình của bạn vận hành. Dữ liệu sẽ quyết định. Vòng lặp gồm bốn bước:

1. Mô tả quy trình và các ràng buộc.
2. Yêu cầu Claude đề xuất các điểm nghẽn có thể có và bằng chứng xác nhận từng điểm.
3. Thu thập những bằng chứng đó.
4. Thay đổi bước mà bằng chứng chỉ ra là nguyên nhân.

Bằng chứng được thu thập sau khi các giả thuyết đã được nêu, để bạn biết mình cần tìm gì. Bằng chứng được thu thập trước khi thay đổi bất cứ điều gì, để thay đổi có mục tiêu cụ thể. Với quy trình cho thuê của công ty, Claude có thể gợi ý khâu kiểm tra thông tin và hồ sơ người thuê bị chậm hoặc chủ nhà phê duyệt muộn; ngày tháng ở từng giai đoạn trong hồ sơ nội bộ sẽ quyết định.

Cũng hướng dẫn đó khuyên nên tiếp cận công việc như một nhà khoa học, thường xuyên thử nghiệm và lặp lại, đồng thời kết hợp việc xây dựng prompt với các chuyên gia trong lĩnh vực liên quan của tổ chức thay vì chỉ tin vào một bên.

## Chọn nhầm điểm nghẽn

Sai lầm tốn kém nhất là tối ưu một bước vốn không phải điểm nghẽn. Việc đó tiêu tốn ngân sách và sự sẵn lòng thay đổi cho một việc vốn vẫn ổn. Sai lầm thường xảy ra khi coi giả thuyết nghe hợp lý nhất là kết luận đã được xác nhận. Nguyên nhân nghe hợp lý đôi khi trùng với nguyên nhân thực tế, đủ để khiến ta dễ tin, nhưng cũng đủ thường xuyên không trùng để gây tốn kém. Thường chỉ cần một ngày làm việc để thu thập bằng chứng phân biệt chúng. Nếu mua dịch vụ kiểm tra thông tin và hồ sơ người thuê nhanh hơn trong khi dữ liệu chỉ ra chủ nhà phê duyệt muộn, công ty vừa tốn tiền vừa không giải quyết được sự chậm trễ.

## Trong kỳ thi

Kỳ thi kiểm tra khả năng phán đoán, chứ không phải bản nháp đầu tiên. Mọi đáp án đúng trong mục tiêu này đều cung cấp những dữ kiện Claude không thể biết hoặc kiểm tra thông tin trước khi hành động. Các phương án gây nhiễu lặp đi lặp lại lỗi coi kết quả trôi chảy là kết quả hoàn chỉnh. Miền 3 quyết định tính năng nào phục vụ nghiên cứu; mục tiêu này kiểm tra cách thực hành quanh tính năng đó. Kiểm tra phát hiện trước khi truyền đạt lại là nguyên tắc của Miền 2.

### Dấu hiệu của người làm chuyên nghiệp

Trong các câu hỏi thuộc mục tiêu này, đáp án đúng kiểm tra bằng chứng trước khi thay đổi bất cứ điều gì: thời gian của mùa trước, hồ sơ sử dụng, nhật ký khiếu nại. Các phương án gây nhiễu xây dựng lại quy trình dựa trên lập luận trôi chảy, hoặc tìm đến tính năng lớn hơn trong khi còn thiếu dữ kiện tại chỗ.

## Bẫy trong kỳ thi

### Bẫy: Coi kế hoạch có vẻ hợp lý và được cấu trúc tốt là kế hoạch đã được kiểm tra

Tính hợp lý là đặc tính của câu chữ; tính hợp lệ phụ thuộc vào các ràng buộc và dữ kiện mà người lập kế hoạch cung cấp. Kế hoạch được lập mà không có ràng buộc thực tế sẽ thất bại khi gặp sự kiện thật. Vì vậy, đáp án đúng nêu rõ các ràng buộc ngay từ đầu hoặc xác thực bản nháp dựa trên chúng trước khi sử dụng.

### Bẫy: Thay đổi quy trình chỉ dựa trên giả thuyết nghe thuyết phục nhất

Các điểm nghẽn Claude đề xuất là giả thuyết, không phải chẩn đoán; Claude chưa từng quan sát quy trình vận hành. Hành động theo giả thuyết có vẻ hợp lý nhất sẽ tiêu tiền vào một bước chưa có bằng chứng cho thấy là nguyên nhân. Đáp án đúng thu thập bằng chứng trước.

### Bẫy: Dùng nghiên cứu bổ sung thay cho bằng chứng tại chỗ

Trích dẫn từ nơi khác không thể cho biết nguyên nhân nào đúng trong quy trình của bạn. Khi câu hỏi là vì sao chính quy trình này lại hoạt động theo cách hiện tại, dữ liệu tại chỗ mới là bằng chứng quyết định; không lượng tổng hợp thông tin bên ngoài nào có thể thay thế. Nâng cấp tính năng không đồng nghĩa với trả lời được câu hỏi.

## Tình huống thực hành

Điều phối viên của một chương trình cho thuê xe đạp trong thành phố liên tục nghe phản ánh rằng các trạm xe ở vùng ven đô nơi người dân đi làm vào thành phố đều đã hết xe vào tám giờ sáng. Cô mô tả chương trình cho Claude, và Claude đề xuất bốn nguyên nhân có thể xảy ra:

- Lượt điều chuyển xe ban đêm kết thúc quá sớm.
- Hai trạm trong khu dân cư cùng phục vụ một cụm văn phòng.
- Công tác bảo trì cuối tuần khiến xe không thể hoạt động vào thứ Hai.
- Người đi xe đến trạm đã đầy sẽ tiếp tục đi nơi khác cùng chiếc xe.

Chỉ số liệu của chính chương trình mới xác định được nguyên nhân nào đang xảy ra, và cô sẽ không hành động theo giả thuyết nào cho đến khi có bằng chứng. Bước tiếp theo chuyên nghiệp là gì?

**Phương án A**

Lập tức bổ sung lượt điều chuyển xe thứ hai vào buổi sáng, vì nguyên nhân đầu tiên Claude liệt kê có vẻ hợp lý nhất và khiếu nại xảy ra vào buổi sáng.

**Phương án B**

Hỏi Claude bằng chứng nào sẽ xác nhận hoặc loại trừ từng nguyên nhân, sau đó lấy dữ liệu chuyến đi và việc nhận, trả xe tại trạm của chương trình trước khi thay đổi bất cứ điều gì.

**Phương án C**

Đặt lại câu hỏi trong Research mode để bốn nguyên nhân được hỗ trợ bằng trích dẫn từ các chương trình xe đạp ở thành phố khác.

**Phương án D**

Yêu cầu Claude thiết kế lại mạng lưới trạm theo luồng đi làm, coi việc các trạm buổi sáng hết xe là bằng chứng đủ để kết luận bố trí hiện tại không hiệu quả.

## Bài tập thực hành

### Lập kế hoạch hai lần, rồi tìm điểm nghẽn thật

**Độ khó:** Trung cấp (2/4)

**Thời lượng:** 40 phút

**Bạn sẽ học được**

- Các ràng buộc được nêu rõ làm thay đổi tính hữu ích của bản kế hoạch nháp như thế nào.
- Cách nhận ra lỗi “xa rời thực tế nhưng trông như do người am hiểu lập ra”.
- Cách thực hiện vòng lặp mô tả, giả thuyết, bằng chứng, thay đổi.
- Cách kiểm tra xem dữ liệu có chỉ ra bước mà bạn vốn sẽ đoán hay không.

1. **Chọn một công việc sắp tới có những ràng buộc thật:** sự kiện, lịch trực, đợt ra mắt hay việc gì đó thực sự thuộc trách nhiệm của bạn.

   **Vì sao:** Bài tập chỉ hiệu quả khi bạn hiểu rõ các ràng buộc thực tế để nhận ra kế hoạch nào bỏ qua chúng.

   **Bạn cần thấy:** Một công việc cụ thể được gọi tên và ba ràng buộc hạn chế công việc nhiều nhất (giữ riêng cho bạn).

2. **Yêu cầu Claude lập kế hoạch nháp hai lần:** lần đầu không nêu ràng buộc, lần sau nêu ba ràng buộc thực tế quan trọng nhất.

   **Vì sao:** Việc so sánh cho thấy rõ lỗi cốt lõi của mục tiêu: kế hoạch không nêu ràng buộc vẫn có vẻ được lập thành thạo như kế hoạch nêu ràng buộc.

   **Bạn cần thấy:** Hai kế hoạch trôi chảy, khác nhau đúng ở những chỗ chịu ảnh hưởng của các ràng buộc.

3. **Liệt kê điều kế hoạch không có ràng buộc đã làm sai nhưng vẫn có vẻ hoàn toàn hợp lý.**

   **Vì sao:** Gọi tên những điểm hư cấu cụ thể giúp hình thành phản xạ kiểm tra kế hoạch bằng sự thật thay vì độ trôi chảy.

   **Bạn cần thấy:** Ba hoặc bốn lỗi cụ thể, người không biết các ràng buộc sẽ không nhận ra những lỗi này.

4. **Chọn một quy trình có vẻ chậm, mô tả toàn bộ quy trình cho Claude, rồi yêu cầu bốn điểm nghẽn có thể có và bằng chứng xác nhận hoặc loại trừ từng điểm.**

   **Vì sao:** Đây là nửa đầu của vòng lặp tối ưu hóa: lập giả thuyết và nêu bằng chứng giúp phân biệt chúng.

   **Bạn cần thấy:** Bốn nguyên nhân có thể có, mỗi nguyên nhân đi kèm một bằng chứng cụ thể có thể thu thập.

5. **Trong tuần này, thu thập một trong các bằng chứng đó và ghi lại liệu dữ liệu có chỉ ra bước mà bạn đã đoán hay không.**

   **Vì sao:** Khoảng cách giữa điểm nghẽn bạn đoán và điểm nghẽn được bằng chứng xác nhận chính là bài học; hầu hết mọi người đều ít nhất một lần bất ngờ.

   **Bạn cần thấy:** Một bằng chứng dữ liệu thực tế và kết luận một dòng: dự đoán đúng hay sai.

## Nguồn

- [Use research on Claude](https://support.claude.com/en/articles/11088861-use-research-on-claude) — Anthropic
- [When should I use web search, extended thinking, and research?](https://support.claude.com/en/articles/11095361-when-should-i-use-web-search-extended-thinking-and-research) — Anthropic
- [Prompt engineering for business performance](https://www.anthropic.com/news/prompt-engineering-for-business-performance) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

Không có tài liệu nào của Anthropic đề cập đến tối ưu hóa quy trình như một kỹ năng kinh doanh. Bài học này dựa trên mục tiêu trong hướng dẫn kỳ thi và thực hành tiêu chuẩn; các bài viết ở trên chỉ hỗ trợ những luận điểm được trích dẫn từ chúng.

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=4) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/4-workflow-integration) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-4) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-4)

**Bài học trước:** [Phân tích yêu cầu và trường hợp sử dụng](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-1-requirements-and-use-cases)

**Bài học tiếp theo:** [Hỗ trợ thiết kế, phát triển và lặp lại giải pháp](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-3-solution-design-iteration)
