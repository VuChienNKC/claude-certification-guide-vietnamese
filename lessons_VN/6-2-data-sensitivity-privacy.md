# Áp dụng các cân nhắc về độ nhạy cảm của dữ liệu, quy định và quyền riêng tư

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/6-governance-responsible-use/6-2-data-sensitivity-privacy

**Miền:** 6  
**Nhiệm vụ:** 6.2

## Những điều bạn cần biết

Tài liệu nhạy cảm là bất kỳ nội dung nào mà tổ chức không nên giao cho một dịch vụ bên ngoài nếu chưa có quyết định cho phép. Đó có thể là dữ liệu cá nhân, hoặc tài liệu nhạy cảm vì ai sở hữu nó hay những điều đã cam kết về cách xử lý. Biện pháp bảo vệ làm thay đổi nội dung rời khỏi phạm vi kiểm soát của tổ chức. Có bốn nấc bảo vệ theo một thứ tự cố định. Một biện pháp chỉ có tác dụng trên danh nghĩa sẽ chỉ được thực hiện sau khi tài liệu đã đi khỏi tay bạn.

Quản lý một nhà trẻ muốn nhờ Claude giải thích vì sao khoản học phí còn nợ tăng trong học kỳ này. Bảng tính của cô có tên, ngày sinh, địa chỉ và ghi chú về dị ứng của từng trẻ, cùng số tài khoản và khoản thanh toán của phụ huynh. Tải nguyên bảng tính lên sẽ gửi toàn bộ thông tin ra ngoài. Từ chối thì không tìm ra nguyên nhân khoản nợ tăng. Câu trả lời nằm giữa hai lựa chọn đó: áp dụng biện pháp bảo vệ để có thể làm công việc theo đúng chính sách.

### Nhận biết tài liệu nhạy cảm

Danh sách dễ nhận ra gồm tên, địa chỉ, ngày sinh, mã tham chiếu và số tài khoản, thông tin sức khỏe, chi tiết tài chính và mọi thông tin về trẻ em. Mọi người thường bỏ sót các nhóm liên quan đến quyền sở hữu và cam kết:

- thông tin được nắm giữ theo nghĩa vụ bảo mật;
- số liệu mật về thương mại;
- tài liệu của bên thứ ba mà hợp đồng quy định cách xử lý.

Bảng giá của nhà cung cấp không có dữ liệu cá nhân. Tuy nhiên, nó vẫn có thể là tài liệu bị hạn chế nhất trên bàn làm việc vì cách xử lý có thể do hợp đồng quy định. Bảng giá của nhà cung cấp thực phẩm cho nhà trẻ là một ví dụ.

Usage Policy của Anthropic xếp dữ liệu mật hoặc độc quyền cùng với thông tin liên hệ không công khai và dữ liệu sức khỏe vào nhóm thông tin riêng tư không được sử dụng sai mục đích hoặc truy cập nếu chưa được phép. Chính sách cũng cấm xâm phạm quyền riêng tư theo quy định của luật quyền riêng tư hiện hành, chẳng hạn chia sẻ thông tin cá nhân khi chưa có sự đồng ý.

Bài viết về các biện pháp bảo vệ của Anthropic mô tả việc mã hóa dữ liệu khi truyền và khi lưu trữ, đồng thời mặc định chặn nhân viên truy cập dữ liệu. Những biện pháp đó bảo vệ dữ liệu Anthropic nắm giữ. Chúng không thay thế quyết định riêng của tổ chức bạn về nội dung nào được phép rời khỏi phạm vi kiểm soát của tổ chức.

### Các nấc bảo vệ, theo đúng thứ tự

Mỗi nấc giữ lại được nhiều phần công việc hơn nấc tiếp theo, vì vậy hãy chọn nấc thấp nhất có thể giải quyết vấn đề.

