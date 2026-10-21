# Tối ưu hóa quy trình làm việc để tăng hiệu suất và hiệu quả

**Nguồn:** https://claudecertificationguide.com/ccao-f/learn/7-troubleshooting-optimisation/7-3-optimising-workflows

**Miền:** 7  
**Nhiệm vụ:** 7.3

## Điều cần biết

Chi phí lặp lại (overhead) là bất cứ nội dung nào bạn phải gõ, giải thích hoặc đính kèm khi bắt đầu mỗi cuộc trò chuyện tương tự. Tối ưu hóa nghĩa là giảm thời gian hoặc mức sử dụng cần cho công việc với Claude. Việc đo lường sẽ tính thời gian của phần lặp lại và số lần nó tái diễn. Mục tiêu này nói về cách bạn làm việc với Claude, không phải quy trình kinh doanh xung quanh nó (Miền 4.2).

Một thợ lắp đặt bếp soạn báo giá khách hàng bằng Claude. Mỗi cuộc trò chuyện báo giá bắt đầu bằng phần giải thích cách doanh nghiệp hoạt động và tính giá công việc, cùng một bảng giá và danh mục sản phẩm như các lần trước. Khi bấm giờ, phần này mất khoảng mười phút, ba hoặc bốn lần mỗi tuần.

## Đo lường trước

Điểm khác nhau giữa tối ưu hóa và mày mò là một con số. Mười phút được đo lường là căn cứ để chuyển phần giới thiệu lặp lại đến nơi lưu trữ cố định. “Việc báo giá có vẻ rườm rà” mới chỉ là lý do để bấm giờ, chưa đủ để biện minh cho thay đổi nào. Đây là quy tắc trung thực ở mục 4.5 của Miền 4 áp dụng cho chính quy trình làm việc của bạn: cải thiện điều bạn đã quan sát và không tuyên bố tiết kiệm khoản thời gian chưa đo được.

## Kiểm tra phần lặp lại

Trong một cuộc trò chuyện, Claude nhớ ngữ cảnh từ các tin nhắn trước. Phần giới thiệu của người thợ lặp lại vì anh ấy gõ lại nó mỗi khi bắt đầu một cuộc trò chuyện báo giá mới. Nội dung lặp lại nên được lưu ở nơi chỉ cần tồn tại một lần.

- Ngữ cảnh và quy tắc cố định, chẳng hạn quy tắc định giá của anh ấy, nên đưa vào **chỉ dẫn của Project**. Anthropic mô tả đây là cách điều chỉnh phản hồi của Claude cho từng Project. Chúng phù hợp với công việc cần Claude duy trì ngữ cảnh nhất quán qua nhiều cuộc trò chuyện trong cùng Project.
- Tài liệu tham khảo thường dùng, chẳng hạn bảng giá, nên đưa vào **kiến thức của Project**, giúp Project trở thành một không gian làm việc độc lập.
- Một yêu cầu hầu như giống nhau mỗi tuần nên trở thành **biểu mẫu lưu sẵn** để điều chỉnh cho từng lần sử dụng.
- Tùy chọn áp dụng cho mọi việc bạn làm thuộc **cài đặt cá nhân hóa ở cấp tài khoản**, nơi chúng có hiệu lực trong mọi cuộc trò chuyện.

## Gộp các yêu cầu liên quan và đặt tên tệp rõ ràng

Có hai cách đã được tài liệu hóa giúp tiết kiệm thời gian.

**Thứ nhất, gộp yêu cầu (batching).** Hướng dẫn sử dụng của Anthropic khuyên nên nhóm nhiều nhiệm vụ hoặc câu hỏi có liên quan vào một tin nhắn thay vì chia thành nhiều lượt trao đổi. Tài liệu cũng khuyên nêu yêu cầu cụ thể và ngắn gọn, vì câu hỏi mơ hồ có thể khiến Claude phải yêu cầu làm rõ. Người thợ yêu cầu tạo báo giá và email gửi kèm trong cùng một tin nhắn. Bài viết của Anthropic về giới hạn sử dụng và độ dài bổ sung rằng những cuộc trò chuyện dài kích hoạt cơ chế quản lý ngữ cảnh tự động sẽ tiêu tốn nhiều hạn mức hơn. Vì vậy, để các cuộc trò chuyện công việc kéo dài lê thê vừa gây mất trật tự vừa tốn mức sử dụng.

**Thứ hai, đặt tên tệp.** Trong một Project lớn, khả năng truy xuất quyết định Claude dùng tài liệu nào. Anthropic nêu rằng tên tệp rõ ràng giúp Claude hiểu và truy xuất đúng thông tin; đồng thời nên gọi tên tài liệu cụ thể và nhóm các tài liệu liên quan trong cùng Project. Tệp tên “pl_v3_final” được đổi thành “Bảng giá mặt bàn bếp”. Đổi tên tệp sao cho người lạ cũng biết nội dung bên trong là một cách tối ưu hóa thực sự, với cơ chế tác động đã được tài liệu hóa.

## Chọn cài đặt phù hợp với công việc

