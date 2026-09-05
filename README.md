# Mineflayer Minecraft Bot

Bot Minecraft sử dụng Node.js và Mineflayer, có thể chạy trên Android bằng Termux.

## Yêu cầu
- Android
- Termux
- Internet
- Node.js
- Minecraft Server mà bạn được phép cho bot tham gia

## Cài Termux
Bạn có thể cài Termux từ:
- [F-Droid](https://f-droid.org/packages/com.termux/)
- [Google Play](https://play.google.com/store/apps/details?id=com.termux)

## Bước 1 — Cập nhật Termux
Mở Termux và chạy:

`pkg update && pkg upgrade`

Nếu hỏi `Do you want to continue? [Y/n]`, nhập `Y` rồi nhấn Enter.

## Bước 2 — Cài Node.js
Chạy:

`pkg install nodejs`

Kiểm tra:

`node -v`

`npm -v`

## Bước 3 — Cài curl
Chạy:

`pkg install curl`

## Bước 4 — Tạo thư mục bot
Chạy:

`mkdir minecraft-bot`

Sau đó:

`cd minecraft-bot`

## Bước 5 — Tải bot từ GitHub
Chạy:

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

Kiểm tra:

`ls`

Nếu thấy `index.js` thì đã tải thành công.

## Bước 6 — Setup Node.js
Chạy:

`npm init -y`

## Bước 7 — Cài thư viện
Chạy:

`npm install mineflayer mineflayer-pathfinder vec3 minecraft-data`

## Bước 8 — Cấu hình bot
Mở file:

`nano index.js`

Tìm phần cấu hình server trong `index.js` và nhập thông tin Minecraft Server của bạn.

Sau khi chỉnh sửa:
- `CTRL + O` để lưu
- Nhấn `Enter`
- `CTRL + X` để thoát

## Bước 9 — Chạy bot
Chạy:

`node index.js`

Bot sẽ bắt đầu kết nối tới Minecraft Server.

## Dừng bot
Nhấn:

`CTRL + C`

## Chạy lại bot
Chạy:

`node index.js`

## Cập nhật bot
Tải lại file `index.js` mới nhất:

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

Sau đó:

`npm install`

Rồi chạy:

`node index.js`

## Setup nhanh
Nếu Node.js đã được cài:

`mkdir minecraft-bot`

`cd minecraft-bot`

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

`npm init -y`

`npm install mineflayer mineflayer-pathfinder vec3 minecraft-data`

`node index.js`

## Lỗi thường gặp

### node: command not found
Chạy:

`pkg install nodejs`

### npm: command not found
Chạy:

`pkg install nodejs`

### curl: command not found
Chạy:

`pkg install curl`

### Cannot find module 'mineflayer'
Chạy:

`npm install mineflayer`

### Cannot find module 'mineflayer-pathfinder'
Chạy:

`npm install mineflayer-pathfinder`

### Cannot find module 'vec3'
Chạy:

`npm install vec3`

### Cannot find module 'minecraft-data'
Chạy:

`npm install minecraft-data`

### Bot không kết nối được
Kiểm tra:
- Địa chỉ server
- Port
- Phiên bản Minecraft
- Tên bot
- Server có đang online không
- Kết nối Internet
## Thư viện
- [Mineflayer](https://github.com/PrismarineJS/mineflayer)
- [Mineflayer Pathfinder](https://github.com/PrismarineJS/mineflayer-pathfinder)
- [Vec3](https://github.com/PrismarineJS/node-vec3)
- [Minecraft Data](https://github.com/PrismarineJS/minecraft-data)

## Nguồn
- [GitHub Repository](https://github.com/Moon50112344/Bot-Mineflayer-Minecraft)
- [index.js](https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js)
 <table align="center">
  <tr>
    <td>
      <a href="https://www.tiktok.com/@moon501_vn">
        <img src="https://cdn.simpleicons.org/tiktok" width="40" alt="TikTok">
      </a>
    </td>
    <td width="25"></td>
    <td>
      <a href="https://github.com/Moon50112344">
        <img src="https://cdn.simpleicons.org/github" width="40" alt="GitHub">
      </a>
    </td>
  </tr>
</table>
