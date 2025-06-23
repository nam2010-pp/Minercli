
# 💻 DUCO CLI Miner

Đào [Duino-Coin (DUCO)](https://duinocoin.com/) bằng Node.js **hoàn toàn không cần giao diện web**.

## ⚙️ Tính năng
- ✅ CLI miner (không web)
- 🧪 Kiểm tra SHA1 trước khi đào
- 🛠 Dùng được trên GitHub Actions, VPS, Termux

## 🚀 Sử dụng
```bash
npm install benchmark ini js-sha1 jshashes node-fetch promise-socket rusha sha1
node cli.js
```

## 📝 Cấu trúc
minercli/
├─ cli.js
├─ miner/
│  ├─ index.js
│  └─ testLib.js

## 📜 License
MIT – Free to use, fork, and share!
