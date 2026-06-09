---
layout: default
title: "Horizon Summary: 2026-06-09 (VI)"
date: 2026-06-09
lang: vi
---

> From 781 items, 1 important content pieces were selected

---

1. [Unstructured 0.22.32 khắc phục lỗi trích xuất văn bản từ overlay hình trong PDF](#item-1) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Unstructured 0.22.32 khắc phục lỗi trích xuất văn bản từ overlay hình trong PDF](https://github.com/Unstructured-IO/unstructured/releases/tag/0.22.32) ⭐️ 8.0/10

Unstructured-IO phát hành phiên bản 0.22.32, sửa lỗi trong chiến lược hi_res để khôi phục văn bản bên trong các overlay hình trong PDF. Bản sửa lỗi này cải thiện độ chính xác khi trích xuất văn bản từ các PDF phức tạp có hình ảnh chồng lên, rất quan trọng cho các pipeline xử lý tài liệu. Tại Việt Nam, nhiều doanh nghiệp sử dụng tài liệu PDF có hình ảnh nhúng, khiến bản cập nhật này trở nên hữu ích cho các giải pháp SaaS nội địa. Bản sửa lỗi tập trung vào chế độ xử lý hi_res (độ phân giải cao), sử dụng OCR và phát hiện bố cục. Người dùng nâng cấp từ phiên bản 0.22.31 sẽ tự động nhận được cải tiến này.

github · qued · Jun 8, 18:29

**Background**: Unstructured là thư viện mã nguồn mở để tiền xử lý tài liệu phi cấu trúc (PDF, hình ảnh, v.v.) thành dữ liệu có cấu trúc. Chiến lược hi_res kết hợp OCR với phân tích bố cục để trích xuất văn bản từ các layout phức tạp, nhưng trước đây không thể lấy được văn bản bên trong các overlay hình.

**Tags**: `#pdf`, `#ocr`, `#document-processing`, `#unstructured`, `#saas`

---