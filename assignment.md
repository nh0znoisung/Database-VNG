# Assigment

## Đề bài

Thiết kế schema cho chương trình chia sẻ ảnh, gần giống như Pinterest, chi tiết như sau:

`Người dùng chia sẻ hình ảnh bằng cách tạo ghim (pin) gồm thông tin tựa đề, mô tả, các hình kèm theo ghim.

Pin tạo ra phải gắng trên bảng (board) nào đó. Board có thể là công khai (public) hoặc riêng tư(private): các user khác không thấy được pin trong board. Tuy nhiên private board có thể mời user khác cùng cộng tác: tạo pin, trả lời bình luận, . . .

User có thể lưu pin của user khác vào board của mình.

User có thể bình luận (comment), thả tim (like) vào pin.

User có thể theo dõi (follow) nhiều user khác.
`

## Yêu cầu

- Phân tích yêu cầu, từ đó thiết kế các APIs, database schema.

- Mỗi API thiết kế các câu query (đã tuning) có thể có, vẽ workflow dùng planUML hoặc drawio

- Thiết kế sharding trên tầng ứng dụng.

- Viết tài liệu chi tiết database schema, các query, sharding.

### Tính năng yêu cầu

- Tạo tài khoản (username/password, email,...)
- Cho phép user tạo, xem pin, tạo board
- Cho user dùng lưu pin người khác
- Cho user dùng theo dõi người khác
- Cho user dùng bình luận, thả tim (like) vào pin

## Hướng dẫn

- Các tính năng yêu cầu gần giống như [Pinterest](https://www.pinterest.com) nên trải nghiệm trước khi thiết kế.
