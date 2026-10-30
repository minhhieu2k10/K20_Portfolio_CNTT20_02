# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Lộc Hoàng Minh Hiệu ]
- Mã sinh viên – Lớp: [ 2071020077 - CNTT 20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/minhhieu2k10/K20_Portfolio_CNTT20_02.git ]
- URL website: [ https://minhhieu2k10.github.io/K20_Portfolio_CNTT20_02/ ]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ trang web hiển thị giao diện HTML nhưng CSS không hoạt động ]
- Mong muốn và hiện tượng thực tế: [ mong muốn web hiển thị đúng bố cục, màu sắc trong CSS và kích thước. Thực tế chỉ hiện giao diện HTML không có phần CSS ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [đã kiểm tra giao diện trên trình duyệt, thấy chữ và menu hiển thị mặc định, ảnh quá lớn ]
- Tôi nghi nguyên nhân là: [ sai liên kết CSS ]
- Vì sao tôi nhận định như vậy: [ nội dung HTML và hình ảnh vẫn hiển thị nhưng màu sắc, font chữ và bố cục đều không được áp dụng như thiết kế ]
## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ github copilot ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Tôi có URL [https://minhhieu2k10.github.io/K20_Portfolio_CNTT20_02/], Tôi dự đoán [liên kết sai css]. Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu. Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công. ]

- Gợi ý chính của AI:

  [ sai liên kết đến file css. Sửa lại liên kết thành <link rel="stylesheet" href="css/style.css" /> ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [x] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ sửa lại liên kết đến file css ]
- Lý do, dựa trên dữ kiện nào: [ tôi kiểm tra lại liên kết đến file css và thấy sai thật, dựa trên liên kết trước khi nhờ AI kiểm tra ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ file index.html]
- Nội dung thay đổi hoặc cách xử lý khác: [ sửa đường dẫn đến file css trong index.html]
- Commit của bản sửa, nếu có: [ đã commit ]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ css không tải được ] | [css tải thành công]
| Giao diện/chức năng trên URL website | [ mất định dạng, ảnh quá to ] | [hiển thị đúng bố cục và màu sắc]

- Cách thử lại và kết quả thực tế: [ commit và tải lại trang, giao diện hiển thị bình thường ]  
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ kiểm tra trực tiếp giao diện web trước và sau khi sửa ]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [cần kiểm tra kỹ đường dẫn file CSS khi làm web và sử dụng devtools để tìm lỗi nhanh hơn]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
