# Cấu hình Project với chỉ dẫn và nguồn kiến thức

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-1-project-instructions-knowledge

**Miền:** 5

**Nhiệm vụ:** 5.1

## Những điều bạn cần biết

## Hai vùng chứa, hai nhiệm vụ

Help Center của Anthropic mô tả Project là một không gian làm việc độc lập, có lịch sử trò chuyện và cơ sở kiến thức riêng. Project có hai phần có thể cấu hình, được tài liệu hóa riêng vì chúng thực hiện hai nhiệm vụ khác nhau. **Chỉ dẫn tùy chỉnh (custom instructions)** là nơi bạn đặt cách Claude nên thực hiện công việc và trả lời. Chúng điều chỉnh phản hồi của Claude, chẳng hạn yêu cầu giọng văn trang trọng hơn hoặc trả lời theo góc nhìn của một vai trò hay ngành cụ thể. **Kiến thức của Project (project knowledge)** là tài liệu Claude làm việc dựa trên đó. Bạn tải các tài liệu, văn bản và tệp có liên quan lên cơ sở kiến thức. Claude sử dụng chúng để hiểu bối cảnh và thông tin nền của các cuộc trò chuyện trong Project. Chỉ dẫn trả lời câu hỏi “nên thực hiện công việc này như thế nào?”, còn kiến thức trả lời “nên dựa vào tài liệu nào để thực hiện?”.

Hãy hình dung một công ty vệ sinh cửa sổ, nơi quản lý hàng tuần viết báo giá và thư nhắc. Mỗi lần, cô yêu cầu Claude viết bằng ngôn ngữ đơn giản dành cho chủ nhà và ghi ngày đến vệ sinh cửa sổ lần tiếp theo. Mỗi lần, cô đính kèm bảng giá, điều khoản dịch vụ và các câu trả lời mẫu tốt trước đây. Cả hai phần đều là thao tác thiết lập thông thường trên màn hình Project: viết và lưu chỉ dẫn, rồi dùng nút thêm để tải tệp kiến thức lên.

## Phép thử phân loại vùng chứa

Thiết lập Project tốt phụ thuộc vào một quyết định phân loại, áp dụng cho từng nội dung. Đây là quy tắc về cách thực hiện công việc hay tài liệu cần tham khảo? Với công ty vệ sinh cửa sổ, “viết cho chủ nhà bằng ngôn ngữ đơn giản” là quy tắc về cách thực hiện công việc, nên thuộc phần chỉ dẫn. Bảng giá là tài liệu tham khảo, nên thuộc phần kiến thức.

Phép thử này quan trọng vì mỗi vùng chứa có đặc tính mà vùng kia không có. Claude áp dụng chỉ dẫn cho mọi cuộc trò chuyện trong Project. Claude tham khảo kiến thức khi công việc cần đến. Có thể thay một tệp kiến thức trong một bước khi tài liệu được cập nhật. Nếu dán chính sách vào phần chỉ dẫn, bạn phải tự tìm và xóa nội dung đó bằng tay.

## Hai lỗi đặt nhầm vùng chứa

Lỗi thứ nhất là dán tài liệu tham khảo vào chỉ dẫn, thường được biện minh là làm thật đầy đủ: đưa toàn bộ chính sách vào nơi Claude không thể bỏ sót. Các quy tắc hành vi sẽ bị chìm trong phần nội dung được dán. Khi chính sách được sửa đổi, văn bản cũ mắc kẹt ở nơi không thể thay thế gọn gàng. Nếu dán điều khoản dịch vụ của công ty vào phần chỉ dẫn, hai quy tắc hành vi của công ty sẽ nằm giữa hàng trang điều khoản.

Lỗi thứ hai là trường hợp ngược lại: chôn quy tắc trong cơ sở kiến thức. Tải hướng dẫn phong cách của công ty dưới dạng tài liệu có nghĩa là bạn đưa tài liệu về hành vi, chứ không phải chỉ dẫn. Không có gì cho biết tài liệu đó chi phối mọi câu trả lời, nên nó chỉ được áp dụng khi Project tình cờ tham khảo. Nếu tải hướng dẫn phong cách của công ty vệ sinh cửa sổ lên phần kiến thức, quy tắc chỉ được áp dụng đôi lúc. “Đôi lúc” không phải là tiêu chuẩn. Quy tắc mà công việc luôn phụ thuộc vào phải nằm trong chỉ dẫn, được viết thành một yêu cầu về hành vi.

## Xây dựng thiết lập từ công việc bạn đã làm

