![OKX banner](https://github.com/user-attachments/assets/6c52d2b3-c510-4ecb-ac07-254c1d3f9e30)

# Tool Auto OKX Racer NodeJS by kênh Telegram Lượm Airdrop Auto @autoairdropref

**Tool phát triển và chia sẻ miễn phí tại Lượm Airdrop Auto**

## 🛠️ Hướng dẫn cài đặt

> Yêu cầu đã cài đặt NodeJS

- Bước 1: Tải về phiên bản mới nhất của tool [tại đây ⬇️](https://github.com/donguyen82/OKX-Racer/archive/refs/heads/main.zip)
- Bước 2: Giải nén tool
- Bước 3: Tại thư mục tool vừa giải nén, chạy lệnh `npm install` để cài đặt các thư viện bổ trợ

## 💾 Cách thêm dữ liệu tài khoản

> Tool sử dụng `query_id` làm dữ liệu đầu vào cho mỗi tài khoản

> Tất cả dữ liệu mà bạn cần nhập đều nằm ở các file trong thư mục 📁 `src / data`

- [user.txt](user.txt) : chứa danh sách `query_id` của các tài khoản, mỗi dòng ứng với một tài khoản
- [proxy.txt](proxy.txt) : chứa danh sách proxy, proxy ở mỗi dòng sẽ ứng với tài khoản ở dòng đó trong file users.txt phía trên, để trống nếu không dùng proxy

> Định dạng proxy: http://user:pass@ip:port

> Lưu ý: Nếu nhận được thông báo đăng nhập thất bại, hãy lấy mới lại `query_id`

## >\_ Các lệnh và chức năng tương ứng

| Lệnh                | Chức năng                               |
| ------------------- | --------------------------------------- |
| `npm run okx`       | Dùng để chạy chơi game không dùng proxy |
| `npm run okx-proxy` | Dùng để chạy chơi game có dùng proxy    |

> Các lệnh trên chạy hoàn toàn độc lập với nhau

## 🕹️ Các tính năng có trong tool

- Đa luồng, tự động chạy khi đủ lượt (mặc định sẽ chạy khi còn thiếu 1 lượt để tối ưu, có thể tìm biến `numberX = 1` sửa lại theo ý thích)
- Tự động nhận diện proxy
- Tự động làm nhiệm vụ nếu có
- Chơi game dự đoán auto win 90%.
- Nâng cấp boost hàng loạt
- Tự động chuyển đổi định dạng query_id/user

## 🔄 Lịch sử cập nhật

> Phiên bản mới nhất: `v1.0.0`

<details>
<summary>v1.0.0 - 📅 21/08/2024</summary>
  
- Chia sẻ tool cho cộng đồng
- Bổ sung readme
</details>