1. **Loại bỏ.** Phần lớn phân tích không cần tên. Hãy xóa thông tin nhận diện rồi tiến hành ngay. Câu hỏi về khoản nợ cần các mẫu hình thanh toán, vì vậy hãy xóa tên và địa chỉ của trẻ.
2. **Ẩn danh hoặc tổng hợp.** Dùng nhóm đối tượng thay cho từng cá nhân, và dùng khoảng thay vì con số chính xác. Nhà trẻ có thể nhóm gia đình theo phòng và trình bày khoản nợ dưới dạng các khoảng.
3. **Dùng lộ trình được cho phép.** Chuyển công việc sang một workspace được phê duyệt theo thỏa thuận bao quát loại tài liệu này.
4. **Xin phép.** Đưa câu hỏi đến người sở hữu dữ liệu hoặc chính sách. Đây là một hành động, không phải lời từ chối.

Từ bỏ công việc là lựa chọn cuối cùng: nếu ẩn danh cho phép tiếp tục phân tích, thì bỏ cuộc không đem lại lợi ích gì.

### Vì sao biện pháp chỉ có tác dụng trên danh nghĩa không hiệu quả

Biện pháp kiểm soát của chính sách liên quan đến nội dung rời khỏi phạm vi kiểm soát của tổ chức, và điều đó xảy ra khi tải lên. Một bước làm sau đó không thể đảo ngược việc này. Mọi biện pháp chỉ có tác dụng trên danh nghĩa đều thất bại theo cách đó: bảo Claude quên tài liệu, tuyên bố nội dung tải lên là bảo mật, thêm dòng bảo mật vào câu lệnh hoặc xóa cuộc trò chuyện. Nếu quản lý nhà trẻ tải toàn bộ bảng tính lên rồi yêu cầu Claude không lưu lại, thông tin chi tiết vẫn đã được gửi đi. Không nội dung nào được nhập vào cuộc trò chuyện có thể hồi tố quy định cách xử lý nội dung đã tải lên. Biện pháp bảo vệ phải được áp dụng trước khi tải lên, nếu không thì không còn tác dụng.

### Bạn đang dùng sản phẩm nào?

Hiện có hai bài viết về quyền riêng tư của Anthropic cùng mang chính xác tiêu đề “Is my data used for model training?” (Dữ liệu của tôi có được dùng để huấn luyện mô hình không?). Một bài nói về sản phẩm dành cho người tiêu dùng, bài còn lại về sản phẩm thương mại; nội dung trả lời khác nhau. Theo mặc định, Anthropic không dùng đầu vào hoặc đầu ra từ sản phẩm thương mại, chẳng hạn Claude for Work, để huấn luyện mô hình. Cách xử lý dữ liệu phụ thuộc vào gói dịch vụ, và chi tiết đã thay đổi theo lịch sử của các tài liệu. Vì vậy, thay vì ghi nhớ câu trả lời hiện tại, hãy đặt ba câu hỏi: Tôi đang dùng sản phẩm nào? Tài liệu hướng dẫn của sản phẩm đó hiện nói gì? Thỏa thuận của tổ chức bổ sung điều gì? Quản lý nhà trẻ cần hỏi những điều này trước. Mục tiêu 6.3 đề cập những việc cần làm dựa trên câu trả lời.

### Trong kỳ thi

Câu hỏi mẫu của hướng dẫn thi trong miền này nói về một quản lý dự án muốn tải lên bảng tính chứa tên và số tài khoản của khách hàng. Đáp án chuẩn không tải nguyên dữ liệu lên cũng không từ bỏ phân tích. Đáp án ẩn danh dữ liệu để công việc có thể tiếp tục trong khuôn khổ chính sách. Cấu trúc đó — một biện pháp bảo vệ cho phép tiếp tục nằm giữa hai thái cực sai — thu nhỏ mục tiêu này thành hình mẫu điển hình. Kỹ năng được kiểm tra là biết thứ tự các nấc. Hầu như không bao giờ chọn đáp án từ bỏ công việc vì lý do giải thích trong hướng dẫn là ẩn danh cho phép tiến hành phân tích. Hướng dẫn cũng nói rằng bảo mô hình không lưu dữ liệu không đáp ứng yêu cầu kiểm soát của chính sách.

### Dấu hiệu trong đề thi

Mọi lựa chọn có biện pháp bảo vệ chỉ hoạt động sau khi tải lên đều sai. Không biện pháp nào chỉ có tác dụng trên danh nghĩa được chọn làm đáp án chuẩn. Đáp án chuẩn thay đổi nội dung được đưa vào, không phải việc xảy ra sau đó.

