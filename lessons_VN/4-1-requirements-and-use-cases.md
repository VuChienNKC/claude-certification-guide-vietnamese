# Phân tích yêu cầu và trường hợp sử dụng

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-1-requirements-and-use-cases

**Miền:** 4

**Nhiệm vụ:** 4.1

## Những điều bạn cần biết

Yêu cầu là một tuyên bố về điều mà một công việc cần đạt được. Phân tích trường hợp sử dụng là đánh giá xem một nhiệm vụ có phù hợp để giao cho Claude trước khi bỏ công sức vào đó hay không. Chủ đề (theme) là một nhóm bình luận có liên quan được đặt tên. Mục tiêu này kiểm tra hai kỹ năng liên quan: dùng Claude để chuyển đầu vào lộn xộn thành các yêu cầu có cấu trúc, và phân tích trường hợp sử dụng. Mọi quyết định về quy trình trong miền này đều bắt đầu từ hai câu hỏi: công việc này cần đạt được điều gì, và có nên để Claude tham gia hay không? Cả hai cùng dựa trên một nguyên tắc phân công: Claude sắp xếp thông tin; con người xác thực và chịu trách nhiệm về kết quả.

Hãy hình dung một cửa hàng báo có dịch vụ giao báo tận nhà. Chủ cửa hàng muốn sắp xếp lại các tuyến giao báo. Tài liệu của chị gồm email khách hàng, ghi chú họp nhân viên, bình luận trong sổ đặt hàng và nhận xét của khách tại quầy.

## Sắp xếp thông tin lộn xộn

Yêu cầu thực tế thường xuất hiện trong các chuỗi khiếu nại, ghi chú cuộc họp, bình luận khảo sát và những cuộc trò chuyện được nhớ mang máng, chứ không bao giờ thành một danh sách gọn gàng. Help Center liệt kê việc tóm tắt tài liệu dài và cuộc trò chuyện dài trong số những công dụng cốt lõi của Claude, cùng với việc tạo góc nhìn và đưa ra đề xuất. Từ tài liệu thô, Claude có thể nhóm nội dung thành các chủ đề và phân biệt điều mọi người nói rằng họ muốn với điều có vẻ họ thực sự cần. Claude cũng nêu ra nơi hai nhóm muốn những điều không tương thích và chỉ ra điều chưa ai đề cập.

Với cửa hàng báo, Claude có thể đưa ra các chủ đề như báo giao trễ và tạp chí bị giao nhầm. Claude có thể phát hiện một khu dân cư muốn nhận báo trước bảy giờ, trong khi nhân viên muốn bắt đầu muộn hơn. Việc đọc tài liệu vốn mất cả buổi chiều nay chỉ còn mất vài phút; những người liên quan có được một cách trình bày vấn đề rõ ràng để xem xét và phản biện.

## Chủ đề chỉ là một giả thuyết

Claude sắp xếp những gì được cung cấp. Claude không thể biết tổ chức của bạn cần gì. Chủ đề do Claude nêu ra là giả thuyết về đầu vào, không phải phát hiện đã được xác thực về doanh nghiệp của bạn. Những người có yêu cầu được mô tả phải xác nhận chủ đề trước khi thiết kế bất cứ thứ gì dựa trên đó. Khung AI Fluency của Anthropic cũng chỉ ra sự phân chia công việc tương tự. Hai yếu tố **Discernment** (đánh giá nội dung AI tạo ra) và **Diligence** (chịu trách nhiệm về kết quả) thuộc về con người.

Vì thế, chủ cửa hàng xác nhận mâu thuẫn về việc giao báo sớm với khách hàng trong khu dân cư và nhân viên trước khi vẽ lại bất kỳ tuyến giao nào. Thiết kế ngay từ các nhóm chủ đề của Claude sẽ nhầm đầu ra gọn gàng với yêu cầu đã được xác thực. Xác nhận là bước ít tốn kém.