Phương pháp này không đòi hỏi phân tích lại từ đầu, vì người đang tự làm công việc đã có sẵn cả hai danh sách. Bất cứ điều gì bạn phải giải thích lại ở đầu mỗi cuộc trò chuyện đều thuộc bộ chỉ dẫn: đối tượng, giọng văn, định dạng, quy tắc áp dụng thường xuyên. Bất cứ thứ gì bạn đính kèm lại đều thuộc cơ sở kiến thức: chính sách, mẫu biểu và ví dụ cũ. Ở công ty vệ sinh cửa sổ, hai quy tắc trở thành chỉ dẫn và ba tệp trở thành kiến thức. Hãy viết danh sách thứ nhất thành các yêu cầu về hành vi và tải danh sách thứ hai lên dưới dạng tệp. Sau đó, thực hiện công việc thực tế tiếp theo chỉ với prompt ngắn nêu nhiệm vụ và ghi lại điều gì bạn không còn phải nhắc đến.

## Trong kỳ thi

Mục tiêu này bắt đầu sau khi đã quyết định dùng Project và kiểm tra cách thiết lập Project hiệu quả. Việc một công việc có nên dùng Project hay không là phán đoán thuộc Miền 3. Vị trí của Project trong quy trình lớn hơn thuộc Miền 4. Hầu hết câu hỏi ở đây đều đặt phép thử phân loại vùng chứa vào một tình huống, vì vậy hãy luyện đến khi phản xạ trở nên tự động. Cả hai lỗi đặt nhầm vùng chứa thường gặp trong thiết lập thực tế và là các phương án gây nhiễu dễ khiến người làm bài mắc bẫy. Vì câu hỏi bắt đầu sau khi đã đưa ra quyết định đó, “dùng Project” không bao giờ là đáp án đúng ở đây. Phương án quay lại tranh luận quyết định đó đã lạc sang Miền 3.

### Khái niệm chính

Khi câu hỏi đưa ra các phương án thiết lập khác nhau, hãy áp dụng phép thử phân loại vùng chứa cho từng nội dung được nêu. Đáp án đúng đưa quy tắc hành vi vào chỉ dẫn và tài liệu vào phần kiến thức. Phương án gây nhiễu đưa ít nhất một nội dung vào sai vùng, thường được ngụy trang thành việc làm đầy đủ hoặc gọn gàng.

## Bẫy trong kỳ thi

### Bẫy: Dán tài liệu tham khảo vào chỉ dẫn tùy chỉnh để Claude không thể bỏ sót

Các quy tắc hành vi bị chìm trong phần tài liệu được dán; khi tài liệu được sửa đổi, văn bản cũ bị mắc kẹt trong chỉ dẫn thay vì có thể thay mới dễ dàng như một tệp trong phần kiến thức. Phương án gây nhiễu này thường được ngụy trang dưới danh nghĩa làm cho đầy đủ.

### Bẫy: Tải quy tắc áp dụng thường xuyên lên thành tài liệu kiến thức và mong nó chi phối mọi câu trả lời

Kiến thức là tài liệu Claude tham khảo, không phải quy tắc hành vi áp dụng thường xuyên. Nếu một quy tắc phải được tuân thủ mọi lúc, quy tắc ấy chỉ được áp dụng đôi lúc trừ khi được viết trong chỉ dẫn — đó chính là nhiệm vụ của phần chỉ dẫn.

### Bẫy: Bỏ qua Project, rồi giải thích lại và đính kèm lại mọi thứ trong từng cuộc trò chuyện, với lý do muốn thông tin luôn cập nhật

Để giữ thông tin mới nhất, hãy thay tệp kiến thức khi tài liệu nguồn thay đổi. Cách làm trong từng cuộc trò chuyện lại tạo ra chính phần công việc lặp lại mà Project giúp loại bỏ, đồng thời phụ thuộc vào việc từng người dùng phải nhớ thực hiện.

## Tình huống thực hành

Thư ký của một hội người thuê nhà và cư dân đã quyết định hồ sơ xử lý vụ việc trong khu nhà và tài liệu họp hàng tháng sẽ nằm trong một Project, và hiện đang thiết lập Project đó. Có hai nội dung: chính sách sửa chữa của hội và quy tắc yêu cầu mỗi lá thư phải nêu tên người phụ trách cùng ngày vấn đề cần sửa chữa được báo cáo. Mỗi nội dung nên được đưa vào đâu?

**Phương án A**

Tải chính sách sửa chữa lên phần kiến thức của Project và viết quy tắc ghi tên người phụ trách cùng ngày báo cáo vào phần chỉ dẫn tùy chỉnh.

**Phương án B**

Dán chính sách sửa chữa vào chỉ dẫn tùy chỉnh để Claude không bao giờ bỏ sót, đồng thời tải một ghi chú hướng dẫn ngắn có nhắc đến quy tắc về người phụ trách lên phần kiến thức của Project.

**Phương án C**

Tải cả chính sách sửa chữa và tài liệu nêu quy tắc về người phụ trách lên làm tệp kiến thức, để trống chỉ dẫn tùy chỉnh nhằm giữ cho Project linh hoạt.

