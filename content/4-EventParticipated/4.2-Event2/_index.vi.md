---
title: "Event 2"
date: 2026-07-07
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch “FCAJ COMMUNITY DAY - DATA DRIVEN, AI RISEN”

### Mục Đích Của Sự Kiện

-   Cung cấp góc nhìn thực tế về làn sóng AI đang định hình tương lai của các doanh nghiệp.
-   Hướng dẫn cách tích hợp các giải pháp hiện đại như AI đàm thoại (Voice AI), tự động hóa DevOps, và AI trong tuyển dụng (HR).
-   Chia sẻ phương pháp bảo mật kết nối nội bộ khi triển khai các hệ thống AI Agents (qua giao thức MCP) trên đám mây AWS.

### Danh Sách Diễn Giả

-   **Steve Tran** - CTO/Founder, CloudThinker
-   **Trung Vu** - CEO, Revve AI
-   **Nghi Danh** - AI Engineer, Renova Cloud
-   **Kiet Tran** - AI Engineer, AWS Student Builder Group
-   **Bao Phan & Nguyen Nguyen** - Cloud Engineers, Cloud Kinetics
-   **Truong Tran & Anh Dang** - AI Solution Sales, Noventiq
-   **Toan Nguyen** - AWS Security Builder

### Nội Dung Nổi Bật

#### Sự dịch chuyển định hướng nghề nghiệp:
Các doanh nghiệp đang ngừng tuyển dụng những vị trí cơ bản và thay bằng AI hoặc các nhân sự Senior có khả năng vận hành AI xuất sắc. Việc tích lũy kinh nghiệm trong môi trường doanh nghiệp thực tế càng sớm càng tốt là điều bắt buộc cho sinh viên IT.

#### DevOps Automation & Cloud Infrastructure:
Giới thiệu công cụ DevOps Agent giúp các kỹ sư điều tra nguyên nhân sự cố (Root Cause Analysis), giảm thời gian từ hàng giờ xuống còn vài phút bằng cách tự học topology hệ thống và kết xuất dữ liệu qua giao thức bảo mật. Tuy nhiên, AI chỉ đề xuất, con người vẫn là chốt chặn cuối cùng thực thi quyết định.

#### Giải pháp Voice AI cho tiếng Việt:
Giải quyết bài toán thiếu hụt nguồn dữ liệu tiếng Việt (Low-resource language). Thay vì dùng mô hình Speech-to-Speech truyền thống, các chuyên gia giới thiệu mô hình tách biệt 3 phần: Speech-to-Text -> LLM xử lý logic -> Text-to-Speech. Cách này giúp doanh nghiệp kiểm soát chặt chẽ nội dung AI phát ngôn, nhận diện giới tính/vùng miền, và tích hợp Tool Calling hiệu quả.

#### Ứng dụng AI trong Nhân sự (HR):
Giải quyết vấn đề thiên kiến cá nhân và thất thoát ứng viên giỏi. Sử dụng Amazon Q kết nối thẳng với các nền tảng công sở để quét hàng loạt CV, tạo JD tự động, so sánh năng lực ứng viên và báo cáo lương dự kiến mà không bị giới hạn số lượng token xử lý.

#### Bảo mật kết nối MCP Private:
Để Amazon Q kết nối với database nội bộ mà không đưa dữ liệu ra Public Internet, mô hình đề xuất đặt MCP Server trong Private Subnet của VPC, đi qua VPC Endpoints và mã hóa chứng chỉ qua AWS Certificate Manager (ACM), đảm bảo tuân thủ bảo mật tuyệt đối.

### Bài học & Trải nghiệm thực tế

#### Trải nghiệm thực tế:
Được tận mắt xem các bản demo trực tiếp cực kỳ ấn tượng, từ Voice Agent trả lời thông tin MacBook qua tổng đài, DevOps AI tự động tìm ra lỗi hệ thống do bị DDoS chỉ trong chốc lát, cho đến Amazon Q phân tích trực tiếp CV và chấm điểm ứng viên.

#### Bài học rút ra:
-   AI không cướp việc của con người, nhưng người biết dùng AI sẽ thay thế người không biết.
-   Xây dựng AI Agent cho doanh nghiệp thì bảo mật là số 1. Các luồng dữ liệu (Data Pipeline) phải được thiết lập theo chuẩn mã hóa, đặc biệt là khi tương tác qua Model Context Protocol (MCP) nội bộ.
-   Cần kết hợp kiến trúc Multi-Agent thay vì Single Agent cho các hệ thống phức tạp để giảm "ảo giác", tối ưu Contact Window và dễ dàng phân quyền (Role-Based Access Control).

### Ứng dụng vào công việc 

-   **Nâng cấp Backend cho dự án:** Ứng dụng mô hình VPC Connection và Private MCP Server được chia sẻ trong sự kiện để đảm bảo các yêu cầu gọi API từ hệ thống gợi ý món ăn vào Database (lưu trữ thông tin dị ứng/sở thích của khách hàng) hoàn toàn kín và không bị rò rỉ ra ngoài Internet.
-   **Kiểm thử và vận hành tự động:** Triển khai thử nghiệm các bộ công cụ DevOps AI Agent để tự động phân tích log mỗi khi ứng dụng báo lỗi (ví dụ lỗi không load được hình ảnh món ăn), từ đó giảm thời gian xử lý sự cố.
-   **Ứng dụng Voice AI (Gợi ý thêm):** Tương lai có thể tích hợp mô hình Voice AI (chuyển đổi Giọng nói -> Văn bản -> LLM tìm công thức -> Văn bản -> Giọng nói) vào AI Recipe Finder, giúp người dùng vừa nấu ăn vừa hỏi/đáp công thức với trợ lý ảo hoàn toàn bằng tiếng Việt mà không cần chạm tay vào màn hình.

#### Một số hình ảnh chứng minh tham gia sự kiện:

![Event 2](/images/4-Event/Event2_1.jpg)
![Event 2](/images/4-Event/Event2_3.jpg)