## Đặc điểm của trường hợp sử dụng phù hợp

Các trường hợp sử dụng Claude tốt có một dạng dễ nhận biết:

- Công việc liên quan đến ngôn ngữ: soạn thảo, tóm tắt, định dạng lại, giải thích, so sánh. Đây là phạm vi được bài viết về các trường hợp sử dụng trong Help Center ghi nhận.
- Tài liệu cần thiết là tài liệu bạn có thể cung cấp.
- Có người đủ năng lực để kiểm tra đầu ra.
- Hoặc khối lượng công việc lớn, hoặc việc bắt đầu từ trang giấy trắng rất tốn kém.

AI Fluency gọi phán đoán này là **Delegation** (ủy thác): quyết định nên giao công việc nào cho AI. Khung này xem Delegation là kỹ năng riêng, có trước khi viết bất kỳ prompt nào. Trường hợp không phù hợp có đặc điểm ngược lại: công việc cần thẩm quyền ra quyết định chứ không phải khả năng soạn thảo; hoặc phụ thuộc vào thông tin Claude không thể truy cập; hoặc thiên về quan hệ giữa người với người thay vì xử lý tài liệu.

Ở cửa hàng báo, viết thư thông báo giờ giao báo mới là trường hợp phù hợp: chủ cửa hàng có thể kiểm tra. Quyết định ai phụ trách tuyến giao nào cần có thẩm quyền. Biết một tờ báo đã được giao đến trước cửa nhà hay chưa đòi hỏi thông tin Claude không có. Gọi cho một khách quen đã hủy dịch vụ là công việc duy trì quan hệ khách hàng.

## Bài kiểm tra người rà soát

Đây là bước mọi người thường bỏ qua: nếu bạn không thể nhận ra câu trả lời sai, thì bạn chưa sẵn sàng dùng Claude cho nhiệm vụ đó. Khi không có người rà soát, đầu ra sai cũng dễ được chấp nhận như đầu ra đúng. Công việc có hệ quả quan trọng không phải lý do để từ bỏ nó; thiếu người rà soát cũng vậy. Cả hai đều có nghĩa là cần tìm người có thể phân biệt đầu ra tốt với đầu ra kém và đưa họ vào quy trình.

Bài kiểm tra này cũng vạch rõ vấn đề của việc ủy thác không giới hạn: tuyên bố rằng Claude sẽ xử lý trọn một loại công việc. Một loại công việc có thể bao gồm cả trường hợp phù hợp lẫn không phù hợp. Cam kết giao toàn bộ được đưa ra trước bước phân tích vốn phải là cơ sở cho cam kết đó. Giao toàn bộ công việc quản lý giao báo cho Claude sẽ gộp cả viết thư thông báo với phân công tuyến giao.

## Trong kỳ thi

Sai lầm được đề thi ưa dùng nhất ở đây là bỏ qua bước xác nhận. Công việc có phù hợp với Claude không và phù hợp ở khâu nào là câu hỏi của mục tiêu này. Cách diễn đạt yêu cầu sau đó là kỹ năng của Miền 1; lựa chọn tính năng sản phẩm để thực hiện là nội dung của Miền 3.

## Khái niệm chính

Khi câu hỏi thuộc mục 4.1 kết thúc bằng các chủ đề Claude vừa nhóm xong, đáp án đúng sẽ đưa chúng trở lại với những người chịu trách nhiệm về các yêu cầu trước khi bắt đầu thiết kế. Các đáp án đánh lạc hướng sẽ coi chủ đề là phát hiện đã được xác nhận, giao luôn quyết định cho Claude, hoặc từ bỏ công việc vì công việc có vẻ quá hệ trọng.

## Bẫy trong kỳ thi

### Bẫy: Coi chủ đề của Claude là phát hiện đã được xác thực vì chúng xuất hiện nhanh và nghe hợp lý