Dùng một cài đặt cho mọi việc sẽ gây lãng phí theo cả hai hướng. Mức effort cao hơn tạo câu trả lời kỹ lưỡng hơn nhưng mất nhiều thời gian và dùng nhiều hạn mức hơn. Dùng mức effort tối đa để định dạng lại một nội dung thường ngày là trả phí cho chiều sâu không cần đến. Phân tích chuyên sâu mà dùng cài đặt thấp thì không đáp ứng được nhiệm vụ. Mẫu phản hồi chậm, làm quá mức cho công việc thường nhật, chẳng hạn định dạng lại báo giá, tự nó là số liệu cho thấy cài đặt không phù hợp.

## Quy tắc tương xứng

Không phải chi phí lặp lại nào cũng đáng loại bỏ. Một nhiệm vụ kéo dài hai mươi phút nhưng chỉ làm mỗi năm một lần không đáng để người thợ tạo Project, biểu mẫu lưu sẵn hay dành cả buổi chiều thiết lập. Phép tính không mang lại lợi ích, còn tài liệu phải bảo trì sẽ trở nên lỗi thời giữa các lần sử dụng. Nhận ra một giải pháp tối ưu hóa tốn nhiều hơn mức tiết kiệm được cũng chuyên nghiệp như nhận ra giải pháp có lợi.

## Trong kỳ thi

Phần lớn câu hỏi xoay quanh việc phương án trước mắt có con số đo lường hay không. Điều được kiểm tra là khả năng nhận biết, dựa trên triệu chứng hoặc số liệu đo, nơi cần đặt giải pháp tối ưu hóa; bao gồm việc xác định phần nào của nội dung mở đầu lặp lại thuộc cấp độ nào. Đôi khi, không tối ưu hóa ở đâu cả mới là lựa chọn đúng: trong các câu khó nhất của miền này, quyết định không tối ưu hóa dựa trên số liệu là đáp án đúng. Lựa chọn mô hình và mức effort thuộc quyết định ở mục 3.3 của Miền 3; viết cấu hình là công việc của Miền 5.

### Khái niệm then chốt

Trong tình huống ở mục 7.3, hãy tìm số liệu đo. Đáp án đúng chuyển phần lặp lại đã được đo lường đến nơi nó chỉ cần tồn tại một lần, hoặc từ chối việc thiết lập nếu chi phí cao hơn phần tiết kiệm. Phương án gây nhiễu tối ưu hóa thứ chưa được bấm giờ, chẳng hạn sắp xếp lại công việc chưa đo lường, hoặc tìm cách tối ưu hóa tất cả một cách vô điều kiện.

## Bẫy trong kỳ thi

### Bẫy: Đề xuất thay đổi toàn diện quy trình chỉ dựa trên cảm giác

Không có số đo thì không có mốc ban đầu, không có cách biết thay đổi có hiệu quả không, và không thể trung thực tuyên bố đã tiết kiệm được gì. Đáp án đúng bấm giờ công việc trước; việc sắp xếp lại có thể chờ đến khi có con số.

### Bẫy: Tạo Project hoặc biểu mẫu lưu sẵn cho nhiệm vụ chỉ làm hai lần một năm

Nếu chi phí thiết lập và bảo trì vượt quá phần lặp lại được loại bỏ thì đó là một khoản chi phí giả dạng cải tiến; tài liệu tạo ra sẽ lỗi thời giữa các lần dùng. Quy tắc tương xứng khuyên nên giữ nguyên nhiệm vụ hiếm gặp.

### Bẫy: Tăng effort hoặc đổi mô hình để tăng tốc quy trình có phần mở đầu lặp lại

Không cài đặt nào loại bỏ được mười phút gõ lại ngữ cảnh; phần này phải được đưa vào chỉ dẫn và kiến thức của Project hoặc tiếp tục được nhập lại. Effort cao hơn còn mất nhiều thời gian và dùng nhiều hạn mức hơn, khiến tối ưu hóa đi sai hướng.

## Tình huống thực hành

Nhân viên phụ trách phát triển của một trang trại đô thị luôn bắt đầu cuộc trò chuyện với nhà tài trợ bằng cách giải thích trang trại là gì và đang triển khai những chương trình nào, sau đó đính kèm cùng ba tài liệu. Bấm giờ cho thấy việc này mất khoảng mười phút, ba hoặc bốn lần mỗi tuần. Mỗi tháng Một, cô ấy cũng dành hai mươi phút chuẩn bị báo cáo thường niên của trang trại cho cơ quan quản lý từ thiện. Cô ấy chỉ muốn đầu tư công sức vào phần được đo lường là tốn thời gian, và chỉ khi khoản tiết kiệm lớn hơn chi phí thiết lập. Cách tối ưu hóa phù hợp nhất là gì?

