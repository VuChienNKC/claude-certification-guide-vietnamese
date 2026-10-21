# Xác định trường hợp sử dụng phù hợp và không phù hợp

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/6-governance-responsible-use/6-1-appropriate-use-cases

**Miền:** 6  
**Nhiệm vụ:** 6.1

## Những điều bạn cần biết

Hai câu hỏi quyết định một nhiệm vụ có nên giao cho Claude hay không. **Mức độ phù hợp về năng lực** hỏi Claude có thể làm tốt công việc này không: công việc có cấu trúc phù hợp, khối lượng phù hợp và đầu ra có thể được ai đó kiểm tra. Miền 4 đề cập đến mức độ phù hợp về năng lực. **Tính phù hợp về việc giao nhiệm vụ** hỏi liệu có nên giao công việc đó cho Claude hay không. Câu hỏi này dựa trên bằng chứng khác: mức độ hệ trọng, thẩm quyền chuyên môn mà công việc đòi hỏi và ai chịu trách nhiệm về kết quả. Một nhiệm vụ có thể hoàn toàn phù hợp với năng lực thực tế của Claude nhưng vẫn chỉ nên do một người có chuyên môn đảm nhận.

### Có năng lực làm việc không đồng nghĩa với được phép giao việc

Hãy hình dung chủ một cửa hàng xe đạp có hai việc cần xử lý. Việc thứ nhất là tóm tắt hàng loạt đánh giá của khách hàng thành các chủ đề. Việc thứ hai là chấm điểm một chồng đơn ứng tuyển vị trí thợ sửa xe để chọn người được tuyển. Chấm điểm đơn ứng tuyển rất phù hợp về mặt thực tế: có cấu trúc, khối lượng lớn và có thể kiểm tra. Tuy vậy, giao việc này vẫn có thể không phù hợp, bởi quyết định mà điểm số tạo ra và việc người bị ảnh hưởng không thể khiếu nại. Đáp án sai lặp đi lặp lại thường lập luận dựa trên chất lượng: Claude làm nhanh và tốt, nên giao việc chắc chắn ổn. Nhưng chất lượng chưa bao giờ là câu hỏi cần trả lời.

### Bốn nhóm trường hợp không phù hợp

Có bốn nhóm dễ nhận biết khiến một trường hợp sử dụng trở nên không phù hợp.

1. **Công việc cần thẩm quyền chuyên môn:** phán đoán pháp lý, y tế, tài chính và bảo vệ an toàn. Người có chuyên môn phải đưa ra và chịu trách nhiệm về những phán đoán này. Claude có thể giúp chuẩn bị, tóm tắt hoặc tìm hiểu, nhưng không thể là nguồn đưa ra lời khuyên. Ở cửa hàng xe đạp, tư vấn y tế cho khách hàng bị thương phải đến từ người đủ chuyên môn. **Usage Policy** (Chính sách sử dụng) nêu những lĩnh vực cần lưu ý nhất. Các **High-risk Areas** (Lĩnh vực rủi ro cao) gồm tư vấn pháp lý và y tế, tài chính, tín dụng, bảo hiểm, nhà ở, việc làm, giáo dục và quyền tiếp cận dịch vụ chăm sóc sức khỏe. Trong những lĩnh vực này, người có chuyên môn phải xem xét khuyến nghị của Claude trước khi khuyến nghị được đưa ra thành lời khuyên hoặc được dùng để ra quyết định; và “Người có chuyên môn vẫn chịu trách nhiệm về tính chính xác và phù hợp của nội dung được cung cấp hoặc quyết định được đưa ra.” Chính sách loại trừ nội dung về sức khỏe tổng quát, chẳng hạn kiến thức về giấc ngủ, căng thẳng, dinh dưỡng hoặc tập thể dục.
2. **Quyết định có hệ quả đáng kể về những người có thể nhận diện:** ai được tuyển, nhận giải, chịu hình thức kỷ luật hoặc được thăm khám. Đầu ra kém chất lượng không phải lý do. Vấn đề là không ai chịu trách nhiệm về quyết định và người bị ảnh hưởng không thể phản đối quyết định đó. Việc chấm điểm ứng viên thợ sửa xe thuộc nhóm này.
3. **Bịa đặt và trình bày như sự thật:** trích dẫn, lời chứng thực, nghiên cứu tình huống hoặc bằng chứng được tạo ra, chẳng hạn cửa hàng tự viết lời chứng thực giả của khách hàng. Tính hợp lý của nội dung bịa đặt khiến vấn đề nghiêm trọng hơn, vì một điều bịa nghe có vẻ đáng tin sẽ dễ được tin hơn. Các điều khoản trong Usage Policy cấm thông tin sai lệch và hành vi lừa dối là nền tảng của nhóm này.
4. **Bất cứ điều gì bị Usage Policy hoặc chính sách riêng của tổ chức cấm.** Mục tiêu 6.3 đề cập lĩnh vực này.

