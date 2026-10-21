# Tạo hướng dẫn hiệu quả ở cấp hệ thống

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/5-configuration-knowledge/5-3-system-level-instructions

**Miền:** 5  
**Nhiệm vụ:** 5.3

## Những điều bạn cần biết

Trong chứng chỉ này, hướng dẫn ở cấp hệ thống (system-level instructions) là các quy tắc thường trực do một người viết bằng tiếng Anh thông thường. Chúng nằm ở một trong ba nơi: phần cài đặt claude.ai, một Project hoặc, với quản trị viên, phần cài đặt của tổ chức. Không có lớp kỹ thuật nào bên dưới các hướng dẫn này.

Quản lý văn phòng tại một công ty khóa nhỏ dùng Claude để viết email cho khách hàng, báo giá cho chủ nhà và hướng dẫn về an ninh nhà ở. Một số quy tắc là của riêng cô, một số dành cho báo giá, một số áp dụng cho mọi người trong công ty, còn một số chỉ đúng trong tuần này. Có hai lựa chọn quyết định các quy tắc đó có hiệu quả hay không: đặt từng quy tắc ở đâu và diễn đạt như thế nào.

### Ba cấp độ, ba phạm vi áp dụng

Mỗi cấp độ có một người phụ trách và phạm vi áp dụng riêng; cả ba đều được tài liệu mô tả.

**Cấp tài khoản.**  
Phần cài đặt claude.ai có một ô tên **Instructions for Claude** (Hướng dẫn cho Claude). Bất cứ điều gì ghi ở đó đều áp dụng cho mọi cuộc trò chuyện của bạn. Nội dung được gợi ý là những điều mang tính cá nhân và áp dụng xuyên suốt, chẳng hạn cách tiếp cận bạn ưa thích, thuật ngữ thường dùng và sở thích giao tiếp chung.

**Cấp Project.**  
Hướng dẫn được xác định cho một Project chỉ điều chỉnh phản hồi của Claude trong các cuộc trò chuyện thuộc Project đó.

**Cấp tổ chức.**  
Trong các gói Team và Enterprise, Owner và Primary Owner có thể đặt hướng dẫn cho tổ chức. Claude tuân theo chúng trong mọi cuộc trò chuyện trên toàn tổ chức.

Khi các cấp độ trùng lặp, hướng dẫn của tổ chức được ưu tiên. Hướng dẫn cá nhân vẫn áp dụng cho những điều mà hướng dẫn của tổ chức không đề cập. Quy tắc của Owner về cách ký email sẽ được ưu tiên hơn quy tắc của chính cô. Quy tắc chính tả của cô vẫn áp dụng vì tổ chức không đặt quy tắc nào về chính tả.

Điểm thực tế nằm ở vai trò, không phải cách vận hành. Thành viên thông thường không đặt hướng dẫn cho tổ chức. Vì vậy, nếu một quy tắc cần ràng buộc toàn tổ chức, hãy yêu cầu người quản trị workspace thêm quy tắc đó. Nếu cô muốn bản nháp của mọi đồng nghiệp đều không đưa địa chỉ nhà của khách hàng vào, cô cần đề nghị Owner thêm quy tắc.

### Câu hỏi về vị trí đặt

Hãy xác định quy tắc đúng với phạm vi nào. Một quy tắc áp dụng cho mọi cuộc trò chuyện ở cấp độ của nó, vì vậy phạm vi của quy tắc và cấp độ phải khớp nhau.

- Đúng với bạn trong mọi công việc — chẳng hạn ngôn ngữ, ưu tiên phần tóm tắt trước, hoặc mặc định viết cho độc giả phổ thông — thì đặt ở **cấp tài khoản**.
- Đúng với một loại công việc, đối tượng độc giả, quy ước định dạng hoặc quy tắc thường trực của công việc đó — thì đặt trong **hướng dẫn của Project** tương ứng.
- Đúng với mọi người trong tổ chức — thì đặt ở **cấp tổ chức**, thông qua yêu cầu gửi Owner của workspace.
- Chỉ đúng với công việc hôm nay — thì không phải hướng dẫn ở cấp nào cả, mà là một phần của **câu lệnh hôm nay**.