**Phương án D**

Không đưa nội dung nào vào Project; thay vào đó, đính kèm lại chính sách và nhắc lại quy tắc ở đầu mỗi cuộc trò chuyện mới vì tài liệu được dán mới luôn là phiên bản cập nhật nhất.

## Bài tập thực hành

### Phân loại một tháng công việc thủ công vào hai vùng chứa

**Độ khó:** Cơ bản (1/4)

**Thời lượng:** 25 phút

**Bạn sẽ học được**

- Cách nhận diện bộ chỉ dẫn ẩn trong những gì bạn giải thích lại ở mỗi cuộc trò chuyện.
- Cách nhận diện cơ sở kiến thức ẩn trong những gì bạn đính kèm lại.
- Cách áp dụng phép thử phân loại vùng chứa cho các nội dung chưa rõ ràng.
- Cách xác nhận thiết lập có hiệu quả bằng những điều bạn không còn phải nói.

1. **Chọn một công việc định kỳ hiện bạn thực hiện trong các cuộc trò chuyện thông thường:** công việc mà mỗi lần bạn đều giải thích lại bối cảnh và đính kèm lại tệp.

   **Vì sao:** Hai danh sách Project cần đã tồn tại trong thói quen thủ công của bạn; công việc định kỳ giúp làm rõ chúng.

   **Bạn cần thấy:** Một dòng nêu tên công việc và tần suất lặp lại.

2. **Dựa vào trí nhớ về một vài cuộc trò chuyện gần đây, lập hai danh sách:** mọi thứ bạn giải thích lại, chẳng hạn đối tượng, giọng văn, định dạng và quy tắc áp dụng thường xuyên; cùng mọi thứ bạn đính kèm lại, chẳng hạn chính sách, mẫu biểu, ví dụ và dữ liệu.

   **Vì sao:** Danh sách những điều phải giải thích lại là bộ chỉ dẫn; danh sách những gì đính kèm lại là cơ sở kiến thức. Chính hành vi của bạn đã phân loại chúng.

   **Bạn cần thấy:** Hai danh sách bằng văn bản, một về hành vi và một về tài liệu.

3. **Tạo Project, viết danh sách thứ nhất vào phần chỉ dẫn tùy chỉnh theo cách diễn đạt thành yêu cầu về hành vi, rồi tải danh sách thứ hai lên làm kiến thức của Project.**

   **Vì sao:** Diễn đạt chỉ dẫn thành hành vi giúp kiểm tra được; tải tài liệu thực tế tốt hơn là chỉ mô tả chúng.

   **Bạn cần thấy:** Bộ chỉ dẫn đã lưu và cơ sở kiến thức có tài liệu trong màn hình Project.

4. **Áp dụng phép thử phân loại cho từng nội dung còn mơ hồ:** đây là quy tắc về hành vi hay tài liệu cần tham khảo? Di chuyển mọi nội dung đang nằm sai phần.

   **Vì sao:** Nội dung mơ hồ là nơi các thiết lập thực tế thường sai; phép thử giúp giải quyết từng nội dung.

   **Bạn cần thấy:** Ít nhất một nội dung đã được chuyển, hoặc ghi chú rằng mọi nội dung đều được phân loại đúng.

5. **Thực hiện công việc thực tế tiếp theo trong Project bằng một prompt ngắn chỉ nêu nhiệm vụ, rồi ghi lại điều gì bạn không còn phải nói.**

   **Vì sao:** Bằng chứng về thiết lập tốt là prompt ngày càng ngắn; bất cứ điều gì bạn vẫn phải giải thích đều thuộc một trong hai vùng chứa.

   **Bạn cần thấy:** Đầu ra đầu tiên có chất lượng tương đương thường lệ, với prompt chỉ dài bằng một phần nhỏ.

## Nguồn

- [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects) — Anthropic
- [How can I create and manage projects?](https://support.claude.com/en/articles/9519177-how-can-i-create-and-manage-projects) — Anthropic
- [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work) — Anthropic
- [Claude Certified Associate – Foundations Exam Guide](https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification) — Anthropic

[Luyện tập Miền này](https://claudecertificationguide.com/ccao-f/drill?domain=5) · [Bài tập thực hành](https://claudecertificationguide.com/ccao-f/exercises/5-configuration-knowledge) · [Tham khảo nhanh](https://claudecertificationguide.com/ccao-f/quick-reference/domain-5) · [Bảng thuật ngữ](https://claudecertificationguide.com/ccao-f/glossary/domain-5)

**Bài học trước:** [Truyền đạt giá trị và giới hạn cho các bên liên quan](https://claudecertificationguide.com/ccao-f/learn/4-workflow-integration/4-5-communicating-value-limitations)

**Bài học tiếp theo:** [Quản lý kiến thức đã tải lên và connectors](https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-2-uploads-and-connectors)
