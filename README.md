# TECOTEC OES — Brand Playbook v1.0

> Brand Voice & Identity Playbook cho **TECOTEC Quang Điện Tử** (Optronics Equipment & Solutions)

## Xem trực tuyến

Playbook được publish tại:

**https://mkt-tecotec.github.io/TECOTEC-OES-Brand-Playbook/**

## Cấu trúc

```
├── index.html          ← Playbook chính (single-page, 15 sections)
├── styles.css          ← Design system & tokens
├── main.js             ← Tương tác (scroll spy, swatch copy, filter...)
├── og-image.svg        ← Ảnh social share (1200×630)
├── .impeccable.md      ← Design context cho AI-assisted edits
├── README.md           ← File này
└── logos/              ← Tất cả biến thể logo
    ├── logo-TECOTEC-OES.svg
    ├── logo-TECOTEC-OES-black.svg
    ├── logo-TECOTEC-OES-white.svg
    ├── logo-TECOTEC-OES.png
    ├── logo-TECOTEC-OES.webp
    ├── logo-TECOTEC-OES.pdf
    └── logo-TECOTEC-OES.eps
```

## Nội dung Playbook

| # | Phần | Mô tả |
|---|------|--------|
| 01 | Giới thiệu & Mục đích | Đối tượng, phạm vi |
| 02 | Nền tảng thương hiệu | Định vị, tầm nhìn, sứ mệnh, giá trị |
| 03 | Nhận diện thị giác | Logo, bảng màu, typography, hình ảnh, icon |
| 04 | Cá tính thương hiệu | 5 đặc điểm tính cách OES |
| 05 | Giọng điệu & Ngôn ngữ | Ma trận tone, quy tắc ngôn ngữ |
| 06 | Bộ lọc nội dung | Checklist 6 câu hỏi trước khi xuất bản |
| 07 | Quy tắc viết | Thuật ngữ, cấu trúc, dấu câu |
| 08 | Viết kỹ thuật | Application note, product description |
| 09 | Khung Case Study | Cấu trúc 6 phần chuẩn |
| 10 | Giọng Proposal & RFP | Tone và template proposal |
| 11 | AI Content Guardrails | Quy tắc sử dụng AI cho nội dung |
| 12 | Hướng dẫn theo kênh | Website, LinkedIn, Email, Catalogue |
| 13 | Ma trận ứng phó | Response matrix L0–L3 |
| 14 | Nên & Không nên | Do's & Don'ts tổng hợp |
| 15 | Tham khảo nhanh | Quick reference card (in được) |

## Design System

### Màu chính
- **OES Orange:** `#FF9900` — CTA, accent
- **OES Navy:** `#114466` — Authority surfaces
- **TECOTEC Blue:** `#146EB4` — Links, secondary

### Typography
- **Display:** [Manrope](https://fonts.google.com/specimen/Manrope) (400–800)
- **Body:** [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3)
- **Code:** [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

### Tính năng tương tác
- Scroll spy navigation
- Click-to-copy hex color swatches
- Content filter checklist
- Mobile responsive sidebar
- CSS scroll-drive progress bar + JS fallback
- Scroll reveal animations (respects `prefers-reduced-motion`)
- Print-friendly quick reference

## Cập nhật nội dung

1. Chỉnh sửa `index.html` trực tiếp trên repo
2. Tìm section cần sửa theo `id` (VD: `id="brand-foundation"`)
3. Cập nhật nội dung trong `<div class="section__body">`
4. Commit & push — GitHub Pages tự động deploy

## License

Tài liệu nội bộ TECOTEC Group. Không phân phối ngoài tổ chức.