Quy tắc chính tả Anh-Anh và ưu tiên phần tóm tắt trước đúng với mọi công việc của cô, nên được đặt ở cấp tài khoản. “Hiển thị phí gọi thợ thành một dòng riêng” đúng với Project báo giá cho chủ nhà. Mức tăng giá của tuần này thuộc các câu lệnh trong tuần này.

Đặt sai vị trí gây tốn kém theo cả hai hướng. Đưa một quy tắc của Project lên cấp tài khoản sẽ làm thay đổi mọi cuộc trò chuyện không liên quan. Quy tắc về phí gọi thợ sẽ xuất hiện cả trong hướng dẫn an ninh. Ngược lại, giữ một quy tắc áp dụng mọi nơi ở cấp Project sẽ buộc bạn sao chép và duy trì nó trong từng Project cần đến. Quy tắc chính tả của cô sẽ phải được sao chép vào mọi Project.

### Mô tả hành vi, không phải khát vọng

Một hướng dẫn hữu ích có thể kiểm tra được: ai đó có thể nhận biết hướng dẫn đã được tuân theo hay chưa. “Giữ mỗi mục dưới chín mươi giây khi đọc thành tiếng” có thể được thực hiện và cũng có thể không đạt. “Hãy hấp dẫn” không thể được thực hiện theo cách nào khác với cách công việc vốn đã diễn ra. Câu này không nêu hành vi cụ thể, nên không có gì để kiểm tra.

Hãy dùng phép thử sau cho từng dòng: một đồng nghiệp mới có thể làm theo điều này và tạo ra kết quả bạn mong muốn không? Nếu không, đó mới là hy vọng chứ chưa phải hướng dẫn. “Nghe đáng tin cậy” không đạt phép thử khi viết báo giá cho cô. “Đưa giá và phí gọi thợ vào hai dòng đầu tiên” thì đạt. Những lời khát vọng còn làm bộ hướng dẫn chật chội và tạo cảm giác bao quát một cách giả tạo.

### Bộ hướng dẫn ngắn, có thứ tự ưu tiên tốt hơn bộ dài và toàn diện

Hướng dẫn thường trực áp dụng cho mọi cuộc trò chuyện trong phạm vi của chúng, vì vậy chỉ nên chứa những điều luôn đúng. Một quy tắc chỉ đúng với một công việc sẽ làm sai lệch các công việc khác. Bộ quy tắc gom chi tiết của từng nhiệm vụ sẽ không còn mô tả công việc nói chung, mà chỉ phản ánh nhiệm vụ gần nhất. Đưa ghi chú tăng giá vào Project báo giá sẽ khiến mọi báo giá sau này nhắc đến mức tăng đó cho đến khi ai đó xóa đi.

Độ dài cũng có tác động tương tự. Bộ hướng dẫn ngắn, có thứ tự ưu tiên thường được tuân theo đáng tin cậy hơn bộ dài và toàn diện. Khi mọi thứ đều là quy tắc, các quy tắc cạnh tranh với nhau và những quy tắc bị lấn át có thể không phải là những quy tắc bạn muốn bỏ qua. Khi bộ hướng dẫn đã dài đến mức đồng nghiệp không thể ghi nhớ, hãy nhóm và sắp thứ tự ưu tiên. Thêm một quy tắc nữa không giải quyết được vấn đề. Project báo giá của cô có thể nhóm quy tắc theo giá, cách diễn đạt và bố cục, trong đó giá được đặt trước.

Styles (Kiểu) là một thiết lập riêng, dùng để định dạng và trình bày phản hồi (xem ghi chú bên dưới). Theo đó, Styles không phải nơi để đặt các quy tắc về nội dung.

### Trong kỳ thi

Mục tiêu này kiểm tra hai nhận định: cấp độ mà quy tắc áp dụng và cách diễn đạt sao cho có thể kiểm tra. Điểm về vai trò giống với Miền 4, nơi cần chuyển yêu cầu lên đúng người thay vì tự ý tìm cách xử lý. Ranh giới giữa hướng dẫn thường trực và câu lệnh hôm nay là ranh giới rõ nhất với Miền 1. Lời khát vọng là phương án gây nhiễu đặc trưng của mục tiêu này, vì “bảo Claude viết rõ ràng và chuyên nghiệp” luôn nghe có vẻ hợp lý.

### Khái niệm chính

Hai câu hỏi giúp giải quyết gần như mọi câu trong mục tiêu này:

1. Quy tắc này đúng với phạm vi nào? Câu trả lời quyết định cấp độ.
2. Một đồng nghiệp mới có thể làm theo quy tắc và được đánh giá dựa trên quy tắc đó không? Câu trả lời quyết định cách diễn đạt.

Đáp án chuẩn đáp ứng cả hai; mỗi phương án gây nhiễu trượt đúng một tiêu chí.

### Ghi chú về Styles

Help Center chỉ đề cập Styles trong một so sánh về định dạng, nên nhận định rằng Styles không dành cho nội dung là cách diễn giải của chúng tôi, không phải tuyên bố được tài liệu xác nhận. **Hiện trạng (kiểm tra ngày 30 tháng 9 năm 2026):** bài viết về tính năng cá nhân hóa không còn nhắc đến Styles, và phần so sánh định dạng gọi Skills là công cụ để tùy chỉnh cách Claude định dạng và trình bày phản hồi.

## Những bẫy trong kỳ thi

### Bẫy trong kỳ thi: Khát vọng được ngụy trang thành hướng dẫn — hãy chuyên nghiệp, kỹ lưỡng, tạo ra sản phẩm chất lượng cao

Không thể tuân theo lời khát vọng theo cách khác với mặc định, và cũng không thể xác định khi nào chúng bị vi phạm. Vì vậy, chúng không thay đổi điều gì nhưng lại chiếm chỗ của các quy tắc thực sự hữu ích. Đáp án chuẩn nêu hành vi có thể kiểm tra; lựa chọn mang tính khát vọng là đáp án sai đặc trưng của mục tiêu này.

### Bẫy trong kỳ thi: Đưa yêu cầu của tuần này vào hướng dẫn thường trực

Hướng dẫn thường trực áp dụng cho mọi cuộc trò chuyện trong phạm vi của nó. Quy tắc chỉ đúng với một công việc sẽ làm sai lệch mọi công việc khác cho đến khi ai đó nhớ xóa nó. Quy tắc đó thuộc câu lệnh của công việc, đúng tại ranh giới với Miền 1.

### Bẫy trong kỳ thi: Đặt quy tắc của một Project ở cấp tài khoản, hoặc tự đặt quy tắc cho toàn tổ chức

Quy tắc cấp tài khoản làm thay đổi mọi cuộc trò chuyện không liên quan; hướng dẫn cấp tổ chức do Owner và Primary Owner đặt trong các gói Team và Enterprise. Khi cần có một quy tắc áp dụng toàn tổ chức, động thái đúng của Associate là đề nghị quản trị viên workspace, không tự đặt nó trong cài đặt cá nhân.

## Tình huống thực hành

Một biên tập viên tài liệu dễ đọc tại tổ chức từ thiện hỗ trợ người khuyết tật học tập đang viết hướng dẫn cho Project tạo bản tóm tắt tài liệu dễ đọc dành cho hội viên. Mỗi dòng hướng dẫn phải còn đúng cả với những tài liệu được tạo ra nhiều năm sau. Bộ hướng dẫn nào sẽ giúp một tình nguyện viên kiểm tra đầu ra?

**Lựa chọn A**  
Dùng quy tắc về độ dài câu và từ ngữ thông dụng, đồng thời luôn ghi thời hạn khảo sát hội viên hiện tại vì thông tin này quan trọng với hội viên lúc này.

**Lựa chọn B**  
Luôn rõ ràng, tôn trọng và dễ tiếp cận; luôn tạo tài liệu dễ đọc chất lượng cao mà hội viên của tổ chức từ thiện thấy thực sự hữu ích.

**Lựa chọn C**  
Giữ mỗi câu dưới mười lăm từ và chỉ diễn đạt một ý; dùng từ ngữ thông dụng; giải thích từ khó trong ngoặc ở lần đầu tiên xuất hiện; kết thúc mỗi bản tóm tắt bằng việc nêu người đọc có thể làm gì tiếp theo.

**Lựa chọn D**  
Đặt quy tắc về độ dài câu và từ ngữ thông dụng trong **Instructions for Claude** ở cấp tài khoản thay vì trong Project, để mọi cuộc trò chuyện của cô đều tuân theo quy tắc viết dễ đọc.

## Bài tập thực hành

### Thử thách bộ hướng dẫn thực tế và đặt từng quy tắc đúng cấp độ