### Phép thử thay thế

Hãy dùng phép thử sau để phân loại nhiệm vụ. Hãy hình dung một đồng nghiệp có năng lực và thiện chí, nhưng:

- không có bằng cấp chuyên môn trong lĩnh vực đó;
- không được tiếp cận lịch sử của người liên quan;
- không chịu trách nhiệm về kết quả.

Bạn có chấp nhận phần việc của họ không? Phép thử này biến câu hỏi trừu tượng về tính phù hợp thành một nhận định giao việc thông thường mà mọi chuyên gia đều đã thực hiện. Bản tóm tắt đánh giá đạt yêu cầu: đồng nghiệp đó có thể viết và chủ cửa hàng sẽ kiểm tra. Việc chấm điểm ứng viên thợ sửa xe trượt cả ba tiêu chí cùng lúc. Khung **AI Fluency** gọi kỹ năng này là **Delegation** (Giao việc).

### Phần lớn công việc đều phù hợp

Điều cần lưu ý ngược lại cũng quan trọng không kém các nhóm trên. Tài liệu chính thức mô tả một phạm vi sử dụng phù hợp khá rộng: viết nhiều định dạng, tóm tắt tài liệu dài, lên ý tưởng, phân tích hình ảnh và dữ liệu, dịch thuật. Soạn thảo, định dạng lại, phân tích tài liệu bạn đang nắm giữ và chuẩn bị thông tin để ai đó đưa ra quyết định đều phù hợp. Các nhóm không phù hợp hẹp và cụ thể. Cho rằng mọi việc gần với các nhóm đó đều bị cấm sẽ khiến bạn bỏ qua những công việc có thể thực hiện với một biện pháp bảo vệ đơn giản. Chủ cửa hàng vẫn có thể yêu cầu tóm tắt từng đơn ứng tuyển, sau đó tự đọc và lựa chọn.

### Trong kỳ thi

Mục tiêu này đặt một câu hỏi khác với các phần còn lại của chứng chỉ, và thí sinh đã học Miền 4 thường trả lời nhầm câu hỏi. Phép thử thay thế bao quát toàn bộ phạm vi nội dung thi. Kỳ thi cũng đánh giá việc quá thận trọng là sai: đáp án chuẩn hầu như luôn tìm cách thực hiện công việc trong khuôn khổ quy định.

### Dấu hiệu trong đề thi

Thêm bước rà soát vào một nhiệm vụ không phù hợp không làm cho việc giao nhiệm vụ đó trở nên phù hợp. Việc quản lý kiểm tra đầu ra của một quyết định có hệ quả về người có thể nhận diện không khôi phục được trách nhiệm đối với phán đoán, cũng không giúp người bị ảnh hưởng có thể khiếu nại. Chủ cửa hàng tự đọc điểm số của từng ứng viên cũng không thay đổi điều đó. Các lựa chọn cho rằng rà soát là cách khắc phục đang kiểm tra chính điểm này.

Quy tắc rà soát trong Usage Policy trả lời một câu hỏi khác. Khi một trường hợp sử dụng trong High-risk Areas được tiến hành, chính sách yêu cầu: “Người có chuyên môn phải xem xét có ý nghĩa một Khuyến nghị AI rủi ro cao và có thẩm quyền thay đổi hoặc sửa đổi khuyến nghị đó trước khi nó được đưa ra dưới dạng lời khuyên.” Trong trường hợp đó, rà soát là biện pháp kiểm soát bắt buộc và mục tiêu 2.4 dạy đây là tiêu chuẩn. Rà soát không thể biến một quyết định lẽ ra không nên giao thành quyết định có thể giao. Trước tiên, hãy hỏi việc giao nhiệm vụ có phù hợp không. Chỉ sau đó mới áp dụng yêu cầu rà soát.

