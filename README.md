# Aethelgard - The Swift Blade

Bản web tĩnh thuần HTML/CSS/JS, không dùng React/Vite, không cần npm và không cần build.

## Chạy thử trên máy

Mở trực tiếp `index.html` bằng trình duyệt.

## Deploy Render đơn giản nhất

Chọn **New → Static Site** rồi cấu hình:

```txt
Build Command: bỏ trống
Publish Directory: .
```

Không dùng:

```txt
npm install
npm run build
npm start
```

## Cấu trúc chính

```txt
index.html
assets/styles.css
assets/main.js
downloads/Aethelgard-The-Swift-Blade.zip
bg/
clouds/
game/
logo/
```

File game nằm trong `downloads/Aethelgard-The-Swift-Blade.zip`, nút tải xuống đã trỏ trực tiếp tới file này.