Chủ đề là giả thuyết về đầu vào, không phải phát hiện đã được xác thực về doanh nghiệp. Thiết kế dựa trên một mâu thuẫn chưa được xác nhận sẽ khiến bạn tự tin xây sai thứ cần xây. Vì vậy, đáp án đúng đưa cấu trúc đó trở lại với các bên liên quan trước; xác nhận là bước ít tốn kém, còn bỏ qua nó mới tốn kém.

### Bẫy: Giao luôn quyết định cho Claude cùng với phần phân tích

Không thể ủy thác thẩm quyền ra quyết định. Claude sắp xếp tài liệu và soạn nội dung xoay quanh quyết định, nhưng việc chọn chính sách, chọn phương án thắng cuộc hoặc giải quyết tranh chấp vẫn thuộc về những người chịu trách nhiệm. Các lựa chọn giao phán đoán cho Claude đều sai, dù nghe có vẻ hiệu quả đến đâu.

### Bẫy: Loại bỏ công việc vì nó quá quan trọng để Claude tham gia

Cách từ chối này đánh đồng mức độ hệ trọng của công việc với rủi ro khi dùng Claude. Công việc có hệ quả quan trọng là lý do để đưa vào quy trình một người rà soát có chuyên môn được chỉ định, chứ không phải từ bỏ sự hỗ trợ soạn thảo. Giải pháp là dùng bài kiểm tra người rà soát; đề thi xem việc từ chối toàn diện là đáp án sai, cũng như việc áp dụng toàn diện.

## Tình huống thực hành

Người quản lý một khu chợ đường phố họp vào thứ Bảy có một thư mục email khiếu nại và bình luận của người bán về cách phân chia vị trí bán hàng. Chị muốn xác định một phương án phân bổ công bằng hơn cần đáp ứng điều gì trước khi bất kỳ ai thiết kế phương án. Claude nhóm tài liệu thành sáu chủ đề, bao gồm một mâu thuẫn: người bán thường xuyên cho rằng người bán không thường xuyên được các vị trí góc đẹp nhất, còn người bán không thường xuyên lại nói rằng chính các vị trí đó được dành riêng cho người bán thường xuyên. Chị không có thời gian tự đọc lại toàn bộ thư mục. Chị nên làm gì tiếp theo?

### Lựa chọn

- **A.** Coi các chủ đề là giả thuyết về đầu vào và đưa chúng trở lại cho người bán xác nhận, bắt đầu với mâu thuẫn, trước khi thiết kế bất cứ điều gì.
- **B.** Gác thư mục sang một bên và tự đọc lại từng email vì việc phân bổ vị trí quá dễ gây tranh cãi để Claude tham gia.
- **C.** Giao toàn bộ vấn đề phân bổ cho Claude: cung cấp sơ đồ vị trí và danh sách người bán, rồi yêu cầu Claude tạo ra cách phân bổ công bằng nhất cho mùa tiếp theo.
- **D.** Chấp nhận sáu chủ đề làm tài liệu yêu cầu vì chúng xuất phát trực tiếp từ lời người bán, rồi chuyển sang thiết kế phương án phân bổ mới.

## Bài tập thực hành

### Nhóm chủ đề, xác nhận rồi phân loại

**Độ khó:** Cơ bản (1/4)

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách yêu cầu Claude sắp xếp đầu vào thực sự lộn xộn.
- Cách coi chủ đề là giả thuyết và xác nhận với những người liên quan.
- Cách phân loại công việc có phù hợp với Claude hay không.
- Cách áp dụng bài kiểm tra người rà soát trước khi cam kết dùng một trường hợp cụ thể.

**Thu thập một đầu vào thực sự lộn xộn thuộc quyền của bạn: một chuỗi phản hồi, ghi chú từ ba cuộc họp nhóm gần đây hoặc thư mục khiếu nại về một quy trình.**