Chi tiết về xóa và lưu giữ dữ liệu thay đổi thường xuyên. Phần tham khảo nhanh của Miền 6 có các con số hiện hành kèm ngày cập nhật.

## Những bẫy trong kỳ thi

### Bẫy trong kỳ thi: Coi hướng dẫn bảo mật hoặc việc xóa dữ liệu sau đó là biện pháp bảo vệ

Phần giải thích câu hỏi mẫu trong chính hướng dẫn thi nêu rõ rằng bảo mô hình không lưu dữ liệu không đáp ứng yêu cầu kiểm soát của chính sách. Việc tiết lộ xảy ra lúc tải lên; mọi việc thuộc nhóm biện pháp chỉ có tác dụng trên danh nghĩa đều xảy ra sau đó.

### Bẫy trong kỳ thi: Đi lên nấc cao hơn dù chỉ cần loại bỏ thông tin

Chuyển công việc sang workspace được phê duyệt hoặc xin phép nghe có vẻ cẩn trọng. Nhưng nếu chỉ cần xóa thông tin nhận diện là có thể tiếp tục ngay, các nấc cao hơn làm mất thời gian mà không tăng thêm lợi ích bảo vệ. Đáp án chuẩn là nấc thấp nhất đáp ứng yêu cầu.

### Bẫy trong kỳ thi: Xóa một tài liệu chỉ vì nó không có tên người

Độ nhạy cảm không chỉ nằm ở thông tin nhận diện cá nhân. Nghĩa vụ bảo mật, bí mật thương mại và hạn chế trong hợp đồng với bên thứ ba đều có hiệu lực ngay cả khi không nêu tên một cá nhân nào. Đây là lỗi nhận diện mà người làm chuyên môn thường mắc nhất.

### Bẫy trong kỳ thi: Trả lời bằng thời hạn lưu giữ hoặc mặc định huấn luyện đã ghi nhớ

Các thời hạn lưu giữ, thiết lập mặc định và ngày có hiệu lực là thông tin sản phẩm cần xét theo thời điểm; chúng đã thay đổi trong chính lịch sử tài liệu. Câu hỏi đánh giá hành vi chuyên nghiệp: kiểm tra tài liệu hiện hành cho sản phẩm và thỏa thuận của bạn. Hành vi đó không hết hạn.

## Tình huống thực hành

Điều phối viên của một chương trình đào tạo tài xế xe buýt nhỏ muốn dùng Claude để tìm hiểu vì sao tỷ lệ đậu giảm trong năm nay. Hồ sơ học viên có tên, số giấy phép lái xe, ngày sinh và khai báo về tình trạng đủ điều kiện sức khỏe. Chính sách dữ liệu của chương trình chỉ cho phép đưa thông tin cá nhân hoặc sức khỏe vào công cụ AI khi không thể hoàn thành công việc nếu thiếu những thông tin đó. Cách tiến hành nào phù hợp nhất?

**Lựa chọn A**  
Xóa thông tin nhận diện và khai báo sức khỏe khỏi hồ sơ, sau đó phân tích tỷ lệ đậu theo nhóm học viên, giảng viên và ngày học.

**Lựa chọn B**  
Tải nguyên hồ sơ lên vì phân tích này là rà soát nội bộ và kết quả sẽ được giữ trong chương trình.

**Lựa chọn C**  
Kết luận rằng hồ sơ học viên quá nhạy cảm để sử dụng với Claude và thực hiện phân tích năm nay trên giấy.

**Lựa chọn D**  
Tải hồ sơ lên kèm hướng dẫn bảo mật trong câu lệnh, rồi xóa cuộc trò chuyện sau khi phân tích xong.

## Bài tập thực hành

### Đi qua các nấc bảo vệ với một bộ dữ liệu thực tế

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách liệt kê các yếu tố nhạy cảm trong một tài liệu thực tế.
- Cách phân biệt điều câu hỏi cần với nội dung tài liệu đang có.
- Cách áp dụng loại bỏ và tổng hợp trước khi nghĩ đến việc chuyển cấp.
- Cách xác định lộ trình được phép hoặc người phụ trách khi một yếu tố thực sự không thể thiếu.

