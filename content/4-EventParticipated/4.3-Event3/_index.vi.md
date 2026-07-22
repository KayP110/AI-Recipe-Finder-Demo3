---
title: "Event 3"
date: 2026-07-07
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Bài thu hoạch “TRẬN CHUNG KẾT CLOUD ARCHITECT” 

### Mục Đích Của Sự Kiện 

-   Tổ chức vòng thi chung kết của giải đấu Cloud Architect, tạo sân chơi cọ xát kiến thức thực tế về thiết kế và vận hành hạ tầng AWS cho sinh viên. 
-   Cung cấp các phiên chia sẻ kỹ thuật chuyên sâu (Tech Sharing) từ các kỹ sư và chuyên gia xoay quanh chứng chỉ AWS Cloud Practitioner, tự động hóa bảo mật với AI (DevSecOps) và quản trị rủi ro hệ thống (Monitoring & SLA). 

### Danh Sách Diễn Giả 

-   **Thinh Nguyen** - DevOps/DevSecOps/Cloud Engineer, Styl Solutions 
-   **Ngo Le Tan Huy** - Presenter về AWS Cloud Practitioner Roadmap 
-   **Nguyen Huynh Son** - Freshly graduated from HUFLIT / Member of AWS Student Builder Group / Ex-Infrastructure Reliability Engineer at SPS 

### Nội Dung Nổi Bật 

#### Trận chung kết Cloud Architect kịch tính:
Trận đấu diễn ra giữa hai đội KLKAT và Ngũ Đại Hiệp. Mở đầu là sự giằng co điểm số sát sao. Điều thú vị chưa từng có trong lịch sử giải đấu là cả hai đội đều bị điểm âm ở phần giữa. Về cuối, đội Ngũ Đại Hiệp quyết định đánh liều chọn "Ngôi sao hy vọng" nhưng trả lời sai, khiến điểm âm càng lùi sâu. Nhờ vậy, đội KLKAT đã giành chiến thắng chung cuộc mà không cần trả lời câu hỏi cuối, trở thành đội đầu tiên vô địch với mức điểm âm. 

#### Tự động hóa Pentest bằng AWS Security Agent:
Diễn giả Thịnh Nguyễn từ Styl Solutions mang đến một góc nhìn mới về DevSecOps.
- Chỉ ra những nút thắt của Pentest truyền thống: Tốn thời gian, đắt đỏ ($5k - $20k), và phụ thuộc vào trình độ của người test.
- Giới thiệu "Frontier Agent" chạy trên nền tảng Amazon Bedrock. Đây là một agent tự trị có khả năng đọc hiểu tài liệu thiết kế (Markdown/Terraform), tự động review code tìm lỗ hổng bảo mật, và chủ động rà quét, tự tấn công (Pentest) vào hệ thống đang chạy để kiểm chứng lỗi. Dù có chi phí khoảng $50/Task-Hour nhưng so với việc thuê đội Pentest chuyên nghiệp ($10,000) thì đây vẫn là một lựa chọn cực kỳ tối ưu. 

#### Chiến lược chinh phục chứng chỉ AWS Cloud Practitioner (CLF-C02):
Diễn giả Ngô Lê Tấn Huy đã hệ thống hóa lộ trình ôn thi chứng chỉ nền tảng của AWS.
- Bài thi dài 90 phút (thêm 30 phút cho người không nói tiếng Anh bản xứ), cấu trúc gồm 4 phần: Cloud Concepts (24%), Security and Compliance (30%), Cloud Technology and Services (34%), và Billing/Pricing (12%).
- Chia sẻ các "mẹo" thi thực chiến: Học theo phương pháp "Keyword Thinking" gắn dịch vụ với Use-case (ví dụ: "Decouple" chọn SQS), luyện thói quen phân tích kỹ các câu trả lời sai khi làm Mock Test, và sử dụng phương pháp loại trừ (loại bỏ các dịch vụ không tồn tại). 



#### SLA & Monitoring - Khoảng cách giữa hạ tầng và trải nghiệm người dùng:
Diễn giả Nguyễn Huỳnh Sơn trình bày về tư duy giám sát hệ thống (Monitoring) đúng nghĩa.
- SLA (Service Level Agreement) rất quan trọng để đặt kỳ vọng, quy trách nhiệm và quản trị rủi ro.
- Chỉ ra sai lầm kinh điển: "Hạ tầng xanh (mọi chỉ số CPU, RAM đều tốt) không đồng nghĩa với trải nghiệm người dùng tốt". Ví dụ: Dù EC2 hay ALB chạy ổn định, nhưng nếu kết nối DB bị lỗi thì người dùng vẫn không thể Login.
- Chuyển đổi góc nhìn theo Monitoring Pyramid: Thay vì chỉ nhìn từ dưới lên (Hạ tầng -> Ứng dụng), kỹ sư cần giám sát từ trên xuống, đo lường các chỉ số của Business (như tỷ lệ Login thành công, số lượng đơn hàng) để thực sự nắm bắt được cảm nhận của người dùng. 

### Những Gì Học Được 

- **Xu hướng DevSecOps:** Thấy rõ tương lai của ngành bảo mật khi AI Agent (đại diện bởi Bedrock) có thể tự động hóa toàn bộ vòng đời Security (từ Design Review đến Pentest). Tuy nhiên, cũng cần hiểu giới hạn của AI Agent như không vượt qua được MFA/Biometrics hay khó phát hiện các lỗ hổng logic nghiệp vụ phức tạp.

- **Tư duy chứng chỉ & Thực hành:** Chứng chỉ không chỉ là tờ giấy mà là quá trình tư duy logic theo Framework của AWS. Không nên học vẹt mà cần thực hành trực tiếp trên AWS Free Tier và phân tích sâu sắc các lựa chọn trong câu hỏi. 
 
- **Mindset "Plan for failure":** Như câu nói của Dr. Werner Vogels "Everything fails all the time", kỹ sư cần xây dựng hệ thống giám sát dựa trên hành vi của người dùng (Customer Journey) thay vì chỉ chăm chăm nhìn vào chỉ số phần cứng. 

### Trải nghiệm trong sự kiện 

- **Giao lưu và học hỏi:** Trải nghiệm xem trực tiếp trận chung kết Cloud Architect rất hồi hộp và mang lại nhiều bài học thú vị về chiến thuật thi đấu cũng như sự bình tĩnh trước áp lực. 
- **Cập nhật góc nhìn thực chiến:** Các diễn giả đều là những người trẻ tài năng nhưng đã có kinh nghiệm thực chiến sâu sắc, giúp em hiểu rõ hơn khoảng cách giữa việc cấu hình một hệ thống cho "chạy được" và việc xây dựng một hệ thống "an toàn, tối ưu chi phí, và tập trung vào trải nghiệm người dùng". 

#### Một số hình ảnh chứng minh tham gia sự kiện: 

![Event 3](/images/4-Event/Event3_1.jpg)
![Event 3](/images/4-Event/Event3_2.jpg)