# 🎨 Tài liệu tài nguyên thiết kế — LinkJob

Tài liệu này tổng hợp các công cụ thiết kế, nguồn tham khảo và quy ước quản lý tài nguyên thiết kế được sử dụng trong quá trình phát triển dự án **LinkJob**.

## 📌 1. Công cụ thiết kế

| Công cụ | Mục đích sử dụng | Liên kết |
|---|---|---|
| Figma | Thiết kế giao diện UI/UX và tạo bản mẫu tương tác | [Figma](https://www.figma.com/design/4iheA8qAOf3AygiP4Ysd2j/LinkJob?node-id=0-1&p=f&t=9prri4xQvHSUc1Sn-0) |
| Google Fonts | Tìm kiếm và sử dụng phông chữ | [Google Fonts](https://fonts.google.com/) |
| Unsplash | Trang web sử dụng hình ảnh miễn phí | [Unsplash](https://unsplash.com/) |

## 🖼️ 2. Tài nguyên tham khảo

- **Logo:** Các nguồn tham khảo, ý tưởng và mẫu thiết kế logo cho LinkJob.
- **UI/UX:** Các tài liệu và giao diện tham khảo phục vụ quá trình thiết kế trải nghiệm người dùng.
- **Hình ảnh:** Các nguồn cung cấp hình ảnh được sử dụng trong dự án.
- **Biểu tượng và phông chữ:** Các thư viện hỗ trợ xây dựng giao diện nhất quán.

> Bổ sung đường dẫn cụ thể vào từng mục khi có nguồn tham khảo thực tế.

## 📝 3. Quy ước Git Commit

Sử dụng quy ước commit nhất quán để giúp lịch sử thay đổi của dự án dễ đọc và dễ quản lý.

| Trường hợp | Commit message |
|---|---|
| Thêm tài liệu chứa các liên kết công cụ thiết kế | `docs(design): add design resource links` |
| Cập nhật các liên kết trong tài liệu hiện có | `docs(design): update design resources` |
| Thêm tài liệu hướng dẫn thiết kế | `docs(design): add design documentation` |
| Thêm ảnh logo mới | `chore(assets): add new logos` |

### Ví dụ sử dụng

```bash
git add docs/
git commit -m "docs(design): add design resource links"
```

**Lưu ý:** Chỉ sử dụng nội dung commit phù hợp với những thay đổi thực tế. Nếu chỉ thêm ảnh logo, hãy sử dụng thông điệp commit tương ứng với việc bổ sung tài nguyên.

## ⚠️ 4. Lưu ý khi sử dụng tài nguyên

- Ghi lại nguồn của các tài nguyên bên ngoài khi cần thiết.
- Kiểm tra giấy phép sử dụng trước khi đưa logo, hình ảnh, biểu tượng hoặc phông chữ vào dự án.
- Ưu tiên các tài nguyên có nguồn gốc rõ ràng và được phép sử dụng.
- Cập nhật tài liệu khi bổ sung công cụ thiết kế hoặc nguồn tham khảo mới.
- Đặt các tài nguyên thực tế của ứng dụng trong thư mục phù hợp, chẳng hạn `source_of_common/logo/`, thay vì lưu trực tiếp tất cả trong thư mục tài liệu.

---

*Tài liệu phục vụ quá trình thiết kế và phát triển dự án LinkJob.*