Khung AI Fluency liệt kê bốn chữ D dưới dạng tên mô-đun nhưng không định nghĩa chúng. Cách diễn giải Delegation là “quyết định giao việc gì cho AI và giữ lại việc gì” là phần chú giải của chúng tôi. Bài viết use-case của Help Center liệt kê những việc Claude có thể làm nhưng không nêu điều cấm. Các nhóm trường hợp không phù hợp dựa trên Usage Policy và hướng dẫn thi.

## Những bẫy trong kỳ thi

### Bẫy trong kỳ thi: Nhầm khả năng thực hiện phù hợp với quyền được tiến hành

Mức độ phù hợp về năng lực và tính phù hợp của việc giao nhiệm vụ là hai phép thử riêng, dựa trên bằng chứng khác nhau. Một công việc có thể có cấu trúc, khối lượng lớn và có thể kiểm tra — tất cả đều là điều Miền 4 yêu cầu — nhưng vẫn không phù hợp vì việc đánh giá tính phù hợp dựa trên trách nhiệm giải trình và khả năng khiếu nại, không phải mức độ Claude có thể làm tốt đến đâu.

### Bẫy trong kỳ thi: Chấp nhận lý do “chỉ dùng nội bộ”

Lý do kết quả không rời khỏi tổ chức xuất hiện làm phương án gây nhiễu trong nhiều câu hỏi của miền này và không bao giờ là đáp án chuẩn. Giữ kết quả trong nội bộ không khôi phục trách nhiệm giải trình cho quyết định mà kết quả đó ảnh hưởng, cũng không tạo lại con đường khiếu nại cho người bị ảnh hưởng.

### Bẫy trong kỳ thi: Từ chối cả hai phần của một đề xuất kết hợp

Kiêng dùng AI vì quá thận trọng là phương án sai nhưng có vẻ hợp lý thứ hai. Khi đề xuất kết hợp việc phù hợp và không phù hợp, đáp án chuẩn giữ phần phù hợp và chỉ từ chối phần không phù hợp. Từ chối cả hai sẽ lãng phí công cụ và hiểu sai miền kiến thức.

## Tình huống thực hành

Một quản lý trung tâm dành cho trẻ em được đề nghị dùng Claude để xử lý khảo sát gia đình hằng năm. Có hai đề xuất cùng lúc: tóm tắt ba trăm câu trả lời tự do thành các chủ đề để rà soát dịch vụ, và chấm điểm câu trả lời của từng gia đình để xác định gia đình nào nên được thăm nhà. Việc rà soát dịch vụ cần các chủ đề. Chính sách của trung tâm cho phép dùng Claude với nội dung khảo sát nhưng cấm mọi công cụ chấm điểm gia đình để quyết định thăm nhà. Người quản lý nên làm gì?

**Lựa chọn A**  
Sau khi xóa thông tin nhận diện, tóm tắt các câu trả lời thành chủ đề và giao việc xác định gia đình cần thăm nhà cho nhân viên đủ chuyên môn của trung tâm.

**Lựa chọn B**  
Thực hiện việc chấm điểm như đề xuất, rồi yêu cầu phó giám đốc rà soát từng gia đình được đánh dấu trước khi có chuyến thăm để vẫn có người tham gia quyết định.

**Lựa chọn C**  
Từ chối cả hai đề xuất vì nội dung khảo sát gia đình quá nhạy cảm, không công cụ AI nào được phép xử lý.

**Lựa chọn D**  
Thực hiện cả hai việc vì dữ liệu khảo sát không rời khỏi trung tâm và các gia đình đã đồng ý cho dùng dữ liệu vào việc lập kế hoạch dịch vụ khi hoàn thành khảo sát.

## Bài tập thực hành

### Phân loại hai tuần công việc thực tế

**Thời lượng:** 25 phút

**Bạn sẽ học được**