- **Tại sao:** Kỹ năng này chỉ thể hiện rõ khi xử lý tài liệu thật sự lộn xộn; đầu vào gọn gàng sẽ che khuất chính phần sắp xếp mà mục tiêu này kiểm tra.
- **Bạn cần thấy:** Một tập tài liệu thô duy nhất, chưa chỉnh sửa, trong một tài liệu hoặc cuộc trò chuyện.

**Yêu cầu Claude nhóm tài liệu thành các chủ đề, đánh dấu nơi hai người muốn những điều không tương thích và nêu điều chưa ai đề cập.**

- **Tại sao:** Ba yêu cầu này bao quát những điểm khó thấy nhất trong tài liệu: mẫu hình, mâu thuẫn và khoảng trống.
- **Bạn cần thấy:** Một nhóm các chủ đề có tên, ít nhất một điểm xung đột được đánh dấu và một hoặc hai khoảng trống.

**Đánh dấu từng chủ đề là đã xác nhận hoặc còn là giả thuyết, rồi mang hai giả thuyết có ảnh hưởng lớn nhất đến các bước tiếp theo trở lại với những người phụ trách chúng và ghi lại điều gì thay đổi.**

- **Tại sao:** Đây là nguyên tắc đề thi kiểm tra: chủ đề vẫn là giả thuyết về đầu vào cho đến khi những người liên quan xác nhận.
- **Bạn cần thấy:** Ít nhất một chủ đề được sửa đổi hoặc diễn đạt lại sau một cuộc trao đổi thực tế.

**Liệt kê những công việc mà các yêu cầu đã xác nhận đặt ra và phân loại chúng: công việc ngôn ngữ có tài liệu bạn cung cấp được, hoặc công việc phụ thuộc vào thẩm quyền, quyền truy cập hay quan hệ giữa người với người.**

- **Tại sao:** Phân tích trường hợp sử dụng diễn ra theo từng công việc, không phải theo cả một loại công việc; phân loại giúp nhìn thấy các trường hợp phù hợp và không phù hợp.
- **Bạn cần thấy:** Hai danh sách, mỗi công việc chỉ nằm trong đúng một danh sách.

**Với từng công việc bạn định giao cho Claude, hãy nêu tên người có thể phân biệt đầu ra sai với đầu ra đúng; nếu chưa có tên ai thì trường hợp sử dụng đó chưa sẵn sàng.**

- **Tại sao:** Bài kiểm tra người rà soát là bộ lọc sắc bén nhất trong mục tiêu này, và việc nêu đích danh một người giúp bảo đảm yêu cầu rà soát được thực hiện nghiêm túc.
- **Bạn cần thấy:** Tên người rà soát bên cạnh mỗi công việc giao cho Claude, hoặc ghi chú về người cần mời tham gia vai trò rà soát.

## Nguồn

- [What are some things I can use Claude for?](https://support.claude.com/en/articles/7996845-what-are-some-things-i-can-use-claude-for) — Anthropic
- [AI Fluency: Framework and Foundations](https://www.anthropic.com/learn/claude-for-you) — Anthropic *(tên các yếu tố là tên mô-đun của khóa học; phần diễn giải mỗi yếu tố bằng một mệnh đề là nội dung diễn đạt lại của chúng tôi từ nội dung khóa học)*
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic *(hướng dẫn kỳ thi; các nhận định về thực hành chuyên nghiệp là đánh giá của chúng tôi, không phải hướng dẫn của Anthropic)*

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=4) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/4-workflow-integration) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-4) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-4)

**Bài trước:** [Quản lý giới hạn ngữ cảnh và bộ nhớ: bắt đầu lại, tóm tắt, lưu giữ](https://claudecertificationguide.com/ccao-f/learn/3-product-model-selection/3-4-context-and-memory-management)

**Bài tiếp theo:** [Dùng Claude cho nghiên cứu, lập kế hoạch và tối ưu hóa quy trình](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-2-research-planning-optimisation)