**Thời lượng:** 30 phút

**Bạn sẽ học được**

- Cách viết lại lời khát vọng thành hành vi có thể kiểm tra.
- Cách đặt từng quy tắc ở cấp độ mà nó thực sự áp dụng.
- Cách chuyển quy tắc toàn tổ chức qua quản trị viên workspace.
- Cách rút gọn bộ hướng dẫn đến mức đồng nghiệp có thể ghi nhớ.

1. Lấy hướng dẫn từ một Project bạn sử dụng, hoặc soạn bộ hướng dẫn cho Project đã tạo trong bài tập 5.1.

   **Lý do:** Bài tập cần một bộ hướng dẫn thực tế với những thiếu sót thực tế; ví dụ tự nghĩ ra thường khiến phép thử có vẻ dễ hơn.  
   **Bạn sẽ thấy:** Toàn bộ bộ hướng dẫn trước mắt, mỗi quy tắc nằm trên một dòng.

2. Áp dụng phép thử “đồng nghiệp mới” cho từng dòng: ai đó có thể làm theo và tạo ra điều bạn muốn không? Viết lại mỗi lời khát vọng thành hành vi mà bạn thực sự kiểm tra, rồi xóa các dòng chỉ nhắc lại điều mặc định.

   **Lý do:** Khả năng kiểm tra là điều phân biệt hướng dẫn với hy vọng; nhắc lại mặc định làm bộ hướng dẫn dài hơn mà không thay đổi điều gì.  
   **Bạn sẽ thấy:** Bộ hướng dẫn mà mỗi dòng còn lại đều mô tả điều có thể quan sát thấy đã được thực hiện hay chưa.

3. Đánh dấu từng dòng còn lại: đúng với công việc này mọi lần, đúng với bạn ở mọi nơi, hay chỉ đúng với một nhiệm vụ gần đây. Chuyển quy tắc áp dụng ở mọi nơi sang cài đặt **Instructions for Claude** ở cấp tài khoản, và chuyển các dòng chỉ đúng cho một nhiệm vụ về câu lệnh của nhiệm vụ đó.

   **Lý do:** Đặt đúng vị trí là một nửa mục tiêu: mỗi quy tắc thuộc cấp độ tương ứng với phạm vi của nó; đặt sai sẽ gây tốn kém theo cả hai hướng.  
   **Bạn sẽ thấy:** Mỗi dòng được gắn nhãn cấp độ, và ít nhất một dòng đã được đưa ra khỏi bộ hướng dẫn của Project.

4. Nếu có quy tắc cần áp dụng cho toàn tổ chức, hãy viết yêu cầu một câu gửi cho người quản trị workspace thay vì cố tự đặt quy tắc đó.

   **Lý do:** Owner và Primary Owner là người đặt hướng dẫn tổ chức, vì vậy đóng góp chuyên nghiệp là một yêu cầu được diễn đạt rõ ràng.  
   **Bạn sẽ thấy:** Một câu nêu quy tắc và lý do quy tắc đó nên áp dụng cho mọi cuộc trò chuyện trong tổ chức.

5. Nếu bộ hướng dẫn còn lại dài hơn mức đồng nghiệp có thể ghi nhớ, hãy nhóm chúng dưới ba hoặc bốn tiêu đề và đặt quy tắc quan trọng nhất lên trước.

   **Lý do:** Khi mọi thứ đều là quy tắc, các quy tắc sẽ cạnh tranh với nhau. Nhóm và sắp thứ tự ưu tiên giúp quyết định quy tắc nào được ưu tiên một cách có chủ đích, thay vì tình cờ.  
   **Bạn sẽ thấy:** Một bộ hướng dẫn ngắn, được nhóm và sắp xếp, với các quy tắc quan trọng nhất ở đầu.

## Nguồn

- Understanding Claude's personalization features — Anthropic
- Set organization instructions — Anthropic
- What are projects? — Anthropic
- How can I create and manage projects? — Anthropic
- Claude Certified Associate – Foundations Exam Guide — Anthropic

**Luyện tập Miền này** · **Bài tập thực hành** · **Tham khảo nhanh** · **Thuật ngữ**  
**Bài học trước:** Quản lý kiến thức đã tải lên và trình kết nối  
**Bài học tiếp theo:** Cung cấp thông tin, duy trì và cập nhật cấu hình
