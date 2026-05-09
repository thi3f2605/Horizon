---
layout: default
title: "Horizon Summary: 2026-05-09 (VI)"
date: 2026-05-09
lang: vi
---

> From 542 items, 2 important content pieces were selected

---

1. [Khung AI tự động kiểm toán giao dịch quy mô lớn](#item-1) ⭐️ 7.0/10
2. [Resume Tailor: Tối ưu CV theo nghề nghiệp bằng RAG đa nguồn và theo dõi nguồn gốc](#item-2) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Khung AI tự động kiểm toán giao dịch quy mô lớn](https://arxiv.org/abs/2605.05252) ⭐️ 7.0/10

Một khung giải pháp mới sử dụng Snowflake Document AI để trích xuất dữ liệu có cấu trúc từ các bản sao kê PDF phi cấu trúc chỉ với khoảng 20 tài liệu gán nhãn, cho phép kiểm toán toàn bộ dân số thay vì lấy mẫu. Khung giải pháp này cải thiện đáng kể phạm vi và hiệu quả kiểm toán, chuyển từ kiểm tra mẫu sang kiểm tra toàn bộ, rất quan trọng cho đảm bảo liên tục trong dịch vụ tài chính. Tại Việt Nam, có thể đóng gói thành SaaS cho các công ty kiểm toán, giúp xử lý khối lượng lớn chứng từ PDF và đối chiếu số liệu nội bộ. Khung giải pháp chỉ cần khoảng 20 tài liệu gán nhãn để huấn luyện, sử dụng Snowflake Document AI để trích xuất, và đối chiếu dữ liệu với nguồn tin cậy thông qua bảng điều khiển tương tác và báo cáo tự động.

rss · ArXiv cs.AI · May 8, 04:00

**Background**: Kiểm toán giao dịch truyền thống dựa vào xem xét thủ công một mẫu các bản sao kê PDF, tốn nhiều nhân lực và không thể mở rộng cho hàng triệu giao dịch. Khung giải pháp này tận dụng các tiến bộ gần đây trong AI tài liệu để tự động hóa trích xuất và đối chiếu, cho phép xác định rủi ro gần như thời gian thực.

**Tags**: `#audit`, `#document-ai`, `#pdf-extraction`, `#snowflake`, `#automation`

---

<a id="item-2"></a>
## [Resume Tailor: Tối ưu CV theo nghề nghiệp bằng RAG đa nguồn và theo dõi nguồn gốc](https://arxiv.org/abs/2605.05257) ⭐️ 7.0/10

Các nhà nghiên cứu giới thiệu Resume Tailor, một hệ thống tác tử sử dụng sinh tăng cường truy xuất đa nguồn (RAG) và kho lưu trữ sự nghiệp dọc theo thời gian để tùy chỉnh CV theo từng mô tả công việc, kèm theo dõi nguồn gốc và biện pháp chống ảo giác. Hệ thống này giải quyết vấn đề đau đầu cho người tìm việc và công nghệ nhân sự: tạo CV tùy chỉnh hiệu quả. Tại Việt Nam, nơi nhu cầu tối ưu CV đang tăng nhưng ít giải pháp nội địa, hệ thống này có thể đóng gói thành SaaS cho ứng viên và công ty tuyển dụng. Hệ thống được triển khai dưới dạng pipeline LangGraph 12 nút với chấm điểm độ tin cậy lai ngữ nghĩa-từ vựng và vòng lặp xem xét có điều kiện. Trong thử nghiệm với chín mô tả công việc, kích hoạt kho lưu trữ sự nghiệp cải thiện điểm ATS trung bình 7,8 điểm cho các vai trò phù hợp, nhưng giảm 8,0 điểm cho các vai trò thiếu liên quan lĩnh vực.

rss · ArXiv cs.AI · May 8, 04:00

**Background**: Các công cụ tối ưu CV truyền thống thường chỉ dựa trên một CV tải lên duy nhất, hạn chế khả năng khôi phục kinh nghiệm bị bỏ sót và khó phân biệt chỉnh sửa có căn cứ với gợi ý AI. Resume Tailor giải quyết điều này bằng cách duy trì kho lưu trữ sự nghiệp gồm CV lịch sử và hồ sơ có cấu trúc, sử dụng RAG đa nguồn để tạo nội dung phù hợp với công việc.

**Tags**: `#resume tailoring`, `#rag`, `#career management`, `#hr tech`, `#langgraph`

---