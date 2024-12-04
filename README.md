# JSON server

## Khái niệm

**Json server** hiểu đơn giản là một server trả về các dữ liệu dưới dạng json. Dùng để fake API.

## Yêu cầu

⚙ Cài đặt trước nodejs vào máy tính, gõ npm -v để xem phiên bản.

⚙ Cài đặt Postman để thử tính năng thêm, sửa, xóa dữ liệu.

## Hướng dẫn cài đặt

⚙ Tạo tệp database - > Gõ npm init để khởi tạo file package.json (Chứa những thông tin các gói đã cài đặt, nếu có file package.json rồi thì thôi, nếu không cứ bấm enter)

⚙ Truy cập vào [link](https://www.npmjs.com/package/json-server) để cài json server. Sau đó chạy lệnh npm i json-server

⚙ Tạo 1 file database.json với nội dung mẫu theo mục **Usage**.

```
{
  "posts": [
    { "id": "1", "title": "a title", "views": 100 },
    { "id": "2", "title": "another title", "views": 200 }
  ],
  "comments": [
    { "id": "1", "text": "a comment about post 1", "postId": "1" },
    { "id": "2", "text": "another comment about post 1", "postId": "1" }
  ],
  "profile": {
    "name": "typicode"
  }
}
```

⚙ Thêm vào mục "scripts" trong package.json dòng lệnh: "start": "json-server --watch database.json",

⚙ Chạy lệnh npm start

<p align="start">
  <img src="https://github.com/user-attachments/assets/24b42c39-baac-4114-96c6-d057c17fa491" {height=200px}>
</p>




