# Tra cứu KTV 4.0

Web tra cứu nhanh Ngân hàng câu hỏi KTV 4.0 (VNPT) — 3.785 câu, 19 phần thi.

- Ô tìm kiếm sticky trên đầu, hiển thị kết quả ngay khi gõ
- Tìm kiếm thông minh: không phân biệt dấu, không phân biệt hoa thường, lọc theo từng từ
- Highlight từ khóa trong câu hỏi và đáp án
- Static site, chạy trên GitHub Pages: https://hlutools.github.io/e-learning

## Cấu trúc

- `index.html` — giao diện + logic tìm kiếm
- `data/d1.js` … `data/d5.js` — dữ liệu câu hỏi (chia chunk để dễ deploy)

Nguồn dữ liệu: `ktv-4.0-knowledge_1.md`.