- Cách áp dụng phép thử thay thế cho các nhiệm vụ thực tế.
- Cách xác định nhóm nào trong bốn nhóm khiến một nhiệm vụ không phù hợp.
- Cách viết biện pháp bảo vệ giúp thực hiện một nhiệm vụ ở ranh giới giữa hai nhóm.
- Cách kiểm tra nhận định của chính bạn để tránh quá thận trọng.

1. Liệt kê mười công việc gần đây bạn đã giao cho Claude hoặc đã cân nhắc giao, cùng hai việc bạn sẽ không bao giờ giao.

   **Lý do:** Phép thử cần những công việc giao thực tế để có tác dụng; ví dụ tự nghĩ ra thường làm bài tập có vẻ dễ hơn và che giấu thói quen thật của bạn.  
   **Bạn sẽ thấy:** Danh sách mười hai nhiệm vụ bằng lời của bạn, mỗi nhiệm vụ một dòng.

2. Áp dụng phép thử thay thế cho từng việc: bạn có chấp nhận giao việc đó cho một đồng nghiệp có năng lực nhưng không có chuyên môn trong lĩnh vực, không được tiếp cận những người liên quan và không chịu trách nhiệm về kết quả không?

   **Lý do:** Phép thử chuyển khái niệm về tính phù hợp thành một nhận định giao việc mà bạn vốn đã biết cách đưa ra.  
   **Bạn sẽ thấy:** Mỗi nhiệm vụ được đánh dấu đạt hoặc không đạt, kèm lý do trượt: chuyên môn, lịch sử hay trách nhiệm giải trình.

3. Chia danh sách thành nhóm phù hợp và không phù hợp; với mỗi việc không phù hợp, nêu rõ việc đó thuộc nhóm nào trong bốn nhóm.

   **Lý do:** Gọi tên đúng nhóm là kỹ năng cần cho kỳ thi: đề đánh giá người biết giải thích tại sao một cách sử dụng không phù hợp, chứ không chỉ cảm thấy nó có vẻ rủi ro.  
   **Bạn sẽ thấy:** Mỗi nhiệm vụ không phù hợp được gắn một nhãn: thẩm quyền chuyên môn, quyết định có hệ quả, bịa đặt hoặc bị chính sách cấm.

4. Với mọi nhiệm vụ ở ranh giới, viết biện pháp bảo vệ có thể cho phép tiến hành: cần thay đổi điều gì — tài liệu, lộ trình hay quyền cho phép?

   **Lý do:** Đáp án chuẩn hầu như luôn tìm cách thực hiện công việc; kỹ năng chuyên nghiệp là tìm biện pháp bảo vệ, không phải tìm lý do để từ chối.  
   **Bạn sẽ thấy:** Một biện pháp bảo vệ cho mỗi nhiệm vụ ở ranh giới, đủ cụ thể để áp dụng ngay ngày mai.

5. Kiểm tra xem nhóm phù hợp có nhiều hơn không. Nếu không, hãy xem lại kết quả phép thử và lưu ý đến yếu tố cân bằng.

   **Lý do:** Quá thận trọng là lỗi mà các phương án gây nhiễu trong mục tiêu này nhắm đến; nếu phần lớn nhiệm vụ bị xếp vào nhóm không phù hợp, có thể bạn đã áp dụng phép thử quá khắt khe.  
   **Bạn sẽ thấy:** Ít nhất tám trong mười hai nhiệm vụ nằm trong nhóm phù hợp, hoặc có lời giải thích bằng văn bản vì sao công việc của bạn thực sự đặc biệt.

## Nguồn

- Usage Policy — Anthropic
- What are some things I can use Claude for? — Anthropic
- AI Fluency: Framework and Foundations — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic. Bài viết Help Center mô tả các trường hợp sử dụng phù hợp nhưng không liệt kê điều cấm. Các nhóm không phù hợp đến từ Usage Policy và mục tiêu trong hướng dẫn thi.

**Luyện tập Miền này** · **Bài tập thực hành** · **Tham khảo nhanh** · **Thuật ngữ**  
**Bài học trước:** Cung cấp thông tin, duy trì và cập nhật cấu hình  
**Bài học tiếp theo:** Áp dụng các cân nhắc về độ nhạy cảm của dữ liệu, quy định và quyền riêng tư
