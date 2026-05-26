---
layout: default
title: "Horizon Summary: 2026-05-26 (VI)"
date: 2026-05-26
lang: vi
---

> From 778 items, 2 important content pieces were selected

---

1. [Quy trình mã nguồn mở tạo avatar biết nói từ slide giảng dạy](#item-1) ⭐️ 7.0/10
2. [Chuỗi Bằng Chứng: Gán nhãn trực quan cấp pixel cho iRAG](#item-2) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Quy trình mã nguồn mở tạo avatar biết nói từ slide giảng dạy](https://arxiv.org/abs/2604.23703) ⭐️ 7.0/10

Các nhà nghiên cứu đã công bố quy trình mã nguồn mở kết hợp OpenVoice để tổng hợp giọng nói và Ditto-TalkingHead để tạo hình ảnh biết nói từ âm thanh, cho phép giảng viên biến kịch bản và ảnh chân dung thành video thuyết minh cho slide. Quy trình này giải quyết vấn đề thiếu sự hiện diện của giảng viên trong dạy học trực tuyến và kết hợp, cung cấp giải pháp tái sử dụng, ít tốn công sức thay thế cho video bài giảng đầy đủ. Tại Việt Nam, nó có thể giúp sản xuất nội dung giảng dạy số với chi phí thấp, đặc biệt cho các startup EdTech và trường đại học muốn mở rộng khóa học trực tuyến. Quy trình sử dụng OpenVoice để nhân bản giọng nói và Ditto-TalkingHead để tạo avatar khớp môi. Nó được thiết kế cho các đoạn ngắn như giới thiệu và tóm tắt, không phải bài giảng đầy đủ, và kèm theo hướng dẫn đạo đức về sự đồng ý và minh bạch.

rss · ArXiv cs.AI · May 26, 04:00

**Background**: Giảng dạy dựa trên slide phổ biến trong giáo dục đại học, nhưng các hình thức trực tuyến thường mất đi khung cảnh biểu cảm của giảng viên. Video bài giảng đầy đủ khôi phục sự hiện diện nhưng tốn thời gian sản xuất. Quy trình mã nguồn mở này nhằm thu hẹp khoảng cách đó bằng cách tạo avatar biết nói từ slide, kết hợp công nghệ tổng hợp giọng nói và tạo hình ảnh.

**Tags**: `#edtech`, `#avatar`, `#text-to-speech`, `#open-source`, `#slide`

---

<a id="item-2"></a>
## [Chuỗi Bằng Chứng: Gán nhãn trực quan cấp pixel cho iRAG](https://arxiv.org/abs/2605.01284) ⭐️ 7.0/10

Các nhà nghiên cứu giới thiệu Chuỗi Bằng Chứng (CoE), một khung gán nhãn trực quan không phụ thuộc bộ truy xuất, sử dụng Mô hình Ngôn ngữ-Thị giác để lý luận trực tiếp trên ảnh chụp tài liệu được truy xuất, xuất ra các hộp giới hạn chính xác cho bằng chứng. CoE giải quyết hai nút thắt quan trọng trong hệ thống iRAG hiện tại: gán nhãn thô và mất mát ngữ nghĩa thị giác, cho phép khả năng diễn giải cấp pixel cho các câu hỏi đa bước phức tạp trên tài liệu giàu hình ảnh như slide và PDF, rất phù hợp với nhu cầu xử lý tài liệu văn phòng tại Việt Nam. CoE được đánh giá trên hai chuẩn: Wiki-CoE (từ 2WikiMultiHopQA) và SlideVQA, sử dụng Qwen3-VL-8B-Instruct tinh chỉnh, vượt trội so với các baseline dựa trên văn bản trong hiểu bố cục trực quan.

rss · ArXiv cs.AI · May 26, 04:00

**Background**: Truy xuất Tăng cường Sinh lặp (iRAG) trả lời câu hỏi đa bước bằng cách truy xuất và lý luận dần trên tài liệu. Các hệ thống hiện tại dựa vào văn bản đã phân tích, mất đi tín hiệu trực quan như bố cục và biểu đồ, chỉ cung cấp trích dẫn văn bản mơ hồ, buộc người dùng phải tìm bằng chứng thủ công.

**Tags**: `#retrieval-augmented generation`, `#visual attribution`, `#vision-language model`, `#document understanding`, `#pdf analysis`

---