1. Chọn một tài liệu hoặc bộ dữ liệu thực tế mà bạn thực sự muốn được hỗ trợ, rồi liệt kê mọi yếu tố nhạy cảm: thông tin nhận diện, sức khỏe, tài chính, trẻ em, nghĩa vụ bảo mật, bí mật thương mại và tài liệu bên thứ ba được quản lý bằng hợp đồng.

   **Lý do:** Cần nhận biết trước khi chọn kỹ thuật; những nhóm thường bị bỏ sót chỉ lộ ra khi bạn chủ động tìm kiếm.  
   **Bạn sẽ thấy:** Danh sách các yếu tố nhạy cảm, mỗi yếu tố được gắn lý do nhạy cảm: nhận diện ai, thuộc quyền sở hữu của ai hoặc có cam kết nào về cách xử lý.

2. Viết câu hỏi thực tế mà công việc cần trả lời, rồi đánh dấu những yếu tố nhạy cảm mà câu hỏi thực sự cần đến.

   **Lý do:** Khoảng cách giữa nội dung tài liệu đang có và điều câu hỏi cần chính là nơi các nấc bảo vệ phát huy tác dụng.  
   **Bạn sẽ thấy:** Một câu mô tả câu hỏi và một danh sách ngắn hơn nhiều về các yếu tố thực sự cần thiết; thường sẽ ít hơn bạn nghĩ.

3. Áp dụng hai nấc đầu: loại bỏ nội dung câu hỏi không cần, rồi tổng hợp hoặc ẩn danh nội dung chỉ cần ở mức khái quát.

   **Lý do:** Chọn nấc thấp nhất đáp ứng yêu cầu là cách xử lý chuyên nghiệp và thường giúp bạn tiếp tục công việc ngay.  
   **Bạn sẽ thấy:** Phiên bản tài liệu đã chuẩn bị, trong đó thông tin nhận diện bị xóa và các yếu tố nhạy cảm còn lại được chuyển thành nhóm hoặc khoảng.

4. Nếu một yếu tố nhạy cảm thực sự không thể thiếu, hãy nêu lộ trình được phép nếu có, hoặc người sở hữu dữ liệu hay chính sách, rồi soạn yêu cầu ngắn gửi cho họ.

   **Lý do:** Chuyển cấp là một hành động, không phải từ chối; xác định đúng lộ trình hoặc người phụ trách giúp phân biệt nó với sự do dự mơ hồ.  
   **Bạn sẽ thấy:** Tên một workspace được phê duyệt và bao quát loại tài liệu này, hoặc yêu cầu hai câu gửi đến người phụ trách cụ thể.

5. Ghi lại biện pháp chỉ có tác dụng trên danh nghĩa mà bạn dễ muốn dùng nhất, rồi giải thích trong một câu vì sao nó không phải biện pháp kiểm soát.

   **Lý do:** Gọi tên biện pháp của chính mình giúp bạn tránh bị phương án gây nhiễu tương tự đánh lừa khi chịu áp lực trong kỳ thi.  
   **Bạn sẽ thấy:** Một câu bằng lời của bạn giải thích rằng biện pháp đó chỉ hoạt động sau khi thông tin đã bị tiết lộ.

## Nguồn

- How long do you store my data? — Anthropic
- Is my data used for model training? (consumer products) — Anthropic
- Is my data used for model training? (commercial products) — Anthropic
- How does Anthropic protect the personal data of Claude users? — Anthropic
- Usage Policy — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic. Thứ tự các nấc và nguyên tắc về biện pháp chỉ có tác dụng trên danh nghĩa đến từ phần giải thích Câu hỏi mẫu 3 trong hướng dẫn. Phần tham khảo nhanh của Miền 6 có các chi tiết hiện hành, kèm ngày cập nhật, về thời hạn lưu giữ và xóa dữ liệu.

**Luyện tập Miền này** · **Bài tập thực hành** · **Tham khảo nhanh** · **Thuật ngữ**  
**Bài học trước:** Xác định trường hợp sử dụng phù hợp và không phù hợp  
**Bài học tiếp theo:** Tuân theo chính sách AI và tiêu chuẩn quản trị của tổ chức