- **Phương án A:** Tạo một Project dành cho việc xin tài trợ, đưa phần giới thiệu cố định vào chỉ dẫn, ba tài liệu vào kiến thức và lưu sẵn phiên bản yêu cầu thường dùng để điều chỉnh.
- **Phương án B:** Tăng mức effort cho các cuộc trò chuyện với nhà tài trợ để bản nháp đầy đủ hơn và cần ít vòng chỉnh sửa hơn.
- **Phương án C:** Tạo Projects và biểu mẫu yêu cầu lưu sẵn cho mọi nhiệm vụ lặp lại ở bất kỳ khoảng thời gian nào, kể cả báo cáo thường niên tháng Một, để không việc thường xuyên nào phải bắt đầu từ một cuộc trò chuyện trống.
- **Phương án D:** Tổ chức lại toàn bộ tuần làm việc quanh Claude trước, rồi đo thời gian sau để xem các thay đổi tiết kiệm được bao nhiêu.

## Bài tập thực hành

### Đo phần lặp lại, rồi lưu đúng chỗ hoặc giữ nguyên

**Độ khó:** 30 phút, chia đều trong một tuần

**Bạn sẽ học được**

- Cách đo lường trung thực phần lặp lại.
- Cách đặt từng phần lặp lại ở cấp độ chỉ cần có một lần.
- Cách dùng tên tệp làm đòn bẩy cho việc truy xuất.
- Cách áp dụng quy tắc tương xứng và quyết định không tối ưu hóa.

1. Trong một tuần, ghi lại những gì bạn gõ, giải thích hoặc đính kèm khi bắt đầu mỗi cuộc trò chuyện Claude tương tự, rồi đo thời gian một cách trung thực.
   - **Vì sao:** Tối ưu hóa bắt đầu từ phép đo; ghi chép trong một tuần biến cảm giác rườm rà thành số liệu có thể hành động.
   - **Bạn cần có:** Danh sách ngắn các mục lặp lại, mỗi mục có thời gian ước tính và tần suất tái diễn.
2. Áp dụng phép thử phần lặp lại cho từng mục: ngữ cảnh cố định thuộc chỉ dẫn của Project; tài liệu tham khảo thường dùng thuộc phần kiến thức; yêu cầu hằng tuần gần như giống nhau thuộc biểu mẫu lưu sẵn để điều chỉnh.
   - **Vì sao:** Mỗi loại chi phí lặp lại có một nơi chỉ cần tồn tại một lần; đặt sai chỗ có thể khiến bạn vẫn phải nhập lại hoặc khiến nội dung không áp dụng được.
   - **Bạn cần có:** Mỗi mục được ghi nơi lưu trữ: chỉ dẫn, kiến thức, biểu mẫu lưu sẵn hoặc tùy chọn cấp tài khoản.
3. Kiểm tra tên các tệp đã có trong Projects; đổi tên mọi tệp mà người lạ không thể nhận ra nội dung chỉ từ tên tệp.
   - **Vì sao:** Truy xuất quyết định Claude dùng tài liệu nào trong Project lớn; tên tệp rõ ràng là một yếu tố đã được tài liệu hóa để lấy đúng tài liệu.
   - **Bạn cần có:** Tên tệp thể hiện nội dung của từng tài liệu, thay cho phiên bản, chữ viết tắt và biệt hiệu chỉ bạn hiểu.
4. Tìm một nhiệm vụ lặp lại có cài đặt chưa phù hợp: công việc thường ngày ở mức effort tối đa hoặc phân tích chuyên sâu ở mức thấp; điều chỉnh cài đặt cho phù hợp với công việc.
   - **Vì sao:** Cài đặt không phù hợp gây lãng phí thời gian và mức sử dụng theo một hướng, đồng thời ảnh hưởng chất lượng theo hướng khác; phản hồi thường nhật bị làm quá mức cũng là một phép đo.
   - **Bạn cần có:** Một nhiệm vụ được chuyển sang cài đặt phù hợp, kèm ghi chú về thay đổi tốc độ hoặc độ sâu.
5. Chọn nhiệm vụ lặp lại hiếm nhất và tính theo quy tắc tương xứng: nếu thiết lập tốn nhiều hơn thời gian lặp lại tiết kiệm được trong một năm, hãy giữ nguyên và ghi lại quyết định.
   - **Vì sao:** Từ chối tối ưu hóa dựa trên số liệu là kỷ luật giúp phân biệt tối ưu hóa chuyên nghiệp với việc dùng công cụ chỉ vì thích.
   - **Bạn cần có:** Một dòng ghi lại nhiệm vụ, phép tính và quyết định có chủ ý không tối ưu hóa nó.

## Nguồn

- **What are projects?** — Anthropic
- **Understanding Claude's personalization features** — Anthropic
- **Usage limit best practices** — Anthropic
- **How do usage and length limits work?** — Anthropic
- **Retrieval augmented generation (RAG) for projects** — Anthropic
- **Change the model, effort, and thinking settings** — Anthropic
- **Claude Certified Associate – Foundations Exam Guide** — Anthropic. Quy tắc đo lường trước và tương xứng dựa trên mục tiêu trong đề cương kỳ thi và thực tiễn thông thường. Các cách gộp yêu cầu, đặt tên tệp, sử dụng chỉ dẫn và cài đặt đến từ những bài viết Help Center nêu trên.

**Luyện tập miền này · Bài tập thực hành · Tham khảo nhanh · Bảng thuật ngữ**  
**Bài học trước:** Điều chỉnh cách tiếp cận dựa trên phản hồi và kết